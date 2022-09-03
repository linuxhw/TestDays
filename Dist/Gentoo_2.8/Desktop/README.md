Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 142

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock   | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock   | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo   | 3716 SDK0R32862 WIN 3258... | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Gigabyte | Z77X-D3H                    | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte | Z77X-D3H                    | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| ASUSTek  | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI      | Z590-A PRO                  | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| ASUSTek  | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte | B450 GAMING X               | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Gigabyte | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| MSI      | B450 TOMAHAWK               | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| MSI      | B450 GAMING PRO CARBON A... | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Unknown  | QNAP TS-221                 | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek  | PRIME Z390-A                | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASRock   | P67 Extreme4 Gen3           | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| ASUSTek  | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| ASUSTek  | TUF B450M-PLUS GAMING       | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| Gigabyte | B450 GAMING X               | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Gigabyte | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock   | B75M-GL R2.0                | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| ASUSTek  | ROG Maximus Z690 EXTREME    | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock   | B550M Steel Legend          | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| ASUSTek  | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte | 970A-DS3                    | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Lenovo   | 1046 SDK0T08861 WIN 3305... | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI      | B450M MORTAR                | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| Intel    | D54250WYK H13922-303        | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI      | MPG Z390 GAMING PRO CARB... | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| ASRock   | X399 Taichi                 | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek  | ROG Maximus XI HERO         | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek  | ROG Maximus Z690 EXTREME    | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| ASUSTek  | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock   | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Unknown  | QNAP TS-221                 | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock   | X570 Taichi                 | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI      | MEG X570 UNIFY              | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek  | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek  | ROG STRIX B560-I GAMING ... | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek  | ROG STRIX B560-I GAMING ... | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte | Z590 UD                     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| MSI      | Z87-G45 GAMING              | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Gigabyte | B450 AORUS M                | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Dell     | 0J3C2F A02                  | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek  | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell     | 0J3C2F A02                  | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek  | ROG Maximus XI HERO         | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte | Z690 AORUS MASTER           | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| ASUSTek  | PRIME Z390-A                | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| ASUSTek  | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu  | D3417-B2 S26361-D3417-B2    | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Gigabyte | Z590 UD                     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Gigabyte | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek  | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek  | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Pegatron | 2ACE                        | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell     | 0KWVT8 A03                  | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| Gigabyte | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Unknown  | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| Unknown  | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| MSI      | X570-A PRO                  | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| ASUSTek  | TUF Gaming Z690-PLUS WIF... | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| ASUSTek  | Z170-A                      | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| ASUSTek  | Z170-A                      | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| MSI      | PRO Z690-A DDR4             | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock   | B450 Gaming K4              | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| ASUSTek  | PRIME X570-PRO              | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek  | PRIME X570-PRO              | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| ASUSTek  | ROG Maximus XIII APEX       | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| Dell     | 0J3C2F A02                  | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Gigabyte | Z590 UD                     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| Dell     | 0J3C2F A02                  | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| ASRock   | X370 Gaming X               | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| MSI      | MPG Z390 GAMING PRO CARB... | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Dell     | 0J37VM A00                  | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI      | Z390-A PRO                  | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| ASUSTek  | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI      | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| ASUSTek  | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Gigabyte | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASUSTek  | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek  | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASRock   | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI      | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Gigabyte | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek  | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI      | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek  | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| Dell     | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| ASUSTek  | TUF Gaming X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Gigabyte | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASRock   | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| EVGA     | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Gigabyte | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.15.52-gentoo-x86_64     | 5        | 4.85%   |
| 5.15.41-gentoo            | 5        | 4.85%   |
| 5.15.52-gentoo            | 4        | 3.88%   |
| 5.17.1-gentoo-r1          | 3        | 2.91%   |
| 5.15.41-gentoo-x86_64     | 3        | 2.91%   |
| 5.19.0-gentoo             | 2        | 1.94%   |
| 5.18.14-gentoo-x86_64     | 2        | 1.94%   |
| 5.18.10-gentoo            | 2        | 1.94%   |
| 5.17.0-gentoo             | 2        | 1.94%   |
| 5.16.11-gentoo-x86_64     | 2        | 1.94%   |
| 5.15.59-gentoo            | 2        | 1.94%   |
| 5.15.52-gentoo-dist       | 2        | 1.94%   |
| 5.15.10-gentoo            | 2        | 1.94%   |
| 5.14.13-gentoo            | 2        | 1.94%   |
| 5.14.12-gentoo            | 2        | 1.94%   |
| 6.0.0-Phaco-g8f10ff49057f | 1        | 0.97%   |
| 5.19.1-gentoo-a6          | 1        | 0.97%   |
| 5.19.0-xanmod1-x86_64     | 1        | 0.97%   |
| 5.19.0-gentoo-x86_64      | 1        | 0.97%   |
| 5.19.0-gentoo-carbon      | 1        | 0.97%   |
| 5.18.9-gentoo-x86_64      | 1        | 0.97%   |
| 5.18.9-gentoo             | 1        | 0.97%   |
| 5.18.7-gentoo             | 1        | 0.97%   |
| 5.18.6-gentoo-x86_64      | 1        | 0.97%   |
| 5.18.6-gentoo             | 1        | 0.97%   |
| 5.18.3-zen1               | 1        | 0.97%   |
| 5.18.15-gentoo-x86_64     | 1        | 0.97%   |
| 5.18.15-gentoo            | 1        | 0.97%   |
| 5.18.14-gentoo            | 1        | 0.97%   |
| 5.18.10-k08               | 1        | 0.97%   |
| 5.18.10-gentoo-x86_64     | 1        | 0.97%   |
| 5.18.1-gentoo-r2          | 1        | 0.97%   |
| 5.18.0-gentoo             | 1        | 0.97%   |
| 5.17.9-gentoo-x86_64      | 1        | 0.97%   |
| 5.17.9-gentoo-dist        | 1        | 0.97%   |
| 5.17.8-gentoo-x86_64      | 1        | 0.97%   |
| 5.17.7-gentoo-x86_64      | 1        | 0.97%   |
| 5.17.7-gentoo-limelight   | 1        | 0.97%   |
| 5.17.7-gentoo-dist        | 1        | 0.97%   |
| 5.17.6-gentoo-x86_64      | 1        | 0.97%   |
| 5.17.3-gentoo-11-02-22    | 1        | 0.97%   |
| 5.17.3-gentoo             | 1        | 0.97%   |
| 5.17.2-gentoo-limelight   | 1        | 0.97%   |
| 5.17.2-gentoo             | 1        | 0.97%   |
| 5.17.1-gentoo-r1-x86_64   | 1        | 0.97%   |
| 5.17.0-gentoo-x86_64      | 1        | 0.97%   |
| 5.16.8-gentoo-x86_64      | 1        | 0.97%   |
| 5.16.7-tkg-cacule         | 1        | 0.97%   |
| 5.16.5-gentoo-dist        | 1        | 0.97%   |
| 5.16.4-gentoo             | 1        | 0.97%   |
| 5.16.2-gentoo             | 1        | 0.97%   |
| 5.16.15                   | 1        | 0.97%   |
| 5.16.14-gentoo-x86_64     | 1        | 0.97%   |
| 5.16.14-gentoo-girlhog    | 1        | 0.97%   |
| 5.16.13-gentoo            | 1        | 0.97%   |
| 5.16.10-gentoo-x86_64     | 1        | 0.97%   |
| 5.15.6-gentoo             | 1        | 0.97%   |
| 5.15.55-gentoo            | 1        | 0.97%   |
| 5.15.52-gentoo-ts221      | 1        | 0.97%   |
| 5.15.41-gentoo-dist       | 1        | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.52  | 12       | 11.65%  |
| 5.15.41  | 9        | 8.74%   |
| 5.19.0   | 5        | 4.85%   |
| 5.18.10  | 4        | 3.88%   |
| 5.17.1   | 4        | 3.88%   |
| 5.18.14  | 3        | 2.91%   |
| 5.17.7   | 3        | 2.91%   |
| 5.17.0   | 3        | 2.91%   |
| 5.18.9   | 2        | 1.94%   |
| 5.18.6   | 2        | 1.94%   |
| 5.18.15  | 2        | 1.94%   |
| 5.17.9   | 2        | 1.94%   |
| 5.17.3   | 2        | 1.94%   |
| 5.17.2   | 2        | 1.94%   |
| 5.16.14  | 2        | 1.94%   |
| 5.16.11  | 2        | 1.94%   |
| 5.15.59  | 2        | 1.94%   |
| 5.15.2   | 2        | 1.94%   |
| 5.15.10  | 2        | 1.94%   |
| 5.14.14  | 2        | 1.94%   |
| 5.14.13  | 2        | 1.94%   |
| 5.14.12  | 2        | 1.94%   |
| 6.0.0    | 1        | 0.97%   |
| 5.19.1   | 1        | 0.97%   |
| 5.18.7   | 1        | 0.97%   |
| 5.18.3   | 1        | 0.97%   |
| 5.18.1   | 1        | 0.97%   |
| 5.18.0   | 1        | 0.97%   |
| 5.17.8   | 1        | 0.97%   |
| 5.17.6   | 1        | 0.97%   |
| 5.16.8   | 1        | 0.97%   |
| 5.16.7   | 1        | 0.97%   |
| 5.16.5   | 1        | 0.97%   |
| 5.16.4   | 1        | 0.97%   |
| 5.16.2   | 1        | 0.97%   |
| 5.16.15  | 1        | 0.97%   |
| 5.16.13  | 1        | 0.97%   |
| 5.16.10  | 1        | 0.97%   |
| 5.15.6   | 1        | 0.97%   |
| 5.15.55  | 1        | 0.97%   |
| 5.15.4   | 1        | 0.97%   |
| 5.15.32  | 1        | 0.97%   |
| 5.15.16  | 1        | 0.97%   |
| 5.15.12  | 1        | 0.97%   |
| 5.15.11  | 1        | 0.97%   |
| 5.15.1   | 1        | 0.97%   |
| 5.15.0   | 1        | 0.97%   |
| 5.14.6   | 1        | 0.97%   |
| 5.14.15  | 1        | 0.97%   |
| 5.14.11  | 1        | 0.97%   |
| 5.10.84  | 1        | 0.97%   |
| 5.10.74  | 1        | 0.97%   |
| 4.9.16   | 1        | 0.97%   |
| 4.14.280 | 1        | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 32       | 34.04%  |
| 5.18    | 16       | 17.02%  |
| 5.17    | 15       | 15.96%  |
| 5.16    | 11       | 11.7%   |
| 5.14    | 9        | 9.57%   |
| 5.19    | 6        | 6.38%   |
| 5.10    | 2        | 2.13%   |
| 6.0     | 1        | 1.06%   |
| 4.9     | 1        | 1.06%   |
| 4.14    | 1        | 1.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 82       | 97.62%  |
| ppc      | 1        | 1.19%   |
| armv5tel | 1        | 1.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 28       | 32.56%  |
| Unknown  | 26       | 30.23%  |
| GNOME    | 17       | 19.77%  |
| XFCE     | 6        | 6.98%   |
| MATE     | 3        | 3.49%   |
| DWM      | 2        | 2.33%   |
| LXQt     | 1        | 1.16%   |
| KDE      | 1        | 1.16%   |
| i3       | 1        | 1.16%   |
| Cinnamon | 1        | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 43       | 48.86%  |
| Wayland | 17       | 19.32%  |
| Tty     | 15       | 17.05%  |
| Unknown | 13       | 14.77%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 41.86%  |
| SDDM    | 27       | 31.4%   |
| GDM     | 10       | 11.63%  |
| LightDM | 7        | 8.14%   |
| LXDM    | 4        | 4.65%   |
| XDM     | 1        | 1.16%   |
| SLiM    | 1        | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 35       | 41.67%  |
| en_GB   | 11       | 13.1%   |
| Unknown | 9        | 10.71%  |
| ru_RU   | 6        | 7.14%   |
| de_DE   | 5        | 5.95%   |
| C.UTF8  | 5        | 5.95%   |
| pl_PL   | 3        | 3.57%   |
| C       | 2        | 2.38%   |
| zh_TW   | 1        | 1.19%   |
| sl_SI   | 1        | 1.19%   |
| ja_JP   | 1        | 1.19%   |
| fr_FR   | 1        | 1.19%   |
| es_ES   | 1        | 1.19%   |
| en_CA   | 1        | 1.19%   |
| el_GR   | 1        | 1.19%   |
| de_CH   | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 74       | 86.05%  |
| BIOS | 12       | 13.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 47       | 55.95%  |
| Btrfs   | 19       | 22.62%  |
| F2fs    | 9        | 10.71%  |
| Zfs     | 3        | 3.57%   |
| Xfs     | 3        | 3.57%   |
| XXXXXXX | 2        | 2.38%   |
| XXX     | 1        | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 78       | 90.7%   |
| Unknown | 6        | 6.98%   |
| MBR     | 2        | 2.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 55.29%  |
| Yes       | 38       | 44.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 57.14%  |
| Yes       | 36       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 33       | 39.29%  |
| MSI                 | 15       | 17.86%  |
| Gigabyte Technology | 13       | 15.48%  |
| ASRock              | 12       | 14.29%  |
| Dell                | 3        | 3.57%   |
| Lenovo              | 2        | 2.38%   |
| Unknown             | 2        | 2.38%   |
| Pegatron            | 1        | 1.19%   |
| Intel               | 1        | 1.19%   |
| Fujitsu             | 1        | 1.19%   |
| EVGA                | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS Z170-A                         | 2        | 2.38%   |
| ASUS TUF Gaming X570-PLUS           | 2        | 2.38%   |
| ASUS TUF GAMING B550-PLUS           | 2        | 2.38%   |
| ASUS ROG STRIX X570-E GAMING        | 2        | 2.38%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 2.38%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 2        | 2.38%   |
| Unknown                             | 2        | 2.38%   |
| Pegatron 810-170st                  | 1        | 1.19%   |
| MSI MS-7D31                         | 1        | 1.19%   |
| MSI MS-7D25                         | 1        | 1.19%   |
| MSI MS-7D09                         | 1        | 1.19%   |
| MSI MS-7C94                         | 1        | 1.19%   |
| MSI MS-7C56                         | 1        | 1.19%   |
| MSI MS-7C37                         | 1        | 1.19%   |
| MSI MS-7C35                         | 1        | 1.19%   |
| MSI MS-7C02                         | 1        | 1.19%   |
| MSI MS-7B98                         | 1        | 1.19%   |
| MSI MS-7B89                         | 1        | 1.19%   |
| MSI MS-7B86                         | 1        | 1.19%   |
| MSI MS-7B85                         | 1        | 1.19%   |
| MSI MS-7B17                         | 1        | 1.19%   |
| MSI MS-7996                         | 1        | 1.19%   |
| MSI MS-7821                         | 1        | 1.19%   |
| Lenovo ThinkStation P620 30E0001TGE | 1        | 1.19%   |
| Lenovo Legion T5 26AMR5 90RB0002US  | 1        | 1.19%   |
| Intel D54250WYK H13922-303          | 1        | 1.19%   |
| Gigabyte Z87X-UD3H                  | 1        | 1.19%   |
| Gigabyte Z77X-D3H                   | 1        | 1.19%   |
| Gigabyte Z690 AORUS MASTER          | 1        | 1.19%   |
| Gigabyte Z590 UD                    | 1        | 1.19%   |
| Gigabyte Z490 UD                    | 1        | 1.19%   |
| Gigabyte X570 AORUS MASTER          | 1        | 1.19%   |
| Gigabyte H470 HD3                   | 1        | 1.19%   |
| Gigabyte B550M DS3H                 | 1        | 1.19%   |
| Gigabyte B450M S2H                  | 1        | 1.19%   |
| Gigabyte B450 GAMING X              | 1        | 1.19%   |
| Gigabyte B450 AORUS M               | 1        | 1.19%   |
| Gigabyte AB350-Gaming               | 1        | 1.19%   |
| Gigabyte 970A-DS3                   | 1        | 1.19%   |
| Fujitsu D3417-B2 S26361-D3417-B2    | 1        | 1.19%   |
| EVGA Z390 DARK                      | 1        | 1.19%   |
| Dell XPS 8700                       | 1        | 1.19%   |
| Dell OptiPlex 790                   | 1        | 1.19%   |
| Dell OptiPlex 7080                  | 1        | 1.19%   |
| ASUS Z170 PRO GAMING                | 1        | 1.19%   |
| ASUS TUF Gaming Z690-PLUS WIFI D4   | 1        | 1.19%   |
| ASUS TUF Gaming X570-PRO            | 1        | 1.19%   |
| ASUS TUF B450M-PLUS GAMING          | 1        | 1.19%   |
| ASUS TUF B450-PLUS GAMING           | 1        | 1.19%   |
| ASUS ROG ZENITH II EXTREME          | 1        | 1.19%   |
| ASUS ROG STRIX Z390-E GAMING        | 1        | 1.19%   |
| ASUS ROG STRIX Z370-H GAMING        | 1        | 1.19%   |
| ASUS ROG STRIX B560-I GAMING WIFI   | 1        | 1.19%   |
| ASUS ROG STRIX B450-F GAMING        | 1        | 1.19%   |
| ASUS ROG Maximus Z690 EXTREME       | 1        | 1.19%   |
| ASUS ROG Maximus XIII APEX          | 1        | 1.19%   |
| ASUS ROG Maximus XI HERO            | 1        | 1.19%   |
| ASUS ROG CROSSHAIR VIII HERO        | 1        | 1.19%   |
| ASUS PRIME Z390-A                   | 1        | 1.19%   |
| ASUS PRIME X570-PRO                 | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 15       | 17.86%  |
| ASUS TUF              | 8        | 9.52%   |
| ASUS PRIME            | 4        | 4.76%   |
| Gigabyte B450         | 2        | 2.38%   |
| Dell OptiPlex         | 2        | 2.38%   |
| ASUS Z170-A           | 2        | 2.38%   |
| ASRock X370           | 2        | 2.38%   |
| Unknown               | 2        | 2.38%   |
| Pegatron 810-170st    | 1        | 1.19%   |
| MSI MS-7D31           | 1        | 1.19%   |
| MSI MS-7D25           | 1        | 1.19%   |
| MSI MS-7D09           | 1        | 1.19%   |
| MSI MS-7C94           | 1        | 1.19%   |
| MSI MS-7C56           | 1        | 1.19%   |
| MSI MS-7C37           | 1        | 1.19%   |
| MSI MS-7C35           | 1        | 1.19%   |
| MSI MS-7C02           | 1        | 1.19%   |
| MSI MS-7B98           | 1        | 1.19%   |
| MSI MS-7B89           | 1        | 1.19%   |
| MSI MS-7B86           | 1        | 1.19%   |
| MSI MS-7B85           | 1        | 1.19%   |
| MSI MS-7B17           | 1        | 1.19%   |
| MSI MS-7996           | 1        | 1.19%   |
| MSI MS-7821           | 1        | 1.19%   |
| Lenovo ThinkStation   | 1        | 1.19%   |
| Lenovo Legion         | 1        | 1.19%   |
| Intel D54250WYK       | 1        | 1.19%   |
| Gigabyte Z87X-UD3H    | 1        | 1.19%   |
| Gigabyte Z77X-D3H     | 1        | 1.19%   |
| Gigabyte Z690         | 1        | 1.19%   |
| Gigabyte Z590         | 1        | 1.19%   |
| Gigabyte Z490         | 1        | 1.19%   |
| Gigabyte X570         | 1        | 1.19%   |
| Gigabyte H470         | 1        | 1.19%   |
| Gigabyte B550M        | 1        | 1.19%   |
| Gigabyte B450M        | 1        | 1.19%   |
| Gigabyte AB350-Gaming | 1        | 1.19%   |
| Gigabyte 970A-DS3     | 1        | 1.19%   |
| Fujitsu D3417-B2      | 1        | 1.19%   |
| EVGA Z390             | 1        | 1.19%   |
| Dell XPS              | 1        | 1.19%   |
| ASUS Z170             | 1        | 1.19%   |
| ASUS P6X58D-E         | 1        | 1.19%   |
| ASUS P5LD2-Deluxe     | 1        | 1.19%   |
| ASUS M3A78-CM         | 1        | 1.19%   |
| ASRock Z170A-X1       | 1        | 1.19%   |
| ASRock X570           | 1        | 1.19%   |
| ASRock X399           | 1        | 1.19%   |
| ASRock P67            | 1        | 1.19%   |
| ASRock H110M-HDV      | 1        | 1.19%   |
| ASRock B75M-GL        | 1        | 1.19%   |
| ASRock B550M          | 1        | 1.19%   |
| ASRock B450           | 1        | 1.19%   |
| ASRock AM1H-ITX       | 1        | 1.19%   |
| ASRock AB350M         | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 14       | 16.67%  |
| 2019    | 14       | 16.67%  |
| 2018    | 13       | 15.48%  |
| 2021    | 12       | 14.29%  |
| 2017    | 7        | 8.33%   |
| 2013    | 4        | 4.76%   |
| 2016    | 3        | 3.57%   |
| 2015    | 3        | 3.57%   |
| 2014    | 3        | 3.57%   |
| 2022    | 2        | 2.38%   |
| 2012    | 2        | 2.38%   |
| 2011    | 2        | 2.38%   |
| Unknown | 2        | 2.38%   |
| 2010    | 1        | 1.19%   |
| 2008    | 1        | 1.19%   |
| 2005    | 1        | 1.19%   |

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
| Disabled | 82       | 96.47%  |
| Enabled  | 3        | 3.53%   |

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
| 32.01-64.0  | 35       | 41.67%  |
| 64.01-256.0 | 19       | 22.62%  |
| 16.01-24.0  | 15       | 17.86%  |
| 24.01-32.0  | 5        | 5.95%   |
| 8.01-16.0   | 5        | 5.95%   |
| 4.01-8.0    | 2        | 2.38%   |
| 0.51-1.0    | 2        | 2.38%   |
| 2.01-3.0    | 1        | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 26       | 26.53%  |
| 8.01-16.0  | 19       | 19.39%  |
| 2.01-3.0   | 12       | 12.24%  |
| 1.01-2.0   | 11       | 11.22%  |
| 3.01-4.0   | 10       | 10.2%   |
| 16.01-24.0 | 8        | 8.16%   |
| 0.51-1.0   | 4        | 4.08%   |
| 0.01-0.5   | 3        | 3.06%   |
| 32.01-64.0 | 2        | 2.04%   |
| 24.01-32.0 | 2        | 2.04%   |
| 0          | 1        | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 30.23%  |
| 3      | 20       | 23.26%  |
| 5      | 10       | 11.63%  |
| 4      | 10       | 11.63%  |
| 1      | 8        | 9.3%    |
| 6      | 7        | 8.14%   |
| 7      | 4        | 4.65%   |
| 12     | 1        | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 77.91%  |
| Yes       | 19       | 22.09%  |

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
| No        | 44       | 51.76%  |
| Yes       | 41       | 48.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 51.76%  |
| No        | 41       | 48.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 23       | 27.38%  |
| Germany     | 13       | 15.48%  |
| Russia      | 9        | 10.71%  |
| Poland      | 8        | 9.52%   |
| UK          | 4        | 4.76%   |
| Switzerland | 3        | 3.57%   |
| Spain       | 2        | 2.38%   |
| Czechia     | 2        | 2.38%   |
| Canada      | 2        | 2.38%   |
| Taiwan      | 1        | 1.19%   |
| Slovenia    | 1        | 1.19%   |
| Slovakia    | 1        | 1.19%   |
| Romania     | 1        | 1.19%   |
| Netherlands | 1        | 1.19%   |
| Mexico      | 1        | 1.19%   |
| Malaysia    | 1        | 1.19%   |
| Japan       | 1        | 1.19%   |
| Ireland     | 1        | 1.19%   |
| India       | 1        | 1.19%   |
| Hong Kong   | 1        | 1.19%   |
| Greece      | 1        | 1.19%   |
| France      | 1        | 1.19%   |
| Finland     | 1        | 1.19%   |
| China       | 1        | 1.19%   |
| Belarus     | 1        | 1.19%   |
| Bangladesh  | 1        | 1.19%   |
| Australia   | 1        | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Moscow               | 4        | 4.71%   |
| Swansea              | 3        | 3.53%   |
| Cieszyn              | 3        | 3.53%   |
| Zurich               | 2        | 2.35%   |
| Warsaw               | 2        | 2.35%   |
| Seattle              | 2        | 2.35%   |
| Los Angeles          | 2        | 2.35%   |
| Yekaterinburg        | 1        | 1.18%   |
| Wrentham             | 1        | 1.18%   |
| Warren               | 1        | 1.18%   |
| Vladivostok          | 1        | 1.18%   |
| Vigo                 | 1        | 1.18%   |
| Vancouver            | 1        | 1.18%   |
| Ufa                  | 1        | 1.18%   |
| Troisdorf            | 1        | 1.18%   |
| Trnava               | 1        | 1.18%   |
| Thibodaux            | 1        | 1.18%   |
| Texas City           | 1        | 1.18%   |
| Taichung City        | 1        | 1.18%   |
| Sydney               | 1        | 1.18%   |
| Svobodnyy            | 1        | 1.18%   |
| Sterling             | 1        | 1.18%   |
| Stasi Las            | 1        | 1.18%   |
| St. Cloud            | 1        | 1.18%   |
| St Louis             | 1        | 1.18%   |
| Schwieberdingen      | 1        | 1.18%   |
| Sankt Wendel         | 1        | 1.18%   |
| Rostock              | 1        | 1.18%   |
| Renens               | 1        | 1.18%   |
| Redmond              | 1        | 1.18%   |
| Radovljica           | 1        | 1.18%   |
| Prague               | 1        | 1.18%   |
| Oulu                 | 1        | 1.18%   |
| Orange               | 1        | 1.18%   |
| Ocala                | 1        | 1.18%   |
| Murmansk             | 1        | 1.18%   |
| Munich               | 1        | 1.18%   |
| Morcenx              | 1        | 1.18%   |
| Monroe               | 1        | 1.18%   |
| Mildstedt            | 1        | 1.18%   |
| Meguro-ku            | 1        | 1.18%   |
| Mariánské Lázně  | 1        | 1.18%   |
| Laziska Gorne        | 1        | 1.18%   |
| Laka                 | 1        | 1.18%   |
| Kulmbach             | 1        | 1.18%   |
| Kuala Lumpur         | 1        | 1.18%   |
| Krakow               | 1        | 1.18%   |
| Kensington           | 1        | 1.18%   |
| Kallithea            | 1        | 1.18%   |
| Hyderabad            | 1        | 1.18%   |
| Hyannis              | 1        | 1.18%   |
| Houston              | 1        | 1.18%   |
| Gunzenhausen         | 1        | 1.18%   |
| Gomel                | 1        | 1.18%   |
| Glen Ellyn           | 1        | 1.18%   |
| Freiburg im Breisgau | 1        | 1.18%   |
| Foshan               | 1        | 1.18%   |
| Fort Collins         | 1        | 1.18%   |
| Florence             | 1        | 1.18%   |
| Essen                | 1        | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 45       | 105    | 23.2%   |
| WDC                 | 38       | 67     | 19.59%  |
| Seagate             | 27       | 58     | 13.92%  |
| Toshiba             | 13       | 22     | 6.7%    |
| Hitachi             | 9        | 21     | 4.64%   |
| SanDisk             | 7        | 9      | 3.61%   |
| Crucial             | 7        | 14     | 3.61%   |
| Kingston            | 6        | 7      | 3.09%   |
| Intel               | 5        | 6      | 2.58%   |
| Phison              | 4        | 6      | 2.06%   |
| HGST                | 4        | 5      | 2.06%   |
| Corsair             | 4        | 5      | 2.06%   |
| A-DATA Technology   | 4        | 5      | 2.06%   |
| OCZ                 | 3        | 3      | 1.55%   |
| GOODRAM             | 3        | 7      | 1.55%   |
| KIOXIA-EXCERIA      | 2        | 3      | 1.03%   |
| Kingchuxing         | 2        | 5      | 1.03%   |
| Unknown             | 1        | 1      | 0.52%   |
| Transcend           | 1        | 1      | 0.52%   |
| Team                | 1        | 3      | 0.52%   |
| SK hynix            | 1        | 2      | 0.52%   |
| Silicon Motion      | 1        | 2      | 0.52%   |
| PNY                 | 1        | 1      | 0.52%   |
| Plextor             | 1        | 2      | 0.52%   |
| OCZ-VERTEX          | 1        | 1      | 0.52%   |
| LaCie               | 1        | 2      | 0.52%   |
| Fujitsu             | 1        | 1      | 0.52%   |
| Apacer              | 1        | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 970 EVO 500GB        | 5        | 1.94%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.16%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 1.16%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 1.16%   |
| Samsung SSD 980 PRO 2TB          | 3        | 1.16%   |
| Samsung SSD 980 1TB              | 3        | 1.16%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 1.16%   |
| Samsung SSD 970 EVO Plus 2TB     | 3        | 1.16%   |
| Samsung SSD 870 EVO 1TB          | 3        | 1.16%   |
| Samsung SSD 850 EVO 500GB        | 3        | 1.16%   |
| Crucial CT2000MX500SSD1 2TB      | 3        | 1.16%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 1.16%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.78%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.78%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 0.78%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.78%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.78%   |
| Seagate ST4000DM005-2DP166 4TB   | 2        | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.78%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.78%   |
| Samsung SSD 980 PRO 500GB        | 2        | 0.78%   |
| Samsung SSD 980 PRO 1TB          | 2        | 0.78%   |
| Samsung SSD 970 PRO 1TB          | 2        | 0.78%   |
| Samsung SSD 970 EVO Plus 250GB   | 2        | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.78%   |
| Samsung SSD 970 EVO 250GB        | 2        | 0.78%   |
| Samsung SSD 860 QVO 2TB          | 2        | 0.78%   |
| Samsung SSD 860 PRO 4TB          | 2        | 0.78%   |
| Samsung SSD 850 PRO 256GB        | 2        | 0.78%   |
| Samsung SSD 850 EVO 250GB        | 2        | 0.78%   |
| Samsung SSD 840 PRO Series 128GB | 2        | 0.78%   |
| Samsung NVMe SSD Drive 512GB     | 2        | 0.78%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.78%   |
| Samsung NVMe SSD Drive 2TB       | 2        | 0.78%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 0.78%   |
| Phison Sabrent Rocket 4.0 1TB    | 2        | 0.78%   |
| Hitachi HDS723020BLA642 2TB      | 2        | 0.78%   |
| HGST HTS545050A7E380 500GB       | 2        | 0.78%   |
| GOODRAM SSDPR-CL100-480-G2 480GB | 2        | 0.78%   |
| A-DATA SX8200PNP 512GB           | 2        | 0.78%   |
| A-DATA SX8200PNP 1TB             | 2        | 0.78%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.39%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.39%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.39%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.39%   |
| WDC WDS500G1B0C-00S6U0 500GB     | 1        | 0.39%   |
| WDC WDS240G2G0A 240GB SSD        | 1        | 0.39%   |
| WDC WDS200T3X0C-00SJG0 2TB       | 1        | 0.39%   |
| WDC WDS100T2B0A 1TB SSD          | 1        | 0.39%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 0.39%   |
| WDC WD80EDAZ-11TA3A0 8TB         | 1        | 0.39%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1        | 0.39%   |
| WDC WD7500BPVT-22HXZT1 752GB     | 1        | 0.39%   |
| WDC WD60EZRX-00MVLB1 6TB         | 1        | 0.39%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.39%   |
| WDC WD5000AZLX-00JKKA0 500GB     | 1        | 0.39%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.39%   |
| WDC WD3200AAJS-22RYA0 320GB      | 1        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 30       | 54     | 37.04%  |
| Seagate | 25       | 55     | 30.86%  |
| Toshiba | 11       | 18     | 13.58%  |
| Hitachi | 9        | 21     | 11.11%  |
| HGST    | 4        | 5      | 4.94%   |
| LaCie   | 1        | 2      | 1.23%   |
| Fujitsu | 1        | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 41     | 37.31%  |
| SanDisk             | 6        | 8      | 8.96%   |
| Kingston            | 6        | 7      | 8.96%   |
| Crucial             | 6        | 12     | 8.96%   |
| WDC                 | 5        | 6      | 7.46%   |
| OCZ                 | 3        | 3      | 4.48%   |
| Intel               | 3        | 3      | 4.48%   |
| GOODRAM             | 3        | 7      | 4.48%   |
| Corsair             | 3        | 4      | 4.48%   |
| Transcend           | 1        | 1      | 1.49%   |
| Toshiba             | 1        | 2      | 1.49%   |
| PNY                 | 1        | 1      | 1.49%   |
| OCZ-VERTEX          | 1        | 1      | 1.49%   |
| Kingchuxing         | 1        | 1      | 1.49%   |
| Apacer              | 1        | 1      | 1.49%   |
| A-DATA Technology   | 1        | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 58       | 156    | 34.94%  |
| NVMe    | 55       | 109    | 33.13%  |
| SSD     | 52       | 99     | 31.33%  |
| Unknown | 1        | 1      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 78       | 251    | 57.78%  |
| NVMe | 55       | 109    | 40.74%  |
| SAS  | 2        | 5      | 1.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 40       | 74     | 29.41%  |
| 0.51-1.0   | 34       | 49     | 25%     |
| 1.01-2.0   | 28       | 45     | 20.59%  |
| 3.01-4.0   | 15       | 22     | 11.03%  |
| 4.01-10.0  | 10       | 41     | 7.35%   |
| 2.01-3.0   | 6        | 17     | 4.41%   |
| 10.01-20.0 | 3        | 7      | 2.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 20       | 22.73%  |
| 501-1000       | 15       | 17.05%  |
| 1001-2000      | 13       | 14.77%  |
| 251-500        | 11       | 12.5%   |
| 2001-3000      | 11       | 12.5%   |
| 101-250        | 6        | 6.82%   |
| 1-20           | 4        | 4.55%   |
| 51-100         | 3        | 3.41%   |
| Unknown        | 3        | 3.41%   |
| 21-50          | 2        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 15       | 16.85%  |
| 1001-2000      | 14       | 15.73%  |
| More than 3000 | 11       | 12.36%  |
| 1-20           | 11       | 12.36%  |
| 501-1000       | 11       | 12.36%  |
| 101-250        | 9        | 10.11%  |
| 21-50          | 6        | 6.74%   |
| 51-100         | 5        | 5.62%   |
| 2001-3000      | 4        | 4.49%   |
| Unknown        | 3        | 3.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 3      | 3.85%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 1      | 3.85%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 2      | 3.85%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 3.85%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 3.85%   |
| WDC WD20EARS-00J2GB0 2TB              | 1        | 1      | 3.85%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 1      | 3.85%   |
| WDC WD1002FBYS-18W8B0 1TB             | 1        | 1      | 3.85%   |
| Transcend TS512GSSD720 512GB          | 1        | 1      | 3.85%   |
| Toshiba HDWA120 2TB                   | 1        | 1      | 3.85%   |
| Seagate ST3160023AS 160GB             | 1        | 1      | 3.85%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 3.85%   |
| Seagate ST10000VN0004-1ZD101 10TB     | 1        | 4      | 3.85%   |
| SanDisk SSD PLUS 1000GB               | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 1TB   | 1        | 2      | 3.85%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 4      | 3.85%   |
| OCZ VERTEX4 128GB SSD                 | 1        | 1      | 3.85%   |
| Kingston SV100S2128G 128GB SSD        | 1        | 1      | 3.85%   |
| Hitachi HUA721010KLA330 1TB           | 1        | 1      | 3.85%   |
| Hitachi HTS541680J9SA00 80GB          | 1        | 1      | 3.85%   |
| Hitachi HDS722020ALA330 2TB           | 1        | 2      | 3.85%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 30.77%  |
| Samsung Electronics | 6        | 10     | 23.08%  |
| Seagate             | 3        | 6      | 11.54%  |
| Hitachi             | 3        | 4      | 11.54%  |
| Transcend           | 1        | 1      | 3.85%   |
| Toshiba             | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| OCZ                 | 1        | 1      | 3.85%   |
| Kingston            | 1        | 1      | 3.85%   |
| Crucial             | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 11     | 53.33%  |
| Seagate | 3        | 6      | 20%     |
| Hitachi | 3        | 4      | 20%     |
| Toshiba | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 22     | 54.17%  |
| SSD  | 8        | 11     | 33.33%  |
| NVMe | 3        | 4      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 77       | 293    | 70.64%  |
| Malfunc  | 22       | 37     | 20.18%  |
| Detected | 9        | 34     | 8.26%   |
| Failed   | 1        | 1      | 0.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 44       | 27.67%  |
| Intel                          | 37       | 23.27%  |
| Samsung Electronics            | 34       | 21.38%  |
| ASMedia Technology             | 8        | 5.03%   |
| SanDisk                        | 7        | 4.4%    |
| Phison Electronics             | 6        | 3.77%   |
| Silicon Motion                 | 3        | 1.89%   |
| Marvell Technology Group       | 3        | 1.89%   |
| ADATA Technology               | 3        | 1.89%   |
| Toshiba America Info Systems   | 2        | 1.26%   |
| Seagate Technology             | 2        | 1.26%   |
| KIOXIA                         | 2        | 1.26%   |
| Broadcom / LSI                 | 2        | 1.26%   |
| Unknown                        | 1        | 0.63%   |
| Solid State Storage Technology | 1        | 0.63%   |
| SK hynix                       | 1        | 0.63%   |
| Silicon Image                  | 1        | 0.63%   |
| Micron/Crucial Technology      | 1        | 0.63%   |
| JMicron Technology             | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 16.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24       | 13.19%  |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 6.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 4.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 4.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 4.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.65%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 1.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.65%   |
| Seagate FireCuda 520 SSD                                                                | 2        | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.1%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 1.1%    |
| Phison E12 NVMe Controller                                                              | 2        | 1.1%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.1%    |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.1%    |
| Unknown Non-Volatile memory controller                                                  | 1        | 0.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.55%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.55%   |
| Solid State Storage Non-Volatile memory controller                                      | 1        | 0.55%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.55%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.55%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 1        | 0.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.55%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.55%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.55%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.55%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.55%   |
| KIOXIA NVMe SSD                                                                         | 1        | 0.55%   |
| KIOXIA Non-Volatile memory controller                                                   | 1        | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.55%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.55%   |
| Intel Optane SSD 900P Series                                                            | 1        | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 0.55%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 1        | 0.55%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.55%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 79       | 55.24%  |
| NVMe | 55       | 38.46%  |
| IDE  | 4        | 2.8%    |
| RAID | 3        | 2.1%    |
| SAS  | 2        | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 44       | 52.38%  |
| Intel                 | 38       | 45.24%  |
| PowerBook6,7          | 1        | 1.19%   |
| Marvell Semiconductor | 1        | 1.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor                                      | 5        | 5.95%   |
| AMD Ryzen 9 5950X 16-Core Processor                                      | 4        | 4.76%   |
| AMD Ryzen 9 3950X 16-Core Processor                                      | 4        | 4.76%   |
| AMD Ryzen 5 2600 Six-Core Processor                                      | 4        | 4.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                        | 3        | 3.57%   |
| AMD Ryzen 9 3900X 12-Core Processor                                      | 3        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor                                        | 3        | 3.57%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                        | 2        | 2.38%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                        | 2        | 2.38%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                        | 2        | 2.38%   |
| Intel 12th Gen Core i9-12900K                                            | 2        | 2.38%   |
| Intel 12th Gen Core i7-12700K                                            | 2        | 2.38%   |
| AMD Ryzen 7 3700X 8-Core Processor                                       | 2        | 2.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor                                   | 2        | 2.38%   |
| AMD Ryzen 5 1600 Six-Core Processor                                      | 2        | 2.38%   |
| PowerBook6,7 7447A, altivec supported                                    | 1        | 1.19%   |
| Marvell Semiconductor Marvell Kirkwood (Flattened Device Tree) Processor | 1        | 1.19%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                           | 1        | 1.19%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz                                      | 1        | 1.19%   |
| Intel Pentium 4 CPU 3.20GHz                                              | 1        | 1.19%   |
| Intel Core i7-8086K CPU @ 4.00GHz                                        | 1        | 1.19%   |
| Intel Core i7-4930K CPU @ 3.40GHz                                        | 1        | 1.19%   |
| Intel Core i7-4790K CPU @ 4.00GHz                                        | 1        | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz                                         | 1        | 1.19%   |
| Intel Core i7-10700F CPU @ 2.90GHz                                       | 1        | 1.19%   |
| Intel Core i7-10700 CPU @ 2.90GHz                                        | 1        | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                         | 1        | 1.19%   |
| Intel Core i5-6500 CPU @ 3.20GHz                                         | 1        | 1.19%   |
| Intel Core i5-6400 CPU @ 2.70GHz                                         | 1        | 1.19%   |
| Intel Core i5-4670K CPU @ 3.40GHz                                        | 1        | 1.19%   |
| Intel Core i5-4250U CPU @ 1.30GHz                                        | 1        | 1.19%   |
| Intel Core i5-3550 CPU @ 3.30GHz                                         | 1        | 1.19%   |
| Intel Core i5-2500S CPU @ 2.70GHz                                        | 1        | 1.19%   |
| Intel Core i5-2500K CPU @ 3.30GHz                                        | 1        | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz                                         | 1        | 1.19%   |
| Intel Core i5-10400F CPU @ 2.90GHz                                       | 1        | 1.19%   |
| Intel Core i5-10400 CPU @ 2.90GHz                                        | 1        | 1.19%   |
| Intel 12th Gen Core i7-12700KF                                           | 1        | 1.19%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz                                 | 1        | 1.19%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz                                  | 1        | 1.19%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz                                  | 1        | 1.19%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz                                   | 1        | 1.19%   |
| AMD Sempron 3850 APU with Radeon R3                                      | 1        | 1.19%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores                               | 1        | 1.19%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor                           | 1        | 1.19%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor                           | 1        | 1.19%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics                               | 1        | 1.19%   |
| AMD Ryzen 7 5800X 8-Core Processor                                       | 1        | 1.19%   |
| AMD Ryzen 7 5700G with Radeon Graphics                                   | 1        | 1.19%   |
| AMD Ryzen 7 3800X 8-Core Processor                                       | 1        | 1.19%   |
| AMD Ryzen 7 1700X Eight-Core Processor                                   | 1        | 1.19%   |
| AMD Ryzen 5 5600X 6-Core Processor                                       | 1        | 1.19%   |
| AMD Ryzen 5 3600X 6-Core Processor                                       | 1        | 1.19%   |
| AMD Ryzen 5 2600X Six-Core Processor                                     | 1        | 1.19%   |
| AMD Ryzen 3 4300GE with Radeon Graphics                                  | 1        | 1.19%   |
| AMD Phenom II X4 955 Processor                                           | 1        | 1.19%   |
| AMD FX-4300 Quad-Core Processor                                          | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 16       | 19.05%  |
| Intel Core i5          | 13       | 15.48%  |
| AMD Ryzen 5            | 12       | 14.29%  |
| Other                  | 11       | 13.1%   |
| Intel Core i7          | 11       | 13.1%   |
| AMD Ryzen 7            | 8        | 9.52%   |
| AMD Ryzen Threadripper | 3        | 3.57%   |
| Intel Xeon             | 2        | 2.38%   |
| Intel Core i9          | 2        | 2.38%   |
| Intel Pentium 4        | 1        | 1.19%   |
| AMD Sempron            | 1        | 1.19%   |
| AMD Ryzen 7 PRO        | 1        | 1.19%   |
| AMD Ryzen 3            | 1        | 1.19%   |
| AMD Phenom II X4       | 1        | 1.19%   |
| AMD FX                 | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 22       | 26.19%  |
| 4      | 17       | 20.24%  |
| 8      | 16       | 19.05%  |
| 12     | 12       | 14.29%  |
| 16     | 11       | 13.1%   |
| 1      | 3        | 3.57%   |
| 2      | 2        | 2.38%   |
| 24     | 1        | 1.19%   |

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
| 2      | 68       | 80.95%  |
| 1      | 16       | 19.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 82       | 97.62%  |
| 32-bit         | 1        | 1.19%   |
| Unknown        | 1        | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 16.47%  |
| 0x08701021 | 10       | 11.76%  |
| 0x0a201016 | 7        | 8.24%   |
| 0x90672    | 5        | 5.88%   |
| 0x0800820d | 5        | 5.88%   |
| 0xa0671    | 4        | 4.71%   |
| 0x506e3    | 4        | 4.71%   |
| 0x906ed    | 3        | 3.53%   |
| 0x08001138 | 3        | 3.53%   |
| 0xa0655    | 2        | 2.35%   |
| 0xa0653    | 2        | 2.35%   |
| 0x906ea    | 2        | 2.35%   |
| 0x906e9    | 2        | 2.35%   |
| 0x306c3    | 2        | 2.35%   |
| 0x206a7    | 2        | 2.35%   |
| 0x0a201204 | 2        | 2.35%   |
| 0x08301039 | 2        | 2.35%   |
| 0xf43      | 1        | 1.18%   |
| 0x906ec    | 1        | 1.18%   |
| 0x40651    | 1        | 1.18%   |
| 0x306e4    | 1        | 1.18%   |
| 0x306a9    | 1        | 1.18%   |
| 0x206c2    | 1        | 1.18%   |
| 0x0a50000c | 1        | 1.18%   |
| 0x0a50000b | 1        | 1.18%   |
| 0x0a201205 | 1        | 1.18%   |
| 0x0a201009 | 1        | 1.18%   |
| 0x08600106 | 1        | 1.18%   |
| 0x08001137 | 1        | 1.18%   |
| 0x0700010f | 1        | 1.18%   |
| 0x010000db | 1        | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 17       | 20%     |
| Zen 3            | 13       | 15.29%  |
| KabyLake         | 9        | 10.59%  |
| Zen+             | 7        | 8.24%   |
| Skylake          | 5        | 5.88%   |
| Alderlake Hybrid | 5        | 5.88%   |
| Zen              | 4        | 4.71%   |
| Icelake          | 4        | 4.71%   |
| Haswell          | 4        | 4.71%   |
| CometLake        | 4        | 4.71%   |
| SandyBridge      | 3        | 3.53%   |
| Unknown          | 3        | 3.53%   |
| IvyBridge        | 2        | 2.35%   |
| Westmere         | 1        | 1.18%   |
| Piledriver       | 1        | 1.18%   |
| NetBurst         | 1        | 1.18%   |
| K10              | 1        | 1.18%   |
| Jaguar           | 1        | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 47       | 51.65%  |
| Nvidia | 32       | 35.16%  |
| Intel  | 12       | 13.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 20       | 21.28%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                        | 5        | 5.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                   | 3        | 3.19%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                 | 2        | 2.13%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                | 2        | 2.13%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                | 2        | 2.13%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                             | 2        | 2.13%   |
| Nvidia GP104 [GeForce GTX 1080]                                       | 2        | 2.13%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                    | 2        | 2.13%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                    | 2        | 2.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                              | 2        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                             | 2        | 2.13%   |
| Intel AlderLake-S GT1                                                 | 2        | 2.13%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                            | 2        | 2.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                      | 2        | 2.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]   | 2        | 2.13%   |
| Nvidia TU116 [GeForce GTX 1650]                                       | 1        | 1.06%   |
| Nvidia TU106 [GeForce RTX 2070]                                       | 1        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                 | 1        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                 | 1        | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                        | 1        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                   | 1        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                       | 1        | 1.06%   |
| Nvidia GM206 [GeForce GTX 960]                                        | 1        | 1.06%   |
| Nvidia GM204 [GeForce GTX 970]                                        | 1        | 1.06%   |
| Nvidia GM107 [GeForce GTX 745]                                        | 1        | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                        | 1        | 1.06%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                    | 1        | 1.06%   |
| Nvidia GF119 [GeForce GT 610]                                         | 1        | 1.06%   |
| Nvidia GA106 [Geforce RTX 3050]                                       | 1        | 1.06%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                    | 1        | 1.06%   |
| Nvidia GA102 [GeForce RTX 3090]                                       | 1        | 1.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller      | 1        | 1.06%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                             | 1        | 1.06%   |
| Intel HD Graphics P630                                                | 1        | 1.06%   |
| Intel HD Graphics 630                                                 | 1        | 1.06%   |
| Intel HD Graphics 530                                                 | 1        | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                      | 1        | 1.06%   |
| AMD Vega 20 [Radeon VII]                                              | 1        | 1.06%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                              | 1        | 1.06%   |
| AMD Turks PRO [Radeon HD 7570]                                        | 1        | 1.06%   |
| AMD RV360/M12 [Mobility Radeon 9550]                                  | 1        | 1.06%   |
| AMD RS780C [Radeon 3100]                                              | 1        | 1.06%   |
| AMD Renoir                                                            | 1        | 1.06%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 1.06%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                        | 1        | 1.06%   |
| AMD Navi 23 [Radeon RX 6650 XT]                                       | 1        | 1.06%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                  | 1        | 1.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]               | 1        | 1.06%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                      | 1        | 1.06%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                               | 1        | 1.06%   |
| AMD Fiji [Radeon R9 FURY / NANO Series]                               | 1        | 1.06%   |
| AMD Ellesmere [Radeon Pro WX 7100]                                    | 1        | 1.06%   |
| AMD Cezanne                                                           | 1        | 1.06%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                  | 1        | 1.06%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                        | 1        | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 40       | 47.06%  |
| 1 x Nvidia     | 28       | 32.94%  |
| 1 x Intel      | 7        | 8.24%   |
| AMD + Nvidia   | 3        | 3.53%   |
| Other          | 2        | 2.35%   |
| 2 x AMD        | 2        | 2.35%   |
| Intel + AMD    | 2        | 2.35%   |
| Intel + Nvidia | 1        | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 62.35%  |
| Proprietary | 26       | 30.59%  |
| Unknown     | 6        | 7.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 27       | 30.68%  |
| Unknown    | 25       | 28.41%  |
| 8.01-16.0  | 12       | 13.64%  |
| 3.01-4.0   | 8        | 9.09%   |
| 5.01-6.0   | 5        | 5.68%   |
| 0.51-1.0   | 5        | 5.68%   |
| 1.01-2.0   | 4        | 4.55%   |
| 2.01-3.0   | 1        | 1.14%   |
| 0.01-0.5   | 1        | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 14       | 12.73%  |
| Goldstar                | 14       | 12.73%  |
| Dell                    | 8        | 7.27%   |
| ViewSonic               | 6        | 5.45%   |
| Hewlett-Packard         | 6        | 5.45%   |
| AOC                     | 6        | 5.45%   |
| Ancor Communications    | 5        | 4.55%   |
| Acer                    | 5        | 4.55%   |
| Lenovo                  | 4        | 3.64%   |
| BenQ                    | 4        | 3.64%   |
| Iiyama                  | 3        | 2.73%   |
| Eizo                    | 3        | 2.73%   |
| ASUSTek Computer        | 3        | 2.73%   |
| Unknown                 | 2        | 1.82%   |
| Toshiba                 | 2        | 1.82%   |
| Philips                 | 2        | 1.82%   |
| NEC Computers           | 2        | 1.82%   |
| Unknown                 | 2        | 1.82%   |
| ___                     | 1        | 0.91%   |
| Valve                   | 1        | 0.91%   |
| Sony                    | 1        | 0.91%   |
| Sceptre Tech            | 1        | 0.91%   |
| PNP                     | 1        | 0.91%   |
| Onkyo                   | 1        | 0.91%   |
| MStar                   | 1        | 0.91%   |
| MSI                     | 1        | 0.91%   |
| Microstep               | 1        | 0.91%   |
| Mi                      | 1        | 0.91%   |
| LYC                     | 1        | 0.91%   |
| LG Electronics          | 1        | 0.91%   |
| KTC                     | 1        | 0.91%   |
| HannStar                | 1        | 0.91%   |
| Gigabyte Technology     | 1        | 0.91%   |
| Gateway                 | 1        | 0.91%   |
| Chi Mei Optoelectronics | 1        | 0.91%   |
| Belinea                 | 1        | 0.91%   |
| Apple                   | 1        | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 5        | 4.13%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 1.65%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 2        | 1.65%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 2        | 1.65%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2        | 1.65%   |
| Unknown                                                                 | 2        | 1.65%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 0.83%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch              | 1        | 0.83%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch           | 1        | 0.83%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1        | 0.83%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1        | 0.83%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                  | 1        | 0.83%   |
| ViewSonic LCD Monitor VSC2034 2560x1440 600x340mm 27.2-inch             | 1        | 0.83%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.83%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                        | 1        | 0.83%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.83%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                    | 1        | 0.83%   |
| Toshiba 32FHD_LCD_TV TSB3700 1920x1080 700x400mm 31.7-inch              | 1        | 0.83%   |
| Sony SDMU27M90*30 SNY075A 3840x2160 596x335mm 26.9-inch                 | 1        | 0.83%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.83%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch    | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch    | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM0194 1280x1024 376x301mm 19.0-inch    | 1        | 0.83%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1        | 0.83%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1        | 0.83%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.83%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch     | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM0357 1920x1080                       | 1        | 0.83%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 0.83%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch      | 1        | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 0.83%   |
| PNP LCD Monitor PNP0801 1280x960                                        | 1        | 0.83%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 0.83%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                 | 1        | 0.83%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                    | 1        | 0.83%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch            | 1        | 0.83%   |
| NEC Computers 70GX2 NEC6691 1280x1024 338x270mm 17.0-inch               | 1        | 0.83%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                          | 1        | 0.83%   |
| MSI MAG241C MSI3EA2 1920x1080 521x293mm 23.5-inch                       | 1        | 0.83%   |
| Microstep LCD Monitor MSI MPG27CQ 2560x1440                             | 1        | 0.83%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                        | 1        | 0.83%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                         | 1        | 0.83%   |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                          | 1        | 0.83%   |
| LG Electronics LCD Monitor LG HDR 4K                                    | 1        | 0.83%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                    | 1        | 0.83%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                       | 1        | 0.83%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch                | 1        | 0.83%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                | 1        | 0.83%   |
| KTC Q2702S KTC2700 2560x1440 597x336mm 27.0-inch                        | 1        | 0.83%   |
| Iiyama PLG2488H IVM6127 1920x1080 530x300mm 24.0-inch                   | 1        | 0.83%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                    | 1        | 0.83%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 0.83%   |
| Iiyama PL2760Q IVM663D 2560x1440 600x340mm 27.2-inch                    | 1        | 0.83%   |
| Iiyama PL2480H IVM610B 1920x1080 521x293mm 23.5-inch                    | 1        | 0.83%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch            | 1        | 0.83%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch           | 1        | 0.83%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch           | 1        | 0.83%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch               | 1        | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 36.19%  |
| 2560x1440 (QHD)    | 25       | 23.81%  |
| 3840x2160 (4K)     | 13       | 12.38%  |
| 1280x1024 (SXGA)   | 5        | 4.76%   |
| 3440x1440          | 4        | 3.81%   |
| 1920x1200 (WUXGA)  | 3        | 2.86%   |
| Unknown            | 3        | 2.86%   |
| 3840x1080          | 2        | 1.9%    |
| 1440x900 (WXGA+)   | 2        | 1.9%    |
| 7680x2160          | 1        | 0.95%   |
| 2560x1080          | 1        | 0.95%   |
| 2288x1287          | 1        | 0.95%   |
| 2048x1152          | 1        | 0.95%   |
| 1680x1050 (WSXGA+) | 1        | 0.95%   |
| 1600x900 (HD+)     | 1        | 0.95%   |
| 1366x768 (WXGA)    | 1        | 0.95%   |
| 1360x768           | 1        | 0.95%   |
| 1280x960           | 1        | 0.95%   |
| 1024x768 (XGA)     | 1        | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 33       | 29.73%  |
| 23      | 18       | 16.22%  |
| 24      | 11       | 9.91%   |
| 21      | 9        | 8.11%   |
| Unknown | 8        | 7.21%   |
| 34      | 5        | 4.5%    |
| 19      | 4        | 3.6%    |
| 17      | 4        | 3.6%    |
| 25      | 3        | 2.7%    |
| 84      | 2        | 1.8%    |
| 72      | 2        | 1.8%    |
| 49      | 2        | 1.8%    |
| 31      | 2        | 1.8%    |
| 15      | 2        | 1.8%    |
| 14      | 2        | 1.8%    |
| 142     | 1        | 0.9%    |
| 28      | 1        | 0.9%    |
| 26      | 1        | 0.9%    |
| 20      | 1        | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 54       | 53.47%  |
| 401-500        | 11       | 10.89%  |
| Unknown        | 8        | 7.92%   |
| 301-350        | 7        | 6.93%   |
| 601-700        | 6        | 5.94%   |
| 701-800        | 5        | 4.95%   |
| 1501-2000      | 4        | 3.96%   |
| 351-400        | 2        | 1.98%   |
| 1001-1500      | 2        | 1.98%   |
| More than 2000 | 1        | 0.99%   |
| 201-300        | 1        | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 63       | 70.79%  |
| 16/10   | 7        | 7.87%   |
| 5/4     | 5        | 5.62%   |
| 21/9    | 5        | 5.62%   |
| Unknown | 5        | 5.62%   |
| 4/3     | 2        | 2.25%   |
| 32/9    | 1        | 1.12%   |
| 1.00    | 1        | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 33       | 30.84%  |
| 201-250        | 29       | 27.1%   |
| 351-500        | 8        | 7.48%   |
| Unknown        | 8        | 7.48%   |
| 251-300        | 7        | 6.54%   |
| 151-200        | 7        | 6.54%   |
| More than 1000 | 6        | 5.61%   |
| 141-150        | 4        | 3.74%   |
| 101-110        | 2        | 1.87%   |
| 81-90          | 1        | 0.93%   |
| 501-1000       | 1        | 0.93%   |
| 91-100         | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 42       | 42%     |
| 101-120 | 33       | 33%     |
| 121-160 | 8        | 8%      |
| Unknown | 8        | 8%      |
| 161-240 | 6        | 6%      |
| 1-50    | 3        | 3%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 51.16%  |
| 2     | 27       | 31.4%   |
| 0     | 7        | 8.14%   |
| 3     | 5        | 5.81%   |
| 4     | 3        | 3.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 51       | 43.59%  |
| Realtek Semiconductor    | 40       | 34.19%  |
| Aquantia                 | 7        | 5.98%   |
| Qualcomm Atheros         | 5        | 4.27%   |
| Microsoft                | 2        | 1.71%   |
| Marvell Technology Group | 2        | 1.71%   |
| Broadcom                 | 2        | 1.71%   |
| Raspberry Pi             | 1        | 0.85%   |
| Ralink Technology        | 1        | 0.85%   |
| NetGear                  | 1        | 0.85%   |
| MediaTek                 | 1        | 0.85%   |
| Dresden Elektronik       | 1        | 0.85%   |
| DisplayLink              | 1        | 0.85%   |
| Broadcom Limited         | 1        | 0.85%   |
| Apple                    | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 27       | 18.62%  |
| Intel Wi-Fi 6 AX200                                                 | 14       | 9.66%   |
| Realtek RTL8125 2.5GbE Controller                                   | 12       | 8.28%   |
| Intel I211 Gigabit Network Connection                               | 12       | 8.28%   |
| Intel Ethernet Controller I225-V                                    | 9        | 6.21%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 4.14%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 3.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 2.76%   |
| Intel Wireless-AC 9260                                              | 3        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 2.07%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 1.38%   |
| Microsoft XBOX ACC                                                  | 2        | 1.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 1.38%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.38%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.69%   |
| Raspberry Pi Pico                                                   | 1        | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.69%   |
| NetGear A6210                                                       | 1        | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.69%   |
| Intel Wireless 7265                                                 | 1        | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 0.69%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.69%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.69%   |
| Intel Ethernet Connection I218-V                                    | 1        | 0.69%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 0.69%   |
| Intel 82575GB Gigabit Network Connection                            | 1        | 0.69%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                       | 1        | 0.69%   |
| DisplayLink Dell D3100 Docking Station                              | 1        | 0.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 0.69%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 0.69%   |
| Aquantia Ethernet controller                                        | 1        | 0.69%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                     | 1        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 30       | 69.77%  |
| Qualcomm Atheros      | 4        | 9.3%    |
| Microsoft             | 2        | 4.65%   |
| Broadcom              | 2        | 4.65%   |
| Realtek Semiconductor | 1        | 2.33%   |
| Ralink Technology     | 1        | 2.33%   |
| NetGear               | 1        | 2.33%   |
| MediaTek              | 1        | 2.33%   |
| Broadcom Limited      | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 14       | 31.82%  |
| Intel Wireless-AC 9260                                              | 3        | 6.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 6.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 6.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 4.55%   |
| Microsoft XBOX ACC                                                  | 2        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 4.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 2.27%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 2.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 2.27%   |
| NetGear A6210                                                       | 1        | 2.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 2.27%   |
| Intel Wireless 7265                                                 | 1        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 2.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 2.27%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 41       | 43.62%  |
| Realtek Semiconductor    | 40       | 42.55%  |
| Aquantia                 | 7        | 7.45%   |
| Qualcomm Atheros         | 2        | 2.13%   |
| Marvell Technology Group | 2        | 2.13%   |
| DisplayLink              | 1        | 1.06%   |
| Apple                    | 1        | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 27       | 27.27%  |
| Realtek RTL8125 2.5GbE Controller                                   | 12       | 12.12%  |
| Intel I211 Gigabit Network Connection                               | 12       | 12.12%  |
| Intel Ethernet Controller I225-V                                    | 9        | 9.09%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 6.06%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 5.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 4.04%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 2.02%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 2.02%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 1.01%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 1.01%   |
| Intel I210 Gigabit Network Connection                               | 1        | 1.01%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 1.01%   |
| Intel Ethernet Connection I218-V                                    | 1        | 1.01%   |
| Intel Ethernet Connection I217-V                                    | 1        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 1.01%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 1.01%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 1.01%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 1.01%   |
| Intel 82575GB Gigabit Network Connection                            | 1        | 1.01%   |
| DisplayLink Dell D3100 Docking Station                              | 1        | 1.01%   |
| Aquantia Ethernet controller                                        | 1        | 1.01%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                     | 1        | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 66.13%  |
| WiFi     | 40       | 32.26%  |
| Modem    | 2        | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 72       | 83.72%  |
| WiFi     | 14       | 16.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 45.88%  |
| 2     | 31       | 36.47%  |
| 3     | 10       | 11.76%  |
| 4     | 2        | 2.35%   |
| 0     | 2        | 2.35%   |
| 5     | 1        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 71.43%  |
| Yes  | 24       | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 70.45%  |
| Cambridge Silicon Radio         | 6        | 13.64%  |
| Realtek Semiconductor           | 1        | 2.27%   |
| Qualcomm Atheros Communications | 1        | 2.27%   |
| MediaTek                        | 1        | 2.27%   |
| Foxconn / Hon Hai               | 1        | 2.27%   |
| Broadcom                        | 1        | 2.27%   |
| ASUSTek Computer                | 1        | 2.27%   |
| Apple                           | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 15       | 34.09%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 13.64%  |
| Intel AX201 Bluetooth                               | 4        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6.82%   |
| Intel AX210 Bluetooth                               | 3        | 6.82%   |
| Realtek Bluetooth Radio                             | 1        | 2.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2.27%   |
| MediaTek Wireless_Device                            | 1        | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.27%   |
| Intel Bluetooth wireless interface                  | 1        | 2.27%   |
| Intel Bluetooth Device                              | 1        | 2.27%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 2.27%   |
| Broadcom BCM20702A0                                 | 1        | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.27%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 58       | 31.35%  |
| Intel                                | 35       | 18.92%  |
| Nvidia                               | 32       | 17.3%   |
| C-Media Electronics                  | 8        | 4.32%   |
| Thesycon Systemsoftware & Consulting | 4        | 2.16%   |
| ASUSTek Computer                     | 4        | 2.16%   |
| SteelSeries ApS                      | 3        | 1.62%   |
| Realtek Semiconductor                | 3        | 1.62%   |
| Creative Labs                        | 3        | 1.62%   |
| Yamaha                               | 2        | 1.08%   |
| Sony                                 | 2        | 1.08%   |
| RODE Microphones                     | 2        | 1.08%   |
| Razer USA                            | 2        | 1.08%   |
| Logitech                             | 2        | 1.08%   |
| Creative Technology                  | 2        | 1.08%   |
| Blue Microphones                     | 2        | 1.08%   |
| AudioQuest                           | 2        | 1.08%   |
| Audio-Technica                       | 2        | 1.08%   |
| Valve Software                       | 1        | 0.54%   |
| Unknown                              | 1        | 0.54%   |
| TEAC                                 | 1        | 0.54%   |
| Sennheiser Communications            | 1        | 0.54%   |
| SAVITECH                             | 1        | 0.54%   |
| MAG Technology                       | 1        | 0.54%   |
| JOUNIVO                              | 1        | 0.54%   |
| JMTek                                | 1        | 0.54%   |
| Huawei Technologies                  | 1        | 0.54%   |
| GN Netcom                            | 1        | 0.54%   |
| Generalplus Technology               | 1        | 0.54%   |
| Focusrite-Novation                   | 1        | 0.54%   |
| FiiO Electronics Technology          | 1        | 0.54%   |
| FIFINE Microphones                   | 1        | 0.54%   |
| Corsair                              | 1        | 0.54%   |
| BEHRINGER International              | 1        | 0.54%   |
| Astro Gaming                         | 1        | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 23       | 10.7%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 9.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.65%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9        | 4.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 3.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.79%   |
| Thesycon Systemsoftware & Consulting U90                                   | 4        | 1.86%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.4%    |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.4%    |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 1.4%    |
| ASUSTek Computer USB Audio                                                 | 3        | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.4%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.93%   |
| Realtek Semiconductor USB Condenser Microphone                             | 2        | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.93%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.93%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.93%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.93%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 0.93%   |
| C-Media Electronics Blue Snowball                                          | 2        | 0.93%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 0.93%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 0.47%   |
| Yamaha Steinberg UR22C                                                     | 1        | 0.47%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1        | 0.47%   |
| Unknown Realtek USB Audio Rear                                             | 1        | 0.47%   |
| Unknown Realtek USB Audio Front                                            | 1        | 0.47%   |
| TEAC UD-503                                                                | 1        | 0.47%   |
| SteelSeries ApS SteelSeries Arctis 9                                       | 1        | 0.47%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.47%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1        | 0.47%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                          | 1        | 0.47%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.47%   |
| RODE Microphones RODE VideoMic NTG                                         | 1        | 0.47%   |
| RODE Microphones RODE NT-USB                                               | 1        | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.47%   |
| Razer USA Razer Seiren Mini                                                | 1        | 0.47%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.47%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.47%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.47%   |
| MAG Technology ARC AMP DAC                                                 | 1        | 0.47%   |
| Logitech Z-5 Speakers                                                      | 1        | 0.47%   |
| Logitech Yeti X                                                            | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 17       | 19.32%  |
| Crucial             | 16       | 18.18%  |
| Corsair             | 15       | 17.05%  |
| Kingston            | 14       | 15.91%  |
| Unknown             | 6        | 6.82%   |
| Samsung Electronics | 5        | 5.68%   |
| Patriot             | 3        | 3.41%   |
| Team                | 2        | 2.27%   |
| SK hynix            | 2        | 2.27%   |
| Micron Technology   | 2        | 2.27%   |
| A-DATA Technology   | 2        | 2.27%   |
| Patriot Memory      | 1        | 1.14%   |
| Nanya Technology    | 1        | 1.14%   |
| GOODRAM             | 1        | 1.14%   |
| Unknown             | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 3        | 3.13%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s         | 2        | 2.08%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s       | 2        | 2.08%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 2        | 2.08%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s      | 2        | 2.08%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s   | 2        | 2.08%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s   | 2        | 2.08%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s     | 2        | 2.08%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s     | 2        | 2.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                  | 1        | 1.04%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 1.04%   |
| Unknown RAM Module 512MB DIMM SDRAM                        | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                   | 1        | 1.04%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 1        | 1.04%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                 | 1        | 1.04%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s      | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s         | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s        | 1        | 1.04%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.04%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 1.04%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s      | 1        | 1.04%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s       | 1        | 1.04%   |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s       | 1        | 1.04%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 1.04%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s       | 1        | 1.04%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s        | 1        | 1.04%   |
| Patriot RAM 1600 CL9 Series 4GB DIMM DDR3 1600MT/s         | 1        | 1.04%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s | 1        | 1.04%   |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s         | 1        | 1.04%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s         | 1        | 1.04%   |
| Micron RAM 16JTF51264AZ-1G4D 4GB DIMM DDR3 1333MT/s        | 1        | 1.04%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 1.04%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s        | 1        | 1.04%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s        | 1        | 1.04%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 1.04%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 1        | 1.04%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s           | 1        | 1.04%   |
| Kingston RAM HP698651-154-KEB 8GB DIMM DDR3 1333MT/s       | 1        | 1.04%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s       | 1        | 1.04%   |
| Kingston RAM 99U5471-039.A 8GB DIMM DDR3 800MT/s           | 1        | 1.04%   |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3334MT/s      | 1        | 1.04%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s       | 1        | 1.04%   |
| GOODRAM RAM GR1600D364L11/2G 2GB DIMM DDR3 1333MT/s        | 1        | 1.04%   |
| G.Skill RAM F4-4400C19-32GTRS 32GB DIMM DDR4 2667MT/s      | 1        | 1.04%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s      | 1        | 1.04%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s     | 1        | 1.04%   |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s        | 1        | 1.04%   |
| G.Skill RAM F4-3400C16-8GTZ 8GB DIMM DDR4 2197MT/s         | 1        | 1.04%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 1        | 1.04%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s      | 1        | 1.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 1        | 1.04%   |
| G.Skill RAM F4-3200C16-16GTZN 16GB DIMM DDR4 3200MT/s      | 1        | 1.04%   |
| G.Skill RAM F4-3200C14-8GTZR 8192MB DIMM DDR4 3200MT/s     | 1        | 1.04%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s         | 1        | 1.04%   |
| G.Skill RAM F4-3200C14-32GVK 32GB DIMM DDR4 2666MT/s       | 1        | 1.04%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3000MT/s        | 1        | 1.04%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s        | 1        | 1.04%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1867MT/s    | 1        | 1.04%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s      | 1        | 1.04%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s    | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 63       | 81.82%  |
| DDR3    | 10       | 12.99%  |
| SDRAM   | 1        | 1.3%    |
| DDR5    | 1        | 1.3%    |
| DDR2    | 1        | 1.3%    |
| Unknown | 1        | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 77       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 36.78%  |
| 16384 | 30       | 34.48%  |
| 32768 | 13       | 14.94%  |
| 4096  | 7        | 8.05%   |
| 2048  | 3        | 3.45%   |
| 1024  | 1        | 1.15%   |
| 512   | 1        | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 25       | 28.41%  |
| 3600    | 11       | 12.5%   |
| 2133    | 6        | 6.82%   |
| 1600    | 6        | 6.82%   |
| 3400    | 4        | 4.55%   |
| 2667    | 4        | 4.55%   |
| 1333    | 4        | 4.55%   |
| 3733    | 3        | 3.41%   |
| 3466    | 3        | 3.41%   |
| 3000    | 3        | 3.41%   |
| 4000    | 2        | 2.27%   |
| 3866    | 2        | 2.27%   |
| 3666    | 2        | 2.27%   |
| 2400    | 2        | 2.27%   |
| 4800    | 1        | 1.14%   |
| 3334    | 1        | 1.14%   |
| 2933    | 1        | 1.14%   |
| 2866    | 1        | 1.14%   |
| 2733    | 1        | 1.14%   |
| 2666    | 1        | 1.14%   |
| 2197    | 1        | 1.14%   |
| 1867    | 1        | 1.14%   |
| 800     | 1        | 1.14%   |
| 667     | 1        | 1.14%   |
| Unknown | 1        | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP LaserJet M14-M17 | 1        | 50%     |
| Canon LiDE 400      | 1        | 50%     |

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
| Logitech                      | 11       | 45.83%  |
| Sunplus Innovation Technology | 3        | 12.5%   |
| YGTek                         | 1        | 4.17%   |
| Xiaomi                        | 1        | 4.17%   |
| Valve Software                | 1        | 4.17%   |
| Ruision                       | 1        | 4.17%   |
| Microdia                      | 1        | 4.17%   |
| MacroSilicon                  | 1        | 4.17%   |
| Generalplus Technology        | 1        | 4.17%   |
| Cubeternet                    | 1        | 4.17%   |
| Creative Technology           | 1        | 4.17%   |
| Chicony Electronics           | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 2        | 8.33%   |
| Logitech BRIO Ultra HD Webcam                                       | 2        | 8.33%   |
| YGTek Webcam                                                        | 1        | 4.17%   |
| Xiaomi Redmi Note 10 Pro                                            | 1        | 4.17%   |
| Valve Software 3D Camera                                            | 1        | 4.17%   |
| Sunplus NexiGo N940 2K Webcam                                       | 1        | 4.17%   |
| Sunplus Full HD webcam                                              | 1        | 4.17%   |
| Sunplus Canyon CNS-CWC5 Webcam                                      | 1        | 4.17%   |
| Ruision UVC Camera                                                  | 1        | 4.17%   |
| Microdia USB 2.0 Camera                                             | 1        | 4.17%   |
| MacroSilicon USB Video                                              | 1        | 4.17%   |
| Logitech Webcam C270                                                | 1        | 4.17%   |
| Logitech Webcam C110                                                | 1        | 4.17%   |
| Logitech StreamCam                                                  | 1        | 4.17%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1        | 4.17%   |
| Logitech Logi 4K Stream Edition                                     | 1        | 4.17%   |
| Logitech HD Webcam C615                                             | 1        | 4.17%   |
| Logitech HD Webcam C510                                             | 1        | 4.17%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 4.17%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 4.17%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 4.17%   |
| Chicony Gateway Webcam                                              | 1        | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Yubico.com | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Yubico.com Yubikey 4 U2F+CCID | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 58       | 65.91%  |
| 1     | 18       | 20.45%  |
| 2     | 7        | 7.95%   |
| 3     | 3        | 3.41%   |
| 4     | 2        | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 11       | 26.19%  |
| Net/wireless             | 8        | 19.05%  |
| Sound                    | 5        | 11.9%   |
| Graphics card            | 5        | 11.9%   |
| Bluetooth                | 4        | 9.52%   |
| Modem                    | 2        | 4.76%   |
| Storage/raid             | 1        | 2.38%   |
| Storage/ide              | 1        | 2.38%   |
| Storage/ata              | 1        | 2.38%   |
| Network                  | 1        | 2.38%   |
| Multimedia controller    | 1        | 2.38%   |
| Fingerprint reader       | 1        | 2.38%   |
| Camera                   | 1        | 2.38%   |

