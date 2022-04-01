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

Total: 176

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell    | Precision 7560              | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo  | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| Lenovo  | ThinkPad X1 Yoga 1st 20F... | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
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
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 8.55%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 9         | 7.69%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 6.84%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 6.84%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 5.98%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 5         | 4.27%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 3.42%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 3.42%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 3.42%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 3.42%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 3.42%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 3.42%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.56%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.56%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.56%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 2.56%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.56%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.56%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.56%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 2.56%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.56%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.71%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.71%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.71%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.85%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.85%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.85%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 1         | 0.85%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1         | 0.85%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 0.85%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.85%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.85%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.85%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.85%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 1         | 0.85%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 0.85%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 93        | 98.94%  |
| 5.9.1   | 1         | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 93        | 98.94%  |
| 5.9     | 1         | 1.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 83        | 84.69%  |
| Unknown       | 8         | 8.16%   |
| GNOME Classic | 5         | 5.1%    |
| KDE5          | 2         | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 57        | 58.16%  |
| Wayland | 37        | 37.76%  |
| Unknown | 4         | 4.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 84.54%  |
| GDM     | 15        | 15.46%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 67        | 69.07%  |
| Unknown | 7         | 7.22%   |
| fr_FR   | 4         | 4.12%   |
| en_GB   | 4         | 4.12%   |
| pt_BR   | 2         | 2.06%   |
| pl_PL   | 2         | 2.06%   |
| nl_NL   | 2         | 2.06%   |
| en_IN   | 2         | 2.06%   |
| ru_RU   | 1         | 1.03%   |
| ja_JP   | 1         | 1.03%   |
| it_IT   | 1         | 1.03%   |
| es_EC   | 1         | 1.03%   |
| en_IE   | 1         | 1.03%   |
| de_DE   | 1         | 1.03%   |
| de_CH   | 1         | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 79.38%  |
| BIOS | 20        | 20.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 84        | 89.36%  |
| Ext4 | 10        | 10.64%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 81.44%  |
| GPT     | 17        | 17.53%  |
| MBR     | 1         | 1.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 98.94%  |
| Yes       | 1         | 1.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 94.74%  |
| Yes       | 5         | 5.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 56        | 59.57%  |
| Dell             | 18        | 19.15%  |
| Hewlett-Packard  | 10        | 10.64%  |
| ASUSTek Computer | 4         | 4.26%   |
| Sony             | 2         | 2.13%   |
| TUXEDO           | 1         | 1.06%   |
| Toshiba          | 1         | 1.06%   |
| Timi             | 1         | 1.06%   |
| Acer             | 1         | 1.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 4.26%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 2.13%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 2.13%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 2.13%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 2.13%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 2.13%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 2.13%   |
| HP EliteBook 8460p                       | 2         | 2.13%   |
| Dell Latitude E6430                      | 2         | 2.13%   |
| Dell Latitude 5300                       | 2         | 2.13%   |
| TUXEDO N13xWU                            | 1         | 1.06%   |
| Toshiba Satellite Pro R50-C              | 1         | 1.06%   |
| Timi TM1707                              | 1         | 1.06%   |
| Sony VPCEB4L1R                           | 1         | 1.06%   |
| Sony VPCEB23FM                           | 1         | 1.06%   |
| Lenovo Z40-70 20366                      | 1         | 1.06%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 1.06%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 1.06%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 1.06%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 1.06%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 1.06%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 1.06%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 1.06%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 1.06%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 1.06%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 1.06%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 1.06%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 1.06%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 1.06%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 1.06%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 1.06%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 1.06%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 1.06%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 1.06%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 1.06%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 1.06%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 1.06%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N    | 1         | 1.06%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 1.06%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 1.06%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 1.06%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 1.06%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 1.06%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 1.06%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 1.06%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 1.06%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 1.06%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 1.06%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 1.06%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 1.06%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 1.06%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 1.06%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 1.06%   |
| Lenovo ThinkPad E490 20N8000JAD          | 1         | 1.06%   |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 1.06%   |
| HP ZBook Studio G5                       | 1         | 1.06%   |
| HP ZBook 15 G5                           | 1         | 1.06%   |
| HP ProBook 430 G5                        | 1         | 1.06%   |
| HP Pavilion 14                           | 1         | 1.06%   |
| HP OMEN by Laptop 15-dc1xxx              | 1         | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 54        | 57.45%  |
| Dell Latitude       | 8         | 8.51%   |
| Dell Precision      | 5         | 5.32%   |
| HP EliteBook        | 4         | 4.26%   |
| Dell Inspiron       | 3         | 3.19%   |
| HP ZBook            | 2         | 2.13%   |
| TUXEDO N13xWU       | 1         | 1.06%   |
| Toshiba Satellite   | 1         | 1.06%   |
| Timi TM1707         | 1         | 1.06%   |
| Sony VPCEB4L1R      | 1         | 1.06%   |
| Sony VPCEB23FM      | 1         | 1.06%   |
| Lenovo Z40-70       | 1         | 1.06%   |
| Lenovo ThinkpadT460 | 1         | 1.06%   |
| HP ProBook          | 1         | 1.06%   |
| HP Pavilion         | 1         | 1.06%   |
| HP OMEN             | 1         | 1.06%   |
| HP 250              | 1         | 1.06%   |
| Dell XPS            | 1         | 1.06%   |
| Dell G3             | 1         | 1.06%   |
| ASUS Zephyrus       | 1         | 1.06%   |
| ASUS X550VX         | 1         | 1.06%   |
| ASUS TUF            | 1         | 1.06%   |
| ASUS GL502VMK       | 1         | 1.06%   |
| Acer Nitro          | 1         | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 22        | 23.4%   |
| 2019 | 21        | 22.34%  |
| 2018 | 13        | 13.83%  |
| 2017 | 7         | 7.45%   |
| 2015 | 7         | 7.45%   |
| 2011 | 7         | 7.45%   |
| 2016 | 5         | 5.32%   |
| 2012 | 4         | 4.26%   |
| 2021 | 3         | 3.19%   |
| 2010 | 3         | 3.19%   |
| 2013 | 2         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 94        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 82        | 86.32%  |
| Enabled  | 13        | 13.68%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 33        | 34.02%  |
| 16.01-24.0  | 19        | 19.59%  |
| 8.01-16.0   | 17        | 17.53%  |
| 4.01-8.0    | 15        | 15.46%  |
| 3.01-4.0    | 6         | 6.19%   |
| 64.01-256.0 | 6         | 6.19%   |
| 24.01-32.0  | 1         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 45        | 40.91%  |
| 8.01-16.0  | 20        | 18.18%  |
| 3.01-4.0   | 17        | 15.45%  |
| 2.01-3.0   | 14        | 12.73%  |
| 1.01-2.0   | 8         | 7.27%   |
| 16.01-24.0 | 3         | 2.73%   |
| 32.01-64.0 | 1         | 0.91%   |
| 24.01-32.0 | 1         | 0.91%   |
| 0.51-1.0   | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 74.49%  |
| 2      | 16        | 16.33%  |
| 3      | 8         | 8.16%   |
| 4      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 86.32%  |
| Yes       | 13        | 13.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 89.47%  |
| No        | 10        | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 97.87%  |
| No        | 2         | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 74.75%  |
| No        | 25        | 25.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 23        | 24.21%  |
| India        | 13        | 13.68%  |
| UK           | 5         | 5.26%   |
| Germany      | 5         | 5.26%   |
| France       | 5         | 5.26%   |
| Netherlands  | 3         | 3.16%   |
| Mexico       | 3         | 3.16%   |
| Switzerland  | 2         | 2.11%   |
| South Africa | 2         | 2.11%   |
| Romania      | 2         | 2.11%   |
| Japan        | 2         | 2.11%   |
| Czechia      | 2         | 2.11%   |
| Canada       | 2         | 2.11%   |
| Brazil       | 2         | 2.11%   |
| Australia    | 2         | 2.11%   |
| Spain        | 1         | 1.05%   |
| Singapore    | 1         | 1.05%   |
| Saudi Arabia | 1         | 1.05%   |
| Russia       | 1         | 1.05%   |
| Portugal     | 1         | 1.05%   |
| Poland       | 1         | 1.05%   |
| Pakistan     | 1         | 1.05%   |
| Nepal        | 1         | 1.05%   |
| Myanmar      | 1         | 1.05%   |
| Morocco      | 1         | 1.05%   |
| Luxembourg   | 1         | 1.05%   |
| Lithuania    | 1         | 1.05%   |
| Kuwait       | 1         | 1.05%   |
| Italy        | 1         | 1.05%   |
| Israel       | 1         | 1.05%   |
| Ireland      | 1         | 1.05%   |
| Georgia      | 1         | 1.05%   |
| Ecuador      | 1         | 1.05%   |
| Colombia     | 1         | 1.05%   |
| Bulgaria     | 1         | 1.05%   |
| Armenia      | 1         | 1.05%   |
| Argentina    | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Munich                   | 3         | 2.88%   |
| Mexico City              | 3         | 2.88%   |
| Mumbai                   | 2         | 1.92%   |
| Doetinchem               | 2         | 1.92%   |
| Yerevan                  | 1         | 0.96%   |
| Webster                  | 1         | 0.96%   |
| Taringa                  | 1         | 0.96%   |
| Sumida                   | 1         | 0.96%   |
| Stroud                   | 1         | 0.96%   |
| Sofia                    | 1         | 0.96%   |
| Singapore                | 1         | 0.96%   |
| Sheffield                | 1         | 0.96%   |
| San Francisco            | 1         | 0.96%   |
| Sammamish                | 1         | 0.96%   |
| SalÃ©                  | 1         | 0.96%   |
| Saint-Ismier             | 1         | 0.96%   |
| Saint-Alphonse-Rodriguez | 1         | 0.96%   |
| Sagaing                  | 1         | 0.96%   |
| Roudnice nad Labem       | 1         | 0.96%   |
| Roha                     | 1         | 0.96%   |
| Rochester                | 1         | 0.96%   |
| Reims                    | 1         | 0.96%   |
| Raleigh                  | 1         | 0.96%   |
| Quito                    | 1         | 0.96%   |
| Queenscliff              | 1         | 0.96%   |
| Queens                   | 1         | 0.96%   |
| Pune                     | 1         | 0.96%   |
| Prague                   | 1         | 0.96%   |
| Portalegre               | 1         | 0.96%   |
| Port Elizabeth           | 1         | 0.96%   |
| Pleasanton               | 1         | 0.96%   |
| Pickerington             | 1         | 0.96%   |
| Paraiso do Tocantins     | 1         | 0.96%   |
| Paragould                | 1         | 0.96%   |
| Oyama                    | 1         | 0.96%   |
| Ottawa                   | 1         | 0.96%   |
| Ommen                    | 1         | 0.96%   |
| Ogden                    | 1         | 0.96%   |
| New Delhi                | 1         | 0.96%   |
| Neuves-Maisons           | 1         | 0.96%   |
| Mountain View            | 1         | 0.96%   |
| Moscow                   | 1         | 0.96%   |
| Miroslava                | 1         | 0.96%   |
| Milan                    | 1         | 0.96%   |
| Mangalore                | 1         | 0.96%   |
| Madrid                   | 1         | 0.96%   |
| Luxembourg               | 1         | 0.96%   |
| London                   | 1         | 0.96%   |
| Littleton                | 1         | 0.96%   |
| Lahore                   | 1         | 0.96%   |
| Kuwait City              | 1         | 0.96%   |
| Kochi                    | 1         | 0.96%   |
| Khobar                   | 1         | 0.96%   |
| K'alak'i T'bilisi        | 1         | 0.96%   |
| Johnstone                | 1         | 0.96%   |
| Islamabad                | 1         | 0.96%   |
| Impflingen               | 1         | 0.96%   |
| Hyderabad                | 1         | 0.96%   |
| Houston                  | 1         | 0.96%   |
| Hosur                    | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 45     | 24.79%  |
| WDC                 | 14        | 20     | 11.57%  |
| Toshiba             | 11        | 16     | 9.09%   |
| SK Hynix            | 11        | 11     | 9.09%   |
| Seagate             | 11        | 14     | 9.09%   |
| Sandisk             | 10        | 15     | 8.26%   |
| Intel               | 6         | 8      | 4.96%   |
| Unknown             | 5         | 7      | 4.13%   |
| Micron Technology   | 5         | 7      | 4.13%   |
| Kingston            | 3         | 3      | 2.48%   |
| HGST                | 3         | 3      | 2.48%   |
| Lenovo              | 2         | 2      | 1.65%   |
| Crucial             | 2         | 2      | 1.65%   |
| A-DATA Technology   | 2         | 2      | 1.65%   |
| Team                | 1         | 2      | 0.83%   |
| SMI                 | 1         | 2      | 0.83%   |
| Silicon Motion      | 1         | 2      | 0.83%   |
| PNY                 | 1         | 4      | 0.83%   |
| Lite-On             | 1         | 1      | 0.83%   |
| Corsair             | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 10        | 7.63%   |
| Sandisk NVMe SSD Drive 256GB            | 6         | 4.58%   |
| Samsung NVMe SSD Drive 256GB            | 5         | 3.82%   |
| Samsung NVMe SSD Drive 1024GB           | 5         | 3.82%   |
| Samsung NVMe SSD Drive 512GB            | 4         | 3.05%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 2.29%   |
| Toshiba NVMe SSD Drive 256GB            | 3         | 2.29%   |
| Micron NVMe SSD Drive 256GB             | 3         | 2.29%   |
| Unknown NVMe SSD Drive 256GB            | 2         | 1.53%   |
| Seagate Expansion 320GB                 | 2         | 1.53%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 1.53%   |
| Samsung Portable SSD T5 500GB           | 2         | 1.53%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.53%   |
| Samsung NVMe SSD Drive 2TB              | 2         | 1.53%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.53%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.53%   |
| Intel NVMe SSD Drive 2TB                | 2         | 1.53%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.76%   |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.76%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.76%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.76%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.76%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.76%   |
| WDC WD20 SPZX-11UA7T0 2TB               | 1         | 0.76%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.76%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.76%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.76%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.76%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.76%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.76%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.76%   |
| Unknown MMC Card  33GB                  | 1         | 0.76%   |
| Unknown MMC Card  32GB                  | 1         | 0.76%   |
| Unknown MMC Card  16GB                  | 1         | 0.76%   |
| Toshiba TR150 960GB SSD                 | 1         | 0.76%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.76%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.76%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.76%   |
| Toshiba HDWL110 1TB                     | 1         | 0.76%   |
| Team T253X2512G 512GB SSD               | 1         | 0.76%   |
| SMI DISK 506GB                          | 1         | 0.76%   |
| SK Hynix NVMe SSD Drive 1024GB          | 1         | 0.76%   |
| Silicon Motion NVMe SSD Drive 1TB       | 1         | 0.76%   |
| Seagate ST9320325AS 320GB               | 1         | 0.76%   |
| Seagate ST9160827AS 160GB               | 1         | 0.76%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.76%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.76%   |
| Seagate BUP Slim BK 1TB                 | 1         | 0.76%   |
| Seagate BUP Portable 4TB                | 1         | 0.76%   |
| Seagate BUP BL 4TB                      | 1         | 0.76%   |
| Seagate BarraCuda SSD ZA2000CM10002 2TB | 1         | 0.76%   |
| Seagate Backup+ Hub BK 10TB             | 1         | 0.76%   |
| SanDisk SDSSDH31024G 1024GB             | 1         | 0.76%   |
| SanDisk SD7SN6S-256G-1006 256GB SSD     | 1         | 0.76%   |
| SanDisk SD7SB7S512G1001 512GB SSD       | 1         | 0.76%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 13     | 44%     |
| WDC     | 8         | 12     | 32%     |
| Toshiba | 3         | 5      | 12%     |
| HGST    | 3         | 3      | 12%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 38.71%  |
| WDC                 | 3         | 4      | 9.68%   |
| SanDisk             | 3         | 4      | 9.68%   |
| Kingston            | 3         | 3      | 9.68%   |
| Crucial             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| Toshiba             | 1         | 1      | 3.23%   |
| Team                | 1         | 2      | 3.23%   |
| Seagate             | 1         | 1      | 3.23%   |
| PNY                 | 1         | 4      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 62        | 90     | 51.67%  |
| SSD     | 29        | 38     | 24.17%  |
| HDD     | 25        | 33     | 20.83%  |
| MMC     | 3         | 4      | 2.5%    |
| Unknown | 1         | 2      | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 62        | 90     | 54.87%  |
| SATA | 39        | 63     | 34.51%  |
| SAS  | 9         | 10     | 7.96%   |
| MMC  | 3         | 4      | 2.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 33     | 50%     |
| 0.51-1.0   | 17        | 27     | 32.69%  |
| 1.01-2.0   | 5         | 7      | 9.62%   |
| 3.01-4.0   | 3         | 3      | 5.77%   |
| 4.01-10.0  | 1         | 1      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 45.36%  |
| 251-500        | 18        | 18.56%  |
| 501-1000       | 13        | 13.4%   |
| 1001-2000      | 8         | 8.25%   |
| More than 3000 | 5         | 5.15%   |
| 21-50          | 3         | 3.09%   |
| 51-100         | 3         | 3.09%   |
| 2001-3000      | 1         | 1.03%   |
| 1-20           | 1         | 1.03%   |
| Unknown        | 1         | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 25        | 23.58%  |
| 101-250        | 24        | 22.64%  |
| 1-20           | 21        | 19.81%  |
| 51-100         | 15        | 14.15%  |
| 251-500        | 10        | 9.43%   |
| 501-1000       | 7         | 6.6%    |
| More than 3000 | 1         | 0.94%   |
| 2001-3000      | 1         | 0.94%   |
| 1001-2000      | 1         | 0.94%   |
| Unknown        | 1         | 0.94%   |

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
| Detected | 81        | 143    | 81.82%  |
| Works    | 18        | 24     | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 45.87%  |
| Samsung Electronics          | 20        | 18.35%  |
| SK Hynix                     | 11        | 10.09%  |
| Sandisk                      | 10        | 9.17%   |
| Toshiba America Info Systems | 7         | 6.42%   |
| Micron Technology            | 4         | 3.67%   |
| Lenovo                       | 2         | 1.83%   |
| KIOXIA                       | 2         | 1.83%   |
| Silicon Motion               | 1         | 0.92%   |
| Lite-On Technology           | 1         | 0.92%   |
| AMD                          | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 16        | 14.41%  |
| SK Hynix Non-Volatile memory controller                                       | 11        | 9.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 8.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 7         | 6.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 6         | 5.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 5.41%   |
| Micron Non-Volatile memory controller                                         | 4         | 3.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.7%    |
| Intel SSD 660P Series                                                         | 3         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 2.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.8%    |
| Lenovo Non-Volatile memory controller                                         | 2         | 1.8%    |
| KIOXIA Non-Volatile memory controller                                         | 2         | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.8%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 0.9%    |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 0.9%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.9%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.9%    |
| Samsung NVMe SSD Controller 980                                               | 1         | 0.9%    |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 0.9%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 62        | 56.88%  |
| SATA | 42        | 38.53%  |
| RAID | 5         | 4.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 95.74%  |
| AMD    | 4         | 4.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 9.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 9.57%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 6.38%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 4.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 3.19%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 3.19%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 2.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.13%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 2.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 2.13%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 2.13%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.13%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 2.13%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 1.06%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 1.06%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 1.06%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 1.06%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 1.06%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 1.06%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.06%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.06%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.06%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.06%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.06%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 1.06%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.06%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.06%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.06%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.06%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.06%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.06%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.06%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.06%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.06%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 55        | 58.51%  |
| Intel Core i5   | 23        | 24.47%  |
| Intel Xeon      | 5         | 5.32%   |
| Intel Core i3   | 3         | 3.19%   |
| AMD Ryzen 7     | 3         | 3.19%   |
| Other           | 2         | 2.13%   |
| Intel Core i9   | 2         | 2.13%   |
| AMD Ryzen 7 PRO | 1         | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 43        | 45.74%  |
| 2      | 26        | 27.66%  |
| 6      | 19        | 20.21%  |
| 8      | 6         | 6.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 97.87%  |
| 1      | 2         | 2.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 92        | 95.83%  |
| Unknown        | 4         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 21        | 21.88%  |
| 0xa0652    | 10        | 10.42%  |
| 0x806ea    | 10        | 10.42%  |
| 0x906ea    | 7         | 7.29%   |
| 0x206a7    | 6         | 6.25%   |
| 0x406e3    | 5         | 5.21%   |
| 0x306a9    | 5         | 5.21%   |
| 0x906ed    | 4         | 4.17%   |
| 0x506e3    | 4         | 4.17%   |
| 0x806e9    | 3         | 3.13%   |
| 0x306d4    | 3         | 3.13%   |
| 0x20655    | 3         | 3.13%   |
| Unknown    | 3         | 3.13%   |
| 0x906e9    | 2         | 2.08%   |
| 0x806d1    | 2         | 2.08%   |
| 0x40651    | 2         | 2.08%   |
| 0x08108102 | 2         | 2.08%   |
| 0x806c1    | 1         | 1.04%   |
| 0x20652    | 1         | 1.04%   |
| 0x08600104 | 1         | 1.04%   |
| 0x08600103 | 1         | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 48        | 50.53%  |
| CometLake   | 10        | 10.53%  |
| Skylake     | 9         | 9.47%   |
| SandyBridge | 6         | 6.32%   |
| IvyBridge   | 5         | 5.26%   |
| Westmere    | 4         | 4.21%   |
| Broadwell   | 3         | 3.16%   |
| Zen+        | 2         | 2.11%   |
| Zen 2       | 2         | 2.11%   |
| Icelake     | 2         | 2.11%   |
| Haswell     | 2         | 2.11%   |
| TigerLake   | 1         | 1.05%   |
| Unknown     | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 67.52%  |
| Nvidia | 27        | 23.08%  |
| AMD    | 11        | 9.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 14        | 11.97%  |
| Intel UHD Graphics 620                                                                | 10        | 8.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 9         | 7.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 8         | 6.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 5.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 5         | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 3.42%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 2.56%   |
| Intel HD Graphics 620                                                                 | 3         | 2.56%   |
| Intel HD Graphics 5500                                                                | 3         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.71%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 2         | 1.71%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 2         | 1.71%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 1.71%   |
| AMD Renoir                                                                            | 2         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.85%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.85%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.85%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.85%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.85%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.85%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.85%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.85%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 0.85%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 0.85%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.85%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 0.85%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                                    | 1         | 0.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 0.85%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 0.85%   |
| Intel HD Graphics P530                                                                | 1         | 0.85%   |
| Intel HD Graphics 630                                                                 | 1         | 0.85%   |
| Intel HD Graphics 530                                                                 | 1         | 0.85%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.85%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 0.85%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 0.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 58        | 61.05%  |
| Intel + Nvidia | 17        | 17.89%  |
| 1 x Nvidia     | 9         | 9.47%   |
| 1 x AMD        | 5         | 5.26%   |
| Intel + AMD    | 4         | 4.21%   |
| AMD + Nvidia   | 2         | 2.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 87.37%  |
| Proprietary | 9         | 9.47%   |
| Unknown     | 3         | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 69.47%  |
| 3.01-4.0   | 9         | 9.47%   |
| 1.01-2.0   | 7         | 7.37%   |
| 0.51-1.0   | 5         | 5.26%   |
| 5.01-6.0   | 4         | 4.21%   |
| 0.01-0.5   | 2         | 2.11%   |
| 7.01-8.0   | 1         | 1.05%   |
| 8.01-16.0  | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 14.81%  |
| LG Display              | 17        | 12.59%  |
| Chimei Innolux          | 16        | 11.85%  |
| BOE                     | 15        | 11.11%  |
| Dell                    | 14        | 10.37%  |
| Lenovo                  | 10        | 7.41%   |
| Samsung Electronics     | 9         | 6.67%   |
| Hewlett-Packard         | 5         | 3.7%    |
| Sharp                   | 4         | 2.96%   |
| InfoVision              | 4         | 2.96%   |
| Goldstar                | 4         | 2.96%   |
| Acer                    | 3         | 2.22%   |
| Philips                 | 2         | 1.48%   |
| PANDA                   | 2         | 1.48%   |
| LGD                     | 2         | 1.48%   |
| AOC                     | 2         | 1.48%   |
| Sun                     | 1         | 0.74%   |
| Sceptre Tech            | 1         | 0.74%   |
| Planar                  | 1         | 0.74%   |
| Eizo                    | 1         | 0.74%   |
| Chi Mei Optoelectronics | 1         | 0.74%   |
| BOE Technology Group    | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 6         | 4.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 2.86%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 2.14%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 2.14%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 3         | 2.14%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 2.14%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.43%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.43%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.43%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.43%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 1.43%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 1.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 1.43%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.43%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.43%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.71%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.71%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.71%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.71%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.71%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.71%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 698x393mm 31.5-inch    | 1         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.71%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.71%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.71%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 1         | 0.71%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.71%   |
| Lenovo LEN L27m-28 LEN65E6 1920x1080 597x336mm 27.0-inch              | 1         | 0.71%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.71%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 1         | 0.71%   |
| Hewlett-Packard Pavilion32 HWP3338 2560x1440 708x399mm 32.0-inch      | 1         | 0.71%   |
| Hewlett-Packard LCD Monitor Pavilion32 6400x2160                      | 1         | 0.71%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 57.39%  |
| 1366x768 (WXGA)    | 15        | 13.04%  |
| 3840x2160 (4K)     | 7         | 6.09%   |
| 1600x900 (HD+)     | 7         | 6.09%   |
| 2560x1440 (QHD)    | 6         | 5.22%   |
| 2560x1080          | 3         | 2.61%   |
| 1920x1200 (WUXGA)  | 3         | 2.61%   |
| 6400x2160          | 1         | 0.87%   |
| 3840x1080          | 1         | 0.87%   |
| 3440x1440          | 1         | 0.87%   |
| 2048x1152          | 1         | 0.87%   |
| 1680x1050 (WSXGA+) | 1         | 0.87%   |
| 1440x900 (WXGA+)   | 1         | 0.87%   |
| 1280x800 (WXGA)    | 1         | 0.87%   |
| Unknown            | 1         | 0.87%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 41        | 30.6%   |
| 14      | 24        | 17.91%  |
| 13      | 14        | 10.45%  |
| 24      | 13        | 9.7%    |
| 27      | 11        | 8.21%   |
| 23      | 7         | 5.22%   |
| 12      | 5         | 3.73%   |
| 34      | 4         | 2.99%   |
| 17      | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 31      | 2         | 1.49%   |
| 21      | 2         | 1.49%   |
| 49      | 1         | 0.75%   |
| 32      | 1         | 0.75%   |
| 22      | 1         | 0.75%   |
| 19      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 58.02%  |
| 501-600     | 25        | 19.08%  |
| 201-300     | 8         | 6.11%   |
| 701-800     | 5         | 3.82%   |
| 601-700     | 5         | 3.82%   |
| 401-500     | 5         | 3.82%   |
| 351-400     | 3         | 2.29%   |
| Unknown     | 3         | 2.29%   |
| 1001-1500   | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 83.65%  |
| 16/10   | 8         | 7.69%   |
| 21/9    | 4         | 3.85%   |
| Unknown | 3         | 2.88%   |
| 32/9    | 1         | 0.96%   |
| 3/2     | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 30.83%  |
| 81-90          | 35        | 26.32%  |
| 201-250        | 16        | 12.03%  |
| 301-350        | 11        | 8.27%   |
| 251-300        | 7         | 5.26%   |
| 351-500        | 6         | 4.51%   |
| 61-70          | 5         | 3.76%   |
| 71-80          | 3         | 2.26%   |
| 121-130        | 3         | 2.26%   |
| Unknown        | 3         | 2.26%   |
| 151-200        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 68        | 52.71%  |
| 51-100        | 31        | 24.03%  |
| 101-120       | 20        | 15.5%   |
| More than 240 | 4         | 3.1%    |
| 161-240       | 3         | 2.33%   |
| Unknown       | 3         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 57%     |
| 2     | 33        | 33%     |
| 3     | 6         | 6%      |
| 0     | 4         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 83        | 58.45%  |
| Realtek Semiconductor             | 26        | 18.31%  |
| Lenovo                            | 14        | 9.86%   |
| Qualcomm Atheros                  | 4         | 2.82%   |
| Marvell Technology Group          | 2         | 1.41%   |
| Broadcom Limited                  | 2         | 1.41%   |
| Xiaomi                            | 1         | 0.7%    |
| Sierra Wireless                   | 1         | 0.7%    |
| Samsung Electronics               | 1         | 0.7%    |
| Ralink                            | 1         | 0.7%    |
| Luminary Micro                    | 1         | 0.7%    |
| ICS Advent                        | 1         | 0.7%    |
| Huawei Technologies               | 1         | 0.7%    |
| Ericsson Business Mobile Networks | 1         | 0.7%    |
| DisplayLink                       | 1         | 0.7%    |
| Dell                              | 1         | 0.7%    |
| Broadcom                          | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 13        | 6.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 6.5%    |
| Intel Wireless 8265 / 8275                                                     | 12        | 6%      |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                                 | 10        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 5%      |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 8         | 4%      |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 3.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 3.5%    |
| Intel Wireless 8260                                                            | 6         | 3%      |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 3%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 3%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                            | 5         | 2.5%    |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 2%      |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 2%      |
| Intel Wireless 7265                                                            | 3         | 1.5%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1%      |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1%      |
| Lenovo USB-C to LAN                                                            | 2         | 1%      |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1%      |
| Intel Wireless-AC 9260                                                         | 2         | 1%      |
| Intel Wireless 3165                                                            | 2         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 1%      |
| Intel Ethernet Connection I219-LM                                              | 2         | 1%      |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1%      |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1%      |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1%      |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.5%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.5%    |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.5%    |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.5%    |
| Lenovo ThinkPad Lan                                                            | 1         | 0.5%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.5%    |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.5%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.5%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.5%    |
| Huawei E353/E3131                                                              | 1         | 0.5%    |
| Ericsson Business Mobile Networks N5321 gw                                     | 1         | 0.5%    |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.5%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                           | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 81        | 84.38%  |
| Realtek Semiconductor             | 5         | 5.21%   |
| Qualcomm Atheros                  | 4         | 4.17%   |
| Sierra Wireless                   | 1         | 1.04%   |
| Ralink                            | 1         | 1.04%   |
| Ericsson Business Mobile Networks | 1         | 1.04%   |
| Dell                              | 1         | 1.04%   |
| Broadcom Limited                  | 1         | 1.04%   |
| Broadcom                          | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 13.54%  |
| Intel Wireless 8265 / 8275                                     | 12        | 12.5%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 10.42%  |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 8.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 7.29%   |
| Intel Wireless 8260                                            | 6         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 5.21%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 4.17%   |
| Intel Wireless 7265                                            | 3         | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 2.08%   |
| Intel Wireless-AC 9260                                         | 2         | 2.08%   |
| Intel Wireless 3165                                            | 2         | 2.08%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.04%   |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 1.04%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.04%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 58        | 56.86%  |
| Realtek Semiconductor    | 22        | 21.57%  |
| Lenovo                   | 14        | 13.73%  |
| Marvell Technology Group | 2         | 1.96%   |
| Xiaomi                   | 1         | 0.98%   |
| Samsung Electronics      | 1         | 0.98%   |
| ICS Advent               | 1         | 0.98%   |
| Huawei Technologies      | 1         | 0.98%   |
| DisplayLink              | 1         | 0.98%   |
| Broadcom Limited         | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 13        | 12.62%  |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 9.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 9.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 7.77%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 6.8%    |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 5.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.85%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 4.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 3.88%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.91%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.94%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.94%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.94%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.94%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.94%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.94%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.94%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.97%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.97%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.97%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.97%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.97%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.97%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.97%   |
| Huawei E353/E3131                                                              | 1         | 0.97%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.97%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 51.69%  |
| Ethernet | 85        | 47.75%  |
| Modem    | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 53.09%  |
| Ethernet | 76        | 46.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 81.91%  |
| 1     | 17        | 18.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 92.63%  |
| Yes  | 7         | 7.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 81.08%  |
| Broadcom                        | 5         | 6.76%   |
| Qualcomm Atheros Communications | 2         | 2.7%    |
| IMC Networks                    | 2         | 2.7%    |
| Cambridge Silicon Radio         | 2         | 2.7%    |
| Ralink                          | 1         | 1.35%   |
| Foxconn / Hon Hai               | 1         | 1.35%   |
| Dell                            | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 19        | 25.68%  |
| Intel Bluetooth wireless interface                                                  | 17        | 22.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 21.62%  |
| Intel AX200 Bluetooth                                                               | 5         | 6.76%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.7%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.35%   |
| Intel Bluetooth Device                                                              | 1         | 1.35%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.35%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.35%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 90        | 62.5%   |
| Nvidia                 | 17        | 11.81%  |
| Lenovo                 | 12        | 8.33%   |
| AMD                    | 7         | 4.86%   |
| Plantronics            | 3         | 2.08%   |
| GN Netcom              | 3         | 2.08%   |
| Texas Instruments      | 2         | 1.39%   |
| Realtek Semiconductor  | 2         | 1.39%   |
| Generalplus Technology | 2         | 1.39%   |
| Logitech               | 1         | 0.69%   |
| JMTek                  | 1         | 0.69%   |
| Google                 | 1         | 0.69%   |
| Focusrite-Novation     | 1         | 0.69%   |
| Dell                   | 1         | 0.69%   |
| C-Media Electronics    | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 18        | 11.84%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 14        | 9.21%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 7.24%   |
| Intel Comet Lake PCH cAVS                                                         | 10        | 6.58%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 9         | 5.92%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 8         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 3.29%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4         | 2.63%   |
| Plantronics BT600                                                                 | 3         | 1.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.97%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.97%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.32%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.32%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.32%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.32%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.32%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.66%   |
| Nvidia Audio device                                                               | 1         | 0.66%   |
| Logitech H555 Headset                                                             | 1         | 0.66%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.66%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.66%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.66%   |
| JMTek iTalk-02                                                                    | 1         | 0.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.66%   |
| Google Pixel earbuds                                                              | 1         | 0.66%   |
| GN Netcom Jabra Link 380                                                          | 1         | 0.66%   |
| GN Netcom Jabra EVOLVE 20 MS                                                      | 1         | 0.66%   |
| GN Netcom Jabra BIZ 2400 USB                                                      | 1         | 0.66%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.66%   |
| Generalplus Technology USB Audio Device                                           | 1         | 0.66%   |
| Focusrite-Novation Scarlett 2i2 Camera                                            | 1         | 0.66%   |
| Dell AC511 USB SoundBar                                                           | 1         | 0.66%   |
| C-Media Electronics Blue Snowball                                                 | 1         | 0.66%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 38.71%  |
| SK Hynix            | 10        | 32.26%  |
| Unknown             | 2         | 6.45%   |
| Micron Technology   | 2         | 6.45%   |
| Kingston            | 2         | 6.45%   |
| Crucial             | 2         | 6.45%   |
| Smart               | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 6.25%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 6.25%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 3.13%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 3.13%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 3.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 1         | 3.13%   |
| Samsung RAM M471A2G44AM0-CTD 16384MB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 3.13%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s           | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s           | 1         | 3.13%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s      | 1         | 3.13%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s      | 1         | 3.13%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s         | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 50%     |
| DDR3   | 10        | 41.67%  |
| LPDDR4 | 1         | 4.17%   |
| LPDDR3 | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 95.65%  |
| Row Of Chips | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 33.33%  |
| 4096  | 8         | 33.33%  |
| 16384 | 7         | 29.17%  |
| 32768 | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 26.92%  |
| 1600  | 7         | 26.92%  |
| 3200  | 4         | 15.38%  |
| 1333  | 3         | 11.54%  |
| 2400  | 2         | 7.69%   |
| 2133  | 2         | 7.69%   |
| 1334  | 1         | 3.85%   |

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
| Chicony Electronics                    | 33        | 33%     |
| IMC Networks                           | 13        | 13%     |
| Acer                                   | 11        | 11%     |
| Realtek Semiconductor                  | 8         | 8%      |
| Microdia                               | 7         | 7%      |
| Logitech                               | 7         | 7%      |
| Sunplus Innovation Technology          | 6         | 6%      |
| Suyin                                  | 3         | 3%      |
| Lite-On Technology                     | 3         | 3%      |
| Samsung Electronics                    | 2         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2%      |
| Unknown                                | 1         | 1%      |
| Syntek                                 | 1         | 1%      |
| Quanta                                 | 1         | 1%      |
| Microsoft                              | 1         | 1%      |
| Lenovo                                 | 1         | 1%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 20        | 19.61%  |
| IMC Networks Integrated Camera                               | 11        | 10.78%  |
| Acer Integrated Camera                                       | 8         | 7.84%   |
| Realtek Integrated_Webcam_HD                                 | 6         | 5.88%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.92%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.94%   |
| Lite-On Integrated Camera                                    | 3         | 2.94%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 2.94%   |
| Chicony HP HD Camera                                         | 3         | 2.94%   |
| Acer SunplusIT Integrated Camera                             | 3         | 2.94%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 2         | 1.96%   |
| Microdia Webcam                                              | 2         | 1.96%   |
| Microdia Integrated Webcam                                   | 2         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 1.96%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.96%   |
| Unknown FULL HD 1080P Webcam                                 | 1         | 0.98%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.98%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.98%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.98%   |
| Suyin HP Truevision HD                                       | 1         | 0.98%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.98%   |
| Sunplus Integrated Webcam                                    | 1         | 0.98%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.98%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.98%   |
| Realtek NexiGo N960E FHD Webcam                              | 1         | 0.98%   |
| Quanta HP HD Camera                                          | 1         | 0.98%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.98%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.98%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.98%   |
| Microdia Integrated_Webcam_HD                                | 1         | 0.98%   |
| Logitech Webcam C925e                                        | 1         | 0.98%   |
| Logitech Webcam C310                                         | 1         | 0.98%   |
| Logitech B525 HD Webcam                                      | 1         | 0.98%   |
| Lenovo Integrated Webcam                                     | 1         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.98%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.98%   |
| Chicony Integrated IR Camera                                 | 1         | 0.98%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.98%   |
| Chicony HP Webcam                                            | 1         | 0.98%   |
| Chicony HD User Facing                                       | 1         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.98%   |
| Acer Integrated IR Camera                                    | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 25        | 60.98%  |
| Validity Sensors      | 13        | 31.71%  |
| Upek                  | 2         | 4.88%   |
| Elan Microelectronics | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 46.34%  |
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
| Elan ELAN:Fingerprint                                                      | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 46.15%  |
| Alcor Micro | 4         | 30.77%  |
| Lenovo      | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 30.77%  |
| Broadcom 58200                                             | 3         | 23.08%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 15.38%  |
| Broadcom 5880                                              | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 54.26%  |
| 0     | 34        | 36.17%  |
| 2     | 8         | 8.51%   |
| 3     | 1         | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 41        | 57.75%  |
| Chipcard              | 11        | 15.49%  |
| Graphics card         | 10        | 14.08%  |
| Net/wireless          | 2         | 2.82%   |
| Net/ethernet          | 2         | 2.82%   |
| Bluetooth             | 2         | 2.82%   |
| Storage               | 1         | 1.41%   |
| Multimedia controller | 1         | 1.41%   |
| Card reader           | 1         | 1.41%   |

