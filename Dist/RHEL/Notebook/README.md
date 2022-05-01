RHEL - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for RHEL.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 196

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo   | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell     | Precision 5550              | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell     | Precision 7560              | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo   | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| Lenovo   | ThinkPad X1 Yoga 1st 20F... | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell     | Latitude E5570              | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo   | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP       | EliteBook 8460p             | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung  | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| ASUSTek  | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| Toshiba  | Satellite Pro R50-C         | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba  | Satellite Pro R50-C         | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell     | Precision 3551              | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [6c62008ae3](https://linux-hardware.org/?probe=6c62008ae3) | Dec 21, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [6f29b7bde7](https://linux-hardware.org/?probe=6f29b7bde7) | Dec 21, 2021 |
| Lenovo   | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [f88a7d7f15](https://linux-hardware.org/?probe=f88a7d7f15) | Dec 06, 2021 |
| Acer     | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [cd6c668ae9](https://linux-hardware.org/?probe=cd6c668ae9) | Nov 29, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP       | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo   | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [ab905debb9](https://linux-hardware.org/?probe=ab905debb9) | Nov 17, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo   | ThinkPad P50 20ENS1L000     | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo   | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo   | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| HP       | ZBook Firefly 15 inch G8... | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| Lenovo   | ThinkPad P50 20ENS1L000     | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K90... | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| Lenovo   | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo   | ThinkPad X230 Tablet 343... | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell     | XPS 15 9560                 | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek  | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek  | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell     | XPS 15 9560                 | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| HP       | ZBook 15 G5                 | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Dell     | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP       | EliteBook 850 G7 Noteboo... | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell     | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell     | Latitude E6430              | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell     | Latitude E6430              | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo   | ThinkPad P15 Gen 1 20SUS... | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Dell     | Precision 3541              | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP       | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP       | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell     | Latitude E6530              | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [779849778e](https://linux-hardware.org/?probe=779849778e) | May 26, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell     | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP       | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [bb1cb9b30a](https://linux-hardware.org/?probe=bb1cb9b30a) | Apr 02, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [433f10b16b](https://linux-hardware.org/?probe=433f10b16b) | Mar 16, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo   | ThinkPad T460 20FMS1VA09    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo   | ThinkPad T460 20FMS1VA09    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo   | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek  | Zephyrus G GU502DU_GA502... | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| Dell     | Precision 5510              | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony     | VPCEB4L1R                   | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP       | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Lenovo   | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo   | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo   | ThinkPad L480 20LSCTO1WW    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo   | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| Lenovo   | ThinkPad T480s 20L8S2N80... | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [e3d128beda](https://linux-hardware.org/?probe=e3d128beda) | Dec 28, 2020 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell     | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell     | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP       | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo   | ThinkpadT460 20BUS0QT0A     | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP       | ZBook 14u G6                | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell     | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO   | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell     | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell     | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell     | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO   | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO   | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell     | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP       | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell     | Precision 7510              | [9d901b2f8e](https://linux-hardware.org/?probe=9d901b2f8e) | Nov 01, 2020 |
| Dell     | Precision 7510              | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo   | ThinkPad T520 42404CG       | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo   | ThinkPad T520 42404CG       | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo   | ThinkPad T14s Gen 1 20UJ... | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell     | Latitude 5300               | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell     | Latitude 5300               | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP       | Pavilion 14                 | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo   | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo   | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| Lenovo   | ThinkPad P50 20EN0005UK     | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| Dell     | Inspiron 5567               | [a9d66d8f86](https://linux-hardware.org/?probe=a9d66d8f86) | Sep 15, 2020 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP       | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell     | Inspiron N5110              | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell     | Inspiron N5110              | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek  | GL502VMK                    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| Lenovo   | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell     | Latitude 5300               | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi     | TM1707                      | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi     | TM1707                      | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek  | GL502VMK                    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell     | Latitude 5300               | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo   | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP       | ProBook 430 G5              | [20760711e1](https://linux-hardware.org/?probe=20760711e1) | May 24, 2020 |
| HP       | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP       | ProBook 430 G5              | [53ccb8b4bf](https://linux-hardware.org/?probe=53ccb8b4bf) | May 23, 2020 |
| HP       | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell     | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell     | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Dell     | Inspiron 5567               | [6cc6232ddf](https://linux-hardware.org/?probe=6cc6232ddf) | Apr 14, 2020 |
| Lenovo   | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo   | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony     | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony     | VPCEB23FM                   | [4cde30cfa5](https://linux-hardware.org/?probe=4cde30cfa5) | Feb 26, 2020 |
| Sony     | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo   | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo   | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo   | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [73b2494a42](https://linux-hardware.org/?probe=73b2494a42) | Jan 22, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [92086a7925](https://linux-hardware.org/?probe=92086a7925) | Jan 14, 2020 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [c24f015f0f](https://linux-hardware.org/?probe=c24f015f0f) | Jan 13, 2020 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell     | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP       | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP       | 250 G4 Notebook PC          | [e5994eed73](https://linux-hardware.org/?probe=e5994eed73) | Nov 07, 2019 |
| HP       | 250 G4 Notebook PC          | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo   | ThinkPad T480s 20L8S2N80... | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell     | Latitude 7390               | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell     | Latitude 7390               | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo   | ThinkPad L480 20LSS0M100    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Lenovo   | ThinkPad X131e 3368CTO      | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| RHEL 8 | 97        | 88.99%  |
| RHEL 7 | 9         | 8.26%   |
| RHEL 9 | 3         | 2.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| RHEL | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 7.41%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 9         | 6.67%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 5.93%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 5.93%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 5.19%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 5         | 3.7%    |
| 4.18.0-193.19.1.el8_2.x86_64 | 5         | 3.7%    |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 2.96%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 2.96%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 2.96%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 2.96%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 2.96%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 2.96%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.22%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.22%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.22%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3         | 2.22%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.22%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.22%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.22%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 2.22%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.22%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.48%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.48%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.48%   |
| 3.10.0-1127.13.1.el7.x86_64  | 2         | 1.48%   |
| 3.10.0-1062.18.1.el7.x86_64  | 2         | 1.48%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.74%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1         | 0.74%   |
| 5.14.0-39.el9.x86_64         | 1         | 0.74%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 0.74%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.74%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.74%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1         | 0.74%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1         | 0.74%   |
| 4.18.0-193.23.1.el8_2.x86_64 | 1         | 0.74%   |
| 4.18.0-193.13.2.el8_2.x86_64 | 1         | 0.74%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1         | 0.74%   |
| 4.18.0-168.el8.x86_64        | 1         | 0.74%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 1         | 0.74%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1         | 0.74%   |
| 4.18.0-144.el8.x86_64        | 1         | 0.74%   |
| 3.10.0-957.el7.x86_64        | 1         | 0.74%   |
| 3.10.0-957.21.3.el7.x86_64   | 1         | 0.74%   |
| 3.10.0-957.10.1.el7.x86_64   | 1         | 0.74%   |
| 3.10.0-1160.6.1.el7.x86_64   | 1         | 0.74%   |
| 3.10.0-1160.53.1.el7.x86_64  | 1         | 0.74%   |
| 3.10.0-1160.21.1.el7.x86_64  | 1         | 0.74%   |
| 3.10.0-1160.15.2.el7.x86_64  | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 96        | 88.07%  |
| 3.10.0  | 9         | 8.26%   |
| 5.14.0  | 3         | 2.75%   |
| 5.9.1   | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 96        | 88.07%  |
| 3.10    | 9         | 8.26%   |
| 5.14    | 3         | 2.75%   |
| 5.9     | 1         | 0.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 108       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 90        | 78.95%  |
| Unknown       | 13        | 11.4%   |
| GNOME Classic | 8         | 7.02%   |
| KDE5          | 2         | 1.75%   |
| Cinnamon      | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 68        | 60.71%  |
| Wayland | 39        | 34.82%  |
| Unknown | 5         | 4.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 81.08%  |
| GDM     | 21        | 18.92%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 67.57%  |
| Unknown | 10        | 9.01%   |
| en_GB   | 5         | 4.5%    |
| fr_FR   | 4         | 3.6%    |
| pt_BR   | 2         | 1.8%    |
| pl_PL   | 2         | 1.8%    |
| nl_NL   | 2         | 1.8%    |
| en_IN   | 2         | 1.8%    |
| de_DE   | 2         | 1.8%    |
| ru_RU   | 1         | 0.9%    |
| ja_JP   | 1         | 0.9%    |
| it_IT   | 1         | 0.9%    |
| es_ES   | 1         | 0.9%    |
| es_EC   | 1         | 0.9%    |
| en_IE   | 1         | 0.9%    |
| de_CH   | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 76.79%  |
| BIOS | 26        | 23.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 94        | 87.04%  |
| Ext4 | 14        | 12.96%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 79.46%  |
| GPT     | 20        | 17.86%  |
| MBR     | 3         | 2.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 98.17%  |
| Yes       | 2         | 1.83%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 94.5%   |
| Yes       | 6         | 5.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 63        | 58.33%  |
| Dell                | 22        | 20.37%  |
| Hewlett-Packard     | 11        | 10.19%  |
| ASUSTek Computer    | 4         | 3.7%    |
| Sony                | 2         | 1.85%   |
| TUXEDO              | 1         | 0.93%   |
| Toshiba             | 1         | 0.93%   |
| Timi                | 1         | 0.93%   |
| Samsung Electronics | 1         | 0.93%   |
| Gigabyte Technology | 1         | 0.93%   |
| Acer                | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 3.7%    |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.85%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.85%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.85%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.85%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.85%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.85%   |
| HP EliteBook 8460p                       | 2         | 1.85%   |
| Dell Latitude E6430                      | 2         | 1.85%   |
| Dell Latitude 5300                       | 2         | 1.85%   |
| TUXEDO N13xWU                            | 1         | 0.93%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.93%   |
| Timi TM1707                              | 1         | 0.93%   |
| Sony VPCEB4L1R                           | 1         | 0.93%   |
| Sony VPCEB23FM                           | 1         | 0.93%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.93%   |
| Lenovo Z40-70 20366                      | 1         | 0.93%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.93%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.93%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.93%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.93%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.93%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.93%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.93%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.93%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.93%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.93%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.93%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.93%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N3S5DU27          | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S29D02          | 1         | 0.93%   |
| Lenovo ThinkPad T470p 20J7S0FA0E         | 1         | 0.93%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.93%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.93%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N    | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D12    | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0C    | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH0T     | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1S3B00F     | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1S38414     | 1         | 0.93%   |
| Lenovo ThinkPad P52 20MAS17205           | 1         | 0.93%   |
| Lenovo ThinkPad P52 20M9CTO1WW           | 1         | 0.93%   |
| Lenovo ThinkPad P50 20ENS1L000           | 1         | 0.93%   |
| Lenovo ThinkPad P50 20EN0005UK           | 1         | 0.93%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 0.93%   |
| Lenovo ThinkPad P15 Gen 1 20SUS34800     | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V      | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40K      | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 2 20QUS1H300      | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 2 20QUS10L0L      | 1         | 0.93%   |
| Lenovo ThinkPad L480 20LSS0M100          | 1         | 0.93%   |
| Lenovo ThinkPad L480 20LSCTO1WW          | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 60        | 55.56%  |
| Dell Latitude       | 10        | 9.26%   |
| Dell Precision      | 7         | 6.48%   |
| HP EliteBook        | 4         | 3.7%    |
| HP ZBook            | 3         | 2.78%   |
| Dell Inspiron       | 3         | 2.78%   |
| TUXEDO N13xWU       | 1         | 0.93%   |
| Toshiba Satellite   | 1         | 0.93%   |
| Timi TM1707         | 1         | 0.93%   |
| Sony VPCEB4L1R      | 1         | 0.93%   |
| Sony VPCEB23FM      | 1         | 0.93%   |
| Samsung 730QCJ      | 1         | 0.93%   |
| Lenovo Z40-70       | 1         | 0.93%   |
| Lenovo ThinkpadT460 | 1         | 0.93%   |
| Lenovo ThinkBook    | 1         | 0.93%   |
| HP ProBook          | 1         | 0.93%   |
| HP Pavilion         | 1         | 0.93%   |
| HP OMEN             | 1         | 0.93%   |
| HP 250              | 1         | 0.93%   |
| Gigabyte AERO       | 1         | 0.93%   |
| Dell XPS            | 1         | 0.93%   |
| Dell G3             | 1         | 0.93%   |
| ASUS Zephyrus       | 1         | 0.93%   |
| ASUS X550VX         | 1         | 0.93%   |
| ASUS TUF            | 1         | 0.93%   |
| ASUS GL502VMK       | 1         | 0.93%   |
| Acer Nitro          | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 23.15%  |
| 2019 | 24        | 22.22%  |
| 2018 | 16        | 14.81%  |
| 2017 | 8         | 7.41%   |
| 2016 | 7         | 6.48%   |
| 2011 | 7         | 6.48%   |
| 2015 | 6         | 5.56%   |
| 2012 | 5         | 4.63%   |
| 2021 | 4         | 3.7%    |
| 2010 | 3         | 2.78%   |
| 2013 | 2         | 1.85%   |
| 2014 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94        | 86.24%  |
| Enabled  | 15        | 13.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 39        | 35.14%  |
| 16.01-24.0  | 21        | 18.92%  |
| 8.01-16.0   | 19        | 17.12%  |
| 4.01-8.0    | 18        | 16.22%  |
| 64.01-256.0 | 7         | 6.31%   |
| 3.01-4.0    | 6         | 5.41%   |
| 24.01-32.0  | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 51        | 40.8%   |
| 8.01-16.0  | 23        | 18.4%   |
| 3.01-4.0   | 19        | 15.2%   |
| 2.01-3.0   | 16        | 12.8%   |
| 1.01-2.0   | 10        | 8%      |
| 16.01-24.0 | 3         | 2.4%    |
| 32.01-64.0 | 1         | 0.8%    |
| 24.01-32.0 | 1         | 0.8%    |
| 0.51-1.0   | 1         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 75.89%  |
| 2      | 17        | 15.18%  |
| 3      | 9         | 8.04%   |
| 4      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 88.07%  |
| Yes       | 13        | 11.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 88.07%  |
| No        | 13        | 11.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 99.07%  |
| No        | 1         | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 76.11%  |
| No        | 27        | 23.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 27        | 24.77%  |
| India        | 14        | 12.84%  |
| UK           | 6         | 5.5%    |
| Germany      | 6         | 5.5%    |
| France       | 5         | 4.59%   |
| Spain        | 4         | 3.67%   |
| Netherlands  | 3         | 2.75%   |
| Mexico       | 3         | 2.75%   |
| Czechia      | 3         | 2.75%   |
| Switzerland  | 2         | 1.83%   |
| South Africa | 2         | 1.83%   |
| Singapore    | 2         | 1.83%   |
| Romania      | 2         | 1.83%   |
| Japan        | 2         | 1.83%   |
| Italy        | 2         | 1.83%   |
| Canada       | 2         | 1.83%   |
| Brazil       | 2         | 1.83%   |
| Australia    | 2         | 1.83%   |
| Turkey       | 1         | 0.92%   |
| Saudi Arabia | 1         | 0.92%   |
| Russia       | 1         | 0.92%   |
| Portugal     | 1         | 0.92%   |
| Poland       | 1         | 0.92%   |
| Pakistan     | 1         | 0.92%   |
| Nepal        | 1         | 0.92%   |
| Myanmar      | 1         | 0.92%   |
| Morocco      | 1         | 0.92%   |
| Luxembourg   | 1         | 0.92%   |
| Lithuania    | 1         | 0.92%   |
| Kuwait       | 1         | 0.92%   |
| Israel       | 1         | 0.92%   |
| Ireland      | 1         | 0.92%   |
| Georgia      | 1         | 0.92%   |
| Ecuador      | 1         | 0.92%   |
| Colombia     | 1         | 0.92%   |
| Bulgaria     | 1         | 0.92%   |
| Armenia      | 1         | 0.92%   |
| Argentina    | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Munich                   | 3         | 2.54%   |
| Mexico City              | 3         | 2.54%   |
| Singapore                | 2         | 1.69%   |
| Prague                   | 2         | 1.69%   |
| Mumbai                   | 2         | 1.69%   |
| Milan                    | 2         | 1.69%   |
| Madrid                   | 2         | 1.69%   |
| Doetinchem               | 2         | 1.69%   |
| Zaragoza                 | 1         | 0.85%   |
| Yerevan                  | 1         | 0.85%   |
| Webster                  | 1         | 0.85%   |
| Taringa                  | 1         | 0.85%   |
| Sumida                   | 1         | 0.85%   |
| Stroud                   | 1         | 0.85%   |
| Sofia                    | 1         | 0.85%   |
| Sheffield                | 1         | 0.85%   |
| San Jose                 | 1         | 0.85%   |
| San Francisco            | 1         | 0.85%   |
| Sammamish                | 1         | 0.85%   |
| SalÃ©                  | 1         | 0.85%   |
| Saint-Ismier             | 1         | 0.85%   |
| Saint-Alphonse-Rodriguez | 1         | 0.85%   |
| Saint Paul               | 1         | 0.85%   |
| Sagaing                  | 1         | 0.85%   |
| Roudnice nad Labem       | 1         | 0.85%   |
| Roha                     | 1         | 0.85%   |
| Rochester                | 1         | 0.85%   |
| Reims                    | 1         | 0.85%   |
| Raleigh                  | 1         | 0.85%   |
| Quito                    | 1         | 0.85%   |
| Queenscliff              | 1         | 0.85%   |
| Queens                   | 1         | 0.85%   |
| Pune                     | 1         | 0.85%   |
| Providence               | 1         | 0.85%   |
| Portalegre               | 1         | 0.85%   |
| Port Elizabeth           | 1         | 0.85%   |
| Pleasanton               | 1         | 0.85%   |
| Pickerington             | 1         | 0.85%   |
| Paraiso do Tocantins     | 1         | 0.85%   |
| Paragould                | 1         | 0.85%   |
| Oyama                    | 1         | 0.85%   |
| Ottawa                   | 1         | 0.85%   |
| Ommen                    | 1         | 0.85%   |
| Ogden                    | 1         | 0.85%   |
| New Delhi                | 1         | 0.85%   |
| Neuves-Maisons           | 1         | 0.85%   |
| Mountain View            | 1         | 0.85%   |
| Moscow                   | 1         | 0.85%   |
| Miroslava                | 1         | 0.85%   |
| Mangalore                | 1         | 0.85%   |
| Manchester               | 1         | 0.85%   |
| Luxembourg               | 1         | 0.85%   |
| London                   | 1         | 0.85%   |
| Lohmar                   | 1         | 0.85%   |
| Loganville               | 1         | 0.85%   |
| Littleton                | 1         | 0.85%   |
| Lahore                   | 1         | 0.85%   |
| Kuwait City              | 1         | 0.85%   |
| Kochi                    | 1         | 0.85%   |
| Khobar                   | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 53     | 24.82%  |
| WDC                 | 16        | 22     | 11.68%  |
| Toshiba             | 13        | 18     | 9.49%   |
| Sandisk             | 12        | 17     | 8.76%   |
| SK Hynix            | 11        | 11     | 8.03%   |
| Seagate             | 11        | 14     | 8.03%   |
| Intel               | 8         | 11     | 5.84%   |
| Unknown             | 6         | 8      | 4.38%   |
| Micron Technology   | 5         | 7      | 3.65%   |
| Kingston            | 3         | 3      | 2.19%   |
| HGST                | 3         | 3      | 2.19%   |
| Crucial             | 3         | 3      | 2.19%   |
| Lenovo              | 2         | 2      | 1.46%   |
| A-DATA Technology   | 2         | 2      | 1.46%   |
| Transcend           | 1         | 1      | 0.73%   |
| Team                | 1         | 2      | 0.73%   |
| SMI                 | 1         | 2      | 0.73%   |
| Silicon Motion      | 1         | 2      | 0.73%   |
| SABRENT             | 1         | 1      | 0.73%   |
| PNY                 | 1         | 4      | 0.73%   |
| Lite-On             | 1         | 1      | 0.73%   |
| Corsair             | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB        | 10        | 6.71%   |
| Sandisk NVMe SSD Drive 256GB         | 6         | 4.03%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 3.36%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 3.36%   |
| Samsung NVMe SSD Drive 1024GB        | 5         | 3.36%   |
| Intel NVMe SSD Drive 512GB           | 4         | 2.68%   |
| Toshiba NVMe SSD Drive 512GB         | 3         | 2.01%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 3         | 2.01%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 2.01%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 2.01%   |
| Micron NVMe SSD Drive 256GB          | 3         | 2.01%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 1.34%   |
| Toshiba NVMe SSD Drive 1024GB        | 2         | 1.34%   |
| Seagate Expansion+ 2TB               | 2         | 1.34%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 1.34%   |
| Samsung SSD 860 EVO 1TB              | 2         | 1.34%   |
| Samsung Portable SSD T5 500GB        | 2         | 1.34%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 1.34%   |
| Intel NVMe SSD Drive 2TB             | 2         | 1.34%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.67%   |
| WDC WDS400T2B0A-00SM50 4TB SSD       | 1         | 0.67%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.67%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.67%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.67%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1         | 0.67%   |
| WDC WD20 SPZX-11UA7T0 2TB            | 1         | 0.67%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.67%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.67%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.67%   |
| WDC WD10SPCX-75KHST0 1TB             | 1         | 0.67%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.67%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.67%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.67%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 1         | 0.67%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.67%   |
| Unknown MMC Card  33GB               | 1         | 0.67%   |
| Unknown MMC Card  32GB               | 1         | 0.67%   |
| Unknown MMC Card  16GB               | 1         | 0.67%   |
| Unknown MMC Card  128GB              | 1         | 0.67%   |
| Transcend TS512GMTS800 512GB SSD     | 1         | 0.67%   |
| Toshiba TR150 960GB SSD              | 1         | 0.67%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.67%   |
| Toshiba MK3275GSX 320GB              | 1         | 0.67%   |
| Toshiba KXG6AZNV256G 256GB           | 1         | 0.67%   |
| Toshiba HDWL110 1TB                  | 1         | 0.67%   |
| Team T253X2512G 512GB SSD            | 1         | 0.67%   |
| SMI DISK 506GB                       | 1         | 0.67%   |
| SK Hynix NVMe SSD Drive 1024GB       | 1         | 0.67%   |
| Silicon Motion NVMe SSD Drive 1TB    | 1         | 0.67%   |
| Seagate ST9320325AS 320GB            | 1         | 0.67%   |
| Seagate ST9160827AS 160GB            | 1         | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 0.67%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.67%   |
| Seagate BUP Slim BK 1TB              | 1         | 0.67%   |
| Seagate BUP Portable 5TB             | 1         | 0.67%   |
| Seagate BUP BL 4TB                   | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 13     | 40.74%  |
| WDC     | 9         | 13     | 33.33%  |
| Toshiba | 3         | 5      | 11.11%  |
| HGST    | 3         | 3      | 11.11%  |
| SABRENT | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 38.24%  |
| WDC                 | 3         | 4      | 8.82%   |
| SanDisk             | 3         | 4      | 8.82%   |
| Kingston            | 3         | 3      | 8.82%   |
| Crucial             | 3         | 3      | 8.82%   |
| A-DATA Technology   | 2         | 2      | 5.88%   |
| Transcend           | 1         | 1      | 2.94%   |
| Toshiba             | 1         | 1      | 2.94%   |
| Team                | 1         | 2      | 2.94%   |
| Seagate             | 1         | 1      | 2.94%   |
| PNY                 | 1         | 4      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| Corsair             | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 72        | 105    | 52.94%  |
| SSD     | 32        | 41     | 23.53%  |
| HDD     | 27        | 35     | 19.85%  |
| MMC     | 4         | 5      | 2.94%   |
| Unknown | 1         | 2      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 72        | 105    | 55.81%  |
| SATA | 43        | 67     | 33.33%  |
| SAS  | 10        | 11     | 7.75%   |
| MMC  | 4         | 5      | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 32     | 44.64%  |
| 0.51-1.0   | 22        | 33     | 39.29%  |
| 1.01-2.0   | 5         | 7      | 8.93%   |
| 3.01-4.0   | 3         | 3      | 5.36%   |
| 4.01-10.0  | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 41.96%  |
| 251-500        | 22        | 19.64%  |
| 501-1000       | 16        | 14.29%  |
| 1001-2000      | 9         | 8.04%   |
| More than 3000 | 5         | 4.46%   |
| 51-100         | 5         | 4.46%   |
| 21-50          | 3         | 2.68%   |
| 1-20           | 2         | 1.79%   |
| Unknown        | 2         | 1.79%   |
| 2001-3000      | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 23.97%  |
| 21-50          | 27        | 22.31%  |
| 1-20           | 24        | 19.83%  |
| 51-100         | 16        | 13.22%  |
| 251-500        | 13        | 10.74%  |
| 501-1000       | 7         | 5.79%   |
| Unknown        | 2         | 1.65%   |
| More than 3000 | 1         | 0.83%   |
| 2001-3000      | 1         | 0.83%   |
| 1001-2000      | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Transcend TS512GMTS800 512GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Notebooks | Drives | Percent |
|-----------|-----------|--------|---------|
| Transcend | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 91        | 159    | 79.82%  |
| Works    | 22        | 28     | 19.3%   |
| Malfunc  | 1         | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 56        | 45.53%  |
| Samsung Electronics          | 23        | 18.7%   |
| Sandisk                      | 13        | 10.57%  |
| SK Hynix                     | 11        | 8.94%   |
| Toshiba America Info Systems | 9         | 7.32%   |
| Micron Technology            | 4         | 3.25%   |
| Lenovo                       | 2         | 1.63%   |
| KIOXIA                       | 2         | 1.63%   |
| Silicon Motion               | 1         | 0.81%   |
| Lite-On Technology           | 1         | 0.81%   |
| AMD                          | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 17        | 13.6%   |
| SK Hynix Non-Volatile memory controller                                       | 11        | 8.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 10        | 8%      |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                    | 9         | 7.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 8         | 6.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 4.8%    |
| Micron Non-Volatile memory controller                                         | 4         | 3.2%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 4         | 3.2%    |
| Intel SSD 660P Series                                                         | 4         | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 2.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.4%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 2         | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 1.6%    |
| Samsung NVMe SSD Controller 980                                               | 2         | 1.6%    |
| Lenovo Non-Volatile memory controller                                         | 2         | 1.6%    |
| KIOXIA Non-Volatile memory controller                                         | 2         | 1.6%    |
| Intel SATA Controller [RAID mode]                                             | 2         | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.6%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 0.8%    |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 0.8%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.8%    |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 0.8%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 72        | 58.54%  |
| SATA | 44        | 35.77%  |
| RAID | 7         | 5.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 104       | 96.3%   |
| AMD    | 4         | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 9.26%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 8.33%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 5.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 4.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 3.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 2.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.78%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.85%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.85%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.93%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.93%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.93%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.93%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.93%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.93%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.93%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 1         | 0.93%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 0.93%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 0.93%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 0.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 0.93%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 0.93%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 64        | 59.26%  |
| Intel Core i5   | 26        | 24.07%  |
| Intel Xeon      | 5         | 4.63%   |
| Intel Core i3   | 4         | 3.7%    |
| Other           | 3         | 2.78%   |
| AMD Ryzen 7     | 3         | 2.78%   |
| Intel Core i9   | 2         | 1.85%   |
| AMD Ryzen 7 PRO | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 53        | 49.07%  |
| 2      | 28        | 25.93%  |
| 6      | 20        | 18.52%  |
| 8      | 7         | 6.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 105       | 97.22%  |
| 1      | 3         | 2.78%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 93.64%  |
| Unknown        | 7         | 6.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 26        | 23.64%  |
| 0x806ea    | 12        | 10.91%  |
| 0xa0652    | 11        | 10%     |
| 0x906ea    | 7         | 6.36%   |
| 0x206a7    | 7         | 6.36%   |
| 0x506e3    | 6         | 5.45%   |
| 0x406e3    | 5         | 4.55%   |
| 0x306a9    | 5         | 4.55%   |
| 0x906ed    | 4         | 3.64%   |
| 0x806e9    | 4         | 3.64%   |
| 0x906e9    | 3         | 2.73%   |
| 0x806d1    | 3         | 2.73%   |
| 0x306d4    | 3         | 2.73%   |
| 0x20655    | 3         | 2.73%   |
| Unknown    | 3         | 2.73%   |
| 0x40651    | 2         | 1.82%   |
| 0x08108102 | 2         | 1.82%   |
| 0x806c1    | 1         | 0.91%   |
| 0x20652    | 1         | 0.91%   |
| 0x08600104 | 1         | 0.91%   |
| 0x08600103 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 57        | 52.29%  |
| Skylake     | 11        | 10.09%  |
| CometLake   | 11        | 10.09%  |
| SandyBridge | 7         | 6.42%   |
| IvyBridge   | 5         | 4.59%   |
| Westmere    | 4         | 3.67%   |
| Icelake     | 3         | 2.75%   |
| Broadwell   | 3         | 2.75%   |
| Zen+        | 2         | 1.83%   |
| Zen 2       | 2         | 1.83%   |
| Haswell     | 2         | 1.83%   |
| TigerLake   | 1         | 0.92%   |
| Unknown     | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 93        | 67.39%  |
| Nvidia | 33        | 23.91%  |
| AMD    | 12        | 8.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 17        | 12.32%  |
| Intel UHD Graphics 620                                                                | 12        | 8.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 10        | 7.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 7.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 5.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 5         | 3.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 3.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 5         | 3.62%   |
| Intel HD Graphics 620                                                                 | 4         | 2.9%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                 | 3         | 2.17%   |
| Intel HD Graphics 5500                                                                | 3         | 2.17%   |
| Intel HD Graphics 530                                                                 | 3         | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.45%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 2         | 1.45%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 2         | 1.45%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 1.45%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 2         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.45%   |
| Intel HD Graphics 630                                                                 | 2         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.45%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 1.45%   |
| AMD Renoir                                                                            | 2         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.72%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.72%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.72%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.72%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.72%   |
| Nvidia GK107GLM [Quadro K2000M]                                                       | 1         | 0.72%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                      | 1         | 0.72%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.72%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 0.72%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                                    | 1         | 0.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.72%   |
| Intel Iris Pro Graphics P580                                                          | 1         | 0.72%   |
| Intel HD Graphics P530                                                                | 1         | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.72%   |
| AMD Meso XT [Radeon R5 M315]                                                          | 1         | 0.72%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 0.72%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 59.63%  |
| Intel + Nvidia | 23        | 21.1%   |
| 1 x Nvidia     | 9         | 8.26%   |
| Intel + AMD    | 5         | 4.59%   |
| 1 x AMD        | 5         | 4.59%   |
| AMD + Nvidia   | 2         | 1.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 95        | 86.36%  |
| Proprietary | 12        | 10.91%  |
| Unknown     | 3         | 2.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 69.09%  |
| 3.01-4.0   | 11        | 10%     |
| 1.01-2.0   | 9         | 8.18%   |
| 5.01-6.0   | 5         | 4.55%   |
| 0.51-1.0   | 5         | 4.55%   |
| 0.01-0.5   | 2         | 1.82%   |
| 7.01-8.0   | 1         | 0.91%   |
| 8.01-16.0  | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 15.29%  |
| BOE                     | 19        | 12.1%   |
| LG Display              | 17        | 10.83%  |
| Chimei Innolux          | 17        | 10.83%  |
| Dell                    | 16        | 10.19%  |
| Samsung Electronics     | 12        | 7.64%   |
| Lenovo                  | 11        | 7.01%   |
| Sharp                   | 6         | 3.82%   |
| InfoVision              | 5         | 3.18%   |
| Hewlett-Packard         | 5         | 3.18%   |
| Goldstar                | 5         | 3.18%   |
| Acer                    | 3         | 1.91%   |
| Philips                 | 2         | 1.27%   |
| PANDA                   | 2         | 1.27%   |
| LGD                     | 2         | 1.27%   |
| BOE Technology Group    | 2         | 1.27%   |
| AOC                     | 2         | 1.27%   |
| Sun                     | 1         | 0.64%   |
| Sceptre Tech            | 1         | 0.64%   |
| Planar                  | 1         | 0.64%   |
| ITE                     | 1         | 0.64%   |
| Eizo                    | 1         | 0.64%   |
| Chi Mei Optoelectronics | 1         | 0.64%   |
| ASUSTek Computer        | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 3.66%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 2.44%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 2.44%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.83%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.83%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.83%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.83%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 3         | 1.83%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 1.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.22%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.22%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.22%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.22%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.22%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 1.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2         | 1.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.22%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.22%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.61%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.61%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.61%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.61%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.61%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.61%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.61%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 700x400mm 31.7-inch    | 1         | 0.61%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                 | 1         | 0.61%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.61%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 1         | 0.61%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch              | 1         | 0.61%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 0.61%   |
| Lenovo LEN L27m-28 LEN65E6 1920x1080 597x336mm 27.0-inch              | 1         | 0.61%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 58.21%  |
| 1366x768 (WXGA)    | 16        | 11.94%  |
| 3840x2160 (4K)     | 8         | 5.97%   |
| 2560x1440 (QHD)    | 8         | 5.97%   |
| 1600x900 (HD+)     | 7         | 5.22%   |
| 1920x1200 (WUXGA)  | 4         | 2.99%   |
| 2560x1080          | 3         | 2.24%   |
| 1680x1050 (WSXGA+) | 2         | 1.49%   |
| Unknown            | 2         | 1.49%   |
| 6400x2160          | 1         | 0.75%   |
| 3840x1080          | 1         | 0.75%   |
| 3440x1440          | 1         | 0.75%   |
| 2048x1152          | 1         | 0.75%   |
| 1440x900 (WXGA+)   | 1         | 0.75%   |
| 1280x800 (WXGA)    | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 45        | 28.66%  |
| 14      | 27        | 17.2%   |
| 13      | 20        | 12.74%  |
| 24      | 15        | 9.55%   |
| 27      | 14        | 8.92%   |
| 23      | 8         | 5.1%    |
| 12      | 5         | 3.18%   |
| 34      | 4         | 2.55%   |
| Unknown | 4         | 2.55%   |
| 21      | 3         | 1.91%   |
| 17      | 3         | 1.91%   |
| 31      | 2         | 1.27%   |
| 22      | 2         | 1.27%   |
| 49      | 1         | 0.64%   |
| 32      | 1         | 0.64%   |
| 19      | 1         | 0.64%   |
| 18      | 1         | 0.64%   |
| 11      | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 55.84%  |
| 501-600     | 31        | 20.13%  |
| 201-300     | 12        | 7.79%   |
| 401-500     | 7         | 4.55%   |
| 701-800     | 5         | 3.25%   |
| 601-700     | 5         | 3.25%   |
| Unknown     | 4         | 2.6%    |
| 351-400     | 3         | 1.95%   |
| 1001-1500   | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 101       | 83.47%  |
| 16/10   | 10        | 8.26%   |
| 21/9    | 4         | 3.31%   |
| Unknown | 4         | 3.31%   |
| 32/9    | 1         | 0.83%   |
| 3/2     | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 29.03%  |
| 81-90          | 41        | 26.45%  |
| 201-250        | 20        | 12.9%   |
| 301-350        | 14        | 9.03%   |
| 251-300        | 7         | 4.52%   |
| 71-80          | 6         | 3.87%   |
| 351-500        | 6         | 3.87%   |
| 61-70          | 5         | 3.23%   |
| Unknown        | 4         | 2.58%   |
| 121-130        | 3         | 1.94%   |
| 51-60          | 1         | 0.65%   |
| 151-200        | 1         | 0.65%   |
| 141-150        | 1         | 0.65%   |
| 501-1000       | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 52%     |
| 51-100        | 34        | 22.67%  |
| 101-120       | 22        | 14.67%  |
| 161-240       | 7         | 4.67%   |
| More than 240 | 5         | 3.33%   |
| Unknown       | 4         | 2.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 65        | 56.52%  |
| 2     | 38        | 33.04%  |
| 3     | 8         | 6.96%   |
| 0     | 4         | 3.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 96        | 58.9%   |
| Realtek Semiconductor             | 30        | 18.4%   |
| Lenovo                            | 15        | 9.2%    |
| Qualcomm Atheros                  | 5         | 3.07%   |
| Marvell Technology Group          | 2         | 1.23%   |
| Ericsson Business Mobile Networks | 2         | 1.23%   |
| Dell                              | 2         | 1.23%   |
| Broadcom Limited                  | 2         | 1.23%   |
| Xiaomi                            | 1         | 0.61%   |
| Sierra Wireless                   | 1         | 0.61%   |
| Samsung Electronics               | 1         | 0.61%   |
| Ralink                            | 1         | 0.61%   |
| Luminary Micro                    | 1         | 0.61%   |
| ICS Advent                        | 1         | 0.61%   |
| Huawei Technologies               | 1         | 0.61%   |
| DisplayLink                       | 1         | 0.61%   |
| Broadcom                          | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                     | 16        | 7.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 15        | 6.58%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 6.14%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11        | 4.82%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.39%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 10        | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 4.39%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 3.51%   |
| Intel Wireless 8260                                                            | 8         | 3.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 3.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.63%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 2.63%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 2.63%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.75%   |
| Intel Wireless 7265                                                            | 3         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 0.88%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.88%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.88%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.88%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.88%   |
| Intel Wireless 3165                                                            | 2         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.88%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.88%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                           | 2         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.44%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.44%   |
| Luminary Micro In-Circuit Debug Interface                                      | 1         | 0.44%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.44%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.44%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.44%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.44%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.44%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.44%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.44%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.44%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.44%   |
| Huawei E353/E3131                                                              | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 94        | 84.68%  |
| Realtek Semiconductor | 6         | 5.41%   |
| Qualcomm Atheros      | 5         | 4.5%    |
| Dell                  | 2         | 1.8%    |
| Sierra Wireless       | 1         | 0.9%    |
| Ralink                | 1         | 0.9%    |
| Broadcom Limited      | 1         | 0.9%    |
| Broadcom              | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 16        | 14.41%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 13.51%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 9.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 9.01%   |
| Intel Wireless 8260                                            | 8         | 7.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 6.31%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 5.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 5.41%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 3.6%    |
| Intel Wireless 7265                                            | 3         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.8%    |
| Intel Wireless-AC 9260                                         | 2         | 1.8%    |
| Intel Wireless 3165                                            | 2         | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.8%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 2         | 1.8%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.9%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.9%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.9%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 66        | 57.89%  |
| Realtek Semiconductor    | 25        | 21.93%  |
| Lenovo                   | 15        | 13.16%  |
| Marvell Technology Group | 2         | 1.75%   |
| Xiaomi                   | 1         | 0.88%   |
| Samsung Electronics      | 1         | 0.88%   |
| ICS Advent               | 1         | 0.88%   |
| Huawei Technologies      | 1         | 0.88%   |
| DisplayLink              | 1         | 0.88%   |
| Broadcom Limited         | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 12.28%  |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 8.77%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 8.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 8.77%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 7.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 5.26%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 5.26%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 3.51%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 3.51%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 2.63%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 2.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.75%   |
| Lenovo USB-C to LAN                                                            | 2         | 1.75%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.75%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.75%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.75%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.88%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.88%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.88%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.88%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.88%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.88%   |
| Huawei E353/E3131                                                              | 1         | 0.88%   |
| DisplayLink Plugable UGA-3000                                                  | 1         | 0.88%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 51.94%  |
| Ethernet | 96        | 46.6%   |
| Modem    | 3         | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 52.97%  |
| Ethernet | 86        | 46.49%  |
| Modem    | 1         | 0.54%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 80.56%  |
| 1     | 21        | 19.44%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102       | 93.58%  |
| Yes  | 7         | 6.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 82.56%  |
| Broadcom                        | 5         | 5.81%   |
| Qualcomm Atheros Communications | 2         | 2.33%   |
| IMC Networks                    | 2         | 2.33%   |
| Cambridge Silicon Radio         | 2         | 2.33%   |
| Realtek Semiconductor           | 1         | 1.16%   |
| Ralink                          | 1         | 1.16%   |
| Foxconn / Hon Hai               | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 25.58%  |
| Intel Bluetooth Device                                                              | 22        | 25.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 20.93%  |
| Intel AX200 Bluetooth                                                               | 6         | 6.98%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.16%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.16%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.16%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.16%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.16%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.16%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 104       | 63.8%   |
| Nvidia                 | 18        | 11.04%  |
| Lenovo                 | 13        | 7.98%   |
| AMD                    | 7         | 4.29%   |
| Realtek Semiconductor  | 3         | 1.84%   |
| Plantronics            | 3         | 1.84%   |
| GN Netcom              | 3         | 1.84%   |
| Texas Instruments      | 2         | 1.23%   |
| Generalplus Technology | 2         | 1.23%   |
| C-Media Electronics    | 2         | 1.23%   |
| Logitech               | 1         | 0.61%   |
| LG Electronics         | 1         | 0.61%   |
| JMTek                  | 1         | 0.61%   |
| Google                 | 1         | 0.61%   |
| Focusrite-Novation     | 1         | 0.61%   |
| Dell                   | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 21        | 12.28%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 17        | 9.94%   |
| Intel Comet Lake PCH cAVS                                                         | 11        | 6.43%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 6.43%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 10        | 5.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 4.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 3.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6         | 3.51%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.34%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4         | 2.34%   |
| Realtek Semiconductor USB Audio                                                   | 3         | 1.75%   |
| Plantronics BT600                                                                 | 3         | 1.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.75%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 1.75%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 1.75%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.75%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.17%   |
| Nvidia Audio device                                                               | 2         | 1.17%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.17%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 1.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.58%   |
| Logitech H555 Headset                                                             | 1         | 0.58%   |
| LG Electronics USB Audio                                                          | 1         | 0.58%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.58%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.58%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.58%   |
| JMTek iTalk-02                                                                    | 1         | 0.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.58%   |
| Google Pixel earbuds                                                              | 1         | 0.58%   |
| GN Netcom Jabra Link 380                                                          | 1         | 0.58%   |
| GN Netcom Jabra EVOLVE 20 MS                                                      | 1         | 0.58%   |
| GN Netcom Jabra BIZ 2400 USB                                                      | 1         | 0.58%   |
| Generalplus Technology USB Microphone                                             | 1         | 0.58%   |
| Generalplus Technology USB Audio Device                                           | 1         | 0.58%   |
| Focusrite-Novation Scarlett 2i2 Camera                                            | 1         | 0.58%   |
| Dell AC511 USB SoundBar                                                           | 1         | 0.58%   |
| C-Media Electronics Blue Snowball                                                 | 1         | 0.58%   |
| C-Media Electronics Audio Adapter                                                 | 1         | 0.58%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 0.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 42.11%  |
| SK Hynix            | 12        | 31.58%  |
| Crucial             | 3         | 7.89%   |
| Unknown             | 2         | 5.26%   |
| Micron Technology   | 2         | 5.26%   |
| Kingston            | 2         | 5.26%   |
| Smart               | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 5.13%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 5.13%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 5.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 5.13%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 2.56%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.56%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.56%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 2.56%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.56%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 2.56%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.56%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 2.56%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 2.56%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 2.56%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 2.56%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 2.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.56%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 2.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 2.56%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.56%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.56%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 2.56%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 2.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 2.56%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 2.56%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 2.56%   |
| Crucial RAM CT16G4SFRA32A.M8FF 16GB SODIMM DDR4 3200MT/s     | 1         | 2.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 60%     |
| DDR3   | 10        | 33.33%  |
| LPDDR4 | 1         | 3.33%   |
| LPDDR3 | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 96.55%  |
| Row Of Chips | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 11        | 36.67%  |
| 8192  | 9         | 30%     |
| 4096  | 9         | 30%     |
| 32768 | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 10        | 31.25%  |
| 1600  | 7         | 21.88%  |
| 3200  | 6         | 18.75%  |
| 2133  | 3         | 9.38%   |
| 1333  | 3         | 9.38%   |
| 2400  | 2         | 6.25%   |
| 1334  | 1         | 3.13%   |

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
| Chicony Electronics                    | 36        | 31.3%   |
| IMC Networks                           | 16        | 13.91%  |
| Acer                                   | 13        | 11.3%   |
| Realtek Semiconductor                  | 10        | 8.7%    |
| Microdia                               | 9         | 7.83%   |
| Logitech                               | 7         | 6.09%   |
| Sunplus Innovation Technology          | 6         | 5.22%   |
| Suyin                                  | 3         | 2.61%   |
| Lite-On Technology                     | 3         | 2.61%   |
| Unknown                                | 2         | 1.74%   |
| Syntek                                 | 2         | 1.74%   |
| Samsung Electronics                    | 2         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.74%   |
| Quanta                                 | 1         | 0.87%   |
| Microsoft                              | 1         | 0.87%   |
| LG Electronics                         | 1         | 0.87%   |
| Lenovo                                 | 1         | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 18        | 15.25%  |
| IMC Networks Integrated Camera                               | 13        | 11.02%  |
| Realtek Integrated_Webcam_HD                                 | 8         | 6.78%   |
| Acer Integrated Camera                                       | 8         | 6.78%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.39%   |
| Chicony Integrated Camera (1280x720@30)                      | 4         | 3.39%   |
| Chicony HP HD Camera                                         | 4         | 3.39%   |
| Acer SunplusIT Integrated Camera                             | 4         | 3.39%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.54%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.54%   |
| Lite-On Integrated Camera                                    | 3         | 2.54%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 2.54%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.54%   |
| Samsung Galaxy A5 (MTP)                                      | 2         | 1.69%   |
| Microdia Webcam                                              | 2         | 1.69%   |
| Microdia Integrated Webcam                                   | 2         | 1.69%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.69%   |
| Acer Integrated IR Camera                                    | 2         | 1.69%   |
| Unknown FULL HD 1080P Webcam                                 | 1         | 0.85%   |
| Unknown 720p HD Camera                                       | 1         | 0.85%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.85%   |
| Syntek Integrated Camera                                     | 1         | 0.85%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.85%   |
| Suyin HP Truevision HD                                       | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.85%   |
| Sunplus Integrated Webcam                                    | 1         | 0.85%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.85%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.85%   |
| Realtek NexiGo N960E FHD Webcam                              | 1         | 0.85%   |
| Quanta HP HD Camera                                          | 1         | 0.85%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.85%   |
| Logitech Webcam C925e                                        | 1         | 0.85%   |
| Logitech Webcam C310                                         | 1         | 0.85%   |
| Logitech B525 HD Webcam                                      | 1         | 0.85%   |
| LG LG UltraFine Display Camera                               | 1         | 0.85%   |
| Lenovo Integrated Webcam                                     | 1         | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.85%   |
| Chicony Integrated IR Camera                                 | 1         | 0.85%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.85%   |
| Chicony HP Webcam                                            | 1         | 0.85%   |
| Chicony HD User Facing                                       | 1         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.85%   |
| Acer Lenovo Integrated Webcam                                | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 30        | 60%     |
| Validity Sensors           | 14        | 28%     |
| Upek                       | 2         | 4%      |
| Shenzhen Goodix Technology | 2         | 4%      |
| Samsung Electronics        | 1         | 2%      |
| Elan Microelectronics      | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 42%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 12%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 6%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2%      |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2%      |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2%      |
| Shenzhen Goodix FingerPrint                                                | 1         | 2%      |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 2%      |
| Elan ELAN:Fingerprint                                                      | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 53.33%  |
| Alcor Micro | 4         | 26.67%  |
| Lenovo      | 2         | 13.33%  |
| Upek        | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 26.67%  |
| Broadcom 5880                                              | 3         | 20%     |
| Broadcom 58200                                             | 3         | 20%     |
| Lenovo Integrated Smart Card Reader                        | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 59        | 53.15%  |
| 0     | 39        | 35.14%  |
| 2     | 11        | 9.91%   |
| 3     | 2         | 1.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 57.47%  |
| Graphics card            | 12        | 13.79%  |
| Chipcard                 | 11        | 12.64%  |
| Card reader              | 4         | 4.6%    |
| Net/wireless             | 2         | 2.3%    |
| Net/ethernet             | 2         | 2.3%    |
| Bluetooth                | 2         | 2.3%    |
| Storage                  | 1         | 1.15%   |
| Multimedia controller    | 1         | 1.15%   |
| Communication controller | 1         | 1.15%   |
| Camera                   | 1         | 1.15%   |

