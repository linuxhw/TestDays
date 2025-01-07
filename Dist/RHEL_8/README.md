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

Total: 325

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 01G0M6 A02                  | Desktop     | [9018a2ac09](https://linux-hardware.org/?probe=9018a2ac09) | Jan 06, 2025 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [7a11752435](https://linux-hardware.org/?probe=7a11752435) | Sep 11, 2024 |
| Supermicro    | X10SRA                      | Server      | [7b12ea87ed](https://linux-hardware.org/?probe=7b12ea87ed) | Sep 10, 2024 |
| Supermicro    | X9DAi                       | Desktop     | [f84f7e7927](https://linux-hardware.org/?probe=f84f7e7927) | Sep 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [37e0d80500](https://linux-hardware.org/?probe=37e0d80500) | Jul 12, 2024 |
| Dell          | Latitude 5340               | Notebook    | [f8bada88dd](https://linux-hardware.org/?probe=f8bada88dd) | Jun 15, 2024 |
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


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64  | 14        | 5.76%   |
| 4.18.0-240.1.1.el8_3.x86_64   | 14        | 5.76%   |
| 4.18.0-348.20.1.el8_5.x86_64  | 12        | 4.94%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 11        | 4.53%   |
| 4.18.0-305.el8.x86_64         | 10        | 4.12%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 10        | 4.12%   |
| 4.18.0-80.11.2.el8_0.x86_64   | 9         | 3.7%    |
| 4.18.0-348.12.2.el8_5.x86_64  | 9         | 3.7%    |
| 4.18.0-425.10.1.el8_7.x86_64  | 8         | 3.29%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 8         | 3.29%   |
| 4.18.0-305.19.1.el8_4.x86_64  | 8         | 3.29%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 7         | 2.88%   |
| 4.18.0-193.el8.x86_64         | 7         | 2.88%   |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 2.47%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 6         | 2.47%   |
| 4.18.0-193.19.1.el8_2.x86_64  | 6         | 2.47%   |
| 4.18.0-147.5.1.el8_1.x86_64   | 6         | 2.47%   |
| 4.18.0-147.3.1.el8_1.x86_64   | 6         | 2.47%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 5         | 2.06%   |
| 4.18.0-193.6.3.el8_2.x86_64   | 5         | 2.06%   |
| 4.18.0-372.9.1.el8.x86_64     | 4         | 1.65%   |
| 4.18.0-348.7.1.el8_5.x86_64   | 4         | 1.65%   |
| 4.18.0-305.25.1.el8_4.x86_64  | 4         | 1.65%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 4         | 1.65%   |
| 4.18.0-193.28.1.el8_2.x86_64  | 4         | 1.65%   |
| 4.18.0-147.el8.x86_64         | 4         | 1.65%   |
| 4.18.0-553.16.1.el8_10.x86_64 | 3         | 1.23%   |
| 4.18.0-147.8.1.el8_1.x86_64   | 3         | 1.23%   |
| 4.18.0-513.18.1.el8_9.x86_64  | 2         | 0.82%   |
| 4.18.0-477.27.1.el8_8.x86_64  | 2         | 0.82%   |
| 4.18.0-477.21.1.el8_8.x86_64  | 2         | 0.82%   |
| 4.18.0-477.15.1.el8_8.x86_64  | 2         | 0.82%   |
| 4.18.0-477.10.1.el8_8.x86_64  | 2         | 0.82%   |
| 4.18.0-372.32.1.el8_6.x86_64  | 2         | 0.82%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 2         | 0.82%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 2         | 0.82%   |
| 4.18.0-348.el8.x86_64         | 2         | 0.82%   |
| 4.18.0-305.17.1.el8_4.x86_64  | 2         | 0.82%   |
| 4.18.0-240.8.1.el8_3.x86_64   | 2         | 0.82%   |
| 4.18.0-193.14.3.el8_2.x86_64  | 2         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 195       | 97.01%  |
| 5.9.1    | 1         | 0.5%    |
| 5.13.13  | 1         | 0.5%    |
| 5.13.0   | 1         | 0.5%    |
| 5.10.6   | 1         | 0.5%    |
| 4.19.150 | 1         | 0.5%    |
| Unknown  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 195       | 97.01%  |
| 5.13    | 2         | 1%      |
| 5.9     | 1         | 0.5%    |
| 5.10    | 1         | 0.5%    |
| 4.19    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 200       | 99.5%   |
| Unknown | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 171       | 82.21%  |
| Unknown       | 20        | 9.62%   |
| GNOME Classic | 9         | 4.33%   |
| KDE5          | 5         | 2.4%    |
| KDE           | 2         | 0.96%   |
| MATE          | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 115       | 55.29%  |
| Wayland | 83        | 39.9%   |
| Unknown | 10        | 4.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 153       | 72.86%  |
| GDM     | 55        | 26.19%  |
| SDDM    | 1         | 0.48%   |
| LightDM | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 136       | 66.02%  |
| Unknown | 13        | 6.31%   |
| en_GB   | 12        | 5.83%   |
| en_IN   | 5         | 2.43%   |
| de_DE   | 5         | 2.43%   |
| pl_PL   | 4         | 1.94%   |
| fr_FR   | 4         | 1.94%   |
| ru_RU   | 3         | 1.46%   |
| pt_BR   | 2         | 0.97%   |
| nl_NL   | 2         | 0.97%   |
| fr_CA   | 2         | 0.97%   |
| es_ES   | 2         | 0.97%   |
| es_AR   | 2         | 0.97%   |
| en_IE   | 2         | 0.97%   |
| sl_SI   | 1         | 0.49%   |
| nl_BE   | 1         | 0.49%   |
| ko_KR   | 1         | 0.49%   |
| ja_JP   | 1         | 0.49%   |
| it_IT   | 1         | 0.49%   |
| es_MX   | 1         | 0.49%   |
| es_EC   | 1         | 0.49%   |
| es_CO   | 1         | 0.49%   |
| en_NZ   | 1         | 0.49%   |
| en_DK   | 1         | 0.49%   |
| de_CH   | 1         | 0.49%   |
| cs_CZ   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 161       | 78.54%  |
| BIOS | 44        | 21.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 178       | 87.25%  |
| Ext4    | 18        | 8.82%   |
| Unknown | 8         | 3.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 141       | 67.46%  |
| GPT     | 63        | 30.14%  |
| MBR     | 5         | 2.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 91.67%  |
| Yes       | 17        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 89.76%  |
| Yes       | 21        | 10.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 82        | 40.8%   |
| Dell                | 31        | 15.42%  |
| Hewlett-Packard     | 27        | 13.43%  |
| ASUSTek Computer    | 21        | 10.45%  |
| Gigabyte Technology | 9         | 4.48%   |
| Supermicro          | 5         | 2.49%   |
| ASRock              | 5         | 2.49%   |
| MSI                 | 4         | 1.99%   |
| Intel               | 3         | 1.49%   |
| Sony                | 2         | 1%      |
| Unknown             | 2         | 1%      |
| TUXEDO              | 1         | 0.5%    |
| Toshiba             | 1         | 0.5%    |
| Timi                | 1         | 0.5%    |
| IBM                 | 1         | 0.5%    |
| Getac               | 1         | 0.5%    |
| CX / Air Computers. | 1         | 0.5%    |
| AZW                 | 1         | 0.5%    |
| AMI                 | 1         | 0.5%    |
| Alienware           | 1         | 0.5%    |
| Acer                | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X         | 4         | 1.99%   |
| ASUS All Series                             | 4         | 1.99%   |
| Unknown                                     | 3         | 1.49%   |
| Supermicro X10DRi                           | 2         | 1%      |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401    | 2         | 1%      |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00    | 2         | 1%      |
| Lenovo ThinkPad T590 20N5S2NC0N             | 2         | 1%      |
| Lenovo ThinkPad T490s 20NYS7K91R            | 2         | 1%      |
| Lenovo ThinkPad T480s 20L8S2N800            | 2         | 1%      |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08       | 2         | 1%      |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q         | 2         | 1%      |
| HP EliteBook 8460p                          | 2         | 1%      |
| Dell Latitude E6430                         | 2         | 1%      |
| Dell Latitude 5300                          | 2         | 1%      |
| TUXEDO N13xWU                               | 1         | 0.5%    |
| Toshiba Satellite Pro R50-C                 | 1         | 0.5%    |
| Timi TM1707                                 | 1         | 0.5%    |
| Supermicro X9DAi                            | 1         | 0.5%    |
| Supermicro X7DW3                            | 1         | 0.5%    |
| Supermicro X10SRA                           | 1         | 0.5%    |
| Sony VPCEB4L1R                              | 1         | 0.5%    |
| Sony VPCEB23FM                              | 1         | 0.5%    |
| MSI MS-7B51                                 | 1         | 0.5%    |
| MSI MS-7B33                                 | 1         | 0.5%    |
| MSI MS-7A37                                 | 1         | 0.5%    |
| MSI MS-7752                                 | 1         | 0.5%    |
| Lenovo Z40-70 20366                         | 1         | 0.5%    |
| Lenovo Yoga C640-13IML 81UE                 | 1         | 0.5%    |
| Lenovo ThinkSystem SR645                    | 1         | 0.5%    |
| Lenovo ThinkPad X390 Yoga 20NQS18Y00        | 1         | 0.5%    |
| Lenovo ThinkPad X270 20HN001EMC             | 1         | 0.5%    |
| Lenovo ThinkPad X250 20CLS0H807             | 1         | 0.5%    |
| Lenovo ThinkPad X230 Tablet 34373KU         | 1         | 0.5%    |
| Lenovo ThinkPad X201 3680PKS                | 1         | 0.5%    |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100      | 1         | 0.5%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G  | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20UAS2H10S  | 1         | 0.5%    |
| Lenovo ThinkPad W530 2441B32                | 1         | 0.5%    |
| Lenovo ThinkPad W520 4284GN2                | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 72        | 35.82%  |
| Dell Precision     | 12        | 5.97%   |
| Dell Latitude      | 10        | 4.98%   |
| HP EliteBook       | 5         | 2.49%   |
| HP ZBook           | 4         | 1.99%   |
| ASUS All           | 4         | 1.99%   |
| Lenovo ThinkCentre | 3         | 1.49%   |
| Dell Inspiron      | 3         | 1.49%   |
| ASUS ROG           | 3         | 1.49%   |
| ASUS PRIME         | 3         | 1.49%   |
| Unknown            | 3         | 1.49%   |
| Supermicro X10DRi  | 2         | 1%      |
| HP Z230            | 2         | 1%      |
| HP ProBook         | 2         | 1%      |
| Dell PowerEdge     | 2         | 1%      |
| ASUS VivoBook      | 2         | 1%      |
| TUXEDO N13xWU      | 1         | 0.5%    |
| Toshiba Satellite  | 1         | 0.5%    |
| Timi TM1707        | 1         | 0.5%    |
| Supermicro X9DAi   | 1         | 0.5%    |
| Supermicro X7DW3   | 1         | 0.5%    |
| Supermicro X10SRA  | 1         | 0.5%    |
| Sony VPCEB4L1R     | 1         | 0.5%    |
| Sony VPCEB23FM     | 1         | 0.5%    |
| MSI MS-7B51        | 1         | 0.5%    |
| MSI MS-7B33        | 1         | 0.5%    |
| MSI MS-7A37        | 1         | 0.5%    |
| MSI MS-7752        | 1         | 0.5%    |
| Lenovo Z40-70      | 1         | 0.5%    |
| Lenovo Yoga        | 1         | 0.5%    |
| Lenovo ThinkSystem | 1         | 0.5%    |
| Lenovo S40-40      | 1         | 0.5%    |
| Lenovo Legion      | 1         | 0.5%    |
| Lenovo 10SFS03200  | 1         | 0.5%    |
| Intel NUC12SNKi72  | 1         | 0.5%    |
| Intel NUC10i7FNK   | 1         | 0.5%    |
| Intel DX79SR       | 1         | 0.5%    |
| IBM FAB2           | 1         | 0.5%    |
| HP Z840            | 1         | 0.5%    |
| HP Z620            | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 38        | 18.91%  |
| 2019 | 34        | 16.92%  |
| 2018 | 28        | 13.93%  |
| 2012 | 15        | 7.46%   |
| 2015 | 14        | 6.97%   |
| 2017 | 13        | 6.47%   |
| 2016 | 13        | 6.47%   |
| 2021 | 12        | 5.97%   |
| 2014 | 8         | 3.98%   |
| 2011 | 8         | 3.98%   |
| 2013 | 7         | 3.48%   |
| 2022 | 4         | 1.99%   |
| 2010 | 3         | 1.49%   |
| 2023 | 2         | 1%      |
| 2024 | 1         | 0.5%    |
| 2009 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 123       | 61.19%  |
| Desktop     | 58        | 28.86%  |
| Server      | 9         | 4.48%   |
| Mini pc     | 6         | 2.99%   |
| Convertible | 4         | 1.99%   |
| All in one  | 1         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 176       | 86.7%   |
| Enabled  | 27        | 13.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 63        | 30.29%  |
| 16.01-24.0      | 35        | 16.83%  |
| 8.01-16.0       | 33        | 15.87%  |
| 64.01-256.0     | 30        | 14.42%  |
| 4.01-8.0        | 29        | 13.94%  |
| 24.01-32.0      | 8         | 3.85%   |
| 3.01-4.0        | 6         | 2.88%   |
| More than 256.0 | 3         | 1.44%   |
| Unknown         | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 84        | 36.68%  |
| 2.01-3.0        | 40        | 17.47%  |
| 8.01-16.0       | 38        | 16.59%  |
| 3.01-4.0        | 35        | 15.28%  |
| 1.01-2.0        | 17        | 7.42%   |
| 16.01-24.0      | 5         | 2.18%   |
| 24.01-32.0      | 4         | 1.75%   |
| 0.51-1.0        | 3         | 1.31%   |
| More than 256.0 | 1         | 0.44%   |
| 32.01-64.0      | 1         | 0.44%   |
| Unknown         | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 58.57%  |
| 2      | 48        | 22.86%  |
| 3      | 18        | 8.57%   |
| 4      | 8         | 3.81%   |
| 5      | 5         | 2.38%   |
| 8      | 2         | 0.95%   |
| 7      | 2         | 0.95%   |
| 6      | 2         | 0.95%   |
| 10     | 1         | 0.48%   |
| 0      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 77.34%  |
| Yes       | 46        | 22.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 90.1%   |
| No        | 20        | 9.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 81.09%  |
| No        | 38        | 18.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 65.22%  |
| No        | 72        | 34.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 44        | 21.89%  |
| India        | 18        | 8.96%   |
| UK           | 14        | 6.97%   |
| Germany      | 13        | 6.47%   |
| Czechia      | 11        | 5.47%   |
| Canada       | 9         | 4.48%   |
| France       | 6         | 2.99%   |
| Poland       | 5         | 2.49%   |
| Switzerland  | 4         | 1.99%   |
| Netherlands  | 4         | 1.99%   |
| Mexico       | 4         | 1.99%   |
| Italy        | 4         | 1.99%   |
| Brazil       | 4         | 1.99%   |
| Spain        | 3         | 1.49%   |
| South Africa | 3         | 1.49%   |
| Russia       | 3         | 1.49%   |
| Lithuania    | 3         | 1.49%   |
| Finland      | 3         | 1.49%   |
| Australia    | 3         | 1.49%   |
| Argentina    | 3         | 1.49%   |
| Ukraine      | 2         | 1%      |
| South Korea  | 2         | 1%      |
| Romania      | 2         | 1%      |
| Japan        | 2         | 1%      |
| Egypt        | 2         | 1%      |
| Colombia     | 2         | 1%      |
| China        | 2         | 1%      |
| Chile        | 2         | 1%      |
| Turkmenistan | 1         | 0.5%    |
| Sweden       | 1         | 0.5%    |
| Slovenia     | 1         | 0.5%    |
| Singapore    | 1         | 0.5%    |
| Saudi Arabia | 1         | 0.5%    |
| Portugal     | 1         | 0.5%    |
| Pakistan     | 1         | 0.5%    |
| New Zealand  | 1         | 0.5%    |
| Nepal        | 1         | 0.5%    |
| Myanmar      | 1         | 0.5%    |
| Morocco      | 1         | 0.5%    |
| Luxembourg   | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Prague            | 9         | 4.19%   |
| Turku             | 3         | 1.4%    |
| San Jose          | 3         | 1.4%    |
| Munich            | 3         | 1.4%    |
| Mexico City       | 3         | 1.4%    |
| Berlin            | 3         | 1.4%    |
| Bengaluru         | 3         | 1.4%    |
| Sorel-Tracy       | 2         | 0.93%   |
| Ottawa            | 2         | 0.93%   |
| Montreal          | 2         | 0.93%   |
| Milan             | 2         | 0.93%   |
| Leeds             | 2         | 0.93%   |
| Kyiv              | 2         | 0.93%   |
| Didcot            | 2         | 0.93%   |
| Des Moines        | 2         | 0.93%   |
| Chicago           | 2         | 0.93%   |
| Chennai           | 2         | 0.93%   |
| Zaragoza          | 1         | 0.47%   |
| Yongin-si         | 1         | 0.47%   |
| Wroclaw           | 1         | 0.47%   |
| Wiesbaden         | 1         | 0.47%   |
| Webster           | 1         | 0.47%   |
| Wayne             | 1         | 0.47%   |
| Wagholi           | 1         | 0.47%   |
| Vardenis          | 1         | 0.47%   |
| Vaglio            | 1         | 0.47%   |
| Udaipur           | 1         | 0.47%   |
| Toronto           | 1         | 0.47%   |
| Tiruchi           | 1         | 0.47%   |
| Temuco            | 1         | 0.47%   |
| Temara            | 1         | 0.47%   |
| Tauranga          | 1         | 0.47%   |
| Taringa           | 1         | 0.47%   |
| Talkha            | 1         | 0.47%   |
| Syracuse          | 1         | 0.47%   |
| Suffolk           | 1         | 0.47%   |
| Stuttgart         | 1         | 0.47%   |
| Streatham         | 1         | 0.47%   |
| Stellenbosch      | 1         | 0.47%   |
| Steamboat Springs | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 61        | 107    | 19.93%  |
| WDC                         | 36        | 61     | 11.76%  |
| Seagate                     | 30        | 46     | 9.8%    |
| Toshiba                     | 25        | 32     | 8.17%   |
| SK hynix                    | 18        | 22     | 5.88%   |
| SanDisk                     | 18        | 32     | 5.88%   |
| Kingston                    | 17        | 22     | 5.56%   |
| Intel                       | 13        | 21     | 4.25%   |
| Micron Technology           | 11        | 18     | 3.59%   |
| Crucial                     | 10        | 14     | 3.27%   |
| Unknown                     | 8         | 10     | 2.61%   |
| A-DATA Technology           | 6         | 6      | 1.96%   |
| PNY                         | 4         | 5      | 1.31%   |
| HGST                        | 4         | 4      | 1.31%   |
| Hewlett-Packard             | 4         | 6      | 1.31%   |
| Silicon Motion              | 3         | 4      | 0.98%   |
| Phison                      | 3         | 7      | 0.98%   |
| Lenovo                      | 3         | 3      | 0.98%   |
| Hitachi                     | 3         | 3      | 0.98%   |
| Gigabyte Technology         | 3         | 4      | 0.98%   |
| Corsair                     | 3         | 6      | 0.98%   |
| KIOXIA                      | 2         | 3      | 0.65%   |
| XPG                         | 1         | 1      | 0.33%   |
| Western Digital             | 1         | 1      | 0.33%   |
| UMIS                        | 1         | 1      | 0.33%   |
| Team                        | 1         | 2      | 0.33%   |
| T-FORCE                     | 1         | 2      | 0.33%   |
| SSSTC                       | 1         | 1      | 0.33%   |
| SMI                         | 1         | 2      | 0.33%   |
| Plextor                     | 1         | 1      | 0.33%   |
| Phison Electronics          | 1         | 1      | 0.33%   |
| OCZ                         | 1         | 2      | 0.33%   |
| Micron/Crucial Technology   | 1         | 1      | 0.33%   |
| Lite-On                     | 1         | 1      | 0.33%   |
| Kingston Technology Company | 1         | 1      | 0.33%   |
| KingFast                    | 1         | 1      | 0.33%   |
| KINGBANK                    | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |
| HPT                         | 1         | 1      | 0.33%   |
| Hoodisk                     | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                        | 10        | 2.9%    |
| Samsung NVMe SSD Drive 512GB                         | 7         | 2.03%   |
| Toshiba NVMe SSD Drive 256GB                         | 6         | 1.74%   |
| SanDisk NVMe SSD Drive 256GB                         | 6         | 1.74%   |
| Samsung SSD 860 EVO 1TB                              | 6         | 1.74%   |
| Samsung NVMe SSD Drive 256GB                         | 6         | 1.74%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 1.45%   |
| Samsung NVMe SSD Drive 500GB                         | 4         | 1.16%   |
| Toshiba NVMe SSD Drive 512GB                         | 3         | 0.87%   |
| Toshiba DT01ACA200 2TB                               | 3         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 0.87%   |
| Micron NVMe SSD Drive 256GB                          | 3         | 0.87%   |
| Kingston SA400S37480G 480GB SSD                      | 3         | 0.87%   |
| HGST HTS721010A9E630 1TB                             | 3         | 0.87%   |
| Crucial CT240BX500SSD1 240GB                         | 3         | 0.87%   |
| WDC WD1003FZEX-00MK2A0 1TB                           | 2         | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB                            | 2         | 0.58%   |
| Unknown NVMe SSD Drive 256GB                         | 2         | 0.58%   |
| Unknown MMC Card  16GB                               | 2         | 0.58%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 2         | 0.58%   |
| Toshiba KXG6AZNV256G 256GB                           | 2         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB                      | 2         | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB                       | 2         | 0.58%   |
| Seagate ST1000LM049-2GH172 1TB                       | 2         | 0.58%   |
| Seagate ST1000DM003-9YN162 1TB                       | 2         | 0.58%   |
| Seagate Expansion 1TB                                | 2         | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 2         | 0.58%   |
| Samsung SSD 860 QVO 1TB                              | 2         | 0.58%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 0.58%   |
| Samsung SSD 850 EVO 500GB                            | 2         | 0.58%   |
| Samsung Portable SSD T5 500GB                        | 2         | 0.58%   |
| Samsung NVMe SSD Drive 2TB                           | 2         | 0.58%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2         | 0.58%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                       | 2         | 0.58%   |
| Kingston SUV500120G 120GB SSD                        | 2         | 0.58%   |
| Kingston SA400S37240G 240GB SSD                      | 2         | 0.58%   |
| Intel SSDPEL1K100GA 100GB                            | 2         | 0.58%   |
| Intel NVMe SSD Drive 512GB                           | 2         | 0.58%   |
| Intel NVMe SSD Drive 2TB                             | 2         | 0.58%   |

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
| Samsung Electronics | 27        | 44     | 29.35%  |
| Kingston            | 12        | 16     | 13.04%  |
| Crucial             | 10        | 14     | 10.87%  |
| WDC                 | 6         | 8      | 6.52%   |
| SanDisk             | 6         | 12     | 6.52%   |
| Micron Technology   | 5         | 10     | 5.43%   |
| A-DATA Technology   | 5         | 5      | 5.43%   |
| PNY                 | 4         | 5      | 4.35%   |
| Intel               | 3         | 5      | 3.26%   |
| Corsair             | 3         | 6      | 3.26%   |
| SK hynix            | 2         | 5      | 2.17%   |
| Toshiba             | 1         | 1      | 1.09%   |
| Team                | 1         | 2      | 1.09%   |
| Seagate             | 1         | 1      | 1.09%   |
| Plextor             | 1         | 1      | 1.09%   |
| OCZ                 | 1         | 2      | 1.09%   |
| KINGBANK            | 1         | 1      | 1.09%   |
| Intenso             | 1         | 1      | 1.09%   |
| Hoodisk             | 1         | 1      | 1.09%   |
| China               | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 120       | 188    | 42.7%   |
| SSD     | 82        | 141    | 29.18%  |
| HDD     | 70        | 120    | 24.91%  |
| MMC     | 5         | 6      | 1.78%   |
| Unknown | 4         | 6      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 120       | 188    | 48.39%  |
| SATA | 106       | 241    | 42.74%  |
| SAS  | 17        | 26     | 6.85%   |
| MMC  | 5         | 6      | 2.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 123    | 46.01%  |
| 0.51-1.0   | 50        | 80     | 30.67%  |
| 1.01-2.0   | 22        | 27     | 13.5%   |
| 3.01-4.0   | 10        | 22     | 6.13%   |
| 4.01-10.0  | 4         | 7      | 2.45%   |
| 2.01-3.0   | 1         | 1      | 0.61%   |
| 10.01-20.0 | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 35.85%  |
| 251-500        | 36        | 16.98%  |
| 501-1000       | 35        | 16.51%  |
| 1001-2000      | 18        | 8.49%   |
| More than 3000 | 17        | 8.02%   |
| 2001-3000      | 11        | 5.19%   |
| Unknown        | 8         | 3.77%   |
| 51-100         | 6         | 2.83%   |
| 21-50          | 3         | 1.42%   |
| 1-20           | 2         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 49        | 21.68%  |
| 1-20           | 43        | 19.03%  |
| 101-250        | 41        | 18.14%  |
| 51-100         | 35        | 15.49%  |
| 251-500        | 23        | 10.18%  |
| 501-1000       | 11        | 4.87%   |
| 1001-2000      | 9         | 3.98%   |
| Unknown        | 8         | 3.54%   |
| More than 3000 | 4         | 1.77%   |
| 2001-3000      | 3         | 1.33%   |

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
| Detected | 149       | 336    | 68.66%  |
| Works    | 62        | 118    | 28.57%  |
| Malfunc  | 6         | 7      | 2.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 113       | 41.7%   |
| Samsung Electronics            | 41        | 15.13%  |
| AMD                            | 17        | 6.27%   |
| SK hynix                       | 16        | 5.9%    |
| SanDisk                        | 15        | 5.54%   |
| Toshiba America Info Systems   | 14        | 5.17%   |
| Phison Electronics             | 6         | 2.21%   |
| Micron Technology              | 6         | 2.21%   |
| Silicon Motion                 | 5         | 1.85%   |
| Kingston Technology Company    | 5         | 1.85%   |
| Marvell Technology Group       | 4         | 1.48%   |
| KIOXIA                         | 4         | 1.48%   |
| Broadcom / LSI                 | 4         | 1.48%   |
| ASMedia Technology             | 4         | 1.48%   |
| Lenovo                         | 3         | 1.11%   |
| LSI Logic / Symbios Logic      | 2         | 0.74%   |
| Biwin Storage Technology       | 2         | 0.74%   |
| ADATA Technology               | 2         | 0.74%   |
| Western Digital                | 1         | 0.37%   |
| Union Memory (Shenzhen)        | 1         | 0.37%   |
| Solid State Storage Technology | 1         | 0.37%   |
| PMC-Sierra                     | 1         | 0.37%   |
| Micron/Crucial Technology      | 1         | 0.37%   |
| Lite-On Technology             | 1         | 0.37%   |
| HighPoint Technologies         | 1         | 0.37%   |
| Hewlett-Packard                | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 9.76%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 3.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 3.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 3.03%   |
| Intel SATA Controller [RAID Mode]                                              | 8         | 2.69%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.36%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7         | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.36%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 6         | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 2.02%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 6         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.35%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 1.35%   |
| Intel SSD 660P Series                                                          | 4         | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.35%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.35%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.01%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 1.01%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.01%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.01%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.01%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.67%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.67%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.67%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 120       | 45.8%   |
| SATA | 113       | 43.13%  |
| RAID | 19        | 7.25%   |
| SAS  | 6         | 2.29%   |
| IDE  | 4         | 1.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 179       | 89.05%  |
| AMD    | 22        | 10.95%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 12        | 5.97%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 4.98%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.48%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 2.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 1.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.99%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.49%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 1%      |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 2         | 1%      |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 1%      |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1%      |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 1%      |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1%      |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1%      |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1%      |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1%      |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1%      |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1%      |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1%      |
| Intel Xeon w9-3495X                           | 1         | 0.5%    |
| Intel Xeon W-2102 CPU @ 2.90GHz               | 1         | 0.5%    |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.5%    |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.5%    |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.5%    |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 82        | 40.8%   |
| Intel Core i5      | 39        | 19.4%   |
| Intel Xeon         | 26        | 12.94%  |
| Other              | 13        | 6.47%   |
| Intel Core i3      | 10        | 4.98%   |
| AMD Ryzen 7        | 8         | 3.98%   |
| Intel Core i9      | 5         | 2.49%   |
| AMD Ryzen 9        | 4         | 1.99%   |
| AMD Ryzen 5        | 3         | 1.49%   |
| Intel Pentium Gold | 2         | 1%      |
| Intel Pentium      | 2         | 1%      |
| AMD Ryzen 3        | 2         | 1%      |
| AMD EPYC           | 2         | 1%      |
| AMD Ryzen 7 PRO    | 1         | 0.5%    |
| AMD FX             | 1         | 0.5%    |
| AMD A10            | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 87        | 43.28%  |
| 2      | 41        | 20.4%   |
| 6      | 33        | 16.42%  |
| 8      | 18        | 8.96%   |
| 12     | 7         | 3.48%   |
| 16     | 4         | 1.99%   |
| 10     | 3         | 1.49%   |
| 20     | 2         | 1%      |
| 96     | 1         | 0.5%    |
| 64     | 1         | 0.5%    |
| 56     | 1         | 0.5%    |
| 36     | 1         | 0.5%    |
| 24     | 1         | 0.5%    |
| 14     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 190       | 94.53%  |
| 2      | 11        | 5.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 173       | 85.64%  |
| 1      | 29        | 14.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 197       | 97.04%  |
| Unknown        | 6         | 2.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 29        | 14.29%  |
| Unknown    | 15        | 7.39%   |
| 0x906ea    | 14        | 6.9%    |
| 0x806ea    | 14        | 6.9%    |
| 0xa0652    | 12        | 5.91%   |
| 0x306c3    | 12        | 5.91%   |
| 0x306a9    | 11        | 5.42%   |
| 0x206a7    | 8         | 3.94%   |
| 0x906ed    | 7         | 3.45%   |
| 0x506e3    | 7         | 3.45%   |
| 0x406e3    | 7         | 3.45%   |
| 0x806c1    | 6         | 2.96%   |
| 0x906e9    | 5         | 2.46%   |
| 0x306f2    | 5         | 2.46%   |
| 0x806e9    | 4         | 1.97%   |
| 0x806d1    | 3         | 1.48%   |
| 0x406f1    | 3         | 1.48%   |
| 0x306d4    | 3         | 1.48%   |
| 0x20655    | 3         | 1.48%   |
| 0x0a50000c | 3         | 1.48%   |
| 0x08600103 | 3         | 1.48%   |
| 0x08108102 | 3         | 1.48%   |
| 0x40651    | 2         | 0.99%   |
| 0x206d7    | 2         | 0.99%   |
| 0x08701021 | 2         | 0.99%   |
| 0x08701013 | 2         | 0.99%   |
| 0xa0671    | 1         | 0.49%   |
| 0xa0660    | 1         | 0.49%   |
| 0xa0655    | 1         | 0.49%   |
| 0x906eb    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x90675    | 1         | 0.49%   |
| 0x306e4    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x10676    | 1         | 0.49%   |
| 0x0a001119 | 1         | 0.49%   |
| 0x08600106 | 1         | 0.49%   |
| 0x08600104 | 1         | 0.49%   |
| 0x08301034 | 1         | 0.49%   |
| 0x0810100b | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 76        | 37.62%  |
| Haswell          | 20        | 9.9%    |
| CometLake        | 17        | 8.42%   |
| Skylake          | 15        | 7.43%   |
| IvyBridge        | 13        | 6.44%   |
| SandyBridge      | 11        | 5.45%   |
| Zen 2            | 10        | 4.95%   |
| Broadwell        | 7         | 3.47%   |
| TigerLake        | 6         | 2.97%   |
| Unknown          | 5         | 2.48%   |
| Westmere         | 4         | 1.98%   |
| Icelake          | 4         | 1.98%   |
| Zen+             | 3         | 1.49%   |
| Zen 3            | 3         | 1.49%   |
| Zen              | 3         | 1.49%   |
| Alderlake Hybrid | 2         | 0.99%   |
| Steamroller      | 1         | 0.5%    |
| Piledriver       | 1         | 0.5%    |
| Penryn           | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 134       | 54.47%  |
| Nvidia                     | 76        | 30.89%  |
| AMD                        | 29        | 11.79%  |
| Matrox Electronics Systems | 5         | 2.03%   |
| ASPEED Technology          | 2         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 15        | 6%      |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 15        | 6%      |
| Intel UHD Graphics 620                                                      | 14        | 5.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 13        | 5.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 2.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 2%      |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 5         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.6%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.2%    |
| Intel HD Graphics 630                                                       | 3         | 1.2%    |
| Intel HD Graphics 620                                                       | 3         | 1.2%    |
| Intel HD Graphics 5500                                                      | 3         | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.8%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.8%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.8%    |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.8%    |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.8%    |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.8%    |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.8%    |
| Intel HD Graphics 530                                                       | 2         | 0.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.8%    |
| ASPEED Technology ASPEED Graphics Family                                    | 2         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 96        | 47.06%  |
| 1 x Nvidia              | 41        | 20.1%   |
| Intel + Nvidia          | 27        | 13.24%  |
| 1 x AMD                 | 18        | 8.82%   |
| Intel + AMD             | 6         | 2.94%   |
| 1 x Matrox              | 4         | 1.96%   |
| AMD + Nvidia            | 4         | 1.96%   |
| 2 x Nvidia              | 2         | 0.98%   |
| Other                   | 1         | 0.49%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.49%   |
| 2 x Intel               | 1         | 0.49%   |
| 2 x AMD                 | 1         | 0.49%   |
| Nvidia + Matrox         | 1         | 0.49%   |
| Nvidia + ASPEED         | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 159       | 77.94%  |
| Proprietary | 35        | 17.16%  |
| Unknown     | 10        | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 59.42%  |
| 1.01-2.0   | 20        | 9.66%   |
| 3.01-4.0   | 17        | 8.21%   |
| 7.01-8.0   | 10        | 4.83%   |
| 0.51-1.0   | 10        | 4.83%   |
| 0.01-0.5   | 9         | 4.35%   |
| 5.01-6.0   | 8         | 3.86%   |
| 2.01-3.0   | 4         | 1.93%   |
| 8.01-16.0  | 3         | 1.45%   |
| 4.01-5.0   | 2         | 0.97%   |
| 32.01-64.0 | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 11.42%  |
| Samsung Electronics     | 26        | 10.24%  |
| Dell                    | 25        | 9.84%   |
| Lenovo                  | 24        | 9.45%   |
| BOE                     | 24        | 9.45%   |
| LG Display              | 20        | 7.87%   |
| Chimei Innolux          | 20        | 7.87%   |
| Hewlett-Packard         | 15        | 5.91%   |
| Goldstar                | 14        | 5.51%   |
| Sharp                   | 5         | 1.97%   |
| Acer                    | 5         | 1.97%   |
| Philips                 | 4         | 1.57%   |
| InfoVision              | 4         | 1.57%   |
| Eizo                    | 4         | 1.57%   |
| BenQ                    | 4         | 1.57%   |
| PANDA                   | 3         | 1.18%   |
| Ancor Communications    | 3         | 1.18%   |
| ViewSonic               | 2         | 0.79%   |
| LGD                     | 2         | 0.79%   |
| Lenovo Group Limited    | 2         | 0.79%   |
| Iiyama                  | 2         | 0.79%   |
| Gigabyte Technology     | 2         | 0.79%   |
| AOC                     | 2         | 0.79%   |
| Unknown                 | 2         | 0.79%   |
| Sun                     | 1         | 0.39%   |
| Sceptre Tech            | 1         | 0.39%   |
| Planar                  | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| Microstep               | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| Insignia                | 1         | 0.39%   |
| EVE                     | 1         | 0.39%   |
| CSO                     | 1         | 0.39%   |
| Chi Mei Optoelectronics | 1         | 0.39%   |
| BOE Technology Group    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.54%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.81%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 5         | 1.81%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 1.09%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 1.09%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 3         | 1.09%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch          | 3         | 1.09%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 1.09%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 3         | 1.09%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 1.09%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 1.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 2         | 0.72%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.72%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.72%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.72%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.72%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch              | 2         | 0.72%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.72%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.72%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.72%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch        | 2         | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 2         | 0.72%   |
| Unknown                                                           | 2         | 0.72%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch     | 1         | 0.36%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch     | 1         | 0.36%   |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch             | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch           | 1         | 0.36%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch           | 1         | 0.36%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 1         | 0.36%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch           | 1         | 0.36%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch           | 1         | 0.36%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch    | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 119       | 52.42%  |
| 3840x2160 (4K)     | 19        | 8.37%   |
| 1366x768 (WXGA)    | 19        | 8.37%   |
| 2560x1440 (QHD)    | 16        | 7.05%   |
| 1600x900 (HD+)     | 11        | 4.85%   |
| 1920x1200 (WUXGA)  | 7         | 3.08%   |
| Unknown            | 6         | 2.64%   |
| 3440x1440          | 5         | 2.2%    |
| 3840x1080          | 4         | 1.76%   |
| 2560x1080          | 4         | 1.76%   |
| 7680x2160          | 2         | 0.88%   |
| 3840x1200          | 2         | 0.88%   |
| 1680x1050 (WSXGA+) | 2         | 0.88%   |
| 1440x900 (WXGA+)   | 2         | 0.88%   |
| 9600x2160          | 1         | 0.44%   |
| 6400x2160          | 1         | 0.44%   |
| 3840x1600          | 1         | 0.44%   |
| 2880x1800          | 1         | 0.44%   |
| 2560x1600          | 1         | 0.44%   |
| 2048x1152          | 1         | 0.44%   |
| 1920x540           | 1         | 0.44%   |
| 1280x800 (WXGA)    | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 19.29%  |
| 14      | 35        | 13.78%  |
| 24      | 29        | 11.42%  |
| 27      | 26        | 10.24%  |
| 13      | 23        | 9.06%   |
| 23      | 18        | 7.09%   |
| Unknown | 17        | 6.69%   |
| 31      | 9         | 3.54%   |
| 21      | 9         | 3.54%   |
| 34      | 7         | 2.76%   |
| 12      | 5         | 1.97%   |
| 20      | 4         | 1.57%   |
| 32      | 3         | 1.18%   |
| 17      | 3         | 1.18%   |
| 54      | 2         | 0.79%   |
| 47      | 2         | 0.79%   |
| 22      | 2         | 0.79%   |
| 18      | 2         | 0.79%   |
| 16      | 2         | 0.79%   |
| 84      | 1         | 0.39%   |
| 49      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 39      | 1         | 0.39%   |
| 37      | 1         | 0.39%   |
| 25      | 1         | 0.39%   |
| 19      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 41.46%  |
| 501-600     | 62        | 25.2%   |
| 401-500     | 17        | 6.91%   |
| Unknown     | 17        | 6.91%   |
| 601-700     | 14        | 5.69%   |
| 201-300     | 12        | 4.88%   |
| 701-800     | 10        | 4.07%   |
| 1001-1500   | 5         | 2.03%   |
| 801-900     | 3         | 1.22%   |
| 351-400     | 3         | 1.22%   |
| 1501-2000   | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 79.41%  |
| 16/10   | 17        | 8.33%   |
| Unknown | 15        | 7.35%   |
| 21/9    | 8         | 3.92%   |
| 32/9    | 1         | 0.49%   |
| 3/2     | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 20.4%   |
| 101-110        | 48        | 19.2%   |
| 201-250        | 45        | 18%     |
| 301-350        | 26        | 10.4%   |
| 351-500        | 18        | 7.2%    |
| Unknown        | 17        | 6.8%    |
| 251-300        | 10        | 4%      |
| 71-80          | 7         | 2.8%    |
| 151-200        | 7         | 2.8%    |
| 501-1000       | 6         | 2.4%    |
| 61-70          | 5         | 2%      |
| More than 1000 | 3         | 1.2%    |
| 121-130        | 3         | 1.2%    |
| 111-120        | 3         | 1.2%    |
| 141-150        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 89        | 36.48%  |
| 51-100        | 75        | 30.74%  |
| 101-120       | 37        | 15.16%  |
| Unknown       | 17        | 6.97%   |
| 161-240       | 15        | 6.15%   |
| More than 240 | 7         | 2.87%   |
| 1-50          | 4         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 129       | 60.85%  |
| 2     | 55        | 25.94%  |
| 0     | 15        | 7.08%   |
| 3     | 13        | 6.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 162       | 52.6%   |
| Realtek Semiconductor             | 62        | 20.13%  |
| Lenovo                            | 19        | 6.17%   |
| Qualcomm Atheros                  | 13        | 4.22%   |
| Broadcom                          | 8         | 2.6%    |
| Broadcom Limited                  | 5         | 1.62%   |
| MediaTek                          | 4         | 1.3%    |
| ASIX Electronics                  | 4         | 1.3%    |
| Aquantia                          | 3         | 0.97%   |
| TP-Link                           | 2         | 0.65%   |
| Sierra Wireless                   | 2         | 0.65%   |
| Ralink Technology                 | 2         | 0.65%   |
| Ralink                            | 2         | 0.65%   |
| Marvell Technology Group          | 2         | 0.65%   |
| Huawei Technologies               | 2         | 0.65%   |
| Dell                              | 2         | 0.65%   |
| Xiaomi                            | 1         | 0.32%   |
| Samsung Electronics               | 1         | 0.32%   |
| Qualcomm Atheros Communications   | 1         | 0.32%   |
| Qualcomm                          | 1         | 0.32%   |
| Microchip Technology              | 1         | 0.32%   |
| Micro Star International          | 1         | 0.32%   |
| Luminary Micro                    | 1         | 0.32%   |
| ICS Advent                        | 1         | 0.32%   |
| IBM                               | 1         | 0.32%   |
| Google                            | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| DisplayLink                       | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |
| Arduino SA                        | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 9.62%   |
| Intel Wireless 8265 / 8275                                             | 16        | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 16        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 16        | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 3.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.64%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 10        | 2.4%    |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 2.4%    |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.4%    |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 2.4%    |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 2.16%   |
| Intel Wireless 8260                                                    | 7         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.44%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.44%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.72%   |
| Lenovo ThinkPad Lan                                                    | 3         | 0.72%   |
| Lenovo Lenovo USB-C to LAN                                             | 3         | 0.72%   |
| Intel Wireless 7265                                                    | 3         | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.72%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.72%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.72%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.72%   |
| Intel Ethernet Connection (17) I219-LM                                 | 3         | 0.72%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.72%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter           | 3         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 72.35%  |
| Realtek Semiconductor           | 13        | 7.65%   |
| Qualcomm Atheros                | 12        | 7.06%   |
| Broadcom                        | 5         | 2.94%   |
| MediaTek                        | 4         | 2.35%   |
| TP-Link                         | 2         | 1.18%   |
| Sierra Wireless                 | 2         | 1.18%   |
| Ralink Technology               | 2         | 1.18%   |
| Ralink                          | 2         | 1.18%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |
| Micro Star International        | 1         | 0.59%   |
| Dell                            | 1         | 0.59%   |
| D-Link                          | 1         | 0.59%   |
| Broadcom Limited                | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                   | 16        | 9.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                            | 16        | 9.41%   |
| Intel Comet Lake PCH CNVi WiFi                               | 15        | 8.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                     | 14        | 8.24%   |
| Intel Wi-Fi 6 AX200                                          | 11        | 6.47%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 10        | 5.88%   |
| Intel Wireless 8260                                          | 7         | 4.12%   |
| Intel Wi-Fi 6 AX201                                          | 6         | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                 | 6         | 3.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]      | 4         | 2.35%   |
| Intel Centrino Ultimate-N 6300                               | 4         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 3         | 1.76%   |
| Intel Wireless 7265                                          | 3         | 1.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]    | 3         | 1.76%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 2         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 2         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 2         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 2         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter   | 2         | 1.18%   |
| Intel Wireless 7260                                          | 2         | 1.18%   |
| Intel Wireless 3165                                          | 2         | 1.18%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                       | 1         | 0.59%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                          | 1         | 0.59%   |
| Sierra Wireless EM7565 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.59%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem              | 1         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter     | 1         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter              | 1         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                   | 1         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 1         | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 1         | 0.59%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter              | 1         | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 1         | 0.59%   |
| Ralink RT5572 Wireless Adapter                               | 1         | 0.59%   |
| Ralink RT5372 Wireless Adapter                               | 1         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                    | 1         | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                    | 1         | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter   | 1         | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                              | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter             | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 125       | 55.8%   |
| Realtek Semiconductor    | 54        | 24.11%  |
| Lenovo                   | 19        | 8.48%   |
| Broadcom Limited         | 4         | 1.79%   |
| ASIX Electronics         | 4         | 1.79%   |
| Broadcom                 | 3         | 1.34%   |
| Aquantia                 | 3         | 1.34%   |
| Qualcomm Atheros         | 2         | 0.89%   |
| Marvell Technology Group | 2         | 0.89%   |
| Xiaomi                   | 1         | 0.45%   |
| Qualcomm                 | 1         | 0.45%   |
| ICS Advent               | 1         | 0.45%   |
| IBM                      | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |
| Google                   | 1         | 0.45%   |
| DisplayLink              | 1         | 0.45%   |
| Dell                     | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 40        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 4.58%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 4.17%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 4.17%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 4.17%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 3.75%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.5%    |
| Intel I350 Gigabit Network Connection                                          | 5         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 2.08%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.67%   |
| Lenovo ThinkPad Lan                                                            | 3         | 1.25%   |
| Lenovo Lenovo USB-C to LAN                                                     | 3         | 1.25%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.25%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.25%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.25%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.25%   |
| Intel Ethernet Connection (17) I219-LM                                         | 3         | 1.25%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 1.25%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.83%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.83%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.83%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.83%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.83%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.83%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 51.85%  |
| WiFi     | 163       | 46.44%  |
| Modem    | 6         | 1.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 50.23%  |
| Ethernet | 107       | 49.31%  |
| Modem    | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 127       | 62.87%  |
| 1     | 55        | 27.23%  |
| 3     | 11        | 5.45%   |
| 4     | 4         | 1.98%   |
| 6     | 2         | 0.99%   |
| 132   | 1         | 0.5%    |
| 22    | 1         | 0.5%    |
| 8     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 88.18%  |
| Yes  | 24        | 11.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 71.85%  |
| Cambridge Silicon Radio         | 8         | 5.93%   |
| Broadcom                        | 7         | 5.19%   |
| Qualcomm Atheros Communications | 5         | 3.7%    |
| Realtek Semiconductor           | 4         | 2.96%   |
| IMC Networks                    | 4         | 2.96%   |
| Foxconn / Hon Hai               | 3         | 2.22%   |
| ASUSTek Computer                | 3         | 2.22%   |
| Ralink                          | 1         | 0.74%   |
| Micro Star International        | 1         | 0.74%   |
| MediaTek                        | 1         | 0.74%   |
| Dell                            | 1         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 35        | 25.93%  |
| Intel Bluetooth wireless interface                                                  | 23        | 17.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 15.56%  |
| Intel AX200 Bluetooth                                                               | 10        | 7.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.96%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.22%   |
| Intel AX211 Bluetooth                                                               | 3         | 2.22%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.48%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.48%   |
| ASUS BCM20702A0                                                                     | 2         | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.74%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.74%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.74%   |
| MediaTek Wireless_Device                                                            | 1         | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.74%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.74%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.74%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.74%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.74%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.74%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 169       | 52.16%  |
| Nvidia                    | 58        | 17.9%   |
| AMD                       | 29        | 8.95%   |
| Lenovo                    | 17        | 5.25%   |
| GN Netcom                 | 7         | 2.16%   |
| Plantronics               | 6         | 1.85%   |
| JMTek                     | 5         | 1.54%   |
| Creative Technology       | 4         | 1.23%   |
| Texas Instruments         | 3         | 0.93%   |
| Generalplus Technology    | 3         | 0.93%   |
| Creative Labs             | 3         | 0.93%   |
| Realtek Semiconductor     | 2         | 0.62%   |
| Logitech                  | 2         | 0.62%   |
| C-Media Electronics       | 2         | 0.62%   |
| Tenx Technology           | 1         | 0.31%   |
| SteelSeries ApS           | 1         | 0.31%   |
| Sennheiser Communications | 1         | 0.31%   |
| RODE Microphones          | 1         | 0.31%   |
| Hewlett-Packard           | 1         | 0.31%   |
| Google                    | 1         | 0.31%   |
| Giga-Byte Technology      | 1         | 0.31%   |
| Focusrite-Novation        | 1         | 0.31%   |
| Dynex                     | 1         | 0.31%   |
| DSEA A/S                  | 1         | 0.31%   |
| Dell                      | 1         | 0.31%   |
| Corsair                   | 1         | 0.31%   |
| Blue Microphones          | 1         | 0.31%   |
| ASUSTek Computer          | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 25        | 7.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 5.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 4.57%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 4.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 4.57%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 12        | 3.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.57%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.71%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6         | 1.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.43%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.43%   |
| Plantronics BT600                                                          | 4         | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.14%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.14%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.14%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.86%   |
| Nvidia GA107 High Definition Audio Controller                              | 3         | 0.86%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.86%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.86%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.86%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 32.98%  |
| SK hynix            | 21        | 22.34%  |
| Crucial             | 9         | 9.57%   |
| Micron Technology   | 8         | 8.51%   |
| Kingston            | 7         | 7.45%   |
| Corsair             | 5         | 5.32%   |
| Unknown             | 2         | 2.13%   |
| GOODRAM             | 2         | 2.13%   |
| Unknown (0x0B5E)    | 1         | 1.06%   |
| Unknown (0x0205)    | 1         | 1.06%   |
| Transcend           | 1         | 1.06%   |
| Smart               | 1         | 1.06%   |
| Patriot             | 1         | 1.06%   |
| Innodisk            | 1         | 1.06%   |
| Hewlett-Packard     | 1         | 1.06%   |
| Elpida              | 1         | 1.06%   |
| Unknown             | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2%      |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 2%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2%      |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 2%      |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 2%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2%      |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s            | 2         | 2%      |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s            | 2         | 2%      |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 2%      |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1%      |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1%      |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1%      |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 1%      |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 1%      |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1%      |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 1%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1%      |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 1%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1%      |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1%      |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 1%      |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1%      |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 1%      |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1%      |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1%      |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1%      |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB DIMM DDR4 2400MT/s           | 1         | 1%      |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1%      |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1%      |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1%      |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                       | 1         | 1%      |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1         | 1%      |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1%      |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                    | 1         | 1%      |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1%      |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                      | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 50        | 64.94%  |
| DDR3   | 21        | 27.27%  |
| SDRAM  | 2         | 2.6%    |
| LPDDR4 | 1         | 1.3%    |
| LPDDR3 | 1         | 1.3%    |
| DRAM   | 1         | 1.3%    |
| DDR5   | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 57.89%  |
| DIMM         | 31        | 40.79%  |
| Row Of Chips | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 33.33%  |
| 16384 | 24        | 28.57%  |
| 4096  | 17        | 20.24%  |
| 32768 | 13        | 15.48%  |
| 65536 | 1         | 1.19%   |
| 2048  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 24.1%   |
| 1600  | 16        | 19.28%  |
| 2667  | 13        | 15.66%  |
| 2400  | 12        | 14.46%  |
| 1333  | 6         | 7.23%   |
| 2133  | 4         | 4.82%   |
| 3600  | 3         | 3.61%   |
| 3266  | 2         | 2.41%   |
| 2666  | 2         | 2.41%   |
| 4800  | 1         | 1.2%    |
| 3933  | 1         | 1.2%    |
| 2933  | 1         | 1.2%    |
| 1866  | 1         | 1.2%    |
| 1334  | 1         | 1.2%    |

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


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w   | 1         | 14.29%  |
| HP LaserJet Pro M118-M119          | 1         | 14.29%  |
| HP ENVY 4500 series                | 1         | 14.29%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 14.29%  |
| Canon E560 series                  | 1         | 14.29%  |
| Canon CanoScan LiDE 300            | 1         | 14.29%  |
| Brother DCP-1610W                  | 1         | 14.29%  |

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
| Chicony Electronics                    | 41        | 27.89%  |
| IMC Networks                           | 22        | 14.97%  |
| Bison Electronics                      | 13        | 8.84%   |
| Realtek Semiconductor                  | 11        | 7.48%   |
| Logitech                               | 9         | 6.12%   |
| Sunplus Innovation Technology          | 7         | 4.76%   |
| Microdia                               | 7         | 4.76%   |
| Lite-On Technology                     | 4         | 2.72%   |
| Hopewin Electronic Material            | 4         | 2.72%   |
| Acer                                   | 4         | 2.72%   |
| Suyin                                  | 3         | 2.04%   |
| Samsung Electronics                    | 3         | 2.04%   |
| Luxvisions Innotech Limited            | 3         | 2.04%   |
| Ruision                                | 2         | 1.36%   |
| Microsoft                              | 2         | 1.36%   |
| Generalplus Technology                 | 2         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.36%   |
| Syntek                                 | 1         | 0.68%   |
| Remo Tech                              | 1         | 0.68%   |
| Quanta                                 | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| KYE Systems (Mouse Systems)            | 1         | 0.68%   |
| Jieli Technology                       | 1         | 0.68%   |
| Creative Technology                    | 1         | 0.68%   |
| ARC International                      | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 22        | 14.86%  |
| IMC Networks Integrated Camera                    | 19        | 12.84%  |
| Realtek Integrated_Webcam_HD                      | 7         | 4.73%   |
| Bison Integrated Camera                           | 7         | 4.73%   |
| Bison SunplusIT Integrated Camera                 | 5         | 3.38%   |
| Logitech HD Pro Webcam C920                       | 4         | 2.7%    |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 4         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)           | 4         | 2.7%    |
| Sunplus Integrated_Webcam_HD                      | 3         | 2.03%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 2.03%   |
| Lite-On Integrated Camera                         | 3         | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.03%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 2.03%   |
| Chicony HP HD Camera                              | 3         | 2.03%   |
| Ruision UVC Camera                                | 2         | 1.35%   |
| Microdia Webcam                                   | 2         | 1.35%   |
| Microdia Integrated Webcam                        | 2         | 1.35%   |
| Generalplus GENERAL WEBCAM                        | 2         | 1.35%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.35%   |
| Acer Integrated IR Camera                         | 2         | 1.35%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.68%   |
| Suyin RGBIR Camera                                | 1         | 0.68%   |
| Suyin Integrated_Webcam_HD                        | 1         | 0.68%   |
| Suyin HP Truevision HD                            | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.68%   |
| Sunplus Integrated Webcam                         | 1         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.68%   |
| Sunplus DICOTA 4K                                 | 1         | 0.68%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.68%   |
| Realtek USB Camera                                | 1         | 0.68%   |
| Realtek NexiGo N660P FHD Webcam                   | 1         | 0.68%   |
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
| Synaptics                  | 37        | 64.91%  |
| Validity Sensors           | 14        | 24.56%  |
| Shenzhen Goodix Technology | 3         | 5.26%   |
| Upek                       | 2         | 3.51%   |
| Elan Microelectronics      | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 43.86%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.51%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors VFS491                                                    | 1         | 1.75%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.75%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.75%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.75%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.75%   |

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
| 0     | 94        | 46.08%  |
| 1     | 81        | 39.71%  |
| 2     | 20        | 9.8%    |
| 3     | 6         | 2.94%   |
| 5     | 2         | 0.98%   |
| 4     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 39.31%  |
| Graphics card            | 21        | 14.48%  |
| Net/wireless             | 14        | 9.66%   |
| Chipcard                 | 13        | 8.97%   |
| Unassigned class         | 10        | 6.9%    |
| Communication controller | 6         | 4.14%   |
| Card reader              | 6         | 4.14%   |
| Multimedia controller    | 5         | 3.45%   |
| Net/ethernet             | 4         | 2.76%   |
| Bluetooth                | 4         | 2.76%   |
| Storage                  | 2         | 1.38%   |
| Storage/ide              | 1         | 0.69%   |
| Sound                    | 1         | 0.69%   |
| Network                  | 1         | 0.69%   |

