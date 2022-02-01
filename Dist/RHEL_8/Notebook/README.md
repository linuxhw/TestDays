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
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Lenovo  | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP      | EliteBook 8460p             | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| ASUSTek | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| Toshiba | Satellite Pro R50-C         | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba | Satellite Pro R50-C         | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| Dell    | Precision 3551              | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [6c62008ae3](https://linux-hardware.org/?probe=6c62008ae3) | Dec 21, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [6f29b7bde7](https://linux-hardware.org/?probe=6f29b7bde7) | Dec 21, 2021 |
| Lenovo  | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [f88a7d7f15](https://linux-hardware.org/?probe=f88a7d7f15) | Dec 06, 2021 |
| Acer    | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
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
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 8.93%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 9         | 8.04%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 7.14%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 7.14%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 6.25%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 5         | 4.46%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 3.57%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 3.57%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 3.57%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 3.57%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 3.57%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.68%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.68%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 2.68%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.68%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.68%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.68%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 2.68%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.68%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.79%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 2         | 1.79%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.79%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.79%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.89%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.89%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.89%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 0.89%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1         | 0.89%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 0.89%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.89%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.89%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.89%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.89%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 1         | 0.89%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 0.89%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 88        | 98.88%  |
| 5.9.1   | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 88        | 98.88%  |
| 5.9     | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 89        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 78        | 83.87%  |
| Unknown       | 8         | 8.6%    |
| GNOME Classic | 5         | 5.38%   |
| KDE5          | 2         | 2.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 59.14%  |
| Wayland | 34        | 36.56%  |
| Unknown | 4         | 4.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 85.87%  |
| GDM     | 13        | 14.13%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 62        | 67.39%  |
| Unknown | 7         | 7.61%   |
| fr_FR   | 4         | 4.35%   |
| en_GB   | 4         | 4.35%   |
| pt_BR   | 2         | 2.17%   |
| pl_PL   | 2         | 2.17%   |
| nl_NL   | 2         | 2.17%   |
| en_IN   | 2         | 2.17%   |
| ru_RU   | 1         | 1.09%   |
| ja_JP   | 1         | 1.09%   |
| it_IT   | 1         | 1.09%   |
| es_EC   | 1         | 1.09%   |
| en_IE   | 1         | 1.09%   |
| de_DE   | 1         | 1.09%   |
| de_CH   | 1         | 1.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 78.26%  |
| BIOS | 20        | 21.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 79        | 88.76%  |
| Ext4 | 10        | 11.24%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 82.61%  |
| GPT     | 15        | 16.3%   |
| MBR     | 1         | 1.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 98.88%  |
| Yes       | 1         | 1.12%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 94.44%  |
| Yes       | 5         | 5.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 52        | 58.43%  |
| Dell             | 17        | 19.1%   |
| Hewlett-Packard  | 10        | 11.24%  |
| ASUSTek Computer | 4         | 4.49%   |
| Sony             | 2         | 2.25%   |
| TUXEDO           | 1         | 1.12%   |
| Toshiba          | 1         | 1.12%   |
| Timi             | 1         | 1.12%   |
| Acer             | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 3         | 3.37%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 2.25%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 2.25%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 2.25%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 2.25%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 2.25%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 2.25%   |
| HP EliteBook 8460p                       | 2         | 2.25%   |
| Dell Latitude E6430                      | 2         | 2.25%   |
| Dell Latitude 5300                       | 2         | 2.25%   |
| TUXEDO N13xWU                            | 1         | 1.12%   |
| Toshiba Satellite Pro R50-C              | 1         | 1.12%   |
| Timi TM1707                              | 1         | 1.12%   |
| Sony VPCEB4L1R                           | 1         | 1.12%   |
| Sony VPCEB23FM                           | 1         | 1.12%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 1.12%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 1.12%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 1.12%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 1.12%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 1.12%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 1.12%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 1.12%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 1.12%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 1.12%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 1.12%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 1.12%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 1.12%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 1.12%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 1.12%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 1.12%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 1.12%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 1.12%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 1.12%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 1.12%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 1.12%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 1.12%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 1.12%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 1.12%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 1.12%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 1.12%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 1.12%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 1.12%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 1.12%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 1.12%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 1.12%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 1.12%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 1.12%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 1.12%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 1.12%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 1.12%   |
| Lenovo ThinkPad E490 20N8000JAD          | 1         | 1.12%   |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 1.12%   |
| HP ZBook Studio G5                       | 1         | 1.12%   |
| HP ZBook 15 G5                           | 1         | 1.12%   |
| HP ProBook 430 G5                        | 1         | 1.12%   |
| HP Pavilion 14                           | 1         | 1.12%   |
| HP OMEN by Laptop 15-dc1xxx              | 1         | 1.12%   |
| HP EliteBook 850 G7 Notebook PC          | 1         | 1.12%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.12%   |
| HP 250 G4 Notebook PC                    | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 51        | 57.3%   |
| Dell Latitude       | 8         | 8.99%   |
| HP EliteBook        | 4         | 4.49%   |
| Dell Precision      | 4         | 4.49%   |
| Dell Inspiron       | 3         | 3.37%   |
| HP ZBook            | 2         | 2.25%   |
| TUXEDO N13xWU       | 1         | 1.12%   |
| Toshiba Satellite   | 1         | 1.12%   |
| Timi TM1707         | 1         | 1.12%   |
| Sony VPCEB4L1R      | 1         | 1.12%   |
| Sony VPCEB23FM      | 1         | 1.12%   |
| Lenovo ThinkpadT460 | 1         | 1.12%   |
| HP ProBook          | 1         | 1.12%   |
| HP Pavilion         | 1         | 1.12%   |
| HP OMEN             | 1         | 1.12%   |
| HP 250              | 1         | 1.12%   |
| Dell XPS            | 1         | 1.12%   |
| Dell G3             | 1         | 1.12%   |
| ASUS Zephyrus       | 1         | 1.12%   |
| ASUS X550VX         | 1         | 1.12%   |
| ASUS TUF            | 1         | 1.12%   |
| ASUS GL502VMK       | 1         | 1.12%   |
| Acer Nitro          | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 23.6%   |
| 2019 | 20        | 22.47%  |
| 2018 | 14        | 15.73%  |
| 2011 | 7         | 7.87%   |
| 2017 | 6         | 6.74%   |
| 2016 | 5         | 5.62%   |
| 2015 | 5         | 5.62%   |
| 2012 | 4         | 4.49%   |
| 2010 | 3         | 3.37%   |
| 2021 | 2         | 2.25%   |
| 2013 | 2         | 2.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 89        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 78        | 86.67%  |
| Enabled  | 12        | 13.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 31        | 33.7%   |
| 16.01-24.0  | 17        | 18.48%  |
| 8.01-16.0   | 16        | 17.39%  |
| 4.01-8.0    | 15        | 16.3%   |
| 3.01-4.0    | 6         | 6.52%   |
| 64.01-256.0 | 6         | 6.52%   |
| 24.01-32.0  | 1         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 43        | 40.95%  |
| 8.01-16.0  | 18        | 17.14%  |
| 3.01-4.0   | 17        | 16.19%  |
| 2.01-3.0   | 13        | 12.38%  |
| 1.01-2.0   | 8         | 7.62%   |
| 16.01-24.0 | 3         | 2.86%   |
| 32.01-64.0 | 1         | 0.95%   |
| 24.01-32.0 | 1         | 0.95%   |
| 0.51-1.0   | 1         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 73.91%  |
| 2      | 15        | 16.3%   |
| 3      | 8         | 8.7%    |
| 4      | 1         | 1.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 86.67%  |
| Yes       | 12        | 13.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 90%     |
| No        | 9         | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 98.88%  |
| No        | 1         | 1.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 74.47%  |
| No        | 24        | 25.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 23.33%  |
| India        | 13        | 14.44%  |
| UK           | 5         | 5.56%   |
| Germany      | 5         | 5.56%   |
| France       | 5         | 5.56%   |
| Netherlands  | 3         | 3.33%   |
| Switzerland  | 2         | 2.22%   |
| South Africa | 2         | 2.22%   |
| Romania      | 2         | 2.22%   |
| Mexico       | 2         | 2.22%   |
| Japan        | 2         | 2.22%   |
| Czechia      | 2         | 2.22%   |
| Canada       | 2         | 2.22%   |
| Brazil       | 2         | 2.22%   |
| Australia    | 2         | 2.22%   |
| Spain        | 1         | 1.11%   |
| Singapore    | 1         | 1.11%   |
| Saudi Arabia | 1         | 1.11%   |
| Russia       | 1         | 1.11%   |
| Portugal     | 1         | 1.11%   |
| Poland       | 1         | 1.11%   |
| Pakistan     | 1         | 1.11%   |
| Nepal        | 1         | 1.11%   |
| Myanmar      | 1         | 1.11%   |
| Morocco      | 1         | 1.11%   |
| Luxembourg   | 1         | 1.11%   |
| Lithuania    | 1         | 1.11%   |
| Kuwait       | 1         | 1.11%   |
| Italy        | 1         | 1.11%   |
| Ireland      | 1         | 1.11%   |
| Ecuador      | 1         | 1.11%   |
| Colombia     | 1         | 1.11%   |
| Bulgaria     | 1         | 1.11%   |
| Armenia      | 1         | 1.11%   |
| Argentina    | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Munich                   | 3         | 3.03%   |
| Mumbai                   | 2         | 2.02%   |
| Mexico City              | 2         | 2.02%   |
| Doetinchem               | 2         | 2.02%   |
| Yerevan                  | 1         | 1.01%   |
| Webster                  | 1         | 1.01%   |
| Taringa                  | 1         | 1.01%   |
| Sumida                   | 1         | 1.01%   |
| Stroud                   | 1         | 1.01%   |
| Sofia                    | 1         | 1.01%   |
| Singapore                | 1         | 1.01%   |
| Sheffield                | 1         | 1.01%   |
| San Francisco            | 1         | 1.01%   |
| Sammamish                | 1         | 1.01%   |
| Sal?©                    | 1         | 1.01%   |
| Saint-Ismier             | 1         | 1.01%   |
| Saint-Alphonse-Rodriguez | 1         | 1.01%   |
| Sagaing                  | 1         | 1.01%   |
| Roudnice nad Labem       | 1         | 1.01%   |
| Roha                     | 1         | 1.01%   |
| Reims                    | 1         | 1.01%   |
| Raleigh                  | 1         | 1.01%   |
| Quito                    | 1         | 1.01%   |
| Queenscliff              | 1         | 1.01%   |
| Queens                   | 1         | 1.01%   |
| Pune                     | 1         | 1.01%   |
| Prague                   | 1         | 1.01%   |
| Portalegre               | 1         | 1.01%   |
| Port Elizabeth           | 1         | 1.01%   |
| Pleasanton               | 1         | 1.01%   |
| Pickerington             | 1         | 1.01%   |
| Paraiso do Tocantins     | 1         | 1.01%   |
| Paragould                | 1         | 1.01%   |
| Oyama                    | 1         | 1.01%   |
| Ottawa                   | 1         | 1.01%   |
| Ommen                    | 1         | 1.01%   |
| Ogden                    | 1         | 1.01%   |
| New Delhi                | 1         | 1.01%   |
| Neuves-Maisons           | 1         | 1.01%   |
| Mountain View            | 1         | 1.01%   |
| Moscow                   | 1         | 1.01%   |
| Miroslava                | 1         | 1.01%   |
| Milan                    | 1         | 1.01%   |
| Mangalore                | 1         | 1.01%   |
| Madrid                   | 1         | 1.01%   |
| Luxembourg               | 1         | 1.01%   |
| London                   | 1         | 1.01%   |
| Littleton                | 1         | 1.01%   |
| Lahore                   | 1         | 1.01%   |
| Kuwait City              | 1         | 1.01%   |
| Kochi                    | 1         | 1.01%   |
| Khobar                   | 1         | 1.01%   |
| Johnstone                | 1         | 1.01%   |
| Islamabad                | 1         | 1.01%   |
| Impflingen               | 1         | 1.01%   |
| Hyderabad                | 1         | 1.01%   |
| Houston                  | 1         | 1.01%   |
| Hosur                    | 1         | 1.01%   |
| Hobart                   | 1         | 1.01%   |
| Hetauda                  | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 43     | 25.22%  |
| WDC                 | 14        | 20     | 12.17%  |
| Toshiba             | 10        | 15     | 8.7%    |
| SK Hynix            | 10        | 10     | 8.7%    |
| Seagate             | 10        | 13     | 8.7%    |
| Sandisk             | 10        | 15     | 8.7%    |
| Intel               | 6         | 8      | 5.22%   |
| Unknown             | 5         | 7      | 4.35%   |
| Micron Technology   | 4         | 6      | 3.48%   |
| Kingston            | 3         | 3      | 2.61%   |
| HGST                | 3         | 3      | 2.61%   |
| Lenovo              | 2         | 2      | 1.74%   |
| A-DATA Technology   | 2         | 2      | 1.74%   |
| Team                | 1         | 2      | 0.87%   |
| SMI                 | 1         | 2      | 0.87%   |
| Silicon Motion      | 1         | 2      | 0.87%   |
| PNY                 | 1         | 4      | 0.87%   |
| Lite-On             | 1         | 1      | 0.87%   |
| Crucial             | 1         | 1      | 0.87%   |
| Corsair             | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 9         | 7.2%    |
| Sandisk NVMe SSD Drive 256GB            | 6         | 4.8%    |
| Samsung NVMe SSD Drive 256GB            | 5         | 4%      |
| Samsung NVMe SSD Drive 1024GB           | 5         | 4%      |
| Samsung NVMe SSD Drive 512GB            | 4         | 3.2%    |
| Toshiba NVMe SSD Drive 512GB            | 3         | 2.4%    |
| Micron NVMe SSD Drive 256GB             | 3         | 2.4%    |
| Unknown NVMe SSD Drive 256GB            | 2         | 1.6%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 1.6%    |
| Seagate Expansion 1TB                   | 2         | 1.6%    |
| Samsung SSD 860 EVO 1TB                 | 2         | 1.6%    |
| Samsung Portable SSD T5 500GB           | 2         | 1.6%    |
| Samsung NVMe SSD Drive 2TB              | 2         | 1.6%    |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.6%    |
| Intel NVMe SSD Drive 512GB              | 2         | 1.6%    |
| Intel NVMe SSD Drive 2TB                | 2         | 1.6%    |
| HGST HTS721010A9E630 1TB                | 2         | 1.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.8%    |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.8%    |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.8%    |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.8%    |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.8%    |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.8%    |
| WDC WD20 SPZX-11UA7T0 2TB               | 1         | 0.8%    |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.8%    |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.8%    |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.8%    |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.8%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.8%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.8%    |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.8%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.8%    |
| Unknown MMC Card  33GB                  | 1         | 0.8%    |
| Unknown MMC Card  32GB                  | 1         | 0.8%    |
| Unknown MMC Card  16GB                  | 1         | 0.8%    |
| Toshiba TR150 960GB SSD                 | 1         | 0.8%    |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.8%    |
| Toshiba MQ01ABD075 752GB                | 1         | 0.8%    |
| Toshiba MK3275GSX 320GB                 | 1         | 0.8%    |
| Toshiba HDWL110 1TB                     | 1         | 0.8%    |
| Team T253X2512G 512GB SSD               | 1         | 0.8%    |
| SMI DISK 506GB                          | 1         | 0.8%    |
| SK Hynix NVMe SSD Drive 1024GB          | 1         | 0.8%    |
| Silicon Motion NVMe SSD Drive 1TB       | 1         | 0.8%    |
| Seagate ST9320325AS 320GB               | 1         | 0.8%    |
| Seagate ST9160827AS 160GB               | 1         | 0.8%    |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.8%    |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.8%    |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.8%    |
| Seagate BUP Slim BK 1TB                 | 1         | 0.8%    |
| Seagate BUP Portable 5TB                | 1         | 0.8%    |
| Seagate BUP BL 4TB                      | 1         | 0.8%    |
| Seagate BarraCuda SSD ZA2000CM10002 2TB | 1         | 0.8%    |
| SanDisk SDSSDH31024G 1TB                | 1         | 0.8%    |
| SanDisk SD7SN6S-256G-1006 256GB SSD     | 1         | 0.8%    |
| SanDisk SD7SB7S512G1001 512GB SSD       | 1         | 0.8%    |
| Sandisk NVMe SSD Drive 512GB            | 1         | 0.8%    |
| SanDisk Extreme SSD 500GB               | 1         | 0.8%    |
| Samsung SSD PM830 2.5 7mm 256GB         | 1         | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 41.67%  |
| WDC     | 8         | 12     | 33.33%  |
| Toshiba | 3         | 5      | 12.5%   |
| HGST    | 3         | 3      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 40%     |
| WDC                 | 3         | 4      | 10%     |
| SanDisk             | 3         | 4      | 10%     |
| Kingston            | 3         | 3      | 10%     |
| A-DATA Technology   | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| Team                | 1         | 2      | 3.33%   |
| Seagate             | 1         | 1      | 3.33%   |
| PNY                 | 1         | 4      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| Corsair             | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 58        | 85     | 50.88%  |
| SSD     | 28        | 37     | 24.56%  |
| HDD     | 24        | 32     | 21.05%  |
| MMC     | 3         | 4      | 2.63%   |
| Unknown | 1         | 2      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 58        | 85     | 54.21%  |
| SATA | 38        | 62     | 35.51%  |
| SAS  | 8         | 9      | 7.48%   |
| MMC  | 3         | 4      | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 32     | 49.02%  |
| 0.51-1.0   | 18        | 29     | 35.29%  |
| 1.01-2.0   | 5         | 5      | 9.8%    |
| 3.01-4.0   | 2         | 2      | 3.92%   |
| 4.01-10.0  | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 44.57%  |
| 251-500        | 16        | 17.39%  |
| 501-1000       | 13        | 14.13%  |
| 1001-2000      | 8         | 8.7%    |
| More than 3000 | 5         | 5.43%   |
| 21-50          | 3         | 3.26%   |
| 51-100         | 3         | 3.26%   |
| 2001-3000      | 1         | 1.09%   |
| 1-20           | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 24        | 23.76%  |
| 101-250        | 23        | 22.77%  |
| 1-20           | 19        | 18.81%  |
| 51-100         | 15        | 14.85%  |
| 251-500        | 9         | 8.91%   |
| 501-1000       | 7         | 6.93%   |
| More than 3000 | 1         | 0.99%   |
| 2001-3000      | 1         | 0.99%   |
| 1001-2000      | 1         | 0.99%   |
| Unknown        | 1         | 0.99%   |

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
| Detected | 78        | 138    | 82.98%  |
| Works    | 16        | 22     | 17.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 49        | 47.12%  |
| Samsung Electronics          | 19        | 18.27%  |
| SK Hynix                     | 10        | 9.62%   |
| Sandisk                      | 10        | 9.62%   |
| Toshiba America Info Systems | 6         | 5.77%   |
| Micron Technology            | 3         | 2.88%   |
| Lenovo                       | 2         | 1.92%   |
| KIOXIA                       | 2         | 1.92%   |
| Silicon Motion               | 1         | 0.96%   |
| Lite-On Technology           | 1         | 0.96%   |
| AMD                          | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 15        | 14.15%  |
| SK Hynix Non-Volatile memory controller                                       | 10        | 9.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 8.49%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 7         | 6.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 5.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 5         | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.77%   |
| Micron Non-Volatile memory controller                                         | 3         | 2.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.83%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.83%   |
| Intel SSD 660P Series                                                         | 3         | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 2.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 2.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.89%   |
| Lenovo Non-Volatile memory controller                                         | 2         | 1.89%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 1.89%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 0.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 0.94%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.94%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.94%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 0.94%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.94%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 0.94%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 58        | 55.77%  |
| SATA | 42        | 40.38%  |
| RAID | 4         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 95.51%  |
| AMD    | 4         | 4.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 10.11%  |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 8.99%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 5         | 5.62%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 4.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 3.37%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 3.37%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 2.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 2.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 2.25%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 2.25%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.25%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.25%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 2.25%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 1.12%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 1.12%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 1.12%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 1.12%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 1.12%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.12%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.12%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.12%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 1.12%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.12%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.12%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.12%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.12%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.12%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.12%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.12%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.12%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.12%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 52        | 58.43%  |
| Intel Core i5   | 22        | 24.72%  |
| Intel Xeon      | 4         | 4.49%   |
| Intel Core i3   | 3         | 3.37%   |
| AMD Ryzen 7     | 3         | 3.37%   |
| Other           | 2         | 2.25%   |
| Intel Core i9   | 2         | 2.25%   |
| AMD Ryzen 7 PRO | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 42        | 47.19%  |
| 2      | 24        | 26.97%  |
| 6      | 18        | 20.22%  |
| 8      | 5         | 5.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 89        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 87        | 97.75%  |
| 1      | 2         | 2.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 87        | 95.6%   |
| Unknown        | 4         | 4.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 20        | 21.98%  |
| 0x806ea    | 10        | 10.99%  |
| 0xa0652    | 9         | 9.89%   |
| 0x906ea    | 7         | 7.69%   |
| 0x206a7    | 6         | 6.59%   |
| 0x306a9    | 5         | 5.49%   |
| 0x906ed    | 4         | 4.4%    |
| 0x506e3    | 4         | 4.4%    |
| 0x406e3    | 4         | 4.4%    |
| 0x806e9    | 3         | 3.3%    |
| 0x306d4    | 3         | 3.3%    |
| 0x20655    | 3         | 3.3%    |
| Unknown    | 3         | 3.3%    |
| 0x906e9    | 2         | 2.2%    |
| 0x08108102 | 2         | 2.2%    |
| 0x806d1    | 1         | 1.1%    |
| 0x806c1    | 1         | 1.1%    |
| 0x40651    | 1         | 1.1%    |
| 0x20652    | 1         | 1.1%    |
| 0x08600104 | 1         | 1.1%    |
| 0x08600103 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 47        | 52.22%  |
| CometLake   | 9         | 10%     |
| Skylake     | 8         | 8.89%   |
| SandyBridge | 6         | 6.67%   |
| IvyBridge   | 5         | 5.56%   |
| Westmere    | 4         | 4.44%   |
| Broadwell   | 3         | 3.33%   |
| Zen+        | 2         | 2.22%   |
| Zen 2       | 2         | 2.22%   |
| TigerLake   | 1         | 1.11%   |
| Icelake     | 1         | 1.11%   |
| Haswell     | 1         | 1.11%   |
| Unknown     | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 66.96%  |
| Nvidia | 26        | 23.21%  |
| AMD    | 11        | 9.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 14        | 12.5%   |
| Intel UHD Graphics 620                                                                | 10        | 8.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 7.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 6.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 4.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 3.57%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 2.68%   |
| Intel HD Graphics 620                                                                 | 3         | 2.68%   |
| Intel HD Graphics 5500                                                                | 3         | 2.68%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.79%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 2         | 1.79%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 2         | 1.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 1.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 1.79%   |
| AMD Renoir                                                                            | 2         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.89%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.89%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.89%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.89%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.89%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.89%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.89%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 0.89%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 0.89%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.89%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                                    | 1         | 0.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 0.89%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 0.89%   |
| Intel HD Graphics P530                                                                | 1         | 0.89%   |
| Intel HD Graphics 630                                                                 | 1         | 0.89%   |
| Intel HD Graphics 530                                                                 | 1         | 0.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.89%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 0.89%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 0.89%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 60%     |
| Intel + Nvidia | 17        | 18.89%  |
| 1 x Nvidia     | 8         | 8.89%   |
| 1 x AMD        | 5         | 5.56%   |
| Intel + AMD    | 4         | 4.44%   |
| AMD + Nvidia   | 2         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 86.67%  |
| Proprietary | 9         | 10%     |
| Unknown     | 3         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 68.89%  |
| 3.01-4.0   | 8         | 8.89%   |
| 1.01-2.0   | 7         | 7.78%   |
| 0.51-1.0   | 5         | 5.56%   |
| 5.01-6.0   | 4         | 4.44%   |
| 0.01-0.5   | 2         | 2.22%   |
| 7.01-8.0   | 1         | 1.11%   |
| 8.01-16.0  | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 14.96%  |
| Chimei Innolux          | 15        | 11.81%  |
| BOE                     | 15        | 11.81%  |
| LG Display              | 14        | 11.02%  |
| Dell                    | 13        | 10.24%  |
| Samsung Electronics     | 9         | 7.09%   |
| Lenovo                  | 9         | 7.09%   |
| Hewlett-Packard         | 5         | 3.94%   |
| Sharp                   | 4         | 3.15%   |
| InfoVision              | 4         | 3.15%   |
| Goldstar                | 4         | 3.15%   |
| Acer                    | 3         | 2.36%   |
| Philips                 | 2         | 1.57%   |
| PANDA                   | 2         | 1.57%   |
| LGD                     | 2         | 1.57%   |
| Sun                     | 1         | 0.79%   |
| Sceptre Tech            | 1         | 0.79%   |
| Planar                  | 1         | 0.79%   |
| Eizo                    | 1         | 0.79%   |
| Chi Mei Optoelectronics | 1         | 0.79%   |
| BOE Technology Group    | 1         | 0.79%   |
| AOC                     | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 3.79%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 3.03%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 2.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 2.27%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 2.27%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 2.27%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.52%   |
| PANDA LCD Monitor NCP0036 1920x1080 340x190mm 15.3-inch               | 2         | 1.52%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.52%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.52%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.52%   |
| Hewlett-Packard 27y HPN351C 1920x1080 598x336mm 27.0-inch             | 2         | 1.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2         | 1.52%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.52%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.52%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.76%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.76%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.76%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.76%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.76%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.76%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.76%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.76%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.76%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.76%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.76%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 698x393mm 31.5-inch    | 1         | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.76%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.76%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.76%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 1         | 0.76%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.76%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.76%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 1         | 0.76%   |
| Hewlett-Packard Pavilion32 HWP3338 2560x1440 708x399mm 32.0-inch      | 1         | 0.76%   |
| Hewlett-Packard LCD Monitor Pavilion32 6400x2160                      | 1         | 0.76%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 0.76%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch             | 1         | 0.76%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 0.76%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1         | 0.76%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 0.76%   |
| Eizo EV2416W ENC2389 1920x1200 519x324mm 24.1-inch                    | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 61        | 56.48%  |
| 1366x768 (WXGA)    | 14        | 12.96%  |
| 3840x2160 (4K)     | 7         | 6.48%   |
| 1600x900 (HD+)     | 7         | 6.48%   |
| 2560x1440 (QHD)    | 6         | 5.56%   |
| 2560x1080          | 3         | 2.78%   |
| 1920x1200 (WUXGA)  | 3         | 2.78%   |
| 6400x2160          | 1         | 0.93%   |
| 3840x1080          | 1         | 0.93%   |
| 2048x1152          | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1440x900 (WXGA+)   | 1         | 0.93%   |
| 1280x800 (WXGA)    | 1         | 0.93%   |
| Unknown            | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 30.95%  |
| 14      | 21        | 16.67%  |
| 13      | 14        | 11.11%  |
| 24      | 13        | 10.32%  |
| 27      | 10        | 7.94%   |
| 23      | 6         | 4.76%   |
| 12      | 5         | 3.97%   |
| 34      | 3         | 2.38%   |
| 17      | 3         | 2.38%   |
| Unknown | 3         | 2.38%   |
| 31      | 2         | 1.59%   |
| 21      | 2         | 1.59%   |
| 49      | 1         | 0.79%   |
| 32      | 1         | 0.79%   |
| 22      | 1         | 0.79%   |
| 19      | 1         | 0.79%   |
| 18      | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 57.72%  |
| 501-600     | 23        | 18.7%   |
| 201-300     | 8         | 6.5%    |
| 601-700     | 5         | 4.07%   |
| 401-500     | 5         | 4.07%   |
| 701-800     | 4         | 3.25%   |
| 351-400     | 3         | 2.44%   |
| Unknown     | 3         | 2.44%   |
| 1001-1500   | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 84.54%  |
| 16/10   | 7         | 7.22%   |
| 21/9    | 3         | 3.09%   |
| Unknown | 3         | 3.09%   |
| 32/9    | 1         | 1.03%   |
| 3/2     | 1         | 1.03%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 31.2%   |
| 81-90          | 32        | 25.6%   |
| 201-250        | 15        | 12%     |
| 301-350        | 10        | 8%      |
| 251-300        | 7         | 5.6%    |
| 61-70          | 5         | 4%      |
| 351-500        | 5         | 4%      |
| 71-80          | 3         | 2.4%    |
| 121-130        | 3         | 2.4%    |
| Unknown        | 3         | 2.4%    |
| 151-200        | 1         | 0.8%    |
| 141-150        | 1         | 0.8%    |
| 501-1000       | 1         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 64        | 52.89%  |
| 51-100        | 28        | 23.14%  |
| 101-120       | 18        | 14.88%  |
| More than 240 | 4         | 3.31%   |
| 161-240       | 4         | 3.31%   |
| Unknown       | 3         | 2.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 55        | 57.89%  |
| 2     | 30        | 31.58%  |
| 3     | 6         | 6.32%   |
| 0     | 4         | 4.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 58.09%  |
| Realtek Semiconductor             | 25        | 18.38%  |
| Lenovo                            | 14        | 10.29%  |
| Qualcomm Atheros                  | 3         | 2.21%   |
| Marvell Technology Group          | 2         | 1.47%   |
| Broadcom Limited                  | 2         | 1.47%   |
| Xiaomi                            | 1         | 0.74%   |
| Sierra Wireless                   | 1         | 0.74%   |
| Samsung Electronics               | 1         | 0.74%   |
| Ralink                            | 1         | 0.74%   |
| Luminary Micro                    | 1         | 0.74%   |
| ICS Advent                        | 1         | 0.74%   |
| Huawei Technologies               | 1         | 0.74%   |
| Ericsson Business Mobile Networks | 1         | 0.74%   |
| DisplayLink                       | 1         | 0.74%   |
| Dell                              | 1         | 0.74%   |
| Broadcom                          | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 6.81%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 12        | 6.28%   |
| Intel Wireless 8265 / 8275                                                     | 12        | 6.28%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 5.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 5.24%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 9         | 4.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 4.19%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 3.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 7         | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 3.66%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 3.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 3.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.62%   |
| Intel Wireless 8260                                                            | 5         | 2.62%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 2.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2.09%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 2.09%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 2.09%   |
| Intel Wireless 7265                                                            | 3         | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.05%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.05%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.05%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.05%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.05%   |
| Intel Wireless 3165                                                            | 2         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.05%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.52%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.52%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.52%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.52%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.52%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.52%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.52%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.52%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.52%   |
| Huawei E353/E3131                                                              | 1         | 0.52%   |
| Ericsson Business Mobile Networks N5321 gw                                     | 1         | 0.52%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.52%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                           | 1         | 0.52%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 85.71%  |
| Realtek Semiconductor | 5         | 5.49%   |
| Qualcomm Atheros      | 3         | 3.3%    |
| Sierra Wireless       | 1         | 1.1%    |
| Ralink                | 1         | 1.1%    |
| Dell                  | 1         | 1.1%    |
| Broadcom Limited      | 1         | 1.1%    |
| Broadcom              | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 14.29%  |
| Intel Wireless 8265 / 8275                                     | 12        | 13.19%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 9.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 6.59%   |
| Intel Wireless 8260                                            | 5         | 5.49%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 5.49%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 4.4%    |
| Intel Wireless 7265                                            | 3         | 3.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 2.2%    |
| Intel Wireless-AC 9260                                         | 2         | 2.2%    |
| Intel Wireless 3165                                            | 2         | 2.2%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.1%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.1%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.1%    |
| Dell DW5811e Snapdragon???„?? X7 LTE                           | 1         | 1.1%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 55        | 56.12%  |
| Realtek Semiconductor    | 21        | 21.43%  |
| Lenovo                   | 14        | 14.29%  |
| Marvell Technology Group | 2         | 2.04%   |
| Xiaomi                   | 1         | 1.02%   |
| Samsung Electronics      | 1         | 1.02%   |
| ICS Advent               | 1         | 1.02%   |
| Huawei Technologies      | 1         | 1.02%   |
| DisplayLink              | 1         | 1.02%   |
| Broadcom Limited         | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 12        | 12.24%  |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 10.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 10.2%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 8.16%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 7.14%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 6.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 5.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 4.08%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 4.08%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.06%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.04%   |
| Lenovo USB-C to LAN                                                            | 2         | 2.04%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.04%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 2.04%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.02%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 1.02%   |
| Lenovo ThinkPad Lan                                                            | 1         | 1.02%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 1.02%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.02%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.02%   |
| Huawei E353/E3131                                                              | 1         | 1.02%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 1.02%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 51.46%  |
| Ethernet | 81        | 47.37%  |
| Modem    | 2         | 1.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 52.9%   |
| Ethernet | 73        | 47.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 82.02%  |
| 1     | 16        | 17.98%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 92.22%  |
| Yes  | 7         | 7.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 81.43%  |
| Broadcom                        | 5         | 7.14%   |
| IMC Networks                    | 2         | 2.86%   |
| Cambridge Silicon Radio         | 2         | 2.86%   |
| Ralink                          | 1         | 1.43%   |
| Qualcomm Atheros Communications | 1         | 1.43%   |
| Foxconn / Hon Hai               | 1         | 1.43%   |
| Dell                            | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 26        | 37.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 22.86%  |
| Intel Bluetooth wireless interface                                                  | 12        | 17.14%  |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.86%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.43%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.43%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.43%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.43%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 85        | 61.59%  |
| Nvidia                 | 16        | 11.59%  |
| Lenovo                 | 12        | 8.7%    |
| AMD                    | 7         | 5.07%   |
| Plantronics            | 3         | 2.17%   |
| GN Netcom              | 3         | 2.17%   |
| Texas Instruments      | 2         | 1.45%   |
| Realtek Semiconductor  | 2         | 1.45%   |
| Generalplus Technology | 2         | 1.45%   |
| Logitech               | 1         | 0.72%   |
| JMTek                  | 1         | 0.72%   |
| Google                 | 1         | 0.72%   |
| Focusrite-Novation     | 1         | 0.72%   |
| Dell                   | 1         | 0.72%   |
| C-Media Electronics    | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 17        | 11.72%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 14        | 9.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 7.59%   |
| Intel Comet Lake PCH cAVS                                                         | 9         | 6.21%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 7         | 4.83%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.76%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 4         | 2.76%   |
| Plantronics BT600                                                                 | 3         | 2.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 2.07%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 2.07%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.38%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.38%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.38%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 1.38%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.69%   |
| Logitech H555 Headset                                                             | 1         | 0.69%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.69%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.69%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.69%   |
| JMTek iTalk-02                                                                    | 1         | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.69%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 0.69%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 0.69%   |
| Google Pixel USB-C earbuds                                                        | 1         | 0.69%   |
| GN Netcom Jabra Link 380                                                          | 1         | 0.69%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                   | 1         | 0.69%   |
| GN Netcom Jabra BIZ 2400 USB                                                      | 1         | 0.69%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.69%   |
| Generalplus Technology Usb Audio Device                                           | 1         | 0.69%   |
| Focusrite-Novation Scarlett 2i2 Camera                                            | 1         | 0.69%   |
| Dell AC511 USB SoundBar                                                           | 1         | 0.69%   |
| C-Media Electronics Blue Snowball                                                 | 1         | 0.69%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 41.38%  |
| SK Hynix            | 9         | 31.03%  |
| Unknown             | 2         | 6.9%    |
| Kingston            | 2         | 6.9%    |
| Crucial             | 2         | 6.9%    |
| Smart               | 1         | 3.45%   |
| Micron Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 6.9%    |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 3.45%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 3.45%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 3.45%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.45%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.45%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 3.45%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 3.45%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 3.45%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 3.45%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 3.45%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 3.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 3.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 3.45%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 3.45%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 3.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 3.45%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 3.45%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 3.45%   |
| Kingston RAM KHX2400C14S4/8G 8192MB SODIMM DDR4 2400MT/s     | 1         | 3.45%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 3.45%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s   | 1         | 3.45%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 50%     |
| DDR3   | 9         | 40.91%  |
| LPDDR4 | 1         | 4.55%   |
| LPDDR3 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 95.24%  |
| Row Of Chips | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 8         | 36.36%  |
| 16384 | 7         | 31.82%  |
| 8192  | 6         | 27.27%  |
| 32768 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 29.17%  |
| 1600  | 6         | 25%     |
| 3200  | 3         | 12.5%   |
| 1333  | 3         | 12.5%   |
| 2400  | 2         | 8.33%   |
| 2133  | 2         | 8.33%   |
| 1334  | 1         | 4.17%   |

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
| Chicony Electronics                    | 31        | 32.98%  |
| IMC Networks                           | 12        | 12.77%  |
| Acer                                   | 11        | 11.7%   |
| Realtek Semiconductor                  | 8         | 8.51%   |
| Logitech                               | 7         | 7.45%   |
| Sunplus Innovation Technology          | 6         | 6.38%   |
| Microdia                               | 6         | 6.38%   |
| Suyin                                  | 3         | 3.19%   |
| Lite-On Technology                     | 3         | 3.19%   |
| Samsung Electronics                    | 2         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.13%   |
| Unknown                                | 1         | 1.06%   |
| Quanta                                 | 1         | 1.06%   |
| Lenovo                                 | 1         | 1.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 18        | 18.75%  |
| IMC Networks Integrated Camera                               | 10        | 10.42%  |
| Acer Integrated Camera                                       | 8         | 8.33%   |
| Realtek Integrated_Webcam_HD                                 | 6         | 6.25%   |
| Logitech HD Pro Webcam C920                                  | 4         | 4.17%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 3.13%   |
| Lite-On Integrated Camera                                    | 3         | 3.13%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 3.13%   |
| Chicony HP HD Camera                                         | 3         | 3.13%   |
| Acer SunplusIT Integrated Camera                             | 3         | 3.13%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 2.08%   |
| Microdia Webcam                                              | 2         | 2.08%   |
| Microdia Integrated Webcam                                   | 2         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 2.08%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 2.08%   |
| Unknown FULL HD 1080P Webcam                                 | 1         | 1.04%   |
| Suyin RGBIR Camera                                           | 1         | 1.04%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 1.04%   |
| Suyin HP Truevision HD                                       | 1         | 1.04%   |
| Sunplus USB2.0 Camera                                        | 1         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.04%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 1.04%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 1.04%   |
| Realtek NexiGo N660P FHD Webcam                              | 1         | 1.04%   |
| Quanta HP HD Camera                                          | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 1.04%   |
| Logitech Webcam C925e                                        | 1         | 1.04%   |
| Logitech Webcam C310                                         | 1         | 1.04%   |
| Logitech B525 HD Webcam                                      | 1         | 1.04%   |
| Lenovo Integrated Webcam                                     | 1         | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 1.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.04%   |
| Chicony Integrated IR Camera                                 | 1         | 1.04%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.04%   |
| Chicony HP Webcam                                            | 1         | 1.04%   |
| Chicony HD User Facing                                       | 1         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera          | 1         | 1.04%   |
| Acer Integrated IR Camera                                    | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 24        | 61.54%  |
| Validity Sensors      | 12        | 30.77%  |
| Upek                  | 2         | 5.13%   |
| Elan Microelectronics | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 46.15%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 10.26%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.56%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.56%   |

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
| 1     | 48        | 53.93%  |
| 0     | 32        | 35.96%  |
| 2     | 8         | 8.99%   |
| 3     | 1         | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 39        | 57.35%  |
| Graphics card         | 10        | 14.71%  |
| Chipcard              | 10        | 14.71%  |
| Net/wireless          | 2         | 2.94%   |
| Net/ethernet          | 2         | 2.94%   |
| Bluetooth             | 2         | 2.94%   |
| Storage               | 1         | 1.47%   |
| Multimedia controller | 1         | 1.47%   |
| Card reader           | 1         | 1.47%   |

