RHEL - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for RHEL.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL/Desktop/README.md) and [notebooks](/Dist/RHEL/Notebook/README.md).

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

Total: 341

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | Precision 5550              | Notebook    | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Precision 7560              | Notebook    | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Intel         | NUC11DBBi7 M17027-302       | Mini pc     | [e1e4cbbe30](https://linux-hardware.org/?probe=e1e4cbbe30) | Mar 17, 2022 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Notebook    | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell          | Latitude E5570              | Notebook    | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell          | Precision 3551              | Notebook    | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6c62008ae3](https://linux-hardware.org/?probe=6c62008ae3) | Dec 21, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6f29b7bde7](https://linux-hardware.org/?probe=6f29b7bde7) | Dec 21, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [9d1a04cc28](https://linux-hardware.org/?probe=9d1a04cc28) | Dec 15, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f88a7d7f15](https://linux-hardware.org/?probe=f88a7d7f15) | Dec 06, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [cd6c668ae9](https://linux-hardware.org/?probe=cd6c668ae9) | Nov 29, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7052b7628f](https://linux-hardware.org/?probe=7052b7628f) | Nov 18, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ab905debb9](https://linux-hardware.org/?probe=ab905debb9) | Nov 17, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | Notebook    | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| HP            | 212B                        | Desktop     | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | Notebook    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Lenovo        | HR630X                      | Server      | [0627db12df](https://linux-hardware.org/?probe=0627db12df) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Supermicro    | X10DRi                      | Server      | [6be87ab445](https://linux-hardware.org/?probe=6be87ab445) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [54f44d70c5](https://linux-hardware.org/?probe=54f44d70c5) | Jul 24, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell          | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| Dell          | Precision 3541              | Notebook    | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [1b5977b024](https://linux-hardware.org/?probe=1b5977b024) | Jun 03, 2021 |
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Dell          | 074H08 A00                  | Server      | [b7ac531bf5](https://linux-hardware.org/?probe=b7ac531bf5) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [57e5191283](https://linux-hardware.org/?probe=57e5191283) | Jun 01, 2021 |
| Dell          | 0CNCJW A08                  | Server      | [f90168c69d](https://linux-hardware.org/?probe=f90168c69d) | Jun 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| MiTAC         | HS-9215 R0A                 | Server      | [2f38c3fd0e](https://linux-hardware.org/?probe=2f38c3fd0e) | May 27, 2021 |
| HP            | ProLiant DL180 G6           | Server      | [28b04c3004](https://linux-hardware.org/?probe=28b04c3004) | May 26, 2021 |
| Dell          | 0971VF A01                  | Server      | [9d511d1a0b](https://linux-hardware.org/?probe=9d511d1a0b) | May 26, 2021 |
| Lenovo        | HR630X                      | Server      | [fd087082c0](https://linux-hardware.org/?probe=fd087082c0) | May 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [779849778e](https://linux-hardware.org/?probe=779849778e) | May 26, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| HP            | 8054                        | Desktop     | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| Lenovo        | 7D2XCTO1WW                  | Server      | [2175466ea1](https://linux-hardware.org/?probe=2175466ea1) | Apr 25, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [23f12250e5](https://linux-hardware.org/?probe=23f12250e5) | Apr 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell          | Inspiron 3559               | Notebook    | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [bb1cb9b30a](https://linux-hardware.org/?probe=bb1cb9b30a) | Apr 02, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [433f10b16b](https://linux-hardware.org/?probe=433f10b16b) | Mar 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | Notebook    | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| Dell          | Precision 5510              | Notebook    | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony          | VPCEB4L1R                   | Notebook    | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [29d0e20ba4](https://linux-hardware.org/?probe=29d0e20ba4) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Dell          | Board                       | Desktop     | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | Board                       | Desktop     | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | Board                       | Desktop     | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | Board                       | Desktop     | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | Board                       | Desktop     | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | Board                       | Desktop     | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| ASRock        | H270 Pro4                   | Desktop     | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e3d128beda](https://linux-hardware.org/?probe=e3d128beda) | Dec 28, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| Dell          | Latitude 5290               | Notebook    | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell          | Latitude 5290               | Notebook    | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP            | 1905                        | Desktop     | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| HP            | Pavilion 14                 | Notebook    | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo        | ThinkpadT460 20BUS0QT0A     | Notebook    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell          | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ded8f80f0a](https://linux-hardware.org/?probe=ded8f80f0a) | Nov 18, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | Desktop     | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | Desktop     | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| HP            | 1905                        | Desktop     | [872e4ba303](https://linux-hardware.org/?probe=872e4ba303) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell          | Latitude E6420              | Notebook    | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| MSI           | H310M PRO-VD                | Desktop     | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell          | Precision 7510              | Notebook    | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP            | Pavilion 14                 | Notebook    | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell          | Precision 7510              | Notebook    | [9d901b2f8e](https://linux-hardware.org/?probe=9d901b2f8e) | Nov 01, 2020 |
| Dell          | Precision 7510              | Notebook    | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [2dc26a5fbe](https://linux-hardware.org/?probe=2dc26a5fbe) | Oct 29, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [cf0c44ffb8](https://linux-hardware.org/?probe=cf0c44ffb8) | Oct 29, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP            | 1905                        | Desktop     | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP            | Pavilion 14                 | Notebook    | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| HP            | 1905                        | Desktop     | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | Desktop     | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | Desktop     | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| Lenovo        | ThinkPad P50 20EN0005UK     | Notebook    | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| HP            | 843F                        | Desktop     | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [a9d66d8f86](https://linux-hardware.org/?probe=a9d66d8f86) | Sep 15, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| HP            | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | Latitude 5300               | Notebook    | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi          | TM1707                      | Notebook    | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi          | TM1707                      | Notebook    | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell          | Latitude 5300               | Notebook    | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [20760711e1](https://linux-hardware.org/?probe=20760711e1) | May 24, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [53ccb8b4bf](https://linux-hardware.org/?probe=53ccb8b4bf) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [1abce91d71](https://linux-hardware.org/?probe=1abce91d71) | May 08, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell          | G3 3779                     | Notebook    | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell          | Precision 5540              | Notebook    | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [6cc6232ddf](https://linux-hardware.org/?probe=6cc6232ddf) | Apr 14, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Gigabyte      | B75-D3V                     | Desktop     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [1dd5200664](https://linux-hardware.org/?probe=1dd5200664) | Apr 07, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b49a701ac3](https://linux-hardware.org/?probe=b49a701ac3) | Apr 01, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Alienware     | 0VDT73 A00                  | Desktop     | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b5d3a3694d](https://linux-hardware.org/?probe=b5d3a3694d) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [4cde30cfa5](https://linux-hardware.org/?probe=4cde30cfa5) | Feb 26, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [e2a3815dd2](https://linux-hardware.org/?probe=e2a3815dd2) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [da0c7d43d0](https://linux-hardware.org/?probe=da0c7d43d0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [07bde7dae0](https://linux-hardware.org/?probe=07bde7dae0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [6e7911571a](https://linux-hardware.org/?probe=6e7911571a) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [502ac45263](https://linux-hardware.org/?probe=502ac45263) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [412539e106](https://linux-hardware.org/?probe=412539e106) | Feb 21, 2020 |
| Lenovo        | Board                       | Desktop     | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | Board                       | Desktop     | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [5c93a8b972](https://linux-hardware.org/?probe=5c93a8b972) | Feb 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [7b9606b44d](https://linux-hardware.org/?probe=7b9606b44d) | Feb 03, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [f24757810e](https://linux-hardware.org/?probe=f24757810e) | Jan 28, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo        | ThinkPad T490s 20NX002HU... | Notebook    | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [73b2494a42](https://linux-hardware.org/?probe=73b2494a42) | Jan 22, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [bdeba33a9c](https://linux-hardware.org/?probe=bdeba33a9c) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a92733c45d](https://linux-hardware.org/?probe=a92733c45d) | Jan 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [4edc6c52b8](https://linux-hardware.org/?probe=4edc6c52b8) | Jan 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [372bb9dced](https://linux-hardware.org/?probe=372bb9dced) | Jan 15, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [92086a7925](https://linux-hardware.org/?probe=92086a7925) | Jan 14, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [c24f015f0f](https://linux-hardware.org/?probe=c24f015f0f) | Jan 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [61f2cf2ae4](https://linux-hardware.org/?probe=61f2cf2ae4) | Jan 12, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [458ececa20](https://linux-hardware.org/?probe=458ececa20) | Jan 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | Desktop     | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [2979b0995f](https://linux-hardware.org/?probe=2979b0995f) | Dec 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [2ce515411e](https://linux-hardware.org/?probe=2ce515411e) | Dec 13, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [2862a08f39](https://linux-hardware.org/?probe=2862a08f39) | Nov 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Dell          | 0G919G A00                  | Desktop     | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6d1db662fe](https://linux-hardware.org/?probe=6d1db662fe) | Nov 17, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [997d2ae2bf](https://linux-hardware.org/?probe=997d2ae2bf) | Nov 16, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [e5994eed73](https://linux-hardware.org/?probe=e5994eed73) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [c0df153404](https://linux-hardware.org/?probe=c0df153404) | Oct 25, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell          | Latitude 7390               | Notebook    | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell          | Latitude 7390               | Notebook    | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo        | ThinkPad L480 20LSS0M100    | Notebook    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Dell          | 0HHV7N A00                  | Desktop     | [9e55c4bdee](https://linux-hardware.org/?probe=9e55c4bdee) | Apr 05, 2019 |
| HP            | 158A                        | Desktop     | [6924d366ab](https://linux-hardware.org/?probe=6924d366ab) | Jan 09, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [4be9ce0f72](https://linux-hardware.org/?probe=4be9ce0f72) | Dec 20, 2018 |
| Lenovo        | ThinkPad X131e 3368CTO      | Notebook    | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| RHEL 8 | 154       | 78.57%  |
| RHEL 7 | 39        | 19.9%   |
| RHEL 9 | 3         | 1.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 195       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 5.93%   |
| 4.18.0-240.10.1.el8_3.x86_64                 | 13        | 5.51%   |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 4.66%   |
| 4.18.0-305.el8.x86_64                        | 10        | 4.24%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 3.81%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 8         | 3.39%   |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 3.39%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 3.39%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 8         | 3.39%   |
| 4.18.0-348.12.2.el8_5.x86_64                 | 7         | 2.97%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 2.97%   |
| 4.18.0-193.19.1.el8_2.x86_64                 | 7         | 2.97%   |
| 4.18.0-147.3.1.el8_1.x86_64                  | 7         | 2.97%   |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 2.54%   |
| 4.18.0-193.el8.x86_64                        | 6         | 2.54%   |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 2.54%   |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 2.54%   |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 2.12%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 2.12%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.69%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.69%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.69%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.69%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.69%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 4         | 1.69%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 1.27%   |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 1.27%   |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 1.27%   |
| 4.18.0-348.el8.x86_64                        | 2         | 0.85%   |
| 4.18.0-305.17.1.el8_4.x86_64                 | 2         | 0.85%   |
| 4.18.0-240.8.1.el8_3.x86_64                  | 2         | 0.85%   |
| 4.18.0-193.14.3.el8_2.x86_64                 | 2         | 0.85%   |
| 4.18.0-147.0.3.el8_1.x86_64                  | 2         | 0.85%   |
| 3.10.0-1160.6.1.el7.x86_64                   | 2         | 0.85%   |
| 3.10.0-1160.2.2.el7.x86_64                   | 2         | 0.85%   |
| 3.10.0-1160.15.2.el7.x86_64                  | 2         | 0.85%   |
| 3.10.0-1127.13.1.el7.x86_64                  | 2         | 0.85%   |
| 5.9.1-1.el8.elrepo.x86_64                    | 1         | 0.42%   |
| 5.14.0-70.5.1.el9_0.x86_64                   | 1         | 0.42%   |
| 5.14.0-39.el9.x86_64                         | 1         | 0.42%   |
| 5.14.0-1.7.1.el9.x86_64                      | 1         | 0.42%   |
| 5.13.0-1.el8.elrepo.x86_64                   | 1         | 0.42%   |
| 5.10.6-1.el8.elrepo.x86_64                   | 1         | 0.42%   |
| 4.19.150                                     | 1         | 0.42%   |
| 4.18.0-80.el8.x86_64                         | 1         | 0.42%   |
| 4.18.0-80.4.2.el8_0.x86_64                   | 1         | 0.42%   |
| 4.18.0-221.el8.x86_64                        | 1         | 0.42%   |
| 4.18.0-193.23.1.el8_2.x86_64                 | 1         | 0.42%   |
| 4.18.0-193.13.2.el8_2.x86_64                 | 1         | 0.42%   |
| 4.18.0-193.1.2.el8_2.x86_64                  | 1         | 0.42%   |
| 4.18.0-168.el8.x86_64                        | 1         | 0.42%   |
| 4.18.0-144.el8.x86_64                        | 1         | 0.42%   |
| 3.10.0-957.el7.x86_64                        | 1         | 0.42%   |
| 3.10.0-957.5.1.el7.x86_64                    | 1         | 0.42%   |
| 3.10.0-957.21.3.el7.x86_64                   | 1         | 0.42%   |
| 3.10.0-957.10.1.el7.YAHOO.20190320.30.x86_64 | 1         | 0.42%   |
| 3.10.0-957.10.1.el7.x86_64                   | 1         | 0.42%   |
| 3.10.0-957.1.3.el7.x86_64                    | 1         | 0.42%   |
| 3.10.0-862.9.1.el7.x86_64                    | 1         | 0.42%   |
| 3.10.0-862.11.6.el7.x86_64                   | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 149       | 76.02%  |
| 3.10.0   | 39        | 19.9%   |
| 5.14.0   | 3         | 1.53%   |
| 5.9.1    | 1         | 0.51%   |
| 5.13.0   | 1         | 0.51%   |
| 5.10.6   | 1         | 0.51%   |
| 4.19.150 | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 149       | 76.02%  |
| 3.10    | 39        | 19.9%   |
| 5.14    | 3         | 1.53%   |
| 5.9     | 1         | 0.51%   |
| 5.13    | 1         | 0.51%   |
| 5.10    | 1         | 0.51%   |
| 4.19    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 194       | 99.49%  |
| Unknown | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 142       | 69.95%  |
| Unknown       | 41        | 20.2%   |
| GNOME Classic | 12        | 5.91%   |
| KDE5          | 5         | 2.46%   |
| KDE           | 2         | 0.99%   |
| Cinnamon      | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 110       | 54.46%  |
| Wayland | 65        | 32.18%  |
| Unknown | 27        | 13.37%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 157       | 78.5%   |
| GDM     | 43        | 21.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 129       | 64.82%  |
| Unknown | 24        | 12.06%  |
| en_GB   | 10        | 5.03%   |
| pl_PL   | 4         | 2.01%   |
| fr_FR   | 4         | 2.01%   |
| en_IN   | 4         | 2.01%   |
| de_DE   | 4         | 2.01%   |
| ru_RU   | 3         | 1.51%   |
| pt_BR   | 2         | 1.01%   |
| nl_NL   | 2         | 1.01%   |
| es_ES   | 2         | 1.01%   |
| es_AR   | 2         | 1.01%   |
| ko_KR   | 1         | 0.5%    |
| ja_JP   | 1         | 0.5%    |
| it_IT   | 1         | 0.5%    |
| es_MX   | 1         | 0.5%    |
| es_EC   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |
| de_CH   | 1         | 0.5%    |
| cs_CZ   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 134       | 67%     |
| BIOS | 66        | 33%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 166       | 85.13%  |
| Ext4    | 27        | 13.85%  |
| Btrfs   | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 64.18%  |
| GPT     | 54        | 26.87%  |
| MBR     | 18        | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 91.84%  |
| Yes       | 16        | 8.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 185       | 93.91%  |
| Yes       | 12        | 6.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 73        | 37.44%  |
| Dell                | 45        | 23.08%  |
| Hewlett-Packard     | 25        | 12.82%  |
| ASUSTek Computer    | 17        | 8.72%   |
| Gigabyte Technology | 8         | 4.1%    |
| ASRock              | 5         | 2.56%   |
| MSI                 | 4         | 2.05%   |
| Intel               | 3         | 1.54%   |
| ZTSYSTEMS           | 2         | 1.03%   |
| Supermicro          | 2         | 1.03%   |
| Sony                | 2         | 1.03%   |
| TUXEDO              | 1         | 0.51%   |
| Toshiba             | 1         | 0.51%   |
| Timi                | 1         | 0.51%   |
| Samsung Electronics | 1         | 0.51%   |
| MiTAC               | 1         | 0.51%   |
| CX / Air Computers. | 1         | 0.51%   |
| Alienware           | 1         | 0.51%   |
| Acer                | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 3.08%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 2.05%   |
| Dell PowerEdge R230                      | 4         | 2.05%   |
| ASUS All Series                          | 4         | 2.05%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.03%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.03%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.03%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.03%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.03%   |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 1.03%   |
| HP Z620 Workstation                      | 2         | 1.03%   |
| HP EliteBook 8460p                       | 2         | 1.03%   |
| Dell PowerEdge R740                      | 2         | 1.03%   |
| Dell Latitude E6430                      | 2         | 1.03%   |
| Dell Latitude 5300                       | 2         | 1.03%   |
| ZTSYSTEMS Z802                           | 1         | 0.51%   |
| ZTSYSTEMS Z801                           | 1         | 0.51%   |
| TUXEDO N13xWU                            | 1         | 0.51%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.51%   |
| Timi TM1707                              | 1         | 0.51%   |
| Supermicro X7DW3                         | 1         | 0.51%   |
| Supermicro X10DRi                        | 1         | 0.51%   |
| Sony VPCEB4L1R                           | 1         | 0.51%   |
| Sony VPCEB23FM                           | 1         | 0.51%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.51%   |
| MSI MS-7B51                              | 1         | 0.51%   |
| MSI MS-7B33                              | 1         | 0.51%   |
| MSI MS-7A37                              | 1         | 0.51%   |
| MSI MS-7752                              | 1         | 0.51%   |
| MiTAC C4I                                | 1         | 0.51%   |
| Lenovo Z40-70 20366                      | 1         | 0.51%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.51%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.51%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.51%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.51%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.51%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.51%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.51%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.51%   |
| Lenovo ThinkPad X1 Yoga 1st 20FRS17K00   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.51%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.51%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.51%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.51%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.51%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.51%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.51%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.51%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.51%   |
| Lenovo ThinkPad T490 20N3S5DU27          | 1         | 0.51%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.51%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.51%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.51%   |
| Lenovo ThinkPad T480 20L6S29D02          | 1         | 0.51%   |
| Lenovo ThinkPad T470p 20J7S0FA0E         | 1         | 0.51%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.51%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.51%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.51%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 61        | 31.28%  |
| Dell PowerEdge      | 14        | 7.18%   |
| Dell Precision      | 11        | 5.64%   |
| Dell Latitude       | 10        | 5.13%   |
| HP ProLiant         | 5         | 2.56%   |
| HP EliteBook        | 4         | 2.05%   |
| ASUS All            | 4         | 2.05%   |
| Lenovo ThinkCentre  | 3         | 1.54%   |
| HP ZBook            | 3         | 1.54%   |
| Dell Inspiron       | 3         | 1.54%   |
| ASUS PRIME          | 3         | 1.54%   |
| Lenovo 7X56CTO1WW   | 2         | 1.03%   |
| HP Z620             | 2         | 1.03%   |
| HP Z230             | 2         | 1.03%   |
| Dell OptiPlex       | 2         | 1.03%   |
| ASUS ROG            | 2         | 1.03%   |
| ZTSYSTEMS Z802      | 1         | 0.51%   |
| ZTSYSTEMS Z801      | 1         | 0.51%   |
| TUXEDO N13xWU       | 1         | 0.51%   |
| Toshiba Satellite   | 1         | 0.51%   |
| Timi TM1707         | 1         | 0.51%   |
| Supermicro X7DW3    | 1         | 0.51%   |
| Supermicro X10DRi   | 1         | 0.51%   |
| Sony VPCEB4L1R      | 1         | 0.51%   |
| Sony VPCEB23FM      | 1         | 0.51%   |
| Samsung 730QCJ      | 1         | 0.51%   |
| MSI MS-7B51         | 1         | 0.51%   |
| MSI MS-7B33         | 1         | 0.51%   |
| MSI MS-7A37         | 1         | 0.51%   |
| MSI MS-7752         | 1         | 0.51%   |
| MiTAC C4I           | 1         | 0.51%   |
| Lenovo Z40-70       | 1         | 0.51%   |
| Lenovo Yoga         | 1         | 0.51%   |
| Lenovo ThinkSystem  | 1         | 0.51%   |
| Lenovo ThinkpadT460 | 1         | 0.51%   |
| Lenovo ThinkBook    | 1         | 0.51%   |
| Lenovo S40-40       | 1         | 0.51%   |
| Lenovo 10SFS03200   | 1         | 0.51%   |
| Intel NUC11BTMi7    | 1         | 0.51%   |
| Intel NUC10i7FNK    | 1         | 0.51%   |
| Intel DX79SR        | 1         | 0.51%   |
| HP Z840             | 1         | 0.51%   |
| HP Z440             | 1         | 0.51%   |
| HP ProBook          | 1         | 0.51%   |
| HP Pavilion         | 1         | 0.51%   |
| HP OMEN             | 1         | 0.51%   |
| HP EliteDesk        | 1         | 0.51%   |
| HP 290              | 1         | 0.51%   |
| HP 260-P020il       | 1         | 0.51%   |
| HP 250              | 1         | 0.51%   |
| Gigabyte Z97N-WIFI  | 1         | 0.51%   |
| Gigabyte Z490       | 1         | 0.51%   |
| Gigabyte Z390       | 1         | 0.51%   |
| Gigabyte B85M-D3V-A | 1         | 0.51%   |
| Gigabyte B75-D3V    | 1         | 0.51%   |
| Gigabyte B150-HD3   | 1         | 0.51%   |
| Gigabyte AERO       | 1         | 0.51%   |
| Gigabyte 970A-D3    | 1         | 0.51%   |
| Dell XS23-TY3       | 1         | 0.51%   |
| Dell XPS            | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 35        | 17.95%  |
| 2018 | 33        | 16.92%  |
| 2020 | 31        | 15.9%   |
| 2017 | 18        | 9.23%   |
| 2012 | 16        | 8.21%   |
| 2016 | 13        | 6.67%   |
| 2015 | 12        | 6.15%   |
| 2013 | 10        | 5.13%   |
| 2021 | 7         | 3.59%   |
| 2011 | 7         | 3.59%   |
| 2010 | 6         | 3.08%   |
| 2014 | 5         | 2.56%   |
| 2009 | 2         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 108       | 55.38%  |
| Desktop     | 61        | 31.28%  |
| Server      | 20        | 10.26%  |
| Mini pc     | 3         | 1.54%   |
| Convertible | 2         | 1.03%   |
| All in one  | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 179       | 90.86%  |
| Enabled  | 18        | 9.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 49        | 24.62%  |
| 64.01-256.0     | 34        | 17.09%  |
| 4.01-8.0        | 33        | 16.58%  |
| 16.01-24.0      | 31        | 15.58%  |
| 8.01-16.0       | 29        | 14.57%  |
| 24.01-32.0      | 9         | 4.52%   |
| 3.01-4.0        | 7         | 3.52%   |
| More than 256.0 | 5         | 2.51%   |
| 2.01-3.0        | 1         | 0.5%    |
| Unknown         | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 81        | 36.82%  |
| 2.01-3.0        | 39        | 17.73%  |
| 8.01-16.0       | 35        | 15.91%  |
| 3.01-4.0        | 30        | 13.64%  |
| 1.01-2.0        | 19        | 8.64%   |
| 16.01-24.0      | 5         | 2.27%   |
| 24.01-32.0      | 4         | 1.82%   |
| 32.01-64.0      | 2         | 0.91%   |
| 0.51-1.0        | 2         | 0.91%   |
| More than 256.0 | 1         | 0.45%   |
| 64.01-256.0     | 1         | 0.45%   |
| Unknown         | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 53.43%  |
| 2      | 43        | 21.08%  |
| 3      | 25        | 12.25%  |
| 5      | 8         | 3.92%   |
| 4      | 8         | 3.92%   |
| 12     | 3         | 1.47%   |
| 6      | 3         | 1.47%   |
| 8      | 2         | 0.98%   |
| 14     | 1         | 0.49%   |
| 11     | 1         | 0.49%   |
| 7      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 77.16%  |
| Yes       | 45        | 22.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 92.86%  |
| No        | 14        | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 71.28%  |
| No        | 56        | 28.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 56%     |
| No        | 88        | 44%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 50        | 25.51%  |
| India        | 16        | 8.16%   |
| Germany      | 15        | 7.65%   |
| Czechia      | 11        | 5.61%   |
| UK           | 10        | 5.1%    |
| Norway       | 6         | 3.06%   |
| France       | 6         | 3.06%   |
| Canada       | 6         | 3.06%   |
| Spain        | 5         | 2.55%   |
| Poland       | 4         | 2.04%   |
| Netherlands  | 4         | 2.04%   |
| Mexico       | 4         | 2.04%   |
| Italy        | 4         | 2.04%   |
| Switzerland  | 3         | 1.53%   |
| Russia       | 3         | 1.53%   |
| Lithuania    | 3         | 1.53%   |
| Brazil       | 3         | 1.53%   |
| Argentina    | 3         | 1.53%   |
| Ukraine      | 2         | 1.02%   |
| South Korea  | 2         | 1.02%   |
| South Africa | 2         | 1.02%   |
| Singapore    | 2         | 1.02%   |
| Romania      | 2         | 1.02%   |
| Japan        | 2         | 1.02%   |
| Austria      | 2         | 1.02%   |
| Australia    | 2         | 1.02%   |
| Turkmenistan | 1         | 0.51%   |
| Turkey       | 1         | 0.51%   |
| Sweden       | 1         | 0.51%   |
| Saudi Arabia | 1         | 0.51%   |
| Portugal     | 1         | 0.51%   |
| Pakistan     | 1         | 0.51%   |
| New Zealand  | 1         | 0.51%   |
| Nepal        | 1         | 0.51%   |
| Myanmar      | 1         | 0.51%   |
| Morocco      | 1         | 0.51%   |
| Luxembourg   | 1         | 0.51%   |
| Kuwait       | 1         | 0.51%   |
| Israel       | 1         | 0.51%   |
| Ireland      | 1         | 0.51%   |
| Indonesia    | 1         | 0.51%   |
| Georgia      | 1         | 0.51%   |
| Egypt        | 1         | 0.51%   |
| Ecuador      | 1         | 0.51%   |
| Colombia     | 1         | 0.51%   |
| China        | 1         | 0.51%   |
| Bulgaria     | 1         | 0.51%   |
| Belgium      | 1         | 0.51%   |
| Belarus      | 1         | 0.51%   |
| Armenia      | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Quincy                   | 8         | 3.83%   |
| Muggensturm              | 6         | 2.87%   |
| Brno                     | 6         | 2.87%   |
| TromsÃ¸                | 4         | 1.91%   |
| San Jose                 | 3         | 1.44%   |
| Prague                   | 3         | 1.44%   |
| Munich                   | 3         | 1.44%   |
| Milan                    | 3         | 1.44%   |
| Mexico City              | 3         | 1.44%   |
| Chicago                  | 3         | 1.44%   |
| Vienna                   | 2         | 0.96%   |
| Toronto                  | 2         | 0.96%   |
| Singapore                | 2         | 0.96%   |
| Mumbai                   | 2         | 0.96%   |
| Madrid                   | 2         | 0.96%   |
| Kyiv                     | 2         | 0.96%   |
| Kongsberg                | 2         | 0.96%   |
| Doetinchem               | 2         | 0.96%   |
| Coimbatore               | 2         | 0.96%   |
| Berlin                   | 2         | 0.96%   |
| Bengaluru                | 2         | 0.96%   |
| Å iauliai              | 2         | 0.96%   |
| Aurora                   | 2         | 0.96%   |
| Zaragoza                 | 1         | 0.48%   |
| Yorktown Heights         | 1         | 0.48%   |
| Yerevan                  | 1         | 0.48%   |
| Wroclaw                  | 1         | 0.48%   |
| Wiesbaden                | 1         | 0.48%   |
| Weybridge                | 1         | 0.48%   |
| Webster                  | 1         | 0.48%   |
| Warsaw                   | 1         | 0.48%   |
| Valmontone               | 1         | 0.48%   |
| Vaestra Froelunda        | 1         | 0.48%   |
| TÃ¡bor                 | 1         | 0.48%   |
| Tauranga                 | 1         | 0.48%   |
| Taringa                  | 1         | 0.48%   |
| Suwon                    | 1         | 0.48%   |
| Sumida                   | 1         | 0.48%   |
| Stroud                   | 1         | 0.48%   |
| Spokane                  | 1         | 0.48%   |
| Sofia                    | 1         | 0.48%   |
| Sheffield                | 1         | 0.48%   |
| Seoul                    | 1         | 0.48%   |
| Saratov                  | 1         | 0.48%   |
| San Francisco            | 1         | 0.48%   |
| San Fernando             | 1         | 0.48%   |
| Sammamish                | 1         | 0.48%   |
| Salvador                 | 1         | 0.48%   |
| Saltillo                 | 1         | 0.48%   |
| SalÃ©                  | 1         | 0.48%   |
| Saint-Ismier             | 1         | 0.48%   |
| Saint-Alphonse-Rodriguez | 1         | 0.48%   |
| Saint Paul               | 1         | 0.48%   |
| Sagaing                  | 1         | 0.48%   |
| Roudnice nad Labem       | 1         | 0.48%   |
| Rosario                  | 1         | 0.48%   |
| Roha                     | 1         | 0.48%   |
| Rochester                | 1         | 0.48%   |
| Rensselaer               | 1         | 0.48%   |
| Reims                    | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 87     | 17.39%  |
| WDC                 | 43        | 76     | 14.38%  |
| Seagate             | 42        | 86     | 14.05%  |
| Toshiba             | 27        | 41     | 9.03%   |
| SanDisk             | 17        | 28     | 5.69%   |
| SK Hynix            | 15        | 19     | 5.02%   |
| Intel               | 14        | 20     | 4.68%   |
| Kingston            | 11        | 15     | 3.68%   |
| Micron Technology   | 9         | 17     | 3.01%   |
| Crucial             | 8         | 12     | 2.68%   |
| Unknown             | 7         | 9      | 2.34%   |
| HGST                | 5         | 8      | 1.67%   |
| Dell                | 5         | 9      | 1.67%   |
| A-DATA Technology   | 5         | 5      | 1.67%   |
| PNY                 | 3         | 6      | 1%      |
| Phison              | 3         | 7      | 1%      |
| Hitachi             | 3         | 3      | 1%      |
| Hewlett-Packard     | 3         | 11     | 1%      |
| Corsair             | 3         | 6      | 1%      |
| Western Digital     | 2         | 2      | 0.67%   |
| Silicon Motion      | 2         | 3      | 0.67%   |
| Lenovo              | 2         | 2      | 0.67%   |
| XPG                 | 1         | 1      | 0.33%   |
| Transcend           | 1         | 1      | 0.33%   |
| Team                | 1         | 2      | 0.33%   |
| T-FORCE             | 1         | 2      | 0.33%   |
| SMI                 | 1         | 2      | 0.33%   |
| SCST_FIO            | 1         | 9      | 0.33%   |
| SABRENT             | 1         | 1      | 0.33%   |
| OCZ                 | 1         | 2      | 0.33%   |
| NVMe                | 1         | 1      | 0.33%   |
| Lite-On             | 1         | 1      | 0.33%   |
| KingFast            | 1         | 1      | 0.33%   |
| KINGBANK            | 1         | 1      | 0.33%   |
| HPT                 | 1         | 1      | 0.33%   |
| Hoodisk             | 1         | 1      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |
| DELLBOSS            | 1         | 1      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| Anobit              | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB        | 10        | 2.92%   |
| Samsung NVMe SSD Drive 512GB         | 7         | 2.04%   |
| Sandisk NVMe SSD Drive 256GB         | 6         | 1.75%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 5         | 1.46%   |
| Samsung SSD 860 EVO 1TB              | 5         | 1.46%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 1.46%   |
| Samsung NVMe SSD Drive 1024GB        | 5         | 1.46%   |
| Toshiba MG04ACA100NY 1TB             | 4         | 1.17%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 1.17%   |
| Intel NVMe SSD Drive 512GB           | 4         | 1.17%   |
| Dell MD34xx 26TB                     | 4         | 1.17%   |
| WDC WD5003ABYZ-011FA0 500GB          | 3         | 0.87%   |
| Toshiba NVMe SSD Drive 512GB         | 3         | 0.87%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.87%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.87%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.87%   |
| Micron NVMe SSD Drive 256GB          | 3         | 0.87%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.58%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2         | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 0.58%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 0.58%   |
| Toshiba NVMe SSD Drive 1024GB        | 2         | 0.58%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.58%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2         | 0.58%   |
| Seagate ST91000640NS 1TB             | 2         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.58%   |
| Seagate ST4000NM0033-9ZM170 4TB      | 2         | 0.58%   |
| Seagate ST300MP0026 304GB            | 2         | 0.58%   |
| Seagate ST2000NX0433 2TB             | 2         | 0.58%   |
| Seagate ST2000NX0273 2TB             | 2         | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.58%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.58%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 0.58%   |
| Seagate Expansion+ 2TB               | 2         | 0.58%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.58%   |
| Samsung Portable SSD T5 500GB        | 2         | 0.58%   |
| Kingston SUV500120G 120GB SSD        | 2         | 0.58%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.58%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.58%   |
| Intel NVMe SSD Drive 2TB             | 2         | 0.58%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.58%   |
| Corsair Force LE SSD 240GB           | 2         | 0.58%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.29%   |
| Western Digital WUS3BA176C7P3E3 8TB  | 1         | 0.29%   |
| Western Digital NVMe SSD Drive 960GB | 1         | 0.29%   |
| WDC WDS400T2B0A-00SM50 4TB SSD       | 1         | 0.29%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.29%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1         | 0.29%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.29%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 0.29%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.29%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1         | 0.29%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1         | 0.29%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.29%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1         | 0.29%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.29%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 85     | 38.18%  |
| WDC                 | 34        | 62     | 30.91%  |
| Toshiba             | 15        | 25     | 13.64%  |
| HGST                | 5         | 8      | 4.55%   |
| Dell                | 4         | 8      | 3.64%   |
| Hitachi             | 3         | 3      | 2.73%   |
| Hewlett-Packard     | 2         | 9      | 1.82%   |
| Unknown             | 1         | 1      | 0.91%   |
| SCST_FIO            | 1         | 9      | 0.91%   |
| Samsung Electronics | 1         | 2      | 0.91%   |
| SABRENT             | 1         | 1      | 0.91%   |
| DELLBOSS            | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 31     | 27.59%  |
| Kingston            | 11        | 15     | 12.64%  |
| Crucial             | 8         | 12     | 9.2%    |
| WDC                 | 7         | 9      | 8.05%   |
| SanDisk             | 6         | 12     | 6.9%    |
| Micron Technology   | 5         | 11     | 5.75%   |
| A-DATA Technology   | 5         | 5      | 5.75%   |
| SK Hynix            | 3         | 7      | 3.45%   |
| PNY                 | 3         | 6      | 3.45%   |
| Intel               | 3         | 4      | 3.45%   |
| Corsair             | 3         | 6      | 3.45%   |
| Transcend           | 1         | 1      | 1.15%   |
| Toshiba             | 1         | 1      | 1.15%   |
| Team                | 1         | 2      | 1.15%   |
| Seagate             | 1         | 1      | 1.15%   |
| OCZ                 | 1         | 2      | 1.15%   |
| KINGBANK            | 1         | 1      | 1.15%   |
| Hoodisk             | 1         | 1      | 1.15%   |
| China               | 1         | 1      | 1.15%   |
| Anobit              | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 94        | 148    | 34.81%  |
| HDD     | 90        | 214    | 33.33%  |
| SSD     | 78        | 129    | 28.89%  |
| MMC     | 4         | 5      | 1.48%   |
| Unknown | 4         | 6      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 318    | 50.42%  |
| NVMe | 94        | 148    | 39.5%   |
| SAS  | 20        | 31     | 8.4%    |
| MMC  | 4         | 5      | 1.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 137    | 41.11%  |
| 0.51-1.0   | 57        | 94     | 31.67%  |
| 1.01-2.0   | 24        | 52     | 13.33%  |
| 3.01-4.0   | 13        | 33     | 7.22%   |
| 4.01-10.0  | 6         | 17     | 3.33%   |
| 20.01-50.0 | 4         | 8      | 2.22%   |
| 2.01-3.0   | 1         | 1      | 0.56%   |
| 10.01-20.0 | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 30.24%  |
| 251-500        | 36        | 17.56%  |
| 501-1000       | 34        | 16.59%  |
| More than 3000 | 18        | 8.78%   |
| 1001-2000      | 18        | 8.78%   |
| Unknown        | 13        | 6.34%   |
| 51-100         | 8         | 3.9%    |
| 2001-3000      | 7         | 3.41%   |
| 1-20           | 6         | 2.93%   |
| 21-50          | 3         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 21.56%  |
| 21-50          | 45        | 20.64%  |
| 101-250        | 42        | 19.27%  |
| 51-100         | 27        | 12.39%  |
| 251-500        | 18        | 8.26%   |
| Unknown        | 13        | 5.96%   |
| 501-1000       | 11        | 5.05%   |
| 1001-2000      | 8         | 3.67%   |
| More than 3000 | 4         | 1.83%   |
| 2001-3000      | 3         | 1.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5003ABYZ-011FA0 500GB           | 1         | 1      | 11.11%  |
| WDC WD4000FYYZ-01UL1B1 4TB            | 1         | 3      | 11.11%  |
| WDC WD10EALX-759BA1 1TB               | 1         | 2      | 11.11%  |
| Transcend TS512GMTS800 512GB SSD      | 1         | 1      | 11.11%  |
| Seagate ST91000640NS 1TB              | 1         | 2      | 11.11%  |
| Seagate ST6000NM0024-1HT17Z 6TB       | 1         | 2      | 11.11%  |
| Seagate ST1000DM003-9YN162 1TB        | 1         | 1      | 11.11%  |
| Hitachi HDS722020ALA330 2TB           | 1         | 1      | 11.11%  |
| A-DATA Technology SU800NS38 256GB SSD | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 6      | 33.33%  |
| Seagate           | 3         | 5      | 33.33%  |
| Transcend         | 1         | 1      | 11.11%  |
| Hitachi           | 1         | 1      | 11.11%  |
| A-DATA Technology | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 6      | 42.86%  |
| Seagate | 3         | 5      | 42.86%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 12     | 75%     |
| SSD  | 2         | 2      | 25%     |

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
| Detected | 131       | 309    | 62.38%  |
| Works    | 71        | 179    | 33.81%  |
| Malfunc  | 8         | 14     | 3.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 129       | 48.68%  |
| Samsung Electronics          | 35        | 13.21%  |
| Sandisk                      | 14        | 5.28%   |
| Broadcom / LSI               | 13        | 4.91%   |
| SK Hynix                     | 12        | 4.53%   |
| AMD                          | 12        | 4.53%   |
| Toshiba America Info Systems | 11        | 4.15%   |
| LSI Logic / Symbios Logic    | 7         | 2.64%   |
| Phison Electronics           | 4         | 1.51%   |
| Micron Technology            | 4         | 1.51%   |
| Marvell Technology Group     | 4         | 1.51%   |
| Hewlett-Packard              | 4         | 1.51%   |
| Silicon Motion               | 3         | 1.13%   |
| ASMedia Technology           | 3         | 1.13%   |
| Western Digital              | 2         | 0.75%   |
| Lenovo                       | 2         | 0.75%   |
| KIOXIA                       | 2         | 0.75%   |
| Lite-On Technology           | 1         | 0.38%   |
| HighPoint Technologies       | 1         | 0.38%   |
| Biwin Storage Technology     | 1         | 0.38%   |
| ADATA Technology             | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 8.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 14        | 4.58%   |
| SK Hynix Non-Volatile memory controller                                          | 12        | 3.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 12        | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 3.59%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 3.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 3.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 8         | 2.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.61%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 8         | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.96%   |
| Intel SSD 660P Series                                                            | 5         | 1.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 1.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.63%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.31%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                             | 4         | 1.31%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 1.31%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.31%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 4         | 1.31%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 1.31%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 4         | 1.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 1.31%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 4         | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.98%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.98%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.98%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.65%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.65%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.65%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.65%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.65%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.65%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.65%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.65%   |
| HP Smart Array Gen8 Controllers                                                  | 2         | 0.65%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 2         | 0.65%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                      | 1         | 0.33%   |
| Western Digital Ultrastar DC SN630 NVMe SSD                                      | 1         | 0.33%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.33%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.33%   |
| Samsung NVMe SSD Controller PM173X                                               | 1         | 0.33%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 44.74%  |
| NVMe | 95        | 35.71%  |
| RAID | 35        | 13.16%  |
| SAS  | 10        | 3.76%   |
| IDE  | 7         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 180       | 92.31%  |
| AMD    | 15        | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 5.13%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.62%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 3.08%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 2.56%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 4         | 2.05%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 2.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.05%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 3         | 1.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.54%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 2         | 1.03%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 1.03%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 2         | 1.03%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 1.03%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 1.03%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 2         | 1.03%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.03%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.03%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.03%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.03%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.03%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.03%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.51%   |
| Intel Xeon Gold 6263CY CPU @ 2.60GHz          | 1         | 0.51%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz            | 1         | 0.51%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.51%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.51%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.51%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.51%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.51%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.51%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.51%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.51%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.51%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 81        | 41.54%  |
| Intel Core i5      | 38        | 19.49%  |
| Intel Xeon         | 37        | 18.97%  |
| Intel Core i3      | 10        | 5.13%   |
| AMD Ryzen 7        | 5         | 2.56%   |
| Other              | 4         | 2.05%   |
| AMD Ryzen 9        | 3         | 1.54%   |
| Intel Xeon Silver  | 2         | 1.03%   |
| Intel Xeon Gold    | 2         | 1.03%   |
| Intel Pentium Gold | 2         | 1.03%   |
| Intel Core i9      | 2         | 1.03%   |
| AMD Ryzen 3        | 2         | 1.03%   |
| AMD EPYC           | 2         | 1.03%   |
| Intel Pentium      | 1         | 0.51%   |
| Intel Core 2 Duo   | 1         | 0.51%   |
| AMD Ryzen 7 PRO    | 1         | 0.51%   |
| AMD Ryzen 5        | 1         | 0.51%   |
| AMD FX             | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 81        | 41.54%  |
| 2      | 40        | 20.51%  |
| 6      | 30        | 15.38%  |
| 8      | 17        | 8.72%   |
| 12     | 9         | 4.62%   |
| 16     | 6         | 3.08%   |
| 20     | 4         | 2.05%   |
| 36     | 2         | 1.03%   |
| 24     | 2         | 1.03%   |
| 96     | 1         | 0.51%   |
| 64     | 1         | 0.51%   |
| 48     | 1         | 0.51%   |
| 32     | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 169       | 86.67%  |
| 2      | 26        | 13.33%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 168       | 85.71%  |
| 1      | 28        | 14.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 94.92%  |
| Unknown        | 10        | 5.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 27        | 13.71%  |
| 0x906ea    | 14        | 7.11%   |
| 0x806ea    | 12        | 6.09%   |
| Unknown    | 12        | 6.09%   |
| 0xa0652    | 11        | 5.58%   |
| 0x306c3    | 11        | 5.58%   |
| 0x306a9    | 10        | 5.08%   |
| 0x306f2    | 9         | 4.57%   |
| 0x506e3    | 8         | 4.06%   |
| 0x206a7    | 8         | 4.06%   |
| 0x906ed    | 6         | 3.05%   |
| 0x906e9    | 6         | 3.05%   |
| 0x406e3    | 6         | 3.05%   |
| 0x806e9    | 5         | 2.54%   |
| 0x406f1    | 5         | 2.54%   |
| 0x806d1    | 4         | 2.03%   |
| 0x306e4    | 4         | 2.03%   |
| 0x206d7    | 4         | 2.03%   |
| 0x306d4    | 3         | 1.52%   |
| 0x206c2    | 3         | 1.52%   |
| 0x20655    | 3         | 1.52%   |
| 0x08108102 | 3         | 1.52%   |
| 0x40651    | 2         | 1.02%   |
| 0x08701021 | 2         | 1.02%   |
| 0x08600103 | 2         | 1.02%   |
| 0xa0660    | 1         | 0.51%   |
| 0xa0655    | 1         | 0.51%   |
| 0x906eb    | 1         | 0.51%   |
| 0x806c1    | 1         | 0.51%   |
| 0x50657    | 1         | 0.51%   |
| 0x50654    | 1         | 0.51%   |
| 0x20652    | 1         | 0.51%   |
| 0x1067a    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x0a001119 | 1         | 0.51%   |
| 0x08701013 | 1         | 0.51%   |
| 0x08600104 | 1         | 0.51%   |
| 0x08301034 | 1         | 0.51%   |
| 0x0810100b | 1         | 0.51%   |
| 0x08001138 | 1         | 0.51%   |
| 0x08001137 | 1         | 0.51%   |
| 0x06000852 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 72        | 36.73%  |
| Haswell     | 24        | 12.24%  |
| Skylake     | 22        | 11.22%  |
| IvyBridge   | 15        | 7.65%   |
| CometLake   | 13        | 6.63%   |
| SandyBridge | 12        | 6.12%   |
| Broadwell   | 8         | 4.08%   |
| Zen 2       | 7         | 3.57%   |
| Westmere    | 7         | 3.57%   |
| Zen+        | 3         | 1.53%   |
| Zen         | 3         | 1.53%   |
| Icelake     | 3         | 1.53%   |
| Unknown     | 3         | 1.53%   |
| Penryn      | 2         | 1.02%   |
| TigerLake   | 1         | 0.51%   |
| Piledriver  | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 121       | 51.05%  |
| Nvidia                     | 68        | 28.69%  |
| AMD                        | 22        | 9.28%   |
| Matrox Electronics Systems | 19        | 8.02%   |
| ASPEED Technology          | 7         | 2.95%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 17        | 7.11%   |
| Intel UHD Graphics 620                                                      | 12        | 5.02%   |
| Matrox Electronics Systems G200eR2                                          | 11        | 4.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 11        | 4.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 10        | 4.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.93%   |
| ASPEED Technology ASPEED Graphics Family                                    | 7         | 2.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 2.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2.09%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.09%   |
| Intel HD Graphics 630                                                       | 4         | 1.67%   |
| Intel HD Graphics 620                                                       | 4         | 1.67%   |
| Intel HD Graphics 530                                                       | 4         | 1.67%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.26%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 1.26%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 1.26%   |
| Intel HD Graphics 5500                                                      | 3         | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.26%   |
| AMD Renoir                                                                  | 3         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.84%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.84%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.84%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 2         | 0.84%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.84%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2         | 0.84%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.84%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.42%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.42%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.42%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.42%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.42%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.42%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.42%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.42%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.42%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.42%   |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.42%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 0.42%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.42%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.42%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 84        | 42.64%  |
| 1 x Nvidia      | 39        | 19.8%   |
| Intel + Nvidia  | 25        | 12.69%  |
| 1 x Matrox      | 18        | 9.14%   |
| 1 x AMD         | 12        | 6.09%   |
| Intel + AMD     | 7         | 3.55%   |
| 1 x ASPEED      | 6         | 3.05%   |
| AMD + Nvidia    | 2         | 1.02%   |
| 2 x Nvidia      | 1         | 0.51%   |
| 2 x AMD         | 1         | 0.51%   |
| Nvidia + Matrox | 1         | 0.51%   |
| Nvidia + ASPEED | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 153       | 77.27%  |
| Proprietary | 30        | 15.15%  |
| Unknown     | 15        | 7.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 64.18%  |
| 1.01-2.0   | 20        | 9.95%   |
| 3.01-4.0   | 15        | 7.46%   |
| 0.51-1.0   | 10        | 4.98%   |
| 5.01-6.0   | 8         | 3.98%   |
| 7.01-8.0   | 7         | 3.48%   |
| 0.01-0.5   | 6         | 2.99%   |
| 2.01-3.0   | 3         | 1.49%   |
| 8.01-16.0  | 2         | 1%      |
| 4.01-5.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 28        | 12.12%  |
| AU Optronics            | 25        | 10.82%  |
| Samsung Electronics     | 23        | 9.96%   |
| Lenovo                  | 19        | 8.23%   |
| BOE                     | 19        | 8.23%   |
| LG Display              | 18        | 7.79%   |
| Chimei Innolux          | 17        | 7.36%   |
| Goldstar                | 15        | 6.49%   |
| Hewlett-Packard         | 11        | 4.76%   |
| Sharp                   | 6         | 2.6%    |
| InfoVision              | 5         | 2.16%   |
| Acer                    | 5         | 2.16%   |
| Philips                 | 4         | 1.73%   |
| Eizo                    | 4         | 1.73%   |
| BenQ                    | 4         | 1.73%   |
| Ancor Communications    | 3         | 1.3%    |
| ViewSonic               | 2         | 0.87%   |
| PANDA                   | 2         | 0.87%   |
| LGD                     | 2         | 0.87%   |
| Lenovo Group Limited    | 2         | 0.87%   |
| Iiyama                  | 2         | 0.87%   |
| Gigabyte Technology     | 2         | 0.87%   |
| BOE Technology Group    | 2         | 0.87%   |
| AOC                     | 2         | 0.87%   |
| Sun                     | 1         | 0.43%   |
| Sceptre Tech            | 1         | 0.43%   |
| Planar                  | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| ITE                     | 1         | 0.43%   |
| Insignia                | 1         | 0.43%   |
| Chi Mei Optoelectronics | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell IDRAC DEL0001 1280x1024                                          | 6         | 2.41%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 2.41%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 4         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 1.61%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 1.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 1.2%    |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.2%    |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 3         | 1.2%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.2%    |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.2%    |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 3         | 1.2%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.8%    |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.8%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.8%    |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.8%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.8%    |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.8%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.8%    |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 0.8%    |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 0.8%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.8%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.8%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.8%    |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.4%    |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.4%    |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.4%    |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.4%    |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1         | 0.4%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.4%    |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1         | 0.4%    |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 1         | 0.4%    |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor S22B150                               | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1         | 0.4%    |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 700x400mm 31.7-inch    | 1         | 0.4%    |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 52.66%  |
| 3840x2160 (4K)     | 16        | 7.73%   |
| 1366x768 (WXGA)    | 16        | 7.73%   |
| 2560x1440 (QHD)    | 14        | 6.76%   |
| 1600x900 (HD+)     | 11        | 5.31%   |
| 2560x1080          | 6         | 2.9%    |
| 1920x1200 (WUXGA)  | 6         | 2.9%    |
| 1280x1024 (SXGA)   | 6         | 2.9%    |
| Unknown            | 5         | 2.42%   |
| 3840x1080          | 4         | 1.93%   |
| 3440x1440          | 4         | 1.93%   |
| 1680x1050 (WSXGA+) | 2         | 0.97%   |
| 1440x900 (WXGA+)   | 2         | 0.97%   |
| 9600x2160          | 1         | 0.48%   |
| 7680x2160          | 1         | 0.48%   |
| 6400x2160          | 1         | 0.48%   |
| 2048x1152          | 1         | 0.48%   |
| 1280x800 (WXGA)    | 1         | 0.48%   |
| 1280x720 (HD)      | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 19.4%   |
| 14      | 28        | 12.07%  |
| 24      | 25        | 10.78%  |
| 27      | 24        | 10.34%  |
| 13      | 21        | 9.05%   |
| Unknown | 19        | 8.19%   |
| 23      | 17        | 7.33%   |
| 21      | 10        | 4.31%   |
| 34      | 7         | 3.02%   |
| 31      | 6         | 2.59%   |
| 12      | 5         | 2.16%   |
| 20      | 4         | 1.72%   |
| 54      | 3         | 1.29%   |
| 17      | 3         | 1.29%   |
| 47      | 2         | 0.86%   |
| 32      | 2         | 0.86%   |
| 22      | 2         | 0.86%   |
| 18      | 2         | 0.86%   |
| 49      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 39      | 1         | 0.43%   |
| 28      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 38.84%  |
| 501-600     | 57        | 25.45%  |
| Unknown     | 19        | 8.48%   |
| 401-500     | 18        | 8.04%   |
| 201-300     | 13        | 5.8%    |
| 601-700     | 10        | 4.46%   |
| 701-800     | 9         | 4.02%   |
| 1001-1500   | 6         | 2.68%   |
| 351-400     | 3         | 1.34%   |
| 801-900     | 2         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 145       | 77.96%  |
| 16/10   | 14        | 7.53%   |
| Unknown | 11        | 5.91%   |
| 21/9    | 8         | 4.3%    |
| 5/4     | 6         | 3.23%   |
| 32/9    | 1         | 0.54%   |
| 3/2     | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 19.74%  |
| 81-90          | 42        | 18.42%  |
| 201-250        | 41        | 17.98%  |
| 301-350        | 24        | 10.53%  |
| Unknown        | 19        | 8.33%   |
| 351-500        | 14        | 6.14%   |
| 251-300        | 12        | 5.26%   |
| 71-80          | 7         | 3.07%   |
| 151-200        | 6         | 2.63%   |
| 61-70          | 5         | 2.19%   |
| 501-1000       | 5         | 2.19%   |
| More than 1000 | 3         | 1.32%   |
| 121-130        | 3         | 1.32%   |
| 51-60          | 1         | 0.44%   |
| 141-150        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 82        | 36.77%  |
| 51-100        | 67        | 30.04%  |
| 101-120       | 32        | 14.35%  |
| Unknown       | 19        | 8.52%   |
| 161-240       | 13        | 5.83%   |
| More than 240 | 5         | 2.24%   |
| 1-50          | 5         | 2.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 126       | 61.17%  |
| 2     | 47        | 22.82%  |
| 0     | 20        | 9.71%   |
| 3     | 13        | 6.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 153       | 52.22%  |
| Realtek Semiconductor             | 56        | 19.11%  |
| Broadcom                          | 19        | 6.48%   |
| Lenovo                            | 15        | 5.12%   |
| Qualcomm Atheros                  | 12        | 4.1%    |
| Dell                              | 5         | 1.71%   |
| Broadcom Limited                  | 4         | 1.37%   |
| Sierra Wireless                   | 2         | 0.68%   |
| Ralink Technology                 | 2         | 0.68%   |
| Ralink                            | 2         | 0.68%   |
| Marvell Technology Group          | 2         | 0.68%   |
| Huawei Technologies               | 2         | 0.68%   |
| Ericsson Business Mobile Networks | 2         | 0.68%   |
| ASIX Electronics                  | 2         | 0.68%   |
| Xiaomi                            | 1         | 0.34%   |
| Samsung Electronics               | 1         | 0.34%   |
| QLogic                            | 1         | 0.34%   |
| Prolific Technology               | 1         | 0.34%   |
| Microchip Technology              | 1         | 0.34%   |
| Micro Star International          | 1         | 0.34%   |
| Mellanox Technologies             | 1         | 0.34%   |
| MediaTek                          | 1         | 0.34%   |
| Luminary Micro                    | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| IBM                               | 1         | 0.34%   |
| Emulex                            | 1         | 0.34%   |
| DisplayLink                       | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |
| Arduino SA                        | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 9.41%   |
| Intel Wireless 8265 / 8275                                                     | 16        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 4.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 15        | 3.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 12        | 3.05%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11        | 2.8%    |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 2.54%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 2.54%   |
| Intel Wireless 8260                                                            | 9         | 2.29%   |
| Intel Wi-Fi 6 AX200                                                            | 9         | 2.29%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 2.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 2.04%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 2.04%   |
| Intel I350 Gigabit Network Connection                                          | 8         | 2.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 1.78%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.53%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.53%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 1.27%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 1.27%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 1.02%   |
| Intel Wireless-AC 9260                                                         | 4         | 1.02%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.02%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.02%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.02%   |
| Intel Wireless 7265                                                            | 3         | 0.76%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.76%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.51%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.51%   |
| Intel Wireless 7260                                                            | 2         | 0.51%   |
| Intel Wireless 3165                                                            | 2         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.51%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.51%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.51%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.51%   |
| Intel Ethernet Controller 10G X550T                                            | 2         | 0.51%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.51%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.51%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.51%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.51%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 106       | 73.61%  |
| Qualcomm Atheros         | 11        | 7.64%   |
| Realtek Semiconductor    | 10        | 6.94%   |
| Broadcom                 | 5         | 3.47%   |
| Sierra Wireless          | 2         | 1.39%   |
| Ralink Technology        | 2         | 1.39%   |
| Ralink                   | 2         | 1.39%   |
| Dell                     | 2         | 1.39%   |
| Micro Star International | 1         | 0.69%   |
| MediaTek                 | 1         | 0.69%   |
| D-Link                   | 1         | 0.69%   |
| Broadcom Limited         | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 16        | 11.11%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 15        | 10.42%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 12        | 8.33%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 11        | 7.64%   |
| Intel Wireless 8260                                                        | 9         | 6.25%   |
| Intel Wi-Fi 6 AX200                                                        | 9         | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.78%   |
| Intel Wireless-AC 9260                                                     | 4         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 2.78%   |
| Intel Wireless 7265                                                        | 3         | 2.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.39%   |
| Intel Wireless 7260                                                        | 2         | 1.39%   |
| Intel Wireless 3165                                                        | 2         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 1.39%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 2         | 1.39%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                        | 1         | 0.69%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.69%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.69%   |
| Ralink RT5372 Wireless Adapter                                             | 1         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.69%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.69%   |
| MediaTek Wireless                                                          | 1         | 0.69%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.69%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 0.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 120       | 55.56%  |
| Realtek Semiconductor    | 49        | 22.69%  |
| Lenovo                   | 15        | 6.94%   |
| Broadcom                 | 14        | 6.48%   |
| Broadcom Limited         | 3         | 1.39%   |
| Qualcomm Atheros         | 2         | 0.93%   |
| Marvell Technology Group | 2         | 0.93%   |
| ASIX Electronics         | 2         | 0.93%   |
| Xiaomi                   | 1         | 0.46%   |
| Samsung Electronics      | 1         | 0.46%   |
| QLogic                   | 1         | 0.46%   |
| Mellanox Technologies    | 1         | 0.46%   |
| ICS Advent               | 1         | 0.46%   |
| IBM                      | 1         | 0.46%   |
| Huawei Technologies      | 1         | 0.46%   |
| Emulex                   | 1         | 0.46%   |
| DisplayLink              | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 15.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.69%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.18%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4.18%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.35%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 3.35%   |
| Intel I350 Gigabit Network Connection                                          | 8         | 3.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.93%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.51%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 2.51%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 2.09%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 2.09%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.67%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.67%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.67%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.67%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.67%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.26%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.84%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.84%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.84%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.84%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.84%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.84%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.84%   |
| Intel Ethernet Controller 10G X550T                                            | 2         | 0.84%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.84%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.84%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.84%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.84%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.84%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.84%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.42%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 0.42%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                        | 1         | 0.42%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.42%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.42%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.42%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.42%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.42%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.42%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.42%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.42%   |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 54.98%  |
| WiFi     | 139       | 41.99%  |
| Modem    | 7         | 2.11%   |
| Unknown  | 3         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 57.44%  |
| WiFi     | 121       | 41.87%  |
| Modem    | 1         | 0.35%   |
| Unknown  | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 113       | 57.65%  |
| 1     | 52        | 26.53%  |
| 3     | 11        | 5.61%   |
| 4     | 8         | 4.08%   |
| 6     | 7         | 3.57%   |
| 132   | 1         | 0.51%   |
| 22    | 1         | 0.51%   |
| 12    | 1         | 0.51%   |
| 8     | 1         | 0.51%   |
| 5     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 90.86%  |
| Yes  | 18        | 9.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 72.32%  |
| Cambridge Silicon Radio         | 8         | 7.14%   |
| Broadcom                        | 6         | 5.36%   |
| Qualcomm Atheros Communications | 4         | 3.57%   |
| Realtek Semiconductor           | 3         | 2.68%   |
| IMC Networks                    | 3         | 2.68%   |
| ASUSTek Computer                | 3         | 2.68%   |
| Ralink                          | 1         | 0.89%   |
| Micro Star International        | 1         | 0.89%   |
| Foxconn / Hon Hai               | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 22.32%  |
| Intel Bluetooth Device                                                              | 23        | 20.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 18.75%  |
| Intel AX200 Bluetooth                                                               | 8         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.68%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.79%   |
| ASUS BCM20702A0                                                                     | 2         | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.89%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.89%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.89%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.89%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.89%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.89%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 152       | 55.27%  |
| Nvidia                 | 50        | 18.18%  |
| AMD                    | 20        | 7.27%   |
| Lenovo                 | 16        | 5.82%   |
| Realtek Semiconductor  | 4         | 1.45%   |
| Plantronics            | 4         | 1.45%   |
| Texas Instruments      | 3         | 1.09%   |
| JMTek                  | 3         | 1.09%   |
| GN Netcom              | 3         | 1.09%   |
| Generalplus Technology | 3         | 1.09%   |
| Creative Labs          | 3         | 1.09%   |
| Logitech               | 2         | 0.73%   |
| Creative Technology    | 2         | 0.73%   |
| C-Media Electronics    | 2         | 0.73%   |
| Tenx Technology        | 1         | 0.36%   |
| RODE Microphones       | 1         | 0.36%   |
| LG Electronics         | 1         | 0.36%   |
| Google                 | 1         | 0.36%   |
| Focusrite-Novation     | 1         | 0.36%   |
| DYNEX                  | 1         | 0.36%   |
| Dell                   | 1         | 0.36%   |
| ASUSTek Computer       | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 23        | 7.8%    |
| Intel Cannon Lake PCH cAVS                                                        | 19        | 6.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 17        | 5.76%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 12        | 4.07%   |
| Intel Comet Lake PCH cAVS                                                         | 12        | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 10        | 3.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10        | 3.39%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9         | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9         | 3.05%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 2.37%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6         | 2.03%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6         | 2.03%   |
| Realtek Semiconductor USB Audio                                                   | 4         | 1.36%   |
| Plantronics BT600                                                                 | 4         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 1.36%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 4         | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4         | 1.36%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4         | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.36%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.02%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 1.02%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.02%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 0.68%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 0.68%   |
| Nvidia Audio device                                                               | 2         | 0.68%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.68%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.68%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.68%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.68%   |
| Generalplus Technology USB Audio Device                                           | 2         | 0.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.68%   |
| Tenx Technology USB AUDIO                                                         | 1         | 0.34%   |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.34%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.34%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.34%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.34%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1         | 0.34%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1         | 0.34%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.34%   |
| Logitech H570e Mono                                                               | 1         | 0.34%   |
| Logitech H555 Headset                                                             | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 31%     |
| SK Hynix            | 28        | 28%     |
| Micron Technology   | 10        | 10%     |
| Crucial             | 9         | 9%      |
| Kingston            | 6         | 6%      |
| Unknown             | 4         | 4%      |
| Corsair             | 4         | 4%      |
| Hewlett-Packard     | 2         | 2%      |
| Unknown (0x0205)    | 1         | 1%      |
| Transcend           | 1         | 1%      |
| Smart               | 1         | 1%      |
| Patriot             | 1         | 1%      |
| GOODRAM             | 1         | 1%      |
| Elpida              | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 4         | 3.74%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s      | 3         | 2.8%    |
| SK Hynix RAM HMA42GR7MFR4N-TF 16384MB DIMM DDR4 2133MT/s     | 3         | 2.8%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 2         | 1.87%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.87%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.87%   |
| SK Hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s     | 2         | 1.87%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 1.87%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 1.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.87%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s         | 2         | 1.87%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 2         | 1.87%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s         | 2         | 1.87%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s         | 2         | 1.87%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 2         | 1.87%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.93%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s           | 1         | 0.93%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s             | 1         | 0.93%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.93%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s      | 1         | 0.93%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.93%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.93%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 0.93%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.93%   |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 1         | 0.93%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s         | 1         | 0.93%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 0.93%   |
| SK Hynix RAM HMA84GR7CJR4N-WM 32GB DIMM DDR4 2933MT/s        | 1         | 0.93%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 0.93%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 0.93%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 0.93%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 0.93%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                    | 1         | 0.93%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.93%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 0.93%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                   | 1         | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.93%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 1         | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 0.93%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 0.93%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 0.93%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 0.93%   |
| Samsung RAM M393B5173FHD-CF8 4096MB DIMM 1066MT/s            | 1         | 0.93%   |
| Samsung RAM M393A2G40DB0-CPB 16384MB DIMM DDR4 2133MT/s      | 1         | 0.93%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1         | 0.93%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1         | 0.93%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s          | 1         | 0.93%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 667MT/s          | 1         | 0.93%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s          | 1         | 0.93%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.93%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.93%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s             | 1         | 0.93%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 0.93%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s       | 1         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 52        | 61.9%   |
| DDR3    | 23        | 27.38%  |
| SDRAM   | 2         | 2.38%   |
| LPDDR3  | 2         | 2.38%   |
| DRAM    | 2         | 2.38%   |
| LPDDR4  | 1         | 1.19%   |
| DDR2    | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 46        | 55.42%  |
| SODIMM       | 33        | 39.76%  |
| RIMM         | 2         | 2.41%   |
| Row Of Chips | 1         | 1.2%    |
| Chip         | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 27        | 31.03%  |
| 8192  | 27        | 31.03%  |
| 4096  | 21        | 24.14%  |
| 32768 | 8         | 9.2%    |
| 2048  | 2         | 2.3%    |
| 65536 | 1         | 1.15%   |
| 1024  | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 19.1%   |
| 2400  | 16        | 17.98%  |
| 2667  | 14        | 15.73%  |
| 3200  | 11        | 12.36%  |
| 2133  | 10        | 11.24%  |
| 1333  | 6         | 6.74%   |
| 2666  | 4         | 4.49%   |
| 3600  | 2         | 2.25%   |
| 2933  | 2         | 2.25%   |
| 3266  | 1         | 1.12%   |
| 2048  | 1         | 1.12%   |
| 1867  | 1         | 1.12%   |
| 1866  | 1         | 1.12%   |
| 1334  | 1         | 1.12%   |
| 1066  | 1         | 1.12%   |
| 800   | 1         | 1.12%   |

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
| Chicony Electronics                    | 37        | 28.68%  |
| IMC Networks                           | 17        | 13.18%  |
| Acer                                   | 14        | 10.85%  |
| Realtek Semiconductor                  | 10        | 7.75%   |
| Microdia                               | 9         | 6.98%   |
| Logitech                               | 9         | 6.98%   |
| Sunplus Innovation Technology          | 6         | 4.65%   |
| Unknown                                | 5         | 3.88%   |
| Suyin                                  | 3         | 2.33%   |
| Samsung Electronics                    | 3         | 2.33%   |
| Lite-On Technology                     | 3         | 2.33%   |
| Syntek                                 | 2         | 1.55%   |
| Generalplus Technology                 | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.55%   |
| Ruision                                | 1         | 0.78%   |
| Quanta                                 | 1         | 0.78%   |
| Microsoft                              | 1         | 0.78%   |
| LG Electronics                         | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| Jieli Technology                       | 1         | 0.78%   |
| ARC International                      | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 19        | 14.39%  |
| IMC Networks Integrated Camera                               | 14        | 10.61%  |
| Realtek Integrated_Webcam_HD                                 | 8         | 6.06%   |
| Acer Integrated Camera                                       | 8         | 6.06%   |
| Unknown FULL HD 1080P Webcam                                 | 4         | 3.03%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                      | 4         | 3.03%   |
| Chicony HP HD Camera                                         | 4         | 3.03%   |
| Acer SunplusIT Integrated Camera                             | 4         | 3.03%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.27%   |
| Samsung Galaxy A5 (MTP)                                      | 3         | 2.27%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.27%   |
| Lite-On Integrated Camera                                    | 3         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 2.27%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.27%   |
| Microdia Webcam                                              | 2         | 1.52%   |
| Microdia Integrated Webcam                                   | 2         | 1.52%   |
| Generalplus GENERAL WEBCAM                                   | 2         | 1.52%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.52%   |
| Acer Integrated IR Camera                                    | 2         | 1.52%   |
| Unknown 720p HD Camera                                       | 1         | 0.76%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.76%   |
| Syntek Integrated Camera                                     | 1         | 0.76%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.76%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.76%   |
| Suyin HP Truevision HD                                       | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.76%   |
| Sunplus Integrated Webcam                                    | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.76%   |
| Ruision UVC Camera                                           | 1         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.76%   |
| Realtek NexiGo N960E FHD Webcam                              | 1         | 0.76%   |
| Quanta HP HD Camera                                          | 1         | 0.76%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.76%   |
| Logitech Webcam C925e                                        | 1         | 0.76%   |
| Logitech Webcam C310                                         | 1         | 0.76%   |
| Logitech Webcam C270                                         | 1         | 0.76%   |
| Logitech HD Webcam C910                                      | 1         | 0.76%   |
| Logitech B525 HD Webcam                                      | 1         | 0.76%   |
| LG LG UltraFine Display Camera                               | 1         | 0.76%   |
| Lenovo Integrated Webcam                                     | 1         | 0.76%   |
| Jieli USB PHY 2.0                                            | 1         | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.76%   |
| Chicony Integrated IR Camera                                 | 1         | 0.76%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.76%   |
| Chicony HP Webcam                                            | 1         | 0.76%   |
| Chicony HD User Facing                                       | 1         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.76%   |
| ARC International Camera                                     | 1         | 0.76%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.76%   |
| Acer Lenovo Integrated Webcam                                | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 30        | 57.69%  |
| Validity Sensors           | 15        | 28.85%  |
| Shenzhen Goodix Technology | 3         | 5.77%   |
| Upek                       | 2         | 3.85%   |
| Samsung Electronics        | 1         | 1.92%   |
| Elan Microelectronics      | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 40.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.54%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.85%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.92%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.92%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.92%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.92%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.92%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 44.44%  |
| Alcor Micro           | 4         | 22.22%  |
| Lenovo                | 2         | 11.11%  |
| Upek                  | 1         | 5.56%   |
| SCM Microsystems      | 1         | 5.56%   |
| OmniKey               | 1         | 5.56%   |
| Gemalto (was Gemplus) | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 22.22%  |
| Broadcom 5880                                              | 3         | 16.67%  |
| Broadcom 58200                                             | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.56%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 5.56%   |
| OmniKey CardMan 3121 (HID Technologies)                    | 1         | 5.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 47.24%  |
| 1     | 71        | 35.68%  |
| 2     | 22        | 11.06%  |
| 3     | 9         | 4.52%   |
| 5     | 3         | 1.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 34.9%   |
| Graphics card            | 24        | 16.11%  |
| Unassigned class         | 21        | 14.09%  |
| Communication controller | 18        | 12.08%  |
| Chipcard                 | 11        | 7.38%   |
| Net/wireless             | 6         | 4.03%   |
| Card reader              | 4         | 2.68%   |
| Bluetooth                | 3         | 2.01%   |
| Net/ethernet             | 2         | 1.34%   |
| Multimedia controller    | 2         | 1.34%   |
| Storage/raid             | 1         | 0.67%   |
| Storage/ide              | 1         | 0.67%   |
| Storage                  | 1         | 0.67%   |
| Sound                    | 1         | 0.67%   |
| Network                  | 1         | 0.67%   |
| Camera                   | 1         | 0.67%   |

