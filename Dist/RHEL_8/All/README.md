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
| Lenovo     | Z40-70 20366                | Notebook    | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Gigabyte   | B150-HD3-CF                 | Desktop     | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| Lenovo     | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek    | Maximus VII FORMULA         | Desktop     | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| Lenovo     | ThinkPad X1 Yoga 1st 20F... | Notebook    | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 7.73%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 13        | 7.18%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 6.08%   |
| 4.18.0-305.el8.x86_64        | 10        | 5.52%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 4.97%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 4.42%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 8         | 4.42%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 7         | 3.87%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 7         | 3.87%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 7         | 3.87%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 7         | 3.87%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 6         | 3.31%   |
| 4.18.0-193.el8.x86_64        | 6         | 3.31%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 3.31%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 5         | 2.76%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 2.76%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 2.76%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4         | 2.21%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 2.21%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4         | 2.21%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 2.21%   |
| 4.18.0-147.el8.x86_64        | 4         | 2.21%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 4         | 2.21%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.1%    |
| 4.18.0-305.17.1.el8_4.x86_64 | 2         | 1.1%    |
| 4.18.0-240.8.1.el8_3.x86_64  | 2         | 1.1%    |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.1%    |
| 4.18.0-147.0.3.el8_1.x86_64  | 2         | 1.1%    |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.55%   |
| 5.13.0-1.el8.elrepo.x86_64   | 1         | 0.55%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1         | 0.55%   |
| 4.19.150                     | 1         | 0.55%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.55%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.55%   |
| 4.18.0-221.el8.x86_64        | 1         | 0.55%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.55%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.55%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.55%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.55%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.55%   |
| Unknown                      | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 140       | 96.55%  |
| 5.9.1    | 1         | 0.69%   |
| 5.13.0   | 1         | 0.69%   |
| 5.10.6   | 1         | 0.69%   |
| 4.19.150 | 1         | 0.69%   |
| Unknown  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 140       | 96.55%  |
| 5.9     | 1         | 0.69%   |
| 5.13    | 1         | 0.69%   |
| 5.10    | 1         | 0.69%   |
| 4.19    | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 144       | 99.31%  |
| Unknown | 1         | 0.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 125       | 82.78%  |
| Unknown       | 12        | 7.95%   |
| GNOME Classic | 7         | 4.64%   |
| KDE5          | 5         | 3.31%   |
| KDE           | 2         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 85        | 55.92%  |
| Wayland | 61        | 40.13%  |
| Unknown | 6         | 3.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 79.33%  |
| GDM     | 31        | 20.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 100       | 67.11%  |
| Unknown | 10        | 6.71%   |
| en_GB   | 7         | 4.7%    |
| pl_PL   | 4         | 2.68%   |
| fr_FR   | 4         | 2.68%   |
| en_IN   | 4         | 2.68%   |
| ru_RU   | 3         | 2.01%   |
| pt_BR   | 2         | 1.34%   |
| nl_NL   | 2         | 1.34%   |
| de_DE   | 2         | 1.34%   |
| ko_KR   | 1         | 0.67%   |
| ja_JP   | 1         | 0.67%   |
| it_IT   | 1         | 0.67%   |
| es_MX   | 1         | 0.67%   |
| es_ES   | 1         | 0.67%   |
| es_EC   | 1         | 0.67%   |
| es_AR   | 1         | 0.67%   |
| en_NZ   | 1         | 0.67%   |
| en_IE   | 1         | 0.67%   |
| de_CH   | 1         | 0.67%   |
| cs_CZ   | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 77.18%  |
| BIOS | 34        | 22.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 130       | 89.66%  |
| Ext4    | 14        | 9.66%   |
| Unknown | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 112       | 74.67%  |
| GPT     | 33        | 22%     |
| MBR     | 5         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 97.93%  |
| Yes       | 3         | 2.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 136       | 92.52%  |
| Yes       | 11        | 7.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 61        | 42.07%  |
| Dell                | 22        | 15.17%  |
| Hewlett-Packard     | 19        | 13.1%   |
| ASUSTek Computer    | 16        | 11.03%  |
| Gigabyte Technology | 7         | 4.83%   |
| MSI                 | 4         | 2.76%   |
| ASRock              | 4         | 2.76%   |
| Supermicro          | 2         | 1.38%   |
| Sony                | 2         | 1.38%   |
| Intel               | 2         | 1.38%   |
| TUXEDO              | 1         | 0.69%   |
| Toshiba             | 1         | 0.69%   |
| Timi                | 1         | 0.69%   |
| Alienware           | 1         | 0.69%   |
| Acer                | 1         | 0.69%   |
| Unknown             | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 3         | 2.07%   |
| ASUS All Series                          | 3         | 2.07%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.38%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.38%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.38%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.38%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.38%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.38%   |
| HP EliteBook 8460p                       | 2         | 1.38%   |
| Dell Latitude E6430                      | 2         | 1.38%   |
| Dell Latitude 5300                       | 2         | 1.38%   |
| TUXEDO N13xWU                            | 1         | 0.69%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.69%   |
| Timi TM1707                              | 1         | 0.69%   |
| Supermicro X7DW3                         | 1         | 0.69%   |
| Supermicro X10DRi                        | 1         | 0.69%   |
| Sony VPCEB4L1R                           | 1         | 0.69%   |
| Sony VPCEB23FM                           | 1         | 0.69%   |
| MSI MS-7B51                              | 1         | 0.69%   |
| MSI MS-7B33                              | 1         | 0.69%   |
| MSI MS-7A37                              | 1         | 0.69%   |
| MSI MS-7752                              | 1         | 0.69%   |
| Lenovo Z40-70 20366                      | 1         | 0.69%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.69%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.69%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.69%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.69%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.69%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.69%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.69%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.69%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.69%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.69%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.69%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.69%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.69%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.69%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.69%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.69%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.69%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.69%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.69%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.69%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.69%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N    | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 0.69%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 0.69%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 0.69%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 0.69%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 0.69%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 0.69%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 0.69%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 0.69%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 53        | 36.55%  |
| Dell Latitude       | 8         | 5.52%   |
| Dell Precision      | 7         | 4.83%   |
| HP EliteBook        | 4         | 2.76%   |
| Lenovo ThinkCentre  | 3         | 2.07%   |
| Dell Inspiron       | 3         | 2.07%   |
| ASUS PRIME          | 3         | 2.07%   |
| ASUS All            | 3         | 2.07%   |
| HP ZBook            | 2         | 1.38%   |
| HP Z230             | 2         | 1.38%   |
| ASUS ROG            | 2         | 1.38%   |
| TUXEDO N13xWU       | 1         | 0.69%   |
| Toshiba Satellite   | 1         | 0.69%   |
| Timi TM1707         | 1         | 0.69%   |
| Supermicro X7DW3    | 1         | 0.69%   |
| Supermicro X10DRi   | 1         | 0.69%   |
| Sony VPCEB4L1R      | 1         | 0.69%   |
| Sony VPCEB23FM      | 1         | 0.69%   |
| MSI MS-7B51         | 1         | 0.69%   |
| MSI MS-7B33         | 1         | 0.69%   |
| MSI MS-7A37         | 1         | 0.69%   |
| MSI MS-7752         | 1         | 0.69%   |
| Lenovo Z40-70       | 1         | 0.69%   |
| Lenovo Yoga         | 1         | 0.69%   |
| Lenovo ThinkSystem  | 1         | 0.69%   |
| Lenovo ThinkpadT460 | 1         | 0.69%   |
| Lenovo S40-40       | 1         | 0.69%   |
| Intel NUC10i7FNK    | 1         | 0.69%   |
| Intel DX79SR        | 1         | 0.69%   |
| HP Z840             | 1         | 0.69%   |
| HP Z620             | 1         | 0.69%   |
| HP Z440             | 1         | 0.69%   |
| HP ProLiant         | 1         | 0.69%   |
| HP ProBook          | 1         | 0.69%   |
| HP Pavilion         | 1         | 0.69%   |
| HP OMEN             | 1         | 0.69%   |
| HP EliteDesk        | 1         | 0.69%   |
| HP 290              | 1         | 0.69%   |
| HP 260-P020il       | 1         | 0.69%   |
| HP 250              | 1         | 0.69%   |
| Gigabyte Z97N-WIFI  | 1         | 0.69%   |
| Gigabyte Z490       | 1         | 0.69%   |
| Gigabyte Z390       | 1         | 0.69%   |
| Gigabyte B85M-D3V-A | 1         | 0.69%   |
| Gigabyte B75-D3V    | 1         | 0.69%   |
| Gigabyte B150-HD3   | 1         | 0.69%   |
| Gigabyte 970A-D3    | 1         | 0.69%   |
| Dell XPS            | 1         | 0.69%   |
| Dell Vostro         | 1         | 0.69%   |
| Dell PowerEdge      | 1         | 0.69%   |
| Dell G3             | 1         | 0.69%   |
| ASUS Zephyrus       | 1         | 0.69%   |
| ASUS Z10PE-D16      | 1         | 0.69%   |
| ASUS X550VX         | 1         | 0.69%   |
| ASUS TUF            | 1         | 0.69%   |
| ASUS Pro            | 1         | 0.69%   |
| ASUS P8Z77-V        | 1         | 0.69%   |
| ASUS MINIPC         | 1         | 0.69%   |
| ASUS GL502VMK       | 1         | 0.69%   |
| ASRock X99E-ITX     | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 28        | 19.31%  |
| 2020 | 27        | 18.62%  |
| 2018 | 22        | 15.17%  |
| 2017 | 14        | 9.66%   |
| 2012 | 12        | 8.28%   |
| 2015 | 11        | 7.59%   |
| 2016 | 8         | 5.52%   |
| 2011 | 7         | 4.83%   |
| 2013 | 6         | 4.14%   |
| 2021 | 3         | 2.07%   |
| 2014 | 3         | 2.07%   |
| 2010 | 3         | 2.07%   |
| 2009 | 1         | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 92        | 63.45%  |
| Desktop     | 45        | 31.03%  |
| Server      | 4         | 2.76%   |
| Mini pc     | 2         | 1.38%   |
| Convertible | 1         | 0.69%   |
| All in one  | 1         | 0.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 132       | 89.8%   |
| Enabled  | 15        | 10.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 145       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 40        | 26.85%  |
| 16.01-24.0      | 28        | 18.79%  |
| 4.01-8.0        | 24        | 16.11%  |
| 8.01-16.0       | 22        | 14.77%  |
| 64.01-256.0     | 19        | 12.75%  |
| 3.01-4.0        | 7         | 4.7%    |
| 24.01-32.0      | 6         | 4.03%   |
| More than 256.0 | 2         | 1.34%   |
| Unknown         | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 62        | 36.69%  |
| 2.01-3.0        | 31        | 18.34%  |
| 8.01-16.0       | 30        | 17.75%  |
| 3.01-4.0        | 26        | 15.38%  |
| 1.01-2.0        | 11        | 6.51%   |
| 16.01-24.0      | 3         | 1.78%   |
| 24.01-32.0      | 2         | 1.18%   |
| More than 256.0 | 1         | 0.59%   |
| 32.01-64.0      | 1         | 0.59%   |
| 0.51-1.0        | 1         | 0.59%   |
| Unknown         | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 58.17%  |
| 2      | 34        | 22.22%  |
| 3      | 15        | 9.8%    |
| 4      | 6         | 3.92%   |
| 5      | 4         | 2.61%   |
| 8      | 2         | 1.31%   |
| 6      | 2         | 1.31%   |
| 7      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 74.15%  |
| Yes       | 38        | 25.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 93.15%  |
| No        | 10        | 6.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 80.69%  |
| No        | 28        | 19.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 63.33%  |
| No        | 55        | 36.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 31        | 21.23%  |
| India        | 15        | 10.27%  |
| UK           | 9         | 6.16%   |
| Germany      | 7         | 4.79%   |
| Czechia      | 7         | 4.79%   |
| France       | 6         | 4.11%   |
| Canada       | 6         | 4.11%   |
| Poland       | 4         | 2.74%   |
| Netherlands  | 4         | 2.74%   |
| Mexico       | 4         | 2.74%   |
| Switzerland  | 3         | 2.05%   |
| Russia       | 3         | 2.05%   |
| Lithuania    | 3         | 2.05%   |
| Italy        | 3         | 2.05%   |
| Brazil       | 3         | 2.05%   |
| Ukraine      | 2         | 1.37%   |
| Spain        | 2         | 1.37%   |
| South Korea  | 2         | 1.37%   |
| South Africa | 2         | 1.37%   |
| Romania      | 2         | 1.37%   |
| Japan        | 2         | 1.37%   |
| Australia    | 2         | 1.37%   |
| Argentina    | 2         | 1.37%   |
| Turkmenistan | 1         | 0.68%   |
| Sweden       | 1         | 0.68%   |
| Singapore    | 1         | 0.68%   |
| Saudi Arabia | 1         | 0.68%   |
| Portugal     | 1         | 0.68%   |
| Pakistan     | 1         | 0.68%   |
| New Zealand  | 1         | 0.68%   |
| Nepal        | 1         | 0.68%   |
| Myanmar      | 1         | 0.68%   |
| Morocco      | 1         | 0.68%   |
| Luxembourg   | 1         | 0.68%   |
| Kuwait       | 1         | 0.68%   |
| Israel       | 1         | 0.68%   |
| Ireland      | 1         | 0.68%   |
| Indonesia    | 1         | 0.68%   |
| Georgia      | 1         | 0.68%   |
| Egypt        | 1         | 0.68%   |
| Ecuador      | 1         | 0.68%   |
| Colombia     | 1         | 0.68%   |
| Bulgaria     | 1         | 0.68%   |
| Belarus      | 1         | 0.68%   |
| Armenia      | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Brno                     | 5         | 3.16%   |
| Munich                   | 3         | 1.9%    |
| Mexico City              | 3         | 1.9%    |
| Toronto                  | 2         | 1.27%   |
| San Jose                 | 2         | 1.27%   |
| Mumbai                   | 2         | 1.27%   |
| Milan                    | 2         | 1.27%   |
| Kyiv                     | 2         | 1.27%   |
| Doetinchem               | 2         | 1.27%   |
| Coimbatore               | 2         | 1.27%   |
| Chicago                  | 2         | 1.27%   |
| Bengaluru                | 2         | 1.27%   |
| Å iauliai              | 2         | 1.27%   |
| Aurora                   | 2         | 1.27%   |
| Yerevan                  | 1         | 0.63%   |
| Wroclaw                  | 1         | 0.63%   |
| Wiesbaden                | 1         | 0.63%   |
| Weybridge                | 1         | 0.63%   |
| Webster                  | 1         | 0.63%   |
| Warsaw                   | 1         | 0.63%   |
| Valmontone               | 1         | 0.63%   |
| Vaestra Froelunda        | 1         | 0.63%   |
| Tauranga                 | 1         | 0.63%   |
| Taringa                  | 1         | 0.63%   |
| Suwon                    | 1         | 0.63%   |
| Sumida                   | 1         | 0.63%   |
| Stroud                   | 1         | 0.63%   |
| Spokane                  | 1         | 0.63%   |
| Sofia                    | 1         | 0.63%   |
| Singapore                | 1         | 0.63%   |
| Sheffield                | 1         | 0.63%   |
| Seoul                    | 1         | 0.63%   |
| Saratov                  | 1         | 0.63%   |
| San Francisco            | 1         | 0.63%   |
| Sammamish                | 1         | 0.63%   |
| Salvador                 | 1         | 0.63%   |
| Saltillo                 | 1         | 0.63%   |
| SalÃ©                  | 1         | 0.63%   |
| Saint-Ismier             | 1         | 0.63%   |
| Saint-Alphonse-Rodriguez | 1         | 0.63%   |
| Sagaing                  | 1         | 0.63%   |
| Roudnice nad Labem       | 1         | 0.63%   |
| Roha                     | 1         | 0.63%   |
| Reims                    | 1         | 0.63%   |
| Raleigh                  | 1         | 0.63%   |
| Quito                    | 1         | 0.63%   |
| Queenscliff              | 1         | 0.63%   |
| Queens                   | 1         | 0.63%   |
| Pune                     | 1         | 0.63%   |
| Prague                   | 1         | 0.63%   |
| Poznan                   | 1         | 0.63%   |
| Portalegre               | 1         | 0.63%   |
| Port Elizabeth           | 1         | 0.63%   |
| Pleasanton               | 1         | 0.63%   |
| Pickerington             | 1         | 0.63%   |
| Pernis                   | 1         | 0.63%   |
| Paris                    | 1         | 0.63%   |
| Paraiso do Tocantins     | 1         | 0.63%   |
| Paragould                | 1         | 0.63%   |
| Paracuellos de Jarama    | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 71     | 19.64%  |
| WDC                 | 33        | 60     | 14.73%  |
| Seagate             | 25        | 38     | 11.16%  |
| Toshiba             | 17        | 25     | 7.59%   |
| Sandisk             | 14        | 23     | 6.25%   |
| SK Hynix            | 13        | 16     | 5.8%    |
| Kingston            | 11        | 15     | 4.91%   |
| Intel               | 10        | 14     | 4.46%   |
| Crucial             | 7         | 11     | 3.13%   |
| Unknown             | 6         | 8      | 2.68%   |
| Micron Technology   | 6         | 13     | 2.68%   |
| A-DATA Technology   | 5         | 5      | 2.23%   |
| HGST                | 4         | 4      | 1.79%   |
| PNY                 | 3         | 6      | 1.34%   |
| Phison              | 3         | 6      | 1.34%   |
| Hitachi             | 3         | 3      | 1.34%   |
| Corsair             | 3         | 4      | 1.34%   |
| Silicon Motion      | 2         | 3      | 0.89%   |
| Lenovo              | 2         | 2      | 0.89%   |
| Hewlett-Packard     | 2         | 3      | 0.89%   |
| XPG                 | 1         | 1      | 0.45%   |
| Team                | 1         | 2      | 0.45%   |
| T-FORCE             | 1         | 2      | 0.45%   |
| SMI                 | 1         | 2      | 0.45%   |
| OCZ                 | 1         | 2      | 0.45%   |
| Lite-On             | 1         | 1      | 0.45%   |
| Hoodisk             | 1         | 1      | 0.45%   |
| Gigabyte Technology | 1         | 1      | 0.45%   |
| DELLBOSS            | 1         | 1      | 0.45%   |
| Dell                | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB          | 9         | 3.53%   |
| Sandisk NVMe SSD Drive 256GB           | 6         | 2.35%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 2.35%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 5         | 1.96%   |
| Samsung SSD 860 EVO 1TB                | 5         | 1.96%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 5         | 1.96%   |
| Samsung NVMe SSD Drive 1024GB          | 5         | 1.96%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 1.57%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 1.18%   |
| Micron NVMe SSD Drive 256GB            | 3         | 1.18%   |
| HGST HTS721010A9E630 1TB               | 3         | 1.18%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 0.78%   |
| Unknown NVMe SSD Drive 256GB           | 2         | 0.78%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.78%   |
| Seagate ST1000DM003-9YN162 1TB         | 2         | 0.78%   |
| Seagate Expansion+ 2TB                 | 2         | 0.78%   |
| Samsung SSD 860 EVO 500GB              | 2         | 0.78%   |
| Samsung Portable SSD T5 500GB          | 2         | 0.78%   |
| Samsung NVMe SSD Drive 2TB             | 2         | 0.78%   |
| Samsung NVMe SSD Drive 1TB             | 2         | 0.78%   |
| Kingston SUV500120G 120GB SSD          | 2         | 0.78%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.78%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 0.78%   |
| Intel NVMe SSD Drive 512GB             | 2         | 0.78%   |
| Intel NVMe SSD Drive 2TB               | 2         | 0.78%   |
| Crucial CT480BX500SSD1 480GB           | 2         | 0.78%   |
| Corsair Force LE SSD 240GB             | 2         | 0.78%   |
| XPG NVMe SSD Drive 1024GB              | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.39%   |
| WDC WDS400T2B0A-00SM50 4TB SSD         | 1         | 0.39%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.39%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1         | 0.39%   |
| WDC WDS200T2B0B-00YS70 2TB SSD         | 1         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1         | 0.39%   |
| WDC WD7500BPKT-00PK4T0 752GB           | 1         | 0.39%   |
| WDC WD6400BPVT-75HXZT1 640GB           | 1         | 0.39%   |
| WDC WD60 EFAX-68JH4N1 6TB              | 1         | 0.39%   |
| WDC WD60 EFAX-68JH4N0 6TB              | 1         | 0.39%   |
| WDC WD5003ABYZ-011FA0 500GB            | 1         | 0.39%   |
| WDC WD5000LPLX-08ZNTT0 500GB           | 1         | 0.39%   |
| WDC WD5000AAKX-75U6AA0 500GB           | 1         | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 0.39%   |
| WDC WD50 00LPVX-00V0TT0 500GB          | 1         | 0.39%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.39%   |
| WDC WD40EZRZ-19GXCB0 4TB               | 1         | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB               | 1         | 0.39%   |
| WDC WD4005FZBX-00K5WB0 4TB             | 1         | 0.39%   |
| WDC WD2500BEVT-60ZCT1 250GB            | 1         | 0.39%   |
| WDC WD2500BEKT-75F3T0 250GB            | 1         | 0.39%   |
| WDC WD2500AAKX-083CA1 250GB            | 1         | 0.39%   |
| WDC WD20PURZ-85GU6Y0 2TB               | 1         | 0.39%   |
| WDC WD20EARS-22MVWB0 2TB               | 1         | 0.39%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 1         | 0.39%   |
| WDC WD20 SPZX-11UA7T0 2TB              | 1         | 0.39%   |
| WDC WD10SPZX-22Z10T0 1TB               | 1         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 0.39%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 48     | 36.76%  |
| Seagate             | 25        | 37     | 36.76%  |
| Toshiba             | 7         | 11     | 10.29%  |
| HGST                | 4         | 4      | 5.88%   |
| Hitachi             | 3         | 3      | 4.41%   |
| Unknown             | 1         | 1      | 1.47%   |
| Samsung Electronics | 1         | 1      | 1.47%   |
| Hewlett-Packard     | 1         | 1      | 1.47%   |
| DELLBOSS            | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 27     | 28.38%  |
| Kingston            | 11        | 15     | 14.86%  |
| Crucial             | 7         | 11     | 9.46%   |
| WDC                 | 6         | 8      | 8.11%   |
| SanDisk             | 5         | 9      | 6.76%   |
| A-DATA Technology   | 5         | 5      | 6.76%   |
| PNY                 | 3         | 6      | 4.05%   |
| Micron Technology   | 3         | 8      | 4.05%   |
| Corsair             | 3         | 4      | 4.05%   |
| SK Hynix            | 2         | 5      | 2.7%    |
| Intel               | 2         | 3      | 2.7%    |
| Toshiba             | 1         | 1      | 1.35%   |
| Team                | 1         | 2      | 1.35%   |
| Seagate             | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 2      | 1.35%   |
| Hoodisk             | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 77        | 121    | 36.84%  |
| SSD     | 66        | 109    | 31.58%  |
| HDD     | 61        | 107    | 29.19%  |
| MMC     | 3         | 4      | 1.44%   |
| Unknown | 2         | 4      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 201    | 48.04%  |
| NVMe | 77        | 121    | 43.02%  |
| SAS  | 13        | 19     | 7.26%   |
| MMC  | 3         | 4      | 1.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 97     | 44.62%  |
| 0.51-1.0   | 40        | 66     | 30.77%  |
| 1.01-2.0   | 18        | 26     | 13.85%  |
| 3.01-4.0   | 10        | 20     | 7.69%   |
| 4.01-10.0  | 2         | 5      | 1.54%   |
| 2.01-3.0   | 1         | 1      | 0.77%   |
| 10.01-20.0 | 1         | 1      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 36.6%   |
| 251-500        | 27        | 17.65%  |
| 501-1000       | 24        | 15.69%  |
| More than 3000 | 14        | 9.15%   |
| 1001-2000      | 14        | 9.15%   |
| 2001-3000      | 5         | 3.27%   |
| 51-100         | 5         | 3.27%   |
| Unknown        | 4         | 2.61%   |
| 21-50          | 3         | 1.96%   |
| 1-20           | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 38        | 22.89%  |
| 101-250        | 34        | 20.48%  |
| 1-20           | 31        | 18.67%  |
| 51-100         | 22        | 13.25%  |
| 251-500        | 14        | 8.43%   |
| 501-1000       | 11        | 6.63%   |
| 1001-2000      | 6         | 3.61%   |
| Unknown        | 4         | 2.41%   |
| More than 3000 | 3         | 1.81%   |
| 2001-3000      | 3         | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB        | 1         | 1      | 33.33%  |
| Hitachi HDS722020ALA330 2TB           | 1         | 1      | 33.33%  |
| A-DATA Technology SU800NS38 256GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 1         | 1      | 33.33%  |
| Hitachi           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 114       | 265    | 73.08%  |
| Works    | 39        | 77     | 25%     |
| Malfunc  | 3         | 3      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 91        | 47.4%   |
| Samsung Electronics          | 29        | 15.1%   |
| SK Hynix                     | 11        | 5.73%   |
| Sandisk                      | 11        | 5.73%   |
| AMD                          | 11        | 5.73%   |
| Toshiba America Info Systems | 9         | 4.69%   |
| Marvell Technology Group     | 4         | 2.08%   |
| Broadcom / LSI               | 4         | 2.08%   |
| Silicon Motion               | 3         | 1.56%   |
| Phison Electronics           | 3         | 1.56%   |
| Micron Technology            | 3         | 1.56%   |
| ASMedia Technology           | 3         | 1.56%   |
| LSI Logic / Symbios Logic    | 2         | 1.04%   |
| Lenovo                       | 2         | 1.04%   |
| KIOXIA                       | 2         | 1.04%   |
| Lite-On Technology           | 1         | 0.52%   |
| Hewlett-Packard              | 1         | 0.52%   |
| Biwin Storage Technology     | 1         | 0.52%   |
| ADATA Technology             | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 10.38%  |
| SK Hynix Non-Volatile memory controller                                          | 11        | 5.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 4.72%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 4.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 3.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 3.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 3.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 6         | 2.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 5         | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 2.36%   |
| Intel SSD 660P Series                                                            | 4         | 1.89%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.42%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.42%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.42%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.42%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 1.42%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.94%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.94%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.94%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.94%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.94%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2         | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.94%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.47%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.47%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.47%   |
| Samsung NVMe SSD Controller PM173X                                               | 1         | 0.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.47%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 1         | 0.47%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.47%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.47%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                            | 1         | 0.47%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                   | 1         | 0.47%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                             | 1         | 0.47%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.47%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.47%   |
| Intel NVMe Datacenter SSD [Optane]                                               | 1         | 0.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.47%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                       | 1         | 0.47%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 0.47%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 89        | 47.85%  |
| NVMe | 77        | 41.4%   |
| RAID | 13        | 6.99%   |
| IDE  | 4         | 2.15%   |
| SAS  | 3         | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 131       | 90.34%  |
| AMD    | 14        | 9.66%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 6.21%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 5.52%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 4.14%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 2.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.07%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3         | 2.07%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.07%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1.38%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.38%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.38%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1.38%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.38%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.38%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.38%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 1.38%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.38%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.69%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.69%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.69%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.69%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.69%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.69%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.69%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.69%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.69%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.69%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.69%   |
| Intel Core i7-9700F CPU @ 3.00GHz             | 1         | 0.69%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.69%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.69%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.69%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 0.69%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.69%   |
| Intel Core i7-3820 CPU @ 3.60GHz              | 1         | 0.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.69%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.69%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.69%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.69%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.69%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.69%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 68        | 46.9%   |
| Intel Core i5      | 33        | 22.76%  |
| Intel Xeon         | 14        | 9.66%   |
| Intel Core i3      | 9         | 6.21%   |
| AMD Ryzen 7        | 5         | 3.45%   |
| Other              | 2         | 1.38%   |
| Intel Pentium Gold | 2         | 1.38%   |
| Intel Core i9      | 2         | 1.38%   |
| AMD Ryzen 9        | 2         | 1.38%   |
| AMD Ryzen 3        | 2         | 1.38%   |
| AMD EPYC           | 2         | 1.38%   |
| Intel Pentium      | 1         | 0.69%   |
| AMD Ryzen 7 PRO    | 1         | 0.69%   |
| AMD Ryzen 5        | 1         | 0.69%   |
| AMD FX             | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 63        | 43.45%  |
| 2      | 36        | 24.83%  |
| 6      | 26        | 17.93%  |
| 8      | 9         | 6.21%   |
| 12     | 3         | 2.07%   |
| 20     | 2         | 1.38%   |
| 16     | 2         | 1.38%   |
| 96     | 1         | 0.69%   |
| 64     | 1         | 0.69%   |
| 36     | 1         | 0.69%   |
| 24     | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 93.79%  |
| 2      | 9         | 6.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 127       | 86.99%  |
| 1      | 19        | 13.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 95.92%  |
| Unknown        | 6         | 4.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 22        | 14.97%  |
| 0x906ea    | 13        | 8.84%   |
| 0x806ea    | 10        | 6.8%    |
| 0xa0652    | 9         | 6.12%   |
| 0x306c3    | 9         | 6.12%   |
| 0x306a9    | 9         | 6.12%   |
| 0x206a7    | 7         | 4.76%   |
| 0x906ed    | 6         | 4.08%   |
| 0x506e3    | 6         | 4.08%   |
| 0x906e9    | 5         | 3.4%    |
| 0x406e3    | 5         | 3.4%    |
| Unknown    | 5         | 3.4%    |
| 0x806e9    | 4         | 2.72%   |
| 0x306f2    | 3         | 2.04%   |
| 0x306d4    | 3         | 2.04%   |
| 0x20655    | 3         | 2.04%   |
| 0x08108102 | 3         | 2.04%   |
| 0x406f1    | 2         | 1.36%   |
| 0x40651    | 2         | 1.36%   |
| 0x206d7    | 2         | 1.36%   |
| 0x08600103 | 2         | 1.36%   |
| 0xa0660    | 1         | 0.68%   |
| 0xa0655    | 1         | 0.68%   |
| 0x906eb    | 1         | 0.68%   |
| 0x806d1    | 1         | 0.68%   |
| 0x806c1    | 1         | 0.68%   |
| 0x306e4    | 1         | 0.68%   |
| 0x20652    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x0a001119 | 1         | 0.68%   |
| 0x08701021 | 1         | 0.68%   |
| 0x08701013 | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |
| 0x08301034 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x08001138 | 1         | 0.68%   |
| 0x08001137 | 1         | 0.68%   |
| 0x06000852 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 62        | 42.47%  |
| Haswell     | 15        | 10.27%  |
| Skylake     | 11        | 7.53%   |
| IvyBridge   | 11        | 7.53%   |
| CometLake   | 11        | 7.53%   |
| SandyBridge | 9         | 6.16%   |
| Zen 2       | 6         | 4.11%   |
| Broadwell   | 5         | 3.42%   |
| Westmere    | 4         | 2.74%   |
| Zen+        | 3         | 2.05%   |
| Zen         | 3         | 2.05%   |
| Unknown     | 2         | 1.37%   |
| TigerLake   | 1         | 0.68%   |
| Piledriver  | 1         | 0.68%   |
| Penryn      | 1         | 0.68%   |
| Icelake     | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 100       | 55.87%  |
| Nvidia                     | 55        | 30.73%  |
| AMD                        | 20        | 11.17%  |
| Matrox Electronics Systems | 3         | 1.68%   |
| ASPEED Technology          | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 14        | 7.73%   |
| Intel UHD Graphics 620                                                      | 10        | 5.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 9         | 4.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 8         | 4.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 5         | 2.76%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 2.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 2.21%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.66%   |
| Intel HD Graphics 630                                                       | 3         | 1.66%   |
| Intel HD Graphics 620                                                       | 3         | 1.66%   |
| Intel HD Graphics 5500                                                      | 3         | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.66%   |
| AMD Renoir                                                                  | 3         | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.1%    |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 1.1%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.1%    |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 1.1%    |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.1%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 1.1%    |
| Intel HD Graphics 530                                                       | 2         | 1.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.1%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.55%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.55%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.55%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.55%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.55%   |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.55%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.55%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.55%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.55%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.55%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1         | 0.55%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.55%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.55%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 0.55%   |
| Nvidia GM107GL [NVS 810]                                                    | 1         | 0.55%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.55%   |
| Nvidia GK107GLM [Quadro K2000M]                                             | 1         | 0.55%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1         | 0.55%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 0.55%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 0.55%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 71        | 48.3%   |
| 1 x Nvidia      | 34        | 23.13%  |
| Intel + Nvidia  | 18        | 12.24%  |
| 1 x AMD         | 11        | 7.48%   |
| Intel + AMD     | 6         | 4.08%   |
| 1 x Matrox      | 2         | 1.36%   |
| AMD + Nvidia    | 2         | 1.36%   |
| 2 x AMD         | 1         | 0.68%   |
| Nvidia + Matrox | 1         | 0.68%   |
| Nvidia + ASPEED | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 118       | 80.27%  |
| Proprietary | 26        | 17.69%  |
| Unknown     | 3         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 59.33%  |
| 1.01-2.0   | 17        | 11.33%  |
| 3.01-4.0   | 12        | 8%      |
| 5.01-6.0   | 7         | 4.67%   |
| 0.51-1.0   | 7         | 4.67%   |
| 7.01-8.0   | 6         | 4%      |
| 0.01-0.5   | 6         | 4%      |
| 2.01-3.0   | 3         | 2%      |
| 8.01-16.0  | 2         | 1.33%   |
| 4.01-5.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 10.88%  |
| Samsung Electronics     | 19        | 9.84%   |
| Dell                    | 18        | 9.33%   |
| Lenovo                  | 17        | 8.81%   |
| LG Display              | 16        | 8.29%   |
| Chimei Innolux          | 15        | 7.77%   |
| BOE                     | 15        | 7.77%   |
| Goldstar                | 13        | 6.74%   |
| Hewlett-Packard         | 11        | 5.7%    |
| Acer                    | 5         | 2.59%   |
| Sharp                   | 4         | 2.07%   |
| InfoVision              | 4         | 2.07%   |
| Eizo                    | 4         | 2.07%   |
| BenQ                    | 4         | 2.07%   |
| Philips                 | 3         | 1.55%   |
| Ancor Communications    | 3         | 1.55%   |
| ViewSonic               | 2         | 1.04%   |
| PANDA                   | 2         | 1.04%   |
| LGD                     | 2         | 1.04%   |
| Lenovo Group Limited    | 2         | 1.04%   |
| Iiyama                  | 2         | 1.04%   |
| Gigabyte Technology     | 2         | 1.04%   |
| AOC                     | 2         | 1.04%   |
| Sun                     | 1         | 0.52%   |
| Sceptre Tech            | 1         | 0.52%   |
| Planar                  | 1         | 0.52%   |
| LG Electronics          | 1         | 0.52%   |
| Insignia                | 1         | 0.52%   |
| Chi Mei Optoelectronics | 1         | 0.52%   |
| BOE Technology Group    | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 2.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 1.92%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.44%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.44%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 3         | 1.44%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 1.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3         | 1.44%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.44%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.96%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.96%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.96%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.96%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.96%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.96%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.96%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 0.96%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 0.96%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 2         | 0.96%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.96%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.96%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.48%   |
| ViewSonic LCD Monitor VSC3E32 1920x1080 600x340mm 27.2-inch           | 1         | 0.48%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.48%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.48%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.48%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1         | 0.48%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.48%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch     | 1         | 0.48%   |
| Samsung Electronics S22B300 SAM08A9 1440x900 440x250mm 19.9-inch      | 1         | 0.48%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor S22B150                               | 1         | 0.48%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1         | 0.48%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 698x393mm 31.5-inch    | 1         | 0.48%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.48%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 0.48%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.48%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.48%   |
| LG Electronics LCD Monitor W2486 1920x1080                            | 1         | 0.48%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.48%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 53.49%  |
| 1366x768 (WXGA)    | 15        | 8.72%   |
| 3840x2160 (4K)     | 14        | 8.14%   |
| 2560x1440 (QHD)    | 12        | 6.98%   |
| 1600x900 (HD+)     | 11        | 6.4%    |
| 1920x1200 (WUXGA)  | 5         | 2.91%   |
| 3840x1080          | 4         | 2.33%   |
| 2560x1080          | 4         | 2.33%   |
| Unknown            | 4         | 2.33%   |
| 3440x1440          | 2         | 1.16%   |
| 1440x900 (WXGA+)   | 2         | 1.16%   |
| 9600x2160          | 1         | 0.58%   |
| 7680x2160          | 1         | 0.58%   |
| 6400x2160          | 1         | 0.58%   |
| 2048x1152          | 1         | 0.58%   |
| 1680x1050 (WSXGA+) | 1         | 0.58%   |
| 1280x800 (WXGA)    | 1         | 0.58%   |
| 1280x720 (HD)      | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 39        | 20.31%  |
| 14      | 24        | 12.5%   |
| 24      | 23        | 11.98%  |
| 27      | 20        | 10.42%  |
| 23      | 15        | 7.81%   |
| 13      | 15        | 7.81%   |
| Unknown | 11        | 5.73%   |
| 21      | 9         | 4.69%   |
| 31      | 6         | 3.13%   |
| 34      | 5         | 2.6%    |
| 12      | 5         | 2.6%    |
| 20      | 4         | 2.08%   |
| 17      | 3         | 1.56%   |
| 47      | 2         | 1.04%   |
| 32      | 2         | 1.04%   |
| 18      | 2         | 1.04%   |
| 54      | 1         | 0.52%   |
| 49      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 39      | 1         | 0.52%   |
| 25      | 1         | 0.52%   |
| 22      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 40.22%  |
| 501-600     | 49        | 26.63%  |
| 401-500     | 16        | 8.7%    |
| Unknown     | 11        | 5.98%   |
| 601-700     | 9         | 4.89%   |
| 201-300     | 9         | 4.89%   |
| 701-800     | 7         | 3.8%    |
| 1001-1500   | 4         | 2.17%   |
| 351-400     | 3         | 1.63%   |
| 801-900     | 2         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 125       | 82.24%  |
| 16/10   | 11        | 7.24%   |
| Unknown | 9         | 5.92%   |
| 21/9    | 5         | 3.29%   |
| 32/9    | 1         | 0.66%   |
| 3/2     | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 20.63%  |
| 201-250        | 36        | 19.05%  |
| 81-90          | 35        | 18.52%  |
| 301-350        | 20        | 10.58%  |
| 351-500        | 12        | 6.35%   |
| 251-300        | 11        | 5.82%   |
| Unknown        | 11        | 5.82%   |
| 151-200        | 6         | 3.17%   |
| 61-70          | 5         | 2.65%   |
| 501-1000       | 5         | 2.65%   |
| 71-80          | 4         | 2.12%   |
| 121-130        | 3         | 1.59%   |
| More than 1000 | 1         | 0.53%   |
| 141-150        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 37.3%   |
| 51-100        | 60        | 32.43%  |
| 101-120       | 29        | 15.68%  |
| Unknown       | 11        | 5.95%   |
| 161-240       | 9         | 4.86%   |
| More than 240 | 4         | 2.16%   |
| 1-50          | 3         | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 96        | 61.94%  |
| 2     | 41        | 26.45%  |
| 3     | 11        | 7.1%    |
| 0     | 7         | 4.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 117       | 52.47%  |
| Realtek Semiconductor             | 48        | 21.52%  |
| Lenovo                            | 14        | 6.28%   |
| Qualcomm Atheros                  | 10        | 4.48%   |
| Broadcom                          | 6         | 2.69%   |
| Broadcom Limited                  | 4         | 1.79%   |
| Ralink                            | 2         | 0.9%    |
| Marvell Technology Group          | 2         | 0.9%    |
| Huawei Technologies               | 2         | 0.9%    |
| Dell                              | 2         | 0.9%    |
| ASIX Electronics                  | 2         | 0.9%    |
| Xiaomi                            | 1         | 0.45%   |
| Sierra Wireless                   | 1         | 0.45%   |
| Samsung Electronics               | 1         | 0.45%   |
| Ralink Technology                 | 1         | 0.45%   |
| Microchip Technology              | 1         | 0.45%   |
| Micro Star International          | 1         | 0.45%   |
| MediaTek                          | 1         | 0.45%   |
| Luminary Micro                    | 1         | 0.45%   |
| ICS Advent                        | 1         | 0.45%   |
| IBM                               | 1         | 0.45%   |
| Ericsson Business Mobile Networks | 1         | 0.45%   |
| DisplayLink                       | 1         | 0.45%   |
| D-Link                            | 1         | 0.45%   |
| Arduino SA                        | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 33        | 10.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 4.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 4.32%   |
| Intel Wireless 8265 / 8275                                                     | 12        | 3.99%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 10        | 3.32%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 9         | 2.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 2.99%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 2.66%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 2.66%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                            | 7         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 1.99%   |
| Intel Wireless 8260                                                            | 6         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.99%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 1.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.33%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 1%      |
| Intel Wireless-AC 9260                                                         | 3         | 1%      |
| Intel Wireless 7265                                                            | 3         | 1%      |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1%      |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1%      |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.66%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.66%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.66%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.66%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.66%   |
| Intel Wireless 7260                                                            | 2         | 0.66%   |
| Intel Wireless 3165                                                            | 2         | 0.66%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.66%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.66%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.66%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.66%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.33%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1         | 0.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1         | 0.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.33%   |
| Ralink RT5572 Wireless Adapter                                                 | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 89        | 74.17%  |
| Realtek Semiconductor    | 9         | 7.5%    |
| Qualcomm Atheros         | 9         | 7.5%    |
| Broadcom                 | 4         | 3.33%   |
| Ralink                   | 2         | 1.67%   |
| Sierra Wireless          | 1         | 0.83%   |
| Ralink Technology        | 1         | 0.83%   |
| Micro Star International | 1         | 0.83%   |
| MediaTek                 | 1         | 0.83%   |
| Dell                     | 1         | 0.83%   |
| D-Link                   | 1         | 0.83%   |
| Broadcom Limited         | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 13        | 10.83%  |
| Intel Wireless 8265 / 8275                                                 | 12        | 10%     |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 10        | 8.33%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 9         | 7.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 7.5%    |
| Intel Wi-Fi 6 AX200                                                        | 7         | 5.83%   |
| Intel Wireless 8260                                                        | 6         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 5%      |
| Intel Centrino Ultimate-N 6300                                             | 4         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 2.5%    |
| Intel Wireless-AC 9260                                                     | 3         | 2.5%    |
| Intel Wireless 7265                                                        | 3         | 2.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 2.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.67%   |
| Intel Wireless 7260                                                        | 2         | 1.67%   |
| Intel Wireless 3165                                                        | 2         | 1.67%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.83%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.83%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.83%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.83%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.83%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 0.83%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.83%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 1         | 0.83%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 0.83%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 90        | 55.21%  |
| Realtek Semiconductor    | 42        | 25.77%  |
| Lenovo                   | 14        | 8.59%   |
| Broadcom Limited         | 3         | 1.84%   |
| Qualcomm Atheros         | 2         | 1.23%   |
| Marvell Technology Group | 2         | 1.23%   |
| Broadcom                 | 2         | 1.23%   |
| ASIX Electronics         | 2         | 1.23%   |
| Xiaomi                   | 1         | 0.61%   |
| Samsung Electronics      | 1         | 0.61%   |
| ICS Advent               | 1         | 0.61%   |
| IBM                      | 1         | 0.61%   |
| Huawei Technologies      | 1         | 0.61%   |
| DisplayLink              | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 33        | 18.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 8.57%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 5.71%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 4.57%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 4.57%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.43%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.29%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.29%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 2.29%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 2.29%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.71%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.71%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.14%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.14%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 1.14%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.14%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 1.14%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.14%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 1.14%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.14%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.14%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.14%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.14%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.14%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.57%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.57%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.57%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.57%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 0.57%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.57%   |
| IBM RNDIS/Ethernet Gadget                                                      | 1         | 0.57%   |
| Huawei E353/E3131                                                              | 1         | 0.57%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.57%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 0.57%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 0.57%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                         | 1         | 0.57%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.57%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 0.57%   |
| ASIX AX88772A Fast Ethernet                                                    | 1         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 136       | 52.51%  |
| WiFi     | 117       | 45.17%  |
| Modem    | 5         | 1.93%   |
| Unknown  | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 123       | 53.95%  |
| WiFi     | 104       | 45.61%  |
| Unknown  | 1         | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 93        | 63.7%   |
| 1     | 39        | 26.71%  |
| 3     | 8         | 5.48%   |
| 6     | 2         | 1.37%   |
| 132   | 1         | 0.68%   |
| 22    | 1         | 0.68%   |
| 8     | 1         | 0.68%   |
| 4     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 89.8%   |
| Yes  | 15        | 10.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 70.53%  |
| Cambridge Silicon Radio         | 7         | 7.37%   |
| Broadcom                        | 6         | 6.32%   |
| Qualcomm Atheros Communications | 3         | 3.16%   |
| IMC Networks                    | 3         | 3.16%   |
| Realtek Semiconductor           | 2         | 2.11%   |
| ASUSTek Computer                | 2         | 2.11%   |
| Ralink                          | 1         | 1.05%   |
| Qualcomm Atheros                | 1         | 1.05%   |
| Micro Star International        | 1         | 1.05%   |
| Foxconn / Hon Hai               | 1         | 1.05%   |
| Dell                            | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 34        | 35.79%  |
| Intel AX201 Bluetooth                                                               | 19        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 7.37%   |
| Intel Bluetooth wireless interface                                                  | 6         | 6.32%   |
| Intel AX200 Bluetooth                                                               | 6         | 6.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.16%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.11%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.11%   |
| ASUS BCM20702A0                                                                     | 2         | 2.11%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.05%   |
| Micro Star International Bluetooth Device                                           | 1         | 1.05%   |
| IMC Networks BCM20702A0                                                             | 1         | 1.05%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.05%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 126       | 54.08%  |
| Nvidia                 | 42        | 18.03%  |
| AMD                    | 18        | 7.73%   |
| Lenovo                 | 14        | 6.01%   |
| Plantronics            | 4         | 1.72%   |
| Texas Instruments      | 3         | 1.29%   |
| JMTek                  | 3         | 1.29%   |
| GN Netcom              | 3         | 1.29%   |
| Generalplus Technology | 3         | 1.29%   |
| Creative Labs          | 3         | 1.29%   |
| Realtek Semiconductor  | 2         | 0.86%   |
| Logitech               | 2         | 0.86%   |
| Creative Technology    | 2         | 0.86%   |
| Tenx Technology        | 1         | 0.43%   |
| RODE Microphones       | 1         | 0.43%   |
| Google                 | 1         | 0.43%   |
| Focusrite-Novation     | 1         | 0.43%   |
| DYNEX                  | 1         | 0.43%   |
| Dell                   | 1         | 0.43%   |
| C-Media Electronics    | 1         | 0.43%   |
| ASUSTek Computer       | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 19        | 7.57%   |
| Intel Cannon Lake PCH cAVS                                                        | 18        | 7.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 14        | 5.58%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 10        | 3.98%   |
| Intel Comet Lake PCH cAVS                                                         | 10        | 3.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 3.59%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8         | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8         | 3.19%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 7         | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7         | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 2.79%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 2.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 1.99%   |
| Plantronics BT600                                                                 | 4         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 1.59%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.59%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 1.2%    |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 3         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.2%    |
| Realtek Semiconductor USB Audio                                                   | 2         | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 0.8%    |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.8%    |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.8%    |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.8%    |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.8%    |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.8%    |
| Generalplus Technology USB Audio Device                                           | 2         | 0.8%    |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.8%    |
| Tenx Technology USB AUDIO                                                         | 1         | 0.4%    |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.4%    |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.4%    |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.4%    |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.4%    |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.4%    |
| Nvidia GF114 HDMI Audio Controller                                                | 1         | 0.4%    |
| Nvidia GF110 High Definition Audio Controller                                     | 1         | 0.4%    |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.4%    |
| Logitech H570e Mono                                                               | 1         | 0.4%    |
| Logitech H555 Headset                                                             | 1         | 0.4%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.4%    |
| Lenovo ThinkPad USB-C Dock Audio                                                  | 1         | 0.4%    |
| JMTek USB Speaker                                                                 | 1         | 0.4%    |
| JMTek USB PnP Audio Device                                                        | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 33.33%  |
| SK Hynix            | 13        | 21.67%  |
| Crucial             | 7         | 11.67%  |
| Kingston            | 5         | 8.33%   |
| Corsair             | 4         | 6.67%   |
| Micron Technology   | 3         | 5%      |
| Unknown             | 2         | 3.33%   |
| Unknown (0x0205)    | 1         | 1.67%   |
| Transcend           | 1         | 1.67%   |
| Smart               | 1         | 1.67%   |
| Patriot             | 1         | 1.67%   |
| Hewlett-Packard     | 1         | 1.67%   |
| GOODRAM             | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 3.08%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 3.08%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s         | 2         | 3.08%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 3.08%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.54%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 1.54%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 1.54%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.54%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 1.54%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.54%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 1.54%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.54%   |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 1.54%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 1.54%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.54%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                       | 1         | 1.54%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1         | 1.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.54%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                      | 1         | 1.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 1         | 1.54%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 1         | 1.54%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s            | 1         | 1.54%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s            | 1         | 1.54%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                  | 1         | 1.54%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s          | 1         | 1.54%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.54%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s                | 1         | 1.54%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 1.54%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s           | 1         | 1.54%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s            | 1         | 1.54%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s            | 1         | 1.54%   |
| Kingston RAM KHX2400C14S4/8G 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.54%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s            | 1         | 1.54%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s      | 1         | 1.54%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s         | 1         | 1.54%   |
| HP RAM 809082-091 16384MB DIMM DDR4 2400MT/s                    | 1         | 1.54%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s            | 1         | 1.54%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s        | 1         | 1.54%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s         | 1         | 1.54%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s         | 1         | 1.54%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s       | 1         | 1.54%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4096MB DIMM DDR4 2400MT/s        | 1         | 1.54%   |
| Crucial RAM BLS4G3D1609DS1S00 4GB DIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s           | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 60.42%  |
| DDR3   | 16        | 33.33%  |
| SDRAM  | 1         | 2.08%   |
| LPDDR4 | 1         | 2.08%   |
| LPDDR3 | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 51.06%  |
| DIMM         | 22        | 46.81%  |
| Row Of Chips | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 31.37%  |
| 16384 | 14        | 27.45%  |
| 8192  | 13        | 25.49%  |
| 32768 | 6         | 11.76%  |
| 65536 | 1         | 1.96%   |
| 2048  | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 12        | 23.08%  |
| 2667  | 11        | 21.15%  |
| 2400  | 8         | 15.38%  |
| 3200  | 6         | 11.54%  |
| 1333  | 5         | 9.62%   |
| 2133  | 4         | 7.69%   |
| 3600  | 2         | 3.85%   |
| 3266  | 1         | 1.92%   |
| 2933  | 1         | 1.92%   |
| 2666  | 1         | 1.92%   |
| 1334  | 1         | 1.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 50%     |
| Canon              | 2         | 33.33%  |
| Brother Industries | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 30.28%  |
| IMC Networks                           | 13        | 11.93%  |
| Acer                                   | 12        | 11.01%  |
| Logitech                               | 9         | 8.26%   |
| Realtek Semiconductor                  | 8         | 7.34%   |
| Sunplus Innovation Technology          | 6         | 5.5%    |
| Microdia                               | 6         | 5.5%    |
| Unknown                                | 3         | 2.75%   |
| Suyin                                  | 3         | 2.75%   |
| Samsung Electronics                    | 3         | 2.75%   |
| Lite-On Technology                     | 3         | 2.75%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.83%   |
| Syntek                                 | 1         | 0.92%   |
| Ruision                                | 1         | 0.92%   |
| Quanta                                 | 1         | 0.92%   |
| Microsoft                              | 1         | 0.92%   |
| Lenovo                                 | 1         | 0.92%   |
| Jieli Technology                       | 1         | 0.92%   |
| Generalplus Technology                 | 1         | 0.92%   |
| ARC International                      | 1         | 0.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 20        | 18.02%  |
| IMC Networks Integrated Camera                               | 11        | 9.91%   |
| Acer Integrated Camera                                       | 7         | 6.31%   |
| Realtek Integrated_Webcam_HD                                 | 6         | 5.41%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.6%    |
| Unknown FULL HD 1080P Webcam                                 | 3         | 2.7%    |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.7%    |
| Samsung Galaxy A5 (MTP)                                      | 3         | 2.7%    |
| Lite-On Integrated Camera                                    | 3         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 2.7%    |
| Chicony HP HD Camera                                         | 3         | 2.7%    |
| Acer SunplusIT Integrated Camera                             | 3         | 2.7%    |
| Microdia Webcam                                              | 2         | 1.8%    |
| Microdia Integrated Webcam                                   | 2         | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 1.8%    |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.8%    |
| Syntek Lenovo EasyCamera                                     | 1         | 0.9%    |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.9%    |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.9%    |
| Suyin HP Truevision HD                                       | 1         | 0.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.9%    |
| Sunplus Integrated Webcam                                    | 1         | 0.9%    |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.9%    |
| Ruision UVC Camera                                           | 1         | 0.9%    |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.9%    |
| Realtek NexiGo N960E FHD Webcam                              | 1         | 0.9%    |
| Quanta HP HD Camera                                          | 1         | 0.9%    |
| Microsoft LifeCam Cinema                                     | 1         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.9%    |
| Logitech Webcam C925e                                        | 1         | 0.9%    |
| Logitech Webcam C310                                         | 1         | 0.9%    |
| Logitech Webcam C270                                         | 1         | 0.9%    |
| Logitech HD Webcam C910                                      | 1         | 0.9%    |
| Logitech B525 HD Webcam                                      | 1         | 0.9%    |
| Lenovo Integrated Webcam                                     | 1         | 0.9%    |
| Jieli USB PHY 2.0                                            | 1         | 0.9%    |
| Generalplus GENERAL WEBCAM                                   | 1         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.9%    |
| Chicony Integrated IR Camera                                 | 1         | 0.9%    |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.9%    |
| Chicony HP Webcam                                            | 1         | 0.9%    |
| Chicony HD User Facing                                       | 1         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.9%    |
| ARC International Camera                                     | 1         | 0.9%    |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 0.9%    |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.9%    |
| Acer Integrated IR Camera                                    | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 58.54%  |
| Validity Sensors           | 13        | 31.71%  |
| Upek                       | 2         | 4.88%   |
| Shenzhen Goodix Technology | 1         | 2.44%   |
| Elan Microelectronics      | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 43.9%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 9.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 7.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 7.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.44%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 52.41%  |
| 1     | 56        | 38.62%  |
| 2     | 11        | 7.59%   |
| 3     | 2         | 1.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 48.24%  |
| Graphics card            | 10        | 11.76%  |
| Chipcard                 | 10        | 11.76%  |
| Unassigned class         | 7         | 8.24%   |
| Net/wireless             | 5         | 5.88%   |
| Net/ethernet             | 2         | 2.35%   |
| Multimedia controller    | 2         | 2.35%   |
| Communication controller | 2         | 2.35%   |
| Bluetooth                | 2         | 2.35%   |
| Storage/ide              | 1         | 1.18%   |
| Storage                  | 1         | 1.18%   |
| Network                  | 1         | 1.18%   |
| Card reader              | 1         | 1.18%   |

