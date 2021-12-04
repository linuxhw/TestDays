RHEL 8 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [cd6c668ae9](https://linux-hardware.org/?probe=cd6c668ae9) | Nov 29, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP      | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo  | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ab905debb9](https://linux-hardware.org/?probe=ab905debb9) | Nov 17, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo  | ThinkPad P50 20ENS1L000     | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo  | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo  | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| HP      | ZBook Firefly 15 inch G8... | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| Lenovo  | ThinkPad P50 20ENS1L000     | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K90... | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| Lenovo  | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo  | ThinkPad X230 Tablet 343... | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell    | XPS 15 9560                 | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell    | XPS 15 9560                 | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| HP      | ZBook 15 G5                 | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Dell    | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP      | EliteBook 850 G7 Noteboo... | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell    | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell    | Latitude E6430              | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell    | Latitude E6430              | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo  | ThinkPad P15 Gen 1 20SUS... | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Dell    | Precision 3541              | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP      | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP      | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell    | Latitude E6530              | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [779849778e](https://linux-hardware.org/?probe=779849778e) | May 26, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell    | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP      | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [bb1cb9b30a](https://linux-hardware.org/?probe=bb1cb9b30a) | Apr 02, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [433f10b16b](https://linux-hardware.org/?probe=433f10b16b) | Mar 16, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo  | ThinkPad T460 20FMS1VA09    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo  | ThinkPad T460 20FMS1VA09    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo  | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek | Zephyrus G GU502DU_GA502... | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| Sony    | VPCEB4L1R                   | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP      | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Lenovo  | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo  | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo  | ThinkPad L480 20LSCTO1WW    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo  | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| Lenovo  | ThinkPad T480s 20L8S2N80... | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [e3d128beda](https://linux-hardware.org/?probe=e3d128beda) | Dec 28, 2020 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell    | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell    | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP      | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo  | ThinkpadT460 20BUS0QT0A     | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| Dell    | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO  | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell    | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell    | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell    | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO  | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO  | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell    | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP      | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell    | Precision 7510              | [9d901b2f8e](https://linux-hardware.org/?probe=9d901b2f8e) | Nov 01, 2020 |
| Dell    | Precision 7510              | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo  | ThinkPad T520 42404CG       | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo  | ThinkPad T520 42404CG       | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo  | ThinkPad T14s Gen 1 20UJ... | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell    | Latitude 5300               | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell    | Latitude 5300               | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP      | Pavilion 14                 | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo  | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo  | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| Lenovo  | ThinkPad P50 20EN0005UK     | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| Dell    | Inspiron 5567               | [a9d66d8f86](https://linux-hardware.org/?probe=a9d66d8f86) | Sep 15, 2020 |
| HP      | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell    | Inspiron N5110              | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell    | Inspiron N5110              | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| ASUSTek | GL502VMK                    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| Dell    | Latitude 5300               | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi    | TM1707                      | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi    | TM1707                      | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek | GL502VMK                    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell    | Latitude 5300               | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| HP      | ProBook 430 G5              | [20760711e1](https://linux-hardware.org/?probe=20760711e1) | May 24, 2020 |
| HP      | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP      | ProBook 430 G5              | [53ccb8b4bf](https://linux-hardware.org/?probe=53ccb8b4bf) | May 23, 2020 |
| HP      | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell    | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell    | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Dell    | Inspiron 5567               | [6cc6232ddf](https://linux-hardware.org/?probe=6cc6232ddf) | Apr 14, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony    | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony    | VPCEB23FM                   | [4cde30cfa5](https://linux-hardware.org/?probe=4cde30cfa5) | Feb 26, 2020 |
| Sony    | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo  | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [73b2494a42](https://linux-hardware.org/?probe=73b2494a42) | Jan 22, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [92086a7925](https://linux-hardware.org/?probe=92086a7925) | Jan 14, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [c24f015f0f](https://linux-hardware.org/?probe=c24f015f0f) | Jan 13, 2020 |
| Lenovo  | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell    | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP      | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP      | 250 G4 Notebook PC          | [e5994eed73](https://linux-hardware.org/?probe=e5994eed73) | Nov 07, 2019 |
| HP      | 250 G4 Notebook PC          | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo  | ThinkPad X1 Carbon 6th 2... | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo  | ThinkPad T480s 20L8S2N80... | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 9.71%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 9         | 8.74%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 7.77%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 7.77%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 6.8%    |
| 4.18.0-193.19.1.el8_2.x86_64 | 5         | 4.85%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 3.88%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 3.88%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.91%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 3         | 2.91%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 3         | 2.91%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.91%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 2.91%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.91%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.91%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.91%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 2.91%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.91%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.94%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.94%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.97%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.97%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.97%   |
| 4.18.0-348.el8.x86_64        | 1         | 0.97%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 0.97%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1         | 0.97%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 0.97%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.97%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.97%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.97%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.97%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 1         | 0.97%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 0.97%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 82        | 98.8%   |
| 5.9.1   | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 82        | 98.8%   |
| 5.9     | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 83        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 73        | 84.88%  |
| Unknown       | 7         | 8.14%   |
| GNOME Classic | 5         | 5.81%   |
| KDE5          | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 59.77%  |
| Wayland | 31        | 35.63%  |
| Unknown | 4         | 4.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 88.37%  |
| GDM     | 10        | 11.63%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 58        | 68.24%  |
| Unknown | 7         | 8.24%   |
| fr_FR   | 3         | 3.53%   |
| en_GB   | 3         | 3.53%   |
| pl_PL   | 2         | 2.35%   |
| nl_NL   | 2         | 2.35%   |
| en_IN   | 2         | 2.35%   |
| ru_RU   | 1         | 1.18%   |
| pt_BR   | 1         | 1.18%   |
| ja_JP   | 1         | 1.18%   |
| it_IT   | 1         | 1.18%   |
| es_EC   | 1         | 1.18%   |
| en_IE   | 1         | 1.18%   |
| de_DE   | 1         | 1.18%   |
| de_CH   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 67        | 78.82%  |
| BIOS | 18        | 21.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 75        | 90.36%  |
| Ext4 | 8         | 9.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 87.06%  |
| GPT     | 11        | 12.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 98.8%   |
| Yes       | 1         | 1.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 94.05%  |
| Yes       | 5         | 5.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 51        | 61.45%  |
| Dell             | 16        | 19.28%  |
| Hewlett-Packard  | 9         | 10.84%  |
| ASUSTek Computer | 3         | 3.61%   |
| Sony             | 2         | 2.41%   |
| TUXEDO           | 1         | 1.2%    |
| Timi             | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 3         | 3.61%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 2.41%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 2.41%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 2.41%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 2.41%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 2.41%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 2.41%   |
| Dell Latitude E6430                      | 2         | 2.41%   |
| Dell Latitude 5300                       | 2         | 2.41%   |
| TUXEDO N13xWU                            | 1         | 1.2%    |
| Timi TM1707                              | 1         | 1.2%    |
| Sony VPCEB4L1R                           | 1         | 1.2%    |
| Sony VPCEB23FM                           | 1         | 1.2%    |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 1.2%    |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 1.2%    |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 1.2%    |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 1.2%    |
| Lenovo ThinkPad X201 3680PKS             | 1         | 1.2%    |
| Lenovo ThinkPad W530 2441B32             | 1         | 1.2%    |
| Lenovo ThinkPad W520 4284GN2             | 1         | 1.2%    |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 1.2%    |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 1.2%    |
| Lenovo ThinkPad T520 42404CG             | 1         | 1.2%    |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 1.2%    |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 1.2%    |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 1.2%    |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 1.2%    |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 1.2%    |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 1.2%    |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 1.2%    |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 1.2%    |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 1.2%    |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 1.2%    |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 1.2%    |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 1.2%    |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 1.2%    |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 1.2%    |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 1.2%    |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 1.2%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 1.2%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 1.2%    |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 1.2%    |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 1.2%    |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 1.2%    |
| Lenovo ThinkPad E490 20N8000JAD          | 1         | 1.2%    |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 1.2%    |
| HP ZBook Studio G5                       | 1         | 1.2%    |
| HP ZBook 15 G5                           | 1         | 1.2%    |
| HP ProBook 430 G5                        | 1         | 1.2%    |
| HP Pavilion 14                           | 1         | 1.2%    |
| HP OMEN by Laptop 15-dc1xxx              | 1         | 1.2%    |
| HP EliteBook 850 G7 Notebook PC          | 1         | 1.2%    |
| HP EliteBook 8460p                       | 1         | 1.2%    |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.2%    |
| HP 250 G4 Notebook PC                    | 1         | 1.2%    |
| Dell XPS 15 9560                         | 1         | 1.2%    |
| Dell Precision 7510                      | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 50        | 60.24%  |
| Dell Latitude       | 8         | 9.64%   |
| HP EliteBook        | 3         | 3.61%   |
| Dell Precision      | 3         | 3.61%   |
| Dell Inspiron       | 3         | 3.61%   |
| HP ZBook            | 2         | 2.41%   |
| TUXEDO N13xWU       | 1         | 1.2%    |
| Timi TM1707         | 1         | 1.2%    |
| Sony VPCEB4L1R      | 1         | 1.2%    |
| Sony VPCEB23FM      | 1         | 1.2%    |
| Lenovo ThinkpadT460 | 1         | 1.2%    |
| HP ProBook          | 1         | 1.2%    |
| HP Pavilion         | 1         | 1.2%    |
| HP OMEN             | 1         | 1.2%    |
| HP 250              | 1         | 1.2%    |
| Dell XPS            | 1         | 1.2%    |
| Dell G3             | 1         | 1.2%    |
| ASUS Zephyrus       | 1         | 1.2%    |
| ASUS TUF            | 1         | 1.2%    |
| ASUS GL502VMK       | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 31        | 37.35%  |
| 2019 | 20        | 24.1%   |
| 2018 | 11        | 13.25%  |
| 2021 | 10        | 12.05%  |
| 2017 | 3         | 3.61%   |
| 2011 | 3         | 3.61%   |
| 2010 | 2         | 2.41%   |
| 2016 | 1         | 1.2%    |
| 2014 | 1         | 1.2%    |
| 2012 | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 73        | 86.9%   |
| Enabled  | 11        | 13.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 31        | 36.05%  |
| 4.01-8.0    | 15        | 17.44%  |
| 8.01-16.0   | 15        | 17.44%  |
| 16.01-24.0  | 13        | 15.12%  |
| 64.01-256.0 | 6         | 6.98%   |
| 3.01-4.0    | 5         | 5.81%   |
| 24.01-32.0  | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 41        | 42.71%  |
| 8.01-16.0  | 18        | 18.75%  |
| 3.01-4.0   | 15        | 15.63%  |
| 2.01-3.0   | 11        | 11.46%  |
| 1.01-2.0   | 8         | 8.33%   |
| 16.01-24.0 | 2         | 2.08%   |
| 24.01-32.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 74.42%  |
| 2      | 13        | 15.12%  |
| 3      | 8         | 9.3%    |
| 4      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 88.1%   |
| Yes       | 10        | 11.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 89.29%  |
| No        | 9         | 10.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 98.8%   |
| No        | 1         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 76.14%  |
| No        | 21        | 23.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 19        | 22.62%  |
| India        | 13        | 15.48%  |
| UK           | 5         | 5.95%   |
| Germany      | 5         | 5.95%   |
| France       | 4         | 4.76%   |
| Netherlands  | 3         | 3.57%   |
| Switzerland  | 2         | 2.38%   |
| South Africa | 2         | 2.38%   |
| Mexico       | 2         | 2.38%   |
| Japan        | 2         | 2.38%   |
| Czechia      | 2         | 2.38%   |
| Canada       | 2         | 2.38%   |
| Australia    | 2         | 2.38%   |
| Spain        | 1         | 1.19%   |
| Singapore    | 1         | 1.19%   |
| Saudi Arabia | 1         | 1.19%   |
| Russia       | 1         | 1.19%   |
| Romania      | 1         | 1.19%   |
| Portugal     | 1         | 1.19%   |
| Poland       | 1         | 1.19%   |
| Pakistan     | 1         | 1.19%   |
| Nepal        | 1         | 1.19%   |
| Myanmar      | 1         | 1.19%   |
| Morocco      | 1         | 1.19%   |
| Lithuania    | 1         | 1.19%   |
| Kuwait       | 1         | 1.19%   |
| Italy        | 1         | 1.19%   |
| Ireland      | 1         | 1.19%   |
| Ecuador      | 1         | 1.19%   |
| Colombia     | 1         | 1.19%   |
| Bulgaria     | 1         | 1.19%   |
| Brazil       | 1         | 1.19%   |
| Armenia      | 1         | 1.19%   |
| Argentina    | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Munich                   | 3         | 3.23%   |
| Mumbai                   | 2         | 2.15%   |
| Mexico City              | 2         | 2.15%   |
| Doetinchem               | 2         | 2.15%   |
| Yerevan                  | 1         | 1.08%   |
| Webster                  | 1         | 1.08%   |
| Taringa                  | 1         | 1.08%   |
| Sumida                   | 1         | 1.08%   |
| Stroud                   | 1         | 1.08%   |
| Sofia                    | 1         | 1.08%   |
| Singapore                | 1         | 1.08%   |
| Sheffield                | 1         | 1.08%   |
| San Francisco            | 1         | 1.08%   |
| Sammamish                | 1         | 1.08%   |
| Sal?©                    | 1         | 1.08%   |
| Saint-Ismier             | 1         | 1.08%   |
| Saint-Alphonse-Rodriguez | 1         | 1.08%   |
| Sagaing                  | 1         | 1.08%   |
| Roudnice nad Labem       | 1         | 1.08%   |
| Roha                     | 1         | 1.08%   |
| Reims                    | 1         | 1.08%   |
| Raleigh                  | 1         | 1.08%   |
| Quito                    | 1         | 1.08%   |
| Queenscliff              | 1         | 1.08%   |
| Queens                   | 1         | 1.08%   |
| Pune                     | 1         | 1.08%   |
| Prague                   | 1         | 1.08%   |
| Portalegre               | 1         | 1.08%   |
| Port Elizabeth           | 1         | 1.08%   |
| Pleasanton               | 1         | 1.08%   |
| Pickerington             | 1         | 1.08%   |
| Paraiso do Tocantins     | 1         | 1.08%   |
| Paragould                | 1         | 1.08%   |
| Oyama                    | 1         | 1.08%   |
| Ottawa                   | 1         | 1.08%   |
| Ommen                    | 1         | 1.08%   |
| Ogden                    | 1         | 1.08%   |
| New Delhi                | 1         | 1.08%   |
| Neuves-Maisons           | 1         | 1.08%   |
| Moscow                   | 1         | 1.08%   |
| Miroslava                | 1         | 1.08%   |
| Milan                    | 1         | 1.08%   |
| Mangalore                | 1         | 1.08%   |
| Madrid                   | 1         | 1.08%   |
| London                   | 1         | 1.08%   |
| Littleton                | 1         | 1.08%   |
| Lahore                   | 1         | 1.08%   |
| Kuwait City              | 1         | 1.08%   |
| Kochi                    | 1         | 1.08%   |
| Khobar                   | 1         | 1.08%   |
| Johnstone                | 1         | 1.08%   |
| Islamabad                | 1         | 1.08%   |
| Impflingen               | 1         | 1.08%   |
| Hyderabad                | 1         | 1.08%   |
| Houston                  | 1         | 1.08%   |
| Hosur                    | 1         | 1.08%   |
| Hobart                   | 1         | 1.08%   |
| Hetauda                  | 1         | 1.08%   |
| Gurgaon                  | 1         | 1.08%   |
| Grosseto                 | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 38     | 26.17%  |
| WDC                 | 13        | 19     | 12.15%  |
| Toshiba             | 10        | 15     | 9.35%   |
| Sandisk             | 10        | 15     | 9.35%   |
| SK Hynix            | 9         | 9      | 8.41%   |
| Seagate             | 9         | 12     | 8.41%   |
| Unknown             | 5         | 7      | 4.67%   |
| Intel               | 5         | 7      | 4.67%   |
| Micron Technology   | 4         | 6      | 3.74%   |
| Kingston            | 3         | 3      | 2.8%    |
| Lenovo              | 2         | 2      | 1.87%   |
| HGST                | 2         | 2      | 1.87%   |
| Team                | 1         | 2      | 0.93%   |
| SMI                 | 1         | 2      | 0.93%   |
| Silicon Motion      | 1         | 2      | 0.93%   |
| PNY                 | 1         | 4      | 0.93%   |
| Lite-On             | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 8         | 6.84%   |
| Sandisk NVMe SSD Drive 256GB            | 6         | 5.13%   |
| Samsung NVMe SSD Drive 256GB            | 5         | 4.27%   |
| Samsung NVMe SSD Drive 1024GB           | 5         | 4.27%   |
| Samsung NVMe SSD Drive 512GB            | 4         | 3.42%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 2.56%   |
| Micron NVMe SSD Drive 256GB             | 3         | 2.56%   |
| Unknown NVMe SSD Drive 256GB            | 2         | 1.71%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 1.71%   |
| Seagate Expansion 1TB                   | 2         | 1.71%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 1.71%   |
| Samsung Portable SSD T5 500GB           | 2         | 1.71%   |
| Samsung NVMe SSD Drive 2TB              | 2         | 1.71%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.71%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.71%   |
| Intel NVMe SSD Drive 2TB                | 2         | 1.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.85%   |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.85%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.85%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.85%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.85%   |
| WDC WD20 SPZX-11UA7T0 2TB               | 1         | 0.85%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.85%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.85%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.85%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.85%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.85%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.85%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.85%   |
| Unknown MMC Card  33GB                  | 1         | 0.85%   |
| Unknown MMC Card  32GB                  | 1         | 0.85%   |
| Unknown MMC Card  16GB                  | 1         | 0.85%   |
| Toshiba TR150 960GB SSD                 | 1         | 0.85%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.85%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.85%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.85%   |
| Toshiba HDWL110 1TB                     | 1         | 0.85%   |
| Team T253X2512G 512GB SSD               | 1         | 0.85%   |
| SMI DISK 506GB                          | 1         | 0.85%   |
| SK Hynix NVMe SSD Drive 1024GB          | 1         | 0.85%   |
| Silicon Motion NVMe SSD Drive 1TB       | 1         | 0.85%   |
| Seagate ST9160827AS 160GB               | 1         | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.85%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.85%   |
| Seagate BUP Slim BK 1TB                 | 1         | 0.85%   |
| Seagate BUP Portable 4TB                | 1         | 0.85%   |
| Seagate BUP BL 4TB                      | 1         | 0.85%   |
| Seagate BarraCuda SSD ZA2000CM10002 2TB | 1         | 0.85%   |
| SanDisk SDSSDH31024G 1024GB             | 1         | 0.85%   |
| SanDisk SD7SN6S-256G-1006 256GB SSD     | 1         | 0.85%   |
| SanDisk SD7SB7S512G1001 512GB SSD       | 1         | 0.85%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 0.85%   |
| SanDisk Extreme SSD 1TB                 | 1         | 0.85%   |
| Samsung SSD PM830 2.5 7mm 256GB         | 1         | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 0.85%   |
| Samsung SSD 860 QVO 1TB                 | 1         | 0.85%   |
| Samsung SSD 860 EVO M.2 500GB           | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 11     | 42.86%  |
| WDC     | 7         | 11     | 33.33%  |
| Toshiba | 3         | 5      | 14.29%  |
| HGST    | 2         | 2      | 9.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 40.74%  |
| WDC                 | 3         | 4      | 11.11%  |
| SanDisk             | 3         | 4      | 11.11%  |
| Kingston            | 3         | 3      | 11.11%  |
| Toshiba             | 1         | 1      | 3.7%    |
| Team                | 1         | 2      | 3.7%    |
| Seagate             | 1         | 1      | 3.7%    |
| PNY                 | 1         | 4      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Corsair             | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 56        | 79     | 52.83%  |
| SSD     | 25        | 34     | 23.58%  |
| HDD     | 21        | 29     | 19.81%  |
| MMC     | 3         | 4      | 2.83%   |
| Unknown | 1         | 2      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 56        | 79     | 55.45%  |
| SATA | 34        | 56     | 33.66%  |
| SAS  | 8         | 9      | 7.92%   |
| MMC  | 3         | 4      | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 27     | 45.45%  |
| 0.51-1.0   | 16        | 27     | 36.36%  |
| 1.01-2.0   | 5         | 6      | 11.36%  |
| 3.01-4.0   | 3         | 3      | 6.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 47.06%  |
| 251-500        | 14        | 16.47%  |
| 501-1000       | 12        | 14.12%  |
| 1001-2000      | 6         | 7.06%   |
| More than 3000 | 5         | 5.88%   |
| 51-100         | 3         | 3.53%   |
| 21-50          | 2         | 2.35%   |
| 2001-3000      | 1         | 1.18%   |
| 1-20           | 1         | 1.18%   |
| Unknown        | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 23        | 24.73%  |
| 101-250        | 22        | 23.66%  |
| 1-20           | 17        | 18.28%  |
| 51-100         | 14        | 15.05%  |
| 251-500        | 8         | 8.6%    |
| 501-1000       | 5         | 5.38%   |
| More than 3000 | 1         | 1.08%   |
| 2001-3000      | 1         | 1.08%   |
| 1001-2000      | 1         | 1.08%   |
| Unknown        | 1         | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 76        | 132    | 86.36%  |
| Works    | 12        | 16     | 13.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 43        | 44.33%  |
| Samsung Electronics          | 19        | 19.59%  |
| Sandisk                      | 10        | 10.31%  |
| SK Hynix                     | 9         | 9.28%   |
| Toshiba America Info Systems | 6         | 6.19%   |
| Micron Technology            | 3         | 3.09%   |
| Lenovo                       | 2         | 2.06%   |
| KIOXIA                       | 2         | 2.06%   |
| Silicon Motion               | 1         | 1.03%   |
| Lite-On Technology           | 1         | 1.03%   |
| AMD                          | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 15        | 15.15%  |
| SK Hynix Non-Volatile memory controller                                       | 9         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 8         | 8.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 7         | 7.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 6.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 5         | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.05%   |
| Micron Non-Volatile memory controller                                         | 3         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 3.03%   |
| Intel SSD 660P Series                                                         | 3         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 3.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 2.02%   |
| Lenovo Non-Volatile memory controller                                         | 2         | 2.02%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 2.02%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 2         | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 2.02%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 1.01%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 1.01%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.01%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 1.01%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 1.01%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 56        | 57.73%  |
| SATA | 37        | 38.14%  |
| RAID | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 95.18%  |
| AMD    | 4         | 4.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 10.84%  |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 8.43%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 5         | 6.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 4.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 3.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 3.61%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 2.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.41%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.41%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 2.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 2.41%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 2.41%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.41%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 2.41%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 1.2%    |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 1.2%    |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 1.2%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 1.2%    |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 1.2%    |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.2%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.2%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.2%    |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 1.2%    |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.2%    |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.2%    |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 1.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.2%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.2%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 48        | 57.83%  |
| Intel Core i5   | 21        | 25.3%   |
| Intel Xeon      | 4         | 4.82%   |
| AMD Ryzen 7     | 3         | 3.61%   |
| Other           | 2         | 2.41%   |
| Intel Core i9   | 2         | 2.41%   |
| Intel Core i3   | 2         | 2.41%   |
| AMD Ryzen 7 PRO | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 40        | 48.19%  |
| 2      | 22        | 26.51%  |
| 6      | 16        | 19.28%  |
| 8      | 5         | 6.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 97.59%  |
| 1      | 2         | 2.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 95.29%  |
| Unknown        | 4         | 4.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 19        | 22.35%  |
| 0x806ea    | 10        | 11.76%  |
| 0xa0652    | 8         | 9.41%   |
| 0x906ea    | 6         | 7.06%   |
| 0x306a9    | 5         | 5.88%   |
| 0x206a7    | 5         | 5.88%   |
| 0x906ed    | 4         | 4.71%   |
| 0x806e9    | 3         | 3.53%   |
| 0x506e3    | 3         | 3.53%   |
| 0x406e3    | 3         | 3.53%   |
| 0x306d4    | 3         | 3.53%   |
| 0x20655    | 3         | 3.53%   |
| Unknown    | 3         | 3.53%   |
| 0x906e9    | 2         | 2.35%   |
| 0x08108102 | 2         | 2.35%   |
| 0x806d1    | 1         | 1.18%   |
| 0x806c1    | 1         | 1.18%   |
| 0x40651    | 1         | 1.18%   |
| 0x20652    | 1         | 1.18%   |
| 0x08600104 | 1         | 1.18%   |
| 0x08600103 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 45        | 54.22%  |
| CometLake   | 8         | 9.64%   |
| Skylake     | 6         | 7.23%   |
| SandyBridge | 5         | 6.02%   |
| IvyBridge   | 5         | 6.02%   |
| Westmere    | 4         | 4.82%   |
| Broadwell   | 3         | 3.61%   |
| Zen+        | 2         | 2.41%   |
| Zen 2       | 2         | 2.41%   |
| TigerLake   | 1         | 1.2%    |
| Icelake     | 1         | 1.2%    |
| Haswell     | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 70        | 67.96%  |
| Nvidia | 23        | 22.33%  |
| AMD    | 10        | 9.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 13        | 12.62%  |
| Intel UHD Graphics 620                                                                | 10        | 9.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 6.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 6.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 5.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 4.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 3.88%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 2.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 2.91%   |
| Intel HD Graphics 620                                                                 | 3         | 2.91%   |
| Intel HD Graphics 5500                                                                | 3         | 2.91%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.94%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 2         | 1.94%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 1.94%   |
| AMD Renoir                                                                            | 2         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.94%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.97%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.97%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.97%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 0.97%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.97%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.97%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.97%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 0.97%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 0.97%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.97%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                                    | 1         | 0.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 0.97%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 0.97%   |
| Intel HD Graphics P530                                                                | 1         | 0.97%   |
| Intel HD Graphics 630                                                                 | 1         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.97%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 0.97%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 0.97%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 0.97%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 62.65%  |
| Intel + Nvidia | 14        | 16.87%  |
| 1 x Nvidia     | 7         | 8.43%   |
| Intel + AMD    | 4         | 4.82%   |
| 1 x AMD        | 4         | 4.82%   |
| AMD + Nvidia   | 2         | 2.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 73        | 86.9%   |
| Proprietary | 8         | 9.52%   |
| Unknown     | 3         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 72.29%  |
| 3.01-4.0   | 6         | 7.23%   |
| 1.01-2.0   | 6         | 7.23%   |
| 5.01-6.0   | 4         | 4.82%   |
| 0.51-1.0   | 4         | 4.82%   |
| 0.01-0.5   | 2         | 2.41%   |
| 7.01-8.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 13.33%  |
| Chimei Innolux          | 14        | 11.67%  |
| BOE                     | 14        | 11.67%  |
| LG Display              | 13        | 10.83%  |
| Dell                    | 12        | 10%     |
| Samsung Electronics     | 9         | 7.5%    |
| Lenovo                  | 9         | 7.5%    |
| Hewlett-Packard         | 5         | 4.17%   |
| Sharp                   | 4         | 3.33%   |
| InfoVision              | 4         | 3.33%   |
| Goldstar                | 4         | 3.33%   |
| Acer                    | 3         | 2.5%    |
| Philips                 | 2         | 1.67%   |
| PANDA                   | 2         | 1.67%   |
| LGD                     | 2         | 1.67%   |
| Sun                     | 1         | 0.83%   |
| Sceptre Tech            | 1         | 0.83%   |
| Planar                  | 1         | 0.83%   |
| Eizo                    | 1         | 0.83%   |
| Chi Mei Optoelectronics | 1         | 0.83%   |
| BOE Technology Group    | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 4.03%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 3.23%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 2.42%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 2.42%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 2.42%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 2.42%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.61%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.61%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.61%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.61%   |
| Hewlett-Packard 27y HPN351C 1920x1080 598x336mm 27.0-inch             | 2         | 1.61%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 2         | 1.61%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.61%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.61%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.81%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.81%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.81%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.81%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.81%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.81%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.81%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 698x393mm 31.5-inch    | 1         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.81%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.81%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.81%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 1         | 0.81%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.81%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 1         | 0.81%   |
| Hewlett-Packard Pavilion32 HWP3338 2560x1440 708x399mm 32.0-inch      | 1         | 0.81%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 0.81%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch             | 1         | 0.81%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 0.81%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 0.81%   |
| Goldstar LG ULTRAWIDE GSM59F2 1920x1080 800x340mm 34.2-inch           | 1         | 0.81%   |
| Eizo EV2416W ENC2389 1920x1200 519x324mm 24.1-inch                    | 1         | 0.81%   |
| Dell U4919DW DELA10F 3840x1080 1198x337mm 49.0-inch                   | 1         | 0.81%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 0.81%   |
| Dell SP2309W DELD01D 2048x1152 510x290mm 23.1-inch                    | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 57.43%  |
| 1366x768 (WXGA)    | 12        | 11.88%  |
| 3840x2160 (4K)     | 7         | 6.93%   |
| 1600x900 (HD+)     | 6         | 5.94%   |
| 2560x1440 (QHD)    | 5         | 4.95%   |
| 2560x1080          | 3         | 2.97%   |
| 1920x1200 (WUXGA)  | 3         | 2.97%   |
| 6400x2160          | 1         | 0.99%   |
| 3840x1080          | 1         | 0.99%   |
| 2048x1152          | 1         | 0.99%   |
| 1680x1050 (WSXGA+) | 1         | 0.99%   |
| 1440x900 (WXGA+)   | 1         | 0.99%   |
| 1280x800 (WXGA)    | 1         | 0.99%   |
| Unknown            | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 29.41%  |
| 14      | 19        | 15.97%  |
| 13      | 14        | 11.76%  |
| 24      | 13        | 10.92%  |
| 27      | 9         | 7.56%   |
| 23      | 6         | 5.04%   |
| 12      | 5         | 4.2%    |
| 34      | 3         | 2.52%   |
| 17      | 3         | 2.52%   |
| Unknown | 3         | 2.52%   |
| 31      | 2         | 1.68%   |
| 21      | 2         | 1.68%   |
| 49      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 22      | 1         | 0.84%   |
| 19      | 1         | 0.84%   |
| 18      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 56.03%  |
| 501-600     | 22        | 18.97%  |
| 201-300     | 8         | 6.9%    |
| 601-700     | 5         | 4.31%   |
| 401-500     | 5         | 4.31%   |
| 701-800     | 4         | 3.45%   |
| 351-400     | 3         | 2.59%   |
| Unknown     | 3         | 2.59%   |
| 1001-1500   | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 83.52%  |
| 16/10   | 7         | 7.69%   |
| 21/9    | 3         | 3.3%    |
| Unknown | 3         | 3.3%    |
| 32/9    | 1         | 1.1%    |
| 3/2     | 1         | 1.1%    |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 29.66%  |
| 81-90          | 30        | 25.42%  |
| 201-250        | 15        | 12.71%  |
| 301-350        | 9         | 7.63%   |
| 251-300        | 7         | 5.93%   |
| 61-70          | 5         | 4.24%   |
| 351-500        | 5         | 4.24%   |
| 71-80          | 3         | 2.54%   |
| 121-130        | 3         | 2.54%   |
| Unknown        | 3         | 2.54%   |
| 151-200        | 1         | 0.85%   |
| 141-150        | 1         | 0.85%   |
| 501-1000       | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 60        | 52.63%  |
| 51-100        | 28        | 24.56%  |
| 101-120       | 15        | 13.16%  |
| More than 240 | 4         | 3.51%   |
| 161-240       | 4         | 3.51%   |
| Unknown       | 3         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 56.18%  |
| 2     | 29        | 32.58%  |
| 3     | 6         | 6.74%   |
| 0     | 4         | 4.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 74        | 58.27%  |
| Realtek Semiconductor             | 23        | 18.11%  |
| Lenovo                            | 13        | 10.24%  |
| Qualcomm Atheros                  | 2         | 1.57%   |
| Marvell Technology Group          | 2         | 1.57%   |
| Broadcom Limited                  | 2         | 1.57%   |
| Xiaomi                            | 1         | 0.79%   |
| Sierra Wireless                   | 1         | 0.79%   |
| Samsung Electronics               | 1         | 0.79%   |
| Ralink                            | 1         | 0.79%   |
| Luminary Micro                    | 1         | 0.79%   |
| ICS Advent                        | 1         | 0.79%   |
| Huawei Technologies               | 1         | 0.79%   |
| Ericsson Business Mobile Networks | 1         | 0.79%   |
| DisplayLink                       | 1         | 0.79%   |
| Dell                              | 1         | 0.79%   |
| Broadcom                          | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                     | 12        | 6.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 12        | 6.74%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 10        | 5.62%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 5.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 5.06%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 4.49%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 8         | 4.49%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 3.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 7         | 3.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 3.93%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.81%   |
| Intel Wireless 8260                                                            | 5         | 2.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 5         | 2.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.25%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 2.25%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 2.25%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 2.25%   |
| Intel Wireless 7265                                                            | 3         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.12%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.12%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.12%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.12%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.56%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.56%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.56%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.56%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.56%   |
| Intel Wireless 3165                                                            | 1         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.56%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.56%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.56%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.56%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.56%   |
| Huawei E353/E3131                                                              | 1         | 0.56%   |
| Ericsson Business Mobile Networks N5321 gw                                     | 1         | 0.56%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.56%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                           | 1         | 0.56%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 85.88%  |
| Realtek Semiconductor | 5         | 5.88%   |
| Qualcomm Atheros      | 2         | 2.35%   |
| Sierra Wireless       | 1         | 1.18%   |
| Ralink                | 1         | 1.18%   |
| Dell                  | 1         | 1.18%   |
| Broadcom Limited      | 1         | 1.18%   |
| Broadcom              | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 12        | 14.12%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 14.12%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 9.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 8.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 8.24%   |
| Intel Wireless 8260                                            | 5         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 5.88%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.71%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 4.71%   |
| Intel Wireless 7265                                            | 3         | 3.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 2.35%   |
| Intel Wireless-AC 9260                                         | 2         | 2.35%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.18%   |
| Intel Wireless 3165                                            | 1         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.18%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.18%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.18%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                           | 1         | 1.18%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 51        | 56.04%  |
| Realtek Semiconductor    | 19        | 20.88%  |
| Lenovo                   | 13        | 14.29%  |
| Marvell Technology Group | 2         | 2.2%    |
| Xiaomi                   | 1         | 1.1%    |
| Samsung Electronics      | 1         | 1.1%    |
| ICS Advent               | 1         | 1.1%    |
| Huawei Technologies      | 1         | 1.1%    |
| DisplayLink              | 1         | 1.1%    |
| Broadcom Limited         | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 10        | 10.99%  |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 10.99%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 9.89%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 8.79%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 7.69%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 6.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 5.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 4.4%    |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 4.4%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.3%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.2%    |
| Lenovo USB-C to LAN                                                            | 2         | 2.2%    |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 2.2%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.2%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.1%    |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 1.1%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 1.1%    |
| Intel Ethernet Controller I225-LM                                              | 1         | 1.1%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.1%    |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.1%    |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.1%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.1%    |
| Huawei E353/E3131                                                              | 1         | 1.1%    |
| DisplayLink Plugable UGA-3000                                                  | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 51.57%  |
| Ethernet | 75        | 47.17%  |
| Modem    | 2         | 1.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 53.42%  |
| Ethernet | 68        | 46.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 67        | 80.72%  |
| 1     | 16        | 19.28%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 80        | 95.24%  |
| Yes  | 4         | 4.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 80.6%   |
| Broadcom                        | 5         | 7.46%   |
| IMC Networks                    | 2         | 2.99%   |
| Cambridge Silicon Radio         | 2         | 2.99%   |
| Ralink                          | 1         | 1.49%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |
| Dell                            | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 23.88%  |
| Intel Bluetooth Device                                                              | 16        | 23.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 22.39%  |
| Intel AX200 Bluetooth                                                               | 4         | 5.97%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.99%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.49%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.49%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.49%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.49%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 79        | 60.77%  |
| Nvidia                 | 15        | 11.54%  |
| Lenovo                 | 12        | 9.23%   |
| AMD                    | 6         | 4.62%   |
| Plantronics            | 3         | 2.31%   |
| GN Netcom              | 3         | 2.31%   |
| Texas Instruments      | 2         | 1.54%   |
| Realtek Semiconductor  | 2         | 1.54%   |
| Generalplus Technology | 2         | 1.54%   |
| Logitech               | 1         | 0.77%   |
| JMTek                  | 1         | 0.77%   |
| Google                 | 1         | 0.77%   |
| Focusrite-Novation     | 1         | 0.77%   |
| Dell                   | 1         | 0.77%   |
| C-Media Electronics    | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 16        | 11.68%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 13        | 9.49%   |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 7.3%    |
| Intel Comet Lake PCH cAVS                                                         | 8         | 5.84%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 7         | 5.11%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 5.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 3.65%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.92%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 4         | 2.92%   |
| Plantronics BT600                                                                 | 3         | 2.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 2.19%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3         | 2.19%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.46%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.46%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 1.46%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.46%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.73%   |
| Logitech H555 Headset                                                             | 1         | 0.73%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.73%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.73%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.73%   |
| JMTek iTalk-02                                                                    | 1         | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.73%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 0.73%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 0.73%   |
| Google Pixel earbuds                                                              | 1         | 0.73%   |
| GN Netcom Jabra Link 380                                                          | 1         | 0.73%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                   | 1         | 0.73%   |
| GN Netcom Jabra BIZ 2400 USB                                                      | 1         | 0.73%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.73%   |
| Generalplus Technology USB Audio Device                                           | 1         | 0.73%   |
| Focusrite-Novation Scarlett 2i2 USB                                               | 1         | 0.73%   |
| Dell AC511 Sound Bar                                                              | 1         | 0.73%   |
| C-Media Electronics Blue Snowball                                                 | 1         | 0.73%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 41.67%  |
| SK Hynix            | 8         | 33.33%  |
| Unknown             | 2         | 8.33%   |
| Kingston            | 2         | 8.33%   |
| Micron Technology   | 1         | 4.17%   |
| Crucial             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 4.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 4.17%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 4.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 4.17%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 4.17%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 4.17%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 4.17%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 4.17%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 4.17%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 4.17%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 4.17%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 4.17%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 4.17%   |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 4.17%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 4.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 4.17%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 4.17%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.17%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 4.17%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 4.17%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 4.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 50%     |
| DDR3   | 7         | 38.89%  |
| LPDDR4 | 1         | 5.56%   |
| LPDDR3 | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 94.12%  |
| Row Of Chips | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 38.89%  |
| 16384 | 5         | 27.78%  |
| 8192  | 5         | 27.78%  |
| 32768 | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 25%     |
| 1600  | 5         | 25%     |
| 3200  | 3         | 15%     |
| 2400  | 2         | 10%     |
| 2133  | 2         | 10%     |
| 1333  | 2         | 10%     |
| 1334  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| HP ENVY 4500 series | 1         | 100%    |

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
| Chicony Electronics                    | 28        | 31.46%  |
| IMC Networks                           | 12        | 13.48%  |
| Acer                                   | 11        | 12.36%  |
| Logitech                               | 7         | 7.87%   |
| Sunplus Innovation Technology          | 6         | 6.74%   |
| Realtek Semiconductor                  | 6         | 6.74%   |
| Microdia                               | 6         | 6.74%   |
| Suyin                                  | 3         | 3.37%   |
| Lite-On Technology                     | 3         | 3.37%   |
| Samsung Electronics                    | 2         | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.25%   |
| Unknown                                | 1         | 1.12%   |
| Quanta                                 | 1         | 1.12%   |
| Lenovo                                 | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 15        | 16.48%  |
| Acer Integrated Camera                                       | 11        | 12.09%  |
| IMC Networks Integrated Camera                               | 10        | 10.99%  |
| Realtek Integrated_Webcam_HD                                 | 5         | 5.49%   |
| Logitech HD Pro Webcam C920                                  | 4         | 4.4%    |
| Sunplus Integrated_Webcam_HD                                 | 3         | 3.3%    |
| Lite-On Integrated Camera                                    | 3         | 3.3%    |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 3.3%    |
| Chicony HP HD Camera                                         | 3         | 3.3%    |
| Samsung Galaxy A5 (MTP)                                      | 2         | 2.2%    |
| Microdia Webcam                                              | 2         | 2.2%    |
| Microdia Integrated Webcam                                   | 2         | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 2.2%    |
| Chicony ThinkPad T490 Webcam                                 | 2         | 2.2%    |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 2.2%    |
| Unknown FULL HD 1080P Webcam                                 | 1         | 1.1%    |
| Suyin RGBIR Camera                                           | 1         | 1.1%    |
| Suyin Integrated_Webcam_HD                                   | 1         | 1.1%    |
| Suyin HP Truevision HD                                       | 1         | 1.1%    |
| Sunplus USB2.0 Camera                                        | 1         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.1%    |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 1.1%    |
| Realtek WEB CAMERA M9 Pro                                    | 1         | 1.1%    |
| Quanta HP HD Camera                                          | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 1.1%    |
| Logitech Webcam C925e                                        | 1         | 1.1%    |
| Logitech Webcam C310                                         | 1         | 1.1%    |
| Logitech B525 HD Webcam                                      | 1         | 1.1%    |
| Lenovo Integrated Webcam                                     | 1         | 1.1%    |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.1%    |
| Chicony Integrated IR Camera                                 | 1         | 1.1%    |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.1%    |
| Chicony HP Webcam                                            | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 1.1%    |
| Acer Integrated IR Camera                                    | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 23        | 62.16%  |
| Validity Sensors      | 11        | 29.73%  |
| Upek                  | 2         | 5.41%   |
| Elan Microelectronics | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 45.95%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 10.81%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 8.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 5.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                                      | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 41.67%  |
| Alcor Micro | 4         | 33.33%  |
| Lenovo      | 2         | 16.67%  |
| Upek        | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 33.33%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 16.67%  |
| Broadcom 5880                                              | 2         | 16.67%  |
| Broadcom 58200                                             | 2         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 55.42%  |
| 0     | 29        | 34.94%  |
| 2     | 7         | 8.43%   |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 37        | 57.81%  |
| Chipcard              | 10        | 15.63%  |
| Graphics card         | 9         | 14.06%  |
| Net/wireless          | 2         | 3.13%   |
| Net/ethernet          | 2         | 3.13%   |
| Bluetooth             | 2         | 3.13%   |
| Storage               | 1         | 1.56%   |
| Multimedia controller | 1         | 1.56%   |

