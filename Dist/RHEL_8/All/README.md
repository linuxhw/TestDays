RHEL 8 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_8/Desktop/README.md) and [notebooks](/Dist/RHEL_8/Notebook/README.md).

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

Total: 303

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d5d888506b](https://linux-hardware.org/?probe=d5d888506b) | Aug 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [daa3df0f31](https://linux-hardware.org/?probe=daa3df0f31) | Jun 19, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [cc243873e2](https://linux-hardware.org/?probe=cc243873e2) | Mar 26, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [2e55d2163a](https://linux-hardware.org/?probe=2e55d2163a) | Mar 26, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [52e2d79bad](https://linux-hardware.org/?probe=52e2d79bad) | Mar 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac         | S410G4                      | Notebook    | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | Notebook    | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f1ac9526c5](https://linux-hardware.org/?probe=f1ac9526c5) | Dec 08, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ae85dba67e](https://linux-hardware.org/?probe=ae85dba67e) | Nov 28, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo        | Unknown                     | Convertible | [b4fb099c2f](https://linux-hardware.org/?probe=b4fb099c2f) | Nov 11, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| AZW           | SER V01                     | Mini pc     | [7bb271252d](https://linux-hardware.org/?probe=7bb271252d) | Oct 17, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Supermicro    | X10DRi                      | Server      | [0cf218f7bf](https://linux-hardware.org/?probe=0cf218f7bf) | Jun 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f08ef13508](https://linux-hardware.org/?probe=f08ef13508) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | Precision 5550              | Notebook    | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Precision 7560              | Notebook    | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
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
| Lenovo        | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| Dell          | Precision 3551              | Notebook    | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
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
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Dell          | 074H08 A00                  | Server      | [b7ac531bf5](https://linux-hardware.org/?probe=b7ac531bf5) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| HP            | 8054                        | Desktop     | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| Lenovo        | 7D2XCTO1WW                  | Server      | [2175466ea1](https://linux-hardware.org/?probe=2175466ea1) | Apr 25, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [23f12250e5](https://linux-hardware.org/?probe=23f12250e5) | Apr 22, 2021 |
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
| Sony          | VPCEB4L1R                   | Notebook    | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [29d0e20ba4](https://linux-hardware.org/?probe=29d0e20ba4) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
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
| Dell          | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
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
| HP            | ProBook 430 G5              | Notebook    | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| HP            | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
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
| HP            | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
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

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 14        | 6.25%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 6.25%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 12        | 5.36%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 4.91%   |
| 4.18.0-305.el8.x86_64        | 10        | 4.46%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 4.02%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 9         | 4.02%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 9         | 4.02%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 3.57%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 8         | 3.57%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 7         | 3.13%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 7         | 3.13%   |
| 4.18.0-425.3.1.el8.x86_64    | 6         | 2.68%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 6         | 2.68%   |
| 4.18.0-193.el8.x86_64        | 6         | 2.68%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 6         | 2.68%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 2.68%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6         | 2.68%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 2.23%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 2.23%   |
| 4.18.0-372.9.1.el8.x86_64    | 4         | 1.79%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4         | 1.79%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 1.79%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4         | 1.79%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 1.79%   |
| 4.18.0-147.el8.x86_64        | 4         | 1.79%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 1.34%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 2         | 0.89%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 0.89%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 2         | 0.89%   |
| 4.18.0-348.el8.x86_64        | 2         | 0.89%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 2         | 0.89%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 2         | 0.89%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 0.89%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 2         | 0.89%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.45%   |
| 5.13.13-1.el8.elrepo.x86_64  | 1         | 0.45%   |
| 5.13.0-1.el8.elrepo.x86_64   | 1         | 0.45%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1         | 0.45%   |
| 4.19.150                     | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 177       | 96.72%  |
| 5.9.1    | 1         | 0.55%   |
| 5.13.13  | 1         | 0.55%   |
| 5.13.0   | 1         | 0.55%   |
| 5.10.6   | 1         | 0.55%   |
| 4.19.150 | 1         | 0.55%   |
| Unknown  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 177       | 96.72%  |
| 5.13    | 2         | 1.09%   |
| 5.9     | 1         | 0.55%   |
| 5.10    | 1         | 0.55%   |
| 4.19    | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 182       | 99.45%  |
| Unknown | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 154       | 81.05%  |
| Unknown       | 19        | 10%     |
| GNOME Classic | 9         | 4.74%   |
| KDE5          | 5         | 2.63%   |
| KDE           | 2         | 1.05%   |
| MATE          | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 105       | 55.26%  |
| Wayland | 75        | 39.47%  |
| Unknown | 10        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 138       | 71.88%  |
| GDM     | 52        | 27.08%  |
| SDDM    | 1         | 0.52%   |
| LightDM | 1         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 126       | 67.02%  |
| Unknown | 13        | 6.91%   |
| en_GB   | 11        | 5.85%   |
| pl_PL   | 4         | 2.13%   |
| fr_FR   | 4         | 2.13%   |
| en_IN   | 4         | 2.13%   |
| ru_RU   | 3         | 1.6%    |
| de_DE   | 3         | 1.6%    |
| pt_BR   | 2         | 1.06%   |
| nl_NL   | 2         | 1.06%   |
| es_ES   | 2         | 1.06%   |
| es_AR   | 2         | 1.06%   |
| en_IE   | 2         | 1.06%   |
| sl_SI   | 1         | 0.53%   |
| ko_KR   | 1         | 0.53%   |
| ja_JP   | 1         | 0.53%   |
| it_IT   | 1         | 0.53%   |
| es_MX   | 1         | 0.53%   |
| es_EC   | 1         | 0.53%   |
| en_NZ   | 1         | 0.53%   |
| en_DK   | 1         | 0.53%   |
| de_CH   | 1         | 0.53%   |
| cs_CZ   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 148       | 79.14%  |
| BIOS | 39        | 20.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 163       | 87.63%  |
| Ext4    | 15        | 8.06%   |
| Unknown | 8         | 4.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 128       | 67.02%  |
| GPT     | 58        | 30.37%  |
| MBR     | 5         | 2.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 91.4%   |
| Yes       | 16        | 8.6%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 88.77%  |
| Yes       | 21        | 11.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 79        | 43.17%  |
| Dell                | 26        | 14.21%  |
| Hewlett-Packard     | 22        | 12.02%  |
| ASUSTek Computer    | 19        | 10.38%  |
| Gigabyte Technology | 9         | 4.92%   |
| ASRock              | 5         | 2.73%   |
| MSI                 | 4         | 2.19%   |
| Supermicro          | 3         | 1.64%   |
| Sony                | 2         | 1.09%   |
| Intel               | 2         | 1.09%   |
| Unknown             | 2         | 1.09%   |
| TUXEDO              | 1         | 0.55%   |
| Toshiba             | 1         | 0.55%   |
| Timi                | 1         | 0.55%   |
| IBM                 | 1         | 0.55%   |
| Getac               | 1         | 0.55%   |
| CX / Air Computers. | 1         | 0.55%   |
| AZW                 | 1         | 0.55%   |
| AMI                 | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |
| Acer                | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X        | 4         | 2.19%   |
| ASUS All Series                            | 4         | 2.19%   |
| Unknown                                    | 3         | 1.64%   |
| Supermicro X10DRi                          | 2         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401   | 2         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00   | 2         | 1.09%   |
| Lenovo ThinkPad T590 20N5S2NC0N            | 2         | 1.09%   |
| Lenovo ThinkPad T490s 20NYS7K91R           | 2         | 1.09%   |
| Lenovo ThinkPad T480s 20L8S2N800           | 2         | 1.09%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08      | 2         | 1.09%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q        | 2         | 1.09%   |
| HP EliteBook 8460p                         | 2         | 1.09%   |
| Dell Latitude E6430                        | 2         | 1.09%   |
| Dell Latitude 5300                         | 2         | 1.09%   |
| TUXEDO N13xWU                              | 1         | 0.55%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.55%   |
| Timi TM1707                                | 1         | 0.55%   |
| Supermicro X7DW3                           | 1         | 0.55%   |
| Sony VPCEB4L1R                             | 1         | 0.55%   |
| Sony VPCEB23FM                             | 1         | 0.55%   |
| MSI MS-7B51                                | 1         | 0.55%   |
| MSI MS-7B33                                | 1         | 0.55%   |
| MSI MS-7A37                                | 1         | 0.55%   |
| MSI MS-7752                                | 1         | 0.55%   |
| Lenovo Z40-70 20366                        | 1         | 0.55%   |
| Lenovo Yoga C640-13IML 81UE                | 1         | 0.55%   |
| Lenovo ThinkSystem SR645                   | 1         | 0.55%   |
| Lenovo ThinkPad X390 Yoga 20NQS18Y00       | 1         | 0.55%   |
| Lenovo ThinkPad X270 20HN001EMC            | 1         | 0.55%   |
| Lenovo ThinkPad X250 20CLS0H807            | 1         | 0.55%   |
| Lenovo ThinkPad X230 Tablet 34373KU        | 1         | 0.55%   |
| Lenovo ThinkPad X201 3680PKS               | 1         | 0.55%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100     | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G | 1         | 0.55%   |
| Lenovo ThinkPad W530 2441B32               | 1         | 0.55%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 0.55%   |
| Lenovo ThinkPad T590 20N5S2NC0V            | 1         | 0.55%   |
| Lenovo ThinkPad T590 20N5S2NC00            | 1         | 0.55%   |
| Lenovo ThinkPad T520 42404CG               | 1         | 0.55%   |
| Lenovo ThinkPad T490s 20NYS7K905           | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 69        | 37.7%   |
| Dell Precision     | 10        | 5.46%   |
| Dell Latitude      | 8         | 4.37%   |
| HP EliteBook       | 5         | 2.73%   |
| ASUS All           | 4         | 2.19%   |
| Lenovo ThinkCentre | 3         | 1.64%   |
| Dell Inspiron      | 3         | 1.64%   |
| ASUS PRIME         | 3         | 1.64%   |
| Unknown            | 3         | 1.64%   |
| Supermicro X10DRi  | 2         | 1.09%   |
| HP ZBook           | 2         | 1.09%   |
| HP Z230            | 2         | 1.09%   |
| ASUS ROG           | 2         | 1.09%   |
| TUXEDO N13xWU      | 1         | 0.55%   |
| Toshiba Satellite  | 1         | 0.55%   |
| Timi TM1707        | 1         | 0.55%   |
| Supermicro X7DW3   | 1         | 0.55%   |
| Sony VPCEB4L1R     | 1         | 0.55%   |
| Sony VPCEB23FM     | 1         | 0.55%   |
| MSI MS-7B51        | 1         | 0.55%   |
| MSI MS-7B33        | 1         | 0.55%   |
| MSI MS-7A37        | 1         | 0.55%   |
| MSI MS-7752        | 1         | 0.55%   |
| Lenovo Z40-70      | 1         | 0.55%   |
| Lenovo Yoga        | 1         | 0.55%   |
| Lenovo ThinkSystem | 1         | 0.55%   |
| Lenovo S40-40      | 1         | 0.55%   |
| Lenovo Legion      | 1         | 0.55%   |
| Lenovo 10SFS03200  | 1         | 0.55%   |
| Intel NUC10i7FNK   | 1         | 0.55%   |
| Intel DX79SR       | 1         | 0.55%   |
| IBM FAB2           | 1         | 0.55%   |
| HP Z840            | 1         | 0.55%   |
| HP Z620            | 1         | 0.55%   |
| HP Z440            | 1         | 0.55%   |
| HP Z1              | 1         | 0.55%   |
| HP ProLiant        | 1         | 0.55%   |
| HP ProBook         | 1         | 0.55%   |
| HP Pavilion        | 1         | 0.55%   |
| HP OMEN            | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 34        | 18.58%  |
| 2019 | 33        | 18.03%  |
| 2018 | 26        | 14.21%  |
| 2015 | 16        | 8.74%   |
| 2012 | 14        | 7.65%   |
| 2017 | 13        | 7.1%    |
| 2021 | 11        | 6.01%   |
| 2016 | 11        | 6.01%   |
| 2011 | 8         | 4.37%   |
| 2013 | 7         | 3.83%   |
| 2014 | 5         | 2.73%   |
| 2010 | 3         | 1.64%   |
| 2022 | 1         | 0.55%   |
| 2009 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 113       | 61.75%  |
| Desktop     | 54        | 29.51%  |
| Server      | 7         | 3.83%   |
| Convertible | 4         | 2.19%   |
| Mini pc     | 4         | 2.19%   |
| All in one  | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 161       | 87.03%  |
| Enabled  | 24        | 12.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 183       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 56        | 29.47%  |
| 16.01-24.0      | 33        | 17.37%  |
| 8.01-16.0       | 30        | 15.79%  |
| 4.01-8.0        | 27        | 14.21%  |
| 64.01-256.0     | 26        | 13.68%  |
| 24.01-32.0      | 8         | 4.21%   |
| 3.01-4.0        | 7         | 3.68%   |
| More than 256.0 | 2         | 1.05%   |
| Unknown         | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 77        | 36.67%  |
| 2.01-3.0        | 38        | 18.1%   |
| 8.01-16.0       | 35        | 16.67%  |
| 3.01-4.0        | 32        | 15.24%  |
| 1.01-2.0        | 14        | 6.67%   |
| 16.01-24.0      | 5         | 2.38%   |
| 24.01-32.0      | 4         | 1.9%    |
| 0.51-1.0        | 2         | 0.95%   |
| More than 256.0 | 1         | 0.48%   |
| 32.01-64.0      | 1         | 0.48%   |
| Unknown         | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 111       | 57.81%  |
| 2      | 44        | 22.92%  |
| 3      | 18        | 9.38%   |
| 4      | 8         | 4.17%   |
| 5      | 4         | 2.08%   |
| 8      | 2         | 1.04%   |
| 6      | 2         | 1.04%   |
| 10     | 1         | 0.52%   |
| 7      | 1         | 0.52%   |
| 0      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 77.84%  |
| Yes       | 41        | 22.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 90.22%  |
| No        | 18        | 9.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 80.87%  |
| No        | 35        | 19.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 65.08%  |
| No        | 66        | 34.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40        | 21.86%  |
| India        | 16        | 8.74%   |
| UK           | 13        | 7.1%    |
| Czechia      | 11        | 6.01%   |
| Germany      | 10        | 5.46%   |
| France       | 6         | 3.28%   |
| Canada       | 6         | 3.28%   |
| Poland       | 5         | 2.73%   |
| Netherlands  | 4         | 2.19%   |
| Mexico       | 4         | 2.19%   |
| Brazil       | 4         | 2.19%   |
| Switzerland  | 3         | 1.64%   |
| Spain        | 3         | 1.64%   |
| South Africa | 3         | 1.64%   |
| Russia       | 3         | 1.64%   |
| Lithuania    | 3         | 1.64%   |
| Italy        | 3         | 1.64%   |
| Finland      | 3         | 1.64%   |
| Australia    | 3         | 1.64%   |
| Argentina    | 3         | 1.64%   |
| Ukraine      | 2         | 1.09%   |
| South Korea  | 2         | 1.09%   |
| Romania      | 2         | 1.09%   |
| Japan        | 2         | 1.09%   |
| Egypt        | 2         | 1.09%   |
| China        | 2         | 1.09%   |
| Turkmenistan | 1         | 0.55%   |
| Sweden       | 1         | 0.55%   |
| Slovenia     | 1         | 0.55%   |
| Singapore    | 1         | 0.55%   |
| Saudi Arabia | 1         | 0.55%   |
| Portugal     | 1         | 0.55%   |
| Pakistan     | 1         | 0.55%   |
| New Zealand  | 1         | 0.55%   |
| Nepal        | 1         | 0.55%   |
| Myanmar      | 1         | 0.55%   |
| Morocco      | 1         | 0.55%   |
| Luxembourg   | 1         | 0.55%   |
| Kuwait       | 1         | 0.55%   |
| Kenya        | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Prague            | 9         | 4.59%   |
| Turku             | 3         | 1.53%   |
| San Jose          | 3         | 1.53%   |
| Munich            | 3         | 1.53%   |
| Mexico City       | 3         | 1.53%   |
| Montreal          | 2         | 1.02%   |
| Milan             | 2         | 1.02%   |
| Kyiv              | 2         | 1.02%   |
| Didcot            | 2         | 1.02%   |
| Des Moines        | 2         | 1.02%   |
| Chicago           | 2         | 1.02%   |
| Chennai           | 2         | 1.02%   |
| Berlin            | 2         | 1.02%   |
| Bengaluru         | 2         | 1.02%   |
| Zaragoza          | 1         | 0.51%   |
| Yongin-si         | 1         | 0.51%   |
| Wroclaw           | 1         | 0.51%   |
| Wiesbaden         | 1         | 0.51%   |
| Webster           | 1         | 0.51%   |
| Wayne             | 1         | 0.51%   |
| Wagholi           | 1         | 0.51%   |
| Vardenis          | 1         | 0.51%   |
| Vaglio            | 1         | 0.51%   |
| Udaipur           | 1         | 0.51%   |
| Toronto           | 1         | 0.51%   |
| Tiruchi           | 1         | 0.51%   |
| Temuco            | 1         | 0.51%   |
| Temara            | 1         | 0.51%   |
| Tauranga          | 1         | 0.51%   |
| Taringa           | 1         | 0.51%   |
| Talkha            | 1         | 0.51%   |
| Syracuse          | 1         | 0.51%   |
| Suffolk           | 1         | 0.51%   |
| Stuttgart         | 1         | 0.51%   |
| Streatham         | 1         | 0.51%   |
| Stellenbosch      | 1         | 0.51%   |
| Steamboat Springs | 1         | 0.51%   |
| Spokane           | 1         | 0.51%   |
| Sofia             | 1         | 0.51%   |
| Singapore         | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 52        | 97     | 18.64%  |
| WDC                         | 36        | 61     | 12.9%   |
| Seagate                     | 29        | 45     | 10.39%  |
| Toshiba                     | 23        | 30     | 8.24%   |
| SK hynix                    | 17        | 21     | 6.09%   |
| SanDisk                     | 16        | 26     | 5.73%   |
| Kingston                    | 14        | 18     | 5.02%   |
| Intel                       | 11        | 18     | 3.94%   |
| Micron Technology           | 10        | 17     | 3.58%   |
| Crucial                     | 10        | 14     | 3.58%   |
| Unknown                     | 7         | 9      | 2.51%   |
| A-DATA Technology           | 6         | 6      | 2.15%   |
| HGST                        | 4         | 4      | 1.43%   |
| Silicon Motion              | 3         | 4      | 1.08%   |
| PNY                         | 3         | 4      | 1.08%   |
| Phison                      | 3         | 7      | 1.08%   |
| Lenovo                      | 3         | 3      | 1.08%   |
| Hitachi                     | 3         | 3      | 1.08%   |
| Hewlett-Packard             | 3         | 5      | 1.08%   |
| Gigabyte Technology         | 3         | 4      | 1.08%   |
| Corsair                     | 3         | 6      | 1.08%   |
| XPG                         | 1         | 1      | 0.36%   |
| Western Digital             | 1         | 1      | 0.36%   |
| UMIS                        | 1         | 1      | 0.36%   |
| Team                        | 1         | 2      | 0.36%   |
| T-FORCE                     | 1         | 2      | 0.36%   |
| SSSTC                       | 1         | 1      | 0.36%   |
| SMI                         | 1         | 2      | 0.36%   |
| OCZ                         | 1         | 2      | 0.36%   |
| Micron/Crucial Technology   | 1         | 1      | 0.36%   |
| Lite-On                     | 1         | 1      | 0.36%   |
| KIOXIA                      | 1         | 1      | 0.36%   |
| Kingston Technology Company | 1         | 1      | 0.36%   |
| KingFast                    | 1         | 1      | 0.36%   |
| KINGBANK                    | 1         | 1      | 0.36%   |
| Intenso                     | 1         | 1      | 0.36%   |
| HPT                         | 1         | 1      | 0.36%   |
| Hoodisk                     | 1         | 1      | 0.36%   |
| DELLBOSS                    | 1         | 1      | 0.36%   |
| Dell                        | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB       | 10        | 3.14%   |
| Samsung NVMe SSD Drive 512GB        | 7         | 2.2%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 6         | 1.89%   |
| SanDisk NVMe SSD Drive 256GB        | 6         | 1.89%   |
| Samsung SSD 860 EVO 1TB             | 6         | 1.89%   |
| Samsung NVMe SSD Drive 256GB        | 6         | 1.89%   |
| Samsung NVMe SSD Drive 1024GB       | 5         | 1.57%   |
| Samsung NVMe SSD Drive 500GB        | 4         | 1.26%   |
| Toshiba NVMe SSD Drive 512GB        | 3         | 0.94%   |
| Micron NVMe SSD Drive 256GB         | 3         | 0.94%   |
| HGST HTS721010A9E630 1TB            | 3         | 0.94%   |
| Crucial CT240BX500SSD1 240GB        | 3         | 0.94%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 2         | 0.63%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 0.63%   |
| Unknown NVMe SSD Drive 256GB        | 2         | 0.63%   |
| Toshiba KXG6AZNV256G 256GB          | 2         | 0.63%   |
| Toshiba DT01ACA200 2TB              | 2         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 0.63%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.63%   |
| Seagate Expansion 1TB               | 2         | 0.63%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.63%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.63%   |
| Samsung Portable SSD T5 500GB       | 2         | 0.63%   |
| Samsung NVMe SSD Drive 2TB          | 2         | 0.63%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.63%   |
| Samsung MZVL21T0HCLR-00BL7 1TB      | 2         | 0.63%   |
| Kingston SUV500120G 120GB SSD       | 2         | 0.63%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.63%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.63%   |
| Intel SSDPEL1K100GA 100GB           | 2         | 0.63%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.63%   |
| Intel NVMe SSD Drive 2TB            | 2         | 0.63%   |
| HP SSD EX950 512GB                  | 2         | 0.63%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB      | 2         | 0.63%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.63%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.63%   |
| Corsair Force LE SSD 240GB          | 2         | 0.63%   |
| XPG NVMe SSD Drive 1024GB           | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 44     | 38.16%  |
| WDC                 | 27        | 48     | 35.53%  |
| Toshiba             | 9         | 13     | 11.84%  |
| HGST                | 4         | 4      | 5.26%   |
| Hitachi             | 3         | 3      | 3.95%   |
| Unknown             | 1         | 1      | 1.32%   |
| Samsung Electronics | 1         | 2      | 1.32%   |
| Hewlett-Packard     | 1         | 1      | 1.32%   |
| DELLBOSS            | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 40     | 28.24%  |
| Kingston            | 11        | 15     | 12.94%  |
| Crucial             | 10        | 14     | 11.76%  |
| WDC                 | 6         | 8      | 7.06%   |
| SanDisk             | 6         | 12     | 7.06%   |
| Micron Technology   | 5         | 10     | 5.88%   |
| A-DATA Technology   | 5         | 5      | 5.88%   |
| PNY                 | 3         | 4      | 3.53%   |
| Corsair             | 3         | 6      | 3.53%   |
| SK hynix            | 2         | 5      | 2.35%   |
| Intel               | 2         | 3      | 2.35%   |
| Toshiba             | 1         | 1      | 1.18%   |
| Team                | 1         | 2      | 1.18%   |
| Seagate             | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 2      | 1.18%   |
| KINGBANK            | 1         | 1      | 1.18%   |
| Intenso             | 1         | 1      | 1.18%   |
| Hoodisk             | 1         | 1      | 1.18%   |
| China               | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 105       | 166    | 40.86%  |
| SSD     | 77        | 132    | 29.96%  |
| HDD     | 67        | 117    | 26.07%  |
| MMC     | 4         | 5      | 1.56%   |
| Unknown | 4         | 6      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 105       | 166    | 46.88%  |
| SATA | 100       | 231    | 44.64%  |
| SAS  | 15        | 24     | 6.7%    |
| MMC  | 4         | 5      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 115    | 45.45%  |
| 0.51-1.0   | 48        | 77     | 31.17%  |
| 1.01-2.0   | 21        | 27     | 13.64%  |
| 3.01-4.0   | 9         | 19     | 5.84%   |
| 4.01-10.0  | 4         | 9      | 2.6%    |
| 2.01-3.0   | 1         | 1      | 0.65%   |
| 10.01-20.0 | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 69        | 35.57%  |
| 251-500        | 33        | 17.01%  |
| 501-1000       | 31        | 15.98%  |
| More than 3000 | 17        | 8.76%   |
| 1001-2000      | 17        | 8.76%   |
| 2001-3000      | 9         | 4.64%   |
| Unknown        | 8         | 4.12%   |
| 51-100         | 6         | 3.09%   |
| 21-50          | 3         | 1.55%   |
| 1-20           | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 45        | 21.63%  |
| 1-20           | 40        | 19.23%  |
| 101-250        | 37        | 17.79%  |
| 51-100         | 33        | 15.87%  |
| 251-500        | 18        | 8.65%   |
| 501-1000       | 11        | 5.29%   |
| 1001-2000      | 9         | 4.33%   |
| Unknown        | 8         | 3.85%   |
| More than 3000 | 4         | 1.92%   |
| 2001-3000      | 3         | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 20%     |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1      | 20%     |
| Micron Technology M510_2.5 7MM 256GB SSD | 1         | 1      | 20%     |
| Hitachi HDS722020ALA330 2TB              | 1         | 1      | 20%     |
| A-DATA Technology SU800NS38 256GB SSD    | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 2      | 40%     |
| Micron Technology | 1         | 1      | 20%     |
| Hitachi           | 1         | 1      | 20%     |
| A-DATA Technology | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

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
| Detected | 132       | 312    | 67.69%  |
| Works    | 58        | 109    | 29.74%  |
| Malfunc  | 5         | 5      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 104       | 42.45%  |
| Samsung Electronics            | 35        | 14.29%  |
| AMD                            | 16        | 6.53%   |
| SK hynix                       | 15        | 6.12%   |
| Toshiba America Info Systems   | 13        | 5.31%   |
| SanDisk                        | 13        | 5.31%   |
| Silicon Motion                 | 5         | 2.04%   |
| Phison Electronics             | 5         | 2.04%   |
| Micron Technology              | 5         | 2.04%   |
| Marvell Technology Group       | 4         | 1.63%   |
| Broadcom / LSI                 | 4         | 1.63%   |
| Lenovo                         | 3         | 1.22%   |
| KIOXIA                         | 3         | 1.22%   |
| Kingston Technology Company    | 3         | 1.22%   |
| ASMedia Technology             | 3         | 1.22%   |
| LSI Logic / Symbios Logic      | 2         | 0.82%   |
| Biwin Storage Technology       | 2         | 0.82%   |
| ADATA Technology               | 2         | 0.82%   |
| Western Digital                | 1         | 0.41%   |
| Union Memory (Shenzhen)        | 1         | 0.41%   |
| Solid State Storage Technology | 1         | 0.41%   |
| PMC-Sierra                     | 1         | 0.41%   |
| Micron/Crucial Technology      | 1         | 0.41%   |
| Lite-On Technology             | 1         | 0.41%   |
| HighPoint Technologies         | 1         | 0.41%   |
| Hewlett-Packard                | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 10.07%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 5.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 4.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 3.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 3.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 3.36%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7         | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.61%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 6         | 2.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.24%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5         | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.87%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 1.49%   |
| Intel SSD 660P Series                                                          | 4         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.12%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.12%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.75%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.75%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.75%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 105       | 44.68%  |
| SATA | 105       | 44.68%  |
| RAID | 15        | 6.38%   |
| SAS  | 6         | 2.55%   |
| IDE  | 4         | 1.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 88.52%  |
| AMD    | 21        | 11.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 6.01%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.92%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 9         | 4.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 3.28%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 2.19%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 2.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.64%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1.09%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 2         | 1.09%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.09%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.09%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1.09%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.09%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.09%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.55%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.55%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.55%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.55%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.55%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.55%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.55%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.55%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.55%   |
| Intel Xeon CPU E5-2618L v4 @ 2.20GHz          | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 79        | 43.17%  |
| Intel Core i5      | 38        | 20.77%  |
| Intel Xeon         | 21        | 11.48%  |
| Intel Core i3      | 9         | 4.92%   |
| Other              | 8         | 4.37%   |
| AMD Ryzen 7        | 7         | 3.83%   |
| AMD Ryzen 9        | 4         | 2.19%   |
| Intel Core i9      | 3         | 1.64%   |
| AMD Ryzen 5        | 3         | 1.64%   |
| Intel Pentium Gold | 2         | 1.09%   |
| Intel Pentium      | 2         | 1.09%   |
| AMD Ryzen 3        | 2         | 1.09%   |
| AMD EPYC           | 2         | 1.09%   |
| AMD Ryzen 7 PRO    | 1         | 0.55%   |
| AMD FX             | 1         | 0.55%   |
| AMD A10            | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 81        | 44.26%  |
| 2      | 39        | 21.31%  |
| 6      | 32        | 17.49%  |
| 8      | 15        | 8.2%    |
| 12     | 6         | 3.28%   |
| 16     | 3         | 1.64%   |
| 20     | 2         | 1.09%   |
| 96     | 1         | 0.55%   |
| 64     | 1         | 0.55%   |
| 36     | 1         | 0.55%   |
| 24     | 1         | 0.55%   |
| 10     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 173       | 94.54%  |
| 2      | 10        | 5.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 159       | 86.41%  |
| 1      | 25        | 13.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 179       | 96.76%  |
| Unknown        | 6         | 3.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 28        | 15.14%  |
| 0x906ea    | 14        | 7.57%   |
| 0x806ea    | 14        | 7.57%   |
| 0xa0652    | 12        | 6.49%   |
| 0x306c3    | 12        | 6.49%   |
| 0x306a9    | 10        | 5.41%   |
| 0x206a7    | 8         | 4.32%   |
| 0x906ed    | 7         | 3.78%   |
| 0x506e3    | 7         | 3.78%   |
| 0x906e9    | 5         | 2.7%    |
| 0x806c1    | 5         | 2.7%    |
| 0x406e3    | 5         | 2.7%    |
| 0x306f2    | 5         | 2.7%    |
| Unknown    | 5         | 2.7%    |
| 0x806e9    | 4         | 2.16%   |
| 0x806d1    | 3         | 1.62%   |
| 0x406f1    | 3         | 1.62%   |
| 0x306d4    | 3         | 1.62%   |
| 0x20655    | 3         | 1.62%   |
| 0x08600103 | 3         | 1.62%   |
| 0x08108102 | 3         | 1.62%   |
| 0x40651    | 2         | 1.08%   |
| 0x206d7    | 2         | 1.08%   |
| 0x0a50000c | 2         | 1.08%   |
| 0x08701021 | 2         | 1.08%   |
| 0x08701013 | 2         | 1.08%   |
| 0xa0671    | 1         | 0.54%   |
| 0xa0660    | 1         | 0.54%   |
| 0xa0655    | 1         | 0.54%   |
| 0x906eb    | 1         | 0.54%   |
| 0x306e4    | 1         | 0.54%   |
| 0x20652    | 1         | 0.54%   |
| 0x10676    | 1         | 0.54%   |
| 0x0a001119 | 1         | 0.54%   |
| 0x08600106 | 1         | 0.54%   |
| 0x08600104 | 1         | 0.54%   |
| 0x08301034 | 1         | 0.54%   |
| 0x0810100b | 1         | 0.54%   |
| 0x08001138 | 1         | 0.54%   |
| 0x08001137 | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 74        | 40.22%  |
| Haswell     | 20        | 10.87%  |
| CometLake   | 14        | 7.61%   |
| Skylake     | 12        | 6.52%   |
| IvyBridge   | 12        | 6.52%   |
| Zen 2       | 10        | 5.43%   |
| SandyBridge | 10        | 5.43%   |
| Broadwell   | 6         | 3.26%   |
| TigerLake   | 5         | 2.72%   |
| Westmere    | 4         | 2.17%   |
| Icelake     | 4         | 2.17%   |
| Zen+        | 3         | 1.63%   |
| Zen         | 3         | 1.63%   |
| Zen 3       | 2         | 1.09%   |
| Unknown     | 2         | 1.09%   |
| Steamroller | 1         | 0.54%   |
| Piledriver  | 1         | 0.54%   |
| Penryn      | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 123       | 54.67%  |
| Nvidia                     | 69        | 30.67%  |
| AMD                        | 27        | 12%     |
| Matrox Electronics Systems | 4         | 1.78%   |
| ASPEED Technology          | 2         | 0.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 15        | 6.61%   |
| Intel UHD Graphics 620                                                      | 14        | 6.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 13        | 5.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 4.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 3.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 2.64%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 5         | 2.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 2.2%    |
| AMD Renoir                                                                  | 5         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.76%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.32%   |
| Intel HD Graphics 630                                                       | 3         | 1.32%   |
| Intel HD Graphics 620                                                       | 3         | 1.32%   |
| Intel HD Graphics 5500                                                      | 3         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.88%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.88%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.88%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.88%   |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.88%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.88%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.88%   |
| Intel HD Graphics 530                                                       | 2         | 0.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.88%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2         | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 88        | 47.31%  |
| 1 x Nvidia              | 38        | 20.43%  |
| Intel + Nvidia          | 25        | 13.44%  |
| 1 x AMD                 | 17        | 9.14%   |
| Intel + AMD             | 6         | 3.23%   |
| 1 x Matrox              | 3         | 1.61%   |
| AMD + Nvidia            | 3         | 1.61%   |
| Other                   | 1         | 0.54%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.54%   |
| 2 x Nvidia              | 1         | 0.54%   |
| 2 x AMD                 | 1         | 0.54%   |
| Nvidia + Matrox         | 1         | 0.54%   |
| Nvidia + ASPEED         | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 147       | 79.03%  |
| Proprietary | 31        | 16.67%  |
| Unknown     | 8         | 4.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 59.26%  |
| 1.01-2.0   | 19        | 10.05%  |
| 3.01-4.0   | 15        | 7.94%   |
| 7.01-8.0   | 10        | 5.29%   |
| 0.51-1.0   | 10        | 5.29%   |
| 0.01-0.5   | 8         | 4.23%   |
| 5.01-6.0   | 7         | 3.7%    |
| 2.01-3.0   | 4         | 2.12%   |
| 4.01-5.0   | 2         | 1.06%   |
| 8.01-16.0  | 2         | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 11.91%  |
| Samsung Electronics     | 23        | 9.79%   |
| Lenovo                  | 23        | 9.79%   |
| Dell                    | 23        | 9.79%   |
| BOE                     | 20        | 8.51%   |
| LG Display              | 19        | 8.09%   |
| Chimei Innolux          | 19        | 8.09%   |
| Hewlett-Packard         | 14        | 5.96%   |
| Goldstar                | 13        | 5.53%   |
| Sharp                   | 5         | 2.13%   |
| Acer                    | 5         | 2.13%   |
| Philips                 | 4         | 1.7%    |
| InfoVision              | 4         | 1.7%    |
| Eizo                    | 4         | 1.7%    |
| BenQ                    | 4         | 1.7%    |
| Ancor Communications    | 3         | 1.28%   |
| ViewSonic               | 2         | 0.85%   |
| PANDA                   | 2         | 0.85%   |
| LGD                     | 2         | 0.85%   |
| Lenovo Group Limited    | 2         | 0.85%   |
| Iiyama                  | 2         | 0.85%   |
| Gigabyte Technology     | 2         | 0.85%   |
| AOC                     | 2         | 0.85%   |
| Sun                     | 1         | 0.43%   |
| Sceptre Tech            | 1         | 0.43%   |
| Planar                  | 1         | 0.43%   |
| Microstep               | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| Insignia                | 1         | 0.43%   |
| EVE                     | 1         | 0.43%   |
| Chi Mei Optoelectronics | 1         | 0.43%   |
| BOE Technology Group    | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.76%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.97%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.97%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 5         | 1.97%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 1.18%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 1.18%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 3         | 1.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 3         | 1.18%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 1.18%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 3         | 1.18%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 1.18%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 1.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 2         | 0.79%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.79%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.79%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.79%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.79%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch              | 2         | 0.79%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.79%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.79%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.79%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch        | 2         | 0.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.79%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch    | 2         | 0.79%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch     | 1         | 0.39%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch     | 1         | 0.39%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                 | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch           | 1         | 0.39%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch           | 1         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 1         | 0.39%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch           | 1         | 0.39%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch           | 1         | 0.39%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch    | 1         | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 112       | 53.85%  |
| 1366x768 (WXGA)    | 17        | 8.17%   |
| 3840x2160 (4K)     | 16        | 7.69%   |
| 2560x1440 (QHD)    | 16        | 7.69%   |
| 1600x900 (HD+)     | 11        | 5.29%   |
| 1920x1200 (WUXGA)  | 6         | 2.88%   |
| 3440x1440          | 5         | 2.4%    |
| 3840x1080          | 4         | 1.92%   |
| 2560x1080          | 4         | 1.92%   |
| Unknown            | 4         | 1.92%   |
| 1680x1050 (WSXGA+) | 2         | 0.96%   |
| 1440x900 (WXGA+)   | 2         | 0.96%   |
| 9600x2160          | 1         | 0.48%   |
| 7680x2160          | 1         | 0.48%   |
| 6400x2160          | 1         | 0.48%   |
| 3840x1600          | 1         | 0.48%   |
| 3840x1200          | 1         | 0.48%   |
| 2560x1600          | 1         | 0.48%   |
| 2048x1152          | 1         | 0.48%   |
| 1280x800 (WXGA)    | 1         | 0.48%   |
| 1280x720 (HD)      | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 19.66%  |
| 14      | 33        | 14.1%   |
| 24      | 27        | 11.54%  |
| 27      | 24        | 10.26%  |
| 13      | 19        | 8.12%   |
| 23      | 17        | 7.26%   |
| Unknown | 14        | 5.98%   |
| 21      | 11        | 4.7%    |
| 34      | 7         | 2.99%   |
| 31      | 6         | 2.56%   |
| 12      | 5         | 2.14%   |
| 20      | 4         | 1.71%   |
| 32      | 3         | 1.28%   |
| 17      | 3         | 1.28%   |
| 54      | 2         | 0.85%   |
| 47      | 2         | 0.85%   |
| 22      | 2         | 0.85%   |
| 18      | 2         | 0.85%   |
| 49      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 39      | 1         | 0.43%   |
| 37      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 16      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 40.97%  |
| 501-600     | 58        | 25.55%  |
| 401-500     | 19        | 8.37%   |
| Unknown     | 14        | 6.17%   |
| 601-700     | 11        | 4.85%   |
| 201-300     | 11        | 4.85%   |
| 701-800     | 10        | 4.41%   |
| 1001-1500   | 5         | 2.2%    |
| 801-900     | 3         | 1.32%   |
| 351-400     | 3         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 80.32%  |
| 16/10   | 15        | 7.98%   |
| Unknown | 12        | 6.38%   |
| 21/9    | 8         | 4.26%   |
| 32/9    | 1         | 0.53%   |
| 3/2     | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 46        | 19.91%  |
| 201-250        | 45        | 19.48%  |
| 101-110        | 45        | 19.48%  |
| 301-350        | 24        | 10.39%  |
| 351-500        | 15        | 6.49%   |
| Unknown        | 14        | 6.06%   |
| 251-300        | 10        | 4.33%   |
| 151-200        | 7         | 3.03%   |
| 71-80          | 6         | 2.6%    |
| 501-1000       | 6         | 2.6%    |
| 61-70          | 5         | 2.16%   |
| 121-130        | 3         | 1.3%    |
| More than 1000 | 2         | 0.87%   |
| 111-120        | 2         | 0.87%   |
| 141-150        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 85        | 37.78%  |
| 51-100        | 68        | 30.22%  |
| 101-120       | 37        | 16.44%  |
| Unknown       | 14        | 6.22%   |
| 161-240       | 13        | 5.78%   |
| More than 240 | 4         | 1.78%   |
| 1-50          | 4         | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 118       | 60.82%  |
| 2     | 51        | 26.29%  |
| 0     | 13        | 6.7%    |
| 3     | 12        | 6.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 146       | 52.33%  |
| Realtek Semiconductor             | 58        | 20.79%  |
| Lenovo                            | 19        | 6.81%   |
| Qualcomm Atheros                  | 13        | 4.66%   |
| Broadcom                          | 7         | 2.51%   |
| Broadcom Limited                  | 5         | 1.79%   |
| MediaTek                          | 4         | 1.43%   |
| ASIX Electronics                  | 4         | 1.43%   |
| Sierra Wireless                   | 2         | 0.72%   |
| Ralink                            | 2         | 0.72%   |
| Marvell Technology Group          | 2         | 0.72%   |
| Huawei Technologies               | 2         | 0.72%   |
| Dell                              | 2         | 0.72%   |
| Xiaomi                            | 1         | 0.36%   |
| Samsung Electronics               | 1         | 0.36%   |
| Ralink Technology                 | 1         | 0.36%   |
| Qualcomm Atheros Communications   | 1         | 0.36%   |
| Microchip Technology              | 1         | 0.36%   |
| Micro Star International          | 1         | 0.36%   |
| Luminary Micro                    | 1         | 0.36%   |
| ICS Advent                        | 1         | 0.36%   |
| IBM                               | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |
| DisplayLink                       | 1         | 0.36%   |
| D-Link                            | 1         | 0.36%   |
| Arduino SA                        | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 10.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 4.26%   |
| Intel Wireless 8265 / 8275                                        | 15        | 3.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 3.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 3.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 2.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 2.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 2.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 2.66%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 9         | 2.39%   |
| Intel Ethernet Connection (10) I219-LM                            | 8         | 2.13%   |
| Intel Wireless 8260                                               | 6         | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 6         | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 1.06%   |
| Intel Wireless-AC 9260                                            | 4         | 1.06%   |
| Intel I350 Gigabit Network Connection                             | 4         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.8%    |
| Lenovo USB-C to LAN                                               | 3         | 0.8%    |
| Lenovo ThinkPad Lan                                               | 3         | 0.8%    |
| Intel Wireless 7265                                               | 3         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.8%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.8%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3         | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 111       | 72.08%  |
| Qualcomm Atheros                  | 12        | 7.79%   |
| Realtek Semiconductor             | 11        | 7.14%   |
| Broadcom                          | 5         | 3.25%   |
| MediaTek                          | 4         | 2.6%    |
| Sierra Wireless                   | 2         | 1.3%    |
| Ralink                            | 2         | 1.3%    |
| Ralink Technology                 | 1         | 0.65%   |
| Qualcomm Atheros Communications   | 1         | 0.65%   |
| Micro Star International          | 1         | 0.65%   |
| Ericsson Business Mobile Networks | 1         | 0.65%   |
| Dell                              | 1         | 0.65%   |
| D-Link                            | 1         | 0.65%   |
| Broadcom Limited                  | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 15        | 9.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 9.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 14        | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 7.79%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 6.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 6.49%   |
| Intel Wireless 8260                                            | 6         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.9%    |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.25%   |
| Intel Wireless-AC 9260                                         | 4         | 2.6%    |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.95%   |
| Intel Wireless 7265                                            | 3         | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.95%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 3         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.3%    |
| Intel Wireless 7260                                            | 2         | 1.3%    |
| Intel Wireless 3165                                            | 2         | 1.3%    |
| Sierra Wireless EM7511 QualcommÂ Snapdragonâ¢ X16 LTE-A   | 1         | 0.65%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.65%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 0.65%   |
| Micro Star International 802.11 n WLAN                         | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 112       | 55.45%  |
| Realtek Semiconductor    | 51        | 25.25%  |
| Lenovo                   | 19        | 9.41%   |
| Broadcom Limited         | 4         | 1.98%   |
| ASIX Electronics         | 4         | 1.98%   |
| Qualcomm Atheros         | 2         | 0.99%   |
| Marvell Technology Group | 2         | 0.99%   |
| Broadcom                 | 2         | 0.99%   |
| Xiaomi                   | 1         | 0.5%    |
| ICS Advent               | 1         | 0.5%    |
| IBM                      | 1         | 0.5%    |
| Huawei Technologies      | 1         | 0.5%    |
| DisplayLink              | 1         | 0.5%    |
| Dell                     | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 39        | 17.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 7.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 4.61%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 4.61%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.61%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4.61%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 4.15%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 3.69%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.76%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.84%   |
| Intel I350 Gigabit Network Connection                                          | 4         | 1.84%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.84%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.84%   |
| Lenovo USB-C to LAN                                                            | 3         | 1.38%   |
| Lenovo ThinkPad Lan                                                            | 3         | 1.38%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.38%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.38%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.38%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.92%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.92%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.92%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.92%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.92%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.92%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.92%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.46%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.46%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 52.04%  |
| WiFi     | 148       | 46.39%  |
| Modem    | 5         | 1.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 50%     |
| Ethernet | 98        | 49.49%  |
| Modem    | 1         | 0.51%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 62.5%   |
| 1     | 51        | 27.72%  |
| 3     | 10        | 5.43%   |
| 4     | 3         | 1.63%   |
| 6     | 2         | 1.09%   |
| 132   | 1         | 0.54%   |
| 22    | 1         | 0.54%   |
| 8     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 167       | 90.27%  |
| Yes  | 18        | 9.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 69.92%  |
| Cambridge Silicon Radio         | 8         | 6.5%    |
| Broadcom                        | 7         | 5.69%   |
| Qualcomm Atheros Communications | 5         | 4.07%   |
| IMC Networks                    | 4         | 3.25%   |
| Realtek Semiconductor           | 3         | 2.44%   |
| Foxconn / Hon Hai               | 3         | 2.44%   |
| ASUSTek Computer                | 3         | 2.44%   |
| Ralink                          | 1         | 0.81%   |
| Micro Star International        | 1         | 0.81%   |
| MediaTek                        | 1         | 0.81%   |
| Dell                            | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 30        | 24.39%  |
| Intel Bluetooth wireless interface                                                  | 21        | 17.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 17.07%  |
| Intel AX200 Bluetooth                                                               | 9         | 7.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 6.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 3.25%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.44%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.63%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.63%   |
| ASUS BCM20702A0                                                                     | 2         | 1.63%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.81%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.81%   |
| MediaTek Wireless_Device                                                            | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.81%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.81%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.81%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.81%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 153       | 51.69%  |
| Nvidia                    | 52        | 17.57%  |
| AMD                       | 27        | 9.12%   |
| Lenovo                    | 17        | 5.74%   |
| Plantronics               | 6         | 2.03%   |
| JMTek                     | 5         | 1.69%   |
| GN Netcom                 | 5         | 1.69%   |
| Texas Instruments         | 3         | 1.01%   |
| Generalplus Technology    | 3         | 1.01%   |
| Creative Technology       | 3         | 1.01%   |
| Creative Labs             | 3         | 1.01%   |
| Sennheiser Communications | 2         | 0.68%   |
| Realtek Semiconductor     | 2         | 0.68%   |
| Logitech                  | 2         | 0.68%   |
| C-Media Electronics       | 2         | 0.68%   |
| Tenx Technology           | 1         | 0.34%   |
| SteelSeries ApS           | 1         | 0.34%   |
| Scarlett                  | 1         | 0.34%   |
| RODE Microphones          | 1         | 0.34%   |
| Google                    | 1         | 0.34%   |
| Giga-Byte Technology      | 1         | 0.34%   |
| Dynex                     | 1         | 0.34%   |
| Dell                      | 1         | 0.34%   |
| Corsair                   | 1         | 0.34%   |
| Blue Microphones          | 1         | 0.34%   |
| ASUSTek Computer          | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 23        | 7.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 6.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 5.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 4.39%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 4.08%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.13%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 1.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.57%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 1.57%   |
| Plantronics BT600                                                          | 4         | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.25%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.25%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.94%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.94%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.63%   |
| Plantronics Poly BT700                                                     | 2         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.63%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 32.95%  |
| SK hynix            | 20        | 22.73%  |
| Crucial             | 9         | 10.23%  |
| Micron Technology   | 6         | 6.82%   |
| Kingston            | 6         | 6.82%   |
| Corsair             | 5         | 5.68%   |
| Unknown             | 2         | 2.27%   |
| GOODRAM             | 2         | 2.27%   |
| Unknown (0x0B5E)    | 1         | 1.14%   |
| Unknown (0x0205)    | 1         | 1.14%   |
| Transcend           | 1         | 1.14%   |
| Smart               | 1         | 1.14%   |
| Patriot             | 1         | 1.14%   |
| Innodisk            | 1         | 1.14%   |
| Hewlett-Packard     | 1         | 1.14%   |
| Elpida              | 1         | 1.14%   |
| Unknown             | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 4.26%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2.13%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 2.13%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.13%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s            | 2         | 2.13%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s         | 2         | 2.13%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 2.13%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.06%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.06%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 1.06%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 1.06%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 1.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 1.06%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 1.06%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.06%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 1.06%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.06%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 1.06%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB DIMM DDR4 2400MT/s           | 1         | 1.06%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                       | 1         | 1.06%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1         | 1.06%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.06%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                      | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 48        | 66.67%  |
| DDR3   | 20        | 27.78%  |
| SDRAM  | 2         | 2.78%   |
| LPDDR4 | 1         | 1.39%   |
| LPDDR3 | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 56.34%  |
| DIMM         | 30        | 42.25%  |
| Row Of Chips | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 35.44%  |
| 16384 | 21        | 26.58%  |
| 4096  | 17        | 21.52%  |
| 32768 | 11        | 13.92%  |
| 65536 | 1         | 1.27%   |
| 2048  | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 17        | 21.79%  |
| 1600  | 16        | 20.51%  |
| 2667  | 13        | 16.67%  |
| 2400  | 10        | 12.82%  |
| 2133  | 6         | 7.69%   |
| 1333  | 6         | 7.69%   |
| 3600  | 3         | 3.85%   |
| 3266  | 2         | 2.56%   |
| 3933  | 1         | 1.28%   |
| 2933  | 1         | 1.28%   |
| 2666  | 1         | 1.28%   |
| 2472  | 1         | 1.28%   |
| 1334  | 1         | 1.28%   |

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
| Chicony Electronics                    | 40        | 29.41%  |
| IMC Networks                           | 19        | 13.97%  |
| Bison Electronics                      | 11        | 8.09%   |
| Realtek Semiconductor                  | 10        | 7.35%   |
| Logitech                               | 9         | 6.62%   |
| Microdia                               | 7         | 5.15%   |
| Sunplus Innovation Technology          | 6         | 4.41%   |
| Hopewin Electronic Material            | 4         | 2.94%   |
| Acer                                   | 4         | 2.94%   |
| Suyin                                  | 3         | 2.21%   |
| Samsung Electronics                    | 3         | 2.21%   |
| Lite-On Technology                     | 3         | 2.21%   |
| Ruision                                | 2         | 1.47%   |
| Microsoft                              | 2         | 1.47%   |
| Generalplus Technology                 | 2         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.47%   |
| Syntek                                 | 1         | 0.74%   |
| Remo Tech                              | 1         | 0.74%   |
| Quanta                                 | 1         | 0.74%   |
| Luxvisions Innotech Limited            | 1         | 0.74%   |
| Lenovo                                 | 1         | 0.74%   |
| KYE Systems (Mouse Systems)            | 1         | 0.74%   |
| Jieli Technology                       | 1         | 0.74%   |
| Creative Technology                    | 1         | 0.74%   |
| ARC International                      | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 21        | 15.11%  |
| IMC Networks Integrated Camera                    | 17        | 12.23%  |
| Realtek Integrated_Webcam_HD                      | 7         | 5.04%   |
| Bison Integrated Camera                           | 6         | 4.32%   |
| Bison SunplusIT Integrated Camera                 | 5         | 3.6%    |
| Logitech HD Pro Webcam C920                       | 4         | 2.88%   |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 4         | 2.88%   |
| Chicony Integrated Camera (1280x720@30)           | 4         | 2.88%   |
| Sunplus Integrated_Webcam_HD                      | 3         | 2.16%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 2.16%   |
| Lite-On Integrated Camera                         | 3         | 2.16%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 2.16%   |
| Chicony HP HD Camera                              | 3         | 2.16%   |
| Ruision UVC Camera                                | 2         | 1.44%   |
| Microdia Webcam                                   | 2         | 1.44%   |
| Microdia Integrated Webcam                        | 2         | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 2         | 1.44%   |
| Generalplus GENERAL WEBCAM                        | 2         | 1.44%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.44%   |
| Bison Integrated IR Camera                        | 2         | 1.44%   |
| Acer Integrated Camera                            | 2         | 1.44%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.72%   |
| Suyin RGBIR Camera                                | 1         | 0.72%   |
| Suyin Integrated_Webcam_HD                        | 1         | 0.72%   |
| Suyin HP Truevision HD                            | 1         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.72%   |
| Sunplus Integrated Webcam                         | 1         | 0.72%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.72%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.72%   |
| Realtek USB Camera                                | 1         | 0.72%   |
| Realtek ICT Camera                                | 1         | 0.72%   |
| Quanta HP HD Camera                               | 1         | 0.72%   |
| Microsoft LifeCam HD-3000                         | 1         | 0.72%   |
| Microsoft LifeCam Cinema                          | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_E4HD            | 1         | 0.72%   |
| Microdia Integrated_Webcam_HD                     | 1         | 0.72%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.72%   |
| Logitech Webcam C925e                             | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 33        | 62.26%  |
| Validity Sensors           | 14        | 26.42%  |
| Shenzhen Goodix Technology | 3         | 5.66%   |
| Upek                       | 2         | 3.77%   |
| Elan Microelectronics      | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 45.28%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.32%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.89%   |
| Validity Sensors VFS491                                                    | 1         | 1.89%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.89%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.89%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.89%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 35.29%  |
| Alcor Micro           | 5         | 29.41%  |
| Lenovo                | 2         | 11.76%  |
| Yubico.com            | 1         | 5.88%   |
| Upek                  | 1         | 5.88%   |
| SCM Microsystems      | 1         | 5.88%   |
| Gemalto (was Gemplus) | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 29.41%  |
| Broadcom 58200                                             | 3         | 17.65%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 11.76%  |
| Broadcom 5880                                              | 2         | 11.76%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.88%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 90        | 48.39%  |
| 1     | 74        | 39.78%  |
| 2     | 16        | 8.6%    |
| 3     | 4         | 2.15%   |
| 5     | 1         | 0.54%   |
| 4     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 43.44%  |
| Graphics card            | 17        | 13.93%  |
| Chipcard                 | 11        | 9.02%   |
| Unassigned class         | 9         | 7.38%   |
| Net/wireless             | 9         | 7.38%   |
| Multimedia controller    | 4         | 3.28%   |
| Communication controller | 4         | 3.28%   |
| Card reader              | 4         | 3.28%   |
| Bluetooth                | 4         | 3.28%   |
| Storage                  | 2         | 1.64%   |
| Net/ethernet             | 2         | 1.64%   |
| Storage/ide              | 1         | 0.82%   |
| Sound                    | 1         | 0.82%   |
| Network                  | 1         | 0.82%   |

