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

Total: 81

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.41-gentoo               | 4        | 6.45%   |
| 5.17.1-gentoo-r1             | 3        | 4.84%   |
| 5.17.0-gentoo                | 2        | 3.23%   |
| 5.16.11-gentoo-x86_64        | 2        | 3.23%   |
| 5.15.10-gentoo               | 2        | 3.23%   |
| 5.14.13-gentoo               | 2        | 3.23%   |
| 5.14.12-gentoo               | 2        | 3.23%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 1.61%   |
| 5.18.6-gentoo-x86_64         | 1        | 1.61%   |
| 5.18.6-gentoo                | 1        | 1.61%   |
| 5.18.1-gentoo-r2             | 1        | 1.61%   |
| 5.18.0-gentoo                | 1        | 1.61%   |
| 5.17.9-gentoo-x86_64         | 1        | 1.61%   |
| 5.17.9-gentoo-dist           | 1        | 1.61%   |
| 5.17.8-gentoo-x86_64         | 1        | 1.61%   |
| 5.17.7-gentoo-limelight      | 1        | 1.61%   |
| 5.17.7-gentoo-dist           | 1        | 1.61%   |
| 5.17.6-gentoo-x86_64         | 1        | 1.61%   |
| 5.17.3-gentoo-11-02-22       | 1        | 1.61%   |
| 5.17.2-gentoo-limelight      | 1        | 1.61%   |
| 5.17.2-gentoo                | 1        | 1.61%   |
| 5.17.1-gentoo-r1-x86_64      | 1        | 1.61%   |
| 5.17.0-gentoo-x86_64         | 1        | 1.61%   |
| 5.16.8-gentoo-x86_64         | 1        | 1.61%   |
| 5.16.7-tkg-cacule            | 1        | 1.61%   |
| 5.16.5-gentoo-dist           | 1        | 1.61%   |
| 5.16.4-gentoo                | 1        | 1.61%   |
| 5.16.2-gentoo                | 1        | 1.61%   |
| 5.16.15                      | 1        | 1.61%   |
| 5.16.14-gentoo-x86_64        | 1        | 1.61%   |
| 5.16.14-gentoo-girlhog       | 1        | 1.61%   |
| 5.16.13-gentoo               | 1        | 1.61%   |
| 5.16.10-gentoo-x86_64        | 1        | 1.61%   |
| 5.15.6-gentoo                | 1        | 1.61%   |
| 5.15.41-gentoo-x86_64        | 1        | 1.61%   |
| 5.15.4-gentoo-deimos         | 1        | 1.61%   |
| 5.15.32-gentoo-r1            | 1        | 1.61%   |
| 5.15.2-gentoo20210917        | 1        | 1.61%   |
| 5.15.2-gentoo-x86_64         | 1        | 1.61%   |
| 5.15.16-gentoo-dist          | 1        | 1.61%   |
| 5.15.12-gentoo-x86_64        | 1        | 1.61%   |
| 5.15.11-gentoo-x86_64        | 1        | 1.61%   |
| 5.15.1-gentoo-x86_64         | 1        | 1.61%   |
| 5.15.0-gentoo-x86_64         | 1        | 1.61%   |
| 5.14.6                       | 1        | 1.61%   |
| 5.14.15-gentoo20210917       | 1        | 1.61%   |
| 5.14.14-gentoo-x86_64        | 1        | 1.61%   |
| 5.14.14-gentoo               | 1        | 1.61%   |
| 5.14.11-zen1                 | 1        | 1.61%   |
| 5.10.84-gentoo-112-overlayfs | 1        | 1.61%   |
| 5.10.74-gentoo-x86_64        | 1        | 1.61%   |
| 4.9.16-gentoo                | 1        | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.41 | 5        | 8.06%   |
| 5.17.1  | 4        | 6.45%   |
| 5.17.0  | 3        | 4.84%   |
| 5.18.6  | 2        | 3.23%   |
| 5.17.9  | 2        | 3.23%   |
| 5.17.7  | 2        | 3.23%   |
| 5.17.2  | 2        | 3.23%   |
| 5.16.14 | 2        | 3.23%   |
| 5.16.11 | 2        | 3.23%   |
| 5.15.2  | 2        | 3.23%   |
| 5.15.10 | 2        | 3.23%   |
| 5.14.14 | 2        | 3.23%   |
| 5.14.13 | 2        | 3.23%   |
| 5.14.12 | 2        | 3.23%   |
| 6.0.0   | 1        | 1.61%   |
| 5.18.1  | 1        | 1.61%   |
| 5.18.0  | 1        | 1.61%   |
| 5.17.8  | 1        | 1.61%   |
| 5.17.6  | 1        | 1.61%   |
| 5.17.3  | 1        | 1.61%   |
| 5.16.8  | 1        | 1.61%   |
| 5.16.7  | 1        | 1.61%   |
| 5.16.5  | 1        | 1.61%   |
| 5.16.4  | 1        | 1.61%   |
| 5.16.2  | 1        | 1.61%   |
| 5.16.15 | 1        | 1.61%   |
| 5.16.13 | 1        | 1.61%   |
| 5.16.10 | 1        | 1.61%   |
| 5.15.6  | 1        | 1.61%   |
| 5.15.4  | 1        | 1.61%   |
| 5.15.32 | 1        | 1.61%   |
| 5.15.16 | 1        | 1.61%   |
| 5.15.12 | 1        | 1.61%   |
| 5.15.11 | 1        | 1.61%   |
| 5.15.1  | 1        | 1.61%   |
| 5.15.0  | 1        | 1.61%   |
| 5.14.6  | 1        | 1.61%   |
| 5.14.15 | 1        | 1.61%   |
| 5.14.11 | 1        | 1.61%   |
| 5.10.84 | 1        | 1.61%   |
| 5.10.74 | 1        | 1.61%   |
| 4.9.16  | 1        | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 17       | 28.81%  |
| 5.17    | 14       | 23.73%  |
| 5.16    | 11       | 18.64%  |
| 5.14    | 9        | 15.25%  |
| 5.18    | 4        | 6.78%   |
| 5.10    | 2        | 3.39%   |
| 6.0     | 1        | 1.69%   |
| 4.9     | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 52       | 98.11%  |
| ppc    | 1        | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 19       | 35.19%  |
| Unknown | 14       | 25.93%  |
| GNOME   | 11       | 20.37%  |
| XFCE    | 4        | 7.41%   |
| MATE    | 2        | 3.7%    |
| DWM     | 2        | 3.7%    |
| LXQt    | 1        | 1.85%   |
| KDE     | 1        | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 27       | 49.09%  |
| Wayland | 12       | 21.82%  |
| Tty     | 9        | 16.36%  |
| Unknown | 7        | 12.73%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 44.44%  |
| SDDM    | 16       | 29.63%  |
| GDM     | 6        | 11.11%  |
| LightDM | 5        | 9.26%   |
| XDM     | 1        | 1.85%   |
| SLiM    | 1        | 1.85%   |
| LXDM    | 1        | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 21       | 39.62%  |
| en_GB   | 7        | 13.21%  |
| Unknown | 6        | 11.32%  |
| ru_RU   | 3        | 5.66%   |
| pl_PL   | 3        | 5.66%   |
| de_DE   | 3        | 5.66%   |
| C.UTF8  | 3        | 5.66%   |
| sl_SI   | 1        | 1.89%   |
| fr_FR   | 1        | 1.89%   |
| es_ES   | 1        | 1.89%   |
| en_CA   | 1        | 1.89%   |
| el_GR   | 1        | 1.89%   |
| de_CH   | 1        | 1.89%   |
| C       | 1        | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 46       | 83.64%  |
| BIOS | 9        | 16.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 28       | 52.83%  |
| Btrfs   | 15       | 28.3%   |
| F2fs    | 5        | 9.43%   |
| Xfs     | 2        | 3.77%   |
| Zfs     | 1        | 1.89%   |
| XXXXXXX | 1        | 1.89%   |
| XXX     | 1        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 49       | 90.74%  |
| Unknown | 5        | 9.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 56.6%   |
| Yes       | 23       | 43.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 64.15%  |
| Yes       | 19       | 35.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 45.28%  |
| MSI                 | 9        | 16.98%  |
| Gigabyte Technology | 7        | 13.21%  |
| ASRock              | 6        | 11.32%  |
| Dell                | 3        | 5.66%   |
| Pegatron            | 1        | 1.89%   |
| Fujitsu             | 1        | 1.89%   |
| EVGA                | 1        | 1.89%   |
| Unknown             | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS Z170-A                       | 2        | 3.77%   |
| ASUS TUF Gaming B550-PLUS         | 2        | 3.77%   |
| Pegatron 810-170st                | 1        | 1.89%   |
| MSI MS-7D31                       | 1        | 1.89%   |
| MSI MS-7D25                       | 1        | 1.89%   |
| MSI MS-7C94                       | 1        | 1.89%   |
| MSI MS-7C56                       | 1        | 1.89%   |
| MSI MS-7C37                       | 1        | 1.89%   |
| MSI MS-7B98                       | 1        | 1.89%   |
| MSI MS-7B86                       | 1        | 1.89%   |
| MSI MS-7B17                       | 1        | 1.89%   |
| MSI MS-7996                       | 1        | 1.89%   |
| Gigabyte Z87X-UD3H                | 1        | 1.89%   |
| Gigabyte Z590 UD                  | 1        | 1.89%   |
| Gigabyte Z490 UD                  | 1        | 1.89%   |
| Gigabyte X570 AORUS MASTER        | 1        | 1.89%   |
| Gigabyte H470 HD3                 | 1        | 1.89%   |
| Gigabyte B450M S2H                | 1        | 1.89%   |
| Gigabyte AB350-Gaming             | 1        | 1.89%   |
| Fujitsu D3417-B2 S26361-D3417-B2  | 1        | 1.89%   |
| EVGA Z390 DARK                    | 1        | 1.89%   |
| Dell XPS 8700                     | 1        | 1.89%   |
| Dell OptiPlex 790                 | 1        | 1.89%   |
| Dell OptiPlex 7080                | 1        | 1.89%   |
| ASUS Z170 PRO GAMING              | 1        | 1.89%   |
| ASUS TUF Gaming Z690-PLUS WIFI D4 | 1        | 1.89%   |
| ASUS TUF Gaming X570-PRO          | 1        | 1.89%   |
| ASUS TUF Gaming X570-PLUS         | 1        | 1.89%   |
| ASUS TUF B450-PLUS GAMING         | 1        | 1.89%   |
| ASUS ROG ZENITH II EXTREME        | 1        | 1.89%   |
| ASUS ROG STRIX Z390-E GAMING      | 1        | 1.89%   |
| ASUS ROG STRIX Z370-H GAMING      | 1        | 1.89%   |
| ASUS ROG STRIX X570-E GAMING      | 1        | 1.89%   |
| ASUS ROG STRIX B550-F GAMING      | 1        | 1.89%   |
| ASUS ROG STRIX B450-F GAMING      | 1        | 1.89%   |
| ASUS ROG Maximus XIII APEX        | 1        | 1.89%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 1.89%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 1.89%   |
| ASUS PRIME X570-PRO               | 1        | 1.89%   |
| ASUS PRIME X570-P                 | 1        | 1.89%   |
| ASUS PRIME H570M-PLUS             | 1        | 1.89%   |
| ASUS P6X58D-E                     | 1        | 1.89%   |
| ASUS P5LD2-Deluxe                 | 1        | 1.89%   |
| ASUS M3A78-CM                     | 1        | 1.89%   |
| ASRock Z170A-X1                   | 1        | 1.89%   |
| ASRock X370 Killer SLI/ac         | 1        | 1.89%   |
| ASRock X370 Gaming X              | 1        | 1.89%   |
| ASRock H110M-HDV R3.0             | 1        | 1.89%   |
| ASRock B450 Gaming K4             | 1        | 1.89%   |
| ASRock AB350M Pro4                | 1        | 1.89%   |
| Unknown                           | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 9        | 16.98%  |
| ASUS TUF              | 6        | 11.32%  |
| ASUS PRIME            | 3        | 5.66%   |
| Dell OptiPlex         | 2        | 3.77%   |
| ASUS Z170-A           | 2        | 3.77%   |
| ASRock X370           | 2        | 3.77%   |
| Pegatron 810-170st    | 1        | 1.89%   |
| MSI MS-7D31           | 1        | 1.89%   |
| MSI MS-7D25           | 1        | 1.89%   |
| MSI MS-7C94           | 1        | 1.89%   |
| MSI MS-7C56           | 1        | 1.89%   |
| MSI MS-7C37           | 1        | 1.89%   |
| MSI MS-7B98           | 1        | 1.89%   |
| MSI MS-7B86           | 1        | 1.89%   |
| MSI MS-7B17           | 1        | 1.89%   |
| MSI MS-7996           | 1        | 1.89%   |
| Gigabyte Z87X-UD3H    | 1        | 1.89%   |
| Gigabyte Z590         | 1        | 1.89%   |
| Gigabyte Z490         | 1        | 1.89%   |
| Gigabyte X570         | 1        | 1.89%   |
| Gigabyte H470         | 1        | 1.89%   |
| Gigabyte B450M        | 1        | 1.89%   |
| Gigabyte AB350-Gaming | 1        | 1.89%   |
| Fujitsu D3417-B2      | 1        | 1.89%   |
| EVGA Z390             | 1        | 1.89%   |
| Dell XPS              | 1        | 1.89%   |
| ASUS Z170             | 1        | 1.89%   |
| ASUS P6X58D-E         | 1        | 1.89%   |
| ASUS P5LD2-Deluxe     | 1        | 1.89%   |
| ASUS M3A78-CM         | 1        | 1.89%   |
| ASRock Z170A-X1       | 1        | 1.89%   |
| ASRock H110M-HDV      | 1        | 1.89%   |
| ASRock B450           | 1        | 1.89%   |
| ASRock AB350M         | 1        | 1.89%   |
| Unknown               | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 10       | 18.87%  |
| 2019    | 9        | 16.98%  |
| 2021    | 7        | 13.21%  |
| 2018    | 6        | 11.32%  |
| 2017    | 6        | 11.32%  |
| 2016    | 3        | 5.66%   |
| 2015    | 3        | 5.66%   |
| 2014    | 2        | 3.77%   |
| 2022    | 1        | 1.89%   |
| 2013    | 1        | 1.89%   |
| 2011    | 1        | 1.89%   |
| 2010    | 1        | 1.89%   |
| 2008    | 1        | 1.89%   |
| 2005    | 1        | 1.89%   |
| Unknown | 1        | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 51       | 94.44%  |
| Enabled  | 3        | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 19       | 35.85%  |
| 64.01-256.0 | 12       | 22.64%  |
| 16.01-24.0  | 11       | 20.75%  |
| 24.01-32.0  | 4        | 7.55%   |
| 8.01-16.0   | 4        | 7.55%   |
| 4.01-8.0    | 1        | 1.89%   |
| 2.01-3.0    | 1        | 1.89%   |
| 0.51-1.0    | 1        | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 19       | 32.76%  |
| 8.01-16.0  | 12       | 20.69%  |
| 2.01-3.0   | 8        | 13.79%  |
| 1.01-2.0   | 7        | 12.07%  |
| 3.01-4.0   | 4        | 6.9%    |
| 16.01-24.0 | 4        | 6.9%    |
| 32.01-64.0 | 1        | 1.72%   |
| 24.01-32.0 | 1        | 1.72%   |
| 0.51-1.0   | 1        | 1.72%   |
| 0.01-0.5   | 1        | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 24.07%  |
| 3      | 11       | 20.37%  |
| 5      | 9        | 16.67%  |
| 1      | 8        | 14.81%  |
| 4      | 6        | 11.11%  |
| 6      | 5        | 9.26%   |
| 7      | 2        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 83.33%  |
| Yes       | 9        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 98.11%  |
| No        | 1        | 1.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 57.41%  |
| Yes       | 23       | 42.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 51.85%  |
| Yes       | 26       | 48.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 28.3%   |
| Poland      | 7        | 13.21%  |
| Russia      | 6        | 11.32%  |
| Germany     | 4        | 7.55%   |
| UK          | 2        | 3.77%   |
| Switzerland | 2        | 3.77%   |
| Spain       | 2        | 3.77%   |
| Canada      | 2        | 3.77%   |
| Slovenia    | 1        | 1.89%   |
| Netherlands | 1        | 1.89%   |
| Mexico      | 1        | 1.89%   |
| Malaysia    | 1        | 1.89%   |
| Ireland     | 1        | 1.89%   |
| India       | 1        | 1.89%   |
| Hong Kong   | 1        | 1.89%   |
| Greece      | 1        | 1.89%   |
| France      | 1        | 1.89%   |
| Czechia     | 1        | 1.89%   |
| Belarus     | 1        | 1.89%   |
| Bangladesh  | 1        | 1.89%   |
| Australia   | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Zurich              | 2        | 3.77%   |
| Warsaw              | 2        | 3.77%   |
| Swansea             | 2        | 3.77%   |
| Moscow              | 2        | 3.77%   |
| Los Angeles         | 2        | 3.77%   |
| Cieszyn             | 2        | 3.77%   |
| Yekaterinburg       | 1        | 1.89%   |
| Vigo                | 1        | 1.89%   |
| Vancouver           | 1        | 1.89%   |
| Ufa                 | 1        | 1.89%   |
| Sydney              | 1        | 1.89%   |
| Svobodnyy           | 1        | 1.89%   |
| Sterling            | 1        | 1.89%   |
| St Louis            | 1        | 1.89%   |
| Seattle             | 1        | 1.89%   |
| Schwieberdingen     | 1        | 1.89%   |
| Redmond             | 1        | 1.89%   |
| Radovljica          | 1        | 1.89%   |
| Orange              | 1        | 1.89%   |
| Ocala               | 1        | 1.89%   |
| Murmansk            | 1        | 1.89%   |
| Morcenx             | 1        | 1.89%   |
| Monroe              | 1        | 1.89%   |
| Mariánské Lázně | 1        | 1.89%   |
| Laziska Gorne       | 1        | 1.89%   |
| Laka                | 1        | 1.89%   |
| Kulmbach            | 1        | 1.89%   |
| Kuala Lumpur        | 1        | 1.89%   |
| Krakow              | 1        | 1.89%   |
| Kensington          | 1        | 1.89%   |
| Kallithea           | 1        | 1.89%   |
| Hyderabad           | 1        | 1.89%   |
| Hyannis             | 1        | 1.89%   |
| Houston             | 1        | 1.89%   |
| Gunzenhausen        | 1        | 1.89%   |
| Gomel               | 1        | 1.89%   |
| Glen Ellyn          | 1        | 1.89%   |
| Fort Collins        | 1        | 1.89%   |
| Essen               | 1        | 1.89%   |
| Dublin              | 1        | 1.89%   |
| Dhaka               | 1        | 1.89%   |
| Ciudad Juárez      | 1        | 1.89%   |
| Central             | 1        | 1.89%   |
| Boucherville        | 1        | 1.89%   |
| Bellaterra          | 1        | 1.89%   |
| Baton Rouge         | 1        | 1.89%   |
| Amstelveen          | 1        | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 54     | 19.84%  |
| WDC                 | 24       | 44     | 19.05%  |
| Seagate             | 18       | 30     | 14.29%  |
| Toshiba             | 7        | 9      | 5.56%   |
| Hitachi             | 6        | 10     | 4.76%   |
| Crucial             | 6        | 13     | 4.76%   |
| SanDisk             | 5        | 6      | 3.97%   |
| Kingston            | 4        | 4      | 3.17%   |
| Intel               | 4        | 5      | 3.17%   |
| Corsair             | 4        | 5      | 3.17%   |
| A-DATA Technology   | 4        | 5      | 3.17%   |
| Goodram             | 3        | 3      | 2.38%   |
| KIOXIA-EXCERIA      | 2        | 3      | 1.59%   |
| HGST                | 2        | 3      | 1.59%   |
| Transcend           | 1        | 1      | 0.79%   |
| Team                | 1        | 2      | 0.79%   |
| SK hynix            | 1        | 2      | 0.79%   |
| Silicon Motion      | 1        | 2      | 0.79%   |
| PNY                 | 1        | 1      | 0.79%   |
| Plextor             | 1        | 2      | 0.79%   |
| Phison              | 1        | 1      | 0.79%   |
| OCZ-VERTEX          | 1        | 1      | 0.79%   |
| LaCie               | 1        | 2      | 0.79%   |
| Kingchuxing         | 1        | 2      | 0.79%   |
| Fujitsu             | 1        | 1      | 0.79%   |
| Apacer              | 1        | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Crucial CT2000MX500SSD1 2TB      | 3        | 1.84%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 1.23%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 1.23%   |
| Toshiba DT01ACA100 1TB           | 2        | 1.23%   |
| Seagate ST4000DM005-2DP166 4TB   | 2        | 1.23%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.23%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 1.23%   |
| Samsung SSD 980 PRO 2TB          | 2        | 1.23%   |
| Samsung SSD 980 PRO 1TB          | 2        | 1.23%   |
| Samsung SSD 980 1TB              | 2        | 1.23%   |
| Samsung SSD 970 EVO Plus 2TB     | 2        | 1.23%   |
| Samsung SSD 970 EVO Plus 250GB   | 2        | 1.23%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.23%   |
| Samsung NVMe SSD Drive 512GB     | 2        | 1.23%   |
| Hitachi HDS723020BLA642 2TB      | 2        | 1.23%   |
| Goodram SSDPR-CL100-480-G2 480GB | 2        | 1.23%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 1.23%   |
| A-DATA SX8200PNP 512GB           | 2        | 1.23%   |
| A-DATA SX8200PNP 1TB             | 2        | 1.23%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.61%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.61%   |
| WDC WDS240G2G0A 240GB SSD        | 1        | 0.61%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.61%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1        | 0.61%   |
| WDC WD60EZRX-00MVLB1 6TB         | 1        | 0.61%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.61%   |
| WDC WD5000AZLX-00JKKA0 500GB     | 1        | 0.61%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.61%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.61%   |
| WDC WD3200AAJS-22RYA0 320GB      | 1        | 0.61%   |
| WDC WD30EFRX-68N32N0 3TB         | 1        | 0.61%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.61%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.61%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.61%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.61%   |
| WDC WD2003FYYS-18W0B0 2TB        | 1        | 0.61%   |
| WDC WD10PURX-64E5EY0 1TB         | 1        | 0.61%   |
| WDC WD10EZEX-60WN4A1 1TB         | 1        | 0.61%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 0.61%   |
| WDC WD10EZEX-22M                 | 1        | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.61%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 0.61%   |
| WDC WD10EADS-00L5B1 1TB          | 1        | 0.61%   |
| WDC WD1002FBYS-18W8B0 1TB        | 1        | 0.61%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 0.61%   |
| Transcend TS512GSSD720 512GB     | 1        | 0.61%   |
| Toshiba TR200 480GB SSD          | 1        | 0.61%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 0.61%   |
| Toshiba HDWR180 8TB              | 1        | 0.61%   |
| Toshiba HDWQ140 4TB              | 1        | 0.61%   |
| Toshiba HDWE150 5TB              | 1        | 0.61%   |
| Team TM8FP2240G 240GB            | 1        | 0.61%   |
| SK hynix PC611 NVMe 512GB        | 1        | 0.61%   |
| Silicon Motion NVME SSD 128GB    | 1        | 0.61%   |
| Silicon Motion 256GB             | 1        | 0.61%   |
| Seagate ST8000NM0055-1RM112 8TB  | 1        | 0.61%   |
| Seagate ST8000DM004-2CX188 8TB   | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 21       | 39     | 39.62%  |
| Seagate | 17       | 29     | 32.08%  |
| Hitachi | 6        | 10     | 11.32%  |
| Toshiba | 5        | 6      | 9.43%   |
| HGST    | 2        | 3      | 3.77%   |
| LaCie   | 1        | 2      | 1.89%   |
| Fujitsu | 1        | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 21     | 31.11%  |
| Crucial             | 5        | 11     | 11.11%  |
| WDC                 | 4        | 4      | 8.89%   |
| SanDisk             | 4        | 5      | 8.89%   |
| Kingston            | 4        | 4      | 8.89%   |
| Goodram             | 3        | 3      | 6.67%   |
| Corsair             | 3        | 4      | 6.67%   |
| Intel               | 2        | 2      | 4.44%   |
| Transcend           | 1        | 1      | 2.22%   |
| Toshiba             | 1        | 2      | 2.22%   |
| PNY                 | 1        | 1      | 2.22%   |
| OCZ-VERTEX          | 1        | 1      | 2.22%   |
| Apacer              | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 90     | 35.24%  |
| SSD  | 35       | 61     | 33.33%  |
| NVMe | 33       | 61     | 31.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 149    | 59.04%  |
| NVMe | 33       | 61     | 39.76%  |
| SAS  | 1        | 2      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 29       | 48     | 33.33%  |
| 1.01-2.0   | 20       | 33     | 22.99%  |
| 0.51-1.0   | 20       | 27     | 22.99%  |
| 3.01-4.0   | 8        | 12     | 9.2%    |
| 4.01-10.0  | 5        | 21     | 5.75%   |
| 2.01-3.0   | 4        | 9      | 4.6%    |
| 10.01-20.0 | 1        | 1      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 13       | 24.07%  |
| 501-1000       | 11       | 20.37%  |
| 251-500        | 8        | 14.81%  |
| 2001-3000      | 7        | 12.96%  |
| 1001-2000      | 7        | 12.96%  |
| 101-250        | 2        | 3.7%    |
| 1-20           | 2        | 3.7%    |
| 51-100         | 2        | 3.7%    |
| 21-50          | 1        | 1.85%   |
| Unknown        | 1        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 21.82%  |
| More than 3000 | 7        | 12.73%  |
| 1001-2000      | 7        | 12.73%  |
| 1-20           | 6        | 10.91%  |
| 501-1000       | 6        | 10.91%  |
| 101-250        | 5        | 9.09%   |
| 21-50          | 4        | 7.27%   |
| 51-100         | 4        | 7.27%   |
| 2001-3000      | 3        | 5.45%   |
| Unknown        | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 3      | 7.14%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1        | 2      | 7.14%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 7.14%   |
| WDC WD1002FBYS-18W8B0 1TB           | 1        | 1      | 7.14%   |
| Transcend TS512GSSD720 512GB        | 1        | 1      | 7.14%   |
| Seagate ST3160023AS 160GB           | 1        | 1      | 7.14%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1      | 7.14%   |
| SanDisk SSD PLUS 1000GB             | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 980 1TB     | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 7.14%   |
| Kingston SV100S2128G 128GB SSD      | 1        | 1      | 7.14%   |
| Hitachi HUA721010KLA330 1TB         | 1        | 1      | 7.14%   |
| Hitachi HDS722020ALA330 2TB         | 1        | 2      | 7.14%   |
| Crucial CT525MX300SSD1 528GB        | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 28.57%  |
| Seagate             | 2        | 2      | 14.29%  |
| Samsung Electronics | 2        | 2      | 14.29%  |
| Hitachi             | 2        | 3      | 14.29%  |
| Transcend           | 1        | 1      | 7.14%   |
| SanDisk             | 1        | 1      | 7.14%   |
| Kingston            | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 50%     |
| Seagate | 2        | 2      | 25%     |
| Hitachi | 2        | 3      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 12     | 50%     |
| SSD  | 4        | 4      | 33.33%  |
| NVMe | 2        | 2      | 16.67%  |

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
| Works    | 48       | 178    | 73.85%  |
| Malfunc  | 11       | 18     | 16.92%  |
| Detected | 5        | 15     | 7.69%   |
| Failed   | 1        | 1      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 27       | 28.13%  |
| AMD                            | 25       | 26.04%  |
| Samsung Electronics            | 19       | 19.79%  |
| ASMedia Technology             | 6        | 6.25%   |
| Phison Electronics             | 3        | 3.13%   |
| ADATA Technology               | 3        | 3.13%   |
| Silicon Motion                 | 2        | 2.08%   |
| SanDisk                        | 2        | 2.08%   |
| KIOXIA                         | 2        | 2.08%   |
| Toshiba America Info Systems   | 1        | 1.04%   |
| Solid State Storage Technology | 1        | 1.04%   |
| SK hynix                       | 1        | 1.04%   |
| Silicon Image                  | 1        | 1.04%   |
| Seagate Technology             | 1        | 1.04%   |
| Micron/Crucial Technology      | 1        | 1.04%   |
| Marvell Technology Group       | 1        | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19       | 17.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13       | 11.71%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 6.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 5.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6        | 5.41%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 4.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 4.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 3.6%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 2.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 2.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 2.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 2.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.8%    |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.8%    |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 1.8%    |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.8%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.9%    |
| Solid State Storage Non-Volatile memory controller                             | 1        | 0.9%    |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.9%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.9%    |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.9%    |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.9%    |
| Phison E7 NVMe Controller                                                      | 1        | 0.9%    |
| Micron/Crucial NVMe Controller                                                 | 1        | 0.9%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.9%    |
| KIOXIA NVMe SSD                                                                | 1        | 0.9%    |
| KIOXIA Non-Volatile memory controller                                          | 1        | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.9%    |
| Intel Optane SSD 900P Series                                                   | 1        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 51       | 57.95%  |
| NVMe | 33       | 37.5%   |
| RAID | 2        | 2.27%   |
| IDE  | 2        | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 27       | 50.94%  |
| AMD          | 25       | 47.17%  |
| PowerBook6,7 | 1        | 1.89%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-6700K CPU @ 4.00GHz              | 3        | 5.66%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 5.66%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 5.66%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 3        | 5.66%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 5.66%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 3.77%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 2        | 3.77%   |
| Intel 12th Gen Core i7-12700K                  | 2        | 3.77%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 3.77%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.77%   |
| PowerBook6,7 7447A, altivec supported          | 1        | 1.89%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 1        | 1.89%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz            | 1        | 1.89%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 1.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.89%   |
| Intel Core i7-4930K CPU @ 3.40GHz              | 1        | 1.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.89%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 1.89%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 1.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 1.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 1.89%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.89%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 1.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.89%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.89%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.89%   |
| Intel 12th Gen Core i7-12700KF                 | 1        | 1.89%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz        | 1        | 1.89%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 1.89%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 1.89%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 1.89%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.89%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 1.89%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.89%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 1.89%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 1.89%   |
| AMD Ryzen 3 4300GE with Radeon Graphics        | 1        | 1.89%   |
| AMD Phenom II X4 955 Processor                 | 1        | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 11       | 20.75%  |
| Intel Core i5          | 9        | 16.98%  |
| Intel Core i7          | 8        | 15.09%  |
| Other                  | 6        | 11.32%  |
| AMD Ryzen 5            | 6        | 11.32%  |
| AMD Ryzen 7            | 4        | 7.55%   |
| Intel Xeon             | 2        | 3.77%   |
| Intel Core i9          | 2        | 3.77%   |
| Intel Pentium 4        | 1        | 1.89%   |
| AMD Ryzen Threadripper | 1        | 1.89%   |
| AMD Ryzen 7 PRO        | 1        | 1.89%   |
| AMD Ryzen 3            | 1        | 1.89%   |
| AMD Phenom II X4       | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 13       | 24.53%  |
| 4      | 12       | 22.64%  |
| 8      | 11       | 20.75%  |
| 12     | 8        | 15.09%  |
| 16     | 6        | 11.32%  |
| 1      | 2        | 3.77%   |
| 24     | 1        | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 42       | 79.25%  |
| 1      | 11       | 20.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 52       | 98.11%  |
| 32-bit         | 1        | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 14.81%  |
| 0x08701021 | 5        | 9.26%   |
| 0x506e3    | 4        | 7.41%   |
| 0x0a201016 | 4        | 7.41%   |
| 0x906ed    | 3        | 5.56%   |
| 0x90672    | 3        | 5.56%   |
| 0x0800820d | 3        | 5.56%   |
| 0x08001138 | 3        | 5.56%   |
| 0xa0671    | 2        | 3.7%    |
| 0xa0655    | 2        | 3.7%    |
| 0xa0653    | 2        | 3.7%    |
| 0x906e9    | 2        | 3.7%    |
| 0xf43      | 1        | 1.85%   |
| 0x906ec    | 1        | 1.85%   |
| 0x306e4    | 1        | 1.85%   |
| 0x306c3    | 1        | 1.85%   |
| 0x206c2    | 1        | 1.85%   |
| 0x206a7    | 1        | 1.85%   |
| 0x0a50000c | 1        | 1.85%   |
| 0x0a50000b | 1        | 1.85%   |
| 0x0a201205 | 1        | 1.85%   |
| 0x0a201204 | 1        | 1.85%   |
| 0x08600106 | 1        | 1.85%   |
| 0x08301039 | 1        | 1.85%   |
| 0x010000db | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 9        | 16.67%  |
| Zen 3            | 8        | 14.81%  |
| KabyLake         | 7        | 12.96%  |
| Skylake          | 5        | 9.26%   |
| Zen+             | 4        | 7.41%   |
| CometLake        | 4        | 7.41%   |
| Zen              | 3        | 5.56%   |
| Alderlake Hybrid | 3        | 5.56%   |
| Icelake          | 2        | 3.7%    |
| Haswell          | 2        | 3.7%    |
| Unknown          | 2        | 3.7%    |
| Westmere         | 1        | 1.85%   |
| SandyBridge      | 1        | 1.85%   |
| NetBurst         | 1        | 1.85%   |
| K10              | 1        | 1.85%   |
| IvyBridge        | 1        | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 27       | 45%     |
| Nvidia | 24       | 40%     |
| Intel  | 9        | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 10       | 16.13%  |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 3        | 4.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 3        | 4.84%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 2        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                     | 2        | 3.23%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 2        | 3.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 2        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 2        | 3.23%   |
| Intel AlderLake-S GT1                                               | 2        | 3.23%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                          | 2        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 1        | 1.61%   |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 1.61%   |
| Nvidia TU106 [GeForce RTX 2070]                                     | 1        | 1.61%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                              | 1        | 1.61%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                               | 1        | 1.61%   |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 1.61%   |
| Nvidia GP104 [GeForce GTX 1070]                                     | 1        | 1.61%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 1.61%   |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 1.61%   |
| Nvidia GM107 [GeForce GTX 745]                                      | 1        | 1.61%   |
| Nvidia GK208B [GeForce GT 730]                                      | 1        | 1.61%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                  | 1        | 1.61%   |
| Nvidia GA106 [Geforce RTX 3050]                                     | 1        | 1.61%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                  | 1        | 1.61%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                  | 1        | 1.61%   |
| Intel HD Graphics P630                                              | 1        | 1.61%   |
| Intel HD Graphics 630                                               | 1        | 1.61%   |
| Intel HD Graphics 530                                               | 1        | 1.61%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 1        | 1.61%   |
| AMD Turks PRO [Radeon HD 7570]                                      | 1        | 1.61%   |
| AMD RV360/M12 [Mobility Radeon 9550]                                | 1        | 1.61%   |
| AMD RS780C [Radeon 3100]                                            | 1        | 1.61%   |
| AMD Renoir                                                          | 1        | 1.61%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                      | 1        | 1.61%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                | 1        | 1.61%   |
| AMD Ellesmere [Radeon Pro WX 7100]                                  | 1        | 1.61%   |
| AMD Cezanne                                                         | 1        | 1.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                    | 1        | 1.61%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                | 1        | 1.61%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 1.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 21       | 39.62%  |
| 1 x Nvidia     | 20       | 37.74%  |
| 1 x Intel      | 4        | 7.55%   |
| AMD + Nvidia   | 3        | 5.66%   |
| Intel + AMD    | 2        | 3.77%   |
| Other          | 1        | 1.89%   |
| 2 x AMD        | 1        | 1.89%   |
| Intel + Nvidia | 1        | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 31       | 58.49%  |
| Proprietary | 20       | 37.74%  |
| Unknown     | 2        | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 17       | 30.91%  |
| Unknown    | 15       | 27.27%  |
| 8.01-16.0  | 8        | 14.55%  |
| 3.01-4.0   | 4        | 7.27%   |
| 5.01-6.0   | 3        | 5.45%   |
| 1.01-2.0   | 3        | 5.45%   |
| 0.51-1.0   | 3        | 5.45%   |
| 2.01-3.0   | 1        | 1.82%   |
| 0.01-0.5   | 1        | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 8        | 11.43%  |
| Goldstar                | 7        | 10%     |
| Hewlett-Packard         | 5        | 7.14%   |
| ViewSonic               | 4        | 5.71%   |
| Dell                    | 4        | 5.71%   |
| Ancor Communications    | 4        | 5.71%   |
| Lenovo                  | 3        | 4.29%   |
| Iiyama                  | 3        | 4.29%   |
| BenQ                    | 3        | 4.29%   |
| ASUSTek Computer        | 3        | 4.29%   |
| AOC                     | 3        | 4.29%   |
| Acer                    | 3        | 4.29%   |
| Philips                 | 2        | 2.86%   |
| Unknown                 | 2        | 2.86%   |
| Valve                   | 1        | 1.43%   |
| Toshiba                 | 1        | 1.43%   |
| PNP                     | 1        | 1.43%   |
| Onkyo                   | 1        | 1.43%   |
| NEC Computers           | 1        | 1.43%   |
| MStar                   | 1        | 1.43%   |
| Microstep               | 1        | 1.43%   |
| Mi                      | 1        | 1.43%   |
| LYC                     | 1        | 1.43%   |
| KTC                     | 1        | 1.43%   |
| HannStar                | 1        | 1.43%   |
| Gigabyte Technology     | 1        | 1.43%   |
| Gateway                 | 1        | 1.43%   |
| Chi Mei Optoelectronics | 1        | 1.43%   |
| Belinea                 | 1        | 1.43%   |
| Apple                   | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 3        | 3.95%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 2        | 2.63%   |
| Unknown                                                                | 2        | 2.63%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch             | 1        | 1.32%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch          | 1        | 1.32%   |
| ViewSonic LCD Monitor VSCCB25 1920x1080 480x270mm 21.7-inch            | 1        | 1.32%   |
| ViewSonic LCD Monitor VSC2034 2560x1440 600x340mm 27.2-inch            | 1        | 1.32%   |
| Valve Index HMD VLV91A8                                                | 1        | 1.32%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1        | 1.32%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 1.32%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch   | 1        | 1.32%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1        | 1.32%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch      | 1        | 1.32%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1        | 1.32%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1        | 1.32%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1        | 1.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.32%   |
| PNP LCD Monitor PNP0801 1280x960                                       | 1        | 1.32%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.32%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                | 1        | 1.32%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1        | 1.32%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1        | 1.32%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1        | 1.32%   |
| Microstep LCD Monitor MSI MPG27CQ 2560x1440                            | 1        | 1.32%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 1.32%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                        | 1        | 1.32%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1        | 1.32%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                      | 1        | 1.32%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch               | 1        | 1.32%   |
| KTC Q2711SH KTC2700 2560x1440 597x336mm 27.0-inch                      | 1        | 1.32%   |
| Iiyama PLG2488H IVM6127 1920x1080 530x300mm 24.0-inch                  | 1        | 1.32%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 1        | 1.32%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 1        | 1.32%   |
| Iiyama PL2760Q IVM663D 2560x1440 600x340mm 27.2-inch                   | 1        | 1.32%   |
| Iiyama PL2480H IVM610B 1920x1080 521x293mm 23.5-inch                   | 1        | 1.32%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1        | 1.32%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1        | 1.32%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch              | 1        | 1.32%   |
| Hewlett-Packard 27es HWP3325 1920x1080 600x340mm 27.2-inch             | 1        | 1.32%   |
| Hewlett-Packard 24mq HPN366F 2560x1440 527x296mm 23.8-inch             | 1        | 1.32%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch             | 1        | 1.32%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1        | 1.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1        | 1.32%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch               | 1        | 1.32%   |
| Goldstar L1750U GSM440C 1280x1024 338x270mm 17.0-inch                  | 1        | 1.32%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1        | 1.32%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1        | 1.32%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1        | 1.32%   |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                      | 1        | 1.32%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1        | 1.32%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1        | 1.32%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                      | 1        | 1.32%   |
| Dell E2015HV DELF05E 1600x900 430x240mm 19.4-inch                      | 1        | 1.32%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1        | 1.32%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 1        | 1.32%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1        | 1.32%   |
| BenQ E2200HD BNQ790C 1920x1080 470x260mm 21.1-inch                     | 1        | 1.32%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1        | 1.32%   |
| ASUSTek Computer XG27WQ AUS2724 2560x1440 597x336mm 27.0-inch          | 1        | 1.32%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 597x336mm 27.0-inch           | 1        | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 35.82%  |
| 2560x1440 (QHD)    | 18       | 26.87%  |
| 3840x2160 (4K)     | 6        | 8.96%   |
| 3440x1440          | 3        | 4.48%   |
| 1280x1024 (SXGA)   | 3        | 4.48%   |
| 3840x1080          | 2        | 2.99%   |
| Unknown            | 2        | 2.99%   |
| 2560x1080          | 1        | 1.49%   |
| 2048x1152          | 1        | 1.49%   |
| 1920x1200 (WUXGA)  | 1        | 1.49%   |
| 1680x1050 (WSXGA+) | 1        | 1.49%   |
| 1600x900 (HD+)     | 1        | 1.49%   |
| 1440x900 (WXGA+)   | 1        | 1.49%   |
| 1366x768 (WXGA)    | 1        | 1.49%   |
| 1280x960           | 1        | 1.49%   |
| 1024x768 (XGA)     | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 21       | 30%     |
| 23      | 13       | 18.57%  |
| 21      | 6        | 8.57%   |
| 24      | 5        | 7.14%   |
| Unknown | 5        | 7.14%   |
| 34      | 4        | 5.71%   |
| 19      | 3        | 4.29%   |
| 17      | 3        | 4.29%   |
| 49      | 2        | 2.86%   |
| 25      | 2        | 2.86%   |
| 14      | 2        | 2.86%   |
| 31      | 1        | 1.43%   |
| 28      | 1        | 1.43%   |
| 20      | 1        | 1.43%   |
| 15      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 33       | 53.23%  |
| 401-500     | 8        | 12.9%   |
| 301-350     | 5        | 8.06%   |
| Unknown     | 5        | 8.06%   |
| 701-800     | 4        | 6.45%   |
| 601-700     | 3        | 4.84%   |
| 1001-1500   | 2        | 3.23%   |
| 351-400     | 1        | 1.61%   |
| 201-300     | 1        | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 68.42%  |
| 21/9    | 4        | 7.02%   |
| 16/10   | 4        | 7.02%   |
| Unknown | 4        | 7.02%   |
| 5/4     | 3        | 5.26%   |
| 4/3     | 2        | 3.51%   |
| 32/9    | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 21       | 30.43%  |
| 201-250        | 21       | 30.43%  |
| 351-500        | 6        | 8.7%    |
| 151-200        | 5        | 7.25%   |
| Unknown        | 5        | 7.25%   |
| 251-300        | 3        | 4.35%   |
| 141-150        | 3        | 4.35%   |
| More than 1000 | 1        | 1.45%   |
| 81-90          | 1        | 1.45%   |
| 101-110        | 1        | 1.45%   |
| 501-1000       | 1        | 1.45%   |
| 91-100         | 1        | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 40.98%  |
| 101-120 | 23       | 37.7%   |
| Unknown | 5        | 8.2%    |
| 121-160 | 4        | 6.56%   |
| 161-240 | 3        | 4.92%   |
| 1-50    | 1        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 51.85%  |
| 2     | 19       | 35.19%  |
| 0     | 3        | 5.56%   |
| 4     | 2        | 3.7%    |
| 3     | 2        | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 31       | 44.29%  |
| Realtek Semiconductor    | 23       | 32.86%  |
| Aquantia                 | 3        | 4.29%   |
| Qualcomm Atheros         | 2        | 2.86%   |
| Marvell Technology Group | 2        | 2.86%   |
| Broadcom                 | 2        | 2.86%   |
| Raspberry Pi             | 1        | 1.43%   |
| Ralink Technology        | 1        | 1.43%   |
| NetGear                  | 1        | 1.43%   |
| Microsoft                | 1        | 1.43%   |
| MediaTek                 | 1        | 1.43%   |
| Broadcom Limited         | 1        | 1.43%   |
| Apple                    | 1        | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 15       | 17.24%  |
| Realtek RTL8125 2.5GbE Controller                                   | 7        | 8.05%   |
| Intel Wi-Fi 6 AX200                                                 | 7        | 8.05%   |
| Intel I211 Gigabit Network Connection                               | 7        | 8.05%   |
| Intel Ethernet Controller I225-V                                    | 6        | 6.9%    |
| Intel Ethernet Connection (2) I219-V                                | 5        | 5.75%   |
| Intel Ethernet Connection (7) I219-V                                | 4        | 4.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 3        | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 2        | 2.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 2        | 2.3%    |
| Intel 82574L Gigabit Network Connection                             | 2        | 2.3%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 1.15%   |
| Raspberry Pi Pico                                                   | 1        | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 1.15%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.15%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 1.15%   |
| NetGear A6210                                                       | 1        | 1.15%   |
| Microsoft XBOX ACC                                                  | 1        | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 1.15%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 1.15%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 1.15%   |
| Intel Wireless-AC 9260                                              | 1        | 1.15%   |
| Intel I210 Gigabit Network Connection                               | 1        | 1.15%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 1.15%   |
| Intel Ethernet Connection I217-V                                    | 1        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 1.15%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 1.15%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 1.15%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 1.15%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 1.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.15%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.15%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                     | 1        | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 58.33%  |
| Qualcomm Atheros      | 2        | 8.33%   |
| Broadcom              | 2        | 8.33%   |
| Realtek Semiconductor | 1        | 4.17%   |
| Ralink Technology     | 1        | 4.17%   |
| NetGear               | 1        | 4.17%   |
| Microsoft             | 1        | 4.17%   |
| MediaTek              | 1        | 4.17%   |
| Broadcom Limited      | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 7        | 28%     |
| Intel Cannon Lake PCH CNVi WiFi                                     | 2        | 8%      |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 2        | 8%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 4%      |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 4%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 4%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 4%      |
| NetGear A6210                                                       | 1        | 4%      |
| Microsoft XBOX ACC                                                  | 1        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 4%      |
| Intel Wireless-AC 9260                                              | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 4%      |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 4%      |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 4%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 4%      |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 29       | 50%     |
| Realtek Semiconductor    | 23       | 39.66%  |
| Aquantia                 | 3        | 5.17%   |
| Marvell Technology Group | 2        | 3.45%   |
| Apple                    | 1        | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15       | 24.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 11.48%  |
| Intel I211 Gigabit Network Connection                             | 7        | 11.48%  |
| Intel Ethernet Controller I225-V                                  | 6        | 9.84%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 8.2%    |
| Intel Ethernet Connection (7) I219-V                              | 4        | 6.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 4.92%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.64%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.64%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.64%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.64%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.64%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.64%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1        | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 69.33%  |
| WiFi     | 22       | 29.33%  |
| Modem    | 1        | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 85.19%  |
| WiFi     | 8        | 14.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 52.83%  |
| 2     | 17       | 32.08%  |
| 3     | 7        | 13.21%  |
| 0     | 1        | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 73.58%  |
| Yes  | 14       | 26.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 61.54%  |
| Cambridge Silicon Radio         | 4        | 15.38%  |
| Realtek Semiconductor           | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| MediaTek                        | 1        | 3.85%   |
| Broadcom                        | 1        | 3.85%   |
| ASUSTek Computer                | 1        | 3.85%   |
| Apple                           | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 8        | 30.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 15.38%  |
| Intel Bluetooth Device                              | 3        | 11.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 7.69%   |
| Realtek Bluetooth Radio                             | 1        | 3.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 3.85%   |
| MediaTek Wireless_Device                            | 1        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.85%   |
| Intel AX210 Bluetooth                               | 1        | 3.85%   |
| Broadcom BCM20702A0                                 | 1        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.85%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 34       | 28.33%  |
| Intel                                | 25       | 20.83%  |
| Nvidia                               | 24       | 20%     |
| C-Media Electronics                  | 4        | 3.33%   |
| Thesycon Systemsoftware & Consulting | 3        | 2.5%    |
| Realtek Semiconductor                | 3        | 2.5%    |
| ASUSTek Computer                     | 3        | 2.5%    |
| Yamaha                               | 2        | 1.67%   |
| SteelSeries ApS                      | 2        | 1.67%   |
| Sony                                 | 2        | 1.67%   |
| Logitech                             | 2        | 1.67%   |
| Creative Technology                  | 2        | 1.67%   |
| Creative Labs                        | 2        | 1.67%   |
| AudioQuest                           | 2        | 1.67%   |
| Valve Software                       | 1        | 0.83%   |
| Sennheiser Communications            | 1        | 0.83%   |
| SAVITECH                             | 1        | 0.83%   |
| RODE Microphones                     | 1        | 0.83%   |
| Razer USA                            | 1        | 0.83%   |
| JOUNIVO                              | 1        | 0.83%   |
| JMTek                                | 1        | 0.83%   |
| Generalplus Technology               | 1        | 0.83%   |
| FiiO Electronics Technology          | 1        | 0.83%   |
| Astro Gaming                         | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 9.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 8.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 5.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 5.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 4.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.92%   |
| Thesycon Systemsoftware & Consulting E30                                   | 3        | 2.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.19%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.19%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 1.46%   |
| Realtek Semiconductor USB Condenser Microphone                             | 2        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.46%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 1.46%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.46%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.46%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 1.46%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.46%   |
| ASUSTek Computer USB Audio                                                 | 2        | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.46%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 0.73%   |
| Yamaha Steinberg UR22C                                                     | 1        | 0.73%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1        | 0.73%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.73%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1        | 0.73%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                          | 1        | 0.73%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.73%   |
| RODE Microphones RODE VideoMic NTG                                         | 1        | 0.73%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.73%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.73%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia Audio device                                                        | 1        | 0.73%   |
| Logitech Z-5 Speakers                                                      | 1        | 0.73%   |
| Logitech Yeti X                                                            | 1        | 0.73%   |
| JOUNIVO JV601                                                              | 1        | 0.73%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 0.73%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.73%   |
| Intel Audio device                                                         | 1        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 0.73%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 0.73%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 1        | 0.73%   |
| FiiO Electronics Technology K3                                             | 1        | 0.73%   |
| Creative Technology Sound BlasterX G6                                      | 1        | 0.73%   |
| Creative Technology Sound Blaster Play! 3                                  | 1        | 0.73%   |
| C-Media Electronics USB Advanced Audio Device                              | 1        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 13       | 23.64%  |
| Kingston            | 12       | 21.82%  |
| Crucial             | 10       | 18.18%  |
| Unknown             | 4        | 7.27%   |
| Corsair             | 4        | 7.27%   |
| Samsung Electronics | 3        | 5.45%   |
| Patriot             | 2        | 3.64%   |
| Micron Technology   | 2        | 3.64%   |
| A-DATA Technology   | 2        | 3.64%   |
| Team                | 1        | 1.82%   |
| SK hynix            | 1        | 1.82%   |
| Unknown             | 1        | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s       | 2        | 3.33%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s  | 2        | 3.33%   |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s | 2        | 3.33%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 3.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 1.67%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1        | 1.67%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 1.67%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 1.67%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s               | 1        | 1.67%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 1        | 1.67%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.67%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 1.67%   |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s     | 1        | 1.67%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 1        | 1.67%   |
| Samsung RAM M378A2G43MX3-CTD 16384MB DIMM DDR4 3466MT/s  | 1        | 1.67%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s       | 1        | 1.67%   |
| Micron RAM 16JTF51264AZ-1G4D 4GB DIMM DDR3 1333MT/s      | 1        | 1.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 1.67%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 1        | 1.67%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 1.67%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 1        | 1.67%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 1        | 1.67%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s         | 1        | 1.67%   |
| Kingston RAM HP698651-154-KEB 8GB DIMM DDR3 1333MT/s     | 1        | 1.67%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 1        | 1.67%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s     | 1        | 1.67%   |
| G.Skill RAM F4-4400C19-32GTRS 32GB DIMM DDR4 2667MT/s    | 1        | 1.67%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s    | 1        | 1.67%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s   | 1        | 1.67%   |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s      | 1        | 1.67%   |
| G.Skill RAM F4-3400C16-8GTZ 8GB DIMM DDR4 2197MT/s       | 1        | 1.67%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 1.67%   |
| G.Skill RAM F4-3200C16-16GTZN 16384MB DIMM DDR4 3200MT/s | 1        | 1.67%   |
| G.Skill RAM F4-3200C14-32GVK 32GB DIMM DDR4 2666MT/s     | 1        | 1.67%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3000MT/s      | 1        | 1.67%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s      | 1        | 1.67%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s     | 1        | 1.67%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s    | 1        | 1.67%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s  | 1        | 1.67%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s | 1        | 1.67%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 1.67%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s     | 1        | 1.67%   |
| Crucial RAM BL8G32C16U4R.M8FE1 8GB DIMM DDR4 3400MT/s    | 1        | 1.67%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3600MT/s    | 1        | 1.67%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3600MT/s | 1        | 1.67%   |
| Crucial RAM BL32G32C16U4B.M16FB1 32GB DIMM DDR4 3200MT/s | 1        | 1.67%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s | 1        | 1.67%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s | 1        | 1.67%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s  | 1        | 1.67%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s   | 1        | 1.67%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 1        | 1.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 1        | 1.67%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s    | 1        | 1.67%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s              | 1        | 1.67%   |
| A-DATA RAM DDR4 3000 2OZ 4GB DIMM DDR4 3000MT/s          | 1        | 1.67%   |
| Unknown                                                  | 1        | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 85.71%  |
| DDR3    | 4        | 8.16%   |
| SDRAM   | 1        | 2.04%   |
| DDR2    | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 49       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 37.5%   |
| 16384 | 19       | 33.93%  |
| 32768 | 7        | 12.5%   |
| 4096  | 5        | 8.93%   |
| 2048  | 2        | 3.57%   |
| 1024  | 1        | 1.79%   |
| 512   | 1        | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 11       | 20%     |
| 2133    | 6        | 10.91%  |
| 3600    | 5        | 9.09%   |
| 2667    | 4        | 7.27%   |
| 3400    | 3        | 5.45%   |
| 3866    | 2        | 3.64%   |
| 3666    | 2        | 3.64%   |
| 3533    | 2        | 3.64%   |
| 3466    | 2        | 3.64%   |
| 3000    | 2        | 3.64%   |
| 2400    | 2        | 3.64%   |
| 1600    | 2        | 3.64%   |
| 1333    | 2        | 3.64%   |
| 4000    | 1        | 1.82%   |
| 3733    | 1        | 1.82%   |
| 2933    | 1        | 1.82%   |
| 2866    | 1        | 1.82%   |
| 2733    | 1        | 1.82%   |
| 2666    | 1        | 1.82%   |
| 2197    | 1        | 1.82%   |
| 1867    | 1        | 1.82%   |
| 667     | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP LaserJet M14-M17 | 1        | 100%    |

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
| Logitech                      | 7        | 43.75%  |
| Xiaomi                        | 1        | 6.25%   |
| Valve Software                | 1        | 6.25%   |
| Sunplus Innovation Technology | 1        | 6.25%   |
| Ruision                       | 1        | 6.25%   |
| MacroSilicon                  | 1        | 6.25%   |
| HD WEBCAM                     | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| Cubeternet                    | 1        | 6.25%   |
| Creative Technology           | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Xiaomi MI 9                                                         | 1        | 6.25%   |
| Valve Software 3D Camera                                            | 1        | 6.25%   |
| Sunplus Full HD webcam                                              | 1        | 6.25%   |
| Ruision UVC Camera                                                  | 1        | 6.25%   |
| MacroSilicon MiraBox Capture                                        | 1        | 6.25%   |
| Logitech Webcam C270                                                | 1        | 6.25%   |
| Logitech StreamCam                                                  | 1        | 6.25%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1        | 6.25%   |
| Logitech HD Webcam C615                                             | 1        | 6.25%   |
| Logitech HD Webcam C510                                             | 1        | 6.25%   |
| Logitech HD Pro Webcam C920                                         | 1        | 6.25%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 6.25%   |
| HD WEBCAM Web Camera                                                | 1        | 6.25%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 6.25%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 6.25%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 6.25%   |

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
| 0     | 41       | 73.21%  |
| 1     | 10       | 17.86%  |
| 4     | 2        | 3.57%   |
| 2     | 2        | 3.57%   |
| 3     | 1        | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 7        | 36.84%  |
| Net/wireless             | 3        | 15.79%  |
| Graphics card            | 2        | 10.53%  |
| Storage/raid             | 1        | 5.26%   |
| Storage/ata              | 1        | 5.26%   |
| Sound                    | 1        | 5.26%   |
| Modem                    | 1        | 5.26%   |
| Fingerprint reader       | 1        | 5.26%   |
| Camera                   | 1        | 5.26%   |
| Bluetooth                | 1        | 5.26%   |

