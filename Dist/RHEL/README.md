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

Total: 316

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f08ef13508](https://linux-hardware.org/?probe=f08ef13508) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
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
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7052b7628f](https://linux-hardware.org/?probe=7052b7628f) | Nov 18, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
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
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
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
| Dell          | PowerEdge FC630             | Desktop     | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| ASRock        | H270 Pro4                   | Desktop     | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
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
| Lenovo        | ThinkPad T460 20BUS0QT0A    | Notebook    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell          | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ded8f80f0a](https://linux-hardware.org/?probe=ded8f80f0a) | Nov 18, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | Desktop     | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | Desktop     | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell          | Latitude E6420              | Notebook    | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| MSI           | H310M PRO-VD                | Desktop     | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell          | Precision 7510              | Notebook    | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP            | Pavilion 14                 | Notebook    | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
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
| HP            | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell          | G3 3779                     | Notebook    | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell          | Precision 5540              | Notebook    | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Gigabyte      | B75-D3V                     | Desktop     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Alienware     | 0VDT73 A00                  | Desktop     | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [e2a3815dd2](https://linux-hardware.org/?probe=e2a3815dd2) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [da0c7d43d0](https://linux-hardware.org/?probe=da0c7d43d0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [07bde7dae0](https://linux-hardware.org/?probe=07bde7dae0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [6e7911571a](https://linux-hardware.org/?probe=6e7911571a) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [502ac45263](https://linux-hardware.org/?probe=502ac45263) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [412539e106](https://linux-hardware.org/?probe=412539e106) | Feb 21, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo        | ThinkPad T490s 20NX002HU... | Notebook    | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | Desktop     | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Dell          | 0G919G A00                  | Desktop     | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
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
| RHEL 8 | 162       | 78.26%  |
| RHEL 7 | 39        | 18.84%  |
| RHEL 9 | 6         | 2.9%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 206       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64                 | 14        | 5.76%   |
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 5.76%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 12        | 4.94%   |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 4.53%   |
| 4.18.0-305.el8.x86_64                        | 10        | 4.12%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 3.7%    |
| 4.18.0-348.12.2.el8_5.x86_64                 | 8         | 3.29%   |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 3.29%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 3.29%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 8         | 3.29%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 2.88%   |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 2.47%   |
| 4.18.0-193.el8.x86_64                        | 6         | 2.47%   |
| 4.18.0-193.19.1.el8_2.x86_64                 | 6         | 2.47%   |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 2.47%   |
| 4.18.0-147.3.1.el8_1.x86_64                  | 6         | 2.47%   |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 2.47%   |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 2.06%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 2.06%   |
| 5.14.0-70.5.1.el9_0.x86_64                   | 4         | 1.65%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.65%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.65%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.65%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.65%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.65%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 3         | 1.23%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 1.23%   |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 1.23%   |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 1.23%   |
| 4.18.0-348.el8.x86_64                        | 2         | 0.82%   |
| 4.18.0-305.17.1.el8_4.x86_64                 | 2         | 0.82%   |
| 4.18.0-240.8.1.el8_3.x86_64                  | 2         | 0.82%   |
| 4.18.0-193.14.3.el8_2.x86_64                 | 2         | 0.82%   |
| 4.18.0-193.1.2.el8_2.x86_64                  | 2         | 0.82%   |
| 3.10.0-1160.6.1.el7.x86_64                   | 2         | 0.82%   |
| 3.10.0-1160.2.2.el7.x86_64                   | 2         | 0.82%   |
| 3.10.0-1160.15.2.el7.x86_64                  | 2         | 0.82%   |
| 3.10.0-1127.13.1.el7.x86_64                  | 2         | 0.82%   |
| 5.9.1-1.el8.elrepo.x86_64                    | 1         | 0.41%   |
| 5.14.0-39.el9.x86_64                         | 1         | 0.41%   |
| 5.14.0-1.7.1.el9.x86_64                      | 1         | 0.41%   |
| 5.13.0-1.el8.elrepo.x86_64                   | 1         | 0.41%   |
| 5.10.6-1.el8.elrepo.x86_64                   | 1         | 0.41%   |
| 4.19.150                                     | 1         | 0.41%   |
| 4.18.0-80.el8.x86_64                         | 1         | 0.41%   |
| 4.18.0-80.4.2.el8_0.x86_64                   | 1         | 0.41%   |
| 4.18.0-372.9.1.el8.x86_64                    | 1         | 0.41%   |
| 4.18.0-221.el8.x86_64                        | 1         | 0.41%   |
| 4.18.0-193.23.1.el8_2.x86_64                 | 1         | 0.41%   |
| 4.18.0-193.13.2.el8_2.x86_64                 | 1         | 0.41%   |
| 4.18.0-168.el8.x86_64                        | 1         | 0.41%   |
| 4.18.0-147.0.3.el8_1.x86_64                  | 1         | 0.41%   |
| 4.18.0-144.el8.x86_64                        | 1         | 0.41%   |
| 3.10.0-957.el7.x86_64                        | 1         | 0.41%   |
| 3.10.0-957.5.1.el7.x86_64                    | 1         | 0.41%   |
| 3.10.0-957.21.3.el7.x86_64                   | 1         | 0.41%   |
| 3.10.0-957.10.1.el7.YAHOO.20190320.30.x86_64 | 1         | 0.41%   |
| 3.10.0-957.10.1.el7.x86_64                   | 1         | 0.41%   |
| 3.10.0-957.1.3.el7.x86_64                    | 1         | 0.41%   |
| 3.10.0-862.9.1.el7.x86_64                    | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 157       | 75.85%  |
| 3.10.0   | 39        | 18.84%  |
| 5.14.0   | 6         | 2.9%    |
| 5.9.1    | 1         | 0.48%   |
| 5.13.0   | 1         | 0.48%   |
| 5.10.6   | 1         | 0.48%   |
| 4.19.150 | 1         | 0.48%   |
| Unknown  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 157       | 75.85%  |
| 3.10    | 39        | 18.84%  |
| 5.14    | 6         | 2.9%    |
| 5.9     | 1         | 0.48%   |
| 5.13    | 1         | 0.48%   |
| 5.10    | 1         | 0.48%   |
| 4.19    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 205       | 99.51%  |
| Unknown | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 150       | 70.09%  |
| Unknown       | 44        | 20.56%  |
| GNOME Classic | 11        | 5.14%   |
| KDE5          | 5         | 2.34%   |
| KDE           | 2         | 0.93%   |
| MATE          | 1         | 0.47%   |
| Cinnamon      | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 114       | 53.52%  |
| Wayland | 71        | 33.33%  |
| Unknown | 28        | 13.15%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 166       | 77.93%  |
| GDM     | 46        | 21.6%   |
| LightDM | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 136       | 64.76%  |
| Unknown | 26        | 12.38%  |
| en_GB   | 10        | 4.76%   |
| ru_RU   | 4         | 1.9%    |
| pl_PL   | 4         | 1.9%    |
| fr_FR   | 4         | 1.9%    |
| en_IN   | 4         | 1.9%    |
| de_DE   | 4         | 1.9%    |
| pt_BR   | 2         | 0.95%   |
| nl_NL   | 2         | 0.95%   |
| es_ES   | 2         | 0.95%   |
| es_AR   | 2         | 0.95%   |
| en_IE   | 2         | 0.95%   |
| ko_KR   | 1         | 0.48%   |
| ja_JP   | 1         | 0.48%   |
| it_IT   | 1         | 0.48%   |
| es_MX   | 1         | 0.48%   |
| es_EC   | 1         | 0.48%   |
| en_NZ   | 1         | 0.48%   |
| de_CH   | 1         | 0.48%   |
| cs_CZ   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 145       | 68.72%  |
| BIOS | 66        | 31.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 171       | 81.82%  |
| Ext4    | 26        | 12.44%  |
| Unknown | 12        | 5.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 63.55%  |
| GPT     | 60        | 28.04%  |
| MBR     | 18        | 8.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 86.19%  |
| Yes       | 29        | 13.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 195       | 93.75%  |
| Yes       | 13        | 6.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 76        | 36.89%  |
| Dell                | 48        | 23.3%   |
| Hewlett-Packard     | 26        | 12.62%  |
| ASUSTek Computer    | 19        | 9.22%   |
| Gigabyte Technology | 8         | 3.88%   |
| ASRock              | 6         | 2.91%   |
| MSI                 | 4         | 1.94%   |
| Intel               | 3         | 1.46%   |
| ZTSYSTEMS           | 2         | 0.97%   |
| Supermicro          | 2         | 0.97%   |
| Sony                | 2         | 0.97%   |
| TUXEDO              | 1         | 0.49%   |
| Toshiba             | 1         | 0.49%   |
| Timi                | 1         | 0.49%   |
| Samsung Electronics | 1         | 0.49%   |
| MiTAC               | 1         | 0.49%   |
| CX / Air Computers. | 1         | 0.49%   |
| AMI                 | 1         | 0.49%   |
| Alienware           | 1         | 0.49%   |
| Acer                | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 2.91%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.94%   |
| Dell PowerEdge R230                      | 4         | 1.94%   |
| ASUS All Series                          | 4         | 1.94%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.97%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.97%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.97%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.97%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.97%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.97%   |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 0.97%   |
| HP Z620 Workstation                      | 2         | 0.97%   |
| HP EliteBook 8460p                       | 2         | 0.97%   |
| Dell PowerEdge R740                      | 2         | 0.97%   |
| Dell OptiPlex 9020                       | 2         | 0.97%   |
| Dell Latitude E6430                      | 2         | 0.97%   |
| Dell Latitude 5300                       | 2         | 0.97%   |
| ZTSYSTEMS Z802                           | 1         | 0.49%   |
| ZTSYSTEMS Z801                           | 1         | 0.49%   |
| TUXEDO N13xWU                            | 1         | 0.49%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.49%   |
| Timi TM1707                              | 1         | 0.49%   |
| Supermicro X7DW3                         | 1         | 0.49%   |
| Supermicro X10DRi                        | 1         | 0.49%   |
| Sony VPCEB4L1R                           | 1         | 0.49%   |
| Sony VPCEB23FM                           | 1         | 0.49%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.49%   |
| MSI MS-7B51                              | 1         | 0.49%   |
| MSI MS-7B33                              | 1         | 0.49%   |
| MSI MS-7A37                              | 1         | 0.49%   |
| MSI MS-7752                              | 1         | 0.49%   |
| MiTAC C4I                                | 1         | 0.49%   |
| Lenovo Z40-70 20366                      | 1         | 0.49%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.49%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.49%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.49%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.49%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.49%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.49%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.49%   |
| Lenovo ThinkPad X1 Yoga 1st 20FRS17K00   | 1         | 0.49%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.49%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.49%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.49%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.49%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.49%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.49%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.49%   |
| Lenovo ThinkPad T490 20N3S5DU27          | 1         | 0.49%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.49%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S29D02          | 1         | 0.49%   |
| Lenovo ThinkPad T470p 20J7S0FA0E         | 1         | 0.49%   |
| Lenovo ThinkPad T470 20HES57W00          | 1         | 0.49%   |
| Lenovo ThinkPad T460 20FMS1VA09          | 1         | 0.49%   |
| Lenovo ThinkPad T460 20BUS0QT0A          | 1         | 0.49%   |
| Lenovo ThinkPad T450s 20BWS0B500         | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 64        | 31.07%  |
| Dell PowerEdge      | 14        | 6.8%    |
| Dell Precision      | 12        | 5.83%   |
| Dell Latitude       | 10        | 4.85%   |
| HP ProLiant         | 5         | 2.43%   |
| HP EliteBook        | 4         | 1.94%   |
| ASUS All            | 4         | 1.94%   |
| Lenovo ThinkCentre  | 3         | 1.46%   |
| HP ZBook            | 3         | 1.46%   |
| Dell OptiPlex       | 3         | 1.46%   |
| Dell Inspiron       | 3         | 1.46%   |
| ASUS PRIME          | 3         | 1.46%   |
| Lenovo 7X56CTO1WW   | 2         | 0.97%   |
| HP Z620             | 2         | 0.97%   |
| HP Z230             | 2         | 0.97%   |
| Dell XPS            | 2         | 0.97%   |
| ASUS TUF            | 2         | 0.97%   |
| ASUS ROG            | 2         | 0.97%   |
| ZTSYSTEMS Z802      | 1         | 0.49%   |
| ZTSYSTEMS Z801      | 1         | 0.49%   |
| TUXEDO N13xWU       | 1         | 0.49%   |
| Toshiba Satellite   | 1         | 0.49%   |
| Timi TM1707         | 1         | 0.49%   |
| Supermicro X7DW3    | 1         | 0.49%   |
| Supermicro X10DRi   | 1         | 0.49%   |
| Sony VPCEB4L1R      | 1         | 0.49%   |
| Sony VPCEB23FM      | 1         | 0.49%   |
| Samsung 730QCJ      | 1         | 0.49%   |
| MSI MS-7B51         | 1         | 0.49%   |
| MSI MS-7B33         | 1         | 0.49%   |
| MSI MS-7A37         | 1         | 0.49%   |
| MSI MS-7752         | 1         | 0.49%   |
| MiTAC C4I           | 1         | 0.49%   |
| Lenovo Z40-70       | 1         | 0.49%   |
| Lenovo Yoga         | 1         | 0.49%   |
| Lenovo ThinkSystem  | 1         | 0.49%   |
| Lenovo ThinkBook    | 1         | 0.49%   |
| Lenovo S40-40       | 1         | 0.49%   |
| Lenovo Legion       | 1         | 0.49%   |
| Lenovo 10SFS03200   | 1         | 0.49%   |
| Intel NUC11BTMi7    | 1         | 0.49%   |
| Intel NUC10i7FNK    | 1         | 0.49%   |
| Intel DX79SR        | 1         | 0.49%   |
| HP Z840             | 1         | 0.49%   |
| HP Z440             | 1         | 0.49%   |
| HP ProBook          | 1         | 0.49%   |
| HP Pavilion         | 1         | 0.49%   |
| HP OMEN             | 1         | 0.49%   |
| HP ENVY             | 1         | 0.49%   |
| HP EliteDesk        | 1         | 0.49%   |
| HP 290              | 1         | 0.49%   |
| HP 260-P020il       | 1         | 0.49%   |
| HP 250              | 1         | 0.49%   |
| Gigabyte Z97N-WIFI  | 1         | 0.49%   |
| Gigabyte Z490       | 1         | 0.49%   |
| Gigabyte Z390       | 1         | 0.49%   |
| Gigabyte B85M-D3V-A | 1         | 0.49%   |
| Gigabyte B75-D3V    | 1         | 0.49%   |
| Gigabyte B150-HD3   | 1         | 0.49%   |
| Gigabyte AERO       | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 35        | 16.99%  |
| 2020 | 33        | 16.02%  |
| 2018 | 31        | 15.05%  |
| 2017 | 18        | 8.74%   |
| 2016 | 18        | 8.74%   |
| 2012 | 15        | 7.28%   |
| 2015 | 13        | 6.31%   |
| 2021 | 11        | 5.34%   |
| 2013 | 11        | 5.34%   |
| 2011 | 8         | 3.88%   |
| 2010 | 6         | 2.91%   |
| 2014 | 5         | 2.43%   |
| 2009 | 2         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 114       | 55.34%  |
| Desktop     | 64        | 31.07%  |
| Server      | 20        | 9.71%   |
| Mini pc     | 4         | 1.94%   |
| Convertible | 3         | 1.46%   |
| All in one  | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 186       | 89.42%  |
| Enabled  | 22        | 10.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 54        | 25.59%  |
| 64.01-256.0     | 34        | 16.11%  |
| 16.01-24.0      | 34        | 16.11%  |
| 4.01-8.0        | 33        | 15.64%  |
| 8.01-16.0       | 33        | 15.64%  |
| 24.01-32.0      | 9         | 4.27%   |
| 3.01-4.0        | 7         | 3.32%   |
| More than 256.0 | 5         | 2.37%   |
| 2.01-3.0        | 1         | 0.47%   |
| Unknown         | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 85        | 37.12%  |
| 2.01-3.0        | 41        | 17.9%   |
| 8.01-16.0       | 35        | 15.28%  |
| 3.01-4.0        | 32        | 13.97%  |
| 1.01-2.0        | 20        | 8.73%   |
| 24.01-32.0      | 4         | 1.75%   |
| 16.01-24.0      | 4         | 1.75%   |
| 0.51-1.0        | 3         | 1.31%   |
| 32.01-64.0      | 2         | 0.87%   |
| More than 256.0 | 1         | 0.44%   |
| 64.01-256.0     | 1         | 0.44%   |
| Unknown         | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 53.52%  |
| 2      | 44        | 20.66%  |
| 3      | 26        | 12.21%  |
| 5      | 9         | 4.23%   |
| 4      | 8         | 3.76%   |
| 12     | 3         | 1.41%   |
| 6      | 3         | 1.41%   |
| 8      | 2         | 0.94%   |
| 14     | 1         | 0.47%   |
| 11     | 1         | 0.47%   |
| 7      | 1         | 0.47%   |
| 0      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 79.33%  |
| Yes       | 43        | 20.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 91.3%   |
| No        | 18        | 8.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 71.36%  |
| No        | 59        | 28.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 56.4%   |
| No        | 92        | 43.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 53        | 25.73%  |
| India        | 16        | 7.77%   |
| Germany      | 15        | 7.28%   |
| UK           | 12        | 5.83%   |
| Czechia      | 12        | 5.83%   |
| Norway       | 7         | 3.4%    |
| France       | 6         | 2.91%   |
| Canada       | 6         | 2.91%   |
| Spain        | 5         | 2.43%   |
| Russia       | 4         | 1.94%   |
| Poland       | 4         | 1.94%   |
| Netherlands  | 4         | 1.94%   |
| Mexico       | 4         | 1.94%   |
| Italy        | 4         | 1.94%   |
| Switzerland  | 3         | 1.46%   |
| Lithuania    | 3         | 1.46%   |
| Brazil       | 3         | 1.46%   |
| Argentina    | 3         | 1.46%   |
| Ukraine      | 2         | 0.97%   |
| South Korea  | 2         | 0.97%   |
| South Africa | 2         | 0.97%   |
| Singapore    | 2         | 0.97%   |
| Romania      | 2         | 0.97%   |
| Japan        | 2         | 0.97%   |
| Egypt        | 2         | 0.97%   |
| Austria      | 2         | 0.97%   |
| Australia    | 2         | 0.97%   |
| Turkmenistan | 1         | 0.49%   |
| Turkey       | 1         | 0.49%   |
| Sweden       | 1         | 0.49%   |
| Saudi Arabia | 1         | 0.49%   |
| Portugal     | 1         | 0.49%   |
| Pakistan     | 1         | 0.49%   |
| New Zealand  | 1         | 0.49%   |
| Nepal        | 1         | 0.49%   |
| Myanmar      | 1         | 0.49%   |
| Morocco      | 1         | 0.49%   |
| Luxembourg   | 1         | 0.49%   |
| Kuwait       | 1         | 0.49%   |
| Israel       | 1         | 0.49%   |
| Ireland      | 1         | 0.49%   |
| Indonesia    | 1         | 0.49%   |
| Georgia      | 1         | 0.49%   |
| Ecuador      | 1         | 0.49%   |
| Colombia     | 1         | 0.49%   |
| China        | 1         | 0.49%   |
| Chile        | 1         | 0.49%   |
| Bulgaria     | 1         | 0.49%   |
| Belgium      | 1         | 0.49%   |
| Belarus      | 1         | 0.49%   |
| Armenia      | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Prague                   | 10        | 4.59%   |
| Quincy                   | 8         | 3.67%   |
| Langgons                 | 6         | 2.75%   |
| Tromsø                  | 4         | 1.83%   |
| San Jose                 | 3         | 1.38%   |
| Munich                   | 3         | 1.38%   |
| Milan                    | 3         | 1.38%   |
| Mexico City              | 3         | 1.38%   |
| Chicago                  | 3         | 1.38%   |
| Toronto                  | 2         | 0.92%   |
| Singapore                | 2         | 0.92%   |
| Oslo                     | 2         | 0.92%   |
| Montreal                 | 2         | 0.92%   |
| Madrid                   | 2         | 0.92%   |
| Kyiv                     | 2         | 0.92%   |
| Didcot                   | 2         | 0.92%   |
| Des Moines               | 2         | 0.92%   |
| Chennai                  | 2         | 0.92%   |
| Berlin                   | 2         | 0.92%   |
| Bengaluru                | 2         | 0.92%   |
| Zaragoza                 | 1         | 0.46%   |
| Yorktown Heights         | 1         | 0.46%   |
| Yongin-si                | 1         | 0.46%   |
| Wroclaw                  | 1         | 0.46%   |
| Wiesbaden                | 1         | 0.46%   |
| Webster                  | 1         | 0.46%   |
| Vienna                   | 1         | 0.46%   |
| Vardenis                 | 1         | 0.46%   |
| Vaglio                   | 1         | 0.46%   |
| Udaipur                  | 1         | 0.46%   |
| Tiruchi                  | 1         | 0.46%   |
| Temuco                   | 1         | 0.46%   |
| Temara                   | 1         | 0.46%   |
| Tauranga                 | 1         | 0.46%   |
| Taringa                  | 1         | 0.46%   |
| Talkha                   | 1         | 0.46%   |
| Syracuse                 | 1         | 0.46%   |
| Suffolk                  | 1         | 0.46%   |
| Streatham                | 1         | 0.46%   |
| Steamboat Springs        | 1         | 0.46%   |
| Stavropol                | 1         | 0.46%   |
| Spokane                  | 1         | 0.46%   |
| Sofia                    | 1         | 0.46%   |
| Skien                    | 1         | 0.46%   |
| Šilalė                 | 1         | 0.46%   |
| Šiauliai                | 1         | 0.46%   |
| Sheffield                | 1         | 0.46%   |
| Saratov                  | 1         | 0.46%   |
| San Francisco            | 1         | 0.46%   |
| San Fernando             | 1         | 0.46%   |
| Salzburg                 | 1         | 0.46%   |
| Salvador                 | 1         | 0.46%   |
| Saltillo                 | 1         | 0.46%   |
| Salt Lake City           | 1         | 0.46%   |
| Salisbury                | 1         | 0.46%   |
| Saint-Ismier             | 1         | 0.46%   |
| Saint-Alphonse-Rodriguez | 1         | 0.46%   |
| Saint Paul               | 1         | 0.46%   |
| Rosario                  | 1         | 0.46%   |
| Roha                     | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 86     | 16.77%  |
| WDC                 | 44        | 74     | 13.92%  |
| Seagate             | 43        | 86     | 13.61%  |
| Toshiba             | 29        | 42     | 9.18%   |
| Sandisk             | 18        | 27     | 5.7%    |
| SK Hynix            | 17        | 21     | 5.38%   |
| Intel               | 14        | 20     | 4.43%   |
| Kingston            | 13        | 17     | 4.11%   |
| Micron Technology   | 11        | 19     | 3.48%   |
| Unknown             | 8         | 10     | 2.53%   |
| Crucial             | 8         | 11     | 2.53%   |
| Phison              | 5         | 9      | 1.58%   |
| HGST                | 5         | 8      | 1.58%   |
| Dell                | 5         | 9      | 1.58%   |
| A-DATA Technology   | 5         | 5      | 1.58%   |
| Hitachi             | 4         | 4      | 1.27%   |
| PNY                 | 3         | 4      | 0.95%   |
| Hewlett-Packard     | 3         | 11     | 0.95%   |
| Corsair             | 3         | 6      | 0.95%   |
| Western Digital     | 2         | 2      | 0.63%   |
| Silicon Motion      | 2         | 3      | 0.63%   |
| Lenovo              | 2         | 2      | 0.63%   |
| XPG                 | 1         | 1      | 0.32%   |
| Transcend           | 1         | 1      | 0.32%   |
| Team                | 1         | 2      | 0.32%   |
| T-FORCE             | 1         | 2      | 0.32%   |
| SMI                 | 1         | 2      | 0.32%   |
| SCST_FIO            | 1         | 9      | 0.32%   |
| SABRENT             | 1         | 1      | 0.32%   |
| OCZ                 | 1         | 2      | 0.32%   |
| NVMe                | 1         | 1      | 0.32%   |
| Lite-On             | 1         | 1      | 0.32%   |
| KIOXIA              | 1         | 1      | 0.32%   |
| KingFast            | 1         | 1      | 0.32%   |
| KINGBANK            | 1         | 1      | 0.32%   |
| HPT                 | 1         | 1      | 0.32%   |
| Hoodisk             | 1         | 1      | 0.32%   |
| Gigabyte Technology | 1         | 1      | 0.32%   |
| DELLBOSS            | 1         | 1      | 0.32%   |
| China               | 1         | 1      | 0.32%   |
| Anobit              | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB        | 10        | 2.77%   |
| Samsung NVMe SSD Drive 512GB         | 8         | 2.22%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 6         | 1.66%   |
| Sandisk NVMe SSD Drive 256GB         | 6         | 1.66%   |
| Samsung SSD 860 EVO 1TB              | 5         | 1.39%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 1.39%   |
| Samsung NVMe SSD Drive 1024GB        | 5         | 1.39%   |
| Toshiba MG04ACA100NY 1TB             | 4         | 1.11%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 1.11%   |
| Intel NVMe SSD Drive 512GB           | 4         | 1.11%   |
| Dell MD34xx 26TB                     | 4         | 1.11%   |
| WDC WD5003ABYZ-011FA0 500GB          | 3         | 0.83%   |
| Toshiba NVMe SSD Drive 512GB         | 3         | 0.83%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.83%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.83%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.83%   |
| Micron NVMe SSD Drive 256GB          | 3         | 0.83%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.83%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.55%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2         | 0.55%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 0.55%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 0.55%   |
| Toshiba NVMe SSD Drive 1024GB        | 2         | 0.55%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.55%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2         | 0.55%   |
| SK Hynix NVMe SSD Drive 1024GB       | 2         | 0.55%   |
| Seagate ST91000640NS 1TB             | 2         | 0.55%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.55%   |
| Seagate ST4000NM0033-9ZM170 4TB      | 2         | 0.55%   |
| Seagate ST300MP0026 304GB            | 2         | 0.55%   |
| Seagate ST2000NX0433 2TB             | 2         | 0.55%   |
| Seagate ST2000NX0273 2TB             | 2         | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.55%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 0.55%   |
| Seagate Expansion 4TB                | 2         | 0.55%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.55%   |
| Sandisk NVMe SSD Drive 1TB           | 2         | 0.55%   |
| Samsung Portable SSD T5 500GB        | 2         | 0.55%   |
| Kingston SUV500120G 120GB SSD        | 2         | 0.55%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.55%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.55%   |
| Intel NVMe SSD Drive 2TB             | 2         | 0.55%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.55%   |
| Corsair Force LE SSD 240GB           | 2         | 0.55%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.28%   |
| Western Digital WUS3BA176C7P3E3 8TB  | 1         | 0.28%   |
| Western Digital NVMe SSD Drive 960GB | 1         | 0.28%   |
| WDC WDS400T2B0A-00SM50 4TB SSD       | 1         | 0.28%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1         | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.28%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1         | 0.28%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.28%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 0.28%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.28%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1         | 0.28%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1         | 0.28%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.28%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 85     | 37.72%  |
| WDC                 | 35        | 60     | 30.7%   |
| Toshiba             | 16        | 26     | 14.04%  |
| HGST                | 5         | 8      | 4.39%   |
| Hitachi             | 4         | 4      | 3.51%   |
| Dell                | 4         | 8      | 3.51%   |
| Hewlett-Packard     | 2         | 9      | 1.75%   |
| Unknown             | 1         | 1      | 0.88%   |
| SCST_FIO            | 1         | 9      | 0.88%   |
| Samsung Electronics | 1         | 2      | 0.88%   |
| SABRENT             | 1         | 1      | 0.88%   |
| DELLBOSS            | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 30     | 26.97%  |
| Kingston            | 11        | 15     | 12.36%  |
| Crucial             | 8         | 11     | 8.99%   |
| WDC                 | 7         | 9      | 7.87%   |
| Micron Technology   | 7         | 13     | 7.87%   |
| Sandisk             | 6         | 12     | 6.74%   |
| A-DATA Technology   | 5         | 5      | 5.62%   |
| SK Hynix            | 3         | 7      | 3.37%   |
| PNY                 | 3         | 4      | 3.37%   |
| Intel               | 3         | 4      | 3.37%   |
| Corsair             | 3         | 6      | 3.37%   |
| Transcend           | 1         | 1      | 1.12%   |
| Toshiba             | 1         | 1      | 1.12%   |
| Team                | 1         | 2      | 1.12%   |
| Seagate             | 1         | 1      | 1.12%   |
| OCZ                 | 1         | 2      | 1.12%   |
| KINGBANK            | 1         | 1      | 1.12%   |
| Hoodisk             | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| Anobit              | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 102       | 154    | 36.04%  |
| HDD     | 92        | 214    | 32.51%  |
| SSD     | 80        | 127    | 28.27%  |
| MMC     | 5         | 6      | 1.77%   |
| Unknown | 4         | 6      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 124       | 316    | 49.4%   |
| NVMe | 102       | 154    | 40.64%  |
| SAS  | 20        | 31     | 7.97%   |
| MMC  | 5         | 6      | 1.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 138    | 42.02%  |
| 0.51-1.0   | 57        | 90     | 30.32%  |
| 1.01-2.0   | 25        | 51     | 13.3%   |
| 3.01-4.0   | 14        | 34     | 7.45%   |
| 4.01-10.0  | 7         | 18     | 3.72%   |
| 20.01-50.0 | 4         | 8      | 2.13%   |
| 2.01-3.0   | 1         | 1      | 0.53%   |
| 10.01-20.0 | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 31.16%  |
| 251-500        | 37        | 17.21%  |
| 501-1000       | 35        | 16.28%  |
| More than 3000 | 18        | 8.37%   |
| 1001-2000      | 18        | 8.37%   |
| Unknown        | 15        | 6.98%   |
| 51-100         | 9         | 4.19%   |
| 2001-3000      | 7         | 3.26%   |
| 1-20           | 6         | 2.79%   |
| 21-50          | 3         | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 53        | 23.14%  |
| 21-50          | 47        | 20.52%  |
| 101-250        | 42        | 18.34%  |
| 51-100         | 29        | 12.66%  |
| 251-500        | 17        | 7.42%   |
| Unknown        | 15        | 6.55%   |
| 501-1000       | 11        | 4.8%    |
| 1001-2000      | 8         | 3.49%   |
| More than 3000 | 4         | 1.75%   |
| 2001-3000      | 3         | 1.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYZ-011FA0 500GB              | 1         | 1      | 10%     |
| WDC WD4000FYYZ-01UL1B1 4TB               | 1         | 3      | 10%     |
| WDC WD10EALX-759BA1 1TB                  | 1         | 2      | 10%     |
| Transcend TS512GMTS800 512GB SSD         | 1         | 1      | 10%     |
| Seagate ST91000640NS 1TB                 | 1         | 2      | 10%     |
| Seagate ST6000NM0024-1HT17Z 6TB          | 1         | 2      | 10%     |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1      | 10%     |
| Micron Technology M510_2.5 7MM 256GB SSD | 1         | 1      | 10%     |
| Hitachi HDS722020ALA330 2TB              | 1         | 1      | 10%     |
| A-DATA Technology SU800NS38 256GB SSD    | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 6      | 30%     |
| Seagate           | 3         | 5      | 30%     |
| Transcend         | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| Hitachi           | 1         | 1      | 10%     |
| A-DATA Technology | 1         | 1      | 10%     |

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
| HDD  | 6         | 12     | 66.67%  |
| SSD  | 3         | 3      | 33.33%  |

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
| Detected | 139       | 311    | 63.18%  |
| Works    | 72        | 181    | 32.73%  |
| Malfunc  | 9         | 15     | 4.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 47.52%  |
| Samsung Electronics          | 36        | 12.77%  |
| Sandisk                      | 15        | 5.32%   |
| SK Hynix                     | 14        | 4.96%   |
| Broadcom / LSI               | 13        | 4.61%   |
| AMD                          | 13        | 4.61%   |
| Toshiba America Info Systems | 12        | 4.26%   |
| LSI Logic / Symbios Logic    | 7         | 2.48%   |
| Phison Electronics           | 6         | 2.13%   |
| Micron Technology            | 4         | 1.42%   |
| Marvell Technology Group     | 4         | 1.42%   |
| Hewlett-Packard              | 4         | 1.42%   |
| ASMedia Technology           | 4         | 1.42%   |
| Silicon Motion               | 3         | 1.06%   |
| KIOXIA                       | 3         | 1.06%   |
| Western Digital              | 2         | 0.71%   |
| Lenovo                       | 2         | 0.71%   |
| Kingston Technology Company  | 2         | 0.71%   |
| Lite-On Technology           | 1         | 0.35%   |
| HighPoint Technologies       | 1         | 0.35%   |
| Biwin Storage Technology     | 1         | 0.35%   |
| ADATA Technology             | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 26        | 8.05%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 14        | 4.33%   |
| SK Hynix Non-Volatile memory controller                                          | 12        | 3.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 12        | 3.72%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 3.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 3.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 3.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 2.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.48%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 8         | 2.48%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.86%   |
| Intel SSD 660P Series                                                            | 5         | 1.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.55%   |
| Phison E12 NVMe Controller                                                       | 4         | 1.24%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.24%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                             | 4         | 1.24%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 1.24%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 4         | 1.24%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 1.24%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 4         | 1.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.24%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 4         | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.93%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.93%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.62%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.62%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.62%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.62%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.62%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.62%   |
| HP Smart Array Gen8 Controllers                                                  | 2         | 0.62%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 2         | 0.62%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                      | 1         | 0.31%   |
| Western Digital Ultrastar DC SN630 NVMe SSD                                      | 1         | 0.31%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.31%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.31%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 123       | 43.93%  |
| NVMe | 103       | 36.79%  |
| RAID | 37        | 13.21%  |
| SAS  | 10        | 3.57%   |
| IDE  | 7         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 189       | 91.75%  |
| AMD    | 17        | 8.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 4.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.37%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 7         | 3.4%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 2.43%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 4         | 1.94%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 1.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.94%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 3         | 1.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.46%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.46%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.46%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 2         | 0.97%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 0.97%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 2         | 0.97%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 0.97%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 0.97%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 2         | 0.97%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 0.97%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.97%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.97%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.97%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.97%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.97%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.49%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.49%   |
| Intel Xeon Gold 6263CY CPU @ 2.60GHz          | 1         | 0.49%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz            | 1         | 0.49%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.49%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.49%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.49%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.49%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.49%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.49%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.49%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.49%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.49%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz           | 1         | 0.49%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1         | 0.49%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 84        | 40.78%  |
| Intel Xeon         | 39        | 18.93%  |
| Intel Core i5      | 38        | 18.45%  |
| Intel Core i3      | 10        | 4.85%   |
| Other              | 7         | 3.4%    |
| AMD Ryzen 7        | 6         | 2.91%   |
| AMD Ryzen 9        | 3         | 1.46%   |
| Intel Xeon Silver  | 2         | 0.97%   |
| Intel Xeon Gold    | 2         | 0.97%   |
| Intel Pentium Gold | 2         | 0.97%   |
| Intel Pentium      | 2         | 0.97%   |
| Intel Core i9      | 2         | 0.97%   |
| AMD Ryzen 5        | 2         | 0.97%   |
| AMD Ryzen 3        | 2         | 0.97%   |
| AMD EPYC           | 2         | 0.97%   |
| Intel Core 2 Duo   | 1         | 0.49%   |
| AMD Ryzen 7 PRO    | 1         | 0.49%   |
| AMD FX             | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 86        | 41.75%  |
| 2      | 41        | 19.9%   |
| 6      | 32        | 15.53%  |
| 8      | 20        | 9.71%   |
| 12     | 9         | 4.37%   |
| 16     | 6         | 2.91%   |
| 20     | 4         | 1.94%   |
| 36     | 2         | 0.97%   |
| 24     | 2         | 0.97%   |
| 96     | 1         | 0.49%   |
| 64     | 1         | 0.49%   |
| 48     | 1         | 0.49%   |
| 32     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 180       | 87.38%  |
| 2      | 26        | 12.62%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 177       | 85.51%  |
| 1      | 30        | 14.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 198       | 95.19%  |
| Unknown        | 10        | 4.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 29        | 13.94%  |
| 0x906ea    | 15        | 7.21%   |
| 0x806ea    | 12        | 5.77%   |
| 0x306c3    | 12        | 5.77%   |
| Unknown    | 12        | 5.77%   |
| 0xa0652    | 11        | 5.29%   |
| 0x306a9    | 10        | 4.81%   |
| 0x506e3    | 9         | 4.33%   |
| 0x306f2    | 9         | 4.33%   |
| 0x206a7    | 9         | 4.33%   |
| 0x906ed    | 6         | 2.88%   |
| 0x906e9    | 6         | 2.88%   |
| 0x406e3    | 6         | 2.88%   |
| 0x806e9    | 5         | 2.4%    |
| 0x806d1    | 5         | 2.4%    |
| 0x406f1    | 5         | 2.4%    |
| 0x306e4    | 4         | 1.92%   |
| 0x206d7    | 4         | 1.92%   |
| 0x306d4    | 3         | 1.44%   |
| 0x206c2    | 3         | 1.44%   |
| 0x20655    | 3         | 1.44%   |
| 0x08108102 | 3         | 1.44%   |
| 0x806c1    | 2         | 0.96%   |
| 0x40651    | 2         | 0.96%   |
| 0x08701021 | 2         | 0.96%   |
| 0x08600103 | 2         | 0.96%   |
| 0xa0660    | 1         | 0.48%   |
| 0xa0655    | 1         | 0.48%   |
| 0x906eb    | 1         | 0.48%   |
| 0x90672    | 1         | 0.48%   |
| 0x50657    | 1         | 0.48%   |
| 0x50654    | 1         | 0.48%   |
| 0x20652    | 1         | 0.48%   |
| 0x1067a    | 1         | 0.48%   |
| 0x10676    | 1         | 0.48%   |
| 0x0a50000c | 1         | 0.48%   |
| 0x0a001119 | 1         | 0.48%   |
| 0x08701013 | 1         | 0.48%   |
| 0x08600106 | 1         | 0.48%   |
| 0x08600104 | 1         | 0.48%   |
| 0x08301034 | 1         | 0.48%   |
| 0x0810100b | 1         | 0.48%   |
| 0x08001138 | 1         | 0.48%   |
| 0x08001137 | 1         | 0.48%   |
| 0x06000852 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 75        | 36.23%  |
| Haswell          | 25        | 12.08%  |
| Skylake          | 23        | 11.11%  |
| IvyBridge        | 15        | 7.25%   |
| SandyBridge      | 13        | 6.28%   |
| CometLake        | 13        | 6.28%   |
| Zen 2            | 8         | 3.86%   |
| Broadwell        | 8         | 3.86%   |
| Westmere         | 7         | 3.38%   |
| Icelake          | 4         | 1.93%   |
| Zen+             | 3         | 1.45%   |
| Zen              | 3         | 1.45%   |
| Unknown          | 3         | 1.45%   |
| TigerLake        | 2         | 0.97%   |
| Penryn           | 2         | 0.97%   |
| Zen 3            | 1         | 0.48%   |
| Piledriver       | 1         | 0.48%   |
| Alderlake Hybrid | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 125       | 50%     |
| Nvidia                     | 74        | 29.6%   |
| AMD                        | 25        | 10%     |
| Matrox Electronics Systems | 19        | 7.6%    |
| ASPEED Technology          | 7         | 2.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 17        | 6.72%   |
| Intel UHD Graphics 620                                                      | 12        | 4.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 12        | 4.74%   |
| Matrox Electronics Systems G200eR2                                          | 11        | 4.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 10        | 3.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.77%   |
| ASPEED Technology ASPEED Graphics Family                                    | 7         | 2.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.98%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 1.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 1.58%   |
| Intel HD Graphics 630                                                       | 4         | 1.58%   |
| Intel HD Graphics 620                                                       | 4         | 1.58%   |
| Intel HD Graphics 530                                                       | 4         | 1.58%   |
| AMD Renoir                                                                  | 4         | 1.58%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.19%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 1.19%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 1.19%   |
| Intel HD Graphics 5500                                                      | 3         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.19%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.79%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.79%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.79%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 2         | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.79%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2         | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 0.79%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 0.79%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.4%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.4%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.4%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.4%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.4%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.4%    |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                            | 1         | 0.4%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.4%    |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.4%    |
| Nvidia GP107GL [Quadro P600]                                                | 1         | 0.4%    |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 0.4%    |
| Nvidia GP106GL [Quadro P2200]                                               | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 86        | 41.35%  |
| 1 x Nvidia      | 41        | 19.71%  |
| Intel + Nvidia  | 27        | 12.98%  |
| 1 x Matrox      | 18        | 8.65%   |
| 1 x AMD         | 14        | 6.73%   |
| Intel + AMD     | 7         | 3.37%   |
| 1 x ASPEED      | 6         | 2.88%   |
| AMD + Nvidia    | 3         | 1.44%   |
| 2 x Nvidia      | 2         | 0.96%   |
| Other           | 1         | 0.48%   |
| 2 x AMD         | 1         | 0.48%   |
| Nvidia + Matrox | 1         | 0.48%   |
| Nvidia + ASPEED | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 159       | 76.08%  |
| Proprietary | 31        | 14.83%  |
| Unknown     | 19        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 63.21%  |
| 1.01-2.0   | 22        | 10.38%  |
| 3.01-4.0   | 15        | 7.08%   |
| 0.51-1.0   | 11        | 5.19%   |
| 7.01-8.0   | 8         | 3.77%   |
| 5.01-6.0   | 8         | 3.77%   |
| 0.01-0.5   | 7         | 3.3%    |
| 2.01-3.0   | 3         | 1.42%   |
| 8.01-16.0  | 2         | 0.94%   |
| 4.01-5.0   | 1         | 0.47%   |
| 16.01-24.0 | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 30        | 12.5%   |
| AU Optronics            | 26        | 10.83%  |
| Samsung Electronics     | 25        | 10.42%  |
| BOE                     | 21        | 8.75%   |
| Lenovo                  | 19        | 7.92%   |
| LG Display              | 18        | 7.5%    |
| Chimei Innolux          | 17        | 7.08%   |
| Goldstar                | 16        | 6.67%   |
| Hewlett-Packard         | 11        | 4.58%   |
| Sharp                   | 7         | 2.92%   |
| InfoVision              | 5         | 2.08%   |
| Acer                    | 5         | 2.08%   |
| Philips                 | 4         | 1.67%   |
| Eizo                    | 4         | 1.67%   |
| BenQ                    | 4         | 1.67%   |
| Ancor Communications    | 3         | 1.25%   |
| ViewSonic               | 2         | 0.83%   |
| PANDA                   | 2         | 0.83%   |
| LGD                     | 2         | 0.83%   |
| Lenovo Group Limited    | 2         | 0.83%   |
| Iiyama                  | 2         | 0.83%   |
| Gigabyte Technology     | 2         | 0.83%   |
| BOE Technology Group    | 2         | 0.83%   |
| AOC                     | 2         | 0.83%   |
| Sun                     | 1         | 0.42%   |
| Sceptre Tech            | 1         | 0.42%   |
| Planar                  | 1         | 0.42%   |
| LG Electronics          | 1         | 0.42%   |
| ITE                     | 1         | 0.42%   |
| Insignia                | 1         | 0.42%   |
| Chi Mei Optoelectronics | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |
| Unknown                 | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell IDRAC DEL0001 1280x1024                                           | 6         | 2.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 6         | 2.31%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 4         | 1.54%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 4         | 1.54%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 4         | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 1.15%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch           | 3         | 1.15%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 3         | 1.15%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 3         | 1.15%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 3         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 1.15%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                  | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x173mm 13.9-inch         | 3         | 1.15%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 2         | 0.77%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                | 2         | 0.77%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| LGD LCD Monitor 1920x1080                                              | 2         | 0.77%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 2         | 0.77%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2         | 0.77%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 2         | 0.77%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2         | 0.77%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch             | 2         | 0.77%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.77%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch       | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch        | 2         | 0.77%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                  | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch         | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch          | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.77%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1         | 0.38%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1         | 0.38%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                      | 1         | 0.38%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 0.38%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch         | 1         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 1         | 0.38%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch      | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1         | 0.38%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch      | 1         | 0.38%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1         | 0.38%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1         | 0.38%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch      | 1         | 0.38%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch  | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 52.53%  |
| 3840x2160 (4K)     | 18        | 8.29%   |
| 1366x768 (WXGA)    | 16        | 7.37%   |
| 2560x1440 (QHD)    | 14        | 6.45%   |
| 1600x900 (HD+)     | 11        | 5.07%   |
| 1920x1200 (WUXGA)  | 7         | 3.23%   |
| 2560x1080          | 6         | 2.76%   |
| 1280x1024 (SXGA)   | 6         | 2.76%   |
| Unknown            | 5         | 2.3%    |
| 3840x1080          | 4         | 1.84%   |
| 3440x1440          | 4         | 1.84%   |
| 1680x1050 (WSXGA+) | 3         | 1.38%   |
| 1440x900 (WXGA+)   | 2         | 0.92%   |
| 9600x2160          | 1         | 0.46%   |
| 7680x2160          | 1         | 0.46%   |
| 6400x2160          | 1         | 0.46%   |
| 3840x1200          | 1         | 0.46%   |
| 2048x1152          | 1         | 0.46%   |
| 1280x800 (WXGA)    | 1         | 0.46%   |
| 1280x720 (HD)      | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 18.93%  |
| 14      | 30        | 12.35%  |
| 24      | 25        | 10.29%  |
| 27      | 24        | 9.88%   |
| 13      | 21        | 8.64%   |
| 23      | 20        | 8.23%   |
| Unknown | 20        | 8.23%   |
| 21      | 11        | 4.53%   |
| 34      | 7         | 2.88%   |
| 31      | 6         | 2.47%   |
| 12      | 5         | 2.06%   |
| 20      | 4         | 1.65%   |
| 17      | 4         | 1.65%   |
| 54      | 3         | 1.23%   |
| 47      | 2         | 0.82%   |
| 32      | 2         | 0.82%   |
| 22      | 2         | 0.82%   |
| 18      | 2         | 0.82%   |
| 72      | 1         | 0.41%   |
| 64      | 1         | 0.41%   |
| 49      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 39      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| 11      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 38.3%   |
| 501-600     | 60        | 25.53%  |
| Unknown     | 20        | 8.51%   |
| 401-500     | 19        | 8.09%   |
| 201-300     | 13        | 5.53%   |
| 601-700     | 10        | 4.26%   |
| 701-800     | 9         | 3.83%   |
| 1001-1500   | 7         | 2.98%   |
| 351-400     | 4         | 1.7%    |
| 801-900     | 2         | 0.85%   |
| 1501-2000   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 77.44%  |
| 16/10   | 16        | 8.21%   |
| Unknown | 12        | 6.15%   |
| 21/9    | 8         | 4.1%    |
| 5/4     | 6         | 3.08%   |
| 32/9    | 1         | 0.51%   |
| 3/2     | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 19.33%  |
| 81-90          | 44        | 18.49%  |
| 201-250        | 44        | 18.49%  |
| 301-350        | 24        | 10.08%  |
| Unknown        | 20        | 8.4%    |
| 351-500        | 14        | 5.88%   |
| 251-300        | 12        | 5.04%   |
| 71-80          | 7         | 2.94%   |
| 151-200        | 6         | 2.52%   |
| More than 1000 | 5         | 2.1%    |
| 61-70          | 5         | 2.1%    |
| 501-1000       | 5         | 2.1%    |
| 121-130        | 4         | 1.68%   |
| 51-60          | 1         | 0.42%   |
| 141-150        | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 37.07%  |
| 51-100        | 71        | 30.6%   |
| 101-120       | 32        | 13.79%  |
| Unknown       | 20        | 8.62%   |
| 161-240       | 13        | 5.6%    |
| More than 240 | 5         | 2.16%   |
| 1-50          | 5         | 2.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 132       | 60.83%  |
| 2     | 48        | 22.12%  |
| 0     | 23        | 10.6%   |
| 3     | 14        | 6.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 162       | 52.77%  |
| Realtek Semiconductor             | 59        | 19.22%  |
| Broadcom                          | 19        | 6.19%   |
| Lenovo                            | 15        | 4.89%   |
| Qualcomm Atheros                  | 12        | 3.91%   |
| Dell                              | 5         | 1.63%   |
| Broadcom Limited                  | 4         | 1.3%    |
| Sierra Wireless                   | 2         | 0.65%   |
| Ralink Technology                 | 2         | 0.65%   |
| Ralink                            | 2         | 0.65%   |
| Marvell Technology Group          | 2         | 0.65%   |
| Huawei Technologies               | 2         | 0.65%   |
| Ericsson Business Mobile Networks | 2         | 0.65%   |
| ASIX Electronics                  | 2         | 0.65%   |
| Xiaomi                            | 1         | 0.33%   |
| Samsung Electronics               | 1         | 0.33%   |
| Qualcomm Atheros Communications   | 1         | 0.33%   |
| QLogic                            | 1         | 0.33%   |
| Prolific Technology               | 1         | 0.33%   |
| Microchip Technology              | 1         | 0.33%   |
| Micro Star International          | 1         | 0.33%   |
| Mellanox Technologies             | 1         | 0.33%   |
| MediaTek                          | 1         | 0.33%   |
| Luminary Micro                    | 1         | 0.33%   |
| ICS Advent                        | 1         | 0.33%   |
| IBM                               | 1         | 0.33%   |
| Emulex                            | 1         | 0.33%   |
| DisplayLink                       | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| Arduino SA                        | 1         | 0.33%   |
| Aquantia                          | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 38        | 9.2%    |
| Intel Wireless 8265 / 8275                                                     | 16        | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 3.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 15        | 3.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 13        | 3.15%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11        | 2.66%   |
| Intel Wi-Fi 6 AX200                                                            | 10        | 2.42%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 2.42%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 2.18%   |
| Intel Wireless 8260                                                            | 9         | 2.18%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 2.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 2.18%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 1.94%   |
| Intel I350 Gigabit Network Connection                                          | 8         | 1.94%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 1.45%   |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.45%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.45%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.21%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 0.97%   |
| Intel Wireless-AC 9260                                                         | 4         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.97%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 0.97%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 0.97%   |
| Intel Wireless 7265                                                            | 3         | 0.73%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.73%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.73%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.73%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.48%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.48%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.48%   |
| Intel Wireless 7260                                                            | 2         | 0.48%   |
| Intel Wireless 3165                                                            | 2         | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.48%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.48%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.48%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.48%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.48%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.48%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.48%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.48%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.48%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 73.2%   |
| Realtek Semiconductor           | 12        | 7.84%   |
| Qualcomm Atheros                | 11        | 7.19%   |
| Broadcom                        | 5         | 3.27%   |
| Sierra Wireless                 | 2         | 1.31%   |
| Ralink Technology               | 2         | 1.31%   |
| Ralink                          | 2         | 1.31%   |
| Dell                            | 2         | 1.31%   |
| Qualcomm Atheros Communications | 1         | 0.65%   |
| Micro Star International        | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| D-Link                          | 1         | 0.65%   |
| Broadcom Limited                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 16        | 10.46%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 15        | 9.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 13        | 8.5%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 11        | 7.19%   |
| Intel Wi-Fi 6 AX200                                                        | 10        | 6.54%   |
| Intel Wireless 8260                                                        | 9         | 5.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.61%   |
| Intel Wireless-AC 9260                                                     | 4         | 2.61%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 2.61%   |
| Intel Wireless 7265                                                        | 3         | 1.96%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.31%   |
| Intel Wireless 7260                                                        | 2         | 1.31%   |
| Intel Wireless 3165                                                        | 2         | 1.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 1.31%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.31%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 2         | 1.31%   |
| Sierra Wireless EM7455                                                     | 1         | 0.65%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.65%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.65%   |
| Ralink RT5372 Wireless Adapter                                             | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.65%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.65%   |
| MediaTek Wireless                                                          | 1         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1         | 0.65%   |
| D-Link 802.11n WLAN Adapter                                                | 1         | 0.65%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 126       | 56%     |
| Realtek Semiconductor    | 51        | 22.67%  |
| Lenovo                   | 15        | 6.67%   |
| Broadcom                 | 14        | 6.22%   |
| Broadcom Limited         | 3         | 1.33%   |
| Qualcomm Atheros         | 2         | 0.89%   |
| Marvell Technology Group | 2         | 0.89%   |
| ASIX Electronics         | 2         | 0.89%   |
| Xiaomi                   | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| QLogic                   | 1         | 0.44%   |
| Mellanox Technologies    | 1         | 0.44%   |
| ICS Advent               | 1         | 0.44%   |
| IBM                      | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |
| Emulex                   | 1         | 0.44%   |
| DisplayLink              | 1         | 0.44%   |
| Aquantia                 | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 38        | 15.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.4%    |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4%      |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 3.6%    |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 3.6%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 3.2%    |
| Intel I350 Gigabit Network Connection                                          | 8         | 3.2%    |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.8%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.8%    |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 2.4%    |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 2.4%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 2.4%    |
| Intel Ethernet Connection I217-LM                                              | 5         | 2%      |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 2%      |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.6%    |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.6%    |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.6%    |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.6%    |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.2%    |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.8%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.8%    |
| Lenovo USB-C to LAN                                                            | 2         | 0.8%    |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.8%    |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.8%    |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.8%    |
| Intel Ethernet Controller X550                                                 | 2         | 0.8%    |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.8%    |
| Intel Ethernet Connection I217-V                                               | 2         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.8%    |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.8%    |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.8%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.8%    |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.8%    |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.8%    |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.4%    |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 0.4%    |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                        | 1         | 0.4%    |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.4%    |
| Lenovo ThinkPad Lan                                                            | 1         | 0.4%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.4%    |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.4%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.4%    |
| Intel Ethernet Controller I225-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.4%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.4%    |
| Intel DH8900CC Series Gigabit Network Connection                               | 1         | 0.4%    |
| Intel DH8900CC Series Gigabit Backplane Network Connection                     | 1         | 0.4%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 54.62%  |
| WiFi     | 147       | 42.49%  |
| Modem    | 7         | 2.02%   |
| Unknown  | 3         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 53.67%  |
| WiFi     | 100       | 45.87%  |
| Unknown  | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 116       | 56.04%  |
| 1     | 58        | 28.02%  |
| 3     | 11        | 5.31%   |
| 4     | 10        | 4.83%   |
| 6     | 7         | 3.38%   |
| 132   | 1         | 0.48%   |
| 22    | 1         | 0.48%   |
| 12    | 1         | 0.48%   |
| 8     | 1         | 0.48%   |
| 5     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 90.38%  |
| Yes  | 20        | 9.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 72.27%  |
| Cambridge Silicon Radio         | 8         | 6.72%   |
| Broadcom                        | 6         | 5.04%   |
| Realtek Semiconductor           | 4         | 3.36%   |
| Qualcomm Atheros Communications | 4         | 3.36%   |
| IMC Networks                    | 4         | 3.36%   |
| ASUSTek Computer                | 3         | 2.52%   |
| Ralink                          | 1         | 0.84%   |
| Micro Star International        | 1         | 0.84%   |
| Foxconn / Hon Hai               | 1         | 0.84%   |
| Dell                            | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 26        | 21.85%  |
| Intel Bluetooth wireless interface                                                  | 25        | 21.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 17.65%  |
| Intel AX200 Bluetooth                                                               | 9         | 7.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 6.72%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.52%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.68%   |
| ASUS BCM20702A0                                                                     | 2         | 1.68%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.84%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.84%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.84%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.84%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.84%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.84%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.84%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.84%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 160       | 54.42%  |
| Nvidia                    | 55        | 18.71%  |
| AMD                       | 23        | 7.82%   |
| Lenovo                    | 16        | 5.44%   |
| Realtek Semiconductor     | 4         | 1.36%   |
| Plantronics               | 4         | 1.36%   |
| Texas Instruments         | 3         | 1.02%   |
| JMTek                     | 3         | 1.02%   |
| GN Netcom                 | 3         | 1.02%   |
| Generalplus Technology    | 3         | 1.02%   |
| Creative Labs             | 3         | 1.02%   |
| Logitech                  | 2         | 0.68%   |
| Creative Technology       | 2         | 0.68%   |
| C-Media Electronics       | 2         | 0.68%   |
| Tenx Technology           | 1         | 0.34%   |
| Sony                      | 1         | 0.34%   |
| Sennheiser Communications | 1         | 0.34%   |
| RODE Microphones          | 1         | 0.34%   |
| LG Electronics            | 1         | 0.34%   |
| Google                    | 1         | 0.34%   |
| Focusrite-Novation        | 1         | 0.34%   |
| DYNEX                     | 1         | 0.34%   |
| Dell                      | 1         | 0.34%   |
| Corsair                   | 1         | 0.34%   |
| ASUSTek Computer          | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 23        | 7.28%   |
| Intel Cannon Lake PCH cAVS                                                        | 19        | 6.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 18        | 5.7%    |
| Intel Comet Lake PCH-LP cAVS                                                      | 13        | 4.11%   |
| Intel Comet Lake PCH cAVS                                                         | 12        | 3.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10        | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 10        | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9         | 2.85%   |
| AMD Family 17h/19h HD Audio Controller                                            | 9         | 2.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 2.22%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6         | 1.9%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6         | 1.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 1.58%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5         | 1.58%   |
| Realtek Semiconductor USB Audio                                                   | 4         | 1.27%   |
| Plantronics BT600                                                                 | 4         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.27%   |
| Nvidia Audio device                                                               | 4         | 1.27%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 4         | 1.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 1.27%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3         | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 0.95%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 0.95%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 0.95%   |
| Intel 200 Series PCH HD Audio                                                     | 3         | 0.95%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.63%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 0.63%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.63%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.63%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.63%   |
| Generalplus Technology Usb Audio Device                                           | 2         | 0.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.63%   |
| Tenx Technology USB AUDIO                                                         | 1         | 0.32%   |
| Sony Wireless Controller                                                          | 1         | 0.32%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                         | 1         | 0.32%   |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.32%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.32%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.32%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.32%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.32%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.32%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 0.32%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.32%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 29.81%  |
| SK Hynix            | 29        | 27.88%  |
| Micron Technology   | 12        | 11.54%  |
| Crucial             | 9         | 8.65%   |
| Kingston            | 6         | 5.77%   |
| Unknown             | 4         | 3.85%   |
| Corsair             | 4         | 3.85%   |
| Hewlett-Packard     | 2         | 1.92%   |
| Unknown (0x0205)    | 1         | 0.96%   |
| Transcend           | 1         | 0.96%   |
| Smart               | 1         | 0.96%   |
| Patriot             | 1         | 0.96%   |
| GOODRAM             | 1         | 0.96%   |
| Elpida              | 1         | 0.96%   |
| Unknown             | 1         | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 4         | 3.6%    |
| SK Hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s      | 3         | 2.7%    |
| SK Hynix RAM HMA42GR7MFR4N-TF 16384MB DIMM DDR4 2133MT/s     | 3         | 2.7%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 2         | 1.8%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.8%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.8%    |
| SK Hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s     | 2         | 1.8%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 1.8%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s    | 2         | 1.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.8%    |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s         | 2         | 1.8%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 2         | 1.8%    |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s         | 2         | 1.8%    |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s         | 2         | 1.8%    |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 2         | 1.8%    |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s   | 1         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.9%    |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s           | 1         | 0.9%    |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s             | 1         | 0.9%    |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.9%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 1         | 0.9%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s         | 1         | 0.9%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 0.9%    |
| SK Hynix RAM HMA84GR7CJR4N-WM 32GB DIMM DDR4 2933MT/s        | 1         | 0.9%    |
| SK Hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 0.9%    |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 0.9%    |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                    | 1         | 0.9%    |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.9%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 0.9%    |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                   | 1         | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.9%    |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 0.9%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 0.9%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 0.9%    |
| Samsung RAM M393B5173FHD-CF8 4096MB DIMM 1066MT/s            | 1         | 0.9%    |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 1         | 0.9%    |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1         | 0.9%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1         | 0.9%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s          | 1         | 0.9%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s          | 1         | 0.9%    |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s       | 1         | 0.9%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.9%    |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.9%    |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s             | 1         | 0.9%    |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 0.9%    |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s          | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 54        | 61.36%  |
| DDR3    | 24        | 27.27%  |
| SDRAM   | 3         | 3.41%   |
| LPDDR3  | 2         | 2.27%   |
| DRAM    | 2         | 2.27%   |
| LPDDR4  | 1         | 1.14%   |
| DDR2    | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 49        | 56.32%  |
| SODIMM       | 34        | 39.08%  |
| RIMM         | 2         | 2.3%    |
| Row Of Chips | 1         | 1.15%   |
| Chip         | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 34.07%  |
| 16384 | 27        | 29.67%  |
| 4096  | 21        | 23.08%  |
| 32768 | 8         | 8.79%   |
| 2048  | 2         | 2.2%    |
| 65536 | 1         | 1.1%    |
| 1024  | 1         | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 19.35%  |
| 2400  | 16        | 17.2%   |
| 2667  | 14        | 15.05%  |
| 3200  | 12        | 12.9%   |
| 2133  | 11        | 11.83%  |
| 1333  | 7         | 7.53%   |
| 2666  | 4         | 4.3%    |
| 3600  | 2         | 2.15%   |
| 2933  | 2         | 2.15%   |
| 3266  | 1         | 1.08%   |
| 2048  | 1         | 1.08%   |
| 1867  | 1         | 1.08%   |
| 1866  | 1         | 1.08%   |
| 1334  | 1         | 1.08%   |
| 1066  | 1         | 1.08%   |
| 800   | 1         | 1.08%   |

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
| Canon LiDE 300                     | 1         | 16.67%  |
| Canon E560 series                  | 1         | 16.67%  |
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
| Chicony Electronics                    | 37        | 27.82%  |
| IMC Networks                           | 19        | 14.29%  |
| Acer                                   | 14        | 10.53%  |
| Realtek Semiconductor                  | 10        | 7.52%   |
| Logitech                               | 10        | 7.52%   |
| Microdia                               | 9         | 6.77%   |
| Sunplus Innovation Technology          | 6         | 4.51%   |
| Unknown                                | 5         | 3.76%   |
| Suyin                                  | 3         | 2.26%   |
| Samsung Electronics                    | 3         | 2.26%   |
| Lite-On Technology                     | 3         | 2.26%   |
| Syntek                                 | 2         | 1.5%    |
| Microsoft                              | 2         | 1.5%    |
| Generalplus Technology                 | 2         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.5%    |
| Ruision                                | 1         | 0.75%   |
| Quanta                                 | 1         | 0.75%   |
| LG Electronics                         | 1         | 0.75%   |
| Lenovo                                 | 1         | 0.75%   |
| Jieli Technology                       | 1         | 0.75%   |
| ARC International                      | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 19        | 13.97%  |
| IMC Networks Integrated Camera                               | 16        | 11.76%  |
| Realtek Integrated_Webcam_HD                                 | 8         | 5.88%   |
| Acer Integrated Camera                                       | 7         | 5.15%   |
| Unknown FULL HD 1080P Webcam                                 | 4         | 2.94%   |
| Logitech HD Pro Webcam C920                                  | 4         | 2.94%   |
| Chicony Integrated Camera (1280x720@30)                      | 4         | 2.94%   |
| Chicony HP HD Camera                                         | 4         | 2.94%   |
| Acer SunplusIT Integrated Camera                             | 4         | 2.94%   |
| Sunplus Integrated_Webcam_HD                                 | 3         | 2.21%   |
| Samsung Galaxy A5 (MTP)                                      | 3         | 2.21%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.21%   |
| Lite-On Integrated Camera                                    | 3         | 2.21%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 2.21%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.21%   |
| Microdia Webcam                                              | 2         | 1.47%   |
| Microdia Integrated Webcam                                   | 2         | 1.47%   |
| Generalplus CAMERA - UVC                                     | 2         | 1.47%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.47%   |
| Acer Integrated IR Camera                                    | 2         | 1.47%   |
| Unknown 720p HD Camera                                       | 1         | 0.74%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.74%   |
| Syntek Integrated Camera                                     | 1         | 0.74%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.74%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.74%   |
| Suyin HP Truevision HD                                       | 1         | 0.74%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.74%   |
| Sunplus Integrated Webcam                                    | 1         | 0.74%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.74%   |
| Ruision UVC Camera                                           | 1         | 0.74%   |
| Realtek WEB CAMERA M9 Pro                                    | 1         | 0.74%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.74%   |
| Quanta HP HD Camera                                          | 1         | 0.74%   |
| Microsoft LifeCam HD-3000                                    | 1         | 0.74%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.74%   |
| Logitech Webcam C925e                                        | 1         | 0.74%   |
| Logitech Webcam C310                                         | 1         | 0.74%   |
| Logitech Webcam C270                                         | 1         | 0.74%   |
| Logitech Webcam C250                                         | 1         | 0.74%   |
| Logitech HD Webcam C910                                      | 1         | 0.74%   |
| Logitech B525 HD Webcam                                      | 1         | 0.74%   |
| LG LG UltraFine Display Camera                               | 1         | 0.74%   |
| Lenovo Integrated Webcam                                     | 1         | 0.74%   |
| Jieli USB PHY 2.0                                            | 1         | 0.74%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.74%   |
| Chicony Integrated IR Camera                                 | 1         | 0.74%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.74%   |
| Chicony HP Webcam                                            | 1         | 0.74%   |
| Chicony HD User Facing                                       | 1         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.74%   |
| ARC International Camera                                     | 1         | 0.74%   |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 0.74%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.74%   |
| Acer Lenovo Integrated Webcam                                | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 31        | 58.49%  |
| Validity Sensors           | 15        | 28.3%   |
| Shenzhen Goodix Technology | 3         | 5.66%   |
| Upek                       | 2         | 3.77%   |
| Samsung Electronics        | 1         | 1.89%   |
| Elan Microelectronics      | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 41.51%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.32%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 7.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.89%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.89%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.89%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.89%   |

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
| 0     | 100       | 47.62%  |
| 1     | 74        | 35.24%  |
| 2     | 22        | 10.48%  |
| 3     | 10        | 4.76%   |
| 5     | 3         | 1.43%   |
| 4     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 33.76%  |
| Graphics card            | 28        | 17.83%  |
| Unassigned class         | 21        | 13.38%  |
| Communication controller | 18        | 11.46%  |
| Chipcard                 | 11        | 7.01%   |
| Net/wireless             | 8         | 5.1%    |
| Card reader              | 4         | 2.55%   |
| Multimedia controller    | 3         | 1.91%   |
| Bluetooth                | 3         | 1.91%   |
| Net/ethernet             | 2         | 1.27%   |
| Storage/raid             | 1         | 0.64%   |
| Storage/ide              | 1         | 0.64%   |
| Storage                  | 1         | 0.64%   |
| Sound                    | 1         | 0.64%   |
| Network                  | 1         | 0.64%   |
| Camera                   | 1         | 0.64%   |

