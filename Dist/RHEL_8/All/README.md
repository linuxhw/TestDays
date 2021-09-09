RHEL 8 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_8/Desktop/README.md) and [notebooks](/Dist/RHEL_8/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=rhel-8

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
| ASUSTek    | PRIME B350M-A               | Desktop     | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Lenovo     | ThinkPad X230 Tablet 343... | Notebook    | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell       | XPS 15 9560                 | Notebook    | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo     | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Gigabyte   | Z390 AORUS ULTRA-CF         | Desktop     | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| AMD        | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
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
| HP         | OMEN by HP Laptop 15-dc1... | Notebook    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
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
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 9.46%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 13        | 8.78%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 7.43%   |
| 4.18.0-305.el8.x86_64        | 10        | 6.76%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 6.08%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 5.41%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 7         | 4.73%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 7         | 4.73%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 7         | 4.73%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 6         | 4.05%   |
| 4.18.0-193.el8.x86_64        | 6         | 4.05%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 4.05%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 3.38%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 3.38%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 2.7%    |
| 4.18.0-147.el8.x86_64        | 4         | 2.7%    |
| 4.18.0-147.8.1.el8_1.x86_64  | 4         | 2.7%    |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.03%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 2         | 1.35%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.35%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 2         | 1.35%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.68%   |
| 5.13.0-1.el8.elrepo.x86_64   | 1         | 0.68%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1         | 0.68%   |
| 4.19.150                     | 1         | 0.68%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.68%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.68%   |
| 4.18.0-221.el8.x86_64        | 1         | 0.68%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.68%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.68%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.68%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.68%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.68%   |
| Unknown                      | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 114       | 95.8%   |
| 5.9.1    | 1         | 0.84%   |
| 5.13.0   | 1         | 0.84%   |
| 5.10.6   | 1         | 0.84%   |
| 4.19.150 | 1         | 0.84%   |
| Unknown  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 114       | 95.8%   |
| 5.9     | 1         | 0.84%   |
| 5.13    | 1         | 0.84%   |
| 5.10    | 1         | 0.84%   |
| 4.19    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 118       | 99.16%  |
| Unknown | 1         | 0.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 101       | 82.11%  |
| Unknown       | 9         | 7.32%   |
| GNOME Classic | 7         | 5.69%   |
| KDE5          | 4         | 3.25%   |
| KDE           | 2         | 1.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 68        | 54.84%  |
| Wayland | 51        | 41.13%  |
| Unknown | 5         | 4.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 99        | 79.84%  |
| GDM     | 25        | 20.16%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 80        | 65.57%  |
| Unknown | 9         | 7.38%   |
| en_GB   | 6         | 4.92%   |
| en_IN   | 4         | 3.28%   |
| ru_RU   | 3         | 2.46%   |
| fr_FR   | 3         | 2.46%   |
| pl_PL   | 2         | 1.64%   |
| nl_NL   | 2         | 1.64%   |
| de_DE   | 2         | 1.64%   |
| pt_BR   | 1         | 0.82%   |
| ko_KR   | 1         | 0.82%   |
| ja_JP   | 1         | 0.82%   |
| it_IT   | 1         | 0.82%   |
| es_ES   | 1         | 0.82%   |
| es_EC   | 1         | 0.82%   |
| es_AR   | 1         | 0.82%   |
| en_NZ   | 1         | 0.82%   |
| en_IE   | 1         | 0.82%   |
| de_CH   | 1         | 0.82%   |
| cs_CZ   | 1         | 0.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 93        | 76.23%  |
| BIOS | 29        | 23.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 106       | 89.08%  |
| Ext4    | 12        | 10.08%  |
| Unknown | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 94        | 77.05%  |
| GPT     | 24        | 19.67%  |
| MBR     | 4         | 3.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 97.48%  |
| Yes       | 3         | 2.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 92.5%   |
| Yes       | 9         | 7.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 47        | 39.5%   |
| Dell                | 21        | 17.65%  |
| Hewlett-Packard     | 16        | 13.45%  |
| ASUSTek Computer    | 12        | 10.08%  |
| MSI                 | 4         | 3.36%   |
| Gigabyte Technology | 4         | 3.36%   |
| ASRock              | 4         | 3.36%   |
| Supermicro          | 2         | 1.68%   |
| Sony                | 2         | 1.68%   |
| Intel               | 2         | 1.68%   |
| TUXEDO              | 1         | 0.84%   |
| Timi                | 1         | 0.84%   |
| AMD                 | 1         | 0.84%   |
| Alienware           | 1         | 0.84%   |
| Unknown             | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.68%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.68%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.68%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.68%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.68%   |
| Dell Latitude E6430                      | 2         | 1.68%   |
| Dell Latitude 5300                       | 2         | 1.68%   |
| TUXEDO N13xWU                            | 1         | 0.84%   |
| Timi TM1707                              | 1         | 0.84%   |
| Supermicro X7DW3                         | 1         | 0.84%   |
| Supermicro X10DRi                        | 1         | 0.84%   |
| Sony VPCEB4L1R                           | 1         | 0.84%   |
| Sony VPCEB23FM                           | 1         | 0.84%   |
| MSI MS-7B51                              | 1         | 0.84%   |
| MSI MS-7B33                              | 1         | 0.84%   |
| MSI MS-7A37                              | 1         | 0.84%   |
| MSI MS-7752                              | 1         | 0.84%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.84%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.84%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.84%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.84%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.84%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.84%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.84%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.84%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.84%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.84%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.84%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.84%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.84%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.84%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.84%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.84%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 0.84%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 0.84%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 0.84%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 0.84%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 0.84%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 0.84%   |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 0.84%   |
| Lenovo ThinkCentre M920t 10SFS03200      | 1         | 0.84%   |
| Lenovo ThinkCentre M91p 0266RZ1          | 1         | 0.84%   |
| Lenovo S40-40 F0AX00EAPB                 | 1         | 0.84%   |
| Intel NUC10i7FNK                         | 1         | 0.84%   |
| Intel DX79SR AAG57199-200                | 1         | 0.84%   |
| HP ZBook Studio G5                       | 1         | 0.84%   |
| HP ZBook 15 G5                           | 1         | 0.84%   |
| HP Z840 Workstation                      | 1         | 0.84%   |
| HP Z620 Workstation                      | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 41        | 34.45%  |
| Dell Latitude       | 8         | 6.72%   |
| Dell Precision      | 6         | 5.04%   |
| Dell Inspiron       | 3         | 2.52%   |
| ASUS PRIME          | 3         | 2.52%   |
| Lenovo ThinkCentre  | 2         | 1.68%   |
| HP ZBook            | 2         | 1.68%   |
| HP Z230             | 2         | 1.68%   |
| HP EliteBook        | 2         | 1.68%   |
| ASUS ROG            | 2         | 1.68%   |
| TUXEDO N13xWU       | 1         | 0.84%   |
| Timi TM1707         | 1         | 0.84%   |
| Supermicro X7DW3    | 1         | 0.84%   |
| Supermicro X10DRi   | 1         | 0.84%   |
| Sony VPCEB4L1R      | 1         | 0.84%   |
| Sony VPCEB23FM      | 1         | 0.84%   |
| MSI MS-7B51         | 1         | 0.84%   |
| MSI MS-7B33         | 1         | 0.84%   |
| MSI MS-7A37         | 1         | 0.84%   |
| MSI MS-7752         | 1         | 0.84%   |
| Lenovo Yoga         | 1         | 0.84%   |
| Lenovo ThinkSystem  | 1         | 0.84%   |
| Lenovo ThinkpadT460 | 1         | 0.84%   |
| Lenovo S40-40       | 1         | 0.84%   |
| Intel NUC10i7FNK    | 1         | 0.84%   |
| Intel DX79SR        | 1         | 0.84%   |
| HP Z840             | 1         | 0.84%   |
| HP Z620             | 1         | 0.84%   |
| HP ProLiant         | 1         | 0.84%   |
| HP ProBook          | 1         | 0.84%   |
| HP Pavilion         | 1         | 0.84%   |
| HP OMEN             | 1         | 0.84%   |
| HP EliteDesk        | 1         | 0.84%   |
| HP 290              | 1         | 0.84%   |
| HP 260-P020il       | 1         | 0.84%   |
| HP 250              | 1         | 0.84%   |
| Gigabyte Z490       | 1         | 0.84%   |
| Gigabyte Z390       | 1         | 0.84%   |
| Gigabyte B85M-D3V-A | 1         | 0.84%   |
| Gigabyte B75-D3V    | 1         | 0.84%   |
| Dell XPS            | 1         | 0.84%   |
| Dell Vostro         | 1         | 0.84%   |
| Dell PowerEdge      | 1         | 0.84%   |
| Dell G3             | 1         | 0.84%   |
| ASUS Zephyrus       | 1         | 0.84%   |
| ASUS Z10PE-D16      | 1         | 0.84%   |
| ASUS TUF            | 1         | 0.84%   |
| ASUS P8Z77-V        | 1         | 0.84%   |
| ASUS MINIPC         | 1         | 0.84%   |
| ASUS GL502VMK       | 1         | 0.84%   |
| ASUS All            | 1         | 0.84%   |
| ASRock X99E-ITX     | 1         | 0.84%   |
| ASRock H91M-PLUS    | 1         | 0.84%   |
| ASRock H270         | 1         | 0.84%   |
| ASRock A300M-STX    | 1         | 0.84%   |
| AMD 970A-D3         | 1         | 0.84%   |
| Alienware Aurora    | 1         | 0.84%   |
| Unknown             | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 38        | 31.93%  |
| 2019 | 34        | 28.57%  |
| 2018 | 15        | 12.61%  |
| 2021 | 6         | 5.04%   |
| 2017 | 4         | 3.36%   |
| 2016 | 4         | 3.36%   |
| 2013 | 4         | 3.36%   |
| 2012 | 4         | 3.36%   |
| 2014 | 3         | 2.52%   |
| 2011 | 3         | 2.52%   |
| 2010 | 2         | 1.68%   |
| 2015 | 1         | 0.84%   |
| 2009 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 73        | 61.34%  |
| Desktop     | 38        | 31.93%  |
| Server      | 4         | 3.36%   |
| Mini pc     | 2         | 1.68%   |
| Convertible | 1         | 0.84%   |
| All in one  | 1         | 0.84%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 90.83%  |
| Enabled  | 11        | 9.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 119       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 35        | 28.46%  |
| 4.01-8.0        | 21        | 17.07%  |
| 16.01-24.0      | 20        | 16.26%  |
| 8.01-16.0       | 18        | 14.63%  |
| 64.01-256.0     | 15        | 12.2%   |
| 3.01-4.0        | 6         | 4.88%   |
| 24.01-32.0      | 5         | 4.07%   |
| More than 256.0 | 2         | 1.63%   |
| Unknown         | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 48        | 35.04%  |
| 2.01-3.0        | 26        | 18.98%  |
| 8.01-16.0       | 26        | 18.98%  |
| 3.01-4.0        | 20        | 14.6%   |
| 1.01-2.0        | 11        | 8.03%   |
| 24.01-32.0      | 2         | 1.46%   |
| 16.01-24.0      | 2         | 1.46%   |
| More than 256.0 | 1         | 0.73%   |
| Unknown         | 1         | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 57.14%  |
| 2      | 28        | 22.22%  |
| 3      | 14        | 11.11%  |
| 4      | 5         | 3.97%   |
| 5      | 3         | 2.38%   |
| 6      | 2         | 1.59%   |
| 8      | 1         | 0.79%   |
| 7      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 71.9%   |
| Yes       | 34        | 28.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 92.5%   |
| No        | 9         | 7.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 79.83%  |
| No        | 24        | 20.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 61.79%  |
| No        | 47        | 38.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 20%     |
| India        | 13        | 10.83%  |
| UK           | 9         | 7.5%    |
| Germany      | 7         | 5.83%   |
| Czechia      | 7         | 5.83%   |
| Canada       | 6         | 5%      |
| France       | 4         | 3.33%   |
| Russia       | 3         | 2.5%    |
| Netherlands  | 3         | 2.5%    |
| Lithuania    | 3         | 2.5%    |
| Italy        | 3         | 2.5%    |
| Ukraine      | 2         | 1.67%   |
| Switzerland  | 2         | 1.67%   |
| Spain        | 2         | 1.67%   |
| South Korea  | 2         | 1.67%   |
| South Africa | 2         | 1.67%   |
| Poland       | 2         | 1.67%   |
| Mexico       | 2         | 1.67%   |
| Japan        | 2         | 1.67%   |
| Australia    | 2         | 1.67%   |
| Turkmenistan | 1         | 0.83%   |
| Sweden       | 1         | 0.83%   |
| Singapore    | 1         | 0.83%   |
| Romania      | 1         | 0.83%   |
| Pakistan     | 1         | 0.83%   |
| New Zealand  | 1         | 0.83%   |
| Nepal        | 1         | 0.83%   |
| Myanmar      | 1         | 0.83%   |
| Morocco      | 1         | 0.83%   |
| Kuwait       | 1         | 0.83%   |
| Ireland      | 1         | 0.83%   |
| Indonesia    | 1         | 0.83%   |
| Egypt        | 1         | 0.83%   |
| Ecuador      | 1         | 0.83%   |
| Colombia     | 1         | 0.83%   |
| Bulgaria     | 1         | 0.83%   |
| Brazil       | 1         | 0.83%   |
| Belarus      | 1         | 0.83%   |
| Armenia      | 1         | 0.83%   |
| Argentina    | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Brno                     | 5         | 3.88%   |
| Munich                   | 3         | 2.33%   |
| Toronto                  | 2         | 1.55%   |
| Mumbai                   | 2         | 1.55%   |
| Milan                    | 2         | 1.55%   |
| Mexico City              | 2         | 1.55%   |
| Kyiv                     | 2         | 1.55%   |
| Doetinchem               | 2         | 1.55%   |
| Coimbatore               | 2         | 1.55%   |
| Bengaluru                | 2         | 1.55%   |
| ? iauliai                | 2         | 1.55%   |
| Yerevan                  | 1         | 0.78%   |
| Wroclaw                  | 1         | 0.78%   |
| Wiesbaden                | 1         | 0.78%   |
| Weybridge                | 1         | 0.78%   |
| Valmontone               | 1         | 0.78%   |
| Vaestra Froelunda        | 1         | 0.78%   |
| Tauranga                 | 1         | 0.78%   |
| Taringa                  | 1         | 0.78%   |
| Suwon                    | 1         | 0.78%   |
| Sumida                   | 1         | 0.78%   |
| Stroud                   | 1         | 0.78%   |
| Spokane                  | 1         | 0.78%   |
| Sofia                    | 1         | 0.78%   |
| Singapore                | 1         | 0.78%   |
| Sheffield                | 1         | 0.78%   |
| Seoul                    | 1         | 0.78%   |
| Saratov                  | 1         | 0.78%   |
| San Jose                 | 1         | 0.78%   |
| San Francisco            | 1         | 0.78%   |
| Sammamish                | 1         | 0.78%   |
| Sal?©                    | 1         | 0.78%   |
| Saint-Alphonse-Rodriguez | 1         | 0.78%   |
| Sagaing                  | 1         | 0.78%   |
| Roudnice nad Labem       | 1         | 0.78%   |
| Roha                     | 1         | 0.78%   |
| Reims                    | 1         | 0.78%   |
| Raleigh                  | 1         | 0.78%   |
| Quito                    | 1         | 0.78%   |
| Queenscliff              | 1         | 0.78%   |
| Queens                   | 1         | 0.78%   |
| Pune                     | 1         | 0.78%   |
| Prague                   | 1         | 0.78%   |
| Port Elizabeth           | 1         | 0.78%   |
| Pleasanton               | 1         | 0.78%   |
| Pernis                   | 1         | 0.78%   |
| Paris                    | 1         | 0.78%   |
| Paraiso do Tocantins     | 1         | 0.78%   |
| Paragould                | 1         | 0.78%   |
| Paracuellos de Jarama    | 1         | 0.78%   |
| Oyama                    | 1         | 0.78%   |
| Ottawa                   | 1         | 0.78%   |
| Ogden                    | 1         | 0.78%   |
| Neuves-Maisons           | 1         | 0.78%   |
| Musselburgh              | 1         | 0.78%   |
| Moscow                   | 1         | 0.78%   |
| Montreal                 | 1         | 0.78%   |
| Mississauga              | 1         | 0.78%   |
| Miroslava                | 1         | 0.78%   |
| Minsk                    | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 53     | 19.44%  |
| WDC                 | 26        | 46     | 14.44%  |
| Seagate             | 22        | 34     | 12.22%  |
| Toshiba             | 14        | 22     | 7.78%   |
| Sandisk             | 12        | 18     | 6.67%   |
| SK Hynix            | 11        | 14     | 6.11%   |
| Kingston            | 9         | 11     | 5%      |
| Intel               | 9         | 13     | 5%      |
| Unknown             | 5         | 7      | 2.78%   |
| Crucial             | 5         | 9      | 2.78%   |
| Micron Technology   | 4         | 11     | 2.22%   |
| Hitachi             | 3         | 3      | 1.67%   |
| HGST                | 3         | 3      | 1.67%   |
| Silicon Motion      | 2         | 3      | 1.11%   |
| PNY                 | 2         | 5      | 1.11%   |
| Hewlett-Packard     | 2         | 3      | 1.11%   |
| Corsair             | 2         | 2      | 1.11%   |
| A-DATA Technology   | 2         | 2      | 1.11%   |
| XPG                 | 1         | 1      | 0.56%   |
| Team                | 1         | 2      | 0.56%   |
| SMI                 | 1         | 2      | 0.56%   |
| Phison              | 1         | 2      | 0.56%   |
| OCZ                 | 1         | 2      | 0.56%   |
| Lite-On             | 1         | 1      | 0.56%   |
| Lenovo              | 1         | 1      | 0.56%   |
| Hoodisk             | 1         | 1      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| DELLBOSS            | 1         | 1      | 0.56%   |
| Dell                | 1         | 1      | 0.56%   |
| China               | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB        | 7         | 3.4%    |
| Sandisk NVMe SSD Drive 256GB         | 5         | 2.43%   |
| Samsung SSD 860 EVO 1TB              | 5         | 2.43%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 2.43%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 2.43%   |
| Toshiba NVMe SSD Drive 256GB         | 4         | 1.94%   |
| Samsung NVMe SSD Drive 500GB         | 3         | 1.46%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 1.46%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 0.97%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.97%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.97%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 0.97%   |
| Seagate Expansion 1TB                | 2         | 0.97%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.97%   |
| Samsung Portable SSD T5 500GB        | 2         | 0.97%   |
| Samsung NVMe SSD Drive 2TB           | 2         | 0.97%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.97%   |
| Micron NVMe SSD Drive 256GB          | 2         | 0.97%   |
| Kingston SUV500120G 120GB SSD        | 2         | 0.97%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.97%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.97%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.97%   |
| Intel NVMe SSD Drive 2TB             | 2         | 0.97%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.97%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.97%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.49%   |
| WDC WDS400T2B0A-00SM50 4TB SSD       | 1         | 0.49%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.49%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1         | 0.49%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.49%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.49%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 0.49%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.49%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1         | 0.49%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1         | 0.49%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1         | 0.49%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.49%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 1         | 0.49%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1         | 0.49%   |
| WDC WD40EZRZ-19GXCB0 4TB             | 1         | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.49%   |
| WDC WD4005FZBX-00K5WB0 4TB           | 1         | 0.49%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1         | 0.49%   |
| WDC WD2500BEKT-75F3T0 250GB          | 1         | 0.49%   |
| WDC WD2500AAKX-083CA1 250GB          | 1         | 0.49%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 1         | 0.49%   |
| WDC WD20EARS-22MVWB0 2TB             | 1         | 0.49%   |
| WDC WD20 SPZX-11UA7T0 2TB            | 1         | 0.49%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.49%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-75WN4A0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.49%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 1         | 0.49%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 0.49%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.49%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 33     | 39.29%  |
| WDC                 | 19        | 35     | 33.93%  |
| Toshiba             | 6         | 10     | 10.71%  |
| Hitachi             | 3         | 3      | 5.36%   |
| HGST                | 3         | 3      | 5.36%   |
| Samsung Electronics | 1         | 1      | 1.79%   |
| Hewlett-Packard     | 1         | 1      | 1.79%   |
| DELLBOSS            | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 28.81%  |
| Kingston            | 9         | 11     | 15.25%  |
| WDC                 | 6         | 8      | 10.17%  |
| Crucial             | 5         | 9      | 8.47%   |
| SanDisk             | 4         | 5      | 6.78%   |
| SK Hynix            | 2         | 5      | 3.39%   |
| PNY                 | 2         | 5      | 3.39%   |
| Micron Technology   | 2         | 7      | 3.39%   |
| Intel               | 2         | 3      | 3.39%   |
| Corsair             | 2         | 2      | 3.39%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| Toshiba             | 1         | 1      | 1.69%   |
| Team                | 1         | 2      | 1.69%   |
| Seagate             | 1         | 1      | 1.69%   |
| OCZ                 | 1         | 2      | 1.69%   |
| Hoodisk             | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 61        | 97     | 35.67%  |
| SSD     | 55        | 85     | 32.16%  |
| HDD     | 51        | 87     | 29.82%  |
| MMC     | 2         | 3      | 1.17%   |
| Unknown | 2         | 3      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 158    | 48.98%  |
| NVMe | 61        | 97     | 41.5%   |
| SAS  | 12        | 17     | 8.16%   |
| MMC  | 2         | 3      | 1.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 71     | 42.86%  |
| 0.51-1.0   | 35        | 55     | 31.25%  |
| 1.01-2.0   | 16        | 20     | 14.29%  |
| 3.01-4.0   | 7         | 17     | 6.25%   |
| 4.01-10.0  | 4         | 7      | 3.57%   |
| 2.01-3.0   | 1         | 1      | 0.89%   |
| 10.01-20.0 | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 37.3%   |
| 251-500        | 20        | 15.87%  |
| 501-1000       | 19        | 15.08%  |
| More than 3000 | 13        | 10.32%  |
| 1001-2000      | 11        | 8.73%   |
| 2001-3000      | 5         | 3.97%   |
| 51-100         | 5         | 3.97%   |
| Unknown        | 3         | 2.38%   |
| 21-50          | 2         | 1.59%   |
| 1-20           | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 32        | 23.7%   |
| 1-20           | 27        | 20%     |
| 101-250        | 26        | 19.26%  |
| 51-100         | 18        | 13.33%  |
| 501-1000       | 9         | 6.67%   |
| 251-500        | 8         | 5.93%   |
| 1001-2000      | 6         | 4.44%   |
| More than 3000 | 3         | 2.22%   |
| 2001-3000      | 3         | 2.22%   |
| Unknown        | 3         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB | 1         | 1      | 50%     |
| Hitachi HDS722020ALA330 2TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 96        | 217    | 75.59%  |
| Works    | 29        | 56     | 22.83%  |
| Malfunc  | 2         | 2      | 1.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 76        | 48.1%   |
| Samsung Electronics          | 24        | 15.19%  |
| AMD                          | 10        | 6.33%   |
| SK Hynix                     | 9         | 5.7%    |
| Sandisk                      | 9         | 5.7%    |
| Toshiba America Info Systems | 7         | 4.43%   |
| Marvell Technology Group     | 4         | 2.53%   |
| Broadcom / LSI               | 4         | 2.53%   |
| Silicon Motion               | 3         | 1.9%    |
| Micron Technology            | 2         | 1.27%   |
| KIOXIA                       | 2         | 1.27%   |
| Phison Electronics           | 1         | 0.63%   |
| LSI Logic / Symbios Logic    | 1         | 0.63%   |
| Lite-On Technology           | 1         | 0.63%   |
| Lenovo                       | 1         | 0.63%   |
| Hewlett-Packard              | 1         | 0.63%   |
| Biwin Storage Technology     | 1         | 0.63%   |
| ASMedia Technology           | 1         | 0.63%   |
| ADATA Technology             | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19        | 10.8%   |
| SK Hynix Non-Volatile memory controller                                                 | 9         | 5.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 5.11%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 5.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 7         | 3.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 3.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 3.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5         | 2.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 2.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 2.27%   |
| Intel SSD 660P Series                                                                   | 4         | 2.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4         | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.7%    |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 1.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.14%   |
| Samsung NVMe Controller                                                                 | 2         | 1.14%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.14%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 2         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.14%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 1.14%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.57%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.57%   |
| Samsung NVMe SSD Controller PM173X                                                      | 1         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.57%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1         | 0.57%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1         | 0.57%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 0.57%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1         | 0.57%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1         | 0.57%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.57%   |
| Lenovo Non-Volatile memory controller                                                   | 1         | 0.57%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 0.57%   |
| Intel NVMe Datacenter SSD [Optane]                                                      | 1         | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 0.57%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 0.57%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 0.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.57%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1         | 0.57%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.57%   |
| HP Smart Array Gen9 Controllers                                                         | 1         | 0.57%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 0.57%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3516                                                | 1         | 0.57%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 76        | 49.67%  |
| NVMe | 61        | 39.87%  |
| RAID | 10        | 6.54%   |
| IDE  | 4         | 2.61%   |
| SAS  | 2         | 1.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 106       | 89.08%  |
| AMD    | 13        | 10.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 6.72%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 5         | 4.2%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 3.36%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 3.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.52%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3         | 2.52%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.52%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.68%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.68%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.68%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.68%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.68%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.84%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.84%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.84%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.84%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.84%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.84%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.84%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.84%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.84%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.84%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.84%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.84%   |
| Intel Core i7-9700F CPU @ 3.00GHz             | 1         | 0.84%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.84%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.84%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.84%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.84%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.84%   |
| Intel Core i7-3820 CPU @ 3.60GHz              | 1         | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.84%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.84%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.84%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.84%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.84%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 0.84%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 1         | 0.84%   |
| Intel Core i5-3550 CPU @ 3.30GHz              | 1         | 0.84%   |
| Intel Core i5-3450 CPU @ 3.10GHz              | 1         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 53        | 44.54%  |
| Intel Core i5      | 29        | 24.37%  |
| Intel Xeon         | 12        | 10.08%  |
| Intel Core i3      | 7         | 5.88%   |
| AMD Ryzen 7        | 5         | 4.2%    |
| Intel Pentium Gold | 2         | 1.68%   |
| Intel Core i9      | 2         | 1.68%   |
| AMD Ryzen 3        | 2         | 1.68%   |
| AMD EPYC           | 2         | 1.68%   |
| Intel Pentium      | 1         | 0.84%   |
| AMD Ryzen 9        | 1         | 0.84%   |
| AMD Ryzen 7 PRO    | 1         | 0.84%   |
| AMD Ryzen 5        | 1         | 0.84%   |
| AMD FX             | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 51        | 42.86%  |
| 2      | 29        | 24.37%  |
| 6      | 21        | 17.65%  |
| 8      | 8         | 6.72%   |
| 20     | 2         | 1.68%   |
| 16     | 2         | 1.68%   |
| 12     | 2         | 1.68%   |
| 96     | 1         | 0.84%   |
| 64     | 1         | 0.84%   |
| 36     | 1         | 0.84%   |
| 24     | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 110       | 92.44%  |
| 2      | 9         | 7.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 102       | 85%     |
| 1      | 18        | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 115       | 95.04%  |
| Unknown        | 6         | 4.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 17        | 14.05%  |
| 0x906ea    | 12        | 9.92%   |
| 0x806ea    | 9         | 7.44%   |
| 0x306a9    | 9         | 7.44%   |
| 0xa0652    | 6         | 4.96%   |
| 0x906ed    | 6         | 4.96%   |
| 0x306c3    | 6         | 4.96%   |
| 0x206a7    | 6         | 4.96%   |
| 0x906e9    | 4         | 3.31%   |
| 0x506e3    | 4         | 3.31%   |
| Unknown    | 4         | 3.31%   |
| 0x806e9    | 3         | 2.48%   |
| 0x406e3    | 3         | 2.48%   |
| 0x306f2    | 3         | 2.48%   |
| 0x306d4    | 3         | 2.48%   |
| 0x20655    | 3         | 2.48%   |
| 0x08108102 | 3         | 2.48%   |
| 0x206d7    | 2         | 1.65%   |
| 0x08600103 | 2         | 1.65%   |
| 0xa0660    | 1         | 0.83%   |
| 0xa0655    | 1         | 0.83%   |
| 0x906eb    | 1         | 0.83%   |
| 0x406f1    | 1         | 0.83%   |
| 0x40651    | 1         | 0.83%   |
| 0x306e4    | 1         | 0.83%   |
| 0x20652    | 1         | 0.83%   |
| 0x10676    | 1         | 0.83%   |
| 0x0a001119 | 1         | 0.83%   |
| 0x08701013 | 1         | 0.83%   |
| 0x08600104 | 1         | 0.83%   |
| 0x08301034 | 1         | 0.83%   |
| 0x0810100b | 1         | 0.83%   |
| 0x08001138 | 1         | 0.83%   |
| 0x08001137 | 1         | 0.83%   |
| 0x06000852 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 53        | 44.54%  |
| Haswell     | 11        | 9.24%   |
| IvyBridge   | 10        | 8.4%    |
| SandyBridge | 8         | 6.72%   |
| CometLake   | 8         | 6.72%   |
| Skylake     | 7         | 5.88%   |
| Zen 2       | 5         | 4.2%    |
| Westmere    | 4         | 3.36%   |
| Broadwell   | 4         | 3.36%   |
| Zen+        | 3         | 2.52%   |
| Zen         | 3         | 2.52%   |
| Piledriver  | 1         | 0.84%   |
| Penryn      | 1         | 0.84%   |
| Unknown     | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 78        | 53.79%  |
| Nvidia                     | 47        | 32.41%  |
| AMD                        | 16        | 11.03%  |
| Matrox Electronics Systems | 3         | 2.07%   |
| ASPEED Technology          | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 11        | 7.48%   |
| Intel UHD Graphics 620                                                      | 9         | 6.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 7         | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 4.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 5         | 3.4%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 2.72%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 2.04%   |
| Intel HD Graphics 5500                                                      | 3         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 2.04%   |
| AMD Renoir                                                                  | 3         | 2.04%   |
| AMD Picasso                                                                 | 3         | 2.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.36%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 1.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.36%   |
| Intel HD Graphics 630                                                       | 2         | 1.36%   |
| Intel HD Graphics 620                                                       | 2         | 1.36%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.68%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.68%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia GP107GLM [Quadro P620]                                               | 1         | 0.68%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.68%   |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.68%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.68%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.68%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.68%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 1         | 0.68%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 0.68%   |
| Nvidia GM107GL [NVS 810]                                                    | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.68%   |
| Nvidia GK107GLM [Quadro K2000M]                                             | 1         | 0.68%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1         | 0.68%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 0.68%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 0.68%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1         | 0.68%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1         | 0.68%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1         | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 0.68%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 0.68%   |
| Nvidia GF106GLM [Quadro 2000M]                                              | 1         | 0.68%   |
| Nvidia GA100 [A100 PCIe 40GB]                                               | 1         | 0.68%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1         | 0.68%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 0.68%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1         | 0.68%   |
| Matrox Electronics Systems MGA G200EH                                       | 1         | 0.68%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 56        | 47.06%  |
| 1 x Nvidia      | 30        | 25.21%  |
| Intel + Nvidia  | 13        | 10.92%  |
| 1 x AMD         | 10        | 8.4%    |
| Intel + AMD     | 4         | 3.36%   |
| 1 x Matrox      | 2         | 1.68%   |
| AMD + Nvidia    | 2         | 1.68%   |
| Nvidia + Matrox | 1         | 0.84%   |
| Nvidia + ASPEED | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 80.83%  |
| Proprietary | 20        | 16.67%  |
| Unknown     | 3         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 58.2%   |
| 1.01-2.0   | 15        | 12.3%   |
| 3.01-4.0   | 9         | 7.38%   |
| 5.01-6.0   | 7         | 5.74%   |
| 0.51-1.0   | 6         | 4.92%   |
| 0.01-0.5   | 6         | 4.92%   |
| 7.01-8.0   | 4         | 3.28%   |
| 2.01-3.0   | 2         | 1.64%   |
| 4.01-5.0   | 1         | 0.82%   |
| 8.01-16.0  | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 17        | 11.04%  |
| AU Optronics            | 17        | 11.04%  |
| Lenovo                  | 16        | 10.39%  |
| Samsung Electronics     | 14        | 9.09%   |
| Chimei Innolux          | 13        | 8.44%   |
| BOE                     | 11        | 7.14%   |
| LG Display              | 10        | 6.49%   |
| Hewlett-Packard         | 10        | 6.49%   |
| Goldstar                | 8         | 5.19%   |
| Eizo                    | 4         | 2.6%    |
| BenQ                    | 4         | 2.6%    |
| Acer                    | 4         | 2.6%    |
| Sharp                   | 3         | 1.95%   |
| Ancor Communications    | 3         | 1.95%   |
| Philips                 | 2         | 1.3%    |
| PANDA                   | 2         | 1.3%    |
| LGD                     | 2         | 1.3%    |
| Lenovo Group Limited    | 2         | 1.3%    |
| InfoVision              | 2         | 1.3%    |
| Iiyama                  | 2         | 1.3%    |
| Gigabyte Technology     | 2         | 1.3%    |
| ViewSonic               | 1         | 0.65%   |
| Sceptre Tech            | 1         | 0.65%   |
| Planar                  | 1         | 0.65%   |
| LG Electronics          | 1         | 0.65%   |
| Insignia                | 1         | 0.65%   |
| Chi Mei Optoelectronics | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 2.41%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 2.41%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.81%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 3         | 1.81%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.81%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.2%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.2%    |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.2%    |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 2         | 1.2%    |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 1.2%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.2%    |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 1.2%    |
| Hewlett-Packard 27y HPN351C 1920x1080 598x336mm 27.0-inch             | 2         | 1.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.2%    |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 2         | 1.2%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.2%    |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.6%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.6%    |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.6%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.6%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.6%    |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.6%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.6%    |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch     | 1         | 0.6%    |
| Samsung Electronics S22B300 SAM08A9 1440x900 440x250mm 19.9-inch      | 1         | 0.6%    |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor S22B150                               | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1         | 0.6%    |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.6%    |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch     | 1         | 0.6%    |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.6%    |
| LG Electronics LCD Monitor W2486 1920x1080                            | 1         | 0.6%    |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.6%    |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.6%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.6%    |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.6%    |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 1         | 0.6%    |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch              | 1         | 0.6%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.6%    |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 1         | 0.6%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.6%    |
| Lenovo LBG AIO PC LEN8000 1920x1080 521x293mm 23.5-inch               | 1         | 0.6%    |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1         | 0.6%    |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 55.15%  |
| 3840x2160 (4K)     | 11        | 8.09%   |
| 1366x768 (WXGA)    | 11        | 8.09%   |
| 1600x900 (HD+)     | 9         | 6.62%   |
| 2560x1440 (QHD)    | 8         | 5.88%   |
| 1920x1200 (WUXGA)  | 5         | 3.68%   |
| 3840x1080          | 4         | 2.94%   |
| Unknown            | 3         | 2.21%   |
| 3440x1440          | 2         | 1.47%   |
| 9600x2160          | 1         | 0.74%   |
| 7680x2160          | 1         | 0.74%   |
| 2560x1080          | 1         | 0.74%   |
| 2048x1152          | 1         | 0.74%   |
| 1680x1050 (WSXGA+) | 1         | 0.74%   |
| 1440x900 (WXGA+)   | 1         | 0.74%   |
| 1280x800 (WXGA)    | 1         | 0.74%   |
| 1280x720 (HD)      | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 20.92%  |
| 24      | 20        | 13.07%  |
| 27      | 16        | 10.46%  |
| 14      | 14        | 9.15%   |
| 13      | 14        | 9.15%   |
| 23      | 12        | 7.84%   |
| Unknown | 9         | 5.88%   |
| 21      | 8         | 5.23%   |
| 31      | 5         | 3.27%   |
| 12      | 5         | 3.27%   |
| 20      | 3         | 1.96%   |
| 47      | 2         | 1.31%   |
| 34      | 2         | 1.31%   |
| 17      | 2         | 1.31%   |
| 54      | 1         | 0.65%   |
| 49      | 1         | 0.65%   |
| 40      | 1         | 0.65%   |
| 39      | 1         | 0.65%   |
| 32      | 1         | 0.65%   |
| 25      | 1         | 0.65%   |
| 22      | 1         | 0.65%   |
| 19      | 1         | 0.65%   |
| 18      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 38.36%  |
| 501-600     | 39        | 26.71%  |
| 401-500     | 14        | 9.59%   |
| 201-300     | 9         | 6.16%   |
| Unknown     | 9         | 6.16%   |
| 601-700     | 8         | 5.48%   |
| 1001-1500   | 4         | 2.74%   |
| 701-800     | 3         | 2.05%   |
| 801-900     | 2         | 1.37%   |
| 351-400     | 2         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 101       | 83.47%  |
| 16/10   | 8         | 6.61%   |
| Unknown | 8         | 6.61%   |
| 21/9    | 2         | 1.65%   |
| 32/9    | 1         | 0.83%   |
| 3/2     | 1         | 0.83%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 32        | 21.05%  |
| 101-110        | 32        | 21.05%  |
| 81-90          | 24        | 15.79%  |
| 301-350        | 16        | 10.53%  |
| 251-300        | 9         | 5.92%   |
| Unknown        | 9         | 5.92%   |
| 351-500        | 8         | 5.26%   |
| 61-70          | 5         | 3.29%   |
| 501-1000       | 5         | 3.29%   |
| 71-80          | 4         | 2.63%   |
| 151-200        | 4         | 2.63%   |
| 121-130        | 2         | 1.32%   |
| More than 1000 | 1         | 0.66%   |
| 141-150        | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 38.1%   |
| 51-100        | 46        | 31.29%  |
| 101-120       | 23        | 15.65%  |
| Unknown       | 9         | 6.12%   |
| 161-240       | 8         | 5.44%   |
| 1-50          | 3         | 2.04%   |
| More than 240 | 2         | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 61.72%  |
| 2     | 32        | 25%     |
| 3     | 10        | 7.81%   |
| 0     | 7         | 5.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 93        | 51.38%  |
| Realtek Semiconductor             | 40        | 22.1%   |
| Lenovo                            | 11        | 6.08%   |
| Qualcomm Atheros                  | 8         | 4.42%   |
| Broadcom Limited                  | 4         | 2.21%   |
| Broadcom                          | 4         | 2.21%   |
| Ralink                            | 2         | 1.1%    |
| Marvell Technology Group          | 2         | 1.1%    |
| Dell                              | 2         | 1.1%    |
| Xiaomi                            | 1         | 0.55%   |
| Sierra Wireless                   | 1         | 0.55%   |
| Samsung Electronics               | 1         | 0.55%   |
| Ralink Technology                 | 1         | 0.55%   |
| Micro Star International          | 1         | 0.55%   |
| MediaTek                          | 1         | 0.55%   |
| Luminary Micro                    | 1         | 0.55%   |
| ICS Advent                        | 1         | 0.55%   |
| IBM                               | 1         | 0.55%   |
| Huawei Technologies               | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |
| DisplayLink                       | 1         | 0.55%   |
| D-Link                            | 1         | 0.55%   |
| ASIX Electronics                  | 1         | 0.55%   |
| Arduino SA                        | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 26        | 10.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 5.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 11        | 4.51%   |
| Intel Wireless 8265 / 8275                                                     | 10        | 4.1%    |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 3.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 3.69%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 3.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 8         | 3.28%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 6         | 2.46%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 2.46%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 2.46%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 6         | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 5         | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.64%   |
| Intel Wireless 8260                                                            | 4         | 1.64%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.64%   |
| Intel Wireless 7265                                                            | 3         | 1.23%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.23%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.23%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 1.23%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 0.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.82%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.82%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.82%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.82%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.82%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.41%   |
| Sierra Wireless MC7455 Qualcomm?‚ Snapdragon???„?? X7 LTE-A                    | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1         | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1         | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.41%   |
| Ralink RT5572 Wireless Adapter                                                 | 1         | 0.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.41%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]     | 1         | 0.41%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                             | 1         | 0.41%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.41%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.41%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.41%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 72.45%  |
| Realtek Semiconductor    | 9         | 9.18%   |
| Qualcomm Atheros         | 7         | 7.14%   |
| Ralink                   | 2         | 2.04%   |
| Broadcom                 | 2         | 2.04%   |
| Sierra Wireless          | 1         | 1.02%   |
| Ralink Technology        | 1         | 1.02%   |
| Micro Star International | 1         | 1.02%   |
| MediaTek                 | 1         | 1.02%   |
| Dell                     | 1         | 1.02%   |
| D-Link                   | 1         | 1.02%   |
| Broadcom Limited         | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 11        | 11.22%  |
| Intel Wireless 8265 / 8275                                                 | 10        | 10.2%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 9.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 8         | 8.16%   |
| Intel Wi-Fi 6 AX200                                                        | 6         | 6.12%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 6.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 5.1%    |
| Intel Wireless 8260                                                        | 4         | 4.08%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 4.08%   |
| Intel Wireless 7265                                                        | 3         | 3.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 2.04%   |
| Intel Wireless-AC 9260                                                     | 2         | 2.04%   |
| Sierra Wireless MC7455 Qualcomm?‚ Snapdragon???„?? X7 LTE-A                | 1         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 1.02%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.02%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 1.02%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 1.02%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 1.02%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 1.02%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 1.02%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 1.02%   |
| Intel Wireless 7260                                                        | 1         | 1.02%   |
| Intel Wireless 3165                                                        | 1         | 1.02%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 1.02%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                       | 1         | 1.02%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 1.02%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 1         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 53.79%  |
| Realtek Semiconductor    | 34        | 25.76%  |
| Lenovo                   | 11        | 8.33%   |
| Broadcom Limited         | 3         | 2.27%   |
| Qualcomm Atheros         | 2         | 1.52%   |
| Marvell Technology Group | 2         | 1.52%   |
| Broadcom                 | 2         | 1.52%   |
| Xiaomi                   | 1         | 0.76%   |
| Samsung Electronics      | 1         | 0.76%   |
| ICS Advent               | 1         | 0.76%   |
| IBM                      | 1         | 0.76%   |
| Huawei Technologies      | 1         | 0.76%   |
| DisplayLink              | 1         | 0.76%   |
| ASIX Electronics         | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 26        | 18.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 9.15%   |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 6.34%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 5.63%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 6         | 4.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 4.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.82%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.11%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 2.11%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 2.11%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 2.11%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 2.11%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.41%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.41%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.41%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 1.41%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.7%    |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.7%    |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.7%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.7%    |
| Intel I350 Gigabit Network Connection                                          | 1         | 0.7%    |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.7%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.7%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.7%    |
| Intel Ethernet Connection (2) I218-LM                                          | 1         | 0.7%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.7%    |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.7%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.7%    |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 0.7%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.7%    |
| IBM RNDIS/CDC ETHER                                                            | 1         | 0.7%    |
| Huawei E353/E3131                                                              | 1         | 0.7%    |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 0.7%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 0.7%    |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                         | 1         | 0.7%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.7%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 0.7%    |
| ASIX AX88772A Fast Ethernet                                                    | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 52.86%  |
| WiFi     | 95        | 45.24%  |
| Modem    | 3         | 1.43%   |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 101       | 53.72%  |
| WiFi     | 86        | 45.74%  |
| Unknown  | 1         | 0.53%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 63.33%  |
| 1     | 33        | 27.5%   |
| 3     | 7         | 5.83%   |
| 132   | 1         | 0.83%   |
| 22    | 1         | 0.83%   |
| 8     | 1         | 0.83%   |
| 6     | 1         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 92.56%  |
| Yes  | 9         | 7.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 69.74%  |
| Cambridge Silicon Radio         | 6         | 7.89%   |
| Broadcom                        | 5         | 6.58%   |
| Qualcomm Atheros Communications | 3         | 3.95%   |
| IMC Networks                    | 3         | 3.95%   |
| Realtek Semiconductor           | 2         | 2.63%   |
| Ralink                          | 1         | 1.32%   |
| Micro Star International        | 1         | 1.32%   |
| Foxconn / Hon Hai               | 1         | 1.32%   |
| Dell                            | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 32        | 42.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 23.68%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 7.89%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.95%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.63%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.63%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.32%   |
| Micro Star International Bluetooth Device                                           | 1         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.32%   |
| Intel Bluetooth wireless interface                                                  | 1         | 1.32%   |
| IMC Networks BCM20702A0                                                             | 1         | 1.32%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.32%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.32%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 101       | 53.16%  |
| Nvidia                 | 36        | 18.95%  |
| AMD                    | 14        | 7.37%   |
| Lenovo                 | 12        | 6.32%   |
| Plantronics            | 3         | 1.58%   |
| JMTek                  | 3         | 1.58%   |
| Generalplus Technology | 3         | 1.58%   |
| Creative Labs          | 3         | 1.58%   |
| Texas Instruments      | 2         | 1.05%   |
| Realtek Semiconductor  | 2         | 1.05%   |
| Logitech               | 2         | 1.05%   |
| Creative Technology    | 2         | 1.05%   |
| Tenx Technology        | 1         | 0.53%   |
| RODE Microphones       | 1         | 0.53%   |
| GN Netcom              | 1         | 0.53%   |
| Focusrite-Novation     | 1         | 0.53%   |
| DYNEX                  | 1         | 0.53%   |
| Dell                   | 1         | 0.53%   |
| ASUSTek Computer       | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH cAVS                                                 | 17        | 8.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 7.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 5.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 3.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.9%    |
| Intel Comet Lake PCH cAVS                                                  | 7         | 3.41%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 7         | 3.41%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 6         | 2.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.44%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.95%   |
| Plantronics BT600                                                          | 3         | 1.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.46%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3         | 1.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.46%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.46%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 0.98%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.98%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.98%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.98%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.49%   |
| RODE Microphones RODE NT-USB                                               | 1         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 0.49%   |
| Logitech H570e Mono                                                        | 1         | 0.49%   |
| Logitech H555 Headset                                                      | 1         | 0.49%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.49%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.49%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 0.49%   |
| JMTek USB Speaker                                                          | 1         | 0.49%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.49%   |
| JMTek iTalk-02                                                             | 1         | 0.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.49%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 0.49%   |
| GN Netcom Jabra EVOLVE 20 MS                                               | 1         | 0.49%   |
| Generalplus Technology USB Microphone                                      | 1         | 0.49%   |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 1         | 0.49%   |
| DYNEX USB MIC Device                                                       | 1         | 0.49%   |
| Dell AC511 Sound Bar                                                       | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 33.33%  |
| SK Hynix            | 10        | 20.83%  |
| Crucial             | 5         | 10.42%  |
| Kingston            | 4         | 8.33%   |
| Micron Technology   | 3         | 6.25%   |
| Corsair             | 3         | 6.25%   |
| Unknown             | 2         | 4.17%   |
| Unknown (0x0205)    | 1         | 2.08%   |
| Transcend           | 1         | 2.08%   |
| Patriot             | 1         | 2.08%   |
| Hewlett-Packard     | 1         | 2.08%   |
| GOODRAM             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s         | 2         | 3.85%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 1.92%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s           | 1         | 1.92%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s             | 1         | 1.92%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.92%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.92%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s      | 1         | 1.92%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.92%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.92%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 1.92%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.92%   |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 1         | 1.92%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s         | 1         | 1.92%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 1.92%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 1.92%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                    | 1         | 1.92%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 1.92%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                   | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 1.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.92%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.92%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.92%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 1         | 1.92%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1         | 1.92%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s          | 1         | 1.92%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.92%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s          | 1         | 1.92%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 1.92%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 1.92%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s         | 1         | 1.92%   |
| Kingston RAM KHX2666C13/16GX 16384MB DIMM DDR4 3200MT/s      | 1         | 1.92%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 1.92%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 1.92%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s      | 1         | 1.92%   |
| HP RAM 809082-091 16384MB DIMM DDR4 2400MT/s                 | 1         | 1.92%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s     | 1         | 1.92%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s         | 1         | 1.92%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s     | 1         | 1.92%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.92%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s    | 1         | 1.92%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4096MB DIMM DDR4 2400MT/s     | 1         | 1.92%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s     | 1         | 1.92%   |
| Corsair RAM CMSX32GX4M2A2666C18 16384MB SODIMM DDR4 2667MT/s | 1         | 1.92%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 59.46%  |
| DDR3   | 12        | 32.43%  |
| SDRAM  | 1         | 2.7%    |
| LPDDR4 | 1         | 2.7%    |
| LPDDR3 | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 19        | 52.78%  |
| SODIMM       | 16        | 44.44%  |
| Row Of Chips | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 14        | 35%     |
| 16384 | 10        | 25%     |
| 8192  | 10        | 25%     |
| 32768 | 4         | 10%     |
| 65536 | 1         | 2.5%    |
| 2048  | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 24.39%  |
| 1600  | 9         | 21.95%  |
| 2400  | 7         | 17.07%  |
| 3200  | 4         | 9.76%   |
| 1333  | 4         | 9.76%   |
| 2133  | 3         | 7.32%   |
| 3600  | 1         | 2.44%   |
| 2933  | 1         | 2.44%   |
| 2666  | 1         | 2.44%   |
| 1334  | 1         | 2.44%   |

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


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w | 1         | 16.67%  |
| HP ENVY 4500 series              | 1         | 16.67%  |
| HP DeskJet 2600 series           | 1         | 16.67%  |
| Canon LiDE 300                   | 1         | 16.67%  |
| Canon E560 series                | 1         | 16.67%  |
| Brother DCP-1610W                | 1         | 16.67%  |

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
| Chicony Electronics                    | 25        | 29.41%  |
| IMC Networks                           | 10        | 11.76%  |
| Acer                                   | 8         | 9.41%   |
| Logitech                               | 7         | 8.24%   |
| Sunplus Innovation Technology          | 6         | 7.06%   |
| Realtek Semiconductor                  | 6         | 7.06%   |
| Microdia                               | 6         | 7.06%   |
| Unknown                                | 3         | 3.53%   |
| Suyin                                  | 3         | 3.53%   |
| Lite-On Technology                     | 3         | 3.53%   |
| Samsung Electronics                    | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.35%   |
| Quanta                                 | 1         | 1.18%   |
| Lenovo                                 | 1         | 1.18%   |
| Jieli Technology                       | 1         | 1.18%   |
| ARC International                      | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 13        | 15.12%  |
| IMC Networks Integrated Camera                               | 8         | 9.3%    |
| Acer Integrated Camera                                       | 6         | 6.98%   |
| Realtek Integrated_Webcam_HD                                 | 5         | 5.81%   |
| Logitech HD Pro Webcam C920                                  | 4         | 4.65%   |
| Unknown FULL HD 1080P Webcam                                 | 3         | 3.49%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 3.49%   |
| Lite-On Integrated Camera                                    | 3         | 3.49%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 3.49%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 2.33%   |
| Microdia Webcam                                              | 2         | 2.33%   |
| Microdia Integrated Webcam                                   | 2         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 2.33%   |
| Chicony ThinkPad T490 Webcam                                 | 2         | 2.33%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 2.33%   |
| Chicony HP HD Camera                                         | 2         | 2.33%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 1.16%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 1.16%   |
| Suyin HP Truevision HD                                       | 1         | 1.16%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.16%   |
| Sunplus Integrated Webcam                                    | 1         | 1.16%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 1.16%   |
| Realtek NexiGo N660P FHD Webcam                              | 1         | 1.16%   |
| Quanta HP HD Camera                                          | 1         | 1.16%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 1.16%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 1.16%   |
| Logitech Webcam C310                                         | 1         | 1.16%   |
| Logitech Webcam C270                                         | 1         | 1.16%   |
| Logitech HD Webcam C910                                      | 1         | 1.16%   |
| Lenovo Integrated Webcam                                     | 1         | 1.16%   |
| Jieli USB PHY 2.0                                            | 1         | 1.16%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.16%   |
| Chicony Integrated IR Camera                                 | 1         | 1.16%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.16%   |
| Chicony HP Webcam                                            | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 1.16%   |
| ARC International Camera                                     | 1         | 1.16%   |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 1.16%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 56.25%  |
| Validity Sensors           | 10        | 31.25%  |
| Upek                       | 2         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 3.13%   |
| Elan Microelectronics      | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 43.75%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 9.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.13%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 41.67%  |
| Alcor Micro           | 3         | 25%     |
| Lenovo                | 2         | 16.67%  |
| Upek                  | 1         | 8.33%   |
| Gemalto (was Gemplus) | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 25%     |
| Lenovo Integrated Smart Card Reader                        | 2         | 16.67%  |
| Broadcom 5880                                              | 2         | 16.67%  |
| Broadcom 58200                                             | 2         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 8.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 63        | 52.94%  |
| 1     | 45        | 37.82%  |
| 2     | 9         | 7.56%   |
| 3     | 2         | 1.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 46.38%  |
| Chipcard                 | 9         | 13.04%  |
| Graphics card            | 8         | 11.59%  |
| Unassigned class         | 5         | 7.25%   |
| Net/wireless             | 4         | 5.8%    |
| Net/ethernet             | 2         | 2.9%    |
| Multimedia controller    | 2         | 2.9%    |
| Communication controller | 2         | 2.9%    |
| Bluetooth                | 2         | 2.9%    |
| Storage/ide              | 1         | 1.45%   |
| Storage                  | 1         | 1.45%   |
| Network                  | 1         | 1.45%   |

