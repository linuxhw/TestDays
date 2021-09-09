RHEL 8 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
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
| HP      | OMEN by HP Laptop 15-dc1... | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
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
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 10.87%  |
| 4.18.0-240.10.1.el8_3.x86_64 | 9         | 9.78%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 8.7%    |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 8.7%    |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 7.61%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 5         | 5.43%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 4.35%   |
| 4.18.0-305.el8.x86_64        | 3         | 3.26%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 3         | 3.26%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 3.26%   |
| 4.18.0-193.el8.x86_64        | 3         | 3.26%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 3.26%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 3.26%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 3.26%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 3.26%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2         | 2.17%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 2.17%   |
| 4.18.0-147.el8.x86_64        | 2         | 2.17%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 1.09%   |
| 4.18.0-80.el8.x86_64         | 1         | 1.09%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 1.09%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 1.09%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 1.09%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 1.09%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 1.09%   |
| 4.18.0-168.el8.x86_64        | 1         | 1.09%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 1         | 1.09%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 1.09%   |
| 4.18.0-144.el8.x86_64        | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 72        | 98.63%  |
| 5.9.1   | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 72        | 98.63%  |
| 5.9     | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 73        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 64        | 85.33%  |
| GNOME Classic | 5         | 6.67%   |
| Unknown       | 5         | 6.67%   |
| KDE5          | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 44        | 57.89%  |
| Wayland | 29        | 38.16%  |
| Unknown | 3         | 3.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 86.84%  |
| GDM     | 10        | 13.16%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 65.33%  |
| Unknown | 6         | 8%      |
| fr_FR   | 3         | 4%      |
| en_GB   | 3         | 4%      |
| pl_PL   | 2         | 2.67%   |
| nl_NL   | 2         | 2.67%   |
| en_IN   | 2         | 2.67%   |
| ru_RU   | 1         | 1.33%   |
| pt_BR   | 1         | 1.33%   |
| ja_JP   | 1         | 1.33%   |
| it_IT   | 1         | 1.33%   |
| es_EC   | 1         | 1.33%   |
| en_IE   | 1         | 1.33%   |
| de_DE   | 1         | 1.33%   |
| de_CH   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 77.33%  |
| BIOS | 17        | 22.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 65        | 89.04%  |
| Ext4 | 8         | 10.96%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 87.84%  |
| GPT     | 9         | 12.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 98.63%  |
| Yes       | 1         | 1.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 93.24%  |
| Yes       | 5         | 6.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 42        | 57.53%  |
| Dell             | 16        | 21.92%  |
| Hewlett-Packard  | 8         | 10.96%  |
| ASUSTek Computer | 3         | 4.11%   |
| Sony             | 2         | 2.74%   |
| TUXEDO           | 1         | 1.37%   |
| Timi             | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 2.74%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 2.74%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 2.74%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 2.74%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 2.74%   |
| Dell Latitude E6430                      | 2         | 2.74%   |
| Dell Latitude 5300                       | 2         | 2.74%   |
| TUXEDO N13xWU                            | 1         | 1.37%   |
| Timi TM1707                              | 1         | 1.37%   |
| Sony VPCEB4L1R                           | 1         | 1.37%   |
| Sony VPCEB23FM                           | 1         | 1.37%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 1.37%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 1.37%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 1.37%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 1.37%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 1.37%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 1.37%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 1.37%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 1.37%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 1.37%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 1.37%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 1.37%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 1.37%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 1.37%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 1.37%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 1.37%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 1.37%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 1.37%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 1.37%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 1.37%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 1.37%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 1         | 1.37%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 1.37%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 1.37%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 1.37%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 1.37%   |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 1.37%   |
| HP ZBook Studio G5                       | 1         | 1.37%   |
| HP ZBook 15 G5                           | 1         | 1.37%   |
| HP ProBook 430 G5                        | 1         | 1.37%   |
| HP Pavilion 14                           | 1         | 1.37%   |
| HP OMEN by HP Laptop 15-dc1xxx           | 1         | 1.37%   |
| HP EliteBook 850 G7 Notebook PC          | 1         | 1.37%   |
| HP EliteBook 8460p                       | 1         | 1.37%   |
| HP 250 G4 Notebook PC                    | 1         | 1.37%   |
| Dell XPS 15 9560                         | 1         | 1.37%   |
| Dell Precision 7510                      | 1         | 1.37%   |
| Dell Precision 5540                      | 1         | 1.37%   |
| Dell Precision 3541                      | 1         | 1.37%   |
| Dell Latitude E6530                      | 1         | 1.37%   |
| Dell Latitude E6420                      | 1         | 1.37%   |
| Dell Latitude E5510                      | 1         | 1.37%   |
| Dell Latitude 5290                       | 1         | 1.37%   |
| Dell Inspiron N5110                      | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 41        | 56.16%  |
| Dell Latitude       | 8         | 10.96%  |
| Dell Precision      | 3         | 4.11%   |
| Dell Inspiron       | 3         | 4.11%   |
| HP ZBook            | 2         | 2.74%   |
| HP EliteBook        | 2         | 2.74%   |
| TUXEDO N13xWU       | 1         | 1.37%   |
| Timi TM1707         | 1         | 1.37%   |
| Sony VPCEB4L1R      | 1         | 1.37%   |
| Sony VPCEB23FM      | 1         | 1.37%   |
| Lenovo ThinkpadT460 | 1         | 1.37%   |
| HP ProBook          | 1         | 1.37%   |
| HP Pavilion         | 1         | 1.37%   |
| HP OMEN             | 1         | 1.37%   |
| HP 250              | 1         | 1.37%   |
| Dell XPS            | 1         | 1.37%   |
| Dell G3             | 1         | 1.37%   |
| ASUS Zephyrus       | 1         | 1.37%   |
| ASUS TUF            | 1         | 1.37%   |
| ASUS GL502VMK       | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 35.62%  |
| 2019 | 20        | 27.4%   |
| 2018 | 11        | 15.07%  |
| 2021 | 5         | 6.85%   |
| 2017 | 3         | 4.11%   |
| 2011 | 3         | 4.11%   |
| 2010 | 2         | 2.74%   |
| 2016 | 1         | 1.37%   |
| 2014 | 1         | 1.37%   |
| 2012 | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 73        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 64        | 86.49%  |
| Enabled  | 10        | 13.51%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 27        | 35.53%  |
| 4.01-8.0    | 13        | 17.11%  |
| 16.01-24.0  | 13        | 17.11%  |
| 8.01-16.0   | 13        | 17.11%  |
| 3.01-4.0    | 5         | 6.58%   |
| 64.01-256.0 | 4         | 5.26%   |
| 24.01-32.0  | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 35        | 40.7%   |
| 8.01-16.0  | 17        | 19.77%  |
| 3.01-4.0   | 12        | 13.95%  |
| 2.01-3.0   | 11        | 12.79%  |
| 1.01-2.0   | 8         | 9.3%    |
| 16.01-24.0 | 2         | 2.33%   |
| 24.01-32.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 73.68%  |
| 2      | 12        | 15.79%  |
| 3      | 7         | 9.21%   |
| 4      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 83.78%  |
| Yes       | 12        | 16.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 89.19%  |
| No        | 8         | 10.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 98.63%  |
| No        | 1         | 1.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 76.62%  |
| No        | 18        | 23.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 21.62%  |
| India        | 11        | 14.86%  |
| UK           | 5         | 6.76%   |
| Germany      | 5         | 6.76%   |
| France       | 3         | 4.05%   |
| Switzerland  | 2         | 2.7%    |
| South Africa | 2         | 2.7%    |
| Netherlands  | 2         | 2.7%    |
| Mexico       | 2         | 2.7%    |
| Japan        | 2         | 2.7%    |
| Czechia      | 2         | 2.7%    |
| Canada       | 2         | 2.7%    |
| Australia    | 2         | 2.7%    |
| Spain        | 1         | 1.35%   |
| Singapore    | 1         | 1.35%   |
| Russia       | 1         | 1.35%   |
| Romania      | 1         | 1.35%   |
| Poland       | 1         | 1.35%   |
| Pakistan     | 1         | 1.35%   |
| Nepal        | 1         | 1.35%   |
| Myanmar      | 1         | 1.35%   |
| Morocco      | 1         | 1.35%   |
| Lithuania    | 1         | 1.35%   |
| Kuwait       | 1         | 1.35%   |
| Italy        | 1         | 1.35%   |
| Ireland      | 1         | 1.35%   |
| Ecuador      | 1         | 1.35%   |
| Colombia     | 1         | 1.35%   |
| Bulgaria     | 1         | 1.35%   |
| Brazil       | 1         | 1.35%   |
| Armenia      | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Munich                   | 3         | 3.61%   |
| Mumbai                   | 2         | 2.41%   |
| Mexico City              | 2         | 2.41%   |
| Doetinchem               | 2         | 2.41%   |
| Yerevan                  | 1         | 1.2%    |
| Taringa                  | 1         | 1.2%    |
| Sumida                   | 1         | 1.2%    |
| Stroud                   | 1         | 1.2%    |
| Sofia                    | 1         | 1.2%    |
| Singapore                | 1         | 1.2%    |
| Sheffield                | 1         | 1.2%    |
| San Francisco            | 1         | 1.2%    |
| Sammamish                | 1         | 1.2%    |
| Sal?©                    | 1         | 1.2%    |
| Saint-Alphonse-Rodriguez | 1         | 1.2%    |
| Sagaing                  | 1         | 1.2%    |
| Roudnice nad Labem       | 1         | 1.2%    |
| Roha                     | 1         | 1.2%    |
| Reims                    | 1         | 1.2%    |
| Raleigh                  | 1         | 1.2%    |
| Quito                    | 1         | 1.2%    |
| Queenscliff              | 1         | 1.2%    |
| Queens                   | 1         | 1.2%    |
| Pune                     | 1         | 1.2%    |
| Prague                   | 1         | 1.2%    |
| Port Elizabeth           | 1         | 1.2%    |
| Pleasanton               | 1         | 1.2%    |
| Paraiso do Tocantins     | 1         | 1.2%    |
| Paragould                | 1         | 1.2%    |
| Oyama                    | 1         | 1.2%    |
| Ottawa                   | 1         | 1.2%    |
| Ogden                    | 1         | 1.2%    |
| Neuves-Maisons           | 1         | 1.2%    |
| Moscow                   | 1         | 1.2%    |
| Miroslava                | 1         | 1.2%    |
| Milan                    | 1         | 1.2%    |
| Mangalore                | 1         | 1.2%    |
| Madrid                   | 1         | 1.2%    |
| London                   | 1         | 1.2%    |
| Littleton                | 1         | 1.2%    |
| Lahore                   | 1         | 1.2%    |
| Kuwait City              | 1         | 1.2%    |
| Kochi                    | 1         | 1.2%    |
| Johnstone                | 1         | 1.2%    |
| Islamabad                | 1         | 1.2%    |
| Impflingen               | 1         | 1.2%    |
| Hyderabad                | 1         | 1.2%    |
| Houston                  | 1         | 1.2%    |
| Hosur                    | 1         | 1.2%    |
| Hobart                   | 1         | 1.2%    |
| Hetauda                  | 1         | 1.2%    |
| Gurgaon                  | 1         | 1.2%    |
| Grosseto                 | 1         | 1.2%    |
| Grenoble                 | 1         | 1.2%    |
| Grabs                    | 1         | 1.2%    |
| Galway                   | 1         | 1.2%    |
| Fort Lauderdale          | 1         | 1.2%    |
| Drachten                 | 1         | 1.2%    |
| Denver                   | 1         | 1.2%    |
| Coimbatore               | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 26.6%   |
| WDC                 | 10        | 15     | 10.64%  |
| Toshiba             | 9         | 14     | 9.57%   |
| Seagate             | 9         | 12     | 9.57%   |
| Sandisk             | 9         | 14     | 9.57%   |
| SK Hynix            | 8         | 8      | 8.51%   |
| Intel               | 5         | 7      | 5.32%   |
| Unknown             | 4         | 6      | 4.26%   |
| Micron Technology   | 3         | 5      | 3.19%   |
| Kingston            | 3         | 3      | 3.19%   |
| HGST                | 2         | 2      | 2.13%   |
| Team                | 1         | 2      | 1.06%   |
| SMI                 | 1         | 2      | 1.06%   |
| Silicon Motion      | 1         | 2      | 1.06%   |
| PNY                 | 1         | 4      | 1.06%   |
| Lite-On             | 1         | 1      | 1.06%   |
| Lenovo              | 1         | 1      | 1.06%   |
| Corsair             | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 7         | 6.86%   |
| Sandisk NVMe SSD Drive 256GB            | 5         | 4.9%    |
| Samsung NVMe SSD Drive 256GB            | 5         | 4.9%    |
| Samsung NVMe SSD Drive 512GB            | 3         | 2.94%   |
| Samsung NVMe SSD Drive 1024GB           | 3         | 2.94%   |
| Unknown NVMe SSD Drive 256GB            | 2         | 1.96%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 1.96%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 1.96%   |
| Seagate Expansion 1TB                   | 2         | 1.96%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 1.96%   |
| Samsung Portable SSD T5 500GB           | 2         | 1.96%   |
| Samsung NVMe SSD Drive 2TB              | 2         | 1.96%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.96%   |
| Micron NVMe SSD Drive 256GB             | 2         | 1.96%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.96%   |
| Intel NVMe SSD Drive 2TB                | 2         | 1.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.98%   |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.98%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.98%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.98%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.98%   |
| WDC WD20 SPZX-11UA7T0 2TB               | 1         | 0.98%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.98%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.98%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.98%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.98%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.98%   |
| Unknown MMC Card  33GB                  | 1         | 0.98%   |
| Unknown MMC Card  32GB                  | 1         | 0.98%   |
| Toshiba TR150 960GB SSD                 | 1         | 0.98%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.98%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.98%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.98%   |
| Toshiba HDWL110 1TB                     | 1         | 0.98%   |
| Team T253X2512G 512GB SSD               | 1         | 0.98%   |
| SMI DISK 512GB                          | 1         | 0.98%   |
| SK Hynix NVMe SSD Drive 1024GB          | 1         | 0.98%   |
| Silicon Motion NVMe SSD Drive 1TB       | 1         | 0.98%   |
| Seagate ST9160827AS 160GB               | 1         | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.98%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.98%   |
| Seagate BUP Slim BK 1TB                 | 1         | 0.98%   |
| Seagate BUP Portable 5TB                | 1         | 0.98%   |
| Seagate BUP BL 5TB                      | 1         | 0.98%   |
| Seagate BarraCuda SSD ZA2000CM10002 2TB | 1         | 0.98%   |
| SanDisk SDSSDH31024G 1024GB             | 1         | 0.98%   |
| SanDisk SD7SN6S-256G-1006 256GB SSD     | 1         | 0.98%   |
| SanDisk SD7SB7S512G1001 512GB SSD       | 1         | 0.98%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 0.98%   |
| SanDisk Extreme SSD 500GB               | 1         | 0.98%   |
| Samsung SSD PM830 2.5 7mm 256GB         | 1         | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 0.98%   |
| Samsung SSD 860 QVO 1TB                 | 1         | 0.98%   |
| Samsung SSD 860 EVO M.2 500GB           | 1         | 0.98%   |
| Samsung SSD 860 EVO 500GB               | 1         | 0.98%   |
| Samsung SSD 860 EVO 2TB                 | 1         | 0.98%   |
| Samsung SSD 850 PRO 2TB                 | 1         | 0.98%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 11     | 47.37%  |
| WDC     | 5         | 8      | 26.32%  |
| Toshiba | 3         | 5      | 15.79%  |
| HGST    | 2         | 2      | 10.53%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 42.31%  |
| WDC                 | 3         | 4      | 11.54%  |
| SanDisk             | 3         | 4      | 11.54%  |
| Kingston            | 3         | 3      | 11.54%  |
| Toshiba             | 1         | 1      | 3.85%   |
| Team                | 1         | 2      | 3.85%   |
| Seagate             | 1         | 1      | 3.85%   |
| PNY                 | 1         | 4      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Corsair             | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 47        | 68     | 50.54%  |
| SSD     | 24        | 33     | 25.81%  |
| HDD     | 19        | 26     | 20.43%  |
| MMC     | 2         | 3      | 2.15%   |
| Unknown | 1         | 2      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 47        | 68     | 52.81%  |
| SATA | 32        | 52     | 35.96%  |
| SAS  | 8         | 9      | 8.99%   |
| MMC  | 2         | 3      | 2.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 26     | 46.51%  |
| 0.51-1.0   | 15        | 24     | 34.88%  |
| 1.01-2.0   | 5         | 6      | 11.63%  |
| 4.01-10.0  | 2         | 2      | 4.65%   |
| 3.01-4.0   | 1         | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 46.67%  |
| 251-500        | 12        | 16%     |
| 501-1000       | 10        | 13.33%  |
| 1001-2000      | 6         | 8%      |
| More than 3000 | 5         | 6.67%   |
| 51-100         | 3         | 4%      |
| 21-50          | 2         | 2.67%   |
| 2001-3000      | 1         | 1.33%   |
| 1-20           | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 21        | 25.3%   |
| 101-250        | 18        | 21.69%  |
| 1-20           | 16        | 19.28%  |
| 51-100         | 14        | 16.87%  |
| 251-500        | 6         | 7.23%   |
| 501-1000       | 5         | 6.02%   |
| More than 3000 | 1         | 1.2%    |
| 2001-3000      | 1         | 1.2%    |
| 1001-2000      | 1         | 1.2%    |

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
| Detected | 67        | 120    | 88.16%  |
| Works    | 9         | 12     | 11.84%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 47.06%  |
| Samsung Electronics          | 16        | 18.82%  |
| SK Hynix                     | 8         | 9.41%   |
| Sandisk                      | 8         | 9.41%   |
| Toshiba America Info Systems | 5         | 5.88%   |
| Micron Technology            | 2         | 2.35%   |
| KIOXIA                       | 2         | 2.35%   |
| Silicon Motion               | 1         | 1.18%   |
| Lite-On Technology           | 1         | 1.18%   |
| Lenovo                       | 1         | 1.18%   |
| AMD                          | 1         | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 14        | 16.09%  |
| SK Hynix Non-Volatile memory controller                                       | 8         | 9.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 8         | 9.2%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 6         | 6.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 4         | 4.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 3.45%   |
| Intel SSD 660P Series                                                         | 3         | 3.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 3.45%   |
| Micron Non-Volatile memory controller                                         | 2         | 2.3%    |
| KIOXIA Non-Volatile memory controller                                         | 2         | 2.3%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 2         | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 2.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 2.3%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 1.15%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 1.15%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.15%   |
| Samsung NVMe Controller                                                       | 1         | 1.15%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 1.15%   |
| Lenovo Non-Volatile memory controller                                         | 1         | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 1.15%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 47        | 55.29%  |
| SATA | 35        | 41.18%  |
| RAID | 3         | 3.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 94.52%  |
| AMD    | 4         | 5.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 10.96%  |
| Intel Core i7-10850H CPU @ 2.70GHz            | 5         | 6.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 5.48%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 5.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 4.11%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 4.11%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 2.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.74%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 2.74%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 2.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.74%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 2.74%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 1.37%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 1.37%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 1.37%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 1.37%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.37%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.37%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 1.37%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.37%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.37%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.37%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.37%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 42        | 57.53%  |
| Intel Core i5   | 20        | 27.4%   |
| Intel Xeon      | 3         | 4.11%   |
| AMD Ryzen 7     | 3         | 4.11%   |
| Intel Core i9   | 2         | 2.74%   |
| Intel Core i3   | 2         | 2.74%   |
| AMD Ryzen 7 PRO | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 34        | 46.58%  |
| 2      | 21        | 28.77%  |
| 6      | 14        | 19.18%  |
| 8      | 4         | 5.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 98.63%  |
| 1      | 1         | 1.37%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 94.67%  |
| Unknown        | 4         | 5.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 16        | 21.33%  |
| 0x806ea    | 9         | 12%     |
| 0xa0652    | 6         | 8%      |
| 0x906ea    | 6         | 8%      |
| 0x306a9    | 5         | 6.67%   |
| 0x206a7    | 5         | 6.67%   |
| 0x906ed    | 4         | 5.33%   |
| 0x406e3    | 3         | 4%      |
| 0x306d4    | 3         | 4%      |
| 0x20655    | 3         | 4%      |
| Unknown    | 3         | 4%      |
| 0x906e9    | 2         | 2.67%   |
| 0x806e9    | 2         | 2.67%   |
| 0x506e3    | 2         | 2.67%   |
| 0x08108102 | 2         | 2.67%   |
| 0x40651    | 1         | 1.33%   |
| 0x20652    | 1         | 1.33%   |
| 0x08600104 | 1         | 1.33%   |
| 0x08600103 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 40        | 54.79%  |
| CometLake   | 6         | 8.22%   |
| Skylake     | 5         | 6.85%   |
| SandyBridge | 5         | 6.85%   |
| IvyBridge   | 5         | 6.85%   |
| Westmere    | 4         | 5.48%   |
| Broadwell   | 3         | 4.11%   |
| Zen+        | 2         | 2.74%   |
| Zen 2       | 2         | 2.74%   |
| Haswell     | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 66.67%  |
| Nvidia | 21        | 23.33%  |
| AMD    | 9         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 12.22%  |
| Intel UHD Graphics 620                                                                | 9         | 10%     |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 6.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 6.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 4.44%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 3.33%   |
| Intel HD Graphics 5500                                                                | 3         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 3.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 2.22%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 2.22%   |
| Intel HD Graphics 620                                                                 | 2         | 2.22%   |
| AMD Renoir                                                                            | 2         | 2.22%   |
| AMD Picasso                                                                           | 2         | 2.22%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 1.11%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 1.11%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.11%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 1.11%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 1.11%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 1.11%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 1         | 1.11%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 1.11%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 1.11%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 1.11%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 1.11%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 1.11%   |
| Intel HD Graphics 630                                                                 | 1         | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.11%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.11%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 1.11%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 61.64%  |
| Intel + Nvidia | 12        | 16.44%  |
| 1 x Nvidia     | 7         | 9.59%   |
| 1 x AMD        | 4         | 5.48%   |
| Intel + AMD    | 3         | 4.11%   |
| AMD + Nvidia   | 2         | 2.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 87.67%  |
| Proprietary | 6         | 8.22%   |
| Unknown     | 3         | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 71.23%  |
| 3.01-4.0   | 5         | 6.85%   |
| 1.01-2.0   | 5         | 6.85%   |
| 5.01-6.0   | 4         | 5.48%   |
| 0.51-1.0   | 4         | 5.48%   |
| 0.01-0.5   | 2         | 2.74%   |
| 7.01-8.0   | 1         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 15.84%  |
| Chimei Innolux          | 13        | 12.87%  |
| Dell                    | 12        | 11.88%  |
| BOE                     | 11        | 10.89%  |
| LG Display              | 10        | 9.9%    |
| Lenovo                  | 9         | 8.91%   |
| Samsung Electronics     | 7         | 6.93%   |
| Hewlett-Packard         | 4         | 3.96%   |
| Sharp                   | 3         | 2.97%   |
| Acer                    | 3         | 2.97%   |
| Philips                 | 2         | 1.98%   |
| PANDA                   | 2         | 1.98%   |
| LGD                     | 2         | 1.98%   |
| InfoVision              | 2         | 1.98%   |
| Sceptre Tech            | 1         | 0.99%   |
| Planar                  | 1         | 0.99%   |
| Goldstar                | 1         | 0.99%   |
| Eizo                    | 1         | 0.99%   |
| Chi Mei Optoelectronics | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 3.88%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 3.88%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 3         | 2.91%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                  | 2         | 1.94%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 1.94%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 1.94%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch             | 2         | 1.94%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 1.94%   |
| Hewlett-Packard 27y HPN351C 1920x1080 598x336mm 27.0-inch                | 2         | 1.94%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 1.94%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch         | 2         | 1.94%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 1.94%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 2         | 1.94%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                    | 2         | 1.94%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 2         | 1.94%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch           | 2         | 1.94%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 1.94%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.97%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.97%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.97%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch           | 1         | 0.97%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 1         | 0.97%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch        | 1         | 0.97%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch        | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch     | 1         | 0.97%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch        | 1         | 0.97%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch        | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.97%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                    | 1         | 0.97%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 1         | 0.97%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                   | 1         | 0.97%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 0.97%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 0.97%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 0.97%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 1         | 0.97%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch                | 1         | 0.97%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch              | 1         | 0.97%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch              | 1         | 0.97%   |
| Eizo EV2416W ENC2389 1920x1200 519x324mm 24.1-inch                       | 1         | 0.97%   |
| Dell U4919DW DELA10F 3840x1080 1198x337mm 49.0-inch                      | 1         | 0.97%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 1         | 0.97%   |
| Dell SP2309W DELD01D 2048x1152 510x290mm 23.1-inch                       | 1         | 0.97%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                       | 1         | 0.97%   |
| Dell S2318HN/NX DELD0C0 1920x1080 510x290mm 23.1-inch                    | 1         | 0.97%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                        | 1         | 0.97%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                         | 1         | 0.97%   |
| Dell E2414H DEL4091 1920x1080 530x300mm 24.0-inch                        | 1         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 0.97%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 1         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 0.97%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 0.97%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                    | 1         | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 61.45%  |
| 1366x768 (WXGA)    | 11        | 13.25%  |
| 1600x900 (HD+)     | 6         | 7.23%   |
| 3840x2160 (4K)     | 4         | 4.82%   |
| 1920x1200 (WUXGA)  | 3         | 3.61%   |
| 2560x1440 (QHD)    | 2         | 2.41%   |
| 3840x1080          | 1         | 1.2%    |
| 2560x1080          | 1         | 1.2%    |
| 2048x1152          | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |
| 1440x900 (WXGA+)   | 1         | 1.2%    |
| 1280x800 (WXGA)    | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 32        | 32%     |
| 14      | 14        | 14%     |
| 13      | 13        | 13%     |
| 24      | 11        | 11%     |
| 27      | 8         | 8%      |
| 23      | 5         | 5%      |
| 12      | 5         | 5%      |
| 21      | 2         | 2%      |
| 17      | 2         | 2%      |
| Unknown | 2         | 2%      |
| 49      | 1         | 1%      |
| 34      | 1         | 1%      |
| 31      | 1         | 1%      |
| 22      | 1         | 1%      |
| 19      | 1         | 1%      |
| 18      | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 57.73%  |
| 501-600     | 18        | 18.56%  |
| 201-300     | 8         | 8.25%   |
| 401-500     | 5         | 5.15%   |
| 601-700     | 4         | 4.12%   |
| 351-400     | 2         | 2.06%   |
| Unknown     | 2         | 2.06%   |
| 701-800     | 1         | 1.03%   |
| 1001-1500   | 1         | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 86.84%  |
| 16/10   | 5         | 6.58%   |
| Unknown | 2         | 2.63%   |
| 32/9    | 1         | 1.32%   |
| 3/2     | 1         | 1.32%   |
| 21/9    | 1         | 1.32%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 32%     |
| 81-90          | 24        | 24%     |
| 201-250        | 14        | 14%     |
| 301-350        | 8         | 8%      |
| 61-70          | 5         | 5%      |
| 251-300        | 5         | 5%      |
| 71-80          | 3         | 3%      |
| 351-500        | 2         | 2%      |
| 121-130        | 2         | 2%      |
| Unknown        | 2         | 2%      |
| 151-200        | 1         | 1%      |
| 141-150        | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 55.21%  |
| 51-100        | 22        | 22.92%  |
| 101-120       | 14        | 14.58%  |
| 161-240       | 3         | 3.13%   |
| More than 240 | 2         | 2.08%   |
| Unknown       | 2         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 58.97%  |
| 2     | 23        | 29.49%  |
| 3     | 5         | 6.41%   |
| 0     | 4         | 5.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 64        | 56.64%  |
| Realtek Semiconductor             | 21        | 18.58%  |
| Lenovo                            | 11        | 9.73%   |
| Qualcomm Atheros                  | 2         | 1.77%   |
| Marvell Technology Group          | 2         | 1.77%   |
| Broadcom Limited                  | 2         | 1.77%   |
| Xiaomi                            | 1         | 0.88%   |
| Sierra Wireless                   | 1         | 0.88%   |
| Samsung Electronics               | 1         | 0.88%   |
| Ralink                            | 1         | 0.88%   |
| Luminary Micro                    | 1         | 0.88%   |
| ICS Advent                        | 1         | 0.88%   |
| Huawei Technologies               | 1         | 0.88%   |
| Ericsson Business Mobile Networks | 1         | 0.88%   |
| DisplayLink                       | 1         | 0.88%   |
| Dell                              | 1         | 0.88%   |
| Broadcom                          | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 11        | 6.96%   |
| Intel Wireless 8265 / 8275                                                     | 10        | 6.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 9         | 5.7%    |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 5.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 5.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 4.43%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 6         | 3.8%    |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 3.8%    |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 3.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 6         | 3.8%    |
| Intel Comet Lake PCH CNVi WiFi                                                 | 6         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 5         | 3.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.53%   |
| Intel Wireless 8260                                                            | 4         | 2.53%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 2.53%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 2.53%   |
| Intel Wireless 7265                                                            | 3         | 1.9%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.9%    |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 1.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.27%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.63%   |
| Sierra Wireless MC7455 Qualcomm?‚ Snapdragon???„?? X7 LTE-A                    | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.63%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.63%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.63%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.63%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.63%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.63%   |
| Intel Wireless 3165                                                            | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.63%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.63%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.63%   |
| Huawei E353/E3131                                                              | 1         | 0.63%   |
| Ericsson Business Mobile Networks N5321 gw                                     | 1         | 0.63%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.63%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                           | 1         | 0.63%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 84%     |
| Realtek Semiconductor | 5         | 6.67%   |
| Qualcomm Atheros      | 2         | 2.67%   |
| Sierra Wireless       | 1         | 1.33%   |
| Ralink                | 1         | 1.33%   |
| Dell                  | 1         | 1.33%   |
| Broadcom Limited      | 1         | 1.33%   |
| Broadcom              | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 14.67%  |
| Intel Wireless 8265 / 8275                                     | 10        | 13.33%  |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 9.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 8%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 8%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 6.67%   |
| Intel Wireless 8260                                            | 4         | 5.33%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 5.33%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 5.33%   |
| Intel Wireless 7265                                            | 3         | 4%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 2.67%   |
| Sierra Wireless MC7455 Qualcomm?‚ Snapdragon???„?? X7 LTE-A    | 1         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| Intel Wireless-AC 9260                                         | 1         | 1.33%   |
| Intel Wireless 3165                                            | 1         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.33%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                           | 1         | 1.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 55.56%  |
| Realtek Semiconductor    | 17        | 20.99%  |
| Lenovo                   | 11        | 13.58%  |
| Marvell Technology Group | 2         | 2.47%   |
| Xiaomi                   | 1         | 1.23%   |
| Samsung Electronics      | 1         | 1.23%   |
| ICS Advent               | 1         | 1.23%   |
| Huawei Technologies      | 1         | 1.23%   |
| DisplayLink              | 1         | 1.23%   |
| Broadcom Limited         | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 9         | 11.11%  |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 11.11%  |
| Lenovo ThinkPad TBT 3 Dock                                                     | 6         | 7.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 7.41%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 4.94%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.7%    |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 3.7%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.47%   |
| Lenovo USB-C to LAN                                                            | 2         | 2.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 2.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 1.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.23%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 1.23%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 1.23%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.23%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.23%   |
| Huawei E353/E3131                                                              | 1         | 1.23%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 1.23%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 51.43%  |
| Ethernet | 66        | 47.14%  |
| Modem    | 2         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 53.91%  |
| Ethernet | 59        | 46.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 60        | 82.19%  |
| 1     | 13        | 17.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 95.95%  |
| Yes  | 3         | 4.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 77.97%  |
| Broadcom                        | 5         | 8.47%   |
| IMC Networks                    | 2         | 3.39%   |
| Cambridge Silicon Radio         | 2         | 3.39%   |
| Ralink                          | 1         | 1.69%   |
| Qualcomm Atheros Communications | 1         | 1.69%   |
| Foxconn / Hon Hai               | 1         | 1.69%   |
| Dell                            | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 30        | 50.85%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 25.42%  |
| IMC Networks Bluetooth Radio                                                        | 2         | 3.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 3.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 3.39%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.69%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.69%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 69        | 62.73%  |
| Nvidia                 | 13        | 11.82%  |
| Lenovo                 | 10        | 9.09%   |
| AMD                    | 6         | 5.45%   |
| Realtek Semiconductor  | 2         | 1.82%   |
| Plantronics            | 2         | 1.82%   |
| Generalplus Technology | 2         | 1.82%   |
| Texas Instruments      | 1         | 0.91%   |
| Logitech               | 1         | 0.91%   |
| JMTek                  | 1         | 0.91%   |
| GN Netcom              | 1         | 0.91%   |
| Focusrite-Novation     | 1         | 0.91%   |
| Dell                   | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 14        | 11.97%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 11        | 9.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 8.55%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 6         | 5.13%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 6         | 5.13%   |
| Intel Comet Lake PCH cAVS                                                         | 6         | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 4.27%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 3.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 3.42%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 4         | 3.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 2.56%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 2.56%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.71%   |
| Plantronics BT600                                                                 | 2         | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.71%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 1.71%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.71%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.71%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.85%   |
| Logitech H555 Headset                                                             | 1         | 0.85%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 1         | 0.85%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.85%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.85%   |
| JMTek iTalk-02                                                                    | 1         | 0.85%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 0.85%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 0.85%   |
| GN Netcom Jabra EVOLVE 20 MS                                                      | 1         | 0.85%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.85%   |
| Generalplus Technology USB Audio Device                                           | 1         | 0.85%   |
| Focusrite-Novation Scarlett 2i2 Camera                                            | 1         | 0.85%   |
| Dell AC511 Sound Bar                                                              | 1         | 0.85%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 38.1%   |
| SK Hynix            | 7         | 33.33%  |
| Unknown             | 2         | 9.52%   |
| Kingston            | 2         | 9.52%   |
| Micron Technology   | 1         | 4.76%   |
| Crucial             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 4.76%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 4.76%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 4.76%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 4.76%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 4.76%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 4.76%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 4.76%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 4.76%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 4.76%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 4.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 4.76%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 4.76%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 4.76%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 4.76%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.76%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 4.76%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 4.76%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 4.76%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 4.76%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s   | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 46.67%  |
| DDR4   | 6         | 40%     |
| LPDDR4 | 1         | 6.67%   |
| LPDDR3 | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 92.86%  |
| Row Of Chips | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 46.67%  |
| 8192  | 5         | 33.33%  |
| 16384 | 3         | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 29.41%  |
| 1600  | 5         | 29.41%  |
| 2400  | 2         | 11.76%  |
| 1333  | 2         | 11.76%  |
| 3200  | 1         | 5.88%   |
| 2133  | 1         | 5.88%   |
| 1334  | 1         | 5.88%   |

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
| Chicony Electronics                    | 24        | 31.17%  |
| IMC Networks                           | 10        | 12.99%  |
| Acer                                   | 7         | 9.09%   |
| Sunplus Innovation Technology          | 6         | 7.79%   |
| Realtek Semiconductor                  | 6         | 7.79%   |
| Microdia                               | 6         | 7.79%   |
| Logitech                               | 5         | 6.49%   |
| Suyin                                  | 3         | 3.9%    |
| Lite-On Technology                     | 3         | 3.9%    |
| Samsung Electronics                    | 2         | 2.6%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.6%    |
| Unknown                                | 1         | 1.3%    |
| Quanta                                 | 1         | 1.3%    |
| Lenovo                                 | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 12        | 15.38%  |
| IMC Networks Integrated Camera                               | 8         | 10.26%  |
| Acer Integrated Camera                                       | 6         | 7.69%   |
| Realtek Integrated_Webcam_HD                                 | 5         | 6.41%   |
| Logitech HD Pro Webcam C920                                  | 4         | 5.13%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 3.85%   |
| Lite-On Integrated Camera                                    | 3         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 3.85%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 2.56%   |
| Microdia Webcam                                              | 2         | 2.56%   |
| Microdia Integrated Webcam                                   | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 2.56%   |
| Chicony ThinkPad T490 Webcam                                 | 2         | 2.56%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 2.56%   |
| Chicony HP HD Camera                                         | 2         | 2.56%   |
| Unknown FULL HD 1080P Webcam                                 | 1         | 1.28%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 1.28%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 1.28%   |
| Suyin HP Truevision HD                                       | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.28%   |
| Sunplus Integrated Webcam                                    | 1         | 1.28%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 1.28%   |
| Realtek NexiGo N660P FHD Webcam                              | 1         | 1.28%   |
| Quanta HP HD Camera                                          | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 1.28%   |
| Logitech Webcam C310                                         | 1         | 1.28%   |
| Lenovo Integrated Webcam                                     | 1         | 1.28%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.28%   |
| Chicony Integrated IR Camera                                 | 1         | 1.28%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.28%   |
| Chicony HP Webcam                                            | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 1.28%   |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 18        | 58.06%  |
| Validity Sensors      | 10        | 32.26%  |
| Upek                  | 2         | 6.45%   |
| Elan Microelectronics | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 45.16%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 9.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.23%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 45.45%  |
| Alcor Micro | 3         | 27.27%  |
| Lenovo      | 2         | 18.18%  |
| Upek        | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 27.27%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 18.18%  |
| Broadcom 5880                                              | 2         | 18.18%  |
| Broadcom 58200                                             | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 54.79%  |
| 0     | 26        | 35.62%  |
| 2     | 6         | 8.22%   |
| 3     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 31        | 56.36%  |
| Chipcard              | 9         | 16.36%  |
| Graphics card         | 8         | 14.55%  |
| Net/ethernet          | 2         | 3.64%   |
| Bluetooth             | 2         | 3.64%   |
| Storage               | 1         | 1.82%   |
| Net/wireless          | 1         | 1.82%   |
| Multimedia controller | 1         | 1.82%   |

