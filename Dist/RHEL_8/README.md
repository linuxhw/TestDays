RHEL 8 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_8/Desktop/README.md) and [notebooks](/Dist/RHEL_8/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Lenovo     | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek    | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP         | EliteBook 8460p             | Notebook    | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Gigabyte   | Z97N-WIFI                   | Desktop     | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek    | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek    | PRIME B360M-D               | Desktop     | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Toshiba    | Satellite Pro R50-C         | Notebook    | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba    | Satellite Pro R50-C         | Notebook    | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| Dell       | Precision 3551              | Notebook    | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6c62008ae3](https://linux-hardware.org/?probe=6c62008ae3) | Dec 21, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6f29b7bde7](https://linux-hardware.org/?probe=6f29b7bde7) | Dec 21, 2021 |
| Gigabyte   | Z97N-WIFI                   | Desktop     | [9d1a04cc28](https://linux-hardware.org/?probe=9d1a04cc28) | Dec 15, 2021 |
| Lenovo     | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f88a7d7f15](https://linux-hardware.org/?probe=f88a7d7f15) | Dec 06, 2021 |
| Acer       | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [cd6c668ae9](https://linux-hardware.org/?probe=cd6c668ae9) | Nov 29, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP         | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo     | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo     | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ab905debb9](https://linux-hardware.org/?probe=ab905debb9) | Nov 17, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo     | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo     | ThinkPad P50 20ENS1L000     | Notebook    | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo     | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo     | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| ASUSTek    | PRIME B350M-A               | Desktop     | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| ASUSTek    | Pro WS X570-ACE             | Desktop     | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| HP         | ZBook Firefly 15 inch G8... | Notebook    | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| ASUSTek    | PRIME B350M-A               | Desktop     | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| Lenovo     | ThinkPad P50 20ENS1L000     | Notebook    | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| ASUSTek    | Z87-DELUXE                  | Desktop     | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Lenovo     | ThinkPad T490s 20NYS7K90... | Notebook    | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| HP         | 212B                        | Desktop     | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek    | Z87-DELUXE                  | Desktop     | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte   | Z97N-WIFI                   | Desktop     | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Lenovo     | ThinkPad T470 20HES57W00    | Notebook    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Gigabyte   | Z97N-WIFI                   | Desktop     | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo     | MAHOBAY                     | Desktop     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek    | PRIME B350M-A               | Desktop     | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Lenovo     | ThinkPad X230 Tablet 343... | Notebook    | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell       | XPS 15 9560                 | Notebook    | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Gigabyte   | Z390 AORUS ULTRA-CF         | Desktop     | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte   | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek    | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek    | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell       | XPS 15 9560                 | Notebook    | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Supermicro | X10DRi                      | Server      | [6be87ab445](https://linux-hardware.org/?probe=6be87ab445) | Jul 26, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek    | PN50                        | Mini pc     | [54f44d70c5](https://linux-hardware.org/?probe=54f44d70c5) | Jul 24, 2021 |
| HP         | ZBook 15 G5                 | Notebook    | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Gigabyte   | Z490 GAMING X               | Desktop     | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell       | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP         | EliteBook 850 G7 Noteboo... | Notebook    | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo     | ThinkPad T490s 20NYS7K91... | Notebook    | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo     | ThinkPad T490s 20NYS7K91... | Notebook    | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell       | 0MWYPT A02                  | Desktop     | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Dell       | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell       | Latitude E6430              | Notebook    | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell       | Latitude E6430              | Notebook    | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo     | ThinkPad T490s 20NYS7K91... | Notebook    | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo     | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Intel      | DX79SR AAG57199-200         | Desktop     | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| Dell       | Precision 3541              | Notebook    | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP         | ZBook Studio G5             | Notebook    | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP         | ZBook Studio G5             | Notebook    | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| HP         | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Dell       | 074H08 A00                  | Server      | [b7ac531bf5](https://linux-hardware.org/?probe=b7ac531bf5) | Jun 02, 2021 |
| Gigabyte   | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| Dell       | Latitude E6530              | Notebook    | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| MSI        | MPG Z390 GAMING PLUS        | Desktop     | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [779849778e](https://linux-hardware.org/?probe=779849778e) | May 26, 2021 |
| HP         | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI        | Z77A-G45                    | Desktop     | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI        | Z77A-G45                    | Desktop     | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek    | ROG Maximus X HERO          | Desktop     | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| HP         | 8054                        | Desktop     | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock     | X99E-ITX/ac                 | Desktop     | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| Lenovo     | 7D2XCTO1WW                  | Server      | [2175466ea1](https://linux-hardware.org/?probe=2175466ea1) | Apr 25, 2021 |
| HP         | ProLiant DL380 Gen9         | Server      | [23f12250e5](https://linux-hardware.org/?probe=23f12250e5) | Apr 22, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell       | Inspiron 3559               | Notebook    | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP         | OMEN by Laptop 15-dc1xxx    | Notebook    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [bb1cb9b30a](https://linux-hardware.org/?probe=bb1cb9b30a) | Apr 02, 2021 |
| Lenovo     | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo     | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| Lenovo     | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| ASUSTek    | PRIME B360M-D               | Desktop     | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [433f10b16b](https://linux-hardware.org/?probe=433f10b16b) | Mar 16, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo     | ThinkPad T460 20FMS1VA09    | Notebook    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo     | ThinkPad T460 20FMS1VA09    | Notebook    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo     | ThinkPad W530 2441B32       | Notebook    | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek    | Zephyrus G GU502DU_GA502... | Notebook    | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| ASRock     | A300M-STX                   | Desktop     | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell       | 0NNNCT A01                  | Desktop     | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| Sony       | VPCEB4L1R                   | Notebook    | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP         | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Intel      | NUC10i7FNB K61360-302       | Mini pc     | [29d0e20ba4](https://linux-hardware.org/?probe=29d0e20ba4) | Feb 08, 2021 |
| Lenovo     | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo     | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo     | ThinkPad E15 Gen 2 20T80... | Notebook    | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo     | ThinkPad L480 20LSCTO1WW    | Notebook    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo     | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo     | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek    | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| ASUSTek    | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek    | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| Lenovo     | ThinkPad T480s 20L8S2N80... | Notebook    | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| ASRock     | H270 Pro4                   | Desktop     | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo     | ThinkPad E15 Gen 2 20T80... | Notebook    | [e3d128beda](https://linux-hardware.org/?probe=e3d128beda) | Dec 28, 2020 |
| Lenovo     | ThinkPad E15 Gen 2 20T80... | Notebook    | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo     | ThinkPad T490s 20NYS7K91... | Notebook    | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Unknown    | SKYBAY                      | Desktop     | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| Dell       | Latitude 5290               | Notebook    | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell       | Latitude 5290               | Notebook    | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP         | 1905                        | Desktop     | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| HP         | Pavilion 14                 | Notebook    | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo     | ThinkPad X250 20CLS0H807    | Notebook    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo     | ThinkPad X250 20CLS0H807    | Notebook    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo     | ThinkPad X250 20CLS0H807    | Notebook    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo     | ThinkpadT460 20BUS0QT0A     | Notebook    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| Dell       | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell       | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO     | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell       | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell       | 082WXT A01                  | Desktop     | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP         | 81B4                        | Desktop     | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP         | 81B4                        | Desktop     | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| HP         | 1905                        | Desktop     | [872e4ba303](https://linux-hardware.org/?probe=872e4ba303) | Nov 13, 2020 |
| Dell       | Latitude E6420              | Notebook    | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell       | Latitude E6420              | Notebook    | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| MSI        | H310M PRO-VD                | Desktop     | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| TUXEDO     | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO     | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell       | Precision 7510              | Notebook    | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP         | Pavilion 14                 | Notebook    | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell       | Precision 7510              | Notebook    | [9d901b2f8e](https://linux-hardware.org/?probe=9d901b2f8e) | Nov 01, 2020 |
| Dell       | Precision 7510              | Notebook    | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo     | Yoga C640-13IML 81UE        | Convertible | [2dc26a5fbe](https://linux-hardware.org/?probe=2dc26a5fbe) | Oct 29, 2020 |
| Lenovo     | Yoga C640-13IML 81UE        | Convertible | [cf0c44ffb8](https://linux-hardware.org/?probe=cf0c44ffb8) | Oct 29, 2020 |
| Lenovo     | ThinkPad T520 42404CG       | Notebook    | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo     | ThinkPad T520 42404CG       | Notebook    | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo     | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell       | Latitude 5300               | Notebook    | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell       | Latitude 5300               | Notebook    | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP         | 1905                        | Desktop     | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek    | Z10PE-D16 WS                | Desktop     | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP         | Pavilion 14                 | Notebook    | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo     | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo     | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC0V    | Notebook    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| HP         | 1905                        | Desktop     | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP         | 1905                        | Desktop     | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP         | 843F                        | Desktop     | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| Lenovo     | ThinkPad P50 20EN0005UK     | Notebook    | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| HP         | 843F                        | Desktop     | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Dell       | Inspiron 5567               | Notebook    | [a9d66d8f86](https://linux-hardware.org/?probe=a9d66d8f86) | Sep 15, 2020 |
| HP         | ProBook 430 G5              | Notebook    | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell       | Inspiron N5110              | Notebook    | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell       | Inspiron N5110              | Notebook    | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| ASUSTek    | GL502VMK                    | Notebook    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| HP         | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Dell       | Latitude 5300               | Notebook    | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi       | TM1707                      | Notebook    | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi       | TM1707                      | Notebook    | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek    | GL502VMK                    | Notebook    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo     | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell       | Latitude 5300               | Notebook    | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC0N    | Notebook    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC0N    | Notebook    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo     | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| HP         | ProBook 430 G5              | Notebook    | [20760711e1](https://linux-hardware.org/?probe=20760711e1) | May 24, 2020 |
| HP         | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP         | ProBook 430 G5              | Notebook    | [53ccb8b4bf](https://linux-hardware.org/?probe=53ccb8b4bf) | May 23, 2020 |
| HP         | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek    | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP         | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASUSTek    | P8Z77-V PRO                 | Desktop     | [1abce91d71](https://linux-hardware.org/?probe=1abce91d71) | May 08, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC0V    | Notebook    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell       | G3 3779                     | Notebook    | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell       | Precision 5540              | Notebook    | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Dell       | Inspiron 5567               | Notebook    | [6cc6232ddf](https://linux-hardware.org/?probe=6cc6232ddf) | Apr 14, 2020 |
| ASRockRack | EP2C612 WS                  | Desktop     | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Lenovo     | ThinkPad T450s 20BWS0B50... | Notebook    | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Gigabyte   | B75-D3V                     | Desktop     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack | EP2C612 WS                  | Desktop     | [1dd5200664](https://linux-hardware.org/?probe=1dd5200664) | Apr 07, 2020 |
| ASRockRack | EP2C612 WS                  | Desktop     | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [b49a701ac3](https://linux-hardware.org/?probe=b49a701ac3) | Apr 01, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC0N    | Notebook    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC00    | Notebook    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo     | ThinkPad T590 20N5S2NC00    | Notebook    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo     | ThinkPad X1 Carbon 7th 2... | Notebook    | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Alienware  | 0VDT73 A00                  | Desktop     | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo     | ThinkPad T450s 20BWS0B50... | Notebook    | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [b5d3a3694d](https://linux-hardware.org/?probe=b5d3a3694d) | Feb 27, 2020 |
| Sony       | VPCEB23FM                   | Notebook    | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony       | VPCEB23FM                   | Notebook    | [4cde30cfa5](https://linux-hardware.org/?probe=4cde30cfa5) | Feb 26, 2020 |
| Sony       | VPCEB23FM                   | Notebook    | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo     | Board                       | Desktop     | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo     | Board                       | Desktop     | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| Lenovo     | ThinkPad P52 20M9CTO1WW     | Notebook    | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo     | ThinkPad P52 20M9CTO1WW     | Notebook    | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo     | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| MSI        | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [5c93a8b972](https://linux-hardware.org/?probe=5c93a8b972) | Feb 03, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [7b9606b44d](https://linux-hardware.org/?probe=7b9606b44d) | Feb 03, 2020 |
| ASUSTek    | P8Z77-V PRO                 | Desktop     | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo     | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [f24757810e](https://linux-hardware.org/?probe=f24757810e) | Jan 28, 2020 |
| Dell       | 0XR1GT A00                  | Desktop     | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell       | 0XR1GT A00                  | Desktop     | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo     | ThinkPad T490s 20NX002HU... | Notebook    | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo     | ThinkPad X270 20HN001EMC    | Notebook    | [73b2494a42](https://linux-hardware.org/?probe=73b2494a42) | Jan 22, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [bdeba33a9c](https://linux-hardware.org/?probe=bdeba33a9c) | Jan 19, 2020 |
| ASUSTek    | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [a92733c45d](https://linux-hardware.org/?probe=a92733c45d) | Jan 17, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [4edc6c52b8](https://linux-hardware.org/?probe=4edc6c52b8) | Jan 17, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [372bb9dced](https://linux-hardware.org/?probe=372bb9dced) | Jan 15, 2020 |
| Lenovo     | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo     | ThinkPad X270 20HN001EMC    | Notebook    | [92086a7925](https://linux-hardware.org/?probe=92086a7925) | Jan 14, 2020 |
| Lenovo     | ThinkPad X270 20HN001EMC    | Notebook    | [c24f015f0f](https://linux-hardware.org/?probe=c24f015f0f) | Jan 13, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [61f2cf2ae4](https://linux-hardware.org/?probe=61f2cf2ae4) | Jan 12, 2020 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [458ececa20](https://linux-hardware.org/?probe=458ececa20) | Jan 12, 2020 |
| MSI        | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek    | P8Z77-V PRO                 | Desktop     | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock     | H91M-PLUS                   | Desktop     | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [2979b0995f](https://linux-hardware.org/?probe=2979b0995f) | Dec 21, 2019 |
| Lenovo     | ThinkPad X1 Carbon 6th 2... | Notebook    | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [2ce515411e](https://linux-hardware.org/?probe=2ce515411e) | Dec 13, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [2862a08f39](https://linux-hardware.org/?probe=2862a08f39) | Nov 29, 2019 |
| Lenovo     | ThinkPad X1 Carbon 7th 2... | Notebook    | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo     | ThinkPad X1 Carbon 7th 2... | Notebook    | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [6d1db662fe](https://linux-hardware.org/?probe=6d1db662fe) | Nov 17, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [997d2ae2bf](https://linux-hardware.org/?probe=997d2ae2bf) | Nov 16, 2019 |
| Lenovo     | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo     | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Dell       | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP         | 250 G4 Notebook PC          | Notebook    | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP         | 250 G4 Notebook PC          | Notebook    | [e5994eed73](https://linux-hardware.org/?probe=e5994eed73) | Nov 07, 2019 |
| HP         | 250 G4 Notebook PC          | Notebook    | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo     | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Supermicro | X7DWN+                      | Desktop     | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro | X7DWN+                      | Desktop     | [c0df153404](https://linux-hardware.org/?probe=c0df153404) | Oct 25, 2019 |
| Supermicro | X7DWN+                      | Desktop     | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Lenovo     | ThinkPad T590 20N5S2NC0V    | Notebook    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo     | ThinkPad T480s 20L8S2N80... | Notebook    | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 7.91%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 13        | 7.34%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 6.21%   |
| 4.18.0-305.el8.x86_64        | 10        | 5.65%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 5.08%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 4.52%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 8         | 4.52%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 7         | 3.95%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 7         | 3.95%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 7         | 3.95%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 7         | 3.95%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 6         | 3.39%   |
| 4.18.0-193.el8.x86_64        | 6         | 3.39%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 3.39%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 2.82%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 2.82%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 2.26%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4         | 2.26%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 2.26%   |
| 4.18.0-147.el8.x86_64        | 4         | 2.26%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 4         | 2.26%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.69%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.13%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 1.13%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 2         | 1.13%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 2         | 1.13%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.13%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 2         | 1.13%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.56%   |
| 5.13.0-1.el8.elrepo.x86_64   | 1         | 0.56%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1         | 0.56%   |
| 4.19.150                     | 1         | 0.56%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.56%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.56%   |
| 4.18.0-221.el8.x86_64        | 1         | 0.56%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.56%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.56%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.56%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.56%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.56%   |
| Unknown                      | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 136       | 96.45%  |
| 5.9.1    | 1         | 0.71%   |
| 5.13.0   | 1         | 0.71%   |
| 5.10.6   | 1         | 0.71%   |
| 4.19.150 | 1         | 0.71%   |
| Unknown  | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 136       | 96.45%  |
| 5.9     | 1         | 0.71%   |
| 5.13    | 1         | 0.71%   |
| 5.10    | 1         | 0.71%   |
| 4.19    | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 140       | 99.29%  |
| Unknown | 1         | 0.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 121       | 82.31%  |
| Unknown       | 12        | 8.16%   |
| GNOME Classic | 7         | 4.76%   |
| KDE5          | 5         | 3.4%    |
| KDE           | 2         | 1.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 84        | 56.76%  |
| Wayland | 58        | 39.19%  |
| Unknown | 6         | 4.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 117       | 80.14%  |
| GDM     | 29        | 19.86%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 97        | 66.9%   |
| Unknown | 10        | 6.9%    |
| en_GB   | 7         | 4.83%   |
| pl_PL   | 4         | 2.76%   |
| fr_FR   | 4         | 2.76%   |
| en_IN   | 4         | 2.76%   |
| ru_RU   | 3         | 2.07%   |
| pt_BR   | 2         | 1.38%   |
| nl_NL   | 2         | 1.38%   |
| de_DE   | 2         | 1.38%   |
| ko_KR   | 1         | 0.69%   |
| ja_JP   | 1         | 0.69%   |
| it_IT   | 1         | 0.69%   |
| es_ES   | 1         | 0.69%   |
| es_EC   | 1         | 0.69%   |
| es_AR   | 1         | 0.69%   |
| en_NZ   | 1         | 0.69%   |
| en_IE   | 1         | 0.69%   |
| de_CH   | 1         | 0.69%   |
| cs_CZ   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 111       | 76.55%  |
| BIOS | 34        | 23.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 126       | 89.36%  |
| Ext4    | 14        | 9.93%   |
| Unknown | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 110       | 75.34%  |
| GPT     | 31        | 21.23%  |
| MBR     | 5         | 3.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 97.87%  |
| Yes       | 3         | 2.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 93.01%  |
| Yes       | 10        | 6.99%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 58        | 41.13%  |
| Dell                | 22        | 15.6%   |
| Hewlett-Packard     | 19        | 13.48%  |
| ASUSTek Computer    | 16        | 11.35%  |
| Gigabyte Technology | 6         | 4.26%   |
| MSI                 | 4         | 2.84%   |
| ASRock              | 4         | 2.84%   |
| Supermicro          | 2         | 1.42%   |
| Sony                | 2         | 1.42%   |
| Intel               | 2         | 1.42%   |
| TUXEDO              | 1         | 0.71%   |
| Toshiba             | 1         | 0.71%   |
| Timi                | 1         | 0.71%   |
| Alienware           | 1         | 0.71%   |
| Acer                | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 3         | 2.13%   |
| ASUS All Series                          | 3         | 2.13%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.42%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.42%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.42%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.42%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.42%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.42%   |
| HP EliteBook 8460p                       | 2         | 1.42%   |
| Dell Latitude E6430                      | 2         | 1.42%   |
| Dell Latitude 5300                       | 2         | 1.42%   |
| TUXEDO N13xWU                            | 1         | 0.71%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.71%   |
| Timi TM1707                              | 1         | 0.71%   |
| Supermicro X7DW3                         | 1         | 0.71%   |
| Supermicro X10DRi                        | 1         | 0.71%   |
| Sony VPCEB4L1R                           | 1         | 0.71%   |
| Sony VPCEB23FM                           | 1         | 0.71%   |
| MSI MS-7B51                              | 1         | 0.71%   |
| MSI MS-7B33                              | 1         | 0.71%   |
| MSI MS-7A37                              | 1         | 0.71%   |
| MSI MS-7752                              | 1         | 0.71%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.71%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.71%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.71%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.71%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.71%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.71%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.71%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.71%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.71%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.71%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.71%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.71%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.71%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.71%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.71%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.71%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.71%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.71%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.71%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.71%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 0.71%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 0.71%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 0.71%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 0.71%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 0.71%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 0.71%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 0.71%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 0.71%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 0.71%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 0.71%   |
| Lenovo ThinkPad E490 20N8000JAD          | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 51        | 36.17%  |
| Dell Latitude       | 8         | 5.67%   |
| Dell Precision      | 7         | 4.96%   |
| HP EliteBook        | 4         | 2.84%   |
| Lenovo ThinkCentre  | 3         | 2.13%   |
| Dell Inspiron       | 3         | 2.13%   |
| ASUS PRIME          | 3         | 2.13%   |
| ASUS All            | 3         | 2.13%   |
| HP ZBook            | 2         | 1.42%   |
| HP Z230             | 2         | 1.42%   |
| ASUS ROG            | 2         | 1.42%   |
| TUXEDO N13xWU       | 1         | 0.71%   |
| Toshiba Satellite   | 1         | 0.71%   |
| Timi TM1707         | 1         | 0.71%   |
| Supermicro X7DW3    | 1         | 0.71%   |
| Supermicro X10DRi   | 1         | 0.71%   |
| Sony VPCEB4L1R      | 1         | 0.71%   |
| Sony VPCEB23FM      | 1         | 0.71%   |
| MSI MS-7B51         | 1         | 0.71%   |
| MSI MS-7B33         | 1         | 0.71%   |
| MSI MS-7A37         | 1         | 0.71%   |
| MSI MS-7752         | 1         | 0.71%   |
| Lenovo Yoga         | 1         | 0.71%   |
| Lenovo ThinkSystem  | 1         | 0.71%   |
| Lenovo ThinkpadT460 | 1         | 0.71%   |
| Lenovo S40-40       | 1         | 0.71%   |
| Intel NUC10i7FNK    | 1         | 0.71%   |
| Intel DX79SR        | 1         | 0.71%   |
| HP Z840             | 1         | 0.71%   |
| HP Z620             | 1         | 0.71%   |
| HP Z440             | 1         | 0.71%   |
| HP ProLiant         | 1         | 0.71%   |
| HP ProBook          | 1         | 0.71%   |
| HP Pavilion         | 1         | 0.71%   |
| HP OMEN             | 1         | 0.71%   |
| HP EliteDesk        | 1         | 0.71%   |
| HP 290              | 1         | 0.71%   |
| HP 260-P020il       | 1         | 0.71%   |
| HP 250              | 1         | 0.71%   |
| Gigabyte Z97N-WIFI  | 1         | 0.71%   |
| Gigabyte Z490       | 1         | 0.71%   |
| Gigabyte Z390       | 1         | 0.71%   |
| Gigabyte B85M-D3V-A | 1         | 0.71%   |
| Gigabyte B75-D3V    | 1         | 0.71%   |
| Gigabyte 970A-D3    | 1         | 0.71%   |
| Dell XPS            | 1         | 0.71%   |
| Dell Vostro         | 1         | 0.71%   |
| Dell PowerEdge      | 1         | 0.71%   |
| Dell G3             | 1         | 0.71%   |
| ASUS Zephyrus       | 1         | 0.71%   |
| ASUS Z10PE-D16      | 1         | 0.71%   |
| ASUS X550VX         | 1         | 0.71%   |
| ASUS TUF            | 1         | 0.71%   |
| ASUS Pro            | 1         | 0.71%   |
| ASUS P8Z77-V        | 1         | 0.71%   |
| ASUS MINIPC         | 1         | 0.71%   |
| ASUS GL502VMK       | 1         | 0.71%   |
| ASRock X99E-ITX     | 1         | 0.71%   |
| ASRock H91M-PLUS    | 1         | 0.71%   |
| ASRock H270         | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 27        | 19.15%  |
| 2019 | 27        | 19.15%  |
| 2018 | 23        | 16.31%  |
| 2017 | 12        | 8.51%   |
| 2012 | 12        | 8.51%   |
| 2015 | 9         | 6.38%   |
| 2016 | 8         | 5.67%   |
| 2011 | 7         | 4.96%   |
| 2013 | 6         | 4.26%   |
| 2021 | 3         | 2.13%   |
| 2014 | 3         | 2.13%   |
| 2010 | 3         | 2.13%   |
| 2009 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 89        | 63.12%  |
| Desktop     | 44        | 31.21%  |
| Server      | 4         | 2.84%   |
| Mini pc     | 2         | 1.42%   |
| Convertible | 1         | 0.71%   |
| All in one  | 1         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 128       | 90.14%  |
| Enabled  | 14        | 9.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 39        | 26.9%   |
| 16.01-24.0      | 26        | 17.93%  |
| 4.01-8.0        | 24        | 16.55%  |
| 8.01-16.0       | 21        | 14.48%  |
| 64.01-256.0     | 19        | 13.1%   |
| 3.01-4.0        | 7         | 4.83%   |
| 24.01-32.0      | 6         | 4.14%   |
| More than 256.0 | 2         | 1.38%   |
| Unknown         | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 61        | 37.2%   |
| 8.01-16.0       | 29        | 17.68%  |
| 2.01-3.0        | 28        | 17.07%  |
| 3.01-4.0        | 26        | 15.85%  |
| 1.01-2.0        | 11        | 6.71%   |
| 16.01-24.0      | 3         | 1.83%   |
| 24.01-32.0      | 2         | 1.22%   |
| More than 256.0 | 1         | 0.61%   |
| 32.01-64.0      | 1         | 0.61%   |
| 0.51-1.0        | 1         | 0.61%   |
| Unknown         | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 86        | 57.72%  |
| 2      | 34        | 22.82%  |
| 3      | 15        | 10.07%  |
| 4      | 6         | 4.03%   |
| 5      | 3         | 2.01%   |
| 8      | 2         | 1.34%   |
| 6      | 2         | 1.34%   |
| 7      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 74.83%  |
| Yes       | 36        | 25.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 92.96%  |
| No        | 10        | 7.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 80.85%  |
| No        | 27        | 19.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 62.33%  |
| No        | 55        | 37.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 31        | 21.83%  |
| India        | 15        | 10.56%  |
| UK           | 9         | 6.34%   |
| Germany      | 7         | 4.93%   |
| Czechia      | 7         | 4.93%   |
| France       | 6         | 4.23%   |
| Canada       | 6         | 4.23%   |
| Poland       | 4         | 2.82%   |
| Netherlands  | 4         | 2.82%   |
| Switzerland  | 3         | 2.11%   |
| Russia       | 3         | 2.11%   |
| Lithuania    | 3         | 2.11%   |
| Italy        | 3         | 2.11%   |
| Brazil       | 3         | 2.11%   |
| Ukraine      | 2         | 1.41%   |
| Spain        | 2         | 1.41%   |
| South Korea  | 2         | 1.41%   |
| South Africa | 2         | 1.41%   |
| Romania      | 2         | 1.41%   |
| Mexico       | 2         | 1.41%   |
| Japan        | 2         | 1.41%   |
| Australia    | 2         | 1.41%   |
| Argentina    | 2         | 1.41%   |
| Turkmenistan | 1         | 0.7%    |
| Sweden       | 1         | 0.7%    |
| Singapore    | 1         | 0.7%    |
| Saudi Arabia | 1         | 0.7%    |
| Portugal     | 1         | 0.7%    |
| Pakistan     | 1         | 0.7%    |
| New Zealand  | 1         | 0.7%    |
| Nepal        | 1         | 0.7%    |
| Myanmar      | 1         | 0.7%    |
| Morocco      | 1         | 0.7%    |
| Luxembourg   | 1         | 0.7%    |
| Kuwait       | 1         | 0.7%    |
| Ireland      | 1         | 0.7%    |
| Indonesia    | 1         | 0.7%    |
| Egypt        | 1         | 0.7%    |
| Ecuador      | 1         | 0.7%    |
| Colombia     | 1         | 0.7%    |
| Bulgaria     | 1         | 0.7%    |
| Belarus      | 1         | 0.7%    |
| Armenia      | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Brno                     | 5         | 3.25%   |
| Munich                   | 3         | 1.95%   |
| Toronto                  | 2         | 1.3%    |
| San Jose                 | 2         | 1.3%    |
| Mumbai                   | 2         | 1.3%    |
| Milan                    | 2         | 1.3%    |
| Mexico City              | 2         | 1.3%    |
| Kyiv                     | 2         | 1.3%    |
| Doetinchem               | 2         | 1.3%    |
| Coimbatore               | 2         | 1.3%    |
| Chicago                  | 2         | 1.3%    |
| Bengaluru                | 2         | 1.3%    |
| ? iauliai                | 2         | 1.3%    |
| Aurora                   | 2         | 1.3%    |
| Yerevan                  | 1         | 0.65%   |
| Wroclaw                  | 1         | 0.65%   |
| Wiesbaden                | 1         | 0.65%   |
| Weybridge                | 1         | 0.65%   |
| Webster                  | 1         | 0.65%   |
| Warsaw                   | 1         | 0.65%   |
| Valmontone               | 1         | 0.65%   |
| Vaestra Froelunda        | 1         | 0.65%   |
| Tauranga                 | 1         | 0.65%   |
| Taringa                  | 1         | 0.65%   |
| Suwon                    | 1         | 0.65%   |
| Sumida                   | 1         | 0.65%   |
| Stroud                   | 1         | 0.65%   |
| Spokane                  | 1         | 0.65%   |
| Sofia                    | 1         | 0.65%   |
| Singapore                | 1         | 0.65%   |
| Sheffield                | 1         | 0.65%   |
| Seoul                    | 1         | 0.65%   |
| Saratov                  | 1         | 0.65%   |
| San Francisco            | 1         | 0.65%   |
| Sammamish                | 1         | 0.65%   |
| Salvador                 | 1         | 0.65%   |
| Sal?©                    | 1         | 0.65%   |
| Saint-Ismier             | 1         | 0.65%   |
| Saint-Alphonse-Rodriguez | 1         | 0.65%   |
| Sagaing                  | 1         | 0.65%   |
| Roudnice nad Labem       | 1         | 0.65%   |
| Roha                     | 1         | 0.65%   |
| Reims                    | 1         | 0.65%   |
| Raleigh                  | 1         | 0.65%   |
| Quito                    | 1         | 0.65%   |
| Queenscliff              | 1         | 0.65%   |
| Queens                   | 1         | 0.65%   |
| Pune                     | 1         | 0.65%   |
| Prague                   | 1         | 0.65%   |
| Poznan                   | 1         | 0.65%   |
| Portalegre               | 1         | 0.65%   |
| Port Elizabeth           | 1         | 0.65%   |
| Pleasanton               | 1         | 0.65%   |
| Pickerington             | 1         | 0.65%   |
| Pernis                   | 1         | 0.65%   |
| Paris                    | 1         | 0.65%   |
| Paraiso do Tocantins     | 1         | 0.65%   |
| Paragould                | 1         | 0.65%   |
| Paracuellos de Jarama    | 1         | 0.65%   |
| Oyama                    | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 69     | 19.82%  |
| WDC                 | 32        | 57     | 14.75%  |
| Seagate             | 25        | 37     | 11.52%  |
| Toshiba             | 16        | 24     | 7.37%   |
| Sandisk             | 14        | 21     | 6.45%   |
| SK Hynix            | 13        | 16     | 5.99%   |
| Kingston            | 10        | 13     | 4.61%   |
| Intel               | 10        | 14     | 4.61%   |
| Unknown             | 6         | 8      | 2.76%   |
| Micron Technology   | 6         | 13     | 2.76%   |
| Crucial             | 6         | 10     | 2.76%   |
| HGST                | 4         | 4      | 1.84%   |
| A-DATA Technology   | 4         | 4      | 1.84%   |
| Phison              | 3         | 5      | 1.38%   |
| Hitachi             | 3         | 3      | 1.38%   |
| Corsair             | 3         | 3      | 1.38%   |
| Silicon Motion      | 2         | 3      | 0.92%   |
| PNY                 | 2         | 5      | 0.92%   |
| Lenovo              | 2         | 2      | 0.92%   |
| Hewlett-Packard     | 2         | 3      | 0.92%   |
| XPG                 | 1         | 1      | 0.46%   |
| Team                | 1         | 2      | 0.46%   |
| T-FORCE             | 1         | 2      | 0.46%   |
| SMI                 | 1         | 2      | 0.46%   |
| OCZ                 | 1         | 2      | 0.46%   |
| Lite-On             | 1         | 1      | 0.46%   |
| Hoodisk             | 1         | 1      | 0.46%   |
| Gigabyte Technology | 1         | 1      | 0.46%   |
| DELLBOSS            | 1         | 1      | 0.46%   |
| Dell                | 1         | 1      | 0.46%   |
| China               | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB       | 9         | 3.63%   |
| Sandisk NVMe SSD Drive 256GB        | 6         | 2.42%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 2.42%   |
| Samsung SSD 860 EVO 1TB             | 5         | 2.02%   |
| Samsung NVMe SSD Drive 256GB        | 5         | 2.02%   |
| Samsung NVMe SSD Drive 1024GB       | 5         | 2.02%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 4         | 1.61%   |
| Toshiba NVMe SSD Drive 512GB        | 3         | 1.21%   |
| Samsung NVMe SSD Drive 500GB        | 3         | 1.21%   |
| Micron NVMe SSD Drive 256GB         | 3         | 1.21%   |
| HGST HTS721010A9E630 1TB            | 3         | 1.21%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 0.81%   |
| Unknown NVMe SSD Drive 256GB        | 2         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.81%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 0.81%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 0.81%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.81%   |
| Seagate Expansion 1TB               | 2         | 0.81%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.81%   |
| Samsung Portable SSD T5 500GB       | 2         | 0.81%   |
| Samsung NVMe SSD Drive 2TB          | 2         | 0.81%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.81%   |
| Kingston SUV500120G 120GB SSD       | 2         | 0.81%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.81%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.81%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.81%   |
| Intel NVMe SSD Drive 2TB            | 2         | 0.81%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.81%   |
| Corsair Force LE SSD 240GB          | 2         | 0.81%   |
| XPG NVMe SSD Drive 1024GB           | 1         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.4%    |
| WDC WDS400T2B0A-00SM50 4TB SSD      | 1         | 0.4%    |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.4%    |
| WDC WDS240G1G0A-00SS50 240GB SSD    | 1         | 0.4%    |
| WDC WDS200T2B0B-00YS70 2TB SSD      | 1         | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1         | 0.4%    |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 0.4%    |
| WDC WD6400BPVT-75HXZT1 640GB        | 1         | 0.4%    |
| WDC WD60 EFAX-68JH4N1 6TB           | 1         | 0.4%    |
| WDC WD60 EFAX-68JH4N0 6TB           | 1         | 0.4%    |
| WDC WD5003ABYZ-011FA0 500GB         | 1         | 0.4%    |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 0.4%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 0.4%    |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 0.4%    |
| WDC WD50 00LPVX-00V0TT0 500GB       | 1         | 0.4%    |
| WDC WD40PURZ-85TTDY0 4TB            | 1         | 0.4%    |
| WDC WD40EZRZ-19GXCB0 4TB            | 1         | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB            | 1         | 0.4%    |
| WDC WD4005FZBX-00K5WB0 4TB          | 1         | 0.4%    |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 0.4%    |
| WDC WD2500BEKT-75F3T0 250GB         | 1         | 0.4%    |
| WDC WD2500AAKX-083CA1 250GB         | 1         | 0.4%    |
| WDC WD20PURZ-85GU6Y0 2TB            | 1         | 0.4%    |
| WDC WD20EARS-22MVWB0 2TB            | 1         | 0.4%    |
| WDC WD2003FZEX-00SRLA0 2TB          | 1         | 0.4%    |
| WDC WD20 SPZX-11UA7T0 2TB           | 1         | 0.4%    |
| WDC WD10SPZX-22Z10T0 1TB            | 1         | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.4%    |
| WDC WD10SPZX-08Z10 1TB              | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 36     | 37.31%  |
| WDC                 | 24        | 45     | 35.82%  |
| Toshiba             | 7         | 11     | 10.45%  |
| HGST                | 4         | 4      | 5.97%   |
| Hitachi             | 3         | 3      | 4.48%   |
| Unknown             | 1         | 1      | 1.49%   |
| Samsung Electronics | 1         | 1      | 1.49%   |
| Hewlett-Packard     | 1         | 1      | 1.49%   |
| DELLBOSS            | 1         | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 30%     |
| Kingston            | 10        | 13     | 14.29%  |
| WDC                 | 6         | 8      | 8.57%   |
| Crucial             | 6         | 10     | 8.57%   |
| SanDisk             | 5         | 7      | 7.14%   |
| A-DATA Technology   | 4         | 4      | 5.71%   |
| Micron Technology   | 3         | 8      | 4.29%   |
| Corsair             | 3         | 3      | 4.29%   |
| SK Hynix            | 2         | 5      | 2.86%   |
| PNY                 | 2         | 5      | 2.86%   |
| Intel               | 2         | 3      | 2.86%   |
| Toshiba             | 1         | 1      | 1.43%   |
| Team                | 1         | 2      | 1.43%   |
| Seagate             | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 2      | 1.43%   |
| Hoodisk             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 75        | 118    | 36.76%  |
| SSD     | 64        | 100    | 31.37%  |
| HDD     | 60        | 103    | 29.41%  |
| MMC     | 3         | 4      | 1.47%   |
| Unknown | 2         | 4      | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 189    | 48%     |
| NVMe | 75        | 118    | 42.86%  |
| SAS  | 13        | 18     | 7.43%   |
| MMC  | 3         | 4      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 90     | 44.62%  |
| 0.51-1.0   | 40        | 65     | 30.77%  |
| 1.01-2.0   | 18        | 21     | 13.85%  |
| 3.01-4.0   | 9         | 19     | 6.92%   |
| 4.01-10.0  | 3         | 6      | 2.31%   |
| 2.01-3.0   | 1         | 1      | 0.77%   |
| 10.01-20.0 | 1         | 1      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 36.24%  |
| 251-500        | 26        | 17.45%  |
| 501-1000       | 23        | 15.44%  |
| More than 3000 | 14        | 9.4%    |
| 1001-2000      | 14        | 9.4%    |
| 2001-3000      | 5         | 3.36%   |
| 51-100         | 5         | 3.36%   |
| Unknown        | 4         | 2.68%   |
| 21-50          | 3         | 2.01%   |
| 1-20           | 1         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 38        | 23.6%   |
| 101-250        | 31        | 19.25%  |
| 1-20           | 30        | 18.63%  |
| 51-100         | 22        | 13.66%  |
| 251-500        | 13        | 8.07%   |
| 501-1000       | 11        | 6.83%   |
| 1001-2000      | 6         | 3.73%   |
| Unknown        | 4         | 2.48%   |
| More than 3000 | 3         | 1.86%   |
| 2001-3000      | 3         | 1.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB | 1         | 1      | 50%     |
| Hitachi HDS722020ALA330 2TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 112       | 255    | 74.17%  |
| Works    | 37        | 72     | 24.5%   |
| Malfunc  | 2         | 2      | 1.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 89        | 47.34%  |
| Samsung Electronics          | 28        | 14.89%  |
| SK Hynix                     | 11        | 5.85%   |
| Sandisk                      | 11        | 5.85%   |
| AMD                          | 11        | 5.85%   |
| Toshiba America Info Systems | 8         | 4.26%   |
| Marvell Technology Group     | 4         | 2.13%   |
| Broadcom / LSI               | 4         | 2.13%   |
| Silicon Motion               | 3         | 1.6%    |
| Phison Electronics           | 3         | 1.6%    |
| Micron Technology            | 3         | 1.6%    |
| ASMedia Technology           | 3         | 1.6%    |
| LSI Logic / Symbios Logic    | 2         | 1.06%   |
| Lenovo                       | 2         | 1.06%   |
| KIOXIA                       | 2         | 1.06%   |
| Lite-On Technology           | 1         | 0.53%   |
| Hewlett-Packard              | 1         | 0.53%   |
| Biwin Storage Technology     | 1         | 0.53%   |
| ADATA Technology             | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 21        | 10.1%   |
| SK Hynix Non-Volatile memory controller                                          | 11        | 5.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 4.81%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 4.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 2.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 5         | 2.4%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 5         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 2.4%    |
| Intel SSD 660P Series                                                            | 4         | 1.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 1.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.44%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.44%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.44%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 1.44%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.96%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.96%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.96%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.96%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.96%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2         | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.96%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.48%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.48%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.48%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.48%   |
| Samsung NVMe SSD Controller PM173X                                               | 1         | 0.48%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.48%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.48%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 1         | 0.48%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.48%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.48%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                            | 1         | 0.48%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                   | 1         | 0.48%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                             | 1         | 0.48%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.48%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.48%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.48%   |
| Intel NVMe Datacenter SSD [Optane]                                               | 1         | 0.48%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.48%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                       | 1         | 0.48%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 0.48%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 0.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 88        | 48.35%  |
| NVMe | 75        | 41.21%  |
| RAID | 12        | 6.59%   |
| IDE  | 4         | 2.2%    |
| SAS  | 3         | 1.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 127       | 90.07%  |
| AMD    | 14        | 9.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 6.38%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 5.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 5         | 3.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 2.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.13%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3         | 2.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.13%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1.42%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.42%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.42%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.42%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.42%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.42%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.42%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 1.42%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.42%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.71%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.71%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.71%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.71%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.71%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.71%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.71%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.71%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.71%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.71%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.71%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.71%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.71%   |
| Intel Core i7-9700F CPU @ 3.00GHz             | 1         | 0.71%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.71%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.71%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.71%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.71%   |
| Intel Core i7-3820 CPU @ 3.60GHz              | 1         | 0.71%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.71%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.71%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.71%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.71%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.71%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 65        | 46.1%   |
| Intel Core i5      | 32        | 22.7%   |
| Intel Xeon         | 14        | 9.93%   |
| Intel Core i3      | 9         | 6.38%   |
| AMD Ryzen 7        | 5         | 3.55%   |
| Other              | 2         | 1.42%   |
| Intel Pentium Gold | 2         | 1.42%   |
| Intel Core i9      | 2         | 1.42%   |
| AMD Ryzen 9        | 2         | 1.42%   |
| AMD Ryzen 3        | 2         | 1.42%   |
| AMD EPYC           | 2         | 1.42%   |
| Intel Pentium      | 1         | 0.71%   |
| AMD Ryzen 7 PRO    | 1         | 0.71%   |
| AMD Ryzen 5        | 1         | 0.71%   |
| AMD FX             | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 61        | 43.26%  |
| 2      | 34        | 24.11%  |
| 6      | 26        | 18.44%  |
| 8      | 9         | 6.38%   |
| 12     | 3         | 2.13%   |
| 20     | 2         | 1.42%   |
| 16     | 2         | 1.42%   |
| 96     | 1         | 0.71%   |
| 64     | 1         | 0.71%   |
| 36     | 1         | 0.71%   |
| 24     | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 93.62%  |
| 2      | 9         | 6.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 123       | 86.62%  |
| 1      | 19        | 13.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 95.8%   |
| Unknown        | 6         | 4.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 21        | 14.69%  |
| 0x906ea    | 13        | 9.09%   |
| 0x806ea    | 10        | 6.99%   |
| 0xa0652    | 9         | 6.29%   |
| 0x306c3    | 9         | 6.29%   |
| 0x306a9    | 9         | 6.29%   |
| 0x206a7    | 7         | 4.9%    |
| 0x906ed    | 6         | 4.2%    |
| 0x506e3    | 6         | 4.2%    |
| Unknown    | 5         | 3.5%    |
| 0x906e9    | 4         | 2.8%    |
| 0x806e9    | 4         | 2.8%    |
| 0x406e3    | 4         | 2.8%    |
| 0x306f2    | 3         | 2.1%    |
| 0x306d4    | 3         | 2.1%    |
| 0x20655    | 3         | 2.1%    |
| 0x08108102 | 3         | 2.1%    |
| 0x406f1    | 2         | 1.4%    |
| 0x206d7    | 2         | 1.4%    |
| 0x08600103 | 2         | 1.4%    |
| 0xa0660    | 1         | 0.7%    |
| 0xa0655    | 1         | 0.7%    |
| 0x906eb    | 1         | 0.7%    |
| 0x806d1    | 1         | 0.7%    |
| 0x806c1    | 1         | 0.7%    |
| 0x40651    | 1         | 0.7%    |
| 0x306e4    | 1         | 0.7%    |
| 0x20652    | 1         | 0.7%    |
| 0x10676    | 1         | 0.7%    |
| 0x0a001119 | 1         | 0.7%    |
| 0x08701021 | 1         | 0.7%    |
| 0x08701013 | 1         | 0.7%    |
| 0x08600104 | 1         | 0.7%    |
| 0x08301034 | 1         | 0.7%    |
| 0x0810100b | 1         | 0.7%    |
| 0x08001138 | 1         | 0.7%    |
| 0x08001137 | 1         | 0.7%    |
| 0x06000852 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 60        | 42.25%  |
| Haswell     | 14        | 9.86%   |
| IvyBridge   | 11        | 7.75%   |
| CometLake   | 11        | 7.75%   |
| Skylake     | 10        | 7.04%   |
| SandyBridge | 9         | 6.34%   |
| Zen 2       | 6         | 4.23%   |
| Broadwell   | 5         | 3.52%   |
| Westmere    | 4         | 2.82%   |
| Zen+        | 3         | 2.11%   |
| Zen         | 3         | 2.11%   |
| Unknown     | 2         | 1.41%   |
| TigerLake   | 1         | 0.7%    |
| Piledriver  | 1         | 0.7%    |
| Penryn      | 1         | 0.7%    |
| Icelake     | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 96        | 55.17%  |
| Nvidia                     | 55        | 31.61%  |
| AMD                        | 19        | 10.92%  |
| Matrox Electronics Systems | 3         | 1.72%   |
| ASPEED Technology          | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 14        | 7.95%   |
| Intel UHD Graphics 620                                                      | 10        | 5.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 8         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 8         | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 3.98%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 2.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 2.27%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.7%    |
| Intel HD Graphics 620                                                       | 3         | 1.7%    |
| Intel HD Graphics 5500                                                      | 3         | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.7%    |
| AMD Renoir                                                                  | 3         | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.14%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.14%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 1.14%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 1.14%   |
| Intel HD Graphics 630                                                       | 2         | 1.14%   |
| Intel HD Graphics 530                                                       | 2         | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.14%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.57%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.57%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.57%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.57%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.57%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.57%   |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.57%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.57%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.57%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.57%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.57%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1         | 0.57%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.57%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 0.57%   |
| Nvidia GM107GL [NVS 810]                                                    | 1         | 0.57%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.57%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.57%   |
| Nvidia GK107GLM [Quadro K2000M]                                             | 1         | 0.57%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1         | 0.57%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 0.57%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 0.57%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1         | 0.57%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 68        | 47.55%  |
| 1 x Nvidia      | 34        | 23.78%  |
| Intel + Nvidia  | 18        | 12.59%  |
| 1 x AMD         | 11        | 7.69%   |
| Intel + AMD     | 6         | 4.2%    |
| 1 x Matrox      | 2         | 1.4%    |
| AMD + Nvidia    | 2         | 1.4%    |
| Nvidia + Matrox | 1         | 0.7%    |
| Nvidia + ASPEED | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 114       | 79.72%  |
| Proprietary | 26        | 18.18%  |
| Unknown     | 3         | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 58.9%   |
| 1.01-2.0   | 17        | 11.64%  |
| 3.01-4.0   | 12        | 8.22%   |
| 5.01-6.0   | 7         | 4.79%   |
| 0.51-1.0   | 7         | 4.79%   |
| 0.01-0.5   | 6         | 4.11%   |
| 7.01-8.0   | 5         | 3.42%   |
| 2.01-3.0   | 3         | 2.05%   |
| 8.01-16.0  | 2         | 1.37%   |
| 4.01-5.0   | 1         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 10.7%   |
| Samsung Electronics     | 18        | 9.63%   |
| Dell                    | 18        | 9.63%   |
| Lenovo                  | 16        | 8.56%   |
| Chimei Innolux          | 15        | 8.02%   |
| BOE                     | 15        | 8.02%   |
| LG Display              | 14        | 7.49%   |
| Goldstar                | 13        | 6.95%   |
| Hewlett-Packard         | 11        | 5.88%   |
| Acer                    | 5         | 2.67%   |
| Sharp                   | 4         | 2.14%   |
| InfoVision              | 4         | 2.14%   |
| Eizo                    | 4         | 2.14%   |
| BenQ                    | 4         | 2.14%   |
| Philips                 | 3         | 1.6%    |
| Ancor Communications    | 3         | 1.6%    |
| ViewSonic               | 2         | 1.07%   |
| PANDA                   | 2         | 1.07%   |
| LGD                     | 2         | 1.07%   |
| Lenovo Group Limited    | 2         | 1.07%   |
| Iiyama                  | 2         | 1.07%   |
| Gigabyte Technology     | 2         | 1.07%   |
| Sun                     | 1         | 0.53%   |
| Sceptre Tech            | 1         | 0.53%   |
| Planar                  | 1         | 0.53%   |
| LG Electronics          | 1         | 0.53%   |
| Insignia                | 1         | 0.53%   |
| Chi Mei Optoelectronics | 1         | 0.53%   |
| BOE Technology Group    | 1         | 0.53%   |
| AOC                     | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 2.48%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 1.98%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.49%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.49%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 3         | 1.49%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 1.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 3         | 1.49%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.49%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.49%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.99%   |
| PANDA LCD Monitor NCP0036 1920x1080 340x190mm 15.3-inch               | 2         | 0.99%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.99%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.99%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.99%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.99%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 0.99%   |
| Hewlett-Packard 27y HPN351C 1920x1080 598x336mm 27.0-inch             | 2         | 0.99%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 2         | 0.99%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.99%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.99%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.5%    |
| ViewSonic LCD Monitor VSC3E32 1920x1080 600x340mm 27.2-inch           | 1         | 0.5%    |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.5%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.5%    |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.5%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1         | 0.5%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.5%    |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch     | 1         | 0.5%    |
| Samsung Electronics S22B300 SAM08A9 1440x900 440x250mm 19.9-inch      | 1         | 0.5%    |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.5%    |
| Samsung Electronics LCD Monitor S22B150                               | 1         | 0.5%    |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1         | 0.5%    |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 698x393mm 31.5-inch    | 1         | 0.5%    |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.5%    |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch     | 1         | 0.5%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.5%    |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.5%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.5%    |
| LG Electronics LCD Monitor W2486 1920x1080                            | 1         | 0.5%    |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.5%    |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.5%    |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 52.69%  |
| 3840x2160 (4K)     | 14        | 8.38%   |
| 1366x768 (WXGA)    | 14        | 8.38%   |
| 2560x1440 (QHD)    | 12        | 7.19%   |
| 1600x900 (HD+)     | 11        | 6.59%   |
| 1920x1200 (WUXGA)  | 5         | 2.99%   |
| 3840x1080          | 4         | 2.4%    |
| 2560x1080          | 4         | 2.4%    |
| Unknown            | 4         | 2.4%    |
| 3440x1440          | 2         | 1.2%    |
| 1440x900 (WXGA+)   | 2         | 1.2%    |
| 9600x2160          | 1         | 0.6%    |
| 7680x2160          | 1         | 0.6%    |
| 6400x2160          | 1         | 0.6%    |
| 2048x1152          | 1         | 0.6%    |
| 1680x1050 (WSXGA+) | 1         | 0.6%    |
| 1280x800 (WXGA)    | 1         | 0.6%    |
| 1280x720 (HD)      | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 39        | 20.97%  |
| 24      | 23        | 12.37%  |
| 14      | 21        | 11.29%  |
| 27      | 19        | 10.22%  |
| 13      | 15        | 8.06%   |
| 23      | 13        | 6.99%   |
| Unknown | 11        | 5.91%   |
| 21      | 9         | 4.84%   |
| 31      | 6         | 3.23%   |
| 34      | 5         | 2.69%   |
| 12      | 5         | 2.69%   |
| 20      | 4         | 2.15%   |
| 17      | 3         | 1.61%   |
| 47      | 2         | 1.08%   |
| 32      | 2         | 1.08%   |
| 18      | 2         | 1.08%   |
| 54      | 1         | 0.54%   |
| 49      | 1         | 0.54%   |
| 40      | 1         | 0.54%   |
| 39      | 1         | 0.54%   |
| 25      | 1         | 0.54%   |
| 22      | 1         | 0.54%   |
| 19      | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 39.89%  |
| 501-600     | 46        | 25.84%  |
| 401-500     | 16        | 8.99%   |
| Unknown     | 11        | 6.18%   |
| 601-700     | 9         | 5.06%   |
| 201-300     | 9         | 5.06%   |
| 701-800     | 7         | 3.93%   |
| 1001-1500   | 4         | 2.25%   |
| 351-400     | 3         | 1.69%   |
| 801-900     | 2         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 121       | 81.76%  |
| 16/10   | 11        | 7.43%   |
| Unknown | 9         | 6.08%   |
| 21/9    | 5         | 3.38%   |
| 32/9    | 1         | 0.68%   |
| 3/2     | 1         | 0.68%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 21.31%  |
| 201-250        | 34        | 18.58%  |
| 81-90          | 32        | 17.49%  |
| 301-350        | 19        | 10.38%  |
| 351-500        | 12        | 6.56%   |
| 251-300        | 11        | 6.01%   |
| Unknown        | 11        | 6.01%   |
| 151-200        | 6         | 3.28%   |
| 61-70          | 5         | 2.73%   |
| 501-1000       | 5         | 2.73%   |
| 71-80          | 4         | 2.19%   |
| 121-130        | 3         | 1.64%   |
| More than 1000 | 1         | 0.55%   |
| 141-150        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 67        | 37.43%  |
| 51-100        | 57        | 31.84%  |
| 101-120       | 28        | 15.64%  |
| Unknown       | 11        | 6.15%   |
| 161-240       | 9         | 5.03%   |
| More than 240 | 4         | 2.23%   |
| 1-50          | 3         | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 62.25%  |
| 2     | 39        | 25.83%  |
| 3     | 11        | 7.28%   |
| 0     | 7         | 4.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 114       | 52.29%  |
| Realtek Semiconductor             | 47        | 21.56%  |
| Lenovo                            | 14        | 6.42%   |
| Qualcomm Atheros                  | 9         | 4.13%   |
| Broadcom                          | 6         | 2.75%   |
| Broadcom Limited                  | 4         | 1.83%   |
| Ralink                            | 2         | 0.92%   |
| Marvell Technology Group          | 2         | 0.92%   |
| Huawei Technologies               | 2         | 0.92%   |
| Dell                              | 2         | 0.92%   |
| ASIX Electronics                  | 2         | 0.92%   |
| Xiaomi                            | 1         | 0.46%   |
| Sierra Wireless                   | 1         | 0.46%   |
| Samsung Electronics               | 1         | 0.46%   |
| Ralink Technology                 | 1         | 0.46%   |
| Microchip Technology              | 1         | 0.46%   |
| Micro Star International          | 1         | 0.46%   |
| MediaTek                          | 1         | 0.46%   |
| Luminary Micro                    | 1         | 0.46%   |
| ICS Advent                        | 1         | 0.46%   |
| IBM                               | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |
| DisplayLink                       | 1         | 0.46%   |
| D-Link                            | 1         | 0.46%   |
| Arduino SA                        | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 10.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 5.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 4.42%   |
| Intel Wireless 8265 / 8275                                                     | 12        | 4.08%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 9         | 3.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 9         | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 3.06%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 2.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 2.72%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                            | 7         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 2.04%   |
| Intel Wireless 8260                                                            | 5         | 1.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.36%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.36%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 1.36%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 1.02%   |
| Intel Wireless-AC 9260                                                         | 3         | 1.02%   |
| Intel Wireless 7265                                                            | 3         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.02%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.02%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.68%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.68%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.68%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.68%   |
| Intel Wireless 7260                                                            | 2         | 0.68%   |
| Intel Wireless 3165                                                            | 2         | 0.68%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.68%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.68%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.68%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.34%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.34%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1         | 0.34%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.34%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.34%   |
| Ralink RT5572 Wireless Adapter                                                 | 1         | 0.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 74.36%  |
| Realtek Semiconductor    | 9         | 7.69%   |
| Qualcomm Atheros         | 8         | 6.84%   |
| Broadcom                 | 4         | 3.42%   |
| Ralink                   | 2         | 1.71%   |
| Sierra Wireless          | 1         | 0.85%   |
| Ralink Technology        | 1         | 0.85%   |
| Micro Star International | 1         | 0.85%   |
| MediaTek                 | 1         | 0.85%   |
| Dell                     | 1         | 0.85%   |
| D-Link                   | 1         | 0.85%   |
| Broadcom Limited         | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 13        | 11.11%  |
| Intel Wireless 8265 / 8275                                                 | 12        | 10.26%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 9         | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 9         | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 7.69%   |
| Intel Wi-Fi 6 AX200                                                        | 7         | 5.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 5.13%   |
| Intel Wireless 8260                                                        | 5         | 4.27%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 2.56%   |
| Intel Wireless-AC 9260                                                     | 3         | 2.56%   |
| Intel Wireless 7265                                                        | 3         | 2.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 2.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.71%   |
| Intel Wireless 7260                                                        | 2         | 1.71%   |
| Intel Wireless 3165                                                        | 2         | 1.71%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.85%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.85%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.85%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 0.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.85%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                       | 1         | 0.85%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 0.85%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 54.72%  |
| Realtek Semiconductor    | 41        | 25.79%  |
| Lenovo                   | 14        | 8.81%   |
| Broadcom Limited         | 3         | 1.89%   |
| Qualcomm Atheros         | 2         | 1.26%   |
| Marvell Technology Group | 2         | 1.26%   |
| Broadcom                 | 2         | 1.26%   |
| ASIX Electronics         | 2         | 1.26%   |
| Xiaomi                   | 1         | 0.63%   |
| Samsung Electronics      | 1         | 0.63%   |
| ICS Advent               | 1         | 0.63%   |
| IBM                      | 1         | 0.63%   |
| Huawei Technologies      | 1         | 0.63%   |
| DisplayLink              | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 18.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 8.77%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 5.85%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 4.68%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 4.68%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 4.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.34%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.34%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 2.34%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 2.34%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.75%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.17%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.17%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.17%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 1.17%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.17%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 1.17%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.17%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.17%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.17%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.17%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 1.17%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.58%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.58%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.58%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.58%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.58%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.58%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.58%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.58%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.58%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.58%   |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 0.58%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.58%   |
| IBM RNDIS/Ethernet Gadget                                                      | 1         | 0.58%   |
| Huawei E353/E3131                                                              | 1         | 0.58%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 0.58%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 0.58%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                         | 1         | 0.58%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.58%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 0.58%   |
| ASIX AX88772A Fast Ethernet                                                    | 1         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 132       | 52.38%  |
| WiFi     | 114       | 45.24%  |
| Modem    | 5         | 1.98%   |
| Unknown  | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 120       | 54.05%  |
| WiFi     | 101       | 45.5%   |
| Unknown  | 1         | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 63.38%  |
| 1     | 38        | 26.76%  |
| 3     | 8         | 5.63%   |
| 6     | 2         | 1.41%   |
| 132   | 1         | 0.7%    |
| 22    | 1         | 0.7%    |
| 8     | 1         | 0.7%    |
| 4     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 90.21%  |
| Yes  | 14        | 9.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 71.43%  |
| Cambridge Silicon Radio         | 6         | 6.59%   |
| Broadcom                        | 6         | 6.59%   |
| Qualcomm Atheros Communications | 3         | 3.3%    |
| IMC Networks                    | 3         | 3.3%    |
| Realtek Semiconductor           | 2         | 2.2%    |
| ASUSTek Computer                | 2         | 2.2%    |
| Ralink                          | 1         | 1.1%    |
| Micro Star International        | 1         | 1.1%    |
| Foxconn / Hon Hai               | 1         | 1.1%    |
| Dell                            | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 30        | 32.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 20.88%  |
| Intel Bluetooth wireless interface                                                  | 12        | 13.19%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 6.59%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.3%    |
| Realtek Bluetooth Radio                                                             | 2         | 2.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.2%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.2%    |
| ASUS BCM20702A0                                                                     | 2         | 2.2%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.1%    |
| Micro Star International Bluetooth Device                                           | 1         | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.1%    |
| Intel AX210 Bluetooth                                                               | 1         | 1.1%    |
| IMC Networks BCM20702A0                                                             | 1         | 1.1%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.1%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.1%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.1%    |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 122       | 53.51%  |
| Nvidia                 | 42        | 18.42%  |
| AMD                    | 17        | 7.46%   |
| Lenovo                 | 14        | 6.14%   |
| Plantronics            | 4         | 1.75%   |
| Texas Instruments      | 3         | 1.32%   |
| JMTek                  | 3         | 1.32%   |
| GN Netcom              | 3         | 1.32%   |
| Generalplus Technology | 3         | 1.32%   |
| Creative Labs          | 3         | 1.32%   |
| Realtek Semiconductor  | 2         | 0.88%   |
| Logitech               | 2         | 0.88%   |
| Creative Technology    | 2         | 0.88%   |
| Tenx Technology        | 1         | 0.44%   |
| RODE Microphones       | 1         | 0.44%   |
| Google                 | 1         | 0.44%   |
| Focusrite-Novation     | 1         | 0.44%   |
| DYNEX                  | 1         | 0.44%   |
| Dell                   | 1         | 0.44%   |
| C-Media Electronics    | 1         | 0.44%   |
| ASUSTek Computer       | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 18        | 7.35%   |
| Intel Cannon Lake PCH cAVS                                                        | 18        | 7.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 14        | 5.71%   |
| Intel Comet Lake PCH cAVS                                                         | 10        | 4.08%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 9         | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 3.67%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8         | 3.27%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 7         | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 2.86%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 7         | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 2.04%   |
| Plantronics BT600                                                                 | 4         | 1.63%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.63%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 1.63%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4         | 1.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.63%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 1.22%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 3         | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.22%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3         | 1.22%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.22%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 0.82%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.82%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.82%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.82%   |
| Generalplus Technology Usb Audio Device                                           | 2         | 0.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.82%   |
| Tenx Technology USB AUDIO                                                         | 1         | 0.41%   |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.41%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.41%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.41%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.41%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.41%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.41%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1         | 0.41%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1         | 0.41%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.41%   |
| Logitech H570e Mono                                                               | 1         | 0.41%   |
| Logitech H555 Headset                                                             | 1         | 0.41%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.41%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.41%   |
| JMTek USB Speaker                                                                 | 1         | 0.41%   |
| JMTek USB PnP Audio Device                                                        | 1         | 0.41%   |
| JMTek iTalk-02                                                                    | 1         | 0.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 34.48%  |
| SK Hynix            | 12        | 20.69%  |
| Crucial             | 7         | 12.07%  |
| Kingston            | 4         | 6.9%    |
| Corsair             | 4         | 6.9%    |
| Micron Technology   | 3         | 5.17%   |
| Unknown             | 2         | 3.45%   |
| Unknown (0x0205)    | 1         | 1.72%   |
| Transcend           | 1         | 1.72%   |
| Smart               | 1         | 1.72%   |
| Patriot             | 1         | 1.72%   |
| Hewlett-Packard     | 1         | 1.72%   |
| GOODRAM             | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 3.23%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s         | 2         | 3.23%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 2         | 3.23%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 1.61%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.61%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s           | 1         | 1.61%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s             | 1         | 1.61%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s      | 1         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 1.61%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.61%   |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s         | 1         | 1.61%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 1.61%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.61%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                    | 1         | 1.61%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 1.61%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.61%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                   | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.61%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.61%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 1         | 1.61%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1         | 1.61%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1         | 1.61%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s       | 1         | 1.61%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.61%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s             | 1         | 1.61%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 1.61%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 1.61%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s         | 1         | 1.61%   |
| Kingston RAM KHX2666C13/16GX 16384MB DIMM DDR4 3200MT/s      | 1         | 1.61%   |
| Kingston RAM KHX2400C14S4/8G 8192MB SODIMM DDR4 2400MT/s     | 1         | 1.61%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 1.61%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s      | 1         | 1.61%   |
| HP RAM 809082-091 16384MB DIMM DDR4 2400MT/s                 | 1         | 1.61%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s         | 1         | 1.61%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s     | 1         | 1.61%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 1.61%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s    | 1         | 1.61%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4096MB DIMM DDR4 2400MT/s     | 1         | 1.61%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 60.87%  |
| DDR3   | 15        | 32.61%  |
| SDRAM  | 1         | 2.17%   |
| LPDDR4 | 1         | 2.17%   |
| LPDDR3 | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 51.11%  |
| DIMM         | 21        | 46.67%  |
| Row Of Chips | 1         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 32.65%  |
| 16384 | 14        | 28.57%  |
| 8192  | 11        | 22.45%  |
| 32768 | 6         | 12.24%  |
| 65536 | 1         | 2.04%   |
| 2048  | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 11        | 22%     |
| 1600  | 11        | 22%     |
| 2400  | 7         | 14%     |
| 3200  | 6         | 12%     |
| 1333  | 5         | 10%     |
| 2133  | 4         | 8%      |
| 3600  | 2         | 4%      |
| 3266  | 1         | 2%      |
| 2933  | 1         | 2%      |
| 2666  | 1         | 2%      |
| 1334  | 1         | 2%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 50%     |
| Canon              | 2         | 33.33%  |
| Brother Industries | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w   | 1         | 16.67%  |
| HP ENVY 4500 series                | 1         | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 16.67%  |
| Canon E560 series                  | 1         | 16.67%  |
| Canon CanoScan LiDE 300            | 1         | 16.67%  |
| Brother DCP-1610W                  | 1         | 16.67%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 31.07%  |
| IMC Networks                           | 12        | 11.65%  |
| Acer                                   | 12        | 11.65%  |
| Logitech                               | 9         | 8.74%   |
| Realtek Semiconductor                  | 8         | 7.77%   |
| Sunplus Innovation Technology          | 6         | 5.83%   |
| Microdia                               | 6         | 5.83%   |
| Unknown                                | 3         | 2.91%   |
| Suyin                                  | 3         | 2.91%   |
| Lite-On Technology                     | 3         | 2.91%   |
| Samsung Electronics                    | 2         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.94%   |
| Ruision                                | 1         | 0.97%   |
| Quanta                                 | 1         | 0.97%   |
| Lenovo                                 | 1         | 0.97%   |
| Jieli Technology                       | 1         | 0.97%   |
| ARC International                      | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 19        | 18.1%   |
| IMC Networks Integrated Camera                               | 10        | 9.52%   |
| Acer Integrated Camera                                       | 8         | 7.62%   |
| Realtek Integrated_Webcam_HD                                 | 6         | 5.71%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.81%   |
| Unknown FULL HD 1080P Webcam                                 | 3         | 2.86%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.86%   |
| Lite-On Integrated Camera                                    | 3         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 2.86%   |
| Chicony HP HD Camera                                         | 3         | 2.86%   |
| Acer SunplusIT Integrated Camera                             | 3         | 2.86%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 1.9%    |
| Microdia Webcam                                              | 2         | 1.9%    |
| Microdia Integrated Webcam                                   | 2         | 1.9%    |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 1.9%    |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.9%    |
| Suyin RGBIR Camera                                           | 1         | 0.95%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.95%   |
| Suyin HP Truevision HD                                       | 1         | 0.95%   |
| Sunplus USB2.0 Camera                                        | 1         | 0.95%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.95%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.95%   |
| Ruision UVC Camera                                           | 1         | 0.95%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.95%   |
| Realtek NexiGo N660P FHD Webcam                              | 1         | 0.95%   |
| Quanta HP HD Camera                                          | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.95%   |
| Logitech Webcam C925e                                        | 1         | 0.95%   |
| Logitech Webcam C310                                         | 1         | 0.95%   |
| Logitech Webcam C270                                         | 1         | 0.95%   |
| Logitech HD Webcam C910                                      | 1         | 0.95%   |
| Logitech B525 HD Webcam                                      | 1         | 0.95%   |
| Lenovo Integrated Webcam                                     | 1         | 0.95%   |
| Jieli USB PHY 2.0                                            | 1         | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.95%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.95%   |
| Chicony Integrated IR Camera                                 | 1         | 0.95%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.95%   |
| Chicony HP Webcam                                            | 1         | 0.95%   |
| Chicony HD User Facing                                       | 1         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera          | 1         | 0.95%   |
| ARC International Camera                                     | 1         | 0.95%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.95%   |
| Acer Integrated IR Camera                                    | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 60%     |
| Validity Sensors           | 12        | 30%     |
| Upek                       | 2         | 5%      |
| Shenzhen Goodix Technology | 1         | 2.5%    |
| Elan Microelectronics      | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 45%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 7.5%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.5%    |
| Elan ELAN:Fingerprint                                                      | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 35.71%  |
| Alcor Micro           | 4         | 28.57%  |
| Lenovo                | 2         | 14.29%  |
| Upek                  | 1         | 7.14%   |
| SCM Microsystems      | 1         | 7.14%   |
| Gemalto (was Gemplus) | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 28.57%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 14.29%  |
| Broadcom 5880                                              | 2         | 14.29%  |
| Broadcom 58200                                             | 2         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.14%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 73        | 51.77%  |
| 1     | 55        | 39.01%  |
| 2     | 11        | 7.8%    |
| 3     | 2         | 1.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 47.62%  |
| Graphics card            | 10        | 11.9%   |
| Chipcard                 | 10        | 11.9%   |
| Unassigned class         | 7         | 8.33%   |
| Net/wireless             | 5         | 5.95%   |
| Net/ethernet             | 2         | 2.38%   |
| Multimedia controller    | 2         | 2.38%   |
| Communication controller | 2         | 2.38%   |
| Bluetooth                | 2         | 2.38%   |
| Storage/ide              | 1         | 1.19%   |
| Storage                  | 1         | 1.19%   |
| Network                  | 1         | 1.19%   |
| Card reader              | 1         | 1.19%   |

