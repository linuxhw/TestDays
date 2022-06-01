RHEL 8 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 8.

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

Total: 168

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo  | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell    | Precision 5550              | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
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
| Lenovo  | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer    | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP      | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo  | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
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
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell    | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP      | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
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
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell    | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell    | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP      | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo  | ThinkPad T460 20BUS0QT0A    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| Dell    | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO  | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell    | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell    | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell    | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO  | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO  | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell    | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP      | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
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
| HP      | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP      | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell    | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell    | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony    | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony    | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo  | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo  | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell    | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP      | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
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
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 8.2%    |
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 8.2%    |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 6.56%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 6.56%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 7         | 5.74%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 5.74%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 3.28%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 3.28%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 3.28%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 3.28%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 3.28%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 3.28%   |
| 4.18.0-193.el8.x86_64        | 4         | 3.28%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 4         | 3.28%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.46%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.46%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.46%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 2.46%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.46%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.46%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.46%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.64%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.64%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.64%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 2         | 1.64%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.82%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.82%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.82%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1         | 0.82%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 0.82%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.82%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.82%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.82%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.82%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 0.82%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 100       | 99.01%  |
| 5.9.1   | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 100       | 99.01%  |
| 5.9     | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 89        | 85.58%  |
| Unknown       | 9         | 8.65%   |
| GNOME Classic | 4         | 3.85%   |
| KDE5          | 2         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 58.1%   |
| Wayland | 39        | 37.14%  |
| Unknown | 5         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 85        | 80.95%  |
| GDM     | 20        | 19.05%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 72        | 69.23%  |
| Unknown | 7         | 6.73%   |
| fr_FR   | 4         | 3.85%   |
| en_GB   | 4         | 3.85%   |
| pt_BR   | 2         | 1.92%   |
| pl_PL   | 2         | 1.92%   |
| nl_NL   | 2         | 1.92%   |
| en_IN   | 2         | 1.92%   |
| en_IE   | 2         | 1.92%   |
| ru_RU   | 1         | 0.96%   |
| ja_JP   | 1         | 0.96%   |
| it_IT   | 1         | 0.96%   |
| es_ES   | 1         | 0.96%   |
| es_EC   | 1         | 0.96%   |
| de_DE   | 1         | 0.96%   |
| de_CH   | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 84        | 80.77%  |
| BIOS | 20        | 19.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 87        | 84.47%  |
| Ext4    | 11        | 10.68%  |
| Unknown | 5         | 4.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 79.05%  |
| GPT     | 21        | 20%     |
| MBR     | 1         | 0.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 93.2%   |
| Yes       | 7         | 6.8%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 94.12%  |
| Yes       | 6         | 5.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 61        | 60.4%   |
| Dell             | 19        | 18.81%  |
| Hewlett-Packard  | 10        | 9.9%    |
| ASUSTek Computer | 5         | 4.95%   |
| Sony             | 2         | 1.98%   |
| TUXEDO           | 1         | 0.99%   |
| Toshiba          | 1         | 0.99%   |
| Timi             | 1         | 0.99%   |
| Acer             | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 3.96%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.98%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.98%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.98%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.98%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.98%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.98%   |
| HP EliteBook 8460p                       | 2         | 1.98%   |
| Dell Latitude E6430                      | 2         | 1.98%   |
| Dell Latitude 5300                       | 2         | 1.98%   |
| TUXEDO N13xWU                            | 1         | 0.99%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.99%   |
| Timi TM1707                              | 1         | 0.99%   |
| Sony VPCEB4L1R                           | 1         | 0.99%   |
| Sony VPCEB23FM                           | 1         | 0.99%   |
| Lenovo Z40-70 20366                      | 1         | 0.99%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.99%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.99%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.99%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.99%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.99%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.99%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.99%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.99%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.99%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.99%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.99%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.99%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.99%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.99%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.99%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.99%   |
| Lenovo ThinkPad T480 20L6S29D02          | 1         | 0.99%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.99%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.99%   |
| Lenovo ThinkPad T460 20BUS0QT0A          | 1         | 0.99%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.99%   |
| Lenovo ThinkPad T15 Gen 2i 20W5S12J0K    | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N    | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0Y    | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 0.99%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH0T     | 1         | 0.99%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 0.99%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 0.99%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 0.99%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 0.99%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 0.99%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 0.99%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 0.99%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 0.99%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 0.99%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 0.99%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 0.99%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 0.99%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 0.99%   |
| Lenovo ThinkPad E490 20N8000JAD          | 1         | 0.99%   |
| Lenovo ThinkPad E15 Gen 2 20T80002US     | 1         | 0.99%   |
| Lenovo Legion 5 15ACH6 82JW              | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 59        | 58.42%  |
| Dell Latitude     | 8         | 7.92%   |
| Dell Precision    | 6         | 5.94%   |
| HP EliteBook      | 4         | 3.96%   |
| Dell Inspiron     | 3         | 2.97%   |
| HP ZBook          | 2         | 1.98%   |
| TUXEDO N13xWU     | 1         | 0.99%   |
| Toshiba Satellite | 1         | 0.99%   |
| Timi TM1707       | 1         | 0.99%   |
| Sony VPCEB4L1R    | 1         | 0.99%   |
| Sony VPCEB23FM    | 1         | 0.99%   |
| Lenovo Z40-70     | 1         | 0.99%   |
| Lenovo Legion     | 1         | 0.99%   |
| HP ProBook        | 1         | 0.99%   |
| HP Pavilion       | 1         | 0.99%   |
| HP OMEN           | 1         | 0.99%   |
| HP 250            | 1         | 0.99%   |
| Dell XPS          | 1         | 0.99%   |
| Dell G3           | 1         | 0.99%   |
| ASUS Zephyrus     | 1         | 0.99%   |
| ASUS X550VX       | 1         | 0.99%   |
| ASUS VivoBook     | 1         | 0.99%   |
| ASUS TUF          | 1         | 0.99%   |
| ASUS GL502VMK     | 1         | 0.99%   |
| Acer Nitro        | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 24.75%  |
| 2019 | 21        | 20.79%  |
| 2018 | 14        | 13.86%  |
| 2017 | 7         | 6.93%   |
| 2011 | 7         | 6.93%   |
| 2016 | 6         | 5.94%   |
| 2015 | 6         | 5.94%   |
| 2021 | 5         | 4.95%   |
| 2012 | 4         | 3.96%   |
| 2010 | 3         | 2.97%   |
| 2013 | 2         | 1.98%   |
| 2014 | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 101       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 85.29%  |
| Enabled  | 15        | 14.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 101       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 38        | 36.54%  |
| 16.01-24.0  | 19        | 18.27%  |
| 8.01-16.0   | 19        | 18.27%  |
| 4.01-8.0    | 15        | 14.42%  |
| 3.01-4.0    | 6         | 5.77%   |
| 64.01-256.0 | 6         | 5.77%   |
| 24.01-32.0  | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 51        | 44.74%  |
| 8.01-16.0  | 20        | 17.54%  |
| 3.01-4.0   | 16        | 14.04%  |
| 2.01-3.0   | 14        | 12.28%  |
| 1.01-2.0   | 8         | 7.02%   |
| 16.01-24.0 | 2         | 1.75%   |
| 32.01-64.0 | 1         | 0.88%   |
| 24.01-32.0 | 1         | 0.88%   |
| 0.51-1.0   | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 75.96%  |
| 2      | 16        | 15.38%  |
| 3      | 8         | 7.69%   |
| 4      | 1         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 87.25%  |
| Yes       | 13        | 12.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 87.25%  |
| No        | 13        | 12.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 99.01%  |
| No        | 1         | 0.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 76.42%  |
| No        | 25        | 23.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 24        | 23.76%  |
| India        | 13        | 12.87%  |
| UK           | 5         | 4.95%   |
| Germany      | 5         | 4.95%   |
| France       | 5         | 4.95%   |
| Czechia      | 4         | 3.96%   |
| Netherlands  | 3         | 2.97%   |
| Mexico       | 3         | 2.97%   |
| Switzerland  | 2         | 1.98%   |
| Spain        | 2         | 1.98%   |
| South Africa | 2         | 1.98%   |
| Romania      | 2         | 1.98%   |
| Japan        | 2         | 1.98%   |
| Canada       | 2         | 1.98%   |
| Brazil       | 2         | 1.98%   |
| Australia    | 2         | 1.98%   |
| Singapore    | 1         | 0.99%   |
| Saudi Arabia | 1         | 0.99%   |
| Russia       | 1         | 0.99%   |
| Portugal     | 1         | 0.99%   |
| Poland       | 1         | 0.99%   |
| Pakistan     | 1         | 0.99%   |
| Nepal        | 1         | 0.99%   |
| Myanmar      | 1         | 0.99%   |
| Morocco      | 1         | 0.99%   |
| Luxembourg   | 1         | 0.99%   |
| Lithuania    | 1         | 0.99%   |
| Kuwait       | 1         | 0.99%   |
| Italy        | 1         | 0.99%   |
| Israel       | 1         | 0.99%   |
| Ireland      | 1         | 0.99%   |
| Georgia      | 1         | 0.99%   |
| Egypt        | 1         | 0.99%   |
| Ecuador      | 1         | 0.99%   |
| Colombia     | 1         | 0.99%   |
| Chile        | 1         | 0.99%   |
| Bulgaria     | 1         | 0.99%   |
| Armenia      | 1         | 0.99%   |
| Argentina    | 1         | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Prague                   | 3         | 2.73%   |
| Munich                   | 3         | 2.73%   |
| Mexico City              | 3         | 2.73%   |
| Chennai                  | 2         | 1.82%   |
| Zaragoza                 | 1         | 0.91%   |
| Webster                  | 1         | 0.91%   |
| Vardenis                 | 1         | 0.91%   |
| Udaipur                  | 1         | 0.91%   |
| Temuco                   | 1         | 0.91%   |
| Temara                   | 1         | 0.91%   |
| Taringa                  | 1         | 0.91%   |
| Talkha                   | 1         | 0.91%   |
| Syracuse                 | 1         | 0.91%   |
| Streatham                | 1         | 0.91%   |
| Steamboat Springs        | 1         | 0.91%   |
| Sofia                    | 1         | 0.91%   |
| Singapore                | 1         | 0.91%   |
| Šilalė                 | 1         | 0.91%   |
| Sheffield                | 1         | 0.91%   |
| San Jose                 | 1         | 0.91%   |
| San Francisco            | 1         | 0.91%   |
| Salt Lake City           | 1         | 0.91%   |
| Saint-Ismier             | 1         | 0.91%   |
| Saint-Alphonse-Rodriguez | 1         | 0.91%   |
| Roha                     | 1         | 0.91%   |
| Rochester                | 1         | 0.91%   |
| Reims                    | 1         | 0.91%   |
| Raleigh                  | 1         | 0.91%   |
| Quito                    | 1         | 0.91%   |
| Queenscliff              | 1         | 0.91%   |
| Queens                   | 1         | 0.91%   |
| Portalegre               | 1         | 0.91%   |
| Port Elizabeth           | 1         | 0.91%   |
| Pickerington             | 1         | 0.91%   |
| Paraiso do Tocantins     | 1         | 0.91%   |
| Paragould                | 1         | 0.91%   |
| Oyama                    | 1         | 0.91%   |
| Ottawa                   | 1         | 0.91%   |
| Muri bei Bern            | 1         | 0.91%   |
| Mumbai                   | 1         | 0.91%   |
| Mountain View            | 1         | 0.91%   |
| Montreal                 | 1         | 0.91%   |
| Mogilno                  | 1         | 0.91%   |
| Milan                    | 1         | 0.91%   |
| Mangalore                | 1         | 0.91%   |
| Mandalay                 | 1         | 0.91%   |
| Malkajgiri               | 1         | 0.91%   |
| Malappuram               | 1         | 0.91%   |
| Madrid                   | 1         | 0.91%   |
| Luxembourg               | 1         | 0.91%   |
| London                   | 1         | 0.91%   |
| Littleton                | 1         | 0.91%   |
| Lahore                   | 1         | 0.91%   |
| Kuwait City              | 1         | 0.91%   |
| Kirkland                 | 1         | 0.91%   |
| Khobar                   | 1         | 0.91%   |
| Kathmandu                | 1         | 0.91%   |
| K'alak'i T'bilisi        | 1         | 0.91%   |
| Johnstone                | 1         | 0.91%   |
| Jalna                    | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 46     | 24.03%  |
| WDC                 | 15        | 19     | 11.63%  |
| Toshiba             | 14        | 18     | 10.85%  |
| SK Hynix            | 12        | 12     | 9.3%    |
| Seagate             | 11        | 14     | 8.53%   |
| Sandisk             | 11        | 14     | 8.53%   |
| Intel               | 6         | 9      | 4.65%   |
| Unknown             | 5         | 7      | 3.88%   |
| Micron Technology   | 5         | 7      | 3.88%   |
| Kingston            | 4         | 4      | 3.1%    |
| HGST                | 3         | 3      | 2.33%   |
| Lenovo              | 2         | 2      | 1.55%   |
| Crucial             | 2         | 2      | 1.55%   |
| A-DATA Technology   | 2         | 2      | 1.55%   |
| Team                | 1         | 2      | 0.78%   |
| SMI                 | 1         | 2      | 0.78%   |
| Silicon Motion      | 1         | 2      | 0.78%   |
| PNY                 | 1         | 2      | 0.78%   |
| Lite-On             | 1         | 1      | 0.78%   |
| Corsair             | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 10        | 7.19%   |
| Sandisk NVMe SSD Drive 256GB            | 6         | 4.32%   |
| Samsung NVMe SSD Drive 512GB            | 5         | 3.6%    |
| Samsung NVMe SSD Drive 256GB            | 5         | 3.6%    |
| Samsung NVMe SSD Drive 1024GB           | 5         | 3.6%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 4         | 2.88%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 2.16%   |
| Micron NVMe SSD Drive 256GB             | 3         | 2.16%   |
| Unknown NVMe SSD Drive 256GB            | 2         | 1.44%   |
| Seagate Expansion 4TB                   | 2         | 1.44%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 1.44%   |
| Samsung Portable SSD T5 500GB           | 2         | 1.44%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.44%   |
| Samsung NVMe SSD Drive 2TB              | 2         | 1.44%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.44%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.44%   |
| Intel NVMe SSD Drive 2TB                | 2         | 1.44%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.72%   |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.72%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.72%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.72%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.72%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.72%   |
| WDC WD20 SPZX-11UA7T0 2TB               | 1         | 0.72%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.72%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.72%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.72%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.72%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.72%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.72%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 1         | 0.72%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.72%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.72%   |
| Unknown MMC Card  33GB                  | 1         | 0.72%   |
| Unknown MMC Card  32GB                  | 1         | 0.72%   |
| Unknown MMC Card  16GB                  | 1         | 0.72%   |
| Toshiba TR150 960GB SSD                 | 1         | 0.72%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.72%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.72%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.72%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.72%   |
| Toshiba KXG6AZNV256G 256GB              | 1         | 0.72%   |
| Toshiba HDWL110 1TB                     | 1         | 0.72%   |
| Team T253X2512G 512GB SSD               | 1         | 0.72%   |
| SMI DISK 506GB                          | 1         | 0.72%   |
| SK Hynix SKHynix_HFS512GDE9X084N 512GB  | 1         | 0.72%   |
| SK Hynix NVMe SSD Drive 1024GB          | 1         | 0.72%   |
| Silicon Motion NVMe SSD Drive 1TB       | 1         | 0.72%   |
| Seagate ST9320325AS 320GB               | 1         | 0.72%   |
| Seagate ST9160827AS 160GB               | 1         | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.72%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.72%   |
| Seagate BUP Slim BK 1TB                 | 1         | 0.72%   |
| Seagate BUP Portable 5TB                | 1         | 0.72%   |
| Seagate BUP BL 4TB                      | 1         | 0.72%   |
| Seagate BarraCuda SSD ZA2000CM10002 2TB | 1         | 0.72%   |
| Seagate Backup+ Hub BK 8TB              | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 13     | 42.31%  |
| WDC     | 8         | 10     | 30.77%  |
| Toshiba | 4         | 6      | 15.38%  |
| HGST    | 3         | 3      | 11.54%  |

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
| PNY                 | 1         | 2      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 69        | 95     | 53.91%  |
| SSD     | 29        | 36     | 22.66%  |
| HDD     | 26        | 32     | 20.31%  |
| MMC     | 3         | 4      | 2.34%   |
| Unknown | 1         | 2      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 69        | 95     | 57.02%  |
| SATA | 40        | 60     | 33.06%  |
| SAS  | 9         | 10     | 7.44%   |
| MMC  | 3         | 4      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 31     | 47.27%  |
| 0.51-1.0   | 18        | 26     | 32.73%  |
| 1.01-2.0   | 5         | 5      | 9.09%   |
| 3.01-4.0   | 4         | 4      | 7.27%   |
| 4.01-10.0  | 2         | 2      | 3.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 45.19%  |
| 251-500        | 20        | 19.23%  |
| 501-1000       | 14        | 13.46%  |
| 1001-2000      | 8         | 7.69%   |
| More than 3000 | 5         | 4.81%   |
| 51-100         | 4         | 3.85%   |
| 21-50          | 3         | 2.88%   |
| 2001-3000      | 1         | 0.96%   |
| 1-20           | 1         | 0.96%   |
| Unknown        | 1         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 26        | 23.21%  |
| 101-250        | 26        | 23.21%  |
| 1-20           | 23        | 20.54%  |
| 51-100         | 16        | 14.29%  |
| 251-500        | 10        | 8.93%   |
| 501-1000       | 7         | 6.25%   |
| More than 3000 | 1         | 0.89%   |
| 2001-3000      | 1         | 0.89%   |
| 1001-2000      | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

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
| Detected | 86        | 143    | 81.13%  |
| Works    | 20        | 26     | 18.87%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 51        | 43.22%  |
| Samsung Electronics          | 21        | 17.8%   |
| SK Hynix                     | 12        | 10.17%  |
| Sandisk                      | 12        | 10.17%  |
| Toshiba America Info Systems | 9         | 7.63%   |
| Micron Technology            | 4         | 3.39%   |
| Lenovo                       | 2         | 1.69%   |
| KIOXIA                       | 2         | 1.69%   |
| AMD                          | 2         | 1.69%   |
| Silicon Motion               | 1         | 0.85%   |
| Lite-On Technology           | 1         | 0.85%   |
| Kingston Technology Company  | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 17        | 14.17%  |
| SK Hynix Non-Volatile memory controller                                       | 11        | 9.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 7.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 8         | 6.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 8         | 6.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 5%      |
| Micron Non-Volatile memory controller                                         | 4         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.5%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.5%    |
| Intel SSD 660P Series                                                         | 3         | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.5%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 2         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.67%   |
| Lenovo Non-Volatile memory controller                                         | 2         | 1.67%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.67%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2         | 1.67%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.83%   |
| SK Hynix Gold P31 SSD                                                         | 1         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 0.83%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.83%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 0.83%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.83%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 69        | 58.47%  |
| SATA | 45        | 38.14%  |
| RAID | 4         | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 95.05%  |
| AMD    | 5         | 4.95%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 9.9%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 8.91%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 7         | 6.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 4.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.97%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.97%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.98%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.98%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.98%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.98%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.98%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.98%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.99%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.99%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.99%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.99%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.99%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.99%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.99%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.99%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.99%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.99%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.99%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.99%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 0.99%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 0.99%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 0.99%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 0.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 0.99%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 58        | 57.43%  |
| Intel Core i5   | 24        | 23.76%  |
| Intel Xeon      | 5         | 4.95%   |
| AMD Ryzen 7     | 4         | 3.96%   |
| Other           | 3         | 2.97%   |
| Intel Core i3   | 3         | 2.97%   |
| Intel Core i9   | 2         | 1.98%   |
| Intel Pentium   | 1         | 0.99%   |
| AMD Ryzen 7 PRO | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 47        | 46.53%  |
| 2      | 27        | 26.73%  |
| 6      | 20        | 19.8%   |
| 8      | 7         | 6.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 99        | 98.02%  |
| 1      | 2         | 1.98%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 96.12%  |
| Unknown        | 4         | 3.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 24        | 23.3%   |
| 0xa0652    | 11        | 10.68%  |
| 0x806ea    | 11        | 10.68%  |
| 0x906ea    | 7         | 6.8%    |
| 0x206a7    | 6         | 5.83%   |
| 0x406e3    | 5         | 4.85%   |
| 0x306a9    | 5         | 4.85%   |
| 0x906ed    | 4         | 3.88%   |
| 0x506e3    | 4         | 3.88%   |
| 0x806e9    | 3         | 2.91%   |
| 0x306d4    | 3         | 2.91%   |
| 0x20655    | 3         | 2.91%   |
| Unknown    | 3         | 2.91%   |
| 0x906e9    | 2         | 1.94%   |
| 0x806d1    | 2         | 1.94%   |
| 0x806c1    | 2         | 1.94%   |
| 0x40651    | 2         | 1.94%   |
| 0x08108102 | 2         | 1.94%   |
| 0x20652    | 1         | 0.97%   |
| 0x0a50000c | 1         | 0.97%   |
| 0x08600104 | 1         | 0.97%   |
| 0x08600103 | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 52        | 50.98%  |
| CometLake   | 11        | 10.78%  |
| Skylake     | 9         | 8.82%   |
| SandyBridge | 6         | 5.88%   |
| IvyBridge   | 5         | 4.9%    |
| Westmere    | 4         | 3.92%   |
| Broadwell   | 3         | 2.94%   |
| Zen+        | 2         | 1.96%   |
| Zen 2       | 2         | 1.96%   |
| TigerLake   | 2         | 1.96%   |
| Icelake     | 2         | 1.96%   |
| Haswell     | 2         | 1.96%   |
| Zen 3       | 1         | 0.98%   |
| Unknown     | 1         | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 66.41%  |
| Nvidia | 31        | 24.22%  |
| AMD    | 12        | 9.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 14        | 10.94%  |
| Intel UHD Graphics 620                                                                | 11        | 8.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 10        | 7.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 7.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 5.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 5         | 3.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 3.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 3.13%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 2.34%   |
| Intel HD Graphics 620                                                                 | 3         | 2.34%   |
| Intel HD Graphics 5500                                                                | 3         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.34%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.56%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 2         | 1.56%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 2         | 1.56%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 1.56%   |
| AMD Renoir                                                                            | 2         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.56%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.78%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.78%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.78%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.78%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.78%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.78%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.78%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.78%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 0.78%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 0.78%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.78%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 0.78%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 1         | 0.78%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                                    | 1         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 0.78%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 0.78%   |
| Intel HD Graphics P530                                                                | 1         | 0.78%   |
| Intel HD Graphics 630                                                                 | 1         | 0.78%   |
| Intel HD Graphics 530                                                                 | 1         | 0.78%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                         | 1         | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.78%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 0.78%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 0.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 0.78%   |
| AMD Cezanne                                                                           | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 59.8%   |
| Intel + Nvidia | 20        | 19.61%  |
| 1 x Nvidia     | 9         | 8.82%   |
| 1 x AMD        | 5         | 4.9%    |
| Intel + AMD    | 4         | 3.92%   |
| AMD + Nvidia   | 3         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 88        | 86.27%  |
| Proprietary | 9         | 8.82%   |
| Unknown     | 5         | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 69.61%  |
| 3.01-4.0   | 10        | 9.8%    |
| 1.01-2.0   | 8         | 7.84%   |
| 0.51-1.0   | 5         | 4.9%    |
| 5.01-6.0   | 4         | 3.92%   |
| 0.01-0.5   | 2         | 1.96%   |
| 7.01-8.0   | 1         | 0.98%   |
| 8.01-16.0  | 1         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 15.38%  |
| LG Display              | 17        | 11.89%  |
| BOE                     | 17        | 11.89%  |
| Chimei Innolux          | 16        | 11.19%  |
| Dell                    | 15        | 10.49%  |
| Lenovo                  | 11        | 7.69%   |
| Samsung Electronics     | 10        | 6.99%   |
| Sharp                   | 5         | 3.5%    |
| Hewlett-Packard         | 5         | 3.5%    |
| InfoVision              | 4         | 2.8%    |
| Goldstar                | 4         | 2.8%    |
| Acer                    | 3         | 2.1%    |
| Philips                 | 2         | 1.4%    |
| PANDA                   | 2         | 1.4%    |
| LGD                     | 2         | 1.4%    |
| AOC                     | 2         | 1.4%    |
| Sun                     | 1         | 0.7%    |
| Sceptre Tech            | 1         | 0.7%    |
| Planar                  | 1         | 0.7%    |
| Eizo                    | 1         | 0.7%    |
| Chi Mei Optoelectronics | 1         | 0.7%    |
| BOE Technology Group    | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 4.03%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 2.68%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 2.01%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 2.01%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 2.01%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x173mm 13.9-inch        | 3         | 2.01%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.34%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.34%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.34%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 1.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 1.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.34%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.34%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.67%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.67%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.67%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.67%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.67%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.67%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.67%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.67%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 700x400mm 31.7-inch    | 1         | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.67%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.67%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.67%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 1         | 0.67%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch              | 1         | 0.67%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.67%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 1         | 0.67%   |
| Lenovo LEN L27m-28 LEN65E6 1920x1080 597x336mm 27.0-inch              | 1         | 0.67%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 57.38%  |
| 1366x768 (WXGA)    | 15        | 12.3%   |
| 3840x2160 (4K)     | 7         | 5.74%   |
| 2560x1440 (QHD)    | 7         | 5.74%   |
| 1600x900 (HD+)     | 7         | 5.74%   |
| 1920x1200 (WUXGA)  | 4         | 3.28%   |
| 2560x1080          | 3         | 2.46%   |
| 1680x1050 (WSXGA+) | 2         | 1.64%   |
| 6400x2160          | 1         | 0.82%   |
| 3840x1080          | 1         | 0.82%   |
| 3440x1440          | 1         | 0.82%   |
| 2048x1152          | 1         | 0.82%   |
| 1440x900 (WXGA+)   | 1         | 0.82%   |
| 1280x800 (WXGA)    | 1         | 0.82%   |
| Unknown            | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 29.37%  |
| 14      | 27        | 18.88%  |
| 24      | 15        | 10.49%  |
| 13      | 15        | 10.49%  |
| 27      | 11        | 7.69%   |
| 23      | 8         | 5.59%   |
| 12      | 5         | 3.5%    |
| 34      | 4         | 2.8%    |
| 17      | 3         | 2.1%    |
| Unknown | 3         | 2.1%    |
| 31      | 2         | 1.4%    |
| 22      | 2         | 1.4%    |
| 21      | 2         | 1.4%    |
| 49      | 1         | 0.7%    |
| 32      | 1         | 0.7%    |
| 19      | 1         | 0.7%    |
| 18      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 81        | 57.86%  |
| 501-600     | 28        | 20%     |
| 201-300     | 8         | 5.71%   |
| 401-500     | 6         | 4.29%   |
| 701-800     | 5         | 3.57%   |
| 601-700     | 5         | 3.57%   |
| 351-400     | 3         | 2.14%   |
| Unknown     | 3         | 2.14%   |
| 1001-1500   | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 92        | 82.88%  |
| 16/10   | 10        | 9.01%   |
| 21/9    | 4         | 3.6%    |
| Unknown | 3         | 2.7%    |
| 32/9    | 1         | 0.9%    |
| 3/2     | 1         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 29.79%  |
| 81-90          | 39        | 27.66%  |
| 201-250        | 19        | 13.48%  |
| 301-350        | 11        | 7.8%    |
| 251-300        | 7         | 4.96%   |
| 351-500        | 6         | 4.26%   |
| 61-70          | 5         | 3.55%   |
| 71-80          | 3         | 2.13%   |
| 121-130        | 3         | 2.13%   |
| Unknown        | 3         | 2.13%   |
| 151-200        | 1         | 0.71%   |
| 141-150        | 1         | 0.71%   |
| 501-1000       | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 53.68%  |
| 51-100        | 33        | 24.26%  |
| 101-120       | 20        | 14.71%  |
| More than 240 | 4         | 2.94%   |
| 161-240       | 3         | 2.21%   |
| Unknown       | 3         | 2.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 59        | 55.14%  |
| 2     | 35        | 32.71%  |
| 3     | 7         | 6.54%   |
| 0     | 6         | 5.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 88        | 58.28%  |
| Realtek Semiconductor             | 28        | 18.54%  |
| Lenovo                            | 15        | 9.93%   |
| Qualcomm Atheros                  | 4         | 2.65%   |
| Marvell Technology Group          | 2         | 1.32%   |
| Broadcom Limited                  | 2         | 1.32%   |
| Xiaomi                            | 1         | 0.66%   |
| Sierra Wireless                   | 1         | 0.66%   |
| Samsung Electronics               | 1         | 0.66%   |
| Ralink                            | 1         | 0.66%   |
| Qualcomm Atheros Communications   | 1         | 0.66%   |
| Luminary Micro                    | 1         | 0.66%   |
| ICS Advent                        | 1         | 0.66%   |
| Huawei Technologies               | 1         | 0.66%   |
| Ericsson Business Mobile Networks | 1         | 0.66%   |
| DisplayLink                       | 1         | 0.66%   |
| Dell                              | 1         | 0.66%   |
| Broadcom                          | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 6.57%   |
| Intel Wireless 8265 / 8275                                                     | 13        | 6.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 6.1%    |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11        | 5.16%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 10        | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 4.69%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 4.23%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 3.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 3.29%   |
| Intel Wireless 8260                                                            | 6         | 2.82%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 2.82%   |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.35%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 2.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.88%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.88%   |
| Intel Wireless 7265                                                            | 3         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.41%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.94%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.94%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.94%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.94%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.94%   |
| Intel Wireless 3165                                                            | 2         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.94%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.94%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.47%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.47%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.47%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.47%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.47%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.47%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.47%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.47%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.47%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.47%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.47%   |
| Huawei E353/E3131                                                              | 1         | 0.47%   |
| Ericsson Business Mobile Networks N5321 gw                                     | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 83.65%  |
| Realtek Semiconductor           | 7         | 6.73%   |
| Qualcomm Atheros                | 4         | 3.85%   |
| Sierra Wireless                 | 1         | 0.96%   |
| Ralink                          | 1         | 0.96%   |
| Qualcomm Atheros Communications | 1         | 0.96%   |
| Dell                            | 1         | 0.96%   |
| Broadcom Limited                | 1         | 0.96%   |
| Broadcom                        | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 13        | 12.5%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 12.5%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 10.58%  |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 9.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 6.73%   |
| Intel Wireless 8260                                            | 6         | 5.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 5.77%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.81%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 3.85%   |
| Intel Wireless 7265                                            | 3         | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.92%   |
| Intel Wireless-AC 9260                                         | 2         | 1.92%   |
| Intel Wireless 3165                                            | 2         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.92%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.96%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 0.96%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 61        | 57.01%  |
| Realtek Semiconductor    | 23        | 21.5%   |
| Lenovo                   | 15        | 14.02%  |
| Marvell Technology Group | 2         | 1.87%   |
| Xiaomi                   | 1         | 0.93%   |
| Samsung Electronics      | 1         | 0.93%   |
| ICS Advent               | 1         | 0.93%   |
| Huawei Technologies      | 1         | 0.93%   |
| DisplayLink              | 1         | 0.93%   |
| Broadcom Limited         | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 13.08%  |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 9.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 9.35%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 8.41%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 7.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 5.61%   |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 5.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 3.74%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.8%    |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 2.8%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.87%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.87%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.87%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.87%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.87%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.87%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.87%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.93%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.93%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.93%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.93%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.93%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.93%   |
| Huawei E353/E3131                                                              | 1         | 0.93%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 52.36%  |
| Ethernet | 89        | 46.6%   |
| Modem    | 2         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 67.57%  |
| Ethernet | 36        | 32.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 81        | 80.2%   |
| 1     | 20        | 19.8%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 93.14%  |
| Yes  | 7         | 6.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 80.25%  |
| Broadcom                        | 5         | 6.17%   |
| IMC Networks                    | 3         | 3.7%    |
| Qualcomm Atheros Communications | 2         | 2.47%   |
| Cambridge Silicon Radio         | 2         | 2.47%   |
| Realtek Semiconductor           | 1         | 1.23%   |
| Ralink                          | 1         | 1.23%   |
| Foxconn / Hon Hai               | 1         | 1.23%   |
| Dell                            | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 23        | 28.4%   |
| Intel Bluetooth wireless interface                                                  | 18        | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 19.75%  |
| Intel AX200 Bluetooth                                                               | 5         | 6.17%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.47%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.23%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.23%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.23%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.23%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.23%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 96        | 61.94%  |
| Nvidia                 | 18        | 11.61%  |
| Lenovo                 | 13        | 8.39%   |
| AMD                    | 8         | 5.16%   |
| Plantronics            | 3         | 1.94%   |
| GN Netcom              | 3         | 1.94%   |
| Texas Instruments      | 2         | 1.29%   |
| Realtek Semiconductor  | 2         | 1.29%   |
| Generalplus Technology | 2         | 1.29%   |
| C-Media Electronics    | 2         | 1.29%   |
| Logitech               | 1         | 0.65%   |
| JMTek                  | 1         | 0.65%   |
| Google                 | 1         | 0.65%   |
| Focusrite-Novation     | 1         | 0.65%   |
| Dell                   | 1         | 0.65%   |
| Corsair                | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 19        | 11.66%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 15        | 9.2%    |
| Intel Comet Lake PCH cAVS                                                         | 11        | 6.75%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 6.75%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 10        | 6.13%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 3.07%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.45%   |
| Plantronics BT600                                                                 | 3         | 1.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.84%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.84%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.23%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia Audio device                                                               | 2         | 1.23%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.23%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.23%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.61%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.61%   |
| Logitech H555 Headset                                                             | 1         | 0.61%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.61%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.61%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.61%   |
| JMTek iTalk-02                                                                    | 1         | 0.61%   |
| Google Pixel earbuds                                                              | 1         | 0.61%   |
| GN Netcom Jabra Link 380                                                          | 1         | 0.61%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                   | 1         | 0.61%   |
| GN Netcom Jabra BIZ 2400 USB                                                      | 1         | 0.61%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.61%   |
| Generalplus Technology Usb Audio Device                                           | 1         | 0.61%   |
| Focusrite-Novation Scarlett 2i2 Camera                                            | 1         | 0.61%   |
| Dell AC511 Sound Bar                                                              | 1         | 0.61%   |
| Corsair VOID Wireless Gaming Dongle                                               | 1         | 0.61%   |
| C-Media Electronics Blue Snowball                                                 | 1         | 0.61%   |
| C-Media Electronics Audio Adapter                                                 | 1         | 0.61%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 38.89%  |
| SK Hynix            | 12        | 33.33%  |
| Crucial             | 3         | 8.33%   |
| Unknown             | 2         | 5.56%   |
| Micron Technology   | 2         | 5.56%   |
| Kingston            | 2         | 5.56%   |
| Smart               | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 5.41%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 5.41%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 2.7%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.7%    |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.7%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.7%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.7%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 2.7%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.7%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s    | 1         | 2.7%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 2.7%    |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 2.7%    |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.7%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 2.7%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 2.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.7%    |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 2.7%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.7%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 2.7%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.7%    |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 2.7%    |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 2.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 2.7%    |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 2.7%    |
| Crucial RAM CT16G4SFRA32A.M8FF 16GB SODIMM DDR4 3200MT/s     | 1         | 2.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 1         | 2.7%    |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 57.14%  |
| DDR3   | 10        | 35.71%  |
| LPDDR4 | 1         | 3.57%   |
| LPDDR3 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 96.3%   |
| Row Of Chips | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 10        | 35.71%  |
| 8192  | 9         | 32.14%  |
| 4096  | 8         | 28.57%  |
| 32768 | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 8         | 26.67%  |
| 3200  | 7         | 23.33%  |
| 1600  | 7         | 23.33%  |
| 1333  | 3         | 10%     |
| 2400  | 2         | 6.67%   |
| 2133  | 2         | 6.67%   |
| 1334  | 1         | 3.33%   |

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
| Chicony Electronics                    | 33        | 31.43%  |
| IMC Networks                           | 16        | 15.24%  |
| Acer                                   | 12        | 11.43%  |
| Realtek Semiconductor                  | 9         | 8.57%   |
| Microdia                               | 7         | 6.67%   |
| Logitech                               | 7         | 6.67%   |
| Sunplus Innovation Technology          | 6         | 5.71%   |
| Suyin                                  | 3         | 2.86%   |
| Lite-On Technology                     | 3         | 2.86%   |
| Samsung Electronics                    | 2         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.9%    |
| Unknown                                | 1         | 0.95%   |
| Syntek                                 | 1         | 0.95%   |
| Quanta                                 | 1         | 0.95%   |
| Microsoft                              | 1         | 0.95%   |
| Lenovo                                 | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 17        | 15.74%  |
| IMC Networks Integrated Camera                               | 14        | 12.96%  |
| Realtek Integrated_Webcam_HD                                 | 7         | 6.48%   |
| Acer Integrated Camera                                       | 7         | 6.48%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.7%    |
| Acer SunplusIT Integrated Camera                             | 4         | 3.7%    |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.78%   |
| Lite-On Integrated Camera                                    | 3         | 2.78%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 2.78%   |
| Chicony HP HD Camera                                         | 3         | 2.78%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 1.85%   |
| Microdia Webcam                                              | 2         | 1.85%   |
| Microdia Integrated Webcam                                   | 2         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 1.85%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.85%   |
| Acer Integrated IR Camera                                    | 2         | 1.85%   |
| Unknown FULL HD 1080P Webcam                                 | 1         | 0.93%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.93%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.93%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.93%   |
| Suyin HP Truevision HD                                       | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.93%   |
| Sunplus Integrated Webcam                                    | 1         | 0.93%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.93%   |
| Realtek WEB CAMERA M9 Pro                                    | 1         | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.93%   |
| Quanta HP HD Camera                                          | 1         | 0.93%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.93%   |
| Microdia Integrated_Webcam_HD                                | 1         | 0.93%   |
| Logitech Webcam C925e                                        | 1         | 0.93%   |
| Logitech Webcam C310                                         | 1         | 0.93%   |
| Logitech B525 HD Webcam                                      | 1         | 0.93%   |
| Lenovo Integrated Webcam                                     | 1         | 0.93%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.93%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.93%   |
| Chicony Integrated IR Camera                                 | 1         | 0.93%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.93%   |
| Chicony HP Webcam                                            | 1         | 0.93%   |
| Chicony HD User Facing                                       | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.93%   |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 28        | 62.22%  |
| Validity Sensors           | 13        | 28.89%  |
| Upek                       | 2         | 4.44%   |
| Shenzhen Goodix Technology | 1         | 2.22%   |
| Elan Microelectronics      | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 46.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.22%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.22%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.22%   |

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
| 1     | 55        | 53.92%  |
| 0     | 35        | 34.31%  |
| 2     | 9         | 8.82%   |
| 3     | 2         | 1.96%   |
| 4     | 1         | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 45        | 54.88%  |
| Graphics card         | 13        | 15.85%  |
| Chipcard              | 11        | 13.41%  |
| Net/wireless          | 4         | 4.88%   |
| Net/ethernet          | 2         | 2.44%   |
| Multimedia controller | 2         | 2.44%   |
| Card reader           | 2         | 2.44%   |
| Bluetooth             | 2         | 2.44%   |
| Storage               | 1         | 1.22%   |

