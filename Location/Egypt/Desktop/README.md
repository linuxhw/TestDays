Linux in Egypt - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

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

Total: 313

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H61M-DS2                    | [2ef34839f4](https://linux-hardware.org/?probe=2ef34839f4) | Jan 06, 2025 |
| HP            | 3646h                       | [dccac4d763](https://linux-hardware.org/?probe=dccac4d763) | Dec 24, 2024 |
| HP            | 18E7                        | [d0b93f0461](https://linux-hardware.org/?probe=d0b93f0461) | Dec 21, 2024 |
| HP            | 18E7                        | [5a4b0dfd19](https://linux-hardware.org/?probe=5a4b0dfd19) | Dec 19, 2024 |
| Dell          | 0Y9655                      | [02dddf8f3b](https://linux-hardware.org/?probe=02dddf8f3b) | Dec 10, 2024 |
| Dell          | 0Y9655                      | [b5f13b6611](https://linux-hardware.org/?probe=b5f13b6611) | Dec 07, 2024 |
| HP            | 1850                        | [371b052cf9](https://linux-hardware.org/?probe=371b052cf9) | Nov 28, 2024 |
| HP            | 82B4                        | [6d6647f3e4](https://linux-hardware.org/?probe=6d6647f3e4) | Nov 27, 2024 |
| HP            | 82B4                        | [fbe90d8967](https://linux-hardware.org/?probe=fbe90d8967) | Nov 27, 2024 |
| HP            | 829D                        | [e50b3cd963](https://linux-hardware.org/?probe=e50b3cd963) | Nov 16, 2024 |
| HP            | 829D                        | [414970c712](https://linux-hardware.org/?probe=414970c712) | Nov 14, 2024 |
| HP            | 18E7                        | [e6421394f6](https://linux-hardware.org/?probe=e6421394f6) | Nov 13, 2024 |
| Lenovo        | 3176 NOK                    | [5e69593bff](https://linux-hardware.org/?probe=5e69593bff) | Nov 06, 2024 |
| Biostar       | A320MH PRO                  | [714325c3c9](https://linux-hardware.org/?probe=714325c3c9) | Oct 20, 2024 |
| Dell          | 06D7TR A00                  | [489410fb9f](https://linux-hardware.org/?probe=489410fb9f) | Oct 03, 2024 |
| HP            | 158A                        | [6d925337a1](https://linux-hardware.org/?probe=6d925337a1) | Sep 20, 2024 |
| Gigabyte      | H61M-S2PT                   | [addda32455](https://linux-hardware.org/?probe=addda32455) | Sep 10, 2024 |
| HP            | 1850                        | [29a0446b30](https://linux-hardware.org/?probe=29a0446b30) | Sep 04, 2024 |
| HP            | 18E4                        | [c35e92df21](https://linux-hardware.org/?probe=c35e92df21) | Sep 03, 2024 |
| HP            | 1850                        | [497427a54f](https://linux-hardware.org/?probe=497427a54f) | Aug 31, 2024 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [5c65c772a0](https://linux-hardware.org/?probe=5c65c772a0) | Aug 23, 2024 |
| Gigabyte      | G41MT-S2PT                  | [18c286a7b5](https://linux-hardware.org/?probe=18c286a7b5) | Aug 18, 2024 |
| Gigabyte      | G41MT-S2PT                  | [52ae72249a](https://linux-hardware.org/?probe=52ae72249a) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | [b81443c816](https://linux-hardware.org/?probe=b81443c816) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | [c6be5f6727](https://linux-hardware.org/?probe=c6be5f6727) | Aug 17, 2024 |
| HP            | 1850                        | [d54e50f3b1](https://linux-hardware.org/?probe=d54e50f3b1) | Aug 14, 2024 |
| Gigabyte      | H67MA-D2H-B3                | [dcd172f513](https://linux-hardware.org/?probe=dcd172f513) | Aug 01, 2024 |
| HP            | 158B                        | [8968fc3701](https://linux-hardware.org/?probe=8968fc3701) | Jul 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [15d7334bb1](https://linux-hardware.org/?probe=15d7334bb1) | Jul 20, 2024 |
| HP            | 1850                        | [41ee740278](https://linux-hardware.org/?probe=41ee740278) | Jul 20, 2024 |
| HP            | 158B                        | [fd2a4a4a87](https://linux-hardware.org/?probe=fd2a4a4a87) | Jul 13, 2024 |
| Lenovo        | 3098 NOK                    | [bebed79fcb](https://linux-hardware.org/?probe=bebed79fcb) | Jul 11, 2024 |
| Gigabyte      | GA-MA69VM-S2                | [09efd74667](https://linux-hardware.org/?probe=09efd74667) | Jun 27, 2024 |
| Dell          | 0F5C5X A00                  | [8db1dee6a9](https://linux-hardware.org/?probe=8db1dee6a9) | Jun 13, 2024 |
| HP            | 802F                        | [d61162e434](https://linux-hardware.org/?probe=d61162e434) | Jun 05, 2024 |
| Gigabyte      | H61M-S2P                    | [157cc8b4cc](https://linux-hardware.org/?probe=157cc8b4cc) | May 04, 2024 |
| MSI           | MS-7309                     | [0683637148](https://linux-hardware.org/?probe=0683637148) | May 03, 2024 |
| HP            | 805A                        | [1c688de61d](https://linux-hardware.org/?probe=1c688de61d) | May 02, 2024 |
| HP            | 1632                        | [1a23bb9aba](https://linux-hardware.org/?probe=1a23bb9aba) | Apr 19, 2024 |
| HP            | 1632                        | [2d11bc974f](https://linux-hardware.org/?probe=2d11bc974f) | Apr 18, 2024 |
| Shenzhen M... | F7BFC                       | [4b0127a449](https://linux-hardware.org/?probe=4b0127a449) | Apr 04, 2024 |
| HP            | 8434 11                     | [a1a62e20a4](https://linux-hardware.org/?probe=a1a62e20a4) | Apr 03, 2024 |
| HP            | 1998                        | [4c2971ed76](https://linux-hardware.org/?probe=4c2971ed76) | Mar 27, 2024 |
| HP            | 1998                        | [d8865ee940](https://linux-hardware.org/?probe=d8865ee940) | Mar 24, 2024 |
| HP            | 1998                        | [de124e0aad](https://linux-hardware.org/?probe=de124e0aad) | Feb 29, 2024 |
| HP            | 1998                        | [6629121159](https://linux-hardware.org/?probe=6629121159) | Feb 24, 2024 |
| HP            | 1998                        | [c36364061e](https://linux-hardware.org/?probe=c36364061e) | Feb 24, 2024 |
| HP            | 2215                        | [eef0673d86](https://linux-hardware.org/?probe=eef0673d86) | Feb 21, 2024 |
| HP            | 2215                        | [3333f97016](https://linux-hardware.org/?probe=3333f97016) | Feb 21, 2024 |
| HP            | 2215                        | [d23162f59f](https://linux-hardware.org/?probe=d23162f59f) | Feb 20, 2024 |
| Acer          | Veriton X4110G              | [85c69e6034](https://linux-hardware.org/?probe=85c69e6034) | Feb 20, 2024 |
| HP            | 2215                        | [8fec3e792a](https://linux-hardware.org/?probe=8fec3e792a) | Feb 19, 2024 |
| HP            | 3047h                       | [05f8efc7c6](https://linux-hardware.org/?probe=05f8efc7c6) | Feb 15, 2024 |
| HP            | 1998                        | [de3c15346c](https://linux-hardware.org/?probe=de3c15346c) | Feb 10, 2024 |
| HP            | 1998                        | [5e85b19897](https://linux-hardware.org/?probe=5e85b19897) | Feb 05, 2024 |
| Dell          | 0G214D A00                  | [1a1b425da2](https://linux-hardware.org/?probe=1a1b425da2) | Feb 04, 2024 |
| HP            | 1998                        | [8ab7c171c3](https://linux-hardware.org/?probe=8ab7c171c3) | Jan 31, 2024 |
| HP            | 1998                        | [92ff4b3ecd](https://linux-hardware.org/?probe=92ff4b3ecd) | Jan 30, 2024 |
| HP            | 0B4Ch D                     | [fc77fc72a5](https://linux-hardware.org/?probe=fc77fc72a5) | Jan 29, 2024 |
| Dell          | 03NVJ6 A03                  | [2ad42e2ce5](https://linux-hardware.org/?probe=2ad42e2ce5) | Jan 29, 2024 |
| Dell          | 040DDP A01                  | [521a18e93d](https://linux-hardware.org/?probe=521a18e93d) | Jan 20, 2024 |
| MSI           | MAG B660M BAZOOKA DDR4      | [c2522bf7b3](https://linux-hardware.org/?probe=c2522bf7b3) | Jan 19, 2024 |
| Dell          | 040DDP A01                  | [c332d169ee](https://linux-hardware.org/?probe=c332d169ee) | Jan 18, 2024 |
| Gigabyte      | H61M-S2P                    | [b9dd6cbf20](https://linux-hardware.org/?probe=b9dd6cbf20) | Jan 15, 2024 |
| HP            | 3647h                       | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| Dell          | 06FW8P A01                  | [64eb36d553](https://linux-hardware.org/?probe=64eb36d553) | Jan 04, 2024 |
| Dell          | 06FW8P A01                  | [4a93269eb2](https://linux-hardware.org/?probe=4a93269eb2) | Jan 04, 2024 |
| Dell          | 03NVJ6 A03                  | [a87a530d24](https://linux-hardware.org/?probe=a87a530d24) | Dec 30, 2023 |
| Dell          | 02VCFF A00                  | [902c7a4466](https://linux-hardware.org/?probe=902c7a4466) | Dec 27, 2023 |
| Dell          | 03NVJ6 A03                  | [b6056625fc](https://linux-hardware.org/?probe=b6056625fc) | Dec 26, 2023 |
| HP            | 18E7                        | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f33ae0cc45](https://linux-hardware.org/?probe=f33ae0cc45) | Dec 14, 2023 |
| ASUSTek       | H61M-K                      | [15f1f8f029](https://linux-hardware.org/?probe=15f1f8f029) | Dec 13, 2023 |
| ASUSTek       | H61M-K                      | [d7a660dbef](https://linux-hardware.org/?probe=d7a660dbef) | Dec 13, 2023 |
| HP            | 1850                        | [903e4b5eb1](https://linux-hardware.org/?probe=903e4b5eb1) | Dec 11, 2023 |
| HP            | 3029h                       | [f7d6a9e2d4](https://linux-hardware.org/?probe=f7d6a9e2d4) | Dec 10, 2023 |
| HP            | 2215                        | [f29d88c563](https://linux-hardware.org/?probe=f29d88c563) | Dec 03, 2023 |
| ASUSTek       | PRIME X670-P                | [f7bf7a5dcc](https://linux-hardware.org/?probe=f7bf7a5dcc) | Dec 02, 2023 |
| ASUSTek       | PRIME H510M-K               | [cd95525dd4](https://linux-hardware.org/?probe=cd95525dd4) | Dec 01, 2023 |
| ASUSTek       | PRIME X670-P                | [2158fdddd7](https://linux-hardware.org/?probe=2158fdddd7) | Nov 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| Dell          | 0TY915                      | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| Dell          | 0WWJRX A00                  | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Gigabyte      | H510M S2H                   | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| HP            | 8061                        | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| HP            | 18E4                        | [6d3964fd1b](https://linux-hardware.org/?probe=6d3964fd1b) | Jul 05, 2023 |
| HP            | 18E4                        | [8a382f8911](https://linux-hardware.org/?probe=8a382f8911) | Jul 05, 2023 |
| HP            | 18E7                        | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [0f64e88f33](https://linux-hardware.org/?probe=0f64e88f33) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | GA-990FXA-D3                | [44f21e0f7e](https://linux-hardware.org/?probe=44f21e0f7e) | Jun 17, 2023 |
| Dell          | 0HMX8D A01                  | [e96dd04034](https://linux-hardware.org/?probe=e96dd04034) | Jun 15, 2023 |
| HP            | 1494                        | [7e431c0351](https://linux-hardware.org/?probe=7e431c0351) | Jun 08, 2023 |
| HP            | 1494                        | [0f032c101b](https://linux-hardware.org/?probe=0f032c101b) | Jun 07, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Pegatron      | 2A94h                       | [b17003f11e](https://linux-hardware.org/?probe=b17003f11e) | May 27, 2023 |
| Dell          | 0GY6Y8 A02                  | [6a031fd8a6](https://linux-hardware.org/?probe=6a031fd8a6) | May 13, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [25c4b5fe60](https://linux-hardware.org/?probe=25c4b5fe60) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [a2f3590a6a](https://linux-hardware.org/?probe=a2f3590a6a) | May 04, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [bf317c9241](https://linux-hardware.org/?probe=bf317c9241) | May 01, 2023 |
| Dell          | 0773VG A01                  | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [ed8414c493](https://linux-hardware.org/?probe=ed8414c493) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [695220be38](https://linux-hardware.org/?probe=695220be38) | Apr 24, 2023 |
| MSI           | B450 TOMAHAWK               | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Gigabyte      | G41MT-S2P                   | [abb09d2f8e](https://linux-hardware.org/?probe=abb09d2f8e) | Mar 17, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Gigabyte      | H87M-HD3                    | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| HP            | 2B34                        | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP            | 802F                        | [b36a46a944](https://linux-hardware.org/?probe=b36a46a944) | Feb 03, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [9a1bab8f2c](https://linux-hardware.org/?probe=9a1bab8f2c) | Jan 26, 2023 |
| Lenovo        | ThinkCentre M58 6258D3G     | [8bc1c22b23](https://linux-hardware.org/?probe=8bc1c22b23) | Jan 25, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [fc8a27e6c5](https://linux-hardware.org/?probe=fc8a27e6c5) | Jan 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| HP            | 3047h                       | [0dd7c7c08f](https://linux-hardware.org/?probe=0dd7c7c08f) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [cedf3a8ef8](https://linux-hardware.org/?probe=cedf3a8ef8) | Jan 07, 2023 |
| Gigabyte      | GA-990FXA-D3                | [30822e6e18](https://linux-hardware.org/?probe=30822e6e18) | Dec 22, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1613228bb2](https://linux-hardware.org/?probe=1613228bb2) | Dec 08, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [04a09baf04](https://linux-hardware.org/?probe=04a09baf04) | Dec 08, 2022 |
| ASUSTek       | P6T                         | [8268d853c9](https://linux-hardware.org/?probe=8268d853c9) | Dec 06, 2022 |
| HP            | 1850                        | [1d0a3a4461](https://linux-hardware.org/?probe=1d0a3a4461) | Nov 29, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| Acer          | Predator PO3-630            | [aae61f30c7](https://linux-hardware.org/?probe=aae61f30c7) | Oct 20, 2022 |
| HP            | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [6f0af51d33](https://linux-hardware.org/?probe=6f0af51d33) | Oct 06, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [843cabf6e6](https://linux-hardware.org/?probe=843cabf6e6) | Oct 06, 2022 |
| HP            | 1850                        | [f111f19884](https://linux-hardware.org/?probe=f111f19884) | Oct 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Gigabyte      | H510M S2H                   | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Gigabyte      | G31M-S2C                    | [91001df765](https://linux-hardware.org/?probe=91001df765) | Sep 04, 2022 |
| Gigabyte      | G31M-S2C                    | [9281a357e0](https://linux-hardware.org/?probe=9281a357e0) | Sep 04, 2022 |
| Gigabyte      | G31M-S2C                    | [ac5ecfc107](https://linux-hardware.org/?probe=ac5ecfc107) | Sep 04, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| HP            | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| HP            | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| HP            | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| HP            | 3647h                       | [ed98e07a47](https://linux-hardware.org/?probe=ed98e07a47) | Jul 26, 2022 |
| Dell          | 0200DY A01                  | [99eacb5700](https://linux-hardware.org/?probe=99eacb5700) | Jul 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| Dell          | 0GY6Y8 A03                  | [4668e3772e](https://linux-hardware.org/?probe=4668e3772e) | Jun 05, 2022 |
| Dell          | 040DDP A01                  | [208a2ee137](https://linux-hardware.org/?probe=208a2ee137) | Jun 02, 2022 |
| HP            | 0A80h                       | [7e5c6cf61e](https://linux-hardware.org/?probe=7e5c6cf61e) | May 27, 2022 |
| Dell          | 03NVJ6 A04                  | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Dell          | 08WKV3 A00                  | [e6ef37e2a0](https://linux-hardware.org/?probe=e6ef37e2a0) | Apr 24, 2022 |
| HP            | 8053                        | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| HP            | 18E7                        | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Dell          | 08WKV3 A00                  | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| Dell          | 0WK833                      | [efee7c0ec6](https://linux-hardware.org/?probe=efee7c0ec6) | Apr 02, 2022 |
| Dell          | 0WK833                      | [a8703c7598](https://linux-hardware.org/?probe=a8703c7598) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [2da8f96ad8](https://linux-hardware.org/?probe=2da8f96ad8) | Mar 29, 2022 |
| Gigabyte      | H110M-S2PT-CF               | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Intel         | DQ965MT AAD36265-505        | [93758c64fa](https://linux-hardware.org/?probe=93758c64fa) | Mar 07, 2022 |
| Dell          | 0XG309                      | [535c8e4e2e](https://linux-hardware.org/?probe=535c8e4e2e) | Feb 28, 2022 |
| Dell          | 0XG309                      | [d9f753df89](https://linux-hardware.org/?probe=d9f753df89) | Feb 28, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| HP            | 3397                        | [de499e61b9](https://linux-hardware.org/?probe=de499e61b9) | Feb 22, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2ddf4948c9](https://linux-hardware.org/?probe=2ddf4948c9) | Feb 19, 2022 |
| Gigabyte      | GA-MA78G-DS3H               | [d799c9b2f2](https://linux-hardware.org/?probe=d799c9b2f2) | Feb 18, 2022 |
| Dell          | 0C27VV A01                  | [5760b6c177](https://linux-hardware.org/?probe=5760b6c177) | Feb 14, 2022 |
| HP            | 3397                        | [06f2eef752](https://linux-hardware.org/?probe=06f2eef752) | Feb 13, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| Lenovo        | BRASWELL NOK                | [0b12f54345](https://linux-hardware.org/?probe=0b12f54345) | Dec 26, 2021 |
| HP            | 3047h                       | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Dell          | Precision WorkStation 49... | [b40b65db05](https://linux-hardware.org/?probe=b40b65db05) | Nov 07, 2021 |
| Dell          | 0CRH6C A01                  | [ff796824d2](https://linux-hardware.org/?probe=ff796824d2) | Oct 30, 2021 |
| HP            | 1850                        | [b155e888a5](https://linux-hardware.org/?probe=b155e888a5) | Oct 24, 2021 |
| Gigabyte      | G41MT-S2P                   | [e66a1ae149](https://linux-hardware.org/?probe=e66a1ae149) | Oct 21, 2021 |
| Gigabyte      | G41MT-S2P                   | [7339dc6e79](https://linux-hardware.org/?probe=7339dc6e79) | Oct 21, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Alienware     | 0P0JWX A00                  | [bc2b8a4fa5](https://linux-hardware.org/?probe=bc2b8a4fa5) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | [879496302d](https://linux-hardware.org/?probe=879496302d) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | [bbe7dc3f56](https://linux-hardware.org/?probe=bbe7dc3f56) | Oct 11, 2021 |
| Gigabyte      | H510M S2H                   | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6df5eb55f0](https://linux-hardware.org/?probe=6df5eb55f0) | Oct 03, 2021 |
| HP            | 1632                        | [269b4ad58e](https://linux-hardware.org/?probe=269b4ad58e) | Aug 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [26cae4bb7a](https://linux-hardware.org/?probe=26cae4bb7a) | Aug 16, 2021 |
| Intel         | DG31PR AAD97573-205         | [9bda168dc6](https://linux-hardware.org/?probe=9bda168dc6) | Aug 04, 2021 |
| Dell          | 0DR845                      | [1714388038](https://linux-hardware.org/?probe=1714388038) | Aug 03, 2021 |
| HP            | 3047h                       | [58b480757e](https://linux-hardware.org/?probe=58b480757e) | Jul 18, 2021 |
| HP            | 3047h                       | [40a25f223c](https://linux-hardware.org/?probe=40a25f223c) | Jul 18, 2021 |
| HP            | 0AE8h C                     | [b8b861a13d](https://linux-hardware.org/?probe=b8b861a13d) | Jul 13, 2021 |
| MSI           | MS-7507                     | [ede4b6fc34](https://linux-hardware.org/?probe=ede4b6fc34) | Jul 11, 2021 |
| HP            | 0A54h                       | [c8d8757784](https://linux-hardware.org/?probe=c8d8757784) | Jul 02, 2021 |
| Lenovo        | 0B98401 WIN                 | [c432c046f1](https://linux-hardware.org/?probe=c432c046f1) | Jun 04, 2021 |
| HP            | 158B                        | [cc2472f216](https://linux-hardware.org/?probe=cc2472f216) | Jun 03, 2021 |
| HP            | 83E1                        | [a10433a3cb](https://linux-hardware.org/?probe=a10433a3cb) | Jun 03, 2021 |
| Dell          | 09KPNV A01                  | [ace51e66cb](https://linux-hardware.org/?probe=ace51e66cb) | May 31, 2021 |
| HP            | 2129                        | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| Dell          | 09KPNV A01                  | [b902c359da](https://linux-hardware.org/?probe=b902c359da) | Apr 30, 2021 |
| Gigabyte      | H55M-S2V                    | [9170ec8194](https://linux-hardware.org/?probe=9170ec8194) | Apr 20, 2021 |
| HP            | 3397                        | [bb31fb43b4](https://linux-hardware.org/?probe=bb31fb43b4) | Apr 17, 2021 |
| Dell          | 09KPNV A01                  | [b7fe68e060](https://linux-hardware.org/?probe=b7fe68e060) | Apr 17, 2021 |
| HP            | 3397                        | [aa5cc70dda](https://linux-hardware.org/?probe=aa5cc70dda) | Apr 12, 2021 |
| Dell          | 0F5C5X A00                  | [7eda600c97](https://linux-hardware.org/?probe=7eda600c97) | Apr 05, 2021 |
| Dell          | 09KPNV A01                  | [10aaa9110b](https://linux-hardware.org/?probe=10aaa9110b) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | [280d47279c](https://linux-hardware.org/?probe=280d47279c) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | [a33947d95c](https://linux-hardware.org/?probe=a33947d95c) | Mar 23, 2021 |
| HP            | 2215                        | [baefda0ada](https://linux-hardware.org/?probe=baefda0ada) | Mar 22, 2021 |
| Dell          | 06D7TR A00                  | [d48c515893](https://linux-hardware.org/?probe=d48c515893) | Mar 20, 2021 |
| Gigabyte      | G41MT-S2P                   | [ca4e78877a](https://linux-hardware.org/?probe=ca4e78877a) | Mar 12, 2021 |
| Dell          | 09KPNV A01                  | [8f9a642417](https://linux-hardware.org/?probe=8f9a642417) | Feb 22, 2021 |
| HP            | 3397                        | [d20792e0ea](https://linux-hardware.org/?probe=d20792e0ea) | Feb 17, 2021 |
| Gigabyte      | H61M-S2P                    | [93bf0c5ca7](https://linux-hardware.org/?probe=93bf0c5ca7) | Feb 16, 2021 |
| Dell          | 09KPNV A01                  | [80ffaa3d5b](https://linux-hardware.org/?probe=80ffaa3d5b) | Feb 07, 2021 |
| Dell          | 09KPNV A01                  | [ed032a4225](https://linux-hardware.org/?probe=ed032a4225) | Feb 07, 2021 |
| Gigabyte      | G41MT-S2PT                  | [835511d4d7](https://linux-hardware.org/?probe=835511d4d7) | Jan 21, 2021 |
| HP            | 18E7                        | [627983aa9a](https://linux-hardware.org/?probe=627983aa9a) | Jan 08, 2021 |
| HP            | 18E7                        | [84402293e1](https://linux-hardware.org/?probe=84402293e1) | Jan 08, 2021 |
| Acer          | Veriton ES2735G V:2.0       | [c7f3ccb243](https://linux-hardware.org/?probe=c7f3ccb243) | Jan 03, 2021 |
| Gigabyte      | G41MT-S2PT                  | [91e7e7c14e](https://linux-hardware.org/?probe=91e7e7c14e) | Dec 27, 2020 |
| Gigabyte      | G41MT-S2PT                  | [3f73a22244](https://linux-hardware.org/?probe=3f73a22244) | Dec 27, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ed8e771bf5](https://linux-hardware.org/?probe=ed8e771bf5) | Dec 15, 2020 |
| Dell          | 0WWJRX A00                  | [79bddf0f48](https://linux-hardware.org/?probe=79bddf0f48) | Nov 17, 2020 |
| MSI           | B450 TOMAHAWK               | [59b28e7f27](https://linux-hardware.org/?probe=59b28e7f27) | Oct 29, 2020 |
| MSI           | B450 TOMAHAWK               | [812301310e](https://linux-hardware.org/?probe=812301310e) | Oct 29, 2020 |
| Gigabyte      | G41MT-S2PT                  | [183944533e](https://linux-hardware.org/?probe=183944533e) | Oct 19, 2020 |
| HP            | 304Ah                       | [a304d64545](https://linux-hardware.org/?probe=a304d64545) | Oct 14, 2020 |
| HP            | 304Ah                       | [539e24cc37](https://linux-hardware.org/?probe=539e24cc37) | Oct 13, 2020 |
| ASUSTek       | P6T                         | [3dd96c341e](https://linux-hardware.org/?probe=3dd96c341e) | Oct 08, 2020 |
| HP            | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Gigabyte      | G41MT-S2PT                  | [cfddb029a9](https://linux-hardware.org/?probe=cfddb029a9) | Oct 01, 2020 |
| Gigabyte      | P61-DS3-B3                  | [3e2d37b04f](https://linux-hardware.org/?probe=3e2d37b04f) | Sep 30, 2020 |
| Gigabyte      | P61-DS3-B3                  | [a8eb27996e](https://linux-hardware.org/?probe=a8eb27996e) | Sep 30, 2020 |
| HP            | 304Ah                       | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| HP            | 2215                        | [4251c60f57](https://linux-hardware.org/?probe=4251c60f57) | Sep 28, 2020 |
| Dell          | 0C27VV A00                  | [63ac37dbe0](https://linux-hardware.org/?probe=63ac37dbe0) | Sep 09, 2020 |
| HP            | 1850                        | [b4067f01b9](https://linux-hardware.org/?probe=b4067f01b9) | Aug 28, 2020 |
| HP            | 0AA8h                       | [1d5b0d8069](https://linux-hardware.org/?probe=1d5b0d8069) | Aug 18, 2020 |
| Gigabyte      | G41MT-S2PT                  | [2c424580ec](https://linux-hardware.org/?probe=2c424580ec) | Aug 15, 2020 |
| Gigabyte      | G41MT-S2PT                  | [8b2bb78e5e](https://linux-hardware.org/?probe=8b2bb78e5e) | Aug 15, 2020 |
| Gigabyte      | H55M-S2V                    | [07f217e703](https://linux-hardware.org/?probe=07f217e703) | Aug 03, 2020 |
| Gigabyte      | H55M-S2V                    | [ed1664a437](https://linux-hardware.org/?probe=ed1664a437) | Aug 03, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | [0aea737b4e](https://linux-hardware.org/?probe=0aea737b4e) | Jul 14, 2020 |
| ECS           | G41T-M6                     | [c053fd66c4](https://linux-hardware.org/?probe=c053fd66c4) | Jun 20, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [c0a0033c02](https://linux-hardware.org/?probe=c0a0033c02) | Jun 19, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [1785e9c758](https://linux-hardware.org/?probe=1785e9c758) | Jun 09, 2020 |
| HP            | 0AA8h                       | [7bc753da45](https://linux-hardware.org/?probe=7bc753da45) | Jun 01, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [cad337153c](https://linux-hardware.org/?probe=cad337153c) | May 30, 2020 |
| HP            | 0A64h                       | [2bd2c492f2](https://linux-hardware.org/?probe=2bd2c492f2) | May 19, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [143dc371cc](https://linux-hardware.org/?probe=143dc371cc) | May 13, 2020 |
| Dell          | 0F5C5X A00                  | [7249cfd353](https://linux-hardware.org/?probe=7249cfd353) | May 11, 2020 |
| Dell          | 0M863N A01                  | [9d837a84d6](https://linux-hardware.org/?probe=9d837a84d6) | May 06, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [3cc9bc0ca6](https://linux-hardware.org/?probe=3cc9bc0ca6) | May 02, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [ca61693f79](https://linux-hardware.org/?probe=ca61693f79) | May 02, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [aa0e93d8ea](https://linux-hardware.org/?probe=aa0e93d8ea) | May 01, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [ec80a4e6c4](https://linux-hardware.org/?probe=ec80a4e6c4) | May 01, 2020 |
| HP            | 0A64h                       | [33c495a402](https://linux-hardware.org/?probe=33c495a402) | Apr 29, 2020 |
| HP            | 0A64h                       | [fa43db5ed0](https://linux-hardware.org/?probe=fa43db5ed0) | Apr 29, 2020 |
| HP            | 3029h                       | [79951d69d3](https://linux-hardware.org/?probe=79951d69d3) | Apr 03, 2020 |
| HP            | 0B54h D                     | [90835f49e4](https://linux-hardware.org/?probe=90835f49e4) | Apr 01, 2020 |
| HP            | 0B54h D                     | [ccfbb22390](https://linux-hardware.org/?probe=ccfbb22390) | Apr 01, 2020 |
| HP            | 304Ah                       | [6b3da5e7b3](https://linux-hardware.org/?probe=6b3da5e7b3) | Mar 02, 2020 |
| ASUSTek       | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| Gigabyte      | G41MT-S2PT                  | [d9e2a26971](https://linux-hardware.org/?probe=d9e2a26971) | Feb 11, 2020 |
| Gigabyte      | G41MT-S2PT                  | [3b89d35524](https://linux-hardware.org/?probe=3b89d35524) | Feb 11, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | [ad3e13542c](https://linux-hardware.org/?probe=ad3e13542c) | Jan 15, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | [9658459b91](https://linux-hardware.org/?probe=9658459b91) | Jan 14, 2020 |
| IBM           | 81713FG                     | [53dead81c6](https://linux-hardware.org/?probe=53dead81c6) | Jan 03, 2020 |
| IBM           | 81713FG                     | [d8e454de5c](https://linux-hardware.org/?probe=d8e454de5c) | Jan 03, 2020 |
| ASUSTek       | H61M-K                      | [60762839f9](https://linux-hardware.org/?probe=60762839f9) | Nov 28, 2019 |
| ASUSTek       | H61M-K                      | [7ab32a09a5](https://linux-hardware.org/?probe=7ab32a09a5) | Nov 20, 2019 |
| Dell          | 0G214D A00                  | [9ed0af6e0a](https://linux-hardware.org/?probe=9ed0af6e0a) | Oct 11, 2019 |
| Gigabyte      | H61M-S2PT                   | [63cd905908](https://linux-hardware.org/?probe=63cd905908) | Oct 10, 2019 |
| HP            | 2820h                       | [11ccf345fc](https://linux-hardware.org/?probe=11ccf345fc) | Oct 06, 2019 |
| Gigabyte      | 8I848P-G                    | [dc8d0265cd](https://linux-hardware.org/?probe=dc8d0265cd) | Sep 29, 2019 |
| Gigabyte      | 8I848P-G                    | [ab92c43036](https://linux-hardware.org/?probe=ab92c43036) | Sep 28, 2019 |
| Dell          | 0G214D A00                  | [e8c153f59c](https://linux-hardware.org/?probe=e8c153f59c) | Sep 09, 2019 |
| Dell          | 0G214D A00                  | [16230f6527](https://linux-hardware.org/?probe=16230f6527) | Aug 10, 2019 |
| HP            | 0AA8h                       | [590f9d42ea](https://linux-hardware.org/?probe=590f9d42ea) | Aug 09, 2019 |
| HP            | 0AA8h                       | [822e83d86b](https://linux-hardware.org/?probe=822e83d86b) | Aug 09, 2019 |
| Dell          | 0RW199                      | [dfb1809733](https://linux-hardware.org/?probe=dfb1809733) | Aug 05, 2019 |
| HP            | 0AA8h                       | [e4137ad45b](https://linux-hardware.org/?probe=e4137ad45b) | Jul 31, 2019 |
| HP            | 0AA8h                       | [22921b3801](https://linux-hardware.org/?probe=22921b3801) | Jul 31, 2019 |
| Gigabyte      | H61M-S2PT                   | [0beb4b51ba](https://linux-hardware.org/?probe=0beb4b51ba) | Jul 12, 2019 |
| Gigabyte      | H61M-S2PT                   | [8a7237435e](https://linux-hardware.org/?probe=8a7237435e) | Jun 28, 2019 |
| Gigabyte      | G41MT-S2PT                  | [ada1dd6ed6](https://linux-hardware.org/?probe=ada1dd6ed6) | May 25, 2019 |
| HP            | 339A                        | [5b75c30305](https://linux-hardware.org/?probe=5b75c30305) | May 07, 2019 |
| HP            | 339A                        | [8d28878fde](https://linux-hardware.org/?probe=8d28878fde) | Apr 24, 2019 |
| Acer          | RS880M05                    | [17c0c75b39](https://linux-hardware.org/?probe=17c0c75b39) | Apr 23, 2019 |
| HP            | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Gigabyte      | Z97X-Gaming GT              | [7a92794877](https://linux-hardware.org/?probe=7a92794877) | Apr 01, 2019 |
| Gigabyte      | Z97X-Gaming GT              | [db8cfde0fc](https://linux-hardware.org/?probe=db8cfde0fc) | Feb 15, 2019 |
| Gigabyte      | Z97X-Gaming GT              | [2c4a8b9bfc](https://linux-hardware.org/?probe=2c4a8b9bfc) | Feb 14, 2019 |
| Gigabyte      | Z97X-Gaming GT              | [4bd60c5d00](https://linux-hardware.org/?probe=4bd60c5d00) | Feb 13, 2019 |
| Dell          | 0W0CHX A00                  | [84777ce1be](https://linux-hardware.org/?probe=84777ce1be) | Feb 05, 2019 |
| Gigabyte      | H61M-S2V-B3                 | [4ea628d244](https://linux-hardware.org/?probe=4ea628d244) | Nov 27, 2018 |
| MSI           | MS-7309                     | [dcfb685544](https://linux-hardware.org/?probe=dcfb685544) | Nov 16, 2018 |
| Gigabyte      | P31-DS3L                    | [5e5236f775](https://linux-hardware.org/?probe=5e5236f775) | May 31, 2018 |
| Gigabyte      | P31-DS3L                    | [cb1a0d9cdd](https://linux-hardware.org/?probe=cb1a0d9cdd) | Jan 30, 2018 |
| Gigabyte      | P31-DS3L                    | [a3bd2e39bb](https://linux-hardware.org/?probe=a3bd2e39bb) | Jan 05, 2018 |
| MSI           | MS-7309                     | [bfa74baa2d](https://linux-hardware.org/?probe=bfa74baa2d) | Oct 30, 2017 |
| Gigabyte      | GA-MA78G-DS3H               | [d033ac1daf](https://linux-hardware.org/?probe=d033ac1daf) | Jun 18, 2017 |
| Gigabyte      | GA-MA78G-DS3H               | [89a443e757](https://linux-hardware.org/?probe=89a443e757) | Jun 15, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 19       | 8.68%   |
| OpenMandriva 4.3   | 13       | 5.94%   |
| Zorin 16           | 11       | 5.02%   |
| Ubuntu 22.04       | 10       | 4.57%   |
| Ubuntu 18.04       | 10       | 4.57%   |
| Zorin 17           | 9        | 4.11%   |
| Arch Rolling       | 9        | 4.11%   |
| Fedora 39          | 8        | 3.65%   |
| OpenMandriva 4.2   | 7        | 3.2%    |
| OpenMandriva 23.01 | 7        | 3.2%    |
| ArcoLinux Rolling  | 7        | 3.2%    |
| ROSA R10           | 3        | 1.37%   |
| Linux Mint 20      | 3        | 1.37%   |
| BlackPanther 18.1  | 3        | 1.37%   |
| Ubuntu 24.04       | 2        | 0.91%   |
| Ubuntu 23.10       | 2        | 0.91%   |
| Ubuntu 21.10       | 2        | 0.91%   |
| Ubuntu 19.04       | 2        | 0.91%   |
| ROSA R9            | 2        | 0.91%   |
| ROSA R11           | 2        | 0.91%   |
| Pop!_OS 21.04      | 2        | 0.91%   |
| Pop!_OS 20.10      | 2        | 0.91%   |
| OpenMandriva 4.90  | 2        | 0.91%   |
| OpenMandriva 24.12 | 2        | 0.91%   |
| OpenMandriva 23.08 | 2        | 0.91%   |
| OpenMandriva 23.03 | 2        | 0.91%   |
| Manjaro            | 2        | 0.91%   |
| Linux Mint 21.1    | 2        | 0.91%   |
| Kali 2022.1        | 2        | 0.91%   |
| Fedora 35          | 2        | 0.91%   |
| Fedora 32          | 2        | 0.91%   |
| Fedora 30          | 2        | 0.91%   |
| Debian 12          | 2        | 0.91%   |
| Arch               | 2        | 0.91%   |
| Zorin 15           | 1        | 0.46%   |
| Xubuntu 24.04      | 1        | 0.46%   |
| Xubuntu 20.04      | 1        | 0.46%   |
| Xubuntu 18.04      | 1        | 0.46%   |
| Xubuntu 16.04      | 1        | 0.46%   |
| Ultramarine 37     | 1        | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 49       | 23.9%   |
| OpenMandriva | 33       | 16.1%   |
| Zorin        | 21       | 10.24%  |
| Fedora       | 18       | 8.78%   |
| Linux Mint   | 12       | 5.85%   |
| Arch         | 11       | 5.37%   |
| ArcoLinux    | 8        | 3.9%    |
| ROSA         | 7        | 3.41%   |
| Manjaro      | 6        | 2.93%   |
| Pop!_OS      | 5        | 2.44%   |
| Elementary   | 5        | 2.44%   |
| Debian       | 5        | 2.44%   |
| Xubuntu      | 4        | 1.95%   |
| KDE neon     | 3        | 1.46%   |
| Kali         | 3        | 1.46%   |
| BlackPanther | 3        | 1.46%   |
| Kubuntu      | 2        | 0.98%   |
| Ultramarine  | 1        | 0.49%   |
| Ultimate     | 1        | 0.49%   |
| Ubuntu Unity | 1        | 0.49%   |
| TUXEDO OS    | 1        | 0.49%   |
| RHEL         | 1        | 0.49%   |
| Reborn OS    | 1        | 0.49%   |
| Parrot       | 1        | 0.49%   |
| LMDE         | 1        | 0.49%   |
| Linux Lite   | 1        | 0.49%   |
| Endless      | 1        | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 11       | 4.64%   |
| 5.10.14-desktop-1omv4002       | 7        | 2.95%   |
| 6.1.1-desktop-1omv2290         | 6        | 2.53%   |
| 5.4.0-42-generic               | 4        | 1.69%   |
| 6.2.0-39-generic               | 3        | 1.27%   |
| 5.15.0-48-generic              | 3        | 1.27%   |
| 5.11.0-37-generic              | 3        | 1.27%   |
| 6.8.0-45-generic               | 2        | 0.84%   |
| 6.8.0-41-generic               | 2        | 0.84%   |
| 6.7.0-arch3-1                  | 2        | 0.84%   |
| 6.6.6-200.fc39.x86_64          | 2        | 0.84%   |
| 6.6.2-desktop-1omv2390         | 2        | 0.84%   |
| 6.6.2-201.fc39.x86_64          | 2        | 0.84%   |
| 6.5.0-28-generic               | 2        | 0.84%   |
| 6.5.0-27-generic               | 2        | 0.84%   |
| 6.5.0-18-generic               | 2        | 0.84%   |
| 6.5.0-14-generic               | 2        | 0.84%   |
| 6.4.12-arch1-1                 | 2        | 0.84%   |
| 6.2.6-desktop-1omv2390         | 2        | 0.84%   |
| 6.12.1-desktop-1omv2490        | 2        | 0.84%   |
| 5.9.1-arch1-1                  | 2        | 0.84%   |
| 5.4.0-48-generic               | 2        | 0.84%   |
| 5.4.0-37-generic               | 2        | 0.84%   |
| 5.4.0-33-generic               | 2        | 0.84%   |
| 5.4.0-26-generic               | 2        | 0.84%   |
| 5.3.0-51-generic               | 2        | 0.84%   |
| 5.19.0-45-generic              | 2        | 0.84%   |
| 5.18.12-desktop-3omv4090       | 2        | 0.84%   |
| 5.16.13-desktop-1omv4003       | 2        | 0.84%   |
| 5.15.0-69-generic              | 2        | 0.84%   |
| 5.15.0-56-generic              | 2        | 0.84%   |
| 5.15.0-50-generic              | 2        | 0.84%   |
| 5.13.0-39-generic              | 2        | 0.84%   |
| 5.13.0-30-generic              | 2        | 0.84%   |
| 5.13.0-19-generic              | 2        | 0.84%   |
| 5.11.0-7620-generic            | 2        | 0.84%   |
| 4.18.16-desktop-1bP            | 2        | 0.84%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 0.84%   |
| 4.15.0-55-generic              | 2        | 0.84%   |
| 4.15.0-46-generic              | 2        | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 9.78%   |
| 5.15.0  | 19       | 8.44%   |
| 6.5.0   | 11       | 4.89%   |
| 5.16.7  | 11       | 4.89%   |
| 4.15.0  | 10       | 4.44%   |
| 6.8.0   | 9        | 4%      |
| 5.13.0  | 9        | 4%      |
| 5.11.0  | 7        | 3.11%   |
| 5.10.14 | 7        | 3.11%   |
| 6.1.1   | 6        | 2.67%   |
| 5.3.0   | 5        | 2.22%   |
| 6.6.2   | 4        | 1.78%   |
| 5.19.0  | 4        | 1.78%   |
| 5.0.0   | 4        | 1.78%   |
| 6.2.0   | 3        | 1.33%   |
| 5.8.0   | 3        | 1.33%   |
| 6.9.10  | 2        | 0.89%   |
| 6.7.0   | 2        | 0.89%   |
| 6.6.6   | 2        | 0.89%   |
| 6.4.12  | 2        | 0.89%   |
| 6.3.9   | 2        | 0.89%   |
| 6.2.6   | 2        | 0.89%   |
| 6.12.1  | 2        | 0.89%   |
| 6.1.0   | 2        | 0.89%   |
| 5.9.1   | 2        | 0.89%   |
| 5.18.12 | 2        | 0.89%   |
| 5.16.13 | 2        | 0.89%   |
| 5.16.0  | 2        | 0.89%   |
| 5.10.0  | 2        | 0.89%   |
| 4.9.60  | 2        | 0.89%   |
| 4.19.0  | 2        | 0.89%   |
| 4.18.16 | 2        | 0.89%   |
| 4.18.0  | 2        | 0.89%   |
| 6.9.7   | 1        | 0.44%   |
| 6.9.1   | 1        | 0.44%   |
| 6.8.7   | 1        | 0.44%   |
| 6.7.3   | 1        | 0.44%   |
| 6.7.11  | 1        | 0.44%   |
| 6.6.5   | 1        | 0.44%   |
| 6.6.45  | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 10.86%  |
| 5.15    | 21       | 9.5%    |
| 5.16    | 18       | 8.14%   |
| 6.5     | 13       | 5.88%   |
| 5.10    | 13       | 5.88%   |
| 6.1     | 12       | 5.43%   |
| 6.8     | 10       | 4.52%   |
| 5.13    | 10       | 4.52%   |
| 4.15    | 10       | 4.52%   |
| 6.6     | 9        | 4.07%   |
| 5.11    | 8        | 3.62%   |
| 6.2     | 6        | 2.71%   |
| 5.3     | 6        | 2.71%   |
| 5.19    | 6        | 2.71%   |
| 4.9     | 5        | 2.26%   |
| 6.9     | 4        | 1.81%   |
| 6.7     | 4        | 1.81%   |
| 6.4     | 4        | 1.81%   |
| 5.8     | 4        | 1.81%   |
| 5.0     | 4        | 1.81%   |
| 4.18    | 4        | 1.81%   |
| 6.11    | 3        | 1.36%   |
| 6.10    | 3        | 1.36%   |
| 5.9     | 3        | 1.36%   |
| 6.3     | 2        | 0.9%    |
| 6.12    | 2        | 0.9%    |
| 5.6     | 2        | 0.9%    |
| 5.18    | 2        | 0.9%    |
| 4.19    | 2        | 0.9%    |
| 6.0     | 1        | 0.45%   |
| 5.7     | 1        | 0.45%   |
| 5.5     | 1        | 0.45%   |
| 5.2     | 1        | 0.45%   |
| 5.17    | 1        | 0.45%   |
| 4.4     | 1        | 0.45%   |
| 4.13    | 1        | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 191      | 97.45%  |
| i686   | 5        | 2.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 89       | 43.2%   |
| KDE5            | 51       | 24.76%  |
| Unknown         | 19       | 9.22%   |
| XFCE            | 13       | 6.31%   |
| X-Cinnamon      | 9        | 4.37%   |
| Pantheon        | 4        | 1.94%   |
| KDE4            | 4        | 1.94%   |
| KDE6            | 3        | 1.46%   |
| i3              | 2        | 0.97%   |
| Cinnamon        | 2        | 0.97%   |
| Budgie          | 2        | 0.97%   |
| Unity           | 1        | 0.49%   |
| MATE            | 1        | 0.49%   |
| LXQt            | 1        | 0.49%   |
| LXDE            | 1        | 0.49%   |
| KDE             | 1        | 0.49%   |
| GNOME Flashback | 1        | 0.49%   |
| GNOME Classic   | 1        | 0.49%   |
| awesome         | 1        | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 145      | 71.08%  |
| Wayland | 48       | 23.53%  |
| Unknown | 7        | 3.43%   |
| Tty     | 4        | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 92       | 45.77%  |
| SDDM    | 50       | 24.88%  |
| GDM3    | 27       | 13.43%  |
| GDM     | 14       | 6.97%   |
| LightDM | 9        | 4.48%   |
| TDM     | 5        | 2.49%   |
| KDM     | 4        | 1.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 147      | 73.5%   |
| Unknown | 23       | 11.5%   |
| ar_EG   | 18       | 9%      |
| en_GB   | 6        | 3%      |
| C       | 6        | 3%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 142      | 72.45%  |
| EFI  | 54       | 27.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 136      | 65.7%   |
| Overlay | 29       | 14.01%  |
| Btrfs   | 17       | 8.21%   |
| Tmpfs   | 12       | 5.8%    |
| Unknown | 6        | 2.9%    |
| Xfs     | 4        | 1.93%   |
| Zfs     | 2        | 0.97%   |
| Ext2    | 1        | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 47.24%  |
| GPT     | 59       | 29.65%  |
| MBR     | 46       | 23.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 80.9%   |
| Yes       | 38       | 19.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 55.94%  |
| Yes       | 89       | 44.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Hewlett-Packard                      | 71       | 36.41%  |
| Gigabyte Technology                  | 42       | 21.54%  |
| Dell                                 | 37       | 18.97%  |
| ASUSTek Computer                     | 15       | 7.69%   |
| Lenovo                               | 8        | 4.1%    |
| MSI                                  | 7        | 3.59%   |
| Acer                                 | 4        | 2.05%   |
| Intel                                | 3        | 1.54%   |
| Alienware                            | 2        | 1.03%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.51%   |
| Pegatron                             | 1        | 0.51%   |
| IBM                                  | 1        | 0.51%   |
| ECS                                  | 1        | 0.51%   |
| Biostar                              | 1        | 0.51%   |
| ASRock                               | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Gigabyte G41MT-S2PT                        | 8        | 4.1%    |
| HP ProDesk 600 G1 TWR                      | 5        | 2.56%   |
| HP Compaq Pro 6305 SFF                     | 5        | 2.56%   |
| Gigabyte H61M-S2P                          | 5        | 2.56%   |
| Dell OptiPlex 780                          | 5        | 2.56%   |
| HP Compaq 6005 Pro SFF PC                  | 4        | 2.05%   |
| Dell OptiPlex 760                          | 4        | 2.05%   |
| Dell OptiPlex 7020                         | 4        | 2.05%   |
| MSI MS-7C02                                | 3        | 1.54%   |
| HP ProDesk 600 G1 SFF                      | 3        | 1.54%   |
| HP EliteDesk 800 G1 SFF                    | 3        | 1.54%   |
| HP EliteDesk 705 G1 SFF                    | 3        | 1.54%   |
| Dell OptiPlex 7010                         | 3        | 1.54%   |
| HP Z820 Workstation                        | 2        | 1.03%   |
| HP Z620 Workstation                        | 2        | 1.03%   |
| HP Z600 Workstation                        | 2        | 1.03%   |
| HP Z240 Tower Workstation                  | 2        | 1.03%   |
| HP rp5800                                  | 2        | 1.03%   |
| HP EliteDesk 800 G1 TWR                    | 2        | 1.03%   |
| HP Compaq Elite 8300 SFF                   | 2        | 1.03%   |
| HP Compaq dc7800                           | 2        | 1.03%   |
| HP Compaq dc5850 Small Form Factor         | 2        | 1.03%   |
| HP Compaq 8000 Elite CMT PC                | 2        | 1.03%   |
| Gigabyte H61M-S2V-B3                       | 2        | 1.03%   |
| Gigabyte H61M-S2PT                         | 2        | 1.03%   |
| Gigabyte H510M S2H                         | 2        | 1.03%   |
| Gigabyte G41MT-S2P                         | 2        | 1.03%   |
| Dell OptiPlex 990                          | 2        | 1.03%   |
| Dell OptiPlex 3020                         | 2        | 1.03%   |
| ASUS H61M-K                                | 2        | 1.03%   |
| ASUS B250 MINING EXPERT                    | 2        | 1.03%   |
| Alienware Aurora R12                       | 2        | 1.03%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.51%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.51%   |
| MSI MS-7D43                                | 1        | 0.51%   |
| MSI MS-7C84                                | 1        | 0.51%   |
| MSI MS-7507                                | 1        | 0.51%   |
| MSI MS-7309                                | 1        | 0.51%   |
| Lenovo V530-15ICR 11BH001WAX               | 1        | 0.51%   |
| Lenovo ThinkStation S30 4351D32            | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 30       | 15.38%  |
| HP Compaq                                  | 27       | 13.85%  |
| HP EliteDesk                               | 14       | 7.18%   |
| HP ProDesk                                 | 11       | 5.64%   |
| Gigabyte G41MT-S2PT                        | 8        | 4.1%    |
| Dell Precision                             | 7        | 3.59%   |
| Lenovo ThinkCentre                         | 6        | 3.08%   |
| Gigabyte H61M-S2P                          | 5        | 2.56%   |
| ASUS TUF                                   | 4        | 2.05%   |
| MSI MS-7C02                                | 3        | 1.54%   |
| Acer Veriton                               | 3        | 1.54%   |
| HP Z820                                    | 2        | 1.03%   |
| HP Z620                                    | 2        | 1.03%   |
| HP Z600                                    | 2        | 1.03%   |
| HP Z240                                    | 2        | 1.03%   |
| HP rp5800                                  | 2        | 1.03%   |
| Gigabyte H61M-S2V-B3                       | 2        | 1.03%   |
| Gigabyte H61M-S2PT                         | 2        | 1.03%   |
| Gigabyte H510M                             | 2        | 1.03%   |
| Gigabyte G41MT-S2P                         | 2        | 1.03%   |
| ASUS ROG                                   | 2        | 1.03%   |
| ASUS PRIME                                 | 2        | 1.03%   |
| ASUS H61M-K                                | 2        | 1.03%   |
| ASUS B250                                  | 2        | 1.03%   |
| Alienware Aurora                           | 2        | 1.03%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.51%   |
| Pegatron Pro                               | 1        | 0.51%   |
| MSI MS-7D43                                | 1        | 0.51%   |
| MSI MS-7C84                                | 1        | 0.51%   |
| MSI MS-7507                                | 1        | 0.51%   |
| MSI MS-7309                                | 1        | 0.51%   |
| Lenovo V530-15ICR                          | 1        | 0.51%   |
| Lenovo ThinkStation                        | 1        | 0.51%   |
| Intel H61M-DS2                             | 1        | 0.51%   |
| Intel E4610                                | 1        | 0.51%   |
| Intel DG31PR                               | 1        | 0.51%   |
| IBM 81713FG                                | 1        | 0.51%   |
| HP Z840                                    | 1        | 0.51%   |
| HP Z400                                    | 1        | 0.51%   |
| HP Z230                                    | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 26       | 13.33%  |
| 2012 | 22       | 11.28%  |
| 2011 | 21       | 10.77%  |
| 2009 | 18       | 9.23%   |
| 2014 | 14       | 7.18%   |
| 2008 | 14       | 7.18%   |
| 2018 | 12       | 6.15%   |
| 2010 | 11       | 5.64%   |
| 2007 | 10       | 5.13%   |
| 2021 | 7        | 3.59%   |
| 2017 | 6        | 3.08%   |
| 2016 | 6        | 3.08%   |
| 2015 | 6        | 3.08%   |
| 2022 | 5        | 2.56%   |
| 2019 | 5        | 2.56%   |
| 2005 | 4        | 2.05%   |
| 2023 | 3        | 1.54%   |
| 2006 | 3        | 1.54%   |
| 2020 | 2        | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 195      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 193      | 98.97%  |
| Enabled  | 2        | 1.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 195      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 46       | 23.23%  |
| 3.01-4.0    | 42       | 21.21%  |
| 8.01-16.0   | 37       | 18.69%  |
| 16.01-24.0  | 33       | 16.67%  |
| 32.01-64.0  | 13       | 6.57%   |
| 1.01-2.0    | 9        | 4.55%   |
| 2.01-3.0    | 8        | 4.04%   |
| 24.01-32.0  | 4        | 2.02%   |
| 64.01-256.0 | 4        | 2.02%   |
| 0.51-1.0    | 1        | 0.51%   |
| 0.01-0.5    | 1        | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 73       | 34.11%  |
| 2.01-3.0    | 58       | 27.1%   |
| 4.01-8.0    | 26       | 12.15%  |
| 3.01-4.0    | 21       | 9.81%   |
| 0.51-1.0    | 17       | 7.94%   |
| 0.01-0.5    | 9        | 4.21%   |
| 8.01-16.0   | 8        | 3.74%   |
| 64.01-256.0 | 1        | 0.47%   |
| 16.01-24.0  | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 90       | 44.33%  |
| 2       | 74       | 36.45%  |
| 3       | 25       | 12.32%  |
| 4       | 7        | 3.45%   |
| 0       | 3        | 1.48%   |
| 9       | 2        | 0.99%   |
| 5       | 1        | 0.49%   |
| Unknown | 1        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 52.28%  |
| Yes       | 94       | 47.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 194      | 99.49%  |
| No        | 1        | 0.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 61.81%  |
| Yes       | 76       | 38.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 86.36%  |
| Yes       | 27       | 13.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Egypt   | 195      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Cairo                 | 108      | 51.18%  |
| Giza                  | 22       | 10.43%  |
| Alexandria            | 19       | 9%      |
| Al Mansurah           | 9        | 4.27%   |
| Tanta                 | 5        | 2.37%   |
| Zagazig               | 3        | 1.42%   |
| Port Said             | 3        | 1.42%   |
| Assiut                | 3        | 1.42%   |
| Suez                  | 2        | 0.95%   |
| Mohandessin           | 2        | 0.95%   |
| Minya                 | 2        | 0.95%   |
| Kafr ash Shaykh       | 2        | 0.95%   |
| Ismailia              | 2        | 0.95%   |
| Damietta              | 2        | 0.95%   |
| Aswan                 | 2        | 0.95%   |
| Al Ma`adi             | 2        | 0.95%   |
| Zefta                 | 1        | 0.47%   |
| Tukh                  | 1        | 0.47%   |
| Shubra al Khaymah     | 1        | 0.47%   |
| Sharqia               | 1        | 0.47%   |
| Sharm el Sheikh       | 1        | 0.47%   |
| Rosetta               | 1        | 0.47%   |
| Qina                  | 1        | 0.47%   |
| New Cairo             | 1        | 0.47%   |
| Mallawi               | 1        | 0.47%   |
| Madinat an Nasr       | 1        | 0.47%   |
| Luxor                 | 1        | 0.47%   |
| Ibshaway              | 1        | 0.47%   |
| Hurghada              | 1        | 0.47%   |
| Helwan                | 1        | 0.47%   |
| Gharbia               | 1        | 0.47%   |
| Faraskur              | 1        | 0.47%   |
| Faiyum                | 1        | 0.47%   |
| Dishna                | 1        | 0.47%   |
| Al Qalyubiyah         | 1        | 0.47%   |
| Al Qahirah al Jadidah | 1        | 0.47%   |
| Al Fayyum             | 1        | 0.47%   |
| Akhmim                | 1        | 0.47%   |
| 6th of October City   | 1        | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 107      | 166    | 35.2%   |
| Seagate                      | 77       | 109    | 25.33%  |
| Samsung Electronics          | 31       | 43     | 10.2%   |
| Kingston                     | 19       | 30     | 6.25%   |
| Toshiba                      | 10       | 12     | 3.29%   |
| Crucial                      | 9        | 13     | 2.96%   |
| Hitachi                      | 6        | 6      | 1.97%   |
| Sandisk                      | 4        | 4      | 1.32%   |
| LITEONIT                     | 3        | 3      | 0.99%   |
| LITEON                       | 3        | 6      | 0.99%   |
| KingSpec                     | 3        | 3      | 0.99%   |
| HS-SSD-C100                  | 3        | 3      | 0.99%   |
| Hewlett-Packard              | 3        | 3      | 0.99%   |
| Micron/Crucial Technology    | 2        | 2      | 0.66%   |
| Kingston Technology Company  | 2        | 3      | 0.66%   |
| JMicron Technology           | 2        | 2      | 0.66%   |
| Intel                        | 2        | 2      | 0.66%   |
| HS-SSD-E100                  | 2        | 2      | 0.66%   |
| Fujitsu                      | 2        | 3      | 0.66%   |
| ZOTAC                        | 1        | 1      | 0.33%   |
| TwinMOS                      | 1        | 1      | 0.33%   |
| Transcend                    | 1        | 1      | 0.33%   |
| SK hynix                     | 1        | 2      | 0.33%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.33%   |
| Phison Electronics           | 1        | 2      | 0.33%   |
| Micron Technology            | 1        | 1      | 0.33%   |
| Maxtor                       | 1        | 2      | 0.33%   |
| MAXIO Technology (Hangzhou)  | 1        | 2      | 0.33%   |
| Lite-On Technology           | 1        | 1      | 0.33%   |
| Lexar                        | 1        | 1      | 0.33%   |
| Hikvision                    | 1        | 1      | 0.33%   |
| Dahua                        | 1        | 1      | 0.33%   |
| Apple                        | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 13       | 3.8%    |
| Seagate ST3500312CS 500GB                           | 9        | 2.63%   |
| Seagate ST3500414CS 500GB                           | 7        | 2.05%   |
| Kingston SA400S37240G 240GB SSD                     | 6        | 1.75%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5        | 1.46%   |
| Toshiba DT01ACA050 500GB                            | 5        | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5        | 1.46%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 4        | 1.17%   |
| WDC WD5000AADS-00S9B0 500GB                         | 4        | 1.17%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 4        | 1.17%   |
| WDC WD1600AABS-00PRA0 160GB                         | 4        | 1.17%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 1.17%   |
| Seagate ST3500413AS 500GB                           | 4        | 1.17%   |
| Kingston SA400S37480G 480GB SSD                     | 4        | 1.17%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.17%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 3        | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 3        | 0.88%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 3        | 0.88%   |
| WDC WD2500AAKX-75U6AA0 250GB                        | 3        | 0.88%   |
| WDC WD2500AAKX-603CA0 250GB                         | 3        | 0.88%   |
| WDC WD1600AABS-00H4A0 160GB                         | 3        | 0.88%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 3        | 0.88%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 3        | 0.88%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 0.88%   |
| WDC WD10EARS-00Y5B1 1TB                             | 3        | 0.88%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.88%   |
| Seagate ST3320311CS 320GB                           | 3        | 0.88%   |
| Seagate ST3250318AS 250GB                           | 3        | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.88%   |
| Seagate ST1000DM003-1CH162 1TB                      | 3        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3        | 0.88%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.58%   |
| WDC WD800BD-22MRA1 80GB                             | 2        | 0.58%   |
| WDC WD7500AACS-00D6B1 752GB                         | 2        | 0.58%   |
| WDC WD5000LPVT-75G33T0 500GB                        | 2        | 0.58%   |
| WDC WD5000AVVS-63H0B1 500GB                         | 2        | 0.58%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 2        | 0.58%   |
| WDC WD5000AADS-56S9B1 500GB                         | 2        | 0.58%   |
| WDC WD3200AVVS-63L2B0 320GB                         | 2        | 0.58%   |
| WDC WD1600JS-61MHB1 160GB                           | 2        | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 160    | 48.82%  |
| Seagate             | 77       | 109    | 36.49%  |
| Toshiba             | 9        | 11     | 4.27%   |
| Samsung Electronics | 9        | 12     | 4.27%   |
| Hitachi             | 6        | 6      | 2.84%   |
| JMicron Technology  | 2        | 2      | 0.95%   |
| Fujitsu             | 2        | 3      | 0.95%   |
| Maxtor              | 1        | 2      | 0.47%   |
| Hewlett-Packard     | 1        | 1      | 0.47%   |
| Apple               | 1        | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 18       | 28     | 25%     |
| Samsung Electronics | 16       | 18     | 22.22%  |
| Crucial             | 9        | 13     | 12.5%   |
| WDC                 | 6        | 6      | 8.33%   |
| LITEONIT            | 3        | 3      | 4.17%   |
| LITEON              | 3        | 6      | 4.17%   |
| KingSpec            | 3        | 3      | 4.17%   |
| SanDisk             | 2        | 2      | 2.78%   |
| Intel               | 2        | 2      | 2.78%   |
| ZOTAC               | 1        | 1      | 1.39%   |
| TwinMOS             | 1        | 1      | 1.39%   |
| Transcend           | 1        | 1      | 1.39%   |
| Toshiba             | 1        | 1      | 1.39%   |
| Micron Technology   | 1        | 1      | 1.39%   |
| Lexar               | 1        | 1      | 1.39%   |
| HS-SSD-C100         | 1        | 1      | 1.39%   |
| Hikvision           | 1        | 1      | 1.39%   |
| Hewlett-Packard     | 1        | 1      | 1.39%   |
| Dahua               | 1        | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 177      | 307    | 66.79%  |
| SSD     | 64       | 91     | 24.15%  |
| NVMe    | 20       | 31     | 7.55%   |
| Unknown | 4        | 4      | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 184      | 397    | 88.46%  |
| NVMe | 20       | 31     | 9.62%   |
| SAS  | 4        | 5      | 1.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 159      | 301    | 70.04%  |
| 0.51-1.0   | 50       | 66     | 22.03%  |
| 1.01-2.0   | 14       | 20     | 6.17%   |
| 3.01-4.0   | 3        | 5      | 1.32%   |
| 4.01-10.0  | 1        | 6      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 21.7%   |
| 251-500        | 42       | 19.81%  |
| 501-1000       | 32       | 15.09%  |
| 51-100         | 25       | 11.79%  |
| 1-20           | 21       | 9.91%   |
| 21-50          | 18       | 8.49%   |
| 1001-2000      | 13       | 6.13%   |
| More than 3000 | 6        | 2.83%   |
| Unknown        | 5        | 2.36%   |
| 2001-3000      | 4        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 80       | 37.56%  |
| 101-250        | 34       | 15.96%  |
| 21-50          | 32       | 15.02%  |
| 251-500        | 24       | 11.27%  |
| 51-100         | 18       | 8.45%   |
| 501-1000       | 12       | 5.63%   |
| Unknown        | 5        | 2.35%   |
| 2001-3000      | 3        | 1.41%   |
| 1001-2000      | 3        | 1.41%   |
| More than 3000 | 2        | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB    | 4        | 6      | 6.56%   |
| Seagate ST3500312CS 500GB       | 3        | 6      | 4.92%   |
| WDC WD5000AVVS-63H0B1 500GB     | 2        | 2      | 3.28%   |
| WDC WD5000AVDS-63U7B1 500GB     | 2        | 2      | 3.28%   |
| WDC WD1600AABS-00H4A0 160GB     | 2        | 2      | 3.28%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 4      | 3.28%   |
| Seagate ST380815AS 80GB         | 2        | 2      | 3.28%   |
| Seagate ST3500413AS 500GB       | 2        | 3      | 3.28%   |
| WDC WD800JD-60LSA5 80GB         | 1        | 1      | 1.64%   |
| WDC WD800BD-22MRA1 80GB         | 1        | 1      | 1.64%   |
| WDC WD5000AAVS-22G9B1 500GB     | 1        | 1      | 1.64%   |
| WDC WD5000AAKX-75U6AA0 500GB    | 1        | 2      | 1.64%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 1      | 1.64%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 2      | 1.64%   |
| WDC WD5000AAKX-009FA0 500GB     | 1        | 1      | 1.64%   |
| WDC WD5000AAKS-00V6A0 500GB     | 1        | 1      | 1.64%   |
| WDC WD5000AADS-00S9B0 500GB     | 1        | 1      | 1.64%   |
| WDC WD5000AADS-00M2B0 500GB     | 1        | 1      | 1.64%   |
| WDC WD3200AAJS-56M0A0 320GB     | 1        | 1      | 1.64%   |
| WDC WD3200AAJS-56B4A0 320GB     | 1        | 2      | 1.64%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1        | 1      | 1.64%   |
| WDC WD3200AAJS-00B4A0 320GB     | 1        | 1      | 1.64%   |
| WDC WD3200A 320GB               | 1        | 1      | 1.64%   |
| WDC WD2500AAJS-00VTA0 250GB     | 1        | 1      | 1.64%   |
| WDC WD1600AVVS-63L2B0 160GB     | 1        | 1      | 1.64%   |
| WDC WD1600AAJS-00L7A0 160GB     | 1        | 1      | 1.64%   |
| WDC WD1600AABB-22PUA0 160GB     | 1        | 1      | 1.64%   |
| WDC WD10JPVX-60JC3T0 1TB        | 1        | 1      | 1.64%   |
| WDC WD10EZEX-75WN4A1 1TB        | 1        | 1      | 1.64%   |
| WDC WD10EZEX-08M2NA0 1TB        | 1        | 1      | 1.64%   |
| WDC WD10EZEX-00BN5A0 1TB        | 1        | 1      | 1.64%   |
| WDC WD10EARS-00Y5B1 1TB         | 1        | 1      | 1.64%   |
| Toshiba MQ01ABF050 500GB        | 1        | 2      | 1.64%   |
| Seagate ST500DM002-1SB10A 500GB | 1        | 1      | 1.64%   |
| Seagate ST3500412AS 500GB       | 1        | 1      | 1.64%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 1.64%   |
| Seagate ST3320311CS 320GB       | 1        | 1      | 1.64%   |
| Seagate ST3160812AS 160GB       | 1        | 1      | 1.64%   |
| Seagate ST3160211AS 160GB       | 1        | 3      | 1.64%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 2      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 39     | 54.55%  |
| Seagate             | 17       | 29     | 30.91%  |
| Samsung Electronics | 3        | 3      | 5.45%   |
| Toshiba             | 1        | 2      | 1.82%   |
| Kingston            | 1        | 2      | 1.82%   |
| Intel               | 1        | 1      | 1.82%   |
| Hewlett-Packard     | 1        | 1      | 1.82%   |
| Fujitsu             | 1        | 2      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 39     | 58.82%  |
| Seagate             | 17       | 29     | 33.33%  |
| Toshiba             | 1        | 2      | 1.96%   |
| Samsung Electronics | 1        | 1      | 1.96%   |
| Hewlett-Packard     | 1        | 1      | 1.96%   |
| Fujitsu             | 1        | 2      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 48       | 74     | 92.31%  |
| SSD  | 4        | 5      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB                      | 1        | 2      | 33.33%  |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 33.33%  |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 113      | 235    | 51.13%  |
| Works    | 54       | 115    | 24.43%  |
| Malfunc  | 51       | 79     | 23.08%  |
| Failed   | 3        | 4      | 1.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 148      | 66.37%  |
| AMD                          | 43       | 19.28%  |
| Samsung Electronics          | 9        | 4.04%   |
| Kingston Technology Company  | 4        | 1.79%   |
| Broadcom / LSI               | 3        | 1.35%   |
| SanDisk                      | 2        | 0.9%    |
| Micron/Crucial Technology    | 2        | 0.9%    |
| Marvell Technology Group     | 2        | 0.9%    |
| LSI Logic / Symbios Logic    | 2        | 0.9%    |
| SK hynix                     | 1        | 0.45%   |
| Shenzhen Longsys Electronics | 1        | 0.45%   |
| Phison Electronics           | 1        | 0.45%   |
| Nvidia                       | 1        | 0.45%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.45%   |
| Lite-On Technology           | 1        | 0.45%   |
| JMicron Technology           | 1        | 0.45%   |
| INNOGRIT                     | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 7.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 7.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 6%      |
| Intel SATA Controller [RAID mode]                                                       | 14       | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 3.33%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 10       | 3.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 7        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 1.67%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 1.33%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.33%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1%      |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1%      |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1%      |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1%      |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 3        | 1%      |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1%      |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1%      |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1%      |
| AMD SB600 Non-Raid-5 SATA                                                               | 3        | 1%      |
| AMD SB600 IDE                                                                           | 3        | 1%      |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1%      |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 123      | 51.04%  |
| IDE  | 72       | 29.88%  |
| NVMe | 20       | 8.3%    |
| RAID | 18       | 7.47%   |
| SAS  | 6        | 2.49%   |
| SCSI | 2        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 151      | 77.44%  |
| AMD    | 44       | 22.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 9        | 4.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz             | 7        | 3.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz             | 7        | 3.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 5        | 2.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 4        | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 4        | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 4        | 2.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 4        | 2.04%   |
| Intel Pentium D CPU 3.00GHz                  | 3        | 1.53%   |
| Intel Pentium CPU G2030 @ 3.00GHz            | 3        | 1.53%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 3        | 1.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 3        | 1.53%   |
| Intel Core i5-4670 CPU @ 3.40GHz             | 3        | 1.53%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz         | 3        | 1.53%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 3        | 1.53%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz         | 3        | 1.53%   |
| Intel Core 2 CPU 6600 @ 2.40GHz              | 3        | 1.53%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 3        | 1.53%   |
| AMD Ryzen 5 2600 Six-Core Processor          | 3        | 1.53%   |
| AMD A8-5500B APU with Radeon HD Graphics     | 3        | 1.53%   |
| AMD A4-5300B APU with Radeon HD Graphics     | 3        | 1.53%   |
| Intel Pentium 4 CPU 3.20GHz                  | 2        | 1.02%   |
| Intel Pentium 4 CPU 3.00GHz                  | 2        | 1.02%   |
| Intel Core i5-4590S CPU @ 3.00GHz            | 2        | 1.02%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 2        | 1.02%   |
| Intel Core i5-10505 CPU @ 3.20GHz            | 2        | 1.02%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 2        | 1.02%   |
| Intel Core i3-3220 CPU @ 3.30GHz             | 2        | 1.02%   |
| Intel Core i3-2100 CPU @ 3.10GHz             | 2        | 1.02%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz         | 2        | 1.02%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz         | 2        | 1.02%   |
| Intel Celeron D CPU 3.06GHz                  | 2        | 1.02%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2        | 1.02%   |
| AMD Phenom II X4 B95 Processor               | 2        | 1.02%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+   | 2        | 1.02%   |
| AMD A10 PRO-7800B R7, 12 Compute Cores 4C+8G | 2        | 1.02%   |
| Intel Xeon CPU X5680 @ 3.33GHz               | 1        | 0.51%   |
| Intel Xeon CPU X5650 @ 2.67GHz               | 1        | 0.51%   |
| Intel Xeon CPU W3550 @ 3.07GHz               | 1        | 0.51%   |
| Intel Xeon CPU L5640 @ 2.27GHz               | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 44       | 22.45%  |
| Intel Core 2 Duo        | 24       | 12.24%  |
| Intel Core i7           | 18       | 9.18%   |
| Intel Xeon              | 16       | 8.16%   |
| Intel Core i3           | 14       | 7.14%   |
| Other                   | 7        | 3.57%   |
| AMD Ryzen 5             | 7        | 3.57%   |
| Intel Pentium           | 5        | 2.55%   |
| Intel Core 2 Quad       | 5        | 2.55%   |
| Intel Core 2            | 5        | 2.55%   |
| AMD A4                  | 5        | 2.55%   |
| Intel Pentium 4         | 4        | 2.04%   |
| AMD Ryzen 7             | 4        | 2.04%   |
| AMD A8                  | 4        | 2.04%   |
| Intel Pentium D         | 3        | 1.53%   |
| Intel Celeron           | 3        | 1.53%   |
| AMD Ryzen 9             | 3        | 1.53%   |
| AMD Phenom II X4        | 3        | 1.53%   |
| Intel Pentium Dual-Core | 2        | 1.02%   |
| Intel Celeron D         | 2        | 1.02%   |
| AMD Phenom              | 2        | 1.02%   |
| AMD Athlon II X2        | 2        | 1.02%   |
| AMD Athlon 64 X2        | 2        | 1.02%   |
| AMD A6                  | 2        | 1.02%   |
| AMD A10                 | 2        | 1.02%   |
| AMD Sempron             | 1        | 0.51%   |
| AMD Ryzen 3             | 1        | 0.51%   |
| AMD PRO A8              | 1        | 0.51%   |
| AMD PRO A10             | 1        | 0.51%   |
| AMD FX                  | 1        | 0.51%   |
| AMD Athlon II X3        | 1        | 0.51%   |
| AMD Athlon Dual Core    | 1        | 0.51%   |
| AMD Athlon 64           | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 70       | 35.53%  |
| 2      | 69       | 35.03%  |
| 6      | 17       | 8.63%   |
| 1      | 16       | 8.12%   |
| 8      | 13       | 6.6%    |
| 12     | 4        | 2.03%   |
| 3      | 3        | 1.52%   |
| 24     | 2        | 1.02%   |
| 16     | 2        | 1.02%   |
| 10     | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 185      | 94.87%  |
| 2      | 10       | 5.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 57.07%  |
| 2      | 85       | 42.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 193      | 98.47%  |
| 32-bit         | 2        | 1.02%   |
| Unknown        | 1        | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 41.46%  |
| 0x1067a    | 17       | 8.29%   |
| 0x306c3    | 15       | 7.32%   |
| 0x306a9    | 8        | 3.9%    |
| 0x206a7    | 8        | 3.9%    |
| 0x6fb      | 5        | 2.44%   |
| 0x06001119 | 5        | 2.44%   |
| 0xf65      | 4        | 1.95%   |
| 0xa0671    | 3        | 1.46%   |
| 0x906ea    | 3        | 1.46%   |
| 0x6fd      | 3        | 1.46%   |
| 0x506e3    | 3        | 1.46%   |
| 0x206c2    | 3        | 1.46%   |
| 0x0800820d | 3        | 1.46%   |
| 0x010000c8 | 3        | 1.46%   |
| 0xf41      | 2        | 0.98%   |
| 0x906e9    | 2        | 0.98%   |
| 0x6f6      | 2        | 0.98%   |
| 0x306e4    | 2        | 0.98%   |
| 0x106a5    | 2        | 0.98%   |
| 0x10676    | 2        | 0.98%   |
| 0x01000095 | 2        | 0.98%   |
| 0xf64      | 1        | 0.49%   |
| 0xf43      | 1        | 0.49%   |
| 0x906ed    | 1        | 0.49%   |
| 0x6f2      | 1        | 0.49%   |
| 0x406c4    | 1        | 0.49%   |
| 0x306f2    | 1        | 0.49%   |
| 0x206d7    | 1        | 0.49%   |
| 0x20655    | 1        | 0.49%   |
| 0x20652    | 1        | 0.49%   |
| 0x106e5    | 1        | 0.49%   |
| 0x0a601206 | 1        | 0.49%   |
| 0x0a601203 | 1        | 0.49%   |
| 0x0a404102 | 1        | 0.49%   |
| 0x0a201009 | 1        | 0.49%   |
| 0x08701021 | 1        | 0.49%   |
| 0x08701013 | 1        | 0.49%   |
| 0x08701012 | 1        | 0.49%   |
| 0x08008204 | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 31       | 15.74%  |
| Penryn           | 23       | 11.68%  |
| SandyBridge      | 19       | 9.64%   |
| IvyBridge        | 14       | 7.11%   |
| Core             | 14       | 7.11%   |
| NetBurst         | 12       | 6.09%   |
| KabyLake         | 10       | 5.08%   |
| Piledriver       | 9        | 4.57%   |
| K10              | 9        | 4.57%   |
| Westmere         | 7        | 3.55%   |
| Skylake          | 7        | 3.55%   |
| Unknown          | 6        | 3.05%   |
| Zen+             | 5        | 2.54%   |
| Steamroller      | 5        | 2.54%   |
| Zen 2            | 4        | 2.03%   |
| K8 Hammer        | 4        | 2.03%   |
| CometLake        | 4        | 2.03%   |
| Nehalem          | 3        | 1.52%   |
| Icelake          | 3        | 1.52%   |
| Zen 3            | 2        | 1.02%   |
| Alderlake Hybrid | 2        | 1.02%   |
| Zen              | 1        | 0.51%   |
| Silvermont       | 1        | 0.51%   |
| Excavator        | 1        | 0.51%   |
| Bulldozer        | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 92       | 44.23%  |
| Nvidia | 58       | 27.88%  |
| AMD    | 58       | 27.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 25       | 11.68%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 7.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 4.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 4.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 3.27%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 2.34%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 2.34%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 2.34%   |
| Intel HD Graphics 530                                                       | 4        | 1.87%   |
| AMD RS880 [Radeon HD 4200]                                                  | 4        | 1.87%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.87%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.4%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.4%    |
| Nvidia GF119 [NVS 315]                                                      | 3        | 1.4%    |
| Nvidia GF108GL [Quadro 600]                                                 | 3        | 1.4%    |
| Intel HD Graphics 630                                                       | 3        | 1.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.4%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 1.4%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.4%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.4%    |
| AMD Trinity [Radeon HD 7560D]                                               | 3        | 1.4%    |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 3        | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.93%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.93%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 0.93%   |
| Nvidia AD104 [GeForce RTX 4070]                                             | 2        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.93%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.93%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 0.93%   |
| AMD RS780C [Radeon 3100]                                                    | 2        | 0.93%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 0.93%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 0.93%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.47%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.47%   |
| Nvidia NV18 [GeForce4 MX 4000]                                              | 1        | 0.47%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 0.47%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 80       | 40%     |
| 1 x Nvidia             | 53       | 26.5%   |
| 1 x AMD                | 50       | 25%     |
| Intel + Nvidia         | 4        | 2%      |
| Intel + AMD            | 4        | 2%      |
| 2 x Intel              | 2        | 1%      |
| 2 x AMD                | 2        | 1%      |
| AMD + Nvidia           | 2        | 1%      |
| 3 x AMD                | 1        | 0.5%    |
| 2 x Nvidia             | 1        | 0.5%    |
| 1 x Intel + 3 x Nvidia | 1        | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 156      | 77.23%  |
| Proprietary | 28       | 13.86%  |
| Unknown     | 18       | 8.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 117      | 57.92%  |
| 0.51-1.0   | 24       | 11.88%  |
| 0.01-0.5   | 21       | 10.4%   |
| 1.01-2.0   | 17       | 8.42%   |
| 7.01-8.0   | 10       | 4.95%   |
| 3.01-4.0   | 7        | 3.47%   |
| 8.01-16.0  | 5        | 2.48%   |
| 5.01-6.0   | 1        | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 37       | 23.87%  |
| Samsung Electronics     | 31       | 20%     |
| Hewlett-Packard         | 28       | 18.06%  |
| Lenovo                  | 9        | 5.81%   |
| Goldstar                | 8        | 5.16%   |
| Acer                    | 5        | 3.23%   |
| AOC                     | 4        | 2.58%   |
| Philips                 | 3        | 1.94%   |
| NEC Computers           | 3        | 1.94%   |
| Fujitsu Siemens         | 3        | 1.94%   |
| BenQ                    | 3        | 1.94%   |
| ASUSTek Computer        | 3        | 1.94%   |
| Eizo                    | 2        | 1.29%   |
| ViewSonic               | 1        | 0.65%   |
| Unknown                 | 1        | 0.65%   |
| Sun                     | 1        | 0.65%   |
| Sony                    | 1        | 0.65%   |
| RGT                     | 1        | 0.65%   |
| Planar                  | 1        | 0.65%   |
| MStar                   | 1        | 0.65%   |
| MLT                     | 1        | 0.65%   |
| JWY                     | 1        | 0.65%   |
| Iiyama                  | 1        | 0.65%   |
| HKC                     | 1        | 0.65%   |
| Gigabyte Technology     | 1        | 0.65%   |
| eMachines               | 1        | 0.65%   |
| Chi Mei Optoelectronics | 1        | 0.65%   |
| AUS                     | 1        | 0.65%   |
| Ancor Communications    | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 5        | 3.09%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 518x324mm 24.1-inch             | 4        | 2.47%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 3        | 1.85%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch          | 3        | 1.85%   |
| Hewlett-Packard E231 HWP3064 1920x1080 510x290mm 23.1-inch           | 3        | 1.85%   |
| Acer V193W ACR0025 1440x900 408x255mm 18.9-inch                      | 3        | 1.85%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 2        | 1.23%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch  | 2        | 1.23%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 2        | 1.23%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 480x270mm 21.7-inch         | 2        | 1.23%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch         | 2        | 1.23%   |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch          | 2        | 1.23%   |
| Dell P2213 DELF043 1680x1050 473x296mm 22.0-inch                     | 2        | 1.23%   |
| Dell P2211H DEL4060 1920x1080 477x268mm 21.5-inch                    | 2        | 1.23%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 1.23%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 1        | 0.62%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1        | 0.62%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                     | 1        | 0.62%   |
| Sony KDL-23S2000 SNY9900 1360x768                                    | 1        | 0.62%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch  | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.62%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 1        | 0.62%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 0.62%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.62%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 1        | 0.62%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch    | 1        | 0.62%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.62%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 0.62%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch     | 1        | 0.62%   |
| Samsung Electronics S19B300 SAM08A4 1366x768 410x230mm 18.5-inch     | 1        | 0.62%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch    | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SMBX2350 1920x1080                   | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 0.62%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                    | 1        | 0.62%   |
| Samsung Electronics LCD Monitor S22D300 5760x1080                    | 1        | 0.62%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                    | 1        | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 38.96%  |
| 1280x1024 (SXGA)   | 27       | 17.53%  |
| 1440x900 (WXGA+)   | 13       | 8.44%   |
| 1366x768 (WXGA)    | 12       | 7.79%   |
| 1680x1050 (WSXGA+) | 10       | 6.49%   |
| 1600x900 (HD+)     | 9        | 5.84%   |
| 2560x1440 (QHD)    | 5        | 3.25%   |
| 3840x2160 (4K)     | 4        | 2.6%    |
| 1920x540           | 2        | 1.3%    |
| 1920x1200 (WUXGA)  | 2        | 1.3%    |
| 1600x1200          | 2        | 1.3%    |
| 5760x1080          | 1        | 0.65%   |
| 3440x1440          | 1        | 0.65%   |
| 2560x1600          | 1        | 0.65%   |
| 1400x1050          | 1        | 0.65%   |
| 1360x768           | 1        | 0.65%   |
| 1280x720 (HD)      | 1        | 0.65%   |
| 1024x768 (XGA)     | 1        | 0.65%   |
| Unknown            | 1        | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 21       | 13.55%  |
| 24      | 18       | 11.61%  |
| 19      | 18       | 11.61%  |
| 23      | 16       | 10.32%  |
| 21      | 13       | 8.39%   |
| 18      | 13       | 8.39%   |
| 27      | 12       | 7.74%   |
| Unknown | 10       | 6.45%   |
| 22      | 9        | 5.81%   |
| 20      | 9        | 5.81%   |
| 15      | 4        | 2.58%   |
| 32      | 3        | 1.94%   |
| 31      | 2        | 1.29%   |
| 54      | 1        | 0.65%   |
| 46      | 1        | 0.65%   |
| 34      | 1        | 0.65%   |
| 29      | 1        | 0.65%   |
| 25      | 1        | 0.65%   |
| 16      | 1        | 0.65%   |
| 14      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 54       | 35.53%  |
| 501-600     | 42       | 27.63%  |
| 301-350     | 20       | 13.16%  |
| 351-400     | 14       | 9.21%   |
| Unknown     | 10       | 6.58%   |
| 601-700     | 5        | 3.29%   |
| 701-800     | 4        | 2.63%   |
| 1001-1500   | 2        | 1.32%   |
| 201-300     | 1        | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 52.98%  |
| 16/10   | 30       | 19.87%  |
| 5/4     | 24       | 15.89%  |
| Unknown | 9        | 5.96%   |
| 4/3     | 7        | 4.64%   |
| 21/9    | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 44       | 28.57%  |
| 151-200        | 34       | 22.08%  |
| 141-150        | 26       | 16.88%  |
| 301-350        | 12       | 7.79%   |
| Unknown        | 10       | 6.49%   |
| 251-300        | 9        | 5.84%   |
| 351-500        | 7        | 4.55%   |
| 131-140        | 4        | 2.6%    |
| 101-110        | 3        | 1.95%   |
| 111-120        | 2        | 1.3%    |
| More than 1000 | 1        | 0.65%   |
| 121-130        | 1        | 0.65%   |
| 501-1000       | 1        | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 108      | 73.97%  |
| 101-120 | 22       | 15.07%  |
| Unknown | 10       | 6.85%   |
| 1-50    | 3        | 2.05%   |
| 121-160 | 3        | 2.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 157      | 76.96%  |
| 0     | 30       | 14.71%  |
| 2     | 16       | 7.84%   |
| 3     | 1        | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 89       | 32.36%  |
| Realtek Semiconductor             | 78       | 28.36%  |
| Ralink Technology                 | 27       | 9.82%   |
| Broadcom                          | 23       | 8.36%   |
| Qualcomm Atheros                  | 20       | 7.27%   |
| Broadcom Limited                  | 11       | 4%      |
| TP-Link                           | 5        | 1.82%   |
| Qualcomm Atheros Communications   | 5        | 1.82%   |
| Samsung Electronics               | 2        | 0.73%   |
| Ralink                            | 2        | 0.73%   |
| Edimax Technology                 | 2        | 0.73%   |
| Xiaomi                            | 1        | 0.36%   |
| Sundance Technology Inc / IC Plus | 1        | 0.36%   |
| Qualcomm                          | 1        | 0.36%   |
| Nvidia                            | 1        | 0.36%   |
| Motorola                          | 1        | 0.36%   |
| Mercucys                          | 1        | 0.36%   |
| MediaTek                          | 1        | 0.36%   |
| Linux Foundation                  | 1        | 0.36%   |
| Lenovo                            | 1        | 0.36%   |
| D-Link                            | 1        | 0.36%   |
| 3Com                              | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 47       | 15.93%  |
| Intel Ethernet Connection I217-LM                                             | 21       | 7.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18       | 6.1%    |
| Ralink RT5370 Wireless Adapter                                                | 16       | 5.42%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 13       | 4.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 11       | 3.73%   |
| Ralink MT7601U Wireless Adapter                                               | 10       | 3.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 9        | 3.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 8        | 2.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 8        | 2.71%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 7        | 2.37%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 6        | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.69%   |
| Intel I211 Gigabit Network Connection                                         | 4        | 1.36%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 1.36%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 1.36%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 1.02%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.02%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 0.68%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2        | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 0.68%   |
| Intel Ethernet Controller I226-V                                              | 2        | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 0.68%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 0.68%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.68%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 0.68%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 27       | 33.33%  |
| Realtek Semiconductor           | 24       | 29.63%  |
| Intel                           | 9        | 11.11%  |
| TP-Link                         | 5        | 6.17%   |
| Qualcomm Atheros Communications | 5        | 6.17%   |
| Qualcomm Atheros                | 4        | 4.94%   |
| Ralink                          | 2        | 2.47%   |
| Edimax Technology               | 2        | 2.47%   |
| Mercucys                        | 1        | 1.23%   |
| MediaTek                        | 1        | 1.23%   |
| D-Link                          | 1        | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                                | 16       | 19.51%  |
| Ralink MT7601U Wireless Adapter                                               | 10       | 12.2%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 9        | 10.98%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 8        | 9.76%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 3.66%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 3.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 2.44%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 2.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 2.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 2.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.22%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 1.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.22%   |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 1.22%   |
| Realtek 802.11ac NIC                                                          | 1        | 1.22%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 1        | 1.22%   |
| Mercucys 802.11n NIC                                                          | 1        | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1        | 1.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.22%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.22%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.22%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 84       | 41.58%  |
| Realtek Semiconductor             | 60       | 29.7%   |
| Broadcom                          | 23       | 11.39%  |
| Qualcomm Atheros                  | 17       | 8.42%   |
| Broadcom Limited                  | 11       | 5.45%   |
| Xiaomi                            | 1        | 0.5%    |
| Sundance Technology Inc / IC Plus | 1        | 0.5%    |
| Samsung Electronics               | 1        | 0.5%    |
| Qualcomm                          | 1        | 0.5%    |
| Nvidia                            | 1        | 0.5%    |
| Lenovo                            | 1        | 0.5%    |
| 3Com                              | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 47       | 22.38%  |
| Intel Ethernet Connection I217-LM                                          | 21       | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18       | 8.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 13       | 6.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 11       | 5.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 8        | 3.81%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 7        | 3.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 6        | 2.86%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 2.38%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.9%    |
| Intel 82574L Gigabit Network Connection                                    | 4        | 1.9%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 1.43%   |
| Intel 82566DM Gigabit Network Connection                                   | 3        | 1.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 3        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 0.95%   |
| Intel Ethernet Controller I226-V                                           | 2        | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                                      | 2        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 0.95%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.95%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                         | 2        | 0.95%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.95%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express            | 2        | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.48%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.48%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 1        | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.48%   |
| Realtek Killer E2600 GbE Controller                                        | 1        | 0.48%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.48%   |
| Qualcomm Airtel 4G                                                         | 1        | 0.48%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.48%   |
| Lenovo Lenovo                                                              | 1        | 0.48%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.48%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 194      | 71.32%  |
| WiFi     | 75       | 27.57%  |
| Modem    | 3        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 155      | 76.73%  |
| WiFi     | 47       | 23.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 163      | 83.59%  |
| 2     | 28       | 14.36%  |
| 3     | 2        | 1.03%   |
| 0     | 2        | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 193      | 98.47%  |
| Yes  | 3        | 1.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 17       | 60.71%  |
| Intel                   | 9        | 32.14%  |
| Realtek Semiconductor   | 1        | 3.57%   |
| MediaTek                | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 60.71%  |
| Intel AX201 Bluetooth                               | 4        | 14.29%  |
| Realtek RTL8821A Bluetooth                          | 1        | 3.57%   |
| MediaTek Wireless_Device                            | 1        | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.57%   |
| Intel AX211 Bluetooth                               | 1        | 3.57%   |
| Intel AX210 Bluetooth                               | 1        | 3.57%   |
| Intel AX200 Bluetooth                               | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 149      | 53.6%   |
| AMD                    | 66       | 23.74%  |
| Nvidia                 | 48       | 17.27%  |
| C-Media Electronics    | 3        | 1.08%   |
| JMTek                  | 2        | 0.72%   |
| Generalplus Technology | 2        | 0.72%   |
| Thermaltake            | 1        | 0.36%   |
| Tenx Technology        | 1        | 0.36%   |
| Logitech               | 1        | 0.36%   |
| Kingston Technology    | 1        | 0.36%   |
| Hewlett-Packard        | 1        | 0.36%   |
| Conexant Systems       | 1        | 0.36%   |
| ASUSTek Computer       | 1        | 0.36%   |
| Astro Gaming           | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 28       | 8.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25       | 7.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 5.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16       | 4.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 4.22%   |
| AMD FCH Azalia Controller                                                  | 14       | 4.22%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 13       | 3.92%   |
| Nvidia High Definition Audio Controller                                    | 10       | 3.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 3.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 2.41%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 2.41%   |
| AMD Trinity HDMI Audio Controller                                          | 8        | 2.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 1.81%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5        | 1.51%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.51%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.51%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.2%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.9%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.9%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.6%    |
| Nvidia AD104 High Definition Audio Controller                              | 2        | 0.6%    |
| JMTek USB PnP Audio Device                                                 | 2        | 0.6%    |
| Intel HD Graphics SGPC                                                     | 2        | 0.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 28       | 19.18%  |
| Samsung Electronics          | 27       | 18.49%  |
| SK hynix                     | 21       | 14.38%  |
| Kingston                     | 20       | 13.7%   |
| Micron Technology            | 13       | 8.9%    |
| Crucial                      | 8        | 5.48%   |
| Corsair                      | 6        | 4.11%   |
| Ramaxel Technology           | 5        | 3.42%   |
| Nanya Technology             | 5        | 3.42%   |
| M                            | 3        | 2.05%   |
| MINPO                        | 2        | 1.37%   |
| Unknown (E)                  | 1        | 0.68%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.68%   |
| S                            | 1        | 0.68%   |
| Kingmax                      | 1        | 0.68%   |
| H                            | 1        | 0.68%   |
| G.Skill                      | 1        | 0.68%   |
| Elpida                       | 1        | 0.68%   |
| A-DATA Technology            | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s         | 8        | 4.79%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 4        | 2.4%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s    | 4        | 2.4%    |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 4        | 2.4%    |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 3        | 1.8%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 3        | 1.8%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 1.8%    |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.8%    |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 2        | 1.2%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 2        | 1.2%    |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 2        | 1.2%    |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 2        | 1.2%    |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s   | 2        | 1.2%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2        | 1.2%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s   | 2        | 1.2%    |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s    | 2        | 1.2%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 2        | 1.2%    |
| M RAM Module 2048MB DIMM DDR3 667MT/s                  | 2        | 1.2%    |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s     | 2        | 1.2%    |
| Crucial RAM CB16GU2666.C8ET 16GB DIMM DDR4 2667MT/s    | 2        | 1.2%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.6%    |
| Unknown RAM Module 8192MB DIMM 1066MT/s                | 1        | 0.6%    |
| Unknown RAM Module 512MB DIMM DDR 667MT/s              | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s              | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s            | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR2                    | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1066MT/s                | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2                       | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s            | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2                    | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 1        | 0.6%    |
| Unknown RAM Module 1GB DIMM SDRAM                      | 1        | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 49       | 44.55%  |
| DDR4    | 18       | 16.36%  |
| Unknown | 17       | 15.45%  |
| SDRAM   | 14       | 12.73%  |
| DDR2    | 9        | 8.18%   |
| DDR5    | 2        | 1.82%   |
| DDR     | 1        | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 98       | 98.99%  |
| SODIMM | 1        | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 44       | 35.2%   |
| 2048  | 34       | 27.2%   |
| 8192  | 25       | 20%     |
| 16384 | 9        | 7.2%    |
| 1024  | 9        | 7.2%    |
| 32768 | 2        | 1.6%    |
| 512   | 2        | 1.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 36       | 27.48%  |
| 1333    | 15       | 11.45%  |
| 667     | 10       | 7.63%   |
| 400     | 8        | 6.11%   |
| 800     | 7        | 5.34%   |
| 1867    | 6        | 4.58%   |
| 3600    | 5        | 3.82%   |
| 2133    | 5        | 3.82%   |
| 2667    | 4        | 3.05%   |
| 1866    | 4        | 3.05%   |
| 3467    | 3        | 2.29%   |
| 1648    | 3        | 2.29%   |
| 1066    | 3        | 2.29%   |
| Unknown | 3        | 2.29%   |
| 3200    | 2        | 1.53%   |
| 2400    | 2        | 1.53%   |
| 1800    | 2        | 1.53%   |
| 1331    | 2        | 1.53%   |
| 533     | 2        | 1.53%   |
| 49926   | 1        | 0.76%   |
| 5200    | 1        | 0.76%   |
| 4800    | 1        | 0.76%   |
| 3800    | 1        | 0.76%   |
| 3000    | 1        | 0.76%   |
| 2666    | 1        | 0.76%   |
| 2048    | 1        | 0.76%   |
| 2000    | 1        | 0.76%   |
| 1639    | 1        | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 4        | 44.44%  |
| Seiko Epson     | 2        | 22.22%  |
| Ricoh           | 1        | 11.11%  |
| Kyocera         | 1        | 11.11%  |
| Canon           | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seiko Epson Printer             | 1        | 11.11%  |
| Seiko Epson L3150 Series        | 1        | 11.11%  |
| Ricoh Printing Support          | 1        | 11.11%  |
| Kyocera UTAX_TA LP 3240_LP 4240 | 1        | 11.11%  |
| HP LaserJet P3005               | 1        | 11.11%  |
| HP LaserJet M402d               | 1        | 11.11%  |
| HP LaserJet 1018                | 1        | 11.11%  |
| HP DeskJet F2492 All-in-One     | 1        | 11.11%  |
| Canon LBP3010/LBP3018/LBP3050   | 1        | 11.11%  |

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
| Samsung Electronics     | 6        | 33.33%  |
| Logitech                | 2        | 11.11%  |
| Cubeternet              | 2        | 11.11%  |
| Z-Star Microelectronics | 1        | 5.56%   |
| vivo                    | 1        | 5.56%   |
| Realtek Semiconductor   | 1        | 5.56%   |
| OPPO Electronics        | 1        | 5.56%   |
| eMPIA Technology        | 1        | 5.56%   |
| Chicony Electronics     | 1        | 5.56%   |
| Aveo Technology         | 1        | 5.56%   |
| Apple                   | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 5        | 27.78%  |
| Logitech Webcam C270                    | 2        | 11.11%  |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 5.56%   |
| vivo 1904                               | 1        | 5.56%   |
| Samsung Galaxy (debugging mode)         | 1        | 5.56%   |
| Realtek Dell_Monitor_IR_Webcam          | 1        | 5.56%   |
| OPPO realme Phone                       | 1        | 5.56%   |
| eMPIA M035 Compact Web Cam              | 1        | 5.56%   |
| Cubeternet USB2.0 Camera                | 1        | 5.56%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 5.56%   |
| Chicony HP 720p HD Monitor Webcam       | 1        | 5.56%   |
| Aveo USB2.0 Camera                      | 1        | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1        | 5.56%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 1        | 50%     |
| Chicony Electronics | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon)        | 1        | 50%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 157      | 76.96%  |
| 1     | 36       | 17.65%  |
| 2     | 9        | 4.41%   |
| 5     | 2        | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 32       | 56.14%  |
| Net/wireless             | 9        | 15.79%  |
| Communication controller | 3        | 5.26%   |
| Camera                   | 3        | 5.26%   |
| Unassigned class         | 2        | 3.51%   |
| Sound                    | 2        | 3.51%   |
| Multimedia controller    | 2        | 3.51%   |
| Storage/ide              | 1        | 1.75%   |
| Modem                    | 1        | 1.75%   |
| Firewire controller      | 1        | 1.75%   |
| Bluetooth                | 1        | 1.75%   |

