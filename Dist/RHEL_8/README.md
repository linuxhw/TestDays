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

Total: 339

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook Fury 16 G10 Mobile... | Notebook    | [0d1e21ed35](https://linux-hardware.org/?probe=0d1e21ed35) | Oct 18, 2025 |
| Dell          | 05225G A03                  | Desktop     | [242afaa57e](https://linux-hardware.org/?probe=242afaa57e) | Jul 23, 2025 |
| Unknown       | Unknown                     | Notebook    | [b1f831d148](https://linux-hardware.org/?probe=b1f831d148) | Jul 09, 2025 |
| FUXI          | EGS-01 E63448-400           | Server      | [a5944ff110](https://linux-hardware.org/?probe=a5944ff110) | Jun 23, 2025 |
| FUXI          | EGS-01 E63448-400           | Server      | [7aa63d7083](https://linux-hardware.org/?probe=7aa63d7083) | Jun 23, 2025 |
| Dell          | 0GXJYG A02                  | Server      | [1dd09f7499](https://linux-hardware.org/?probe=1dd09f7499) | Jun 02, 2025 |
| HP            | 8754                        | Mini pc     | [59b5f808f5](https://linux-hardware.org/?probe=59b5f808f5) | May 28, 2025 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6fcbd16acf](https://linux-hardware.org/?probe=6fcbd16acf) | May 21, 2025 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [8f1b8a29c4](https://linux-hardware.org/?probe=8f1b8a29c4) | May 06, 2025 |
| Dell          | 006CX9 A02                  | Desktop     | [b0e8c75b5b](https://linux-hardware.org/?probe=b0e8c75b5b) | Apr 09, 2025 |
| Dell          | 006CX9 A02                  | Desktop     | [9dfe2b7429](https://linux-hardware.org/?probe=9dfe2b7429) | Apr 04, 2025 |
| Dell          | 006CX9 A02                  | Desktop     | [6660d03216](https://linux-hardware.org/?probe=6660d03216) | Mar 28, 2025 |
| Dell          | 006CX9 A02                  | Desktop     | [4f2533ac03](https://linux-hardware.org/?probe=4f2533ac03) | Mar 28, 2025 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS1... | Notebook    | [42d17fcd67](https://linux-hardware.org/?probe=42d17fcd67) | Feb 14, 2025 |
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
| 4.18.0-240.10.1.el8_3.x86_64  | 14        | 5.51%   |
| 4.18.0-240.1.1.el8_3.x86_64   | 14        | 5.51%   |
| 4.18.0-348.20.1.el8_5.x86_64  | 12        | 4.72%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 11        | 4.33%   |
| 4.18.0-305.el8.x86_64         | 10        | 3.94%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 10        | 3.94%   |
| 4.18.0-80.11.2.el8_0.x86_64   | 9         | 3.54%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 9         | 3.54%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 8         | 3.15%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 8         | 3.15%   |
| 4.18.0-305.19.1.el8_4.x86_64  | 8         | 3.15%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 7         | 2.76%   |
| 4.18.0-193.el8.x86_64         | 7         | 2.76%   |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 2.36%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 6         | 2.36%   |
| 4.18.0-193.19.1.el8_2.x86_64  | 6         | 2.36%   |
| 4.18.0-147.5.1.el8_1.x86_64   | 6         | 2.36%   |
| 4.18.0-147.3.1.el8_1.x86_64   | 6         | 2.36%   |
| 4.18.0-372.9.1.el8.x86_64     | 5         | 1.97%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 5         | 1.97%   |
| 4.18.0-193.6.3.el8_2.x86_64   | 5         | 1.97%   |
| 4.18.0-147.el8.x86_64         | 5         | 1.97%   |
| 4.18.0-553.16.1.el8_10.x86_64 | 4         | 1.57%   |
| 4.18.0-348.7.1.el8_5.x86_64   | 4         | 1.57%   |
| 4.18.0-305.25.1.el8_4.x86_64  | 4         | 1.57%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 4         | 1.57%   |
| 4.18.0-193.28.1.el8_2.x86_64  | 4         | 1.57%   |
| 4.18.0-477.10.1.el8_8.x86_64  | 3         | 1.18%   |
| 4.18.0-305.17.1.el8_4.x86_64  | 3         | 1.18%   |
| 4.18.0-147.8.1.el8_1.x86_64   | 3         | 1.18%   |
| 4.18.0-553.36.1.el8_10.x86_64 | 2         | 0.79%   |
| 4.18.0-513.18.1.el8_9.x86_64  | 2         | 0.79%   |
| 4.18.0-477.27.1.el8_8.x86_64  | 2         | 0.79%   |
| 4.18.0-477.21.1.el8_8.x86_64  | 2         | 0.79%   |
| 4.18.0-477.15.1.el8_8.x86_64  | 2         | 0.79%   |
| 4.18.0-372.32.1.el8_6.x86_64  | 2         | 0.79%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 2         | 0.79%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 2         | 0.79%   |
| 4.18.0-348.el8.x86_64         | 2         | 0.79%   |
| 4.18.0-240.8.1.el8_3.x86_64   | 2         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 203       | 96.67%  |
| 6.17.3   | 1         | 0.48%   |
| 5.9.1    | 1         | 0.48%   |
| 5.13.13  | 1         | 0.48%   |
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
| 4.18    | 203       | 96.67%  |
| 5.13    | 2         | 0.95%   |
| 6.17    | 1         | 0.48%   |
| 5.9     | 1         | 0.48%   |
| 5.10    | 1         | 0.48%   |
| 4.19    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 209       | 99.52%  |
| Unknown | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 179       | 82.49%  |
| Unknown       | 21        | 9.68%   |
| GNOME Classic | 9         | 4.15%   |
| KDE5          | 5         | 2.3%    |
| KDE           | 2         | 0.92%   |
| MATE          | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 55.76%  |
| Wayland | 86        | 39.63%  |
| Unknown | 10        | 4.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 70.78%  |
| GDM     | 62        | 28.31%  |
| SDDM    | 1         | 0.46%   |
| LightDM | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 142       | 66.05%  |
| en_GB   | 13        | 6.05%   |
| Unknown | 13        | 6.05%   |
| en_IN   | 6         | 2.79%   |
| fr_FR   | 5         | 2.33%   |
| de_DE   | 5         | 2.33%   |
| pl_PL   | 4         | 1.86%   |
| ru_RU   | 3         | 1.4%    |
| pt_BR   | 2         | 0.93%   |
| nl_NL   | 2         | 0.93%   |
| fr_CA   | 2         | 0.93%   |
| es_ES   | 2         | 0.93%   |
| es_AR   | 2         | 0.93%   |
| en_IE   | 2         | 0.93%   |
| sl_SI   | 1         | 0.47%   |
| nl_BE   | 1         | 0.47%   |
| ko_KR   | 1         | 0.47%   |
| ja_JP   | 1         | 0.47%   |
| it_IT   | 1         | 0.47%   |
| es_MX   | 1         | 0.47%   |
| es_EC   | 1         | 0.47%   |
| es_CO   | 1         | 0.47%   |
| en_NZ   | 1         | 0.47%   |
| en_DK   | 1         | 0.47%   |
| de_CH   | 1         | 0.47%   |
| cs_CZ   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 79.44%  |
| BIOS | 44        | 20.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 186       | 87.32%  |
| Ext4    | 18        | 8.45%   |
| Unknown | 8         | 3.76%   |
| Ext3    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 65.14%  |
| GPT     | 71        | 32.57%  |
| MBR     | 5         | 2.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 196       | 91.59%  |
| Yes       | 18        | 8.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 90.19%  |
| Yes       | 21        | 9.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 84        | 40%     |
| Dell                | 34        | 16.19%  |
| Hewlett-Packard     | 29        | 13.81%  |
| ASUSTek Computer    | 21        | 10%     |
| Gigabyte Technology | 9         | 4.29%   |
| Supermicro          | 5         | 2.38%   |
| ASRock              | 5         | 2.38%   |
| MSI                 | 4         | 1.9%    |
| Intel               | 3         | 1.43%   |
| Unknown             | 3         | 1.43%   |
| Sony                | 2         | 0.95%   |
| TUXEDO              | 1         | 0.48%   |
| Toshiba             | 1         | 0.48%   |
| Timi                | 1         | 0.48%   |
| IBM                 | 1         | 0.48%   |
| Getac               | 1         | 0.48%   |
| FUXI                | 1         | 0.48%   |
| CX / Air Computers. | 1         | 0.48%   |
| AZW                 | 1         | 0.48%   |
| AMI                 | 1         | 0.48%   |
| Alienware           | 1         | 0.48%   |
| Acer                | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X         | 4         | 1.9%    |
| ASUS All Series                             | 4         | 1.9%    |
| Unknown                                     | 4         | 1.9%    |
| Supermicro X10DRi                           | 2         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401    | 2         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00    | 2         | 0.95%   |
| Lenovo ThinkPad T590 20N5S2NC0N             | 2         | 0.95%   |
| Lenovo ThinkPad T490s 20NYS7K91R            | 2         | 0.95%   |
| Lenovo ThinkPad T480s 20L8S2N800            | 2         | 0.95%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08       | 2         | 0.95%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q         | 2         | 0.95%   |
| HP EliteBook 8460p                          | 2         | 0.95%   |
| Dell Precision 7960 Tower                   | 2         | 0.95%   |
| Dell Latitude E6430                         | 2         | 0.95%   |
| Dell Latitude 5300                          | 2         | 0.95%   |
| TUXEDO N13xWU                               | 1         | 0.48%   |
| Toshiba Satellite Pro R50-C                 | 1         | 0.48%   |
| Timi TM1707                                 | 1         | 0.48%   |
| Supermicro X9DAi                            | 1         | 0.48%   |
| Supermicro X7DW3                            | 1         | 0.48%   |
| Supermicro X10SRA                           | 1         | 0.48%   |
| Sony VPCEB4L1R                              | 1         | 0.48%   |
| Sony VPCEB23FM                              | 1         | 0.48%   |
| MSI MS-7B51                                 | 1         | 0.48%   |
| MSI MS-7B33                                 | 1         | 0.48%   |
| MSI MS-7A37                                 | 1         | 0.48%   |
| MSI MS-7752                                 | 1         | 0.48%   |
| Lenovo Z40-70 20366                         | 1         | 0.48%   |
| Lenovo Yoga C640-13IML 81UE                 | 1         | 0.48%   |
| Lenovo ThinkSystem SR645                    | 1         | 0.48%   |
| Lenovo ThinkStation P500 30A7000WUS         | 1         | 0.48%   |
| Lenovo ThinkPad X390 Yoga 20NQS18Y00        | 1         | 0.48%   |
| Lenovo ThinkPad X270 20HN001EMC             | 1         | 0.48%   |
| Lenovo ThinkPad X250 20CLS0H807             | 1         | 0.48%   |
| Lenovo ThinkPad X230 Tablet 34373KU         | 1         | 0.48%   |
| Lenovo ThinkPad X201 3680PKS                | 1         | 0.48%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100      | 1         | 0.48%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G  | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20UAS2H10S  | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 73        | 34.76%  |
| Dell Precision      | 14        | 6.67%   |
| Dell Latitude       | 10        | 4.76%   |
| HP ZBook            | 5         | 2.38%   |
| HP EliteBook        | 5         | 2.38%   |
| ASUS All            | 4         | 1.9%    |
| Unknown             | 4         | 1.9%    |
| Lenovo ThinkCentre  | 3         | 1.43%   |
| Dell PowerEdge      | 3         | 1.43%   |
| Dell Inspiron       | 3         | 1.43%   |
| ASUS ROG            | 3         | 1.43%   |
| ASUS PRIME          | 3         | 1.43%   |
| Supermicro X10DRi   | 2         | 0.95%   |
| HP Z230             | 2         | 0.95%   |
| HP ProBook          | 2         | 0.95%   |
| ASUS VivoBook       | 2         | 0.95%   |
| TUXEDO N13xWU       | 1         | 0.48%   |
| Toshiba Satellite   | 1         | 0.48%   |
| Timi TM1707         | 1         | 0.48%   |
| Supermicro X9DAi    | 1         | 0.48%   |
| Supermicro X7DW3    | 1         | 0.48%   |
| Supermicro X10SRA   | 1         | 0.48%   |
| Sony VPCEB4L1R      | 1         | 0.48%   |
| Sony VPCEB23FM      | 1         | 0.48%   |
| MSI MS-7B51         | 1         | 0.48%   |
| MSI MS-7B33         | 1         | 0.48%   |
| MSI MS-7A37         | 1         | 0.48%   |
| MSI MS-7752         | 1         | 0.48%   |
| Lenovo Z40-70       | 1         | 0.48%   |
| Lenovo Yoga         | 1         | 0.48%   |
| Lenovo ThinkSystem  | 1         | 0.48%   |
| Lenovo ThinkStation | 1         | 0.48%   |
| Lenovo S40-40       | 1         | 0.48%   |
| Lenovo Legion       | 1         | 0.48%   |
| Lenovo 10SFS03200   | 1         | 0.48%   |
| Intel NUC12SNKi72   | 1         | 0.48%   |
| Intel NUC10i7FNK    | 1         | 0.48%   |
| Intel DX79SR        | 1         | 0.48%   |
| IBM FAB2            | 1         | 0.48%   |
| HP Z840             | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 38        | 18.1%   |
| 2019 | 34        | 16.19%  |
| 2018 | 29        | 13.81%  |
| 2012 | 15        | 7.14%   |
| 2016 | 14        | 6.67%   |
| 2015 | 14        | 6.67%   |
| 2021 | 13        | 6.19%   |
| 2017 | 12        | 5.71%   |
| 2014 | 8         | 3.81%   |
| 2011 | 8         | 3.81%   |
| 2013 | 7         | 3.33%   |
| 2022 | 5         | 2.38%   |
| 2023 | 4         | 1.9%    |
| 2024 | 3         | 1.43%   |
| 2010 | 3         | 1.43%   |
| 2025 | 2         | 0.95%   |
| 2007 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 126       | 60%     |
| Desktop     | 61        | 29.05%  |
| Server      | 11        | 5.24%   |
| Mini pc     | 7         | 3.33%   |
| Convertible | 4         | 1.9%    |
| All in one  | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 185       | 86.85%  |
| Enabled  | 28        | 13.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 210       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 66        | 30.41%  |
| 16.01-24.0      | 35        | 16.13%  |
| 64.01-256.0     | 34        | 15.67%  |
| 8.01-16.0       | 33        | 15.21%  |
| 4.01-8.0        | 29        | 13.36%  |
| 24.01-32.0      | 8         | 3.69%   |
| 3.01-4.0        | 6         | 2.76%   |
| More than 256.0 | 5         | 2.3%    |
| Unknown         | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 89        | 37.39%  |
| 2.01-3.0        | 40        | 16.81%  |
| 8.01-16.0       | 38        | 15.97%  |
| 3.01-4.0        | 37        | 15.55%  |
| 1.01-2.0        | 17        | 7.14%   |
| 16.01-24.0      | 6         | 2.52%   |
| 24.01-32.0      | 4         | 1.68%   |
| 0.51-1.0        | 3         | 1.26%   |
| More than 256.0 | 1         | 0.42%   |
| 32.01-64.0      | 1         | 0.42%   |
| 64.01-256.0     | 1         | 0.42%   |
| Unknown         | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 58.9%   |
| 2      | 49        | 22.37%  |
| 3      | 18        | 8.22%   |
| 4      | 8         | 3.65%   |
| 5      | 6         | 2.74%   |
| 6      | 3         | 1.37%   |
| 8      | 2         | 0.91%   |
| 7      | 2         | 0.91%   |
| 10     | 1         | 0.46%   |
| 0      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 77.83%  |
| Yes       | 47        | 22.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 90.52%  |
| No        | 20        | 9.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 79.05%  |
| No        | 44        | 20.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 62.96%  |
| No        | 80        | 37.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 47        | 22.38%  |
| India        | 19        | 9.05%   |
| UK           | 14        | 6.67%   |
| Germany      | 13        | 6.19%   |
| Czechia      | 11        | 5.24%   |
| Canada       | 10        | 4.76%   |
| France       | 8         | 3.81%   |
| Poland       | 6         | 2.86%   |
| Switzerland  | 4         | 1.9%    |
| Netherlands  | 4         | 1.9%    |
| Mexico       | 4         | 1.9%    |
| Italy        | 4         | 1.9%    |
| Brazil       | 4         | 1.9%    |
| Spain        | 3         | 1.43%   |
| South Africa | 3         | 1.43%   |
| Russia       | 3         | 1.43%   |
| Lithuania    | 3         | 1.43%   |
| Finland      | 3         | 1.43%   |
| China        | 3         | 1.43%   |
| Australia    | 3         | 1.43%   |
| Argentina    | 3         | 1.43%   |
| Ukraine      | 2         | 0.95%   |
| South Korea  | 2         | 0.95%   |
| Romania      | 2         | 0.95%   |
| Japan        | 2         | 0.95%   |
| Egypt        | 2         | 0.95%   |
| Colombia     | 2         | 0.95%   |
| Chile        | 2         | 0.95%   |
| Turkmenistan | 1         | 0.48%   |
| Sweden       | 1         | 0.48%   |
| Slovenia     | 1         | 0.48%   |
| Singapore    | 1         | 0.48%   |
| Saudi Arabia | 1         | 0.48%   |
| Portugal     | 1         | 0.48%   |
| Pakistan     | 1         | 0.48%   |
| New Zealand  | 1         | 0.48%   |
| Nepal        | 1         | 0.48%   |
| Myanmar      | 1         | 0.48%   |
| Morocco      | 1         | 0.48%   |
| Luxembourg   | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Prague       | 9         | 4%      |
| Bengaluru    | 4         | 1.78%   |
| Turku        | 3         | 1.33%   |
| San Jose     | 3         | 1.33%   |
| Ottawa       | 3         | 1.33%   |
| Munich       | 3         | 1.33%   |
| Mexico City  | 3         | 1.33%   |
| Berlin       | 3         | 1.33%   |
| Sorel-Tracy  | 2         | 0.89%   |
| Montreal     | 2         | 0.89%   |
| Milan        | 2         | 0.89%   |
| Leeds        | 2         | 0.89%   |
| Kyiv         | 2         | 0.89%   |
| Didcot       | 2         | 0.89%   |
| Des Moines   | 2         | 0.89%   |
| Chicago      | 2         | 0.89%   |
| Chennai      | 2         | 0.89%   |
| Zaragoza     | 1         | 0.44%   |
| Yongin-si    | 1         | 0.44%   |
| Wroclaw      | 1         | 0.44%   |
| Wiesbaden    | 1         | 0.44%   |
| Webster      | 1         | 0.44%   |
| Wayne        | 1         | 0.44%   |
| Wagholi      | 1         | 0.44%   |
| Vardenis     | 1         | 0.44%   |
| Vaglio       | 1         | 0.44%   |
| Udaipur      | 1         | 0.44%   |
| Toronto      | 1         | 0.44%   |
| Tiruchi      | 1         | 0.44%   |
| Temuco       | 1         | 0.44%   |
| Temara       | 1         | 0.44%   |
| Tauranga     | 1         | 0.44%   |
| Taringa      | 1         | 0.44%   |
| Talkha       | 1         | 0.44%   |
| Syracuse     | 1         | 0.44%   |
| Suffolk      | 1         | 0.44%   |
| Stuttgart    | 1         | 0.44%   |
| Streatham    | 1         | 0.44%   |
| Strasbourg   | 1         | 0.44%   |
| Stellenbosch | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 62        | 109    | 19.38%  |
| WDC                         | 37        | 63     | 11.56%  |
| Seagate                     | 31        | 48     | 9.69%   |
| Toshiba                     | 25        | 32     | 7.81%   |
| SK hynix                    | 19        | 23     | 5.94%   |
| SanDisk                     | 19        | 34     | 5.94%   |
| Kingston                    | 17        | 22     | 5.31%   |
| Intel                       | 13        | 21     | 4.06%   |
| Micron Technology           | 12        | 19     | 3.75%   |
| Crucial                     | 10        | 14     | 3.13%   |
| Unknown                     | 8         | 10     | 2.5%    |
| A-DATA Technology           | 6         | 6      | 1.88%   |
| PNY                         | 5         | 6      | 1.56%   |
| KIOXIA                      | 5         | 13     | 1.56%   |
| HGST                        | 4         | 4      | 1.25%   |
| Hewlett-Packard             | 4         | 6      | 1.25%   |
| Silicon Motion              | 3         | 4      | 0.94%   |
| Phison                      | 3         | 7      | 0.94%   |
| Lenovo                      | 3         | 3      | 0.94%   |
| Hitachi                     | 3         | 3      | 0.94%   |
| Gigabyte Technology         | 3         | 4      | 0.94%   |
| Corsair                     | 3         | 6      | 0.94%   |
| Kingston Technology Company | 2         | 2      | 0.63%   |
| DELLBOSS                    | 2         | 2      | 0.63%   |
| XPG                         | 1         | 1      | 0.31%   |
| Western Digital             | 1         | 1      | 0.31%   |
| UMIS                        | 1         | 1      | 0.31%   |
| Transcend                   | 1         | 1      | 0.31%   |
| Team                        | 1         | 2      | 0.31%   |
| T-FORCE                     | 1         | 2      | 0.31%   |
| SSSTC                       | 1         | 1      | 0.31%   |
| SMI                         | 1         | 2      | 0.31%   |
| QUANXING                    | 1         | 1      | 0.31%   |
| Plextor                     | 1         | 1      | 0.31%   |
| Phison Electronics          | 1         | 1      | 0.31%   |
| OCZ                         | 1         | 2      | 0.31%   |
| Micron/Crucial Technology   | 1         | 1      | 0.31%   |
| Lite-On                     | 1         | 1      | 0.31%   |
| KingFast                    | 1         | 1      | 0.31%   |
| KINGBANK                    | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                      | 10        | 2.78%   |
| Samsung NVMe SSD Drive 512GB                       | 7         | 1.94%   |
| Toshiba NVMe SSD Drive 256GB                       | 6         | 1.67%   |
| SanDisk NVMe SSD Drive 256GB                       | 6         | 1.67%   |
| Samsung SSD 860 EVO 1TB                            | 6         | 1.67%   |
| Samsung NVMe SSD Drive 256GB                       | 6         | 1.67%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 1.39%   |
| Samsung NVMe SSD Drive 500GB                       | 4         | 1.11%   |
| Toshiba NVMe SSD Drive 512GB                       | 3         | 0.83%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.83%   |
| Micron NVMe SSD Drive 256GB                        | 3         | 0.83%   |
| Kingston SA400S37480G 480GB SSD                    | 3         | 0.83%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.83%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 0.83%   |
| WDC WD2003FZEX-00SRLA0 2TB                         | 2         | 0.56%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 2         | 0.56%   |
| WDC WD1002FAEX-00Z3A0 1TB                          | 2         | 0.56%   |
| Unknown NVMe SSD Drive 256GB                       | 2         | 0.56%   |
| Unknown MMC Card  16GB                             | 2         | 0.56%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 2         | 0.56%   |
| Toshiba KXG6AZNV256G 256GB                         | 2         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                    | 2         | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB                     | 2         | 0.56%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.56%   |
| Seagate ST1000DM003-9YN162 1TB                     | 2         | 0.56%   |
| Seagate Expansion 2TB                              | 2         | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 2         | 0.56%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 0.56%   |
| Samsung SSD 860 QVO 1TB                            | 2         | 0.56%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.56%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.56%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 0.56%   |
| Samsung Portable SSD T5 500GB                      | 2         | 0.56%   |
| Samsung NVMe SSD Drive 2TB                         | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 0.56%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                     | 2         | 0.56%   |
| Kingston SUV500120G 120GB SSD                      | 2         | 0.56%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 47     | 37.35%  |
| WDC                 | 28        | 50     | 33.73%  |
| Toshiba             | 10        | 14     | 12.05%  |
| HGST                | 4         | 4      | 4.82%   |
| Hitachi             | 3         | 3      | 3.61%   |
| Hewlett-Packard     | 2         | 2      | 2.41%   |
| DELLBOSS            | 2         | 2      | 2.41%   |
| Unknown             | 1         | 1      | 1.2%    |
| T-FORCE             | 1         | 2      | 1.2%    |
| Samsung Electronics | 1         | 2      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 46     | 29.17%  |
| Kingston            | 12        | 16     | 12.5%   |
| Crucial             | 10        | 14     | 10.42%  |
| SanDisk             | 7         | 13     | 7.29%   |
| WDC                 | 6         | 8      | 6.25%   |
| PNY                 | 5         | 6      | 5.21%   |
| Micron Technology   | 5         | 10     | 5.21%   |
| A-DATA Technology   | 5         | 5      | 5.21%   |
| Intel               | 3         | 5      | 3.13%   |
| Corsair             | 3         | 6      | 3.13%   |
| SK hynix            | 2         | 5      | 2.08%   |
| Transcend           | 1         | 1      | 1.04%   |
| Toshiba             | 1         | 1      | 1.04%   |
| Team                | 1         | 2      | 1.04%   |
| Seagate             | 1         | 1      | 1.04%   |
| Plextor             | 1         | 1      | 1.04%   |
| OCZ                 | 1         | 2      | 1.04%   |
| KINGBANK            | 1         | 1      | 1.04%   |
| Intenso             | 1         | 1      | 1.04%   |
| Hoodisk             | 1         | 1      | 1.04%   |
| China               | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 126       | 203    | 43.15%  |
| SSD     | 84        | 146    | 28.77%  |
| HDD     | 74        | 127    | 25.34%  |
| MMC     | 5         | 6      | 1.71%   |
| Unknown | 3         | 4      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 126       | 203    | 48.84%  |
| SATA | 110       | 251    | 42.64%  |
| SAS  | 17        | 26     | 6.59%   |
| MMC  | 5         | 6      | 1.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 125    | 45.24%  |
| 0.51-1.0   | 51        | 81     | 30.36%  |
| 1.01-2.0   | 24        | 34     | 14.29%  |
| 3.01-4.0   | 9         | 19     | 5.36%   |
| 4.01-10.0  | 6         | 12     | 3.57%   |
| 2.01-3.0   | 1         | 1      | 0.6%    |
| 10.01-20.0 | 1         | 1      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 34.23%  |
| 251-500        | 40        | 18.02%  |
| 501-1000       | 37        | 16.67%  |
| More than 3000 | 19        | 8.56%   |
| 1001-2000      | 18        | 8.11%   |
| 2001-3000      | 12        | 5.41%   |
| Unknown        | 9         | 4.05%   |
| 51-100         | 6         | 2.7%    |
| 21-50          | 3         | 1.35%   |
| 1-20           | 2         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 51        | 21.61%  |
| 1-20           | 45        | 19.07%  |
| 101-250        | 43        | 18.22%  |
| 51-100         | 36        | 15.25%  |
| 251-500        | 24        | 10.17%  |
| 501-1000       | 11        | 4.66%   |
| 1001-2000      | 9         | 3.81%   |
| Unknown        | 9         | 3.81%   |
| More than 3000 | 5         | 2.12%   |
| 2001-3000      | 3         | 1.27%   |

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
| Detected | 151       | 344    | 66.81%  |
| Works    | 69        | 135    | 30.53%  |
| Malfunc  | 6         | 7      | 2.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 119       | 41.61%  |
| Samsung Electronics            | 41        | 14.34%  |
| SK hynix                       | 17        | 5.94%   |
| AMD                            | 17        | 5.94%   |
| SanDisk                        | 15        | 5.24%   |
| Toshiba America Info Systems   | 14        | 4.9%    |
| Micron Technology              | 7         | 2.45%   |
| KIOXIA                         | 7         | 2.45%   |
| Phison Electronics             | 6         | 2.1%    |
| Kingston Technology Company    | 6         | 2.1%    |
| Silicon Motion                 | 5         | 1.75%   |
| Marvell Technology Group       | 5         | 1.75%   |
| Broadcom / LSI                 | 5         | 1.75%   |
| ASMedia Technology             | 4         | 1.4%    |
| Lenovo                         | 3         | 1.05%   |
| LSI Logic / Symbios Logic      | 2         | 0.7%    |
| Biwin Storage Technology       | 2         | 0.7%    |
| ADATA Technology               | 2         | 0.7%    |
| Western Digital                | 1         | 0.35%   |
| Union Memory (Shenzhen)        | 1         | 0.35%   |
| Solid State Storage Technology | 1         | 0.35%   |
| Shenzhen Quanxing Tech         | 1         | 0.35%   |
| PMC-Sierra                     | 1         | 0.35%   |
| Micron/Crucial Technology      | 1         | 0.35%   |
| Lite-On Technology             | 1         | 0.35%   |
| HighPoint Technologies         | 1         | 0.35%   |
| Hewlett-Packard                | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 9.15%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 4.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 3.47%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 3.15%   |
| Intel SATA Controller [RAID Mode]                                              | 9         | 2.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 2.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 8         | 2.52%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 2.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.21%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 7         | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.21%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 6         | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.26%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.26%   |
| Intel SSD 660P Series                                                          | 4         | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.26%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.95%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.95%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.95%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.95%   |
| KIOXIA NVMe SSD Controller XG8                                                 | 3         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.95%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 126       | 45.49%  |
| SATA | 118       | 42.6%   |
| RAID | 21        | 7.58%   |
| SAS  | 7         | 2.53%   |
| IDE  | 5         | 1.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 188       | 89.52%  |
| AMD    | 22        | 10.48%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 12        | 5.71%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 4.76%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.29%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 2.86%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.9%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.43%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 2         | 0.95%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 2         | 0.95%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 0.95%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.95%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.95%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.95%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.95%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.95%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.95%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| Intel Xeon w9-3495X                           | 1         | 0.48%   |
| Intel Xeon w9-3475X                           | 1         | 0.48%   |
| Intel Xeon W-2102 CPU @ 2.90GHz               | 1         | 0.48%   |
| Intel Xeon W-1290E CPU @ 3.50GHz              | 1         | 0.48%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.48%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 83        | 39.52%  |
| Intel Core i5      | 39        | 18.57%  |
| Intel Xeon         | 29        | 13.81%  |
| Other              | 16        | 7.62%   |
| Intel Core i3      | 10        | 4.76%   |
| AMD Ryzen 7        | 8         | 3.81%   |
| Intel Core i9      | 5         | 2.38%   |
| AMD Ryzen 9        | 4         | 1.9%    |
| AMD Ryzen 5        | 3         | 1.43%   |
| Intel Xeon Gold    | 2         | 0.95%   |
| Intel Pentium Gold | 2         | 0.95%   |
| Intel Pentium      | 2         | 0.95%   |
| AMD Ryzen 3        | 2         | 0.95%   |
| AMD EPYC           | 2         | 0.95%   |
| AMD Ryzen 7 PRO    | 1         | 0.48%   |
| AMD FX             | 1         | 0.48%   |
| AMD A10            | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 87        | 41.43%  |
| 2      | 41        | 19.52%  |
| 6      | 34        | 16.19%  |
| 8      | 19        | 9.05%   |
| 12     | 8         | 3.81%   |
| 16     | 4         | 1.9%    |
| 10     | 4         | 1.9%    |
| 20     | 3         | 1.43%   |
| 64     | 2         | 0.95%   |
| 36     | 2         | 0.95%   |
| 14     | 2         | 0.95%   |
| 96     | 1         | 0.48%   |
| 56     | 1         | 0.48%   |
| 32     | 1         | 0.48%   |
| 24     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 197       | 93.81%  |
| 2      | 13        | 6.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 178       | 84.36%  |
| 1      | 33        | 15.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 206       | 97.17%  |
| Unknown        | 6         | 2.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 29        | 13.68%  |
| Unknown    | 20        | 9.43%   |
| 0x906ea    | 14        | 6.6%    |
| 0x806ea    | 14        | 6.6%    |
| 0xa0652    | 12        | 5.66%   |
| 0x306c3    | 12        | 5.66%   |
| 0x306a9    | 11        | 5.19%   |
| 0x206a7    | 8         | 3.77%   |
| 0x906ed    | 7         | 3.3%    |
| 0x506e3    | 7         | 3.3%    |
| 0x406e3    | 7         | 3.3%    |
| 0x806c1    | 6         | 2.83%   |
| 0x906e9    | 5         | 2.36%   |
| 0x306f2    | 5         | 2.36%   |
| 0x806e9    | 4         | 1.89%   |
| 0xa0655    | 3         | 1.42%   |
| 0x806d1    | 3         | 1.42%   |
| 0x406f1    | 3         | 1.42%   |
| 0x306d4    | 3         | 1.42%   |
| 0x20655    | 3         | 1.42%   |
| 0x0a50000c | 3         | 1.42%   |
| 0x08600103 | 3         | 1.42%   |
| 0x08108102 | 3         | 1.42%   |
| 0x40651    | 2         | 0.94%   |
| 0x206d7    | 2         | 0.94%   |
| 0x08701021 | 2         | 0.94%   |
| 0x08701013 | 2         | 0.94%   |
| 0xa0671    | 1         | 0.47%   |
| 0xa0660    | 1         | 0.47%   |
| 0x906eb    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x90675    | 1         | 0.47%   |
| 0x90672    | 1         | 0.47%   |
| 0x806f8    | 1         | 0.47%   |
| 0x306e4    | 1         | 0.47%   |
| 0x20652    | 1         | 0.47%   |
| 0x10676    | 1         | 0.47%   |
| 0x0a001119 | 1         | 0.47%   |
| 0x08600106 | 1         | 0.47%   |
| 0x08600104 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 76        | 36.02%  |
| Haswell          | 21        | 9.95%   |
| CometLake        | 19        | 9%      |
| Skylake          | 15        | 7.11%   |
| IvyBridge        | 13        | 6.16%   |
| SandyBridge      | 11        | 5.21%   |
| Zen 2            | 10        | 4.74%   |
| Broadwell        | 7         | 3.32%   |
| TigerLake        | 6         | 2.84%   |
| Unknown          | 6         | 2.84%   |
| Icelake          | 5         | 2.37%   |
| Westmere         | 4         | 1.9%    |
| Alderlake Hybrid | 4         | 1.9%    |
| Zen+             | 3         | 1.42%   |
| Zen 3            | 3         | 1.42%   |
| Zen              | 3         | 1.42%   |
| Sapphire Rapids  | 2         | 0.95%   |
| Steamroller      | 1         | 0.47%   |
| Piledriver       | 1         | 0.47%   |
| Penryn           | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 138       | 53.49%  |
| Nvidia                     | 82        | 31.78%  |
| AMD                        | 29        | 11.24%  |
| Matrox Electronics Systems | 6         | 2.33%   |
| ASPEED Technology          | 3         | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 15        | 5.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 15        | 5.73%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 14        | 5.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 13        | 4.96%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 7         | 2.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 2.29%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 2.29%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 1.91%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 5         | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.53%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.15%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 3         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.15%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 3         | 1.15%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.76%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 0.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.76%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.76%   |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.76%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.76%   |
| Nvidia GM107GL [Quadro K620]                                                | 2         | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.76%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.76%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 2         | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.76%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 2         | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 97        | 45.54%  |
| 1 x Nvidia              | 45        | 21.13%  |
| Intel + Nvidia          | 29        | 13.62%  |
| 1 x AMD                 | 18        | 8.45%   |
| Intel + AMD             | 6         | 2.82%   |
| 1 x Matrox              | 5         | 2.35%   |
| AMD + Nvidia            | 4         | 1.88%   |
| 2 x Nvidia              | 2         | 0.94%   |
| Other                   | 1         | 0.47%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.47%   |
| 2 x Intel               | 1         | 0.47%   |
| 2 x AMD                 | 1         | 0.47%   |
| Nvidia + Matrox         | 1         | 0.47%   |
| Nvidia + ASPEED         | 1         | 0.47%   |
| 1 x ASPEED              | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 165       | 77.46%  |
| Proprietary | 37        | 17.37%  |
| Unknown     | 11        | 5.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 59.72%  |
| 1.01-2.0   | 20        | 9.26%   |
| 3.01-4.0   | 18        | 8.33%   |
| 7.01-8.0   | 11        | 5.09%   |
| 0.51-1.0   | 10        | 4.63%   |
| 0.01-0.5   | 9         | 4.17%   |
| 5.01-6.0   | 8         | 3.7%    |
| 2.01-3.0   | 4         | 1.85%   |
| 8.01-16.0  | 4         | 1.85%   |
| 4.01-5.0   | 2         | 0.93%   |
| 32.01-64.0 | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 11.2%   |
| Dell                    | 28        | 10.81%  |
| Samsung Electronics     | 27        | 10.42%  |
| BOE                     | 25        | 9.65%   |
| Lenovo                  | 24        | 9.27%   |
| LG Display              | 20        | 7.72%   |
| Chimei Innolux          | 20        | 7.72%   |
| Hewlett-Packard         | 15        | 5.79%   |
| Goldstar                | 14        | 5.41%   |
| Sharp                   | 5         | 1.93%   |
| Acer                    | 5         | 1.93%   |
| Philips                 | 4         | 1.54%   |
| InfoVision              | 4         | 1.54%   |
| Eizo                    | 4         | 1.54%   |
| BenQ                    | 4         | 1.54%   |
| PANDA                   | 3         | 1.16%   |
| Ancor Communications    | 3         | 1.16%   |
| ViewSonic               | 2         | 0.77%   |
| LGD                     | 2         | 0.77%   |
| Lenovo Group Limited    | 2         | 0.77%   |
| Iiyama                  | 2         | 0.77%   |
| Gigabyte Technology     | 2         | 0.77%   |
| AOC                     | 2         | 0.77%   |
| Unknown                 | 2         | 0.77%   |
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
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.49%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.78%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.78%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 5         | 1.78%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 1.07%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 1.07%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 3         | 1.07%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch       | 3         | 1.07%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 1.07%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 1.07%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 3         | 1.07%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 1.07%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 3         | 1.07%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 1.07%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 2         | 0.71%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.71%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.71%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.71%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.71%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch              | 2         | 0.71%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.71%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.71%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.71%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch        | 2         | 0.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 2         | 0.71%   |
| Unknown                                                           | 2         | 0.71%   |
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
| 1920x1080 (FHD)    | 120       | 51.72%  |
| 3840x2160 (4K)     | 19        | 8.19%   |
| 1366x768 (WXGA)    | 19        | 8.19%   |
| 2560x1440 (QHD)    | 16        | 6.9%    |
| 1600x900 (HD+)     | 11        | 4.74%   |
| 1920x1200 (WUXGA)  | 9         | 3.88%   |
| Unknown            | 6         | 2.59%   |
| 3440x1440          | 5         | 2.16%   |
| 3840x1080          | 4         | 1.72%   |
| 2560x1080          | 4         | 1.72%   |
| 1680x1050 (WSXGA+) | 3         | 1.29%   |
| 7680x2160          | 2         | 0.86%   |
| 3840x1200          | 2         | 0.86%   |
| 1440x900 (WXGA+)   | 2         | 0.86%   |
| 9600x2160          | 1         | 0.43%   |
| 6400x2160          | 1         | 0.43%   |
| 3840x2400          | 1         | 0.43%   |
| 3840x1600          | 1         | 0.43%   |
| 2880x1800          | 1         | 0.43%   |
| 2560x1600          | 1         | 0.43%   |
| 2048x1152          | 1         | 0.43%   |
| 1920x540           | 1         | 0.43%   |
| 1280x800 (WXGA)    | 1         | 0.43%   |
| 1280x720 (HD)      | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 18.6%   |
| 14      | 35        | 13.57%  |
| 24      | 31        | 12.02%  |
| 27      | 26        | 10.08%  |
| 13      | 23        | 8.91%   |
| 23      | 18        | 6.98%   |
| Unknown | 17        | 6.59%   |
| 31      | 9         | 3.49%   |
| 21      | 9         | 3.49%   |
| 34      | 7         | 2.71%   |
| 12      | 5         | 1.94%   |
| 20      | 4         | 1.55%   |
| 16      | 4         | 1.55%   |
| 32      | 3         | 1.16%   |
| 22      | 3         | 1.16%   |
| 17      | 3         | 1.16%   |
| 54      | 2         | 0.78%   |
| 47      | 2         | 0.78%   |
| 18      | 2         | 0.78%   |
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
| 301-350     | 103       | 41.2%   |
| 501-600     | 64        | 25.6%   |
| 401-500     | 18        | 7.2%    |
| Unknown     | 17        | 6.8%    |
| 601-700     | 14        | 5.6%    |
| 201-300     | 12        | 4.8%    |
| 701-800     | 10        | 4%      |
| 1001-1500   | 5         | 2%      |
| 801-900     | 3         | 1.2%    |
| 351-400     | 3         | 1.2%    |
| 1501-2000   | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 77.51%  |
| 16/10   | 22        | 10.53%  |
| Unknown | 15        | 7.18%   |
| 21/9    | 8         | 3.83%   |
| 32/9    | 1         | 0.48%   |
| 3/2     | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 20.08%  |
| 101-110        | 47        | 18.5%   |
| 201-250        | 46        | 18.11%  |
| 301-350        | 26        | 10.24%  |
| 351-500        | 18        | 7.09%   |
| Unknown        | 17        | 6.69%   |
| 251-300        | 12        | 4.72%   |
| 71-80          | 7         | 2.76%   |
| 151-200        | 7         | 2.76%   |
| 501-1000       | 6         | 2.36%   |
| 61-70          | 5         | 1.97%   |
| 111-120        | 5         | 1.97%   |
| More than 1000 | 3         | 1.18%   |
| 121-130        | 3         | 1.18%   |
| 141-150        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 89        | 35.89%  |
| 51-100        | 78        | 31.45%  |
| 101-120       | 37        | 14.92%  |
| Unknown       | 17        | 6.85%   |
| 161-240       | 15        | 6.05%   |
| More than 240 | 8         | 3.23%   |
| 1-50          | 4         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 135       | 60.81%  |
| 2     | 55        | 24.77%  |
| 0     | 19        | 8.56%   |
| 3     | 13        | 5.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 171       | 52.45%  |
| Realtek Semiconductor             | 63        | 19.33%  |
| Lenovo                            | 19        | 5.83%   |
| Qualcomm Atheros                  | 13        | 3.99%   |
| Broadcom                          | 9         | 2.76%   |
| Broadcom Limited                  | 5         | 1.53%   |
| MediaTek                          | 4         | 1.23%   |
| ASIX Electronics                  | 4         | 1.23%   |
| Aquantia                          | 4         | 1.23%   |
| Dell                              | 3         | 0.92%   |
| TP-Link                           | 2         | 0.61%   |
| Sierra Wireless                   | 2         | 0.61%   |
| Shenzhen Goodix Technology        | 2         | 0.61%   |
| Ralink Technology                 | 2         | 0.61%   |
| Ralink                            | 2         | 0.61%   |
| Marvell Technology Group          | 2         | 0.61%   |
| Huawei Technologies               | 2         | 0.61%   |
| Xiaomi                            | 1         | 0.31%   |
| Samsung Electronics               | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| Qualcomm                          | 1         | 0.31%   |
| NetGear                           | 1         | 0.31%   |
| Microchip Technology              | 1         | 0.31%   |
| Micro Star International          | 1         | 0.31%   |
| Mellanox Technologies             | 1         | 0.31%   |
| Luminary Micro                    | 1         | 0.31%   |
| ICS Advent                        | 1         | 0.31%   |
| IBM                               | 1         | 0.31%   |
| Google                            | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| DisplayLink                       | 1         | 0.31%   |
| D-Link                            | 1         | 0.31%   |
| Arduino SA                        | 1         | 0.31%   |
| American Megatrends               | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 9.13%   |
| Intel Wireless 8265 / 8275                                             | 16        | 3.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 16        | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 16        | 3.65%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 3.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 3.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 2.74%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.51%   |
| Intel Ethernet Connection (7) I219-LM                                  | 10        | 2.28%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 2.28%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.28%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 2.28%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 2.05%   |
| Intel Wireless 8260                                                    | 7         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.37%   |
| Intel I350 Gigabit Network Connection                                  | 6         | 1.37%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.14%   |
| Intel Ethernet Connection (17) I219-LM                                 | 5         | 1.14%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 0.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.91%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 0.91%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.91%   |
| Intel Ethernet Connection (11) I219-LM                                 | 4         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.68%   |
| Lenovo ThinkPad Lan                                                    | 3         | 0.68%   |
| Lenovo Lenovo USB-C to LAN                                             | 3         | 0.68%   |
| Intel Wireless 7265                                                    | 3         | 0.68%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.68%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                  | 3         | 0.68%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 125       | 72.25%  |
| Realtek Semiconductor           | 13        | 7.51%   |
| Qualcomm Atheros                | 12        | 6.94%   |
| Broadcom                        | 5         | 2.89%   |
| MediaTek                        | 4         | 2.31%   |
| TP-Link                         | 2         | 1.16%   |
| Sierra Wireless                 | 2         | 1.16%   |
| Ralink Technology               | 2         | 1.16%   |
| Ralink                          | 2         | 1.16%   |
| Qualcomm Atheros Communications | 1         | 0.58%   |
| NetGear                         | 1         | 0.58%   |
| Micro Star International        | 1         | 0.58%   |
| Dell                            | 1         | 0.58%   |
| D-Link                          | 1         | 0.58%   |
| Broadcom Limited                | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 16        | 9.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 9.25%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 15        | 8.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 14        | 8.09%   |
| Intel Wi-Fi 6 AX200                                                  | 11        | 6.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 10        | 5.78%   |
| Intel Wireless 8260                                                  | 7         | 4.05%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 3.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 6         | 3.47%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 2.31%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.73%   |
| Intel Wireless 7265                                                  | 3         | 1.73%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 3         | 1.73%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 3         | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.16%   |
| Intel Wireless 7260                                                  | 2         | 1.16%   |
| Intel Wireless 3165                                                  | 2         | 1.16%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.16%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1         | 0.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1         | 0.58%   |
| Sierra Wireless Sierra Wireless EM7511 Qualcomm Snapdragon X16 LTE-A | 1         | 0.58%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                      | 1         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1         | 0.58%   |
| Ralink RT5572 Wireless Adapter                                       | 1         | 0.58%   |
| Ralink RT5372 Wireless Adapter                                       | 1         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 133       | 55.65%  |
| Realtek Semiconductor    | 55        | 23.01%  |
| Lenovo                   | 19        | 7.95%   |
| Broadcom Limited         | 4         | 1.67%   |
| Broadcom                 | 4         | 1.67%   |
| ASIX Electronics         | 4         | 1.67%   |
| Aquantia                 | 4         | 1.67%   |
| Qualcomm Atheros         | 2         | 0.84%   |
| Marvell Technology Group | 2         | 0.84%   |
| Dell                     | 2         | 0.84%   |
| Xiaomi                   | 1         | 0.42%   |
| Samsung Electronics      | 1         | 0.42%   |
| Qualcomm                 | 1         | 0.42%   |
| Mellanox Technologies    | 1         | 0.42%   |
| ICS Advent               | 1         | 0.42%   |
| IBM                      | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| Google                   | 1         | 0.42%   |
| DisplayLink              | 1         | 0.42%   |
| American Megatrends      | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 40        | 15.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 4.65%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 3.88%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 3.88%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 3.88%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 3.49%   |
| Intel I350 Gigabit Network Connection                                          | 6         | 2.33%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 1.94%   |
| Intel Ethernet Connection (17) I219-LM                                         | 5         | 1.94%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.55%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.55%   |
| Intel Ethernet Connection (11) I219-LM                                         | 4         | 1.55%   |
| Lenovo ThinkPad Lan                                                            | 3         | 1.16%   |
| Lenovo Lenovo USB-C to LAN                                                     | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.16%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.16%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.16%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                                          | 3         | 1.16%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 1.16%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.16%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.78%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.78%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.78%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.78%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                   | 2         | 0.78%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.78%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.78%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.78%   |
| Dell iDRAC Virtual NIC                                                         | 2         | 0.78%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 191       | 52.47%  |
| WiFi     | 166       | 45.6%   |
| Modem    | 7         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 115       | 50.66%  |
| WiFi     | 112       | 49.34%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 61.14%  |
| 1     | 59        | 27.96%  |
| 3     | 11        | 5.21%   |
| 4     | 5         | 2.37%   |
| 8     | 2         | 0.95%   |
| 6     | 2         | 0.95%   |
| 132   | 1         | 0.47%   |
| 22    | 1         | 0.47%   |
| 5     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 87.79%  |
| Yes  | 26        | 12.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 72.06%  |
| Cambridge Silicon Radio         | 8         | 5.88%   |
| Broadcom                        | 7         | 5.15%   |
| Qualcomm Atheros Communications | 5         | 3.68%   |
| Realtek Semiconductor           | 4         | 2.94%   |
| IMC Networks                    | 4         | 2.94%   |
| Foxconn / Hon Hai               | 3         | 2.21%   |
| ASUSTek Computer                | 3         | 2.21%   |
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
| Intel AX201 Bluetooth                                                               | 35        | 25.74%  |
| Intel Bluetooth wireless interface                                                  | 23        | 16.91%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 15.44%  |
| Intel AX200 Bluetooth                                                               | 10        | 7.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.94%   |
| Intel Bluetooth Device                                                              | 4         | 2.94%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.21%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.47%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.47%   |
| ASUS BCM20702A0                                                                     | 2         | 1.47%   |
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
| Intel                     | 177       | 52.37%  |
| Nvidia                    | 64        | 18.93%  |
| AMD                       | 29        | 8.58%   |
| Lenovo                    | 17        | 5.03%   |
| GN Netcom                 | 7         | 2.07%   |
| Plantronics               | 6         | 1.78%   |
| JMTek                     | 5         | 1.48%   |
| Creative Technology       | 4         | 1.18%   |
| Texas Instruments         | 3         | 0.89%   |
| Generalplus Technology    | 3         | 0.89%   |
| Creative Labs             | 3         | 0.89%   |
| Realtek Semiconductor     | 2         | 0.59%   |
| Logitech                  | 2         | 0.59%   |
| C-Media Electronics       | 2         | 0.59%   |
| Tenx Technology           | 1         | 0.3%    |
| SteelSeries ApS           | 1         | 0.3%    |
| Sennheiser Communications | 1         | 0.3%    |
| RODE Microphones          | 1         | 0.3%    |
| Hewlett-Packard           | 1         | 0.3%    |
| Google                    | 1         | 0.3%    |
| Giga-Byte Technology      | 1         | 0.3%    |
| Focusrite-Novation        | 1         | 0.3%    |
| Dynex                     | 1         | 0.3%    |
| DSEA A/S                  | 1         | 0.3%    |
| Dell                      | 1         | 0.3%    |
| Corsair                   | 1         | 0.3%    |
| Blue Microphones          | 1         | 0.3%    |
| ASUSTek Computer          | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 25        | 6.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 5.49%   |
| Intel Comet Lake PCH cAVS                                                  | 18        | 4.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 4.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 4.4%    |
| AMD Ryzen HD Audio Controller                                              | 12        | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 2.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.47%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.47%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 1.92%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7         | 1.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.37%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 1.37%   |
| Plantronics BT600                                                          | 4         | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.1%    |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 1.1%    |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.1%    |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.82%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.82%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.82%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.82%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 31.37%  |
| SK hynix            | 26        | 25.49%  |
| Crucial             | 9         | 8.82%   |
| Micron Technology   | 8         | 7.84%   |
| Kingston            | 7         | 6.86%   |
| Corsair             | 5         | 4.9%    |
| Unknown             | 2         | 1.96%   |
| Transcend           | 2         | 1.96%   |
| GOODRAM             | 2         | 1.96%   |
| Unknown (0x0B5E)    | 1         | 0.98%   |
| Unknown (0x0205)    | 1         | 0.98%   |
| Smart               | 1         | 0.98%   |
| Patriot             | 1         | 0.98%   |
| Innodisk            | 1         | 0.98%   |
| Hewlett-Packard     | 1         | 0.98%   |
| GeIL                | 1         | 0.98%   |
| Elpida              | 1         | 0.98%   |
| Unknown             | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 3.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 1.85%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 1.85%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 1.85%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 1.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s           | 2         | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s          | 2         | 1.85%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s            | 2         | 1.85%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s            | 2         | 1.85%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 1.85%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 0.93%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 0.93%   |
| Transcend RAM TS4GLH64V2E-I 32GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 0.93%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 0.93%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                   | 1         | 0.93%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 0.93%   |
| SK hynix RAM HMCG88AGBSA095N 32GB SODIMM DDR5 5600MT/s          | 1         | 0.93%   |
| SK hynix RAM HMCG88AGBRA190N 32GB DIMM DDR5 5600MT/s            | 1         | 0.93%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s          | 1         | 0.93%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 0.93%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 0.93%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 0.93%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 0.93%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB DIMM DDR4 2400MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 0.93%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 0.93%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 0.93%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s           | 1         | 0.93%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                       | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 53        | 62.35%  |
| DDR3   | 21        | 24.71%  |
| DDR5   | 6         | 7.06%   |
| SDRAM  | 2         | 2.35%   |
| LPDDR4 | 1         | 1.18%   |
| LPDDR3 | 1         | 1.18%   |
| DRAM   | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 58.33%  |
| DIMM         | 34        | 40.48%  |
| Row Of Chips | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 30.43%  |
| 16384 | 27        | 29.35%  |
| 32768 | 18        | 19.57%  |
| 4096  | 17        | 18.48%  |
| 65536 | 1         | 1.09%   |
| 2048  | 1         | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 23        | 25%     |
| 1600  | 17        | 18.48%  |
| 2667  | 12        | 13.04%  |
| 2400  | 12        | 13.04%  |
| 1333  | 6         | 6.52%   |
| 2133  | 4         | 4.35%   |
| 5600  | 3         | 3.26%   |
| 4800  | 3         | 3.26%   |
| 3600  | 3         | 3.26%   |
| 8400  | 2         | 2.17%   |
| 3266  | 2         | 2.17%   |
| 2666  | 2         | 2.17%   |
| 3933  | 1         | 1.09%   |
| 2933  | 1         | 1.09%   |
| 1866  | 1         | 1.09%   |

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
| Chicony Electronics                    | 41        | 27.7%   |
| IMC Networks                           | 22        | 14.86%  |
| Bison Electronics                      | 14        | 9.46%   |
| Realtek Semiconductor                  | 11        | 7.43%   |
| Logitech                               | 10        | 6.76%   |
| Sunplus Innovation Technology          | 7         | 4.73%   |
| Microdia                               | 7         | 4.73%   |
| Luxvisions Innotech Limited            | 4         | 2.7%    |
| Lite-On Technology                     | 4         | 2.7%    |
| Hopewin Electronic Material            | 4         | 2.7%    |
| Suyin                                  | 3         | 2.03%   |
| Samsung Electronics                    | 3         | 2.03%   |
| Ruision                                | 2         | 1.35%   |
| Microsoft                              | 2         | 1.35%   |
| Generalplus Technology                 | 2         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.35%   |
| Acer                                   | 2         | 1.35%   |
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


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 22        | 14.57%  |
| IMC Networks Integrated Camera                   | 19        | 12.58%  |
| Bison Integrated Camera                          | 8         | 5.3%    |
| Realtek Integrated_Webcam_HD                     | 7         | 4.64%   |
| Bison SunplusIT Integrated Camera                | 5         | 3.31%   |
| Logitech HD Pro Webcam C920                      | 4         | 2.65%   |
| Hopewin Electronic Material FULL HD 1080P Webcam | 4         | 2.65%   |
| Chicony Integrated Camera (1280x720@30)          | 4         | 2.65%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 1.99%   |
| Samsung Galaxy series, misc. (MTP mode)          | 3         | 1.99%   |
| Lite-On Integrated Camera                        | 3         | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 1.99%   |
| Chicony ThinkPad T490 Webcam                     | 3         | 1.99%   |
| Chicony HP HD Camera                             | 3         | 1.99%   |
| Ruision UVC Camera                               | 2         | 1.32%   |
| Microdia Webcam                                  | 2         | 1.32%   |
| Microdia Integrated Webcam                       | 2         | 1.32%   |
| Luxvisions Innotech Limited HP 5MP Camera        | 2         | 1.32%   |
| Generalplus GENERAL WEBCAM                       | 2         | 1.32%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 1.32%   |
| Bison Integrated IR Camera                       | 2         | 1.32%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.66%   |
| Suyin RGBIR Camera                               | 1         | 0.66%   |
| Suyin Integrated_Webcam_HD                       | 1         | 0.66%   |
| Suyin HP Truevision HD                           | 1         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.66%   |
| Sunplus Integrated Webcam                        | 1         | 0.66%   |
| Sunplus Integrated Camera                        | 1         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.66%   |
| Remo Tech OBSBOT Tiny 4K                         | 1         | 0.66%   |
| Realtek USB2.0 VGA UVC WebCam                    | 1         | 0.66%   |
| Realtek USB Camera                               | 1         | 0.66%   |
| Realtek Thronmax Stream Go Pro Webcam            | 1         | 0.66%   |
| Realtek HP Webcam                                | 1         | 0.66%   |
| Quanta HP HD Camera                              | 1         | 0.66%   |
| Microsoft LifeCam HD-3000                        | 1         | 0.66%   |
| Microsoft LifeCam Cinema                         | 1         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD             | 1         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_E4HD           | 1         | 0.66%   |
| Microdia Integrated_Webcam_HD                    | 1         | 0.66%   |

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


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                         | 5         | 25%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 4         | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                      | 2         | 10%     |
| Lenovo Integrated Smart Card Reader                                         | 2         | 10%     |
| Broadcom 5880                                                               | 2         | 10%     |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                         | 1         | 5%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                  | 1         | 5%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                           | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor                              | 1         | 5%      |
| Broadcom 58200                                                              | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 97        | 45.33%  |
| 1     | 84        | 39.25%  |
| 2     | 21        | 9.81%   |
| 3     | 8         | 3.74%   |
| 5     | 2         | 0.93%   |
| 4     | 2         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 36.31%  |
| Graphics card            | 22        | 14.01%  |
| Net/wireless             | 14        | 8.92%   |
| Chipcard                 | 13        | 8.28%   |
| Unassigned class         | 12        | 7.64%   |
| Communication controller | 10        | 6.37%   |
| Card reader              | 7         | 4.46%   |
| Net/ethernet             | 6         | 3.82%   |
| Multimedia controller    | 5         | 3.18%   |
| Bluetooth                | 4         | 2.55%   |
| Storage                  | 2         | 1.27%   |
| Sound                    | 2         | 1.27%   |
| Network                  | 2         | 1.27%   |
| Storage/ide              | 1         | 0.64%   |

