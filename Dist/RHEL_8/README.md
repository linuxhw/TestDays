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

Total: 319

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [10ff3b22cf](https://linux-hardware.org/?probe=10ff3b22cf) | Apr 03, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [896bd3d75a](https://linux-hardware.org/?probe=896bd3d75a) | Apr 03, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [59749a8b22](https://linux-hardware.org/?probe=59749a8b22) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [24f8aa7cd0](https://linux-hardware.org/?probe=24f8aa7cd0) | Mar 07, 2024 |
| Dell          | 06JWJY A00                  | Desktop     | [f1c6a0f9dd](https://linux-hardware.org/?probe=f1c6a0f9dd) | Mar 06, 2024 |
| Dell          | Latitude 5340               | Notebook    | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5c4714ecce](https://linux-hardware.org/?probe=5c4714ecce) | Dec 01, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [2ed4b6b711](https://linux-hardware.org/?probe=2ed4b6b711) | Oct 24, 2023 |
| Intel         | NUC12SNKi72 M78939-500      | Mini pc     | [1b04f5768f](https://linux-hardware.org/?probe=1b04f5768f) | Oct 24, 2023 |
| Intel         | NUC12SNKi72 M78939-500      | Mini pc     | [eb48924942](https://linux-hardware.org/?probe=eb48924942) | Oct 24, 2023 |
| Dell          | 03X6X0 A01                  | Server      | [eb082ebcfc](https://linux-hardware.org/?probe=eb082ebcfc) | Oct 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| HP            | 8955                        | Mini pc     | [b80c4d0245](https://linux-hardware.org/?probe=b80c4d0245) | Aug 28, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 14        | 5.91%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 5.91%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 12        | 5.06%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 4.64%   |
| 4.18.0-305.el8.x86_64        | 10        | 4.22%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 10        | 4.22%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 3.8%    |
| 4.18.0-348.12.2.el8_5.x86_64 | 9         | 3.8%    |
| 4.18.0-425.10.1.el8_7.x86_64 | 8         | 3.38%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 3.38%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 8         | 3.38%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 7         | 2.95%   |
| 4.18.0-193.el8.x86_64        | 7         | 2.95%   |
| 4.18.0-425.3.1.el8.x86_64    | 6         | 2.53%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 6         | 2.53%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 6         | 2.53%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 2.53%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6         | 2.53%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 2.11%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 2.11%   |
| 4.18.0-372.9.1.el8.x86_64    | 4         | 1.69%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4         | 1.69%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 1.69%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4         | 1.69%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 1.69%   |
| 4.18.0-147.el8.x86_64        | 4         | 1.69%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 1.27%   |
| 4.18.0-513.18.1.el8_9.x86_64 | 2         | 0.84%   |
| 4.18.0-477.27.1.el8_8.x86_64 | 2         | 0.84%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2         | 0.84%   |
| 4.18.0-477.15.1.el8_8.x86_64 | 2         | 0.84%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 2         | 0.84%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 0.84%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 2         | 0.84%   |
| 4.18.0-348.el8.x86_64        | 2         | 0.84%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 2         | 0.84%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 2         | 0.84%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 0.84%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 2         | 0.84%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 190       | 96.94%  |
| 5.9.1    | 1         | 0.51%   |
| 5.13.13  | 1         | 0.51%   |
| 5.13.0   | 1         | 0.51%   |
| 5.10.6   | 1         | 0.51%   |
| 4.19.150 | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 190       | 96.94%  |
| 5.13    | 2         | 1.02%   |
| 5.9     | 1         | 0.51%   |
| 5.10    | 1         | 0.51%   |
| 4.19    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 195       | 99.49%  |
| Unknown | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 166       | 81.77%  |
| Unknown       | 20        | 9.85%   |
| GNOME Classic | 9         | 4.43%   |
| KDE5          | 5         | 2.46%   |
| KDE           | 2         | 0.99%   |
| MATE          | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 112       | 55.17%  |
| Wayland | 81        | 39.9%   |
| Unknown | 10        | 4.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 149       | 72.68%  |
| GDM     | 54        | 26.34%  |
| SDDM    | 1         | 0.49%   |
| LightDM | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 134       | 66.67%  |
| Unknown | 13        | 6.47%   |
| en_GB   | 12        | 5.97%   |
| de_DE   | 5         | 2.49%   |
| pl_PL   | 4         | 1.99%   |
| fr_FR   | 4         | 1.99%   |
| en_IN   | 4         | 1.99%   |
| ru_RU   | 3         | 1.49%   |
| pt_BR   | 2         | 1%      |
| nl_NL   | 2         | 1%      |
| es_ES   | 2         | 1%      |
| es_AR   | 2         | 1%      |
| en_IE   | 2         | 1%      |
| sl_SI   | 1         | 0.5%    |
| nl_BE   | 1         | 0.5%    |
| ko_KR   | 1         | 0.5%    |
| ja_JP   | 1         | 0.5%    |
| it_IT   | 1         | 0.5%    |
| es_MX   | 1         | 0.5%    |
| es_EC   | 1         | 0.5%    |
| es_CO   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| en_DK   | 1         | 0.5%    |
| de_CH   | 1         | 0.5%    |
| cs_CZ   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 158       | 79%     |
| BIOS | 42        | 21%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 173       | 86.93%  |
| Ext4    | 18        | 9.05%   |
| Unknown | 8         | 4.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 137       | 67.16%  |
| GPT     | 62        | 30.39%  |
| MBR     | 5         | 2.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 182       | 91.46%  |
| Yes       | 17        | 8.54%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 179       | 89.5%   |
| Yes       | 21        | 10.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 80        | 40.82%  |
| Dell                | 30        | 15.31%  |
| Hewlett-Packard     | 27        | 13.78%  |
| ASUSTek Computer    | 21        | 10.71%  |
| Gigabyte Technology | 9         | 4.59%   |
| ASRock              | 5         | 2.55%   |
| MSI                 | 4         | 2.04%   |
| Supermicro          | 3         | 1.53%   |
| Intel               | 3         | 1.53%   |
| Sony                | 2         | 1.02%   |
| Unknown             | 2         | 1.02%   |
| TUXEDO              | 1         | 0.51%   |
| Toshiba             | 1         | 0.51%   |
| Timi                | 1         | 0.51%   |
| IBM                 | 1         | 0.51%   |
| Getac               | 1         | 0.51%   |
| CX / Air Computers. | 1         | 0.51%   |
| AZW                 | 1         | 0.51%   |
| AMI                 | 1         | 0.51%   |
| Alienware           | 1         | 0.51%   |
| Acer                | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X        | 4         | 2.04%   |
| ASUS All Series                            | 4         | 2.04%   |
| Unknown                                    | 3         | 1.53%   |
| Supermicro X10DRi                          | 2         | 1.02%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401   | 2         | 1.02%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00   | 2         | 1.02%   |
| Lenovo ThinkPad T590 20N5S2NC0N            | 2         | 1.02%   |
| Lenovo ThinkPad T490s 20NYS7K91R           | 2         | 1.02%   |
| Lenovo ThinkPad T480s 20L8S2N800           | 2         | 1.02%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08      | 2         | 1.02%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q        | 2         | 1.02%   |
| HP EliteBook 8460p                         | 2         | 1.02%   |
| Dell Latitude E6430                        | 2         | 1.02%   |
| Dell Latitude 5300                         | 2         | 1.02%   |
| TUXEDO N13xWU                              | 1         | 0.51%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.51%   |
| Timi TM1707                                | 1         | 0.51%   |
| Supermicro X7DW3                           | 1         | 0.51%   |
| Sony VPCEB4L1R                             | 1         | 0.51%   |
| Sony VPCEB23FM                             | 1         | 0.51%   |
| MSI MS-7B51                                | 1         | 0.51%   |
| MSI MS-7B33                                | 1         | 0.51%   |
| MSI MS-7A37                                | 1         | 0.51%   |
| MSI MS-7752                                | 1         | 0.51%   |
| Lenovo Z40-70 20366                        | 1         | 0.51%   |
| Lenovo Yoga C640-13IML 81UE                | 1         | 0.51%   |
| Lenovo ThinkSystem SR645                   | 1         | 0.51%   |
| Lenovo ThinkPad X390 Yoga 20NQS18Y00       | 1         | 0.51%   |
| Lenovo ThinkPad X270 20HN001EMC            | 1         | 0.51%   |
| Lenovo ThinkPad X250 20CLS0H807            | 1         | 0.51%   |
| Lenovo ThinkPad X230 Tablet 34373KU        | 1         | 0.51%   |
| Lenovo ThinkPad X201 3680PKS               | 1         | 0.51%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100     | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G | 1         | 0.51%   |
| Lenovo ThinkPad W530 2441B32               | 1         | 0.51%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 0.51%   |
| Lenovo ThinkPad T590 20N5S2NC0V            | 1         | 0.51%   |
| Lenovo ThinkPad T590 20N5S2NC00            | 1         | 0.51%   |
| Lenovo ThinkPad T520 42404CG               | 1         | 0.51%   |
| Lenovo ThinkPad T490s 20NYS7K905           | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 70        | 35.71%  |
| Dell Precision     | 11        | 5.61%   |
| Dell Latitude      | 10        | 5.1%    |
| HP EliteBook       | 5         | 2.55%   |
| HP ZBook           | 4         | 2.04%   |
| ASUS All           | 4         | 2.04%   |
| Lenovo ThinkCentre | 3         | 1.53%   |
| Dell Inspiron      | 3         | 1.53%   |
| ASUS ROG           | 3         | 1.53%   |
| ASUS PRIME         | 3         | 1.53%   |
| Unknown            | 3         | 1.53%   |
| Supermicro X10DRi  | 2         | 1.02%   |
| HP Z230            | 2         | 1.02%   |
| HP ProBook         | 2         | 1.02%   |
| Dell PowerEdge     | 2         | 1.02%   |
| ASUS VivoBook      | 2         | 1.02%   |
| TUXEDO N13xWU      | 1         | 0.51%   |
| Toshiba Satellite  | 1         | 0.51%   |
| Timi TM1707        | 1         | 0.51%   |
| Supermicro X7DW3   | 1         | 0.51%   |
| Sony VPCEB4L1R     | 1         | 0.51%   |
| Sony VPCEB23FM     | 1         | 0.51%   |
| MSI MS-7B51        | 1         | 0.51%   |
| MSI MS-7B33        | 1         | 0.51%   |
| MSI MS-7A37        | 1         | 0.51%   |
| MSI MS-7752        | 1         | 0.51%   |
| Lenovo Z40-70      | 1         | 0.51%   |
| Lenovo Yoga        | 1         | 0.51%   |
| Lenovo ThinkSystem | 1         | 0.51%   |
| Lenovo S40-40      | 1         | 0.51%   |
| Lenovo Legion      | 1         | 0.51%   |
| Lenovo 10SFS03200  | 1         | 0.51%   |
| Intel NUC12SNKi72  | 1         | 0.51%   |
| Intel NUC10i7FNK   | 1         | 0.51%   |
| Intel DX79SR       | 1         | 0.51%   |
| IBM FAB2           | 1         | 0.51%   |
| HP Z840            | 1         | 0.51%   |
| HP Z620            | 1         | 0.51%   |
| HP Z440            | 1         | 0.51%   |
| HP Z1              | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 37        | 18.88%  |
| 2019 | 34        | 17.35%  |
| 2018 | 27        | 13.78%  |
| 2015 | 15        | 7.65%   |
| 2012 | 14        | 7.14%   |
| 2017 | 13        | 6.63%   |
| 2016 | 13        | 6.63%   |
| 2021 | 12        | 6.12%   |
| 2011 | 8         | 4.08%   |
| 2013 | 7         | 3.57%   |
| 2014 | 6         | 3.06%   |
| 2022 | 4         | 2.04%   |
| 2010 | 3         | 1.53%   |
| 2023 | 2         | 1.02%   |
| 2009 | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 121       | 61.73%  |
| Desktop     | 56        | 28.57%  |
| Server      | 8         | 4.08%   |
| Mini pc     | 6         | 3.06%   |
| Convertible | 4         | 2.04%   |
| All in one  | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 171       | 86.36%  |
| Enabled  | 27        | 13.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 196       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 62        | 30.54%  |
| 16.01-24.0      | 33        | 16.26%  |
| 8.01-16.0       | 33        | 16.26%  |
| 4.01-8.0        | 29        | 14.29%  |
| 64.01-256.0     | 29        | 14.29%  |
| 24.01-32.0      | 8         | 3.94%   |
| 3.01-4.0        | 6         | 2.96%   |
| More than 256.0 | 2         | 0.99%   |
| Unknown         | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 82        | 36.77%  |
| 2.01-3.0        | 40        | 17.94%  |
| 8.01-16.0       | 36        | 16.14%  |
| 3.01-4.0        | 35        | 15.7%   |
| 1.01-2.0        | 15        | 6.73%   |
| 16.01-24.0      | 5         | 2.24%   |
| 24.01-32.0      | 4         | 1.79%   |
| 0.51-1.0        | 3         | 1.35%   |
| More than 256.0 | 1         | 0.45%   |
| 32.01-64.0      | 1         | 0.45%   |
| Unknown         | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 59.02%  |
| 2      | 46        | 22.44%  |
| 3      | 18        | 8.78%   |
| 4      | 8         | 3.9%    |
| 5      | 4         | 1.95%   |
| 8      | 2         | 0.98%   |
| 7      | 2         | 0.98%   |
| 6      | 2         | 0.98%   |
| 10     | 1         | 0.49%   |
| 0      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 78.28%  |
| Yes       | 43        | 21.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 90.86%  |
| No        | 18        | 9.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 81.12%  |
| No        | 37        | 18.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 65.84%  |
| No        | 69        | 34.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 44        | 22.45%  |
| India        | 17        | 8.67%   |
| UK           | 14        | 7.14%   |
| Germany      | 12        | 6.12%   |
| Czechia      | 11        | 5.61%   |
| France       | 6         | 3.06%   |
| Canada       | 6         | 3.06%   |
| Poland       | 5         | 2.55%   |
| Switzerland  | 4         | 2.04%   |
| Netherlands  | 4         | 2.04%   |
| Mexico       | 4         | 2.04%   |
| Italy        | 4         | 2.04%   |
| Brazil       | 4         | 2.04%   |
| Spain        | 3         | 1.53%   |
| South Africa | 3         | 1.53%   |
| Russia       | 3         | 1.53%   |
| Lithuania    | 3         | 1.53%   |
| Finland      | 3         | 1.53%   |
| Australia    | 3         | 1.53%   |
| Argentina    | 3         | 1.53%   |
| Ukraine      | 2         | 1.02%   |
| South Korea  | 2         | 1.02%   |
| Romania      | 2         | 1.02%   |
| Japan        | 2         | 1.02%   |
| Egypt        | 2         | 1.02%   |
| Colombia     | 2         | 1.02%   |
| China        | 2         | 1.02%   |
| Chile        | 2         | 1.02%   |
| Turkmenistan | 1         | 0.51%   |
| Sweden       | 1         | 0.51%   |
| Slovenia     | 1         | 0.51%   |
| Singapore    | 1         | 0.51%   |
| Saudi Arabia | 1         | 0.51%   |
| Portugal     | 1         | 0.51%   |
| Pakistan     | 1         | 0.51%   |
| New Zealand  | 1         | 0.51%   |
| Nepal        | 1         | 0.51%   |
| Myanmar      | 1         | 0.51%   |
| Morocco      | 1         | 0.51%   |
| Luxembourg   | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Prague            | 9         | 4.31%   |
| Turku             | 3         | 1.44%   |
| San Jose          | 3         | 1.44%   |
| Munich            | 3         | 1.44%   |
| Mexico City       | 3         | 1.44%   |
| Berlin            | 3         | 1.44%   |
| Bengaluru         | 3         | 1.44%   |
| Montreal          | 2         | 0.96%   |
| Milan             | 2         | 0.96%   |
| Leeds             | 2         | 0.96%   |
| Kyiv              | 2         | 0.96%   |
| Didcot            | 2         | 0.96%   |
| Des Moines        | 2         | 0.96%   |
| Chicago           | 2         | 0.96%   |
| Chennai           | 2         | 0.96%   |
| Zaragoza          | 1         | 0.48%   |
| Yongin-si         | 1         | 0.48%   |
| Wroclaw           | 1         | 0.48%   |
| Wiesbaden         | 1         | 0.48%   |
| Webster           | 1         | 0.48%   |
| Wayne             | 1         | 0.48%   |
| Wagholi           | 1         | 0.48%   |
| Vardenis          | 1         | 0.48%   |
| Vaglio            | 1         | 0.48%   |
| Udaipur           | 1         | 0.48%   |
| Toronto           | 1         | 0.48%   |
| Tiruchi           | 1         | 0.48%   |
| Temuco            | 1         | 0.48%   |
| Temara            | 1         | 0.48%   |
| Tauranga          | 1         | 0.48%   |
| Taringa           | 1         | 0.48%   |
| Talkha            | 1         | 0.48%   |
| Syracuse          | 1         | 0.48%   |
| Suffolk           | 1         | 0.48%   |
| Stuttgart         | 1         | 0.48%   |
| Streatham         | 1         | 0.48%   |
| Stellenbosch      | 1         | 0.48%   |
| Steamboat Springs | 1         | 0.48%   |
| Spokane           | 1         | 0.48%   |
| Sofia             | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 59        | 105    | 19.73%  |
| WDC                         | 36        | 61     | 12.04%  |
| Seagate                     | 30        | 46     | 10.03%  |
| Toshiba                     | 25        | 32     | 8.36%   |
| SK hynix                    | 17        | 21     | 5.69%   |
| Sandisk                     | 17        | 27     | 5.69%   |
| Kingston                    | 16        | 21     | 5.35%   |
| Intel                       | 13        | 21     | 4.35%   |
| Micron Technology           | 11        | 18     | 3.68%   |
| Crucial                     | 10        | 14     | 3.34%   |
| Unknown                     | 8         | 10     | 2.68%   |
| A-DATA Technology           | 6         | 6      | 2.01%   |
| HGST                        | 4         | 4      | 1.34%   |
| Hewlett-Packard             | 4         | 6      | 1.34%   |
| Silicon Motion              | 3         | 4      | 1%      |
| PNY                         | 3         | 4      | 1%      |
| Phison                      | 3         | 7      | 1%      |
| Lenovo                      | 3         | 3      | 1%      |
| Hitachi                     | 3         | 3      | 1%      |
| Gigabyte Technology         | 3         | 4      | 1%      |
| Corsair                     | 3         | 6      | 1%      |
| KIOXIA                      | 2         | 2      | 0.67%   |
| XPG                         | 1         | 1      | 0.33%   |
| Western Digital             | 1         | 1      | 0.33%   |
| UMIS                        | 1         | 1      | 0.33%   |
| Team                        | 1         | 2      | 0.33%   |
| T-FORCE                     | 1         | 2      | 0.33%   |
| SSSTC                       | 1         | 1      | 0.33%   |
| SMI                         | 1         | 2      | 0.33%   |
| Plextor                     | 1         | 1      | 0.33%   |
| OCZ                         | 1         | 2      | 0.33%   |
| Micron/Crucial Technology   | 1         | 1      | 0.33%   |
| Lite-On                     | 1         | 1      | 0.33%   |
| Kingston Technology Company | 1         | 1      | 0.33%   |
| KingFast                    | 1         | 1      | 0.33%   |
| KINGBANK                    | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |
| HPT                         | 1         | 1      | 0.33%   |
| Hoodisk                     | 1         | 1      | 0.33%   |
| DELLBOSS                    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                      | 10        | 2.96%   |
| Samsung NVMe SSD Drive 512GB                       | 7         | 2.07%   |
| Toshiba NVMe SSD Drive 256GB                       | 6         | 1.78%   |
| SanDisk NVMe SSD Drive 256GB                       | 6         | 1.78%   |
| Samsung SSD 860 EVO 1TB                            | 6         | 1.78%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 6         | 1.78%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 1.48%   |
| Samsung NVMe SSD Drive 500GB                       | 4         | 1.18%   |
| Toshiba NVMe SSD Drive 512GB                       | 3         | 0.89%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.89%   |
| Micron NVMe SSD Drive 256GB                        | 3         | 0.89%   |
| Kingston SA400S37480G 480GB SSD                    | 3         | 0.89%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.89%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 0.89%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 2         | 0.59%   |
| WDC WD1002FAEX-00Z3A0 1TB                          | 2         | 0.59%   |
| Unknown NVMe SSD Drive 256GB                       | 2         | 0.59%   |
| Unknown MMC Card  16GB                             | 2         | 0.59%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 2         | 0.59%   |
| Toshiba KXG6AZNV256G 256GB                         | 2         | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                    | 2         | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB                     | 2         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.59%   |
| Seagate ST1000DM003-9YN162 1TB                     | 2         | 0.59%   |
| Seagate Expansion 2TB                              | 2         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.59%   |
| Samsung SSD 860 QVO 1TB                            | 2         | 0.59%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.59%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.59%   |
| Samsung Portable SSD T5 500GB                      | 2         | 0.59%   |
| Samsung NVMe SSD Drive 2TB                         | 2         | 0.59%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 0.59%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                     | 2         | 0.59%   |
| Kingston SUV500120G 120GB SSD                      | 2         | 0.59%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 0.59%   |
| Intel SSDPEL1K100GA 100GB                          | 2         | 0.59%   |
| Intel NVMe SSD Drive 512GB                         | 2         | 0.59%   |
| Intel NVMe SSD Drive 2TB                           | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 45     | 37.97%  |
| WDC                 | 27        | 48     | 34.18%  |
| Toshiba             | 10        | 14     | 12.66%  |
| HGST                | 4         | 4      | 5.06%   |
| Hitachi             | 3         | 3      | 3.8%    |
| Hewlett-Packard     | 2         | 2      | 2.53%   |
| Unknown             | 1         | 1      | 1.27%   |
| Samsung Electronics | 1         | 2      | 1.27%   |
| DELLBOSS            | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 43     | 28.89%  |
| Kingston            | 12        | 16     | 13.33%  |
| Crucial             | 10        | 14     | 11.11%  |
| WDC                 | 6         | 8      | 6.67%   |
| SanDisk             | 6         | 12     | 6.67%   |
| Micron Technology   | 5         | 10     | 5.56%   |
| A-DATA Technology   | 5         | 5      | 5.56%   |
| PNY                 | 3         | 4      | 3.33%   |
| Intel               | 3         | 5      | 3.33%   |
| Corsair             | 3         | 6      | 3.33%   |
| SK hynix            | 2         | 5      | 2.22%   |
| Toshiba             | 1         | 1      | 1.11%   |
| Team                | 1         | 2      | 1.11%   |
| Seagate             | 1         | 1      | 1.11%   |
| Plextor             | 1         | 1      | 1.11%   |
| OCZ                 | 1         | 2      | 1.11%   |
| KINGBANK            | 1         | 1      | 1.11%   |
| Intenso             | 1         | 1      | 1.11%   |
| Hoodisk             | 1         | 1      | 1.11%   |
| China               | 1         | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 116       | 178    | 42.18%  |
| SSD     | 80        | 139    | 29.09%  |
| HDD     | 70        | 120    | 25.45%  |
| MMC     | 5         | 6      | 1.82%   |
| Unknown | 4         | 6      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 116       | 178    | 47.93%  |
| SATA | 104       | 239    | 42.98%  |
| SAS  | 17        | 26     | 7.02%   |
| MMC  | 5         | 6      | 2.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 120    | 44.94%  |
| 0.51-1.0   | 50        | 80     | 31.65%  |
| 1.01-2.0   | 22        | 29     | 13.92%  |
| 3.01-4.0   | 9         | 19     | 5.7%    |
| 4.01-10.0  | 4         | 9      | 2.53%   |
| 2.01-3.0   | 1         | 1      | 0.63%   |
| 10.01-20.0 | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 35.27%  |
| 251-500        | 36        | 17.39%  |
| 501-1000       | 33        | 15.94%  |
| 1001-2000      | 18        | 8.7%    |
| More than 3000 | 17        | 8.21%   |
| 2001-3000      | 11        | 5.31%   |
| Unknown        | 8         | 3.86%   |
| 51-100         | 6         | 2.9%    |
| 21-50          | 3         | 1.45%   |
| 1-20           | 2         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 49        | 22.17%  |
| 1-20           | 41        | 18.55%  |
| 101-250        | 38        | 17.19%  |
| 51-100         | 35        | 15.84%  |
| 251-500        | 23        | 10.41%  |
| 501-1000       | 11        | 4.98%   |
| 1001-2000      | 9         | 4.07%   |
| Unknown        | 8         | 3.62%   |
| More than 3000 | 4         | 1.81%   |
| 2001-3000      | 3         | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 16.67%  |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 830 Series 128GB | 1         | 2      | 16.67%  |
| Micron Technology M510_2.5 7MM 256GB SSD | 1         | 1      | 16.67%  |
| Hitachi HDS722020ALA330 2TB              | 1         | 1      | 16.67%  |
| A-DATA Technology SU800NS38 256GB SSD    | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| A-DATA Technology   | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 4      | 50%     |
| HDD  | 3         | 3      | 50%     |

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
| Detected | 145       | 326    | 68.4%   |
| Works    | 61        | 116    | 28.77%  |
| Malfunc  | 6         | 7      | 2.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 110       | 41.83%  |
| Samsung Electronics            | 40        | 15.21%  |
| AMD                            | 17        | 6.46%   |
| SK hynix                       | 15        | 5.7%    |
| Toshiba America Info Systems   | 14        | 5.32%   |
| SanDisk                        | 14        | 5.32%   |
| Micron Technology              | 6         | 2.28%   |
| Silicon Motion                 | 5         | 1.9%    |
| Phison Electronics             | 5         | 1.9%    |
| Marvell Technology Group       | 4         | 1.52%   |
| KIOXIA                         | 4         | 1.52%   |
| Kingston Technology Company    | 4         | 1.52%   |
| Broadcom / LSI                 | 4         | 1.52%   |
| ASMedia Technology             | 4         | 1.52%   |
| Lenovo                         | 3         | 1.14%   |
| LSI Logic / Symbios Logic      | 2         | 0.76%   |
| Biwin Storage Technology       | 2         | 0.76%   |
| ADATA Technology               | 2         | 0.76%   |
| Western Digital                | 1         | 0.38%   |
| Union Memory (Shenzhen)        | 1         | 0.38%   |
| Solid State Storage Technology | 1         | 0.38%   |
| PMC-Sierra                     | 1         | 0.38%   |
| Micron/Crucial Technology      | 1         | 0.38%   |
| Lite-On Technology             | 1         | 0.38%   |
| HighPoint Technologies         | 1         | 0.38%   |
| Hewlett-Packard                | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 10.14%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 3.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 3.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 3.15%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 2.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7         | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.45%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 6         | 2.1%    |
| Intel SATA Controller [RAID Mode]                                              | 6         | 2.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.1%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5         | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.4%    |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 1.4%    |
| Intel SSD 660P Series                                                          | 4         | 1.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.4%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.05%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.05%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.7%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 2         | 0.7%    |
| Phison E12 NVMe Controller                                                     | 2         | 0.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 116       | 45.85%  |
| SATA | 111       | 43.87%  |
| RAID | 16        | 6.32%   |
| SAS  | 6         | 2.37%   |
| IDE  | 4         | 1.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 174       | 88.78%  |
| AMD    | 22        | 11.22%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 5.61%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 5.1%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 3.06%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 2.04%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.53%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1.02%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 2         | 1.02%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1.02%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.02%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1.02%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.02%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.02%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.02%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 1.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.02%   |
| Intel Xeon W-2102 CPU @ 2.90GHz               | 1         | 0.51%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.51%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.51%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.51%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 81        | 41.33%  |
| Intel Core i5      | 38        | 19.39%  |
| Intel Xeon         | 23        | 11.73%  |
| Other              | 13        | 6.63%   |
| Intel Core i3      | 10        | 5.1%    |
| AMD Ryzen 7        | 8         | 4.08%   |
| Intel Core i9      | 5         | 2.55%   |
| AMD Ryzen 9        | 4         | 2.04%   |
| AMD Ryzen 5        | 3         | 1.53%   |
| Intel Pentium Gold | 2         | 1.02%   |
| Intel Pentium      | 2         | 1.02%   |
| AMD Ryzen 3        | 2         | 1.02%   |
| AMD EPYC           | 2         | 1.02%   |
| AMD Ryzen 7 PRO    | 1         | 0.51%   |
| AMD FX             | 1         | 0.51%   |
| AMD A10            | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 86        | 43.88%  |
| 2      | 41        | 20.92%  |
| 6      | 32        | 16.33%  |
| 8      | 17        | 8.67%   |
| 12     | 6         | 3.06%   |
| 16     | 4         | 2.04%   |
| 10     | 3         | 1.53%   |
| 20     | 2         | 1.02%   |
| 96     | 1         | 0.51%   |
| 64     | 1         | 0.51%   |
| 36     | 1         | 0.51%   |
| 24     | 1         | 0.51%   |
| 14     | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 94.9%   |
| 2      | 10        | 5.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 169       | 85.79%  |
| 1      | 28        | 14.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 192       | 96.97%  |
| Unknown        | 6         | 3.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 29        | 14.65%  |
| 0x906ea    | 14        | 7.07%   |
| 0x806ea    | 14        | 7.07%   |
| 0xa0652    | 12        | 6.06%   |
| 0x306c3    | 12        | 6.06%   |
| 0x306a9    | 11        | 5.56%   |
| Unknown    | 10        | 5.05%   |
| 0x206a7    | 8         | 4.04%   |
| 0x906ed    | 7         | 3.54%   |
| 0x506e3    | 7         | 3.54%   |
| 0x406e3    | 7         | 3.54%   |
| 0x806c1    | 6         | 3.03%   |
| 0x906e9    | 5         | 2.53%   |
| 0x306f2    | 5         | 2.53%   |
| 0x806e9    | 4         | 2.02%   |
| 0x806d1    | 3         | 1.52%   |
| 0x406f1    | 3         | 1.52%   |
| 0x306d4    | 3         | 1.52%   |
| 0x20655    | 3         | 1.52%   |
| 0x0a50000c | 3         | 1.52%   |
| 0x08600103 | 3         | 1.52%   |
| 0x08108102 | 3         | 1.52%   |
| 0x40651    | 2         | 1.01%   |
| 0x206d7    | 2         | 1.01%   |
| 0x08701021 | 2         | 1.01%   |
| 0x08701013 | 2         | 1.01%   |
| 0xa0671    | 1         | 0.51%   |
| 0xa0660    | 1         | 0.51%   |
| 0xa0655    | 1         | 0.51%   |
| 0x906eb    | 1         | 0.51%   |
| 0x906a3    | 1         | 0.51%   |
| 0x90675    | 1         | 0.51%   |
| 0x306e4    | 1         | 0.51%   |
| 0x20652    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x0a001119 | 1         | 0.51%   |
| 0x08600106 | 1         | 0.51%   |
| 0x08600104 | 1         | 0.51%   |
| 0x08301034 | 1         | 0.51%   |
| 0x0810100b | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 75        | 38.07%  |
| Haswell          | 20        | 10.15%  |
| CometLake        | 16        | 8.12%   |
| Skylake          | 15        | 7.61%   |
| IvyBridge        | 13        | 6.6%    |
| Zen 2            | 10        | 5.08%   |
| SandyBridge      | 10        | 5.08%   |
| TigerLake        | 6         | 3.05%   |
| Broadwell        | 6         | 3.05%   |
| Westmere         | 4         | 2.03%   |
| Icelake          | 4         | 2.03%   |
| Unknown          | 4         | 2.03%   |
| Zen+             | 3         | 1.52%   |
| Zen 3            | 3         | 1.52%   |
| Zen              | 3         | 1.52%   |
| Alderlake Hybrid | 2         | 1.02%   |
| Steamroller      | 1         | 0.51%   |
| Piledriver       | 1         | 0.51%   |
| Penryn           | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 132       | 55%     |
| Nvidia                     | 73        | 30.42%  |
| AMD                        | 28        | 11.67%  |
| Matrox Electronics Systems | 5         | 2.08%   |
| ASPEED Technology          | 2         | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 15        | 6.15%   |
| Intel UHD Graphics 620                                                      | 14        | 5.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 14        | 5.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 12        | 4.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 2.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 2.46%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 2.05%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 5         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.64%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.23%   |
| Intel HD Graphics 630                                                       | 3         | 1.23%   |
| Intel HD Graphics 620                                                       | 3         | 1.23%   |
| Intel HD Graphics 5500                                                      | 3         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.82%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.82%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.82%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.82%   |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.82%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.82%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.82%   |
| Intel HD Graphics 530                                                       | 2         | 0.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.82%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2         | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 95        | 47.74%  |
| 1 x Nvidia              | 39        | 19.6%   |
| Intel + Nvidia          | 26        | 13.07%  |
| 1 x AMD                 | 17        | 8.54%   |
| Intel + AMD             | 6         | 3.02%   |
| 1 x Matrox              | 4         | 2.01%   |
| AMD + Nvidia            | 4         | 2.01%   |
| 2 x Nvidia              | 2         | 1.01%   |
| Other                   | 1         | 0.5%    |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.5%    |
| 2 x Intel               | 1         | 0.5%    |
| 2 x AMD                 | 1         | 0.5%    |
| Nvidia + Matrox         | 1         | 0.5%    |
| Nvidia + ASPEED         | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 156       | 78.39%  |
| Proprietary | 33        | 16.58%  |
| Unknown     | 10        | 5.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 60.4%   |
| 1.01-2.0   | 19        | 9.41%   |
| 3.01-4.0   | 16        | 7.92%   |
| 7.01-8.0   | 10        | 4.95%   |
| 0.51-1.0   | 10        | 4.95%   |
| 0.01-0.5   | 9         | 4.46%   |
| 5.01-6.0   | 7         | 3.47%   |
| 2.01-3.0   | 4         | 1.98%   |
| 8.01-16.0  | 3         | 1.49%   |
| 4.01-5.0   | 2         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 11.74%  |
| Samsung Electronics     | 24        | 9.72%   |
| Dell                    | 24        | 9.72%   |
| Lenovo                  | 23        | 9.31%   |
| BOE                     | 23        | 9.31%   |
| LG Display              | 20        | 8.1%    |
| Chimei Innolux          | 20        | 8.1%    |
| Hewlett-Packard         | 15        | 6.07%   |
| Goldstar                | 14        | 5.67%   |
| Sharp                   | 5         | 2.02%   |
| Acer                    | 5         | 2.02%   |
| Philips                 | 4         | 1.62%   |
| InfoVision              | 4         | 1.62%   |
| Eizo                    | 4         | 1.62%   |
| BenQ                    | 4         | 1.62%   |
| PANDA                   | 3         | 1.21%   |
| Ancor Communications    | 3         | 1.21%   |
| ViewSonic               | 2         | 0.81%   |
| LGD                     | 2         | 0.81%   |
| Lenovo Group Limited    | 2         | 0.81%   |
| Iiyama                  | 2         | 0.81%   |
| Gigabyte Technology     | 2         | 0.81%   |
| AOC                     | 2         | 0.81%   |
| Unknown                 | 2         | 0.81%   |
| Sun                     | 1         | 0.4%    |
| Sceptre Tech            | 1         | 0.4%    |
| Planar                  | 1         | 0.4%    |
| Microstep               | 1         | 0.4%    |
| LG Electronics          | 1         | 0.4%    |
| Insignia                | 1         | 0.4%    |
| EVE                     | 1         | 0.4%    |
| Chi Mei Optoelectronics | 1         | 0.4%    |
| BOE Technology Group    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.62%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.87%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.87%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 5         | 1.87%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 1.12%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 1.12%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 3         | 1.12%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 3         | 1.12%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 1.12%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 3         | 1.12%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 1.12%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 3         | 1.12%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 2         | 0.75%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.75%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.75%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.75%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.75%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch              | 2         | 0.75%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.75%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.75%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.75%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch        | 2         | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 2         | 0.75%   |
| Unknown                                                           | 2         | 0.75%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch     | 1         | 0.37%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch     | 1         | 0.37%   |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch             | 1         | 0.37%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch           | 1         | 0.37%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch           | 1         | 0.37%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 1         | 0.37%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch           | 1         | 0.37%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch           | 1         | 0.37%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch    | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 53.18%  |
| 1366x768 (WXGA)    | 19        | 8.64%   |
| 3840x2160 (4K)     | 17        | 7.73%   |
| 2560x1440 (QHD)    | 16        | 7.27%   |
| 1600x900 (HD+)     | 11        | 5%      |
| 1920x1200 (WUXGA)  | 7         | 3.18%   |
| 3440x1440          | 5         | 2.27%   |
| Unknown            | 5         | 2.27%   |
| 3840x1080          | 4         | 1.82%   |
| 2560x1080          | 4         | 1.82%   |
| 3840x1200          | 2         | 0.91%   |
| 1680x1050 (WSXGA+) | 2         | 0.91%   |
| 1440x900 (WXGA+)   | 2         | 0.91%   |
| 9600x2160          | 1         | 0.45%   |
| 7680x2160          | 1         | 0.45%   |
| 6400x2160          | 1         | 0.45%   |
| 3840x1600          | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2560x1600          | 1         | 0.45%   |
| 2048x1152          | 1         | 0.45%   |
| 1280x800 (WXGA)    | 1         | 0.45%   |
| 1280x720 (HD)      | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 19.51%  |
| 14      | 35        | 14.23%  |
| 24      | 27        | 10.98%  |
| 27      | 25        | 10.16%  |
| 13      | 22        | 8.94%   |
| 23      | 17        | 6.91%   |
| Unknown | 16        | 6.5%    |
| 21      | 12        | 4.88%   |
| 34      | 7         | 2.85%   |
| 31      | 6         | 2.44%   |
| 12      | 5         | 2.03%   |
| 20      | 4         | 1.63%   |
| 32      | 3         | 1.22%   |
| 17      | 3         | 1.22%   |
| 54      | 2         | 0.81%   |
| 47      | 2         | 0.81%   |
| 22      | 2         | 0.81%   |
| 18      | 2         | 0.81%   |
| 16      | 2         | 0.81%   |
| 49      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 39      | 1         | 0.41%   |
| 37      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 41.84%  |
| 501-600     | 59        | 24.69%  |
| 401-500     | 20        | 8.37%   |
| Unknown     | 16        | 6.69%   |
| 201-300     | 12        | 5.02%   |
| 601-700     | 11        | 4.6%    |
| 701-800     | 10        | 4.18%   |
| 1001-1500   | 5         | 2.09%   |
| 801-900     | 3         | 1.26%   |
| 351-400     | 3         | 1.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 158       | 79.4%   |
| 16/10   | 17        | 8.54%   |
| Unknown | 14        | 7.04%   |
| 21/9    | 8         | 4.02%   |
| 32/9    | 1         | 0.5%    |
| 3/2     | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 50        | 20.58%  |
| 101-110        | 47        | 19.34%  |
| 201-250        | 46        | 18.93%  |
| 301-350        | 25        | 10.29%  |
| Unknown        | 16        | 6.58%   |
| 351-500        | 15        | 6.17%   |
| 251-300        | 10        | 4.12%   |
| 71-80          | 7         | 2.88%   |
| 151-200        | 7         | 2.88%   |
| 501-1000       | 6         | 2.47%   |
| 61-70          | 5         | 2.06%   |
| 121-130        | 3         | 1.23%   |
| 111-120        | 3         | 1.23%   |
| More than 1000 | 2         | 0.82%   |
| 141-150        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 88        | 37.13%  |
| 51-100        | 68        | 28.69%  |
| 101-120       | 40        | 16.88%  |
| Unknown       | 16        | 6.75%   |
| 161-240       | 15        | 6.33%   |
| More than 240 | 6         | 2.53%   |
| 1-50          | 4         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 61.35%  |
| 2     | 53        | 25.6%   |
| 0     | 15        | 7.25%   |
| 3     | 12        | 5.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 157       | 52.68%  |
| Realtek Semiconductor             | 60        | 20.13%  |
| Lenovo                            | 19        | 6.38%   |
| Qualcomm Atheros                  | 13        | 4.36%   |
| Broadcom                          | 8         | 2.68%   |
| Broadcom Limited                  | 5         | 1.68%   |
| MediaTek                          | 4         | 1.34%   |
| ASIX Electronics                  | 4         | 1.34%   |
| Sierra Wireless                   | 2         | 0.67%   |
| Ralink Technology                 | 2         | 0.67%   |
| Ralink                            | 2         | 0.67%   |
| Marvell Technology Group          | 2         | 0.67%   |
| Huawei Technologies               | 2         | 0.67%   |
| Dell                              | 2         | 0.67%   |
| Aquantia                          | 2         | 0.67%   |
| Xiaomi                            | 1         | 0.34%   |
| TP-Link                           | 1         | 0.34%   |
| Samsung Electronics               | 1         | 0.34%   |
| Qualcomm Atheros Communications   | 1         | 0.34%   |
| Microchip Technology              | 1         | 0.34%   |
| Micro Star International          | 1         | 0.34%   |
| Luminary Micro                    | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| IBM                               | 1         | 0.34%   |
| Google                            | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| DisplayLink                       | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |
| Arduino SA                        | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 9.9%    |
| Intel Wireless 8265 / 8275                                             | 16        | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 16        | 3.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 3.71%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 3.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.72%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 10        | 2.48%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 2.48%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.48%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 2.48%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 2.23%   |
| Intel Wireless 8260                                                    | 7         | 1.73%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.49%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 0.99%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.99%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.99%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.74%   |
| Lenovo USB-C to LAN                                                    | 3         | 0.74%   |
| Lenovo ThinkPad Lan                                                    | 3         | 0.74%   |
| Intel Wireless 7265                                                    | 3         | 0.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.74%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.74%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.74%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.74%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.74%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.74%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter           | 3         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 72.89%  |
| Realtek Semiconductor           | 12        | 7.23%   |
| Qualcomm Atheros                | 12        | 7.23%   |
| Broadcom                        | 5         | 3.01%   |
| MediaTek                        | 4         | 2.41%   |
| Sierra Wireless                 | 2         | 1.2%    |
| Ralink Technology               | 2         | 1.2%    |
| Ralink                          | 2         | 1.2%    |
| TP-Link                         | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Micro Star International        | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| D-Link                          | 1         | 0.6%    |
| Broadcom Limited                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                   | 16        | 9.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                            | 15        | 9.04%   |
| Intel Comet Lake PCH CNVi WiFi                                               | 14        | 8.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                     | 14        | 8.43%   |
| Intel Wi-Fi 6 AX200                                                          | 11        | 6.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 10        | 6.02%   |
| Intel Wireless 8260                                                          | 7         | 4.22%   |
| Intel Wi-Fi 6 AX201                                                          | 6         | 3.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                 | 6         | 3.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                      | 4         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                               | 4         | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 3         | 1.81%   |
| Intel Wireless 7265                                                          | 3         | 1.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                    | 3         | 1.81%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                 | 3         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 2         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 2         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 2         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                   | 2         | 1.2%    |
| Intel Wireless 7260                                                          | 2         | 1.2%    |
| Intel Wireless 3165                                                          | 2         | 1.2%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                       | 1         | 0.6%    |
| Sierra Wireless Sierra Wireless EM7431 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.6%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                              | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                              | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                                   | 1         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                              | 1         | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                              | 1         | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                              | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 1         | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                      | 1         | 0.6%    |
| Ralink RT5572 Wireless Adapter                                               | 1         | 0.6%    |
| Ralink RT5372 Wireless Adapter                                               | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1         | 0.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                    | 1         | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 1         | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                              | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 1         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)               | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 121       | 55.5%   |
| Realtek Semiconductor    | 53        | 24.31%  |
| Lenovo                   | 19        | 8.72%   |
| Broadcom Limited         | 4         | 1.83%   |
| ASIX Electronics         | 4         | 1.83%   |
| Broadcom                 | 3         | 1.38%   |
| Qualcomm Atheros         | 2         | 0.92%   |
| Marvell Technology Group | 2         | 0.92%   |
| Aquantia                 | 2         | 0.92%   |
| Xiaomi                   | 1         | 0.46%   |
| Samsung Electronics      | 1         | 0.46%   |
| ICS Advent               | 1         | 0.46%   |
| IBM                      | 1         | 0.46%   |
| Huawei Technologies      | 1         | 0.46%   |
| Google                   | 1         | 0.46%   |
| DisplayLink              | 1         | 0.46%   |
| Dell                     | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 40        | 17.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 4.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 4.29%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.29%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4.29%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 4.29%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 3.86%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.72%   |
| Intel I350 Gigabit Network Connection                                          | 4         | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.72%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.72%   |
| Lenovo USB-C to LAN                                                            | 3         | 1.29%   |
| Lenovo ThinkPad Lan                                                            | 3         | 1.29%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.29%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.29%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.29%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 1.29%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.29%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.86%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.86%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.86%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.86%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.86%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.86%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.86%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 0.86%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 179       | 52.19%  |
| WiFi     | 159       | 46.36%  |
| Modem    | 5         | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 50.47%  |
| Ethernet | 105       | 49.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 124       | 62.94%  |
| 1     | 54        | 27.41%  |
| 3     | 11        | 5.58%   |
| 4     | 3         | 1.52%   |
| 6     | 2         | 1.02%   |
| 132   | 1         | 0.51%   |
| 22    | 1         | 0.51%   |
| 8     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 88.89%  |
| Yes  | 22        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 71.43%  |
| Cambridge Silicon Radio         | 8         | 6.02%   |
| Broadcom                        | 7         | 5.26%   |
| Qualcomm Atheros Communications | 5         | 3.76%   |
| Realtek Semiconductor           | 4         | 3.01%   |
| IMC Networks                    | 4         | 3.01%   |
| Foxconn / Hon Hai               | 3         | 2.26%   |
| ASUSTek Computer                | 3         | 2.26%   |
| Ralink                          | 1         | 0.75%   |
| Micro Star International        | 1         | 0.75%   |
| MediaTek                        | 1         | 0.75%   |
| Dell                            | 1         | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 33        | 24.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 15.79%  |
| Intel Bluetooth Device                                                              | 17        | 12.78%  |
| Intel AX200 Bluetooth                                                               | 10        | 7.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 6.02%   |
| Intel Bluetooth wireless interface                                                  | 6         | 4.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 3.01%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.26%   |
| Intel AX211 Bluetooth                                                               | 3         | 2.26%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.5%    |
| Intel AX210 Bluetooth                                                               | 2         | 1.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.5%    |
| ASUS BCM20702A0                                                                     | 2         | 1.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.75%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.75%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.75%   |
| MediaTek Wireless_Device                                                            | 1         | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.75%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.75%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.75%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.75%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.75%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.75%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 164       | 52.4%   |
| Nvidia                    | 55        | 17.57%  |
| AMD                       | 28        | 8.95%   |
| Lenovo                    | 17        | 5.43%   |
| Plantronics               | 6         | 1.92%   |
| GN Netcom                 | 6         | 1.92%   |
| JMTek                     | 5         | 1.6%    |
| Texas Instruments         | 3         | 0.96%   |
| Generalplus Technology    | 3         | 0.96%   |
| Creative Technology       | 3         | 0.96%   |
| Creative Labs             | 3         | 0.96%   |
| Realtek Semiconductor     | 2         | 0.64%   |
| Logitech                  | 2         | 0.64%   |
| C-Media Electronics       | 2         | 0.64%   |
| Tenx Technology           | 1         | 0.32%   |
| SteelSeries ApS           | 1         | 0.32%   |
| Sennheiser Communications | 1         | 0.32%   |
| RODE Microphones          | 1         | 0.32%   |
| Hewlett-Packard           | 1         | 0.32%   |
| Google                    | 1         | 0.32%   |
| Giga-Byte Technology      | 1         | 0.32%   |
| Focusrite-Novation        | 1         | 0.32%   |
| Dynex                     | 1         | 0.32%   |
| DSEA A/S                  | 1         | 0.32%   |
| Dell                      | 1         | 0.32%   |
| Corsair                   | 1         | 0.32%   |
| Blue Microphones          | 1         | 0.32%   |
| ASUSTek Computer          | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 25        | 7.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 5.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 4.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 4.42%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 4.42%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 2.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.65%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.47%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 1.47%   |
| Plantronics BT600                                                          | 4         | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.18%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.18%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.88%   |
| Nvidia Audio device                                                        | 3         | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 0.88%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.88%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.88%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.59%   |
| Plantronics Poly BT700                                                     | 2         | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 33.7%   |
| SK hynix            | 20        | 21.74%  |
| Crucial             | 9         | 9.78%   |
| Micron Technology   | 8         | 8.7%    |
| Kingston            | 6         | 6.52%   |
| Corsair             | 5         | 5.43%   |
| Unknown             | 2         | 2.17%   |
| GOODRAM             | 2         | 2.17%   |
| Unknown (0x0B5E)    | 1         | 1.09%   |
| Unknown (0x0205)    | 1         | 1.09%   |
| Transcend           | 1         | 1.09%   |
| Smart               | 1         | 1.09%   |
| Patriot             | 1         | 1.09%   |
| Innodisk            | 1         | 1.09%   |
| Hewlett-Packard     | 1         | 1.09%   |
| Elpida              | 1         | 1.09%   |
| Unknown             | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 4.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.04%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2.04%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 2.04%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 2.04%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s            | 2         | 2.04%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s            | 2         | 2.04%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 2.04%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.02%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.02%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.02%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 1.02%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 1.02%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.02%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 1.02%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.02%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 1.02%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 1.02%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.02%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 1.02%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.02%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 1.02%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.02%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB DIMM DDR4 2400MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.02%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.02%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.02%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                       | 1         | 1.02%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1         | 1.02%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.02%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                    | 1         | 1.02%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.02%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                      | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 49        | 64.47%  |
| DDR3   | 21        | 27.63%  |
| SDRAM  | 2         | 2.63%   |
| LPDDR4 | 1         | 1.32%   |
| LPDDR3 | 1         | 1.32%   |
| DRAM   | 1         | 1.32%   |
| DDR5   | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 57.33%  |
| DIMM         | 31        | 41.33%  |
| Row Of Chips | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 33.73%  |
| 16384 | 24        | 28.92%  |
| 4096  | 17        | 20.48%  |
| 32768 | 12        | 14.46%  |
| 65536 | 1         | 1.2%    |
| 2048  | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 19        | 23.17%  |
| 1600  | 16        | 19.51%  |
| 2667  | 13        | 15.85%  |
| 2400  | 12        | 14.63%  |
| 1333  | 6         | 7.32%   |
| 2133  | 4         | 4.88%   |
| 3600  | 3         | 3.66%   |
| 3266  | 2         | 2.44%   |
| 4800  | 1         | 1.22%   |
| 3933  | 1         | 1.22%   |
| 2933  | 1         | 1.22%   |
| 2666  | 1         | 1.22%   |
| 2472  | 1         | 1.22%   |
| 1866  | 1         | 1.22%   |
| 1334  | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 4         | 57.14%  |
| Canon              | 2         | 28.57%  |
| Brother Industries | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w | 1         | 14.29%  |
| HP LaserJet Pro M118-M119        | 1         | 14.29%  |
| HP ENVY 4500 series              | 1         | 14.29%  |
| HP DeskJet 2600 series           | 1         | 14.29%  |
| Canon LiDE 300                   | 1         | 14.29%  |
| Canon E560 series                | 1         | 14.29%  |
| Brother DCP-1610W                | 1         | 14.29%  |

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
| Chicony Electronics                    | 40        | 27.97%  |
| IMC Networks                           | 21        | 14.69%  |
| Bison Electronics                      | 12        | 8.39%   |
| Realtek Semiconductor                  | 11        | 7.69%   |
| Logitech                               | 9         | 6.29%   |
| Sunplus Innovation Technology          | 7         | 4.9%    |
| Microdia                               | 7         | 4.9%    |
| Lite-On Technology                     | 4         | 2.8%    |
| Hopewin Electronic Material            | 4         | 2.8%    |
| Suyin                                  | 3         | 2.1%    |
| Samsung Electronics                    | 3         | 2.1%    |
| Luxvisions Innotech Limited            | 3         | 2.1%    |
| Acer                                   | 3         | 2.1%    |
| Ruision                                | 2         | 1.4%    |
| Microsoft                              | 2         | 1.4%    |
| Generalplus Technology                 | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.4%    |
| Syntek                                 | 1         | 0.7%    |
| Remo Tech                              | 1         | 0.7%    |
| Quanta                                 | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| KYE Systems (Mouse Systems)            | 1         | 0.7%    |
| Jieli Technology                       | 1         | 0.7%    |
| Creative Technology                    | 1         | 0.7%    |
| ARC International                      | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 21        | 14.38%  |
| IMC Networks Integrated Camera                    | 18        | 12.33%  |
| Realtek Integrated_Webcam_HD                      | 7         | 4.79%   |
| Bison Integrated Camera                           | 7         | 4.79%   |
| Bison SunplusIT Integrated Camera                 | 5         | 3.42%   |
| Logitech HD Pro Webcam C920                       | 4         | 2.74%   |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 4         | 2.74%   |
| Chicony Integrated Camera (1280x720@30)           | 4         | 2.74%   |
| Sunplus Integrated_Webcam_HD                      | 3         | 2.05%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 2.05%   |
| Lite-On Integrated Camera                         | 3         | 2.05%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.05%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 2.05%   |
| Chicony HP HD Camera                              | 3         | 2.05%   |
| Ruision UVC Camera                                | 2         | 1.37%   |
| Microdia Webcam                                   | 2         | 1.37%   |
| Microdia Integrated Webcam                        | 2         | 1.37%   |
| Generalplus CAMERA - UVC                          | 2         | 1.37%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.37%   |
| Bison Integrated IR Camera                        | 2         | 1.37%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.68%   |
| Suyin RGBIR Camera                                | 1         | 0.68%   |
| Suyin Integrated_Webcam_HD                        | 1         | 0.68%   |
| Suyin HP Truevision HD                            | 1         | 0.68%   |
| Sunplus USB2.0 Camera                             | 1         | 0.68%   |
| Sunplus PC Camera                                 | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.68%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.68%   |
| Realtek USB Camera                                | 1         | 0.68%   |
| Realtek Thronmax Stream Go Pro Webcam             | 1         | 0.68%   |
| Realtek HP Webcam                                 | 1         | 0.68%   |
| Quanta HP HD Camera                               | 1         | 0.68%   |
| Microsoft LifeCam HD-3000                         | 1         | 0.68%   |
| Microsoft LifeCam Cinema                          | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_E4HD            | 1         | 0.68%   |
| Microdia Integrated_Webcam_HD                     | 1         | 0.68%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 35        | 63.64%  |
| Validity Sensors           | 14        | 25.45%  |
| Shenzhen Goodix Technology | 3         | 5.45%   |
| Upek                       | 2         | 3.64%   |
| Elan Microelectronics      | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 43.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.91%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.82%   |
| Validity Sensors VFS491                                                    | 1         | 1.82%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.82%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.82%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.82%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.82%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.82%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 40%     |
| Alcor Micro           | 5         | 25%     |
| SCM Microsystems      | 2         | 10%     |
| Lenovo                | 2         | 10%     |
| Yubico.com            | 1         | 5%      |
| Upek                  | 1         | 5%      |
| Gemalto (was Gemplus) | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                             | 5         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 25%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 2         | 10%     |
| Lenovo Integrated Smart Card Reader                        | 2         | 10%     |
| Broadcom 5880                                              | 2         | 10%     |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 5%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 47.24%  |
| 1     | 77        | 38.69%  |
| 2     | 20        | 10.05%  |
| 3     | 5         | 2.51%   |
| 5     | 2         | 1.01%   |
| 4     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 39.57%  |
| Graphics card            | 21        | 15.11%  |
| Chipcard                 | 13        | 9.35%   |
| Net/wireless             | 12        | 8.63%   |
| Unassigned class         | 9         | 6.47%   |
| Card reader              | 6         | 4.32%   |
| Multimedia controller    | 5         | 3.6%    |
| Communication controller | 5         | 3.6%    |
| Net/ethernet             | 4         | 2.88%   |
| Bluetooth                | 4         | 2.88%   |
| Storage                  | 2         | 1.44%   |
| Storage/ide              | 1         | 0.72%   |
| Sound                    | 1         | 0.72%   |
| Network                  | 1         | 0.72%   |

