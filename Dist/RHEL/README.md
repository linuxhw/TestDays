RHEL - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for RHEL.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL/Desktop/README.md) and [notebooks](/Dist/RHEL/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 336

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| RHEL 8 | 151       | 78.65%  |
| RHEL 7 | 39        | 20.31%  |
| RHEL 9 | 2         | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 191       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 6.06%   |
| 4.18.0-240.10.1.el8_3.x86_64                 | 13        | 5.63%   |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 4.76%   |
| 4.18.0-305.el8.x86_64                        | 10        | 4.33%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 3.9%    |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 3.46%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 3.46%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 8         | 3.46%   |
| 4.18.0-348.12.2.el8_5.x86_64                 | 7         | 3.03%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 3.03%   |
| 4.18.0-193.19.1.el8_2.x86_64                 | 7         | 3.03%   |
| 4.18.0-147.3.1.el8_1.x86_64                  | 7         | 3.03%   |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 2.6%    |
| 4.18.0-193.el8.x86_64                        | 6         | 2.6%    |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 2.6%    |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 2.6%    |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 2.16%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 2.16%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.73%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 4         | 1.73%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.73%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.73%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.73%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.73%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 4         | 1.73%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 1.3%    |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 1.3%    |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 1.3%    |
| 4.18.0-348.el8.x86_64                        | 2         | 0.87%   |
| 4.18.0-305.17.1.el8_4.x86_64                 | 2         | 0.87%   |
| 4.18.0-240.8.1.el8_3.x86_64                  | 2         | 0.87%   |
| 4.18.0-193.14.3.el8_2.x86_64                 | 2         | 0.87%   |
| 4.18.0-147.0.3.el8_1.x86_64                  | 2         | 0.87%   |
| 3.10.0-1160.6.1.el7.x86_64                   | 2         | 0.87%   |
| 3.10.0-1160.2.2.el7.x86_64                   | 2         | 0.87%   |
| 3.10.0-1160.15.2.el7.x86_64                  | 2         | 0.87%   |
| 3.10.0-1127.13.1.el7.x86_64                  | 2         | 0.87%   |
| 5.9.1-1.el8.elrepo.x86_64                    | 1         | 0.43%   |
| 5.14.0-39.el9.x86_64                         | 1         | 0.43%   |
| 5.14.0-1.7.1.el9.x86_64                      | 1         | 0.43%   |
| 5.13.0-1.el8.elrepo.x86_64                   | 1         | 0.43%   |
| 5.10.6-1.el8.elrepo.x86_64                   | 1         | 0.43%   |
| 4.19.150                                     | 1         | 0.43%   |
| 4.18.0-80.el8.x86_64                         | 1         | 0.43%   |
| 4.18.0-80.4.2.el8_0.x86_64                   | 1         | 0.43%   |
| 4.18.0-221.el8.x86_64                        | 1         | 0.43%   |
| 4.18.0-193.23.1.el8_2.x86_64                 | 1         | 0.43%   |
| 4.18.0-193.13.2.el8_2.x86_64                 | 1         | 0.43%   |
| 4.18.0-193.1.2.el8_2.x86_64                  | 1         | 0.43%   |
| 4.18.0-168.el8.x86_64                        | 1         | 0.43%   |
| 4.18.0-144.el8.x86_64                        | 1         | 0.43%   |
| 3.10.0-957.el7.x86_64                        | 1         | 0.43%   |
| 3.10.0-957.5.1.el7.x86_64                    | 1         | 0.43%   |
| 3.10.0-957.21.3.el7.x86_64                   | 1         | 0.43%   |
| 3.10.0-957.10.1.el7.YAHOO.20190320.30.x86_64 | 1         | 0.43%   |
| 3.10.0-957.10.1.el7.x86_64                   | 1         | 0.43%   |
| 3.10.0-957.1.3.el7.x86_64                    | 1         | 0.43%   |
| 3.10.0-862.9.1.el7.x86_64                    | 1         | 0.43%   |
| 3.10.0-862.11.6.el7.x86_64                   | 1         | 0.43%   |
| 3.10.0-693.11.6.el7.x86_64                   | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 146       | 76.04%  |
| 3.10.0   | 39        | 20.31%  |
| 5.14.0   | 2         | 1.04%   |
| 5.9.1    | 1         | 0.52%   |
| 5.13.0   | 1         | 0.52%   |
| 5.10.6   | 1         | 0.52%   |
| 4.19.150 | 1         | 0.52%   |
| Unknown  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 146       | 76.04%  |
| 3.10    | 39        | 20.31%  |
| 5.14    | 2         | 1.04%   |
| 5.9     | 1         | 0.52%   |
| 5.13    | 1         | 0.52%   |
| 5.10    | 1         | 0.52%   |
| 4.19    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 190       | 99.48%  |
| Unknown | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 139       | 69.85%  |
| Unknown       | 40        | 20.1%   |
| GNOME Classic | 12        | 6.03%   |
| KDE5          | 5         | 2.51%   |
| KDE           | 2         | 1.01%   |
| Cinnamon      | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 108       | 54.55%  |
| Wayland | 64        | 32.32%  |
| Unknown | 26        | 13.13%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 157       | 80.1%   |
| GDM     | 39        | 19.9%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 126       | 64.62%  |
| Unknown | 24        | 12.31%  |
| en_GB   | 10        | 5.13%   |
| pl_PL   | 4         | 2.05%   |
| fr_FR   | 4         | 2.05%   |
| en_IN   | 4         | 2.05%   |
| de_DE   | 4         | 2.05%   |
| ru_RU   | 3         | 1.54%   |
| pt_BR   | 2         | 1.03%   |
| nl_NL   | 2         | 1.03%   |
| es_AR   | 2         | 1.03%   |
| ko_KR   | 1         | 0.51%   |
| ja_JP   | 1         | 0.51%   |
| it_IT   | 1         | 0.51%   |
| es_MX   | 1         | 0.51%   |
| es_ES   | 1         | 0.51%   |
| es_EC   | 1         | 0.51%   |
| en_NZ   | 1         | 0.51%   |
| en_IE   | 1         | 0.51%   |
| de_CH   | 1         | 0.51%   |
| cs_CZ   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 130       | 66.33%  |
| BIOS | 66        | 33.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 163       | 85.34%  |
| Ext4    | 26        | 13.61%  |
| Btrfs   | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 128       | 64.97%  |
| GPT     | 51        | 25.89%  |
| MBR     | 18        | 9.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 91.67%  |
| Yes       | 16        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 93.78%  |
| Yes       | 12        | 6.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 70        | 36.65%  |
| Dell                | 44        | 23.04%  |
| Hewlett-Packard     | 25        | 13.09%  |
| ASUSTek Computer    | 17        | 8.9%    |
| Gigabyte Technology | 8         | 4.19%   |
| ASRock              | 5         | 2.62%   |
| MSI                 | 4         | 2.09%   |
| Intel               | 3         | 1.57%   |
| ZTSYSTEMS           | 2         | 1.05%   |
| Supermicro          | 2         | 1.05%   |
| Sony                | 2         | 1.05%   |
| TUXEDO              | 1         | 0.52%   |
| Toshiba             | 1         | 0.52%   |
| Timi                | 1         | 0.52%   |
| Samsung Electronics | 1         | 0.52%   |
| MiTAC               | 1         | 0.52%   |
| CX / Air Computers. | 1         | 0.52%   |
| Alienware           | 1         | 0.52%   |
| Acer                | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 3.14%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 2.09%   |
| Dell PowerEdge R230                      | 4         | 2.09%   |
| ASUS All Series                          | 4         | 2.09%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 1.05%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 1.05%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 1.05%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 1.05%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 1.05%   |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 1.05%   |
| HP Z620 Workstation                      | 2         | 1.05%   |
| HP EliteBook 8460p                       | 2         | 1.05%   |
| Dell PowerEdge R740                      | 2         | 1.05%   |
| Dell Latitude E6430                      | 2         | 1.05%   |
| Dell Latitude 5300                       | 2         | 1.05%   |
| ZTSYSTEMS Z802                           | 1         | 0.52%   |
| ZTSYSTEMS Z801                           | 1         | 0.52%   |
| TUXEDO N13xWU                            | 1         | 0.52%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.52%   |
| Timi TM1707                              | 1         | 0.52%   |
| Supermicro X7DW3                         | 1         | 0.52%   |
| Supermicro X10DRi                        | 1         | 0.52%   |
| Sony VPCEB4L1R                           | 1         | 0.52%   |
| Sony VPCEB23FM                           | 1         | 0.52%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.52%   |
| MSI MS-7B51                              | 1         | 0.52%   |
| MSI MS-7B33                              | 1         | 0.52%   |
| MSI MS-7A37                              | 1         | 0.52%   |
| MSI MS-7752                              | 1         | 0.52%   |
| MiTAC C4I                                | 1         | 0.52%   |
| Lenovo Z40-70 20366                      | 1         | 0.52%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.52%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.52%   |
| Lenovo ThinkpadT460 20BUS0QT0A           | 1         | 0.52%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.52%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.52%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.52%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.52%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.52%   |
| Lenovo ThinkPad X1 Yoga 1st 20FRS17K00   | 1         | 0.52%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.52%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.52%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.52%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.52%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.52%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.52%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.52%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.52%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.52%   |
| Lenovo ThinkPad T490 20N3S5DU27          | 1         | 0.52%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.52%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.52%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.52%   |
| Lenovo ThinkPad T470p 20J7S0FA0E         | 1         | 0.52%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.52%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.52%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.52%   |
| Lenovo ThinkPad T14s Gen 1 20UJ000WMH    | 1         | 0.52%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N    | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 59        | 30.89%  |
| Dell PowerEdge      | 14        | 7.33%   |
| Dell Precision      | 10        | 5.24%   |
| Dell Latitude       | 10        | 5.24%   |
| HP ProLiant         | 5         | 2.62%   |
| HP EliteBook        | 4         | 2.09%   |
| ASUS All            | 4         | 2.09%   |
| Lenovo ThinkCentre  | 3         | 1.57%   |
| HP ZBook            | 3         | 1.57%   |
| Dell Inspiron       | 3         | 1.57%   |
| ASUS PRIME          | 3         | 1.57%   |
| Lenovo 7X56CTO1WW   | 2         | 1.05%   |
| HP Z620             | 2         | 1.05%   |
| HP Z230             | 2         | 1.05%   |
| Dell OptiPlex       | 2         | 1.05%   |
| ASUS ROG            | 2         | 1.05%   |
| ZTSYSTEMS Z802      | 1         | 0.52%   |
| ZTSYSTEMS Z801      | 1         | 0.52%   |
| TUXEDO N13xWU       | 1         | 0.52%   |
| Toshiba Satellite   | 1         | 0.52%   |
| Timi TM1707         | 1         | 0.52%   |
| Supermicro X7DW3    | 1         | 0.52%   |
| Supermicro X10DRi   | 1         | 0.52%   |
| Sony VPCEB4L1R      | 1         | 0.52%   |
| Sony VPCEB23FM      | 1         | 0.52%   |
| Samsung 730QCJ      | 1         | 0.52%   |
| MSI MS-7B51         | 1         | 0.52%   |
| MSI MS-7B33         | 1         | 0.52%   |
| MSI MS-7A37         | 1         | 0.52%   |
| MSI MS-7752         | 1         | 0.52%   |
| MiTAC C4I           | 1         | 0.52%   |
| Lenovo Z40-70       | 1         | 0.52%   |
| Lenovo Yoga         | 1         | 0.52%   |
| Lenovo ThinkSystem  | 1         | 0.52%   |
| Lenovo ThinkpadT460 | 1         | 0.52%   |
| Lenovo S40-40       | 1         | 0.52%   |
| Lenovo 10SFS03200   | 1         | 0.52%   |
| Intel NUC11BTMi7    | 1         | 0.52%   |
| Intel NUC10i7FNK    | 1         | 0.52%   |
| Intel DX79SR        | 1         | 0.52%   |
| HP Z840             | 1         | 0.52%   |
| HP Z440             | 1         | 0.52%   |
| HP ProBook          | 1         | 0.52%   |
| HP Pavilion         | 1         | 0.52%   |
| HP OMEN             | 1         | 0.52%   |
| HP EliteDesk        | 1         | 0.52%   |
| HP 290              | 1         | 0.52%   |
| HP 260-P020il       | 1         | 0.52%   |
| HP 250              | 1         | 0.52%   |
| Gigabyte Z97N-WIFI  | 1         | 0.52%   |
| Gigabyte Z490       | 1         | 0.52%   |
| Gigabyte Z390       | 1         | 0.52%   |
| Gigabyte B85M-D3V-A | 1         | 0.52%   |
| Gigabyte B75-D3V    | 1         | 0.52%   |
| Gigabyte B150-HD3   | 1         | 0.52%   |
| Gigabyte AERO       | 1         | 0.52%   |
| Gigabyte 970A-D3    | 1         | 0.52%   |
| Dell XS23-TY3       | 1         | 0.52%   |
| Dell XPS            | 1         | 0.52%   |
| Dell Vostro         | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 34        | 17.8%   |
| 2018 | 32        | 16.75%  |
| 2020 | 29        | 15.18%  |
| 2017 | 18        | 9.42%   |
| 2012 | 16        | 8.38%   |
| 2016 | 13        | 6.81%   |
| 2015 | 13        | 6.81%   |
| 2013 | 10        | 5.24%   |
| 2021 | 7         | 3.66%   |
| 2011 | 7         | 3.66%   |
| 2010 | 6         | 3.14%   |
| 2014 | 4         | 2.09%   |
| 2009 | 2         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 104       | 54.45%  |
| Desktop     | 61        | 31.94%  |
| Server      | 20        | 10.47%  |
| Mini pc     | 3         | 1.57%   |
| Convertible | 2         | 1.05%   |
| All in one  | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 175       | 90.67%  |
| Enabled  | 18        | 9.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 191       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 46        | 23.59%  |
| 64.01-256.0     | 34        | 17.44%  |
| 4.01-8.0        | 32        | 16.41%  |
| 16.01-24.0      | 31        | 15.9%   |
| 8.01-16.0       | 29        | 14.87%  |
| 24.01-32.0      | 9         | 4.62%   |
| 3.01-4.0        | 7         | 3.59%   |
| More than 256.0 | 5         | 2.56%   |
| 2.01-3.0        | 1         | 0.51%   |
| Unknown         | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 78        | 36.11%  |
| 2.01-3.0        | 39        | 18.06%  |
| 8.01-16.0       | 34        | 15.74%  |
| 3.01-4.0        | 30        | 13.89%  |
| 1.01-2.0        | 19        | 8.8%    |
| 16.01-24.0      | 5         | 2.31%   |
| 24.01-32.0      | 4         | 1.85%   |
| 32.01-64.0      | 2         | 0.93%   |
| 0.51-1.0        | 2         | 0.93%   |
| More than 256.0 | 1         | 0.46%   |
| 64.01-256.0     | 1         | 0.46%   |
| Unknown         | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 105       | 52.5%   |
| 2      | 43        | 21.5%   |
| 3      | 25        | 12.5%   |
| 5      | 8         | 4%      |
| 4      | 8         | 4%      |
| 12     | 3         | 1.5%    |
| 6      | 3         | 1.5%    |
| 8      | 2         | 1%      |
| 14     | 1         | 0.5%    |
| 11     | 1         | 0.5%    |
| 7      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 76.17%  |
| Yes       | 46        | 23.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 93.75%  |
| No        | 12        | 6.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 70.68%  |
| No        | 56        | 29.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 55.1%   |
| No        | 88        | 44.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 48        | 25%     |
| India        | 16        | 8.33%   |
| Germany      | 15        | 7.81%   |
| UK           | 10        | 5.21%   |
| Czechia      | 10        | 5.21%   |
| Norway       | 6         | 3.13%   |
| France       | 6         | 3.13%   |
| Canada       | 6         | 3.13%   |
| Spain        | 4         | 2.08%   |
| Poland       | 4         | 2.08%   |
| Netherlands  | 4         | 2.08%   |
| Mexico       | 4         | 2.08%   |
| Italy        | 4         | 2.08%   |
| Switzerland  | 3         | 1.56%   |
| Russia       | 3         | 1.56%   |
| Lithuania    | 3         | 1.56%   |
| Brazil       | 3         | 1.56%   |
| Argentina    | 3         | 1.56%   |
| Ukraine      | 2         | 1.04%   |
| South Korea  | 2         | 1.04%   |
| South Africa | 2         | 1.04%   |
| Singapore    | 2         | 1.04%   |
| Romania      | 2         | 1.04%   |
| Japan        | 2         | 1.04%   |
| Austria      | 2         | 1.04%   |
| Australia    | 2         | 1.04%   |
| Turkmenistan | 1         | 0.52%   |
| Turkey       | 1         | 0.52%   |
| Sweden       | 1         | 0.52%   |
| Saudi Arabia | 1         | 0.52%   |
| Portugal     | 1         | 0.52%   |
| Pakistan     | 1         | 0.52%   |
| New Zealand  | 1         | 0.52%   |
| Nepal        | 1         | 0.52%   |
| Myanmar      | 1         | 0.52%   |
| Morocco      | 1         | 0.52%   |
| Luxembourg   | 1         | 0.52%   |
| Kuwait       | 1         | 0.52%   |
| Israel       | 1         | 0.52%   |
| Ireland      | 1         | 0.52%   |
| Indonesia    | 1         | 0.52%   |
| Georgia      | 1         | 0.52%   |
| Egypt        | 1         | 0.52%   |
| Ecuador      | 1         | 0.52%   |
| Colombia     | 1         | 0.52%   |
| China        | 1         | 0.52%   |
| Bulgaria     | 1         | 0.52%   |
| Belgium      | 1         | 0.52%   |
| Belarus      | 1         | 0.52%   |
| Armenia      | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Quincy                   | 8         | 3.9%    |
| Muggensturm              | 6         | 2.93%   |
| Brno                     | 6         | 2.93%   |
| TromsÃ¸                | 4         | 1.95%   |
| Munich                   | 3         | 1.46%   |
| Milan                    | 3         | 1.46%   |
| Mexico City              | 3         | 1.46%   |
| Chicago                  | 3         | 1.46%   |
| Vienna                   | 2         | 0.98%   |
| Toronto                  | 2         | 0.98%   |
| Singapore                | 2         | 0.98%   |
| San Jose                 | 2         | 0.98%   |
| Prague                   | 2         | 0.98%   |
| Mumbai                   | 2         | 0.98%   |
| Madrid                   | 2         | 0.98%   |
| Kyiv                     | 2         | 0.98%   |
| Kongsberg                | 2         | 0.98%   |
| Doetinchem               | 2         | 0.98%   |
| Coimbatore               | 2         | 0.98%   |
| Berlin                   | 2         | 0.98%   |
| Bengaluru                | 2         | 0.98%   |
| Å iauliai              | 2         | 0.98%   |
| Aurora                   | 2         | 0.98%   |
| Yorktown Heights         | 1         | 0.49%   |
| Yerevan                  | 1         | 0.49%   |
| Wroclaw                  | 1         | 0.49%   |
| Wiesbaden                | 1         | 0.49%   |
| Weybridge                | 1         | 0.49%   |
| Webster                  | 1         | 0.49%   |
| Warsaw                   | 1         | 0.49%   |
| Valmontone               | 1         | 0.49%   |
| Vaestra Froelunda        | 1         | 0.49%   |
| TÃ¡bor                 | 1         | 0.49%   |
| Tauranga                 | 1         | 0.49%   |
| Taringa                  | 1         | 0.49%   |
| Suwon                    | 1         | 0.49%   |
| Sumida                   | 1         | 0.49%   |
| Stroud                   | 1         | 0.49%   |
| Spokane                  | 1         | 0.49%   |
| Sofia                    | 1         | 0.49%   |
| Sheffield                | 1         | 0.49%   |
| Seoul                    | 1         | 0.49%   |
| Saratov                  | 1         | 0.49%   |
| San Francisco            | 1         | 0.49%   |
| San Fernando             | 1         | 0.49%   |
| Sammamish                | 1         | 0.49%   |
| Salvador                 | 1         | 0.49%   |
| Saltillo                 | 1         | 0.49%   |
| SalÃ©                  | 1         | 0.49%   |
| Saint-Ismier             | 1         | 0.49%   |
| Saint-Alphonse-Rodriguez | 1         | 0.49%   |
| Sagaing                  | 1         | 0.49%   |
| Roudnice nad Labem       | 1         | 0.49%   |
| Rosario                  | 1         | 0.49%   |
| Roha                     | 1         | 0.49%   |
| Rochester                | 1         | 0.49%   |
| Rensselaer               | 1         | 0.49%   |
| Reims                    | 1         | 0.49%   |
| Raleigh                  | 1         | 0.49%   |
| Quito                    | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 86     | 17.29%  |
| WDC                 | 42        | 75     | 14.24%  |
| Seagate             | 42        | 86     | 14.24%  |
| Toshiba             | 26        | 40     | 8.81%   |
| SanDisk             | 16        | 27     | 5.42%   |
| SK Hynix            | 15        | 19     | 5.08%   |
| Intel               | 14        | 19     | 4.75%   |
| Kingston            | 11        | 15     | 3.73%   |
| Micron Technology   | 9         | 17     | 3.05%   |
| Crucial             | 8         | 12     | 2.71%   |
| Unknown             | 7         | 9      | 2.37%   |
| HGST                | 5         | 8      | 1.69%   |
| Dell                | 5         | 9      | 1.69%   |
| A-DATA Technology   | 5         | 5      | 1.69%   |
| PNY                 | 3         | 6      | 1.02%   |
| Phison              | 3         | 7      | 1.02%   |
| Hitachi             | 3         | 3      | 1.02%   |
| Hewlett-Packard     | 3         | 11     | 1.02%   |
| Corsair             | 3         | 6      | 1.02%   |
| Western Digital     | 2         | 2      | 0.68%   |
| Silicon Motion      | 2         | 3      | 0.68%   |
| Lenovo              | 2         | 2      | 0.68%   |
| XPG                 | 1         | 1      | 0.34%   |
| Transcend           | 1         | 1      | 0.34%   |
| Team                | 1         | 2      | 0.34%   |
| T-FORCE             | 1         | 2      | 0.34%   |
| SMI                 | 1         | 2      | 0.34%   |
| SCST_FIO            | 1         | 9      | 0.34%   |
| SABRENT             | 1         | 1      | 0.34%   |
| OCZ                 | 1         | 2      | 0.34%   |
| NVMe                | 1         | 1      | 0.34%   |
| Lite-On             | 1         | 1      | 0.34%   |
| KingFast            | 1         | 1      | 0.34%   |
| KINGBANK            | 1         | 1      | 0.34%   |
| HPT                 | 1         | 1      | 0.34%   |
| Hoodisk             | 1         | 1      | 0.34%   |
| Gigabyte Technology | 1         | 1      | 0.34%   |
| DELLBOSS            | 1         | 1      | 0.34%   |
| China               | 1         | 1      | 0.34%   |
| Anobit              | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB          | 10        | 2.95%   |
| Samsung NVMe SSD Drive 512GB           | 7         | 2.06%   |
| Sandisk NVMe SSD Drive 256GB           | 6         | 1.77%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 5         | 1.47%   |
| Samsung SSD 860 EVO 1TB                | 5         | 1.47%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 5         | 1.47%   |
| Samsung NVMe SSD Drive 1024GB          | 5         | 1.47%   |
| Toshiba MG04ACA100NY 1TB               | 4         | 1.18%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 1.18%   |
| Intel NVMe SSD Drive 512GB             | 4         | 1.18%   |
| Dell MD34xx 26TB                       | 4         | 1.18%   |
| WDC WD5003ABYZ-011FA0 500GB            | 3         | 0.88%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.88%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.88%   |
| Samsung NVMe SSD Drive 2TB             | 3         | 0.88%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.88%   |
| Micron NVMe SSD Drive 256GB            | 3         | 0.88%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.59%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 2         | 0.59%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 0.59%   |
| Unknown NVMe SSD Drive 256GB           | 2         | 0.59%   |
| Toshiba NVMe SSD Drive 1024GB          | 2         | 0.59%   |
| Toshiba DT01ACA200 2TB                 | 2         | 0.59%   |
| Toshiba AL14SEB18EQ 1.8TB              | 2         | 0.59%   |
| Seagate ST91000640NS 1TB               | 2         | 0.59%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.59%   |
| Seagate ST4000NM0033-9ZM170 4TB        | 2         | 0.59%   |
| Seagate ST300MP0026 304GB              | 2         | 0.59%   |
| Seagate ST2000NX0433 2TB               | 2         | 0.59%   |
| Seagate ST2000NX0273 2TB               | 2         | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.59%   |
| Seagate ST1000DM003-9YN162 1TB         | 2         | 0.59%   |
| Seagate Expansion 1TB                  | 2         | 0.59%   |
| Sandisk NVMe SSD Drive 512GB           | 2         | 0.59%   |
| Samsung Portable SSD T5 500GB          | 2         | 0.59%   |
| Kingston SUV500120G 120GB SSD          | 2         | 0.59%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.59%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 0.59%   |
| Intel NVMe SSD Drive 2TB               | 2         | 0.59%   |
| Crucial CT480BX500SSD1 480GB           | 2         | 0.59%   |
| Corsair Force LE SSD 240GB             | 2         | 0.59%   |
| XPG NVMe SSD Drive 1024GB              | 1         | 0.29%   |
| Western Digital WUS3BA176C7P3E3 8TB    | 1         | 0.29%   |
| Western Digital NVMe SSD Drive 960GB   | 1         | 0.29%   |
| WDC WDS400T2B0A-00SM50 4TB SSD         | 1         | 0.29%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.29%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1         | 0.29%   |
| WDC WDS200T2B0B-00YS70 2TB SSD         | 1         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1         | 0.29%   |
| WDC WD7500BPKT-00PK4T0 752GB           | 1         | 0.29%   |
| WDC WD6400BPVT-75HXZT1 640GB           | 1         | 0.29%   |
| WDC WD60 EFAX-68JH4N1 6TB              | 1         | 0.29%   |
| WDC WD60 EFAX-68JH4N0 6TB              | 1         | 0.29%   |
| WDC WD5000LPLX-08ZNTT0 500GB           | 1         | 0.29%   |
| WDC WD5000HHTZ-04N21V0 500GB           | 1         | 0.29%   |
| WDC WD5000AAKX-75U6AA0 500GB           | 1         | 0.29%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 90        | 143    | 33.83%  |
| HDD     | 90        | 214    | 33.83%  |
| SSD     | 78        | 129    | 29.32%  |
| MMC     | 4         | 5      | 1.5%    |
| Unknown | 4         | 6      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 318    | 51.28%  |
| NVMe | 90        | 143    | 38.46%  |
| SAS  | 20        | 31     | 8.55%   |
| MMC  | 4         | 5      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 137    | 40.88%  |
| 0.51-1.0   | 58        | 96     | 32.04%  |
| 1.01-2.0   | 24        | 50     | 13.26%  |
| 3.01-4.0   | 13        | 33     | 7.18%   |
| 4.01-10.0  | 6         | 17     | 3.31%   |
| 20.01-50.0 | 4         | 8      | 2.21%   |
| 2.01-3.0   | 1         | 1      | 0.55%   |
| 10.01-20.0 | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 29.85%  |
| 251-500        | 35        | 17.41%  |
| 501-1000       | 33        | 16.42%  |
| More than 3000 | 18        | 8.96%   |
| 1001-2000      | 18        | 8.96%   |
| Unknown        | 13        | 6.47%   |
| 51-100         | 8         | 3.98%   |
| 2001-3000      | 7         | 3.48%   |
| 1-20           | 6         | 2.99%   |
| 21-50          | 3         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 21.96%  |
| 21-50          | 45        | 21.03%  |
| 101-250        | 40        | 18.69%  |
| 51-100         | 26        | 12.15%  |
| 251-500        | 17        | 7.94%   |
| Unknown        | 13        | 6.07%   |
| 501-1000       | 11        | 5.14%   |
| 1001-2000      | 8         | 3.74%   |
| More than 3000 | 4         | 1.87%   |
| 2001-3000      | 3         | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 6      | 42.86%  |
| Seagate | 3         | 5      | 42.86%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 307    | 63.11%  |
| Works    | 68        | 176    | 33.01%  |
| Malfunc  | 8         | 14     | 3.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 129       | 49.43%  |
| Samsung Electronics          | 34        | 13.03%  |
| Broadcom / LSI               | 13        | 4.98%   |
| SK Hynix                     | 12        | 4.6%    |
| Sandisk                      | 12        | 4.6%    |
| AMD                          | 12        | 4.6%    |
| Toshiba America Info Systems | 10        | 3.83%   |
| LSI Logic / Symbios Logic    | 7         | 2.68%   |
| Phison Electronics           | 4         | 1.53%   |
| Micron Technology            | 4         | 1.53%   |
| Marvell Technology Group     | 4         | 1.53%   |
| Hewlett-Packard              | 4         | 1.53%   |
| Silicon Motion               | 3         | 1.15%   |
| ASMedia Technology           | 3         | 1.15%   |
| Western Digital              | 2         | 0.77%   |
| Lenovo                       | 2         | 0.77%   |
| KIOXIA                       | 2         | 0.77%   |
| Lite-On Technology           | 1         | 0.38%   |
| HighPoint Technologies       | 1         | 0.38%   |
| Biwin Storage Technology     | 1         | 0.38%   |
| ADATA Technology             | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 8.28%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 14        | 4.64%   |
| SK Hynix Non-Volatile memory controller                                          | 12        | 3.97%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 12        | 3.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 3.64%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 3.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 2.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.65%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 8         | 2.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 7         | 2.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.99%   |
| Intel SSD 660P Series                                                            | 5         | 1.66%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.66%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.32%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                             | 4         | 1.32%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 1.32%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.32%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 4         | 1.32%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 1.32%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 4         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 1.32%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 4         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.99%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.99%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.99%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.66%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.66%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.66%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.66%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.66%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.66%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.66%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.66%   |
| HP Smart Array Gen8 Controllers                                                  | 2         | 0.66%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 2         | 0.66%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                      | 1         | 0.33%   |
| Western Digital Ultrastar DC SN630 NVMe SSD                                      | 1         | 0.33%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.33%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.33%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.33%   |
| Samsung NVMe SSD Controller PM173X                                               | 1         | 0.33%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 45.42%  |
| NVMe | 91        | 34.73%  |
| RAID | 35        | 13.36%  |
| SAS  | 10        | 3.82%   |
| IDE  | 7         | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 176       | 92.15%  |
| AMD    | 15        | 7.85%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.71%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 4.71%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 3.14%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 4         | 2.09%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 2.09%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 2.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.09%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 3         | 1.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.57%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.57%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 2         | 1.05%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 1.05%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 2         | 1.05%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 1.05%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 1.05%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 2         | 1.05%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.05%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.05%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.05%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.05%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.05%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.52%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.52%   |
| Intel Xeon Gold 6263CY CPU @ 2.60GHz          | 1         | 0.52%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz            | 1         | 0.52%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.52%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.52%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.52%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.52%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.52%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.52%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.52%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz           | 1         | 0.52%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.52%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.52%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.52%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 79        | 41.36%  |
| Intel Xeon         | 37        | 19.37%  |
| Intel Core i5      | 36        | 18.85%  |
| Intel Core i3      | 10        | 5.24%   |
| AMD Ryzen 7        | 5         | 2.62%   |
| Other              | 4         | 2.09%   |
| AMD Ryzen 9        | 3         | 1.57%   |
| Intel Xeon Silver  | 2         | 1.05%   |
| Intel Xeon Gold    | 2         | 1.05%   |
| Intel Pentium Gold | 2         | 1.05%   |
| Intel Core i9      | 2         | 1.05%   |
| AMD Ryzen 3        | 2         | 1.05%   |
| AMD EPYC           | 2         | 1.05%   |
| Intel Pentium      | 1         | 0.52%   |
| Intel Core 2 Duo   | 1         | 0.52%   |
| AMD Ryzen 7 PRO    | 1         | 0.52%   |
| AMD Ryzen 5        | 1         | 0.52%   |
| AMD FX             | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 78        | 40.84%  |
| 2      | 40        | 20.94%  |
| 6      | 29        | 15.18%  |
| 8      | 17        | 8.9%    |
| 12     | 9         | 4.71%   |
| 16     | 6         | 3.14%   |
| 20     | 4         | 2.09%   |
| 36     | 2         | 1.05%   |
| 24     | 2         | 1.05%   |
| 96     | 1         | 0.52%   |
| 64     | 1         | 0.52%   |
| 48     | 1         | 0.52%   |
| 32     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 165       | 86.39%  |
| 2      | 26        | 13.61%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 164       | 85.42%  |
| 1      | 28        | 14.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 183       | 94.82%  |
| Unknown        | 10        | 5.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 25        | 12.95%  |
| 0x906ea    | 14        | 7.25%   |
| Unknown    | 12        | 6.22%   |
| 0x806ea    | 11        | 5.7%    |
| 0x306c3    | 11        | 5.7%    |
| 0xa0652    | 10        | 5.18%   |
| 0x306a9    | 10        | 5.18%   |
| 0x306f2    | 9         | 4.66%   |
| 0x506e3    | 8         | 4.15%   |
| 0x206a7    | 8         | 4.15%   |
| 0x906ed    | 6         | 3.11%   |
| 0x906e9    | 6         | 3.11%   |
| 0x406e3    | 6         | 3.11%   |
| 0x806e9    | 5         | 2.59%   |
| 0x406f1    | 5         | 2.59%   |
| 0x806d1    | 4         | 2.07%   |
| 0x306e4    | 4         | 2.07%   |
| 0x206d7    | 4         | 2.07%   |
| 0x306d4    | 3         | 1.55%   |
| 0x206c2    | 3         | 1.55%   |
| 0x20655    | 3         | 1.55%   |
| 0x08108102 | 3         | 1.55%   |
| 0x40651    | 2         | 1.04%   |
| 0x08701021 | 2         | 1.04%   |
| 0x08600103 | 2         | 1.04%   |
| 0xa0660    | 1         | 0.52%   |
| 0xa0655    | 1         | 0.52%   |
| 0x906eb    | 1         | 0.52%   |
| 0x806c1    | 1         | 0.52%   |
| 0x50657    | 1         | 0.52%   |
| 0x50654    | 1         | 0.52%   |
| 0x20652    | 1         | 0.52%   |
| 0x1067a    | 1         | 0.52%   |
| 0x10676    | 1         | 0.52%   |
| 0x0a001119 | 1         | 0.52%   |
| 0x08701013 | 1         | 0.52%   |
| 0x08600104 | 1         | 0.52%   |
| 0x08301034 | 1         | 0.52%   |
| 0x0810100b | 1         | 0.52%   |
| 0x08001138 | 1         | 0.52%   |
| 0x08001137 | 1         | 0.52%   |
| 0x06000852 | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 69        | 35.94%  |
| Haswell     | 24        | 12.5%   |
| Skylake     | 22        | 11.46%  |
| IvyBridge   | 15        | 7.81%   |
| SandyBridge | 12        | 6.25%   |
| CometLake   | 12        | 6.25%   |
| Broadwell   | 8         | 4.17%   |
| Zen 2       | 7         | 3.65%   |
| Westmere    | 7         | 3.65%   |
| Zen+        | 3         | 1.56%   |
| Zen         | 3         | 1.56%   |
| Icelake     | 3         | 1.56%   |
| Unknown     | 3         | 1.56%   |
| Penryn      | 2         | 1.04%   |
| TigerLake   | 1         | 0.52%   |
| Piledriver  | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 117       | 50.65%  |
| Nvidia                     | 66        | 28.57%  |
| AMD                        | 22        | 9.52%   |
| Matrox Electronics Systems | 19        | 8.23%   |
| ASPEED Technology          | 7         | 3.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 16        | 6.87%   |
| Matrox Electronics Systems G200eR2                                          | 11        | 4.72%   |
| Intel UHD Graphics 620                                                      | 11        | 4.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 10        | 4.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 9         | 3.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 3%      |
| ASPEED Technology ASPEED Graphics Family                                    | 7         | 3%      |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 2.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.15%   |
| Intel HD Graphics 630                                                       | 4         | 1.72%   |
| Intel HD Graphics 620                                                       | 4         | 1.72%   |
| Intel HD Graphics 530                                                       | 4         | 1.72%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.29%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 1.29%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 1.29%   |
| Intel HD Graphics 5500                                                      | 3         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.29%   |
| AMD Renoir                                                                  | 3         | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.86%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.86%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.86%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 2         | 0.86%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.86%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2         | 0.86%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.43%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.43%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.43%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.43%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.43%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.43%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.43%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.43%   |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.43%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 0.43%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.43%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.43%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.43%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.43%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.43%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 82        | 42.49%  |
| 1 x Nvidia      | 39        | 20.21%  |
| Intel + Nvidia  | 23        | 11.92%  |
| 1 x Matrox      | 18        | 9.33%   |
| 1 x AMD         | 12        | 6.22%   |
| Intel + AMD     | 7         | 3.63%   |
| 1 x ASPEED      | 6         | 3.11%   |
| AMD + Nvidia    | 2         | 1.04%   |
| 2 x Nvidia      | 1         | 0.52%   |
| 2 x AMD         | 1         | 0.52%   |
| Nvidia + Matrox | 1         | 0.52%   |
| Nvidia + ASPEED | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 149       | 76.8%   |
| Proprietary | 30        | 15.46%  |
| Unknown     | 15        | 7.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 63.96%  |
| 1.01-2.0   | 20        | 10.15%  |
| 3.01-4.0   | 14        | 7.11%   |
| 0.51-1.0   | 10        | 5.08%   |
| 5.01-6.0   | 8         | 4.06%   |
| 7.01-8.0   | 7         | 3.55%   |
| 0.01-0.5   | 6         | 3.05%   |
| 2.01-3.0   | 3         | 1.52%   |
| 8.01-16.0  | 2         | 1.02%   |
| 4.01-5.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 27        | 12%     |
| AU Optronics            | 24        | 10.67%  |
| Samsung Electronics     | 23        | 10.22%  |
| LG Display              | 18        | 8%      |
| Lenovo                  | 18        | 8%      |
| Chimei Innolux          | 17        | 7.56%   |
| BOE                     | 17        | 7.56%   |
| Goldstar                | 15        | 6.67%   |
| Hewlett-Packard         | 11        | 4.89%   |
| Sharp                   | 5         | 2.22%   |
| InfoVision              | 5         | 2.22%   |
| Acer                    | 5         | 2.22%   |
| Philips                 | 4         | 1.78%   |
| Eizo                    | 4         | 1.78%   |
| BenQ                    | 4         | 1.78%   |
| Ancor Communications    | 3         | 1.33%   |
| ViewSonic               | 2         | 0.89%   |
| PANDA                   | 2         | 0.89%   |
| LGD                     | 2         | 0.89%   |
| Lenovo Group Limited    | 2         | 0.89%   |
| Iiyama                  | 2         | 0.89%   |
| Gigabyte Technology     | 2         | 0.89%   |
| BOE Technology Group    | 2         | 0.89%   |
| AOC                     | 2         | 0.89%   |
| Sun                     | 1         | 0.44%   |
| Sceptre Tech            | 1         | 0.44%   |
| Planar                  | 1         | 0.44%   |
| LG Electronics          | 1         | 0.44%   |
| ITE                     | 1         | 0.44%   |
| Insignia                | 1         | 0.44%   |
| Chi Mei Optoelectronics | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell IDRAC DEL0001 1280x1024                                          | 6         | 2.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 6         | 2.48%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 4         | 1.65%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 1.65%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 1.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 1.24%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.24%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 3         | 1.24%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.24%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.24%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.83%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.83%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.83%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.83%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.83%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.83%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.83%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 0.83%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 0.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.83%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.83%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x173mm 13.9-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.83%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.41%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.41%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.41%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.41%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.41%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.41%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch     | 1         | 0.41%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1         | 0.41%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.41%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 1         | 0.41%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.41%   |
| Samsung Electronics LCD Monitor S22B150                               | 1         | 0.41%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1         | 0.41%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 700x400mm 31.7-inch    | 1         | 0.41%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.41%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch     | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 106       | 52.74%  |
| 3840x2160 (4K)     | 16        | 7.96%   |
| 1366x768 (WXGA)    | 16        | 7.96%   |
| 2560x1440 (QHD)    | 13        | 6.47%   |
| 1600x900 (HD+)     | 11        | 5.47%   |
| 2560x1080          | 6         | 2.99%   |
| 1280x1024 (SXGA)   | 6         | 2.99%   |
| 1920x1200 (WUXGA)  | 5         | 2.49%   |
| Unknown            | 5         | 2.49%   |
| 3840x1080          | 4         | 1.99%   |
| 3440x1440          | 4         | 1.99%   |
| 1440x900 (WXGA+)   | 2         | 1%      |
| 9600x2160          | 1         | 0.5%    |
| 7680x2160          | 1         | 0.5%    |
| 6400x2160          | 1         | 0.5%    |
| 2048x1152          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1280x800 (WXGA)    | 1         | 0.5%    |
| 1280x720 (HD)      | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 19.56%  |
| 14      | 27        | 12%     |
| 27      | 24        | 10.67%  |
| 24      | 23        | 10.22%  |
| 13      | 19        | 8.44%   |
| Unknown | 19        | 8.44%   |
| 23      | 17        | 7.56%   |
| 21      | 10        | 4.44%   |
| 34      | 7         | 3.11%   |
| 31      | 6         | 2.67%   |
| 12      | 5         | 2.22%   |
| 20      | 4         | 1.78%   |
| 54      | 3         | 1.33%   |
| 17      | 3         | 1.33%   |
| 47      | 2         | 0.89%   |
| 32      | 2         | 0.89%   |
| 18      | 2         | 0.89%   |
| 49      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 39      | 1         | 0.44%   |
| 28      | 1         | 0.44%   |
| 25      | 1         | 0.44%   |
| 22      | 1         | 0.44%   |
| 19      | 1         | 0.44%   |
| 11      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 38.71%  |
| 501-600     | 55        | 25.35%  |
| Unknown     | 19        | 8.76%   |
| 401-500     | 17        | 7.83%   |
| 201-300     | 12        | 5.53%   |
| 601-700     | 10        | 4.61%   |
| 701-800     | 9         | 4.15%   |
| 1001-1500   | 6         | 2.76%   |
| 351-400     | 3         | 1.38%   |
| 801-900     | 2         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 78.33%  |
| 16/10   | 12        | 6.67%   |
| Unknown | 11        | 6.11%   |
| 21/9    | 8         | 4.44%   |
| 5/4     | 6         | 3.33%   |
| 32/9    | 1         | 0.56%   |
| 3/2     | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 19.82%  |
| 81-90          | 40        | 18.02%  |
| 201-250        | 39        | 17.57%  |
| 301-350        | 24        | 10.81%  |
| Unknown        | 19        | 8.56%   |
| 351-500        | 14        | 6.31%   |
| 251-300        | 12        | 5.41%   |
| 71-80          | 6         | 2.7%    |
| 151-200        | 6         | 2.7%    |
| 61-70          | 5         | 2.25%   |
| 501-1000       | 5         | 2.25%   |
| More than 1000 | 3         | 1.35%   |
| 121-130        | 3         | 1.35%   |
| 51-60          | 1         | 0.45%   |
| 141-150        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 79        | 36.24%  |
| 51-100        | 66        | 30.28%  |
| 101-120       | 32        | 14.68%  |
| Unknown       | 19        | 8.72%   |
| 161-240       | 12        | 5.5%    |
| More than 240 | 5         | 2.29%   |
| 1-50          | 5         | 2.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 124       | 61.39%  |
| 2     | 46        | 22.77%  |
| 0     | 20        | 9.9%    |
| 3     | 12        | 5.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 149       | 51.74%  |
| Realtek Semiconductor             | 56        | 19.44%  |
| Broadcom                          | 19        | 6.6%    |
| Lenovo                            | 14        | 4.86%   |
| Qualcomm Atheros                  | 12        | 4.17%   |
| Dell                              | 5         | 1.74%   |
| Broadcom Limited                  | 4         | 1.39%   |
| Sierra Wireless                   | 2         | 0.69%   |
| Ralink Technology                 | 2         | 0.69%   |
| Ralink                            | 2         | 0.69%   |
| Marvell Technology Group          | 2         | 0.69%   |
| Huawei Technologies               | 2         | 0.69%   |
| Ericsson Business Mobile Networks | 2         | 0.69%   |
| ASIX Electronics                  | 2         | 0.69%   |
| Xiaomi                            | 1         | 0.35%   |
| Samsung Electronics               | 1         | 0.35%   |
| QLogic                            | 1         | 0.35%   |
| Prolific Technology               | 1         | 0.35%   |
| Microchip Technology              | 1         | 0.35%   |
| Micro Star International          | 1         | 0.35%   |
| Mellanox Technologies             | 1         | 0.35%   |
| MediaTek                          | 1         | 0.35%   |
| Luminary Micro                    | 1         | 0.35%   |
| ICS Advent                        | 1         | 0.35%   |
| IBM                               | 1         | 0.35%   |
| Emulex                            | 1         | 0.35%   |
| DisplayLink                       | 1         | 0.35%   |
| D-Link                            | 1         | 0.35%   |
| Arduino SA                        | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 9.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 4.15%   |
| Intel Wireless 8265 / 8275                                                     | 15        | 3.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 14        | 3.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 11        | 2.85%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 2.59%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 10        | 2.59%   |
| Intel Wireless 8260                                                            | 9         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                            | 9         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 2.07%   |
| Intel I350 Gigabit Network Connection                                          | 8         | 2.07%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 1.81%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 1.81%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.55%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 1.3%    |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 1.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 1.04%   |
| Intel Wireless-AC 9260                                                         | 4         | 1.04%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.04%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.04%   |
| Intel Wireless 7265                                                            | 3         | 0.78%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.78%   |
| Dell iDRAC Virtual NIC USB Device                                              | 3         | 0.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.52%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.52%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.52%   |
| Intel Wireless 7260                                                            | 2         | 0.52%   |
| Intel Wireless 3165                                                            | 2         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.52%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.52%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.52%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.52%   |
| Intel Ethernet Controller 10G X550T                                            | 2         | 0.52%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.52%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.52%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.52%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.52%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.52%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 102       | 72.86%  |
| Qualcomm Atheros         | 11        | 7.86%   |
| Realtek Semiconductor    | 10        | 7.14%   |
| Broadcom                 | 5         | 3.57%   |
| Sierra Wireless          | 2         | 1.43%   |
| Ralink Technology        | 2         | 1.43%   |
| Ralink                   | 2         | 1.43%   |
| Dell                     | 2         | 1.43%   |
| Micro Star International | 1         | 0.71%   |
| MediaTek                 | 1         | 0.71%   |
| D-Link                   | 1         | 0.71%   |
| Broadcom Limited         | 1         | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 15        | 10.71%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 14        | 10%     |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 11        | 7.86%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 10        | 7.14%   |
| Intel Wireless 8260                                                        | 9         | 6.43%   |
| Intel Wi-Fi 6 AX200                                                        | 9         | 6.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 6.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 4.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.86%   |
| Intel Wireless-AC 9260                                                     | 4         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 2.86%   |
| Intel Wireless 7265                                                        | 3         | 2.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 2.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.43%   |
| Intel Wireless 7260                                                        | 2         | 1.43%   |
| Intel Wireless 3165                                                        | 2         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 1.43%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 2         | 1.43%   |
| Sierra Wireless EM7455                                                     | 1         | 0.71%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.71%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.71%   |
| Ralink RT5372 Wireless Adapter                                             | 1         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.71%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.71%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 0.71%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 0.71%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.71%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 0.71%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 118       | 55.4%   |
| Realtek Semiconductor    | 49        | 23%     |
| Lenovo                   | 14        | 6.57%   |
| Broadcom                 | 14        | 6.57%   |
| Broadcom Limited         | 3         | 1.41%   |
| Qualcomm Atheros         | 2         | 0.94%   |
| Marvell Technology Group | 2         | 0.94%   |
| ASIX Electronics         | 2         | 0.94%   |
| Xiaomi                   | 1         | 0.47%   |
| Samsung Electronics      | 1         | 0.47%   |
| QLogic                   | 1         | 0.47%   |
| Mellanox Technologies    | 1         | 0.47%   |
| ICS Advent               | 1         | 0.47%   |
| IBM                      | 1         | 0.47%   |
| Huawei Technologies      | 1         | 0.47%   |
| Emulex                   | 1         | 0.47%   |
| DisplayLink              | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 15.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.78%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.24%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 3.81%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.39%   |
| Intel I350 Gigabit Network Connection                                          | 8         | 3.39%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 7         | 2.97%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.97%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 2.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 2.12%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 2.12%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.69%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.69%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.69%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.69%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.69%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.27%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.85%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.85%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.85%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.85%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.85%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.85%   |
| Intel Ethernet Controller 10G X550T                                            | 2         | 0.85%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.85%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.85%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.85%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.85%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.85%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.85%   |
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

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 55.38%  |
| WiFi     | 135       | 41.54%  |
| Modem    | 7         | 2.15%   |
| Unknown  | 3         | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 164       | 57.54%  |
| WiFi     | 119       | 41.75%  |
| Modem    | 1         | 0.35%   |
| Unknown  | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 111       | 57.81%  |
| 1     | 50        | 26.04%  |
| 3     | 11        | 5.73%   |
| 4     | 8         | 4.17%   |
| 6     | 7         | 3.65%   |
| 132   | 1         | 0.52%   |
| 22    | 1         | 0.52%   |
| 12    | 1         | 0.52%   |
| 8     | 1         | 0.52%   |
| 5     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 90.67%  |
| Yes  | 18        | 9.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 71.3%   |
| Cambridge Silicon Radio         | 8         | 7.41%   |
| Broadcom                        | 6         | 5.56%   |
| Qualcomm Atheros Communications | 4         | 3.7%    |
| Realtek Semiconductor           | 3         | 2.78%   |
| IMC Networks                    | 3         | 2.78%   |
| ASUSTek Computer                | 3         | 2.78%   |
| Ralink                          | 1         | 0.93%   |
| Micro Star International        | 1         | 0.93%   |
| Foxconn / Hon Hai               | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 22.22%  |
| Intel Bluetooth Device                                                              | 21        | 19.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 18.52%  |
| Intel AX200 Bluetooth                                                               | 8         | 7.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.78%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.85%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.85%   |
| ASUS BCM20702A0                                                                     | 2         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.93%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.93%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.93%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.93%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.93%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.93%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.93%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 148       | 55.02%  |
| Nvidia                 | 50        | 18.59%  |
| AMD                    | 20        | 7.43%   |
| Lenovo                 | 15        | 5.58%   |
| Realtek Semiconductor  | 4         | 1.49%   |
| Plantronics            | 4         | 1.49%   |
| Texas Instruments      | 3         | 1.12%   |
| JMTek                  | 3         | 1.12%   |
| GN Netcom              | 3         | 1.12%   |
| Generalplus Technology | 3         | 1.12%   |
| Creative Labs          | 3         | 1.12%   |
| Logitech               | 2         | 0.74%   |
| Creative Technology    | 2         | 0.74%   |
| Tenx Technology        | 1         | 0.37%   |
| RODE Microphones       | 1         | 0.37%   |
| LG Electronics         | 1         | 0.37%   |
| Google                 | 1         | 0.37%   |
| Focusrite-Novation     | 1         | 0.37%   |
| DYNEX                  | 1         | 0.37%   |
| Dell                   | 1         | 0.37%   |
| C-Media Electronics    | 1         | 0.37%   |
| ASUSTek Computer       | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 22        | 7.61%   |
| Intel Cannon Lake PCH cAVS                                                        | 19        | 6.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 16        | 5.54%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 11        | 3.81%   |
| Intel Comet Lake PCH cAVS                                                         | 11        | 3.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 10        | 3.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10        | 3.46%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9         | 3.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9         | 3.11%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 7         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 2.42%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 2.42%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6         | 2.08%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6         | 2.08%   |
| Realtek Semiconductor USB Audio                                                   | 4         | 1.38%   |
| Plantronics BT600                                                                 | 4         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 1.38%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 4         | 1.38%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4         | 1.38%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4         | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.38%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.04%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 1.04%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.04%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 0.69%   |
| Nvidia Audio device                                                               | 2         | 0.69%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.69%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.69%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.69%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.69%   |
| Generalplus Technology USB Audio Device                                           | 2         | 0.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.69%   |
| Tenx Technology USB AUDIO                                                         | 1         | 0.35%   |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.35%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.35%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.35%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.35%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1         | 0.35%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1         | 0.35%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.35%   |
| Logitech H570e Mono                                                               | 1         | 0.35%   |
| Logitech H555 Headset                                                             | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 29.47%  |
| SK Hynix            | 27        | 28.42%  |
| Micron Technology   | 10        | 10.53%  |
| Crucial             | 8         | 8.42%   |
| Kingston            | 6         | 6.32%   |
| Unknown             | 4         | 4.21%   |
| Corsair             | 4         | 4.21%   |
| Hewlett-Packard     | 2         | 2.11%   |
| Unknown (0x0205)    | 1         | 1.05%   |
| Transcend           | 1         | 1.05%   |
| Smart               | 1         | 1.05%   |
| Patriot             | 1         | 1.05%   |
| GOODRAM             | 1         | 1.05%   |
| Elpida              | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 4         | 3.92%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s      | 3         | 2.94%   |
| SK Hynix RAM HMA42GR7MFR4N-TF 16384MB DIMM DDR4 2133MT/s     | 3         | 2.94%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 2         | 1.96%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.96%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.96%   |
| SK Hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s     | 2         | 1.96%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 1.96%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s         | 2         | 1.96%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 2         | 1.96%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s         | 2         | 1.96%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s         | 2         | 1.96%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 2         | 1.96%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.98%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s           | 1         | 0.98%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s             | 1         | 0.98%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.98%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 0.98%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s      | 1         | 0.98%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 0.98%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.98%   |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 1         | 0.98%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s         | 1         | 0.98%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMA84GR7CJR4N-WM 32GB DIMM DDR4 2933MT/s        | 1         | 0.98%   |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 0.98%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 0.98%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 0.98%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                    | 1         | 0.98%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.98%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 0.98%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                   | 1         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 0.98%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 1         | 0.98%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 0.98%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 0.98%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 0.98%   |
| Samsung RAM M393B5173FHD-CF8 4096MB DIMM 1066MT/s            | 1         | 0.98%   |
| Samsung RAM M393A2G40DB0-CPB 16384MB DIMM DDR4 2133MT/s      | 1         | 0.98%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1         | 0.98%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s       | 1         | 0.98%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 667MT/s          | 1         | 0.98%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s       | 1         | 0.98%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.98%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.98%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s             | 1         | 0.98%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 0.98%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s       | 1         | 0.98%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s        | 1         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 0.98%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s         | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 60%     |
| DDR3    | 23        | 28.75%  |
| SDRAM   | 2         | 2.5%    |
| LPDDR3  | 2         | 2.5%    |
| DRAM    | 2         | 2.5%    |
| LPDDR4  | 1         | 1.25%   |
| DDR2    | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 46        | 58.23%  |
| SODIMM       | 29        | 36.71%  |
| RIMM         | 2         | 2.53%   |
| Row Of Chips | 1         | 1.27%   |
| Chip         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 31.33%  |
| 16384 | 24        | 28.92%  |
| 4096  | 21        | 25.3%   |
| 32768 | 8         | 9.64%   |
| 2048  | 2         | 2.41%   |
| 65536 | 1         | 1.2%    |
| 1024  | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 20%     |
| 2400  | 16        | 18.82%  |
| 2667  | 12        | 14.12%  |
| 2133  | 10        | 11.76%  |
| 3200  | 9         | 10.59%  |
| 1333  | 6         | 7.06%   |
| 2666  | 4         | 4.71%   |
| 3600  | 2         | 2.35%   |
| 2933  | 2         | 2.35%   |
| 3266  | 1         | 1.18%   |
| 2048  | 1         | 1.18%   |
| 1867  | 1         | 1.18%   |
| 1866  | 1         | 1.18%   |
| 1334  | 1         | 1.18%   |
| 1066  | 1         | 1.18%   |
| 800   | 1         | 1.18%   |

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
| Chicony Electronics                    | 37        | 29.6%   |
| IMC Networks                           | 16        | 12.8%   |
| Acer                                   | 13        | 10.4%   |
| Realtek Semiconductor                  | 9         | 7.2%    |
| Microdia                               | 9         | 7.2%    |
| Logitech                               | 9         | 7.2%    |
| Sunplus Innovation Technology          | 6         | 4.8%    |
| Unknown                                | 5         | 4%      |
| Suyin                                  | 3         | 2.4%    |
| Samsung Electronics                    | 3         | 2.4%    |
| Lite-On Technology                     | 3         | 2.4%    |
| Generalplus Technology                 | 2         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.6%    |
| Syntek                                 | 1         | 0.8%    |
| Ruision                                | 1         | 0.8%    |
| Quanta                                 | 1         | 0.8%    |
| Microsoft                              | 1         | 0.8%    |
| LG Electronics                         | 1         | 0.8%    |
| Lenovo                                 | 1         | 0.8%    |
| Jieli Technology                       | 1         | 0.8%    |
| ARC International                      | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 19        | 14.96%  |
| IMC Networks Integrated Camera                               | 13        | 10.24%  |
| Acer Integrated Camera                                       | 8         | 6.3%    |
| Realtek Integrated_Webcam_HD                                 | 7         | 5.51%   |
| Unknown FULL HD 1080P Webcam                                 | 4         | 3.15%   |
| Logitech HD Pro Webcam C920                                  | 4         | 3.15%   |
| Chicony Integrated Camera (1280x720@30)                      | 4         | 3.15%   |
| Chicony HP HD Camera                                         | 4         | 3.15%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.36%   |
| Samsung Galaxy A5 (MTP)                                      | 3         | 2.36%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.36%   |
| Lite-On Integrated Camera                                    | 3         | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 2.36%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.36%   |
| Acer SunplusIT Integrated Camera                             | 3         | 2.36%   |
| Microdia Webcam                                              | 2         | 1.57%   |
| Microdia Integrated Webcam                                   | 2         | 1.57%   |
| Generalplus GENERAL WEBCAM                                   | 2         | 1.57%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.57%   |
| Unknown 720p HD Camera                                       | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.79%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.79%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.79%   |
| Suyin HP Truevision HD                                       | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.79%   |
| Sunplus Integrated Webcam                                    | 1         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.79%   |
| Ruision UVC Camera                                           | 1         | 0.79%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.79%   |
| Realtek NexiGo N960E FHD Webcam                              | 1         | 0.79%   |
| Quanta HP HD Camera                                          | 1         | 0.79%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.79%   |
| Logitech Webcam C925e                                        | 1         | 0.79%   |
| Logitech Webcam C310                                         | 1         | 0.79%   |
| Logitech Webcam C270                                         | 1         | 0.79%   |
| Logitech HD Webcam C910                                      | 1         | 0.79%   |
| Logitech B525 HD Webcam                                      | 1         | 0.79%   |
| LG LG UltraFine Display Camera                               | 1         | 0.79%   |
| Lenovo Integrated Webcam                                     | 1         | 0.79%   |
| Jieli USB PHY 2.0                                            | 1         | 0.79%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.79%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.79%   |
| Chicony Integrated IR Camera                                 | 1         | 0.79%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.79%   |
| Chicony HP Webcam                                            | 1         | 0.79%   |
| Chicony HD User Facing                                       | 1         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.79%   |
| ARC International Camera                                     | 1         | 0.79%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.79%   |
| Acer Lenovo Integrated Webcam                                | 1         | 0.79%   |
| Acer Integrated IR Camera                                    | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 28        | 58.33%  |
| Validity Sensors           | 15        | 31.25%  |
| Upek                       | 2         | 4.17%   |
| Shenzhen Goodix Technology | 1         | 2.08%   |
| Samsung Electronics        | 1         | 2.08%   |
| Elan Microelectronics      | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 41.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 10.42%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.08%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 2.08%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 48.45%  |
| 1     | 67        | 34.54%  |
| 2     | 21        | 10.82%  |
| 3     | 9         | 4.64%   |
| 5     | 3         | 1.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 33.57%  |
| Graphics card            | 23        | 16.08%  |
| Unassigned class         | 21        | 14.69%  |
| Communication controller | 18        | 12.59%  |
| Chipcard                 | 11        | 7.69%   |
| Net/wireless             | 6         | 4.2%    |
| Card reader              | 3         | 2.1%    |
| Bluetooth                | 3         | 2.1%    |
| Net/ethernet             | 2         | 1.4%    |
| Multimedia controller    | 2         | 1.4%    |
| Storage/raid             | 1         | 0.7%    |
| Storage/ide              | 1         | 0.7%    |
| Storage                  | 1         | 0.7%    |
| Sound                    | 1         | 0.7%    |
| Network                  | 1         | 0.7%    |
| Camera                   | 1         | 0.7%    |

