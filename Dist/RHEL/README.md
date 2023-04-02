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

Total: 396

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [cc243873e2](https://linux-hardware.org/?probe=cc243873e2) | Mar 26, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [2e55d2163a](https://linux-hardware.org/?probe=2e55d2163a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [52e2d79bad](https://linux-hardware.org/?probe=52e2d79bad) | Mar 01, 2023 |
| Getac         | B360                        | Notebook    | [c4bd09adf1](https://linux-hardware.org/?probe=c4bd09adf1) | Mar 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac         | S410G4                      | Notebook    | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | Notebook    | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f1ac9526c5](https://linux-hardware.org/?probe=f1ac9526c5) | Dec 08, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ae85dba67e](https://linux-hardware.org/?probe=ae85dba67e) | Nov 28, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo        | Unknown                     | Convertible | [b4fb099c2f](https://linux-hardware.org/?probe=b4fb099c2f) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [7bb271252d](https://linux-hardware.org/?probe=7bb271252d) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Supermicro    | X10DRi                      | Server      | [0cf218f7bf](https://linux-hardware.org/?probe=0cf218f7bf) | Jun 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
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
| RHEL 8 | 182       | 69.73%  |
| RHEL 7 | 41        | 15.71%  |
| RHEL 9 | 38        | 14.56%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 260       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64                 | 14        | 4.62%   |
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 4.62%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 12        | 3.96%   |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 3.63%   |
| 4.18.0-305.el8.x86_64                        | 10        | 3.3%    |
| 5.14.0-162.6.1.el9_1.x86_64                  | 9         | 2.97%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 2.97%   |
| 4.18.0-348.12.2.el8_5.x86_64                 | 9         | 2.97%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 9         | 2.97%   |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 2.64%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 2.64%   |
| 4.18.0-425.10.1.el8_7.x86_64                 | 7         | 2.31%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 2.31%   |
| 5.14.0-70.17.1.el9_0.x86_64                  | 6         | 1.98%   |
| 4.18.0-425.3.1.el8.x86_64                    | 6         | 1.98%   |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 1.98%   |
| 4.18.0-193.el8.x86_64                        | 6         | 1.98%   |
| 4.18.0-193.19.1.el8_2.x86_64                 | 6         | 1.98%   |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 1.98%   |
| 4.18.0-147.3.1.el8_1.x86_64                  | 6         | 1.98%   |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 1.98%   |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 1.65%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 1.65%   |
| 5.14.0-70.5.1.el9_0.x86_64                   | 4         | 1.32%   |
| 5.14.0-70.26.1.el9_0.x86_64                  | 4         | 1.32%   |
| 5.14.0-162.12.1.el9_1.x86_64                 | 4         | 1.32%   |
| 4.18.0-372.9.1.el8.x86_64                    | 4         | 1.32%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.32%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.32%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.32%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.32%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.32%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 3         | 0.99%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 0.99%   |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 0.99%   |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 0.99%   |
| 5.14.0-70.22.1.el9_0.x86_64                  | 2         | 0.66%   |
| 5.14.0-70.13.1.el9_0.x86_64                  | 2         | 0.66%   |
| 5.14.0-162.18.1.el9_1.x86_64                 | 2         | 0.66%   |
| 4.18.0-372.32.1.el8_6.x86_64                 | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 176       | 67.43%  |
| 3.10.0   | 41        | 15.71%  |
| 5.14.0   | 38        | 14.56%  |
| 5.9.1    | 1         | 0.38%   |
| 5.13.13  | 1         | 0.38%   |
| 5.13.0   | 1         | 0.38%   |
| 5.10.6   | 1         | 0.38%   |
| 4.19.150 | 1         | 0.38%   |
| Unknown  | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 176       | 67.43%  |
| 3.10    | 41        | 15.71%  |
| 5.14    | 38        | 14.56%  |
| 5.13    | 2         | 0.77%   |
| 5.9     | 1         | 0.38%   |
| 5.10    | 1         | 0.38%   |
| 4.19    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 258       | 99.23%  |
| aarch64 | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 197       | 73.23%  |
| Unknown       | 48        | 17.84%  |
| GNOME Classic | 14        | 5.2%    |
| KDE5          | 5         | 1.86%   |
| KDE           | 2         | 0.74%   |
| MATE          | 1         | 0.37%   |
| KDE4          | 1         | 0.37%   |
| Cinnamon      | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 135       | 50.56%  |
| Wayland | 100       | 37.45%  |
| Unknown | 30        | 11.24%  |
| Tty     | 2         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 193       | 71.75%  |
| GDM     | 74        | 27.51%  |
| SDDM    | 1         | 0.37%   |
| LightDM | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 176       | 66.42%  |
| Unknown | 26        | 9.81%   |
| en_GB   | 17        | 6.42%   |
| en_IN   | 7         | 2.64%   |
| ru_RU   | 4         | 1.51%   |
| pt_BR   | 4         | 1.51%   |
| pl_PL   | 4         | 1.51%   |
| fr_FR   | 4         | 1.51%   |
| de_DE   | 4         | 1.51%   |
| nl_NL   | 2         | 0.75%   |
| ja_JP   | 2         | 0.75%   |
| es_ES   | 2         | 0.75%   |
| es_AR   | 2         | 0.75%   |
| en_IE   | 2         | 0.75%   |
| sl_SI   | 1         | 0.38%   |
| ko_KR   | 1         | 0.38%   |
| it_IT   | 1         | 0.38%   |
| es_MX   | 1         | 0.38%   |
| es_EC   | 1         | 0.38%   |
| en_NZ   | 1         | 0.38%   |
| en_DK   | 1         | 0.38%   |
| de_CH   | 1         | 0.38%   |
| cs_CZ   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 193       | 72.83%  |
| BIOS | 72        | 27.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 223       | 84.79%  |
| Ext4    | 28        | 10.65%  |
| Unknown | 12        | 4.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 158       | 58.74%  |
| GPT     | 91        | 33.83%  |
| MBR     | 20        | 7.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 230       | 87.12%  |
| Yes       | 34        | 12.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 239       | 90.53%  |
| Yes       | 25        | 9.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 92        | 35.38%  |
| Dell                    | 54        | 20.77%  |
| Hewlett-Packard         | 31        | 11.92%  |
| ASUSTek Computer        | 24        | 9.23%   |
| Gigabyte Technology     | 13        | 5%      |
| MSI                     | 8         | 3.08%   |
| ASRock                  | 6         | 2.31%   |
| Unknown                 | 5         | 1.92%   |
| Intel                   | 4         | 1.54%   |
| Supermicro              | 3         | 1.15%   |
| ZTSYSTEMS               | 2         | 0.77%   |
| Sony                    | 2         | 0.77%   |
| Getac                   | 2         | 0.77%   |
| Acer                    | 2         | 0.77%   |
| TUXEDO                  | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| Timi                    | 1         | 0.38%   |
| Samsung Electronics     | 1         | 0.38%   |
| Razer                   | 1         | 0.38%   |
| Raspberry Pi Foundation | 1         | 0.38%   |
| MiTAC                   | 1         | 0.38%   |
| Hardkernel              | 1         | 0.38%   |
| CX / Air Computers.     | 1         | 0.38%   |
| AZW                     | 1         | 0.38%   |
| AMI                     | 1         | 0.38%   |
| Alienware               | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 2.31%   |
| Unknown                                  | 6         | 2.31%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.54%   |
| Dell PowerEdge R230                      | 4         | 1.54%   |
| ASUS All Series                          | 4         | 1.54%   |
| Supermicro X10DRi                        | 2         | 0.77%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.77%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.77%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.77%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.77%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 2         | 0.77%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.77%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.77%   |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 0.77%   |
| HP Z620 Workstation                      | 2         | 0.77%   |
| HP EliteBook 8460p                       | 2         | 0.77%   |
| Dell Precision 7560                      | 2         | 0.77%   |
| Dell Precision 7510                      | 2         | 0.77%   |
| Dell PowerEdge R740                      | 2         | 0.77%   |
| Dell OptiPlex 9020                       | 2         | 0.77%   |
| Dell Latitude E6430                      | 2         | 0.77%   |
| Dell Latitude 5300                       | 2         | 0.77%   |
| ZTSYSTEMS Z802                           | 1         | 0.38%   |
| ZTSYSTEMS Z801                           | 1         | 0.38%   |
| TUXEDO N13xWU                            | 1         | 0.38%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.38%   |
| Timi TM1707                              | 1         | 0.38%   |
| Supermicro X7DW3                         | 1         | 0.38%   |
| Sony VPCEB4L1R                           | 1         | 0.38%   |
| Sony VPCEB23FM                           | 1         | 0.38%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.38%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 0.38%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.38%   |
| MSI MS-7C95                              | 1         | 0.38%   |
| MSI MS-7B89                              | 1         | 0.38%   |
| MSI MS-7B51                              | 1         | 0.38%   |
| MSI MS-7B33                              | 1         | 0.38%   |
| MSI MS-7A37                              | 1         | 0.38%   |
| MSI MS-7752                              | 1         | 0.38%   |
| MSI GP75 Leopard 9SD                     | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 78        | 30%     |
| Dell Precision     | 15        | 5.77%   |
| Dell PowerEdge     | 14        | 5.38%   |
| Dell Latitude      | 12        | 4.62%   |
| Unknown            | 6         | 2.31%   |
| HP ProLiant        | 5         | 1.92%   |
| HP EliteBook       | 5         | 1.92%   |
| ASUS PRIME         | 5         | 1.92%   |
| Dell Inspiron      | 4         | 1.54%   |
| ASUS All           | 4         | 1.54%   |
| Lenovo ThinkCentre | 3         | 1.15%   |
| HP ZBook           | 3         | 1.15%   |
| Dell OptiPlex      | 3         | 1.15%   |
| Supermicro X10DRi  | 2         | 0.77%   |
| Lenovo 7X56CTO1WW  | 2         | 0.77%   |
| HP Z620            | 2         | 0.77%   |
| HP Z230            | 2         | 0.77%   |
| HP ProBook         | 2         | 0.77%   |
| Dell XPS           | 2         | 0.77%   |
| ASUS VivoBook      | 2         | 0.77%   |
| ASUS TUF           | 2         | 0.77%   |
| ASUS ROG           | 2         | 0.77%   |
| ZTSYSTEMS Z802     | 1         | 0.38%   |
| ZTSYSTEMS Z801     | 1         | 0.38%   |
| TUXEDO N13xWU      | 1         | 0.38%   |
| Toshiba Satellite  | 1         | 0.38%   |
| Timi TM1707        | 1         | 0.38%   |
| Supermicro X7DW3   | 1         | 0.38%   |
| Sony VPCEB4L1R     | 1         | 0.38%   |
| Sony VPCEB23FM     | 1         | 0.38%   |
| Samsung 730QCJ     | 1         | 0.38%   |
| Razer Blade        | 1         | 0.38%   |
| RPi Raspberry      | 1         | 0.38%   |
| MSI MS-7C95        | 1         | 0.38%   |
| MSI MS-7B89        | 1         | 0.38%   |
| MSI MS-7B51        | 1         | 0.38%   |
| MSI MS-7B33        | 1         | 0.38%   |
| MSI MS-7A37        | 1         | 0.38%   |
| MSI MS-7752        | 1         | 0.38%   |
| MSI GP75           | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 46        | 17.69%  |
| 2020 | 41        | 15.77%  |
| 2018 | 33        | 12.69%  |
| 2016 | 22        | 8.46%   |
| 2021 | 19        | 7.31%   |
| 2017 | 18        | 6.92%   |
| 2015 | 18        | 6.92%   |
| 2012 | 17        | 6.54%   |
| 2013 | 12        | 4.62%   |
| 2022 | 10        | 3.85%   |
| 2011 | 8         | 3.08%   |
| 2014 | 7         | 2.69%   |
| 2010 | 6         | 2.31%   |
| 2009 | 2         | 0.77%   |
| 2023 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 144       | 55.38%  |
| Desktop        | 79        | 30.38%  |
| Server         | 25        | 9.62%   |
| Convertible    | 5         | 1.92%   |
| Mini pc        | 5         | 1.92%   |
| System on chip | 1         | 0.38%   |
| All in one     | 1         | 0.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 232       | 88.55%  |
| Enabled  | 30        | 11.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 260       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 66        | 24.72%  |
| 8.01-16.0       | 49        | 18.35%  |
| 4.01-8.0        | 44        | 16.48%  |
| 64.01-256.0     | 42        | 15.73%  |
| 16.01-24.0      | 37        | 13.86%  |
| 24.01-32.0      | 11        | 4.12%   |
| 3.01-4.0        | 10        | 3.75%   |
| More than 256.0 | 6         | 2.25%   |
| 2.01-3.0        | 1         | 0.37%   |
| Unknown         | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 96        | 33.45%  |
| 2.01-3.0        | 60        | 20.91%  |
| 3.01-4.0        | 43        | 14.98%  |
| 8.01-16.0       | 42        | 14.63%  |
| 1.01-2.0        | 26        | 9.06%   |
| 24.01-32.0      | 6         | 2.09%   |
| 16.01-24.0      | 6         | 2.09%   |
| 0.51-1.0        | 3         | 1.05%   |
| 32.01-64.0      | 2         | 0.7%    |
| More than 256.0 | 1         | 0.35%   |
| 64.01-256.0     | 1         | 0.35%   |
| Unknown         | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 53.73%  |
| 2      | 59        | 22.01%  |
| 3      | 30        | 11.19%  |
| 5      | 11        | 4.1%    |
| 4      | 11        | 4.1%    |
| 12     | 3         | 1.12%   |
| 6      | 3         | 1.12%   |
| 8      | 2         | 0.75%   |
| 0      | 2         | 0.75%   |
| 14     | 1         | 0.37%   |
| 11     | 1         | 0.37%   |
| 7      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 208       | 79.39%  |
| Yes       | 54        | 20.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 90.42%  |
| No        | 25        | 9.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 73.08%  |
| No        | 70        | 26.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 59.4%   |
| No        | 108       | 40.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 67        | 25.77%  |
| India        | 24        | 9.23%   |
| Germany      | 18        | 6.92%   |
| UK           | 16        | 6.15%   |
| Czechia      | 13        | 5%      |
| Canada       | 8         | 3.08%   |
| Norway       | 7         | 2.69%   |
| France       | 6         | 2.31%   |
| Brazil       | 6         | 2.31%   |
| Spain        | 5         | 1.92%   |
| Poland       | 5         | 1.92%   |
| Netherlands  | 5         | 1.92%   |
| Switzerland  | 4         | 1.54%   |
| Russia       | 4         | 1.54%   |
| Mexico       | 4         | 1.54%   |
| Italy        | 4         | 1.54%   |
| Finland      | 4         | 1.54%   |
| South Africa | 3         | 1.15%   |
| Lithuania    | 3         | 1.15%   |
| Japan        | 3         | 1.15%   |
| Chile        | 3         | 1.15%   |
| Argentina    | 3         | 1.15%   |
| Ukraine      | 2         | 0.77%   |
| Turkey       | 2         | 0.77%   |
| South Korea  | 2         | 0.77%   |
| Singapore    | 2         | 0.77%   |
| Romania      | 2         | 0.77%   |
| Indonesia    | 2         | 0.77%   |
| Egypt        | 2         | 0.77%   |
| China        | 2         | 0.77%   |
| Austria      | 2         | 0.77%   |
| Australia    | 2         | 0.77%   |
| Turkmenistan | 1         | 0.38%   |
| Sweden       | 1         | 0.38%   |
| Sri Lanka    | 1         | 0.38%   |
| Slovenia     | 1         | 0.38%   |
| Saudi Arabia | 1         | 0.38%   |
| Portugal     | 1         | 0.38%   |
| Pakistan     | 1         | 0.38%   |
| New Zealand  | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Prague           | 11        | 4.03%   |
| Quincy           | 8         | 2.93%   |
| Langgons         | 6         | 2.2%    |
| Turku            | 4         | 1.47%   |
| Tromsø          | 4         | 1.47%   |
| San Jose         | 3         | 1.1%    |
| Munich           | 3         | 1.1%    |
| Milan            | 3         | 1.1%    |
| Mexico City      | 3         | 1.1%    |
| Chicago          | 3         | 1.1%    |
| Chennai          | 3         | 1.1%    |
| Bengaluru        | 3         | 1.1%    |
| Toronto          | 2         | 0.73%   |
| Singapore        | 2         | 0.73%   |
| Santiago         | 2         | 0.73%   |
| Oslo             | 2         | 0.73%   |
| Montreal         | 2         | 0.73%   |
| Madrid           | 2         | 0.73%   |
| Kyiv             | 2         | 0.73%   |
| Houston          | 2         | 0.73%   |
| Didcot           | 2         | 0.73%   |
| Des Moines       | 2         | 0.73%   |
| Berlin           | 2         | 0.73%   |
| Bandung          | 2         | 0.73%   |
| Zaragoza         | 1         | 0.37%   |
| Yorktown Heights | 1         | 0.37%   |
| Yongin-si        | 1         | 0.37%   |
| Wroclaw          | 1         | 0.37%   |
| Wiesbaden        | 1         | 0.37%   |
| Webster          | 1         | 0.37%   |
| Wayne            | 1         | 0.37%   |
| Vienna           | 1         | 0.37%   |
| Vardenis         | 1         | 0.37%   |
| Vaglio           | 1         | 0.37%   |
| Udaipur          | 1         | 0.37%   |
| Tiruchi          | 1         | 0.37%   |
| Temuco           | 1         | 0.37%   |
| Temara           | 1         | 0.37%   |
| Tauranga         | 1         | 0.37%   |
| Taringa          | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 68        | 109    | 16.96%  |
| Seagate                   | 50        | 97     | 12.47%  |
| WDC                       | 49        | 80     | 12.22%  |
| Toshiba                   | 34        | 47     | 8.48%   |
| SanDisk                   | 22        | 32     | 5.49%   |
| SK hynix                  | 20        | 25     | 4.99%   |
| Kingston                  | 17        | 21     | 4.24%   |
| Intel                     | 16        | 23     | 3.99%   |
| Micron Technology         | 14        | 22     | 3.49%   |
| Unknown                   | 11        | 13     | 2.74%   |
| Crucial                   | 11        | 15     | 2.74%   |
| HGST                      | 7         | 10     | 1.75%   |
| A-DATA Technology         | 7         | 7      | 1.75%   |
| Phison                    | 6         | 10     | 1.5%    |
| Dell                      | 5         | 9      | 1.25%   |
| KIOXIA                    | 4         | 4      | 1%      |
| Hitachi                   | 4         | 4      | 1%      |
| Hewlett-Packard           | 4         | 13     | 1%      |
| Gigabyte Technology       | 4         | 5      | 1%      |
| China                     | 4         | 4      | 1%      |
| Silicon Motion            | 3         | 4      | 0.75%   |
| PNY                       | 3         | 4      | 0.75%   |
| Lenovo                    | 3         | 3      | 0.75%   |
| Corsair                   | 3         | 6      | 0.75%   |
| Western Digital           | 2         | 2      | 0.5%    |
| SSSTC                     | 2         | 2      | 0.5%    |
| Micron/Crucial Technology | 2         | 2      | 0.5%    |
| KingSpec                  | 2         | 2      | 0.5%    |
| ADATA Technology          | 2         | 2      | 0.5%    |
| XUM                       | 1         | 1      | 0.25%   |
| XPG                       | 1         | 1      | 0.25%   |
| UMIS                      | 1         | 1      | 0.25%   |
| Transcend                 | 1         | 1      | 0.25%   |
| Team                      | 1         | 2      | 0.25%   |
| T-FORCE                   | 1         | 2      | 0.25%   |
| SMI                       | 1         | 2      | 0.25%   |
| SCST_FIO                  | 1         | 9      | 0.25%   |
| SABRENT                   | 1         | 1      | 0.25%   |
| Plextor                   | 1         | 1      | 0.25%   |
| OCZ                       | 1         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                      | 10        | 2.22%   |
| Samsung NVMe SSD Drive 512GB                       | 8         | 1.77%   |
| Toshiba NVMe SSD Drive 256GB                       | 6         | 1.33%   |
| SanDisk NVMe SSD Drive 256GB                       | 6         | 1.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB             | 6         | 1.33%   |
| Samsung SSD 860 EVO 1TB                            | 5         | 1.11%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 1.11%   |
| HGST HTS721010A9E630 1TB                           | 5         | 1.11%   |
| Toshiba MG04ACA100NY 1TB                           | 4         | 0.89%   |
| Samsung NVMe SSD Drive 500GB                       | 4         | 0.89%   |
| Intel NVMe SSD Drive 512GB                         | 4         | 0.89%   |
| Dell MD34xx 26TB                                   | 4         | 0.89%   |
| WDC WD5003ABYZ-011FA0 500GB                        | 3         | 0.67%   |
| Toshiba NVMe SSD Drive 512GB                       | 3         | 0.67%   |
| Seagate ST1000LM049-2GH172 1TB                     | 3         | 0.67%   |
| Samsung SSD 860 EVO 500GB                          | 3         | 0.67%   |
| Samsung NVMe SSD Drive 2TB                         | 3         | 0.67%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.67%   |
| Micron NVMe SSD Drive 256GB                        | 3         | 0.67%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 0.67%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 2         | 0.44%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 2         | 0.44%   |
| WDC WD1002FAEX-00Z3A0 1TB                          | 2         | 0.44%   |
| Unknown SD/MMC/MS PRO 64GB                         | 2         | 0.44%   |
| Unknown NVMe SSD Drive 256GB                       | 2         | 0.44%   |
| Toshiba NVMe SSD Drive 1024GB                      | 2         | 0.44%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 0.44%   |
| Toshiba KXG6AZNV256G 256GB                         | 2         | 0.44%   |
| Toshiba DT01ACA200 2TB                             | 2         | 0.44%   |
| Toshiba AL14SEB18EQ 1.8TB                          | 2         | 0.44%   |
| SK hynix NVMe SSD Drive 1024GB                     | 2         | 0.44%   |
| Seagate ST91000640NS 1TB                           | 2         | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                    | 2         | 0.44%   |
| Seagate ST4000NM0033-9ZM170 4TB                    | 2         | 0.44%   |
| Seagate ST300MP0026 304GB                          | 2         | 0.44%   |
| Seagate ST2000NX0433 2TB                           | 2         | 0.44%   |
| Seagate ST2000NX0273 2TB                           | 2         | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                     | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 96     | 37.88%  |
| WDC                 | 40        | 66     | 30.3%   |
| Toshiba             | 19        | 29     | 14.39%  |
| HGST                | 7         | 10     | 5.3%    |
| Hitachi             | 4         | 4      | 3.03%   |
| Dell                | 4         | 8      | 3.03%   |
| Unknown             | 2         | 2      | 1.52%   |
| Hewlett-Packard     | 2         | 9      | 1.52%   |
| SCST_FIO            | 1         | 9      | 0.76%   |
| Samsung Electronics | 1         | 2      | 0.76%   |
| SABRENT             | 1         | 1      | 0.76%   |
| DELLBOSS            | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 38     | 27.68%  |
| Kingston            | 12        | 16     | 10.71%  |
| Crucial             | 11        | 15     | 9.82%   |
| WDC                 | 7         | 9      | 6.25%   |
| SanDisk             | 7         | 13     | 6.25%   |
| Micron Technology   | 7         | 13     | 6.25%   |
| A-DATA Technology   | 5         | 5      | 4.46%   |
| SK hynix            | 4         | 8      | 3.57%   |
| Intel               | 4         | 5      | 3.57%   |
| China               | 4         | 4      | 3.57%   |
| PNY                 | 3         | 4      | 2.68%   |
| Corsair             | 3         | 6      | 2.68%   |
| KingSpec            | 2         | 2      | 1.79%   |
| XUM                 | 1         | 1      | 0.89%   |
| Transcend           | 1         | 1      | 0.89%   |
| Toshiba             | 1         | 1      | 0.89%   |
| Team                | 1         | 2      | 0.89%   |
| Seagate             | 1         | 1      | 0.89%   |
| Plextor             | 1         | 1      | 0.89%   |
| OCZ                 | 1         | 2      | 0.89%   |
| KINGBANK            | 1         | 1      | 0.89%   |
| Intenso             | 1         | 1      | 0.89%   |
| Hoodisk             | 1         | 1      | 0.89%   |
| Gigabyte Technology | 1         | 1      | 0.89%   |
| Anobit              | 1         | 1      | 0.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 140       | 208    | 38.78%  |
| HDD     | 109       | 237    | 30.19%  |
| SSD     | 101       | 152    | 27.98%  |
| MMC     | 6         | 7      | 1.66%   |
| Unknown | 5         | 7      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 153       | 362    | 47.81%  |
| NVMe | 140       | 208    | 43.75%  |
| SAS  | 21        | 34     | 6.56%   |
| MMC  | 6         | 7      | 1.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 161    | 43.64%  |
| 0.51-1.0   | 71        | 108    | 32.27%  |
| 1.01-2.0   | 26        | 55     | 11.82%  |
| 3.01-4.0   | 13        | 33     | 5.91%   |
| 4.01-10.0  | 7         | 20     | 3.18%   |
| 20.01-50.0 | 4         | 8      | 1.82%   |
| 10.01-20.0 | 2         | 3      | 0.91%   |
| 2.01-3.0   | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 31.73%  |
| 251-500        | 48        | 17.71%  |
| 501-1000       | 46        | 16.97%  |
| More than 3000 | 22        | 8.12%   |
| 1001-2000      | 22        | 8.12%   |
| Unknown        | 17        | 6.27%   |
| 51-100         | 11        | 4.06%   |
| 2001-3000      | 10        | 3.69%   |
| 1-20           | 6         | 2.21%   |
| 21-50          | 3         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 25.61%  |
| 21-50          | 60        | 21.05%  |
| 101-250        | 45        | 15.79%  |
| 51-100         | 39        | 13.68%  |
| 251-500        | 22        | 7.72%   |
| Unknown        | 17        | 5.96%   |
| 501-1000       | 11        | 3.86%   |
| 1001-2000      | 10        | 3.51%   |
| More than 3000 | 5         | 1.75%   |
| 2001-3000      | 3         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYZ-011FA0 500GB              | 1         | 1      | 8.33%   |
| WDC WD4000FYYZ-01UL1B1 4TB               | 1         | 3      | 8.33%   |
| WDC WD10EALX-759BA1 1TB                  | 1         | 2      | 8.33%   |
| Transcend TS512GMTS800 512GB SSD         | 1         | 1      | 8.33%   |
| Seagate ST91000640NS 1TB                 | 1         | 2      | 8.33%   |
| Seagate ST6000NM0024-1HT17Z 6TB          | 1         | 2      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1      | 8.33%   |
| Micron Technology M510_2.5 7MM 256GB SSD | 1         | 1      | 8.33%   |
| Intel SSDSC2BA800G4R 800GB               | 1         | 1      | 8.33%   |
| Hitachi HDS722020ALA330 2TB              | 1         | 1      | 8.33%   |
| A-DATA Technology SU800NS38 256GB SSD    | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 6      | 33.33%  |
| WDC               | 3         | 6      | 25%     |
| Transcend         | 1         | 1      | 8.33%   |
| Micron Technology | 1         | 1      | 8.33%   |
| Intel             | 1         | 1      | 8.33%   |
| Hitachi           | 1         | 1      | 8.33%   |
| A-DATA Technology | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 50%     |
| WDC     | 3         | 6      | 37.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 13     | 63.64%  |
| SSD  | 4         | 4      | 36.36%  |

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
| Detected | 166       | 366    | 60.14%  |
| Works    | 99        | 228    | 35.87%  |
| Malfunc  | 11        | 17     | 3.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 165       | 45.45%  |
| Samsung Electronics            | 45        | 12.4%   |
| AMD                            | 21        | 5.79%   |
| SanDisk                        | 18        | 4.96%   |
| SK hynix                       | 16        | 4.41%   |
| Toshiba America Info Systems   | 14        | 3.86%   |
| Broadcom / LSI                 | 14        | 3.86%   |
| Phison Electronics             | 9         | 2.48%   |
| Micron Technology              | 7         | 1.93%   |
| LSI Logic / Symbios Logic      | 7         | 1.93%   |
| KIOXIA                         | 6         | 1.65%   |
| ADATA Technology               | 6         | 1.65%   |
| Silicon Motion                 | 5         | 1.38%   |
| Kingston Technology Company    | 5         | 1.38%   |
| Marvell Technology Group       | 4         | 1.1%    |
| Hewlett-Packard                | 4         | 1.1%    |
| ASMedia Technology             | 4         | 1.1%    |
| Lenovo                         | 3         | 0.83%   |
| Western Digital                | 2         | 0.55%   |
| Micron/Crucial Technology      | 2         | 0.55%   |
| Biwin Storage Technology       | 2         | 0.55%   |
| Union Memory (Shenzhen)        | 1         | 0.28%   |
| Solid State Storage Technology | 1         | 0.28%   |
| Lite-On Technology             | 1         | 0.28%   |
| HighPoint Technologies         | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 32        | 7.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 4.14%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 15        | 3.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 3.41%   |
| SK hynix Non-Volatile memory controller                                        | 13        | 3.16%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 13        | 3.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 2.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 2.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 1.95%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 8         | 1.95%   |
| Micron NVMe Storage Controller                                                 | 7         | 1.7%    |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.46%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 6         | 1.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.22%   |
| Intel SSD 660P Series                                                          | 5         | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.22%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 0.97%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.97%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                           | 4         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 0.97%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.97%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 4         | 0.97%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4         | 0.97%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 4         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 0.97%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 4         | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 0.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 156       | 43.33%  |
| NVMe | 140       | 38.89%  |
| RAID | 46        | 12.78%  |
| SAS  | 10        | 2.78%   |
| IDE  | 8         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 233       | 89.62%  |
| AMD    | 26        | 10%     |
| ARM    | 1         | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz     | 11        | 4.23%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 9         | 3.46%   |
| Intel Core i7-10610U CPU @ 1.80GHz     | 9         | 3.46%   |
| Intel Core i7-8650U CPU @ 1.90GHz      | 6         | 2.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz     | 5         | 1.92%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz    | 4         | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 4         | 1.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 4         | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 4         | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 4         | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4         | 1.54%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz    | 3         | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 3         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 3         | 1.15%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 3         | 1.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 3         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 3         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 3         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 3         | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 3         | 1.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 3         | 1.15%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz   | 2         | 0.77%   |
| Intel Xeon CPU E5620 @ 2.40GHz         | 2         | 0.77%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz    | 2         | 0.77%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 2         | 0.77%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 2         | 0.77%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 2         | 0.77%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 2         | 0.77%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 2         | 0.77%   |
| Intel Core i7-9850H CPU @ 2.60GHz      | 2         | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2         | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2         | 0.77%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 2         | 0.77%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 2         | 0.77%   |
| Intel Core i5-8365U CPU @ 1.60GHz      | 2         | 0.77%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 2         | 0.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 0.77%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 96        | 36.92%  |
| Intel Core i5        | 48        | 18.46%  |
| Intel Xeon           | 43        | 16.54%  |
| Other                | 18        | 6.92%   |
| Intel Core i3        | 12        | 4.62%   |
| AMD Ryzen 7          | 7         | 2.69%   |
| AMD Ryzen 5          | 6         | 2.31%   |
| AMD Ryzen 9          | 5         | 1.92%   |
| Intel Xeon Silver    | 3         | 1.15%   |
| Intel Core i9        | 3         | 1.15%   |
| Intel Xeon Gold      | 2         | 0.77%   |
| Intel Pentium Gold   | 2         | 0.77%   |
| Intel Pentium        | 2         | 0.77%   |
| Intel Celeron        | 2         | 0.77%   |
| AMD Ryzen 3          | 2         | 0.77%   |
| AMD EPYC             | 2         | 0.77%   |
| Intel Xeon Platinum  | 1         | 0.38%   |
| Intel Pentium Silver | 1         | 0.38%   |
| Intel Core 2 Duo     | 1         | 0.38%   |
| AMD Ryzen 7 PRO      | 1         | 0.38%   |
| AMD FX               | 1         | 0.38%   |
| AMD A4               | 1         | 0.38%   |
| AMD A10              | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 109       | 41.92%  |
| 2      | 51        | 19.62%  |
| 6      | 39        | 15%     |
| 8      | 26        | 10%     |
| 12     | 13        | 5%      |
| 16     | 7         | 2.69%   |
| 20     | 4         | 1.54%   |
| 48     | 2         | 0.77%   |
| 36     | 2         | 0.77%   |
| 24     | 2         | 0.77%   |
| 96     | 1         | 0.38%   |
| 64     | 1         | 0.38%   |
| 32     | 1         | 0.38%   |
| 14     | 1         | 0.38%   |
| 10     | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 232       | 89.23%  |
| 2      | 28        | 10.77%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 220       | 84.29%  |
| 1      | 41        | 15.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 252       | 96.18%  |
| Unknown        | 10        | 3.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 35        | 13.36%  |
| 0x906ea    | 16        | 6.11%   |
| 0x806ea    | 15        | 5.73%   |
| 0x306c3    | 14        | 5.34%   |
| 0x306a9    | 14        | 5.34%   |
| Unknown    | 13        | 4.96%   |
| 0xa0652    | 12        | 4.58%   |
| 0x506e3    | 10        | 3.82%   |
| 0x306f2    | 10        | 3.82%   |
| 0x206a7    | 9         | 3.44%   |
| 0x906ed    | 8         | 3.05%   |
| 0x906e9    | 8         | 3.05%   |
| 0x406e3    | 8         | 3.05%   |
| 0x806d1    | 7         | 2.67%   |
| 0x806e9    | 5         | 1.91%   |
| 0x806c1    | 5         | 1.91%   |
| 0x406f1    | 5         | 1.91%   |
| 0x306e4    | 4         | 1.53%   |
| 0x306d4    | 4         | 1.53%   |
| 0x206d7    | 4         | 1.53%   |
| 0xa0671    | 3         | 1.15%   |
| 0x40651    | 3         | 1.15%   |
| 0x206c2    | 3         | 1.15%   |
| 0x20655    | 3         | 1.15%   |
| 0x0a50000c | 3         | 1.15%   |
| 0x08701021 | 3         | 1.15%   |
| 0x08600103 | 3         | 1.15%   |
| 0x08108102 | 3         | 1.15%   |
| 0x906c0    | 2         | 0.76%   |
| 0x50654    | 2         | 0.76%   |
| 0x08701013 | 2         | 0.76%   |
| 0xb0671    | 1         | 0.38%   |
| 0xa0660    | 1         | 0.38%   |
| 0xa0655    | 1         | 0.38%   |
| 0x906eb    | 1         | 0.38%   |
| 0x906a4    | 1         | 0.38%   |
| 0x906a3    | 1         | 0.38%   |
| 0x90672    | 1         | 0.38%   |
| 0x706e5    | 1         | 0.38%   |
| 0x706a8    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 34.1%   |
| Haswell          | 29        | 11.11%  |
| Skylake          | 27        | 10.34%  |
| IvyBridge        | 19        | 7.28%   |
| CometLake        | 14        | 5.36%   |
| SandyBridge      | 13        | 4.98%   |
| Zen 2            | 11        | 4.21%   |
| Icelake          | 11        | 4.21%   |
| Broadwell        | 9         | 3.45%   |
| Westmere         | 7         | 2.68%   |
| TigerLake        | 5         | 1.92%   |
| Unknown          | 5         | 1.92%   |
| Zen+             | 4         | 1.53%   |
| Alderlake Hybrid | 4         | 1.53%   |
| Zen 3            | 3         | 1.15%   |
| Zen              | 3         | 1.15%   |
| Tremont          | 2         | 0.77%   |
| Penryn           | 2         | 0.77%   |
| Steamroller      | 1         | 0.38%   |
| Piledriver       | 1         | 0.38%   |
| Goldmont plus    | 1         | 0.38%   |
| Excavator        | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 160       | 50.96%  |
| Nvidia                     | 90        | 28.66%  |
| AMD                        | 35        | 11.15%  |
| Matrox Electronics Systems | 20        | 6.37%   |
| ASPEED Technology          | 9         | 2.87%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 18        | 5.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 17        | 5.35%   |
| Intel UHD Graphics 620                                                      | 15        | 4.72%   |
| Matrox Electronics Systems G200eR2                                          | 12        | 3.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 3.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 2.83%   |
| ASPEED Technology ASPEED Graphics Family                                    | 9         | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 2.52%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 2.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 1.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 5         | 1.57%   |
| Intel HD Graphics 630                                                       | 5         | 1.57%   |
| Intel HD Graphics 530                                                       | 5         | 1.57%   |
| AMD Renoir                                                                  | 5         | 1.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 1.26%   |
| Intel HD Graphics 620                                                       | 4         | 1.26%   |
| Intel HD Graphics 5500                                                      | 4         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.94%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 0.94%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 0.94%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 0.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 0.94%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.63%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.63%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.63%   |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.63%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.63%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 112       | 42.59%  |
| 1 x Nvidia              | 48        | 18.25%  |
| Intel + Nvidia          | 35        | 13.31%  |
| 1 x AMD                 | 20        | 7.6%    |
| 1 x Matrox              | 19        | 7.22%   |
| Intel + AMD             | 9         | 3.42%   |
| 1 x ASPEED              | 6         | 2.28%   |
| Other                   | 3         | 1.14%   |
| AMD + Nvidia            | 3         | 1.14%   |
| 2 x Nvidia              | 2         | 0.76%   |
| 2 x AMD                 | 2         | 0.76%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.38%   |
| Nvidia + Matrox         | 1         | 0.38%   |
| Nvidia + ASPEED         | 1         | 0.38%   |
| AMD + ASPEED            | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 202       | 76.52%  |
| Proprietary | 38        | 14.39%  |
| Unknown     | 24        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 62.17%  |
| 1.01-2.0   | 26        | 9.74%   |
| 3.01-4.0   | 18        | 6.74%   |
| 7.01-8.0   | 13        | 4.87%   |
| 0.51-1.0   | 13        | 4.87%   |
| 5.01-6.0   | 10        | 3.75%   |
| 0.01-0.5   | 10        | 3.75%   |
| 2.01-3.0   | 5         | 1.87%   |
| 8.01-16.0  | 3         | 1.12%   |
| 4.01-5.0   | 2         | 0.75%   |
| 16.01-24.0 | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 34        | 11.49%  |
| AU Optronics            | 33        | 11.15%  |
| Samsung Electronics     | 31        | 10.47%  |
| BOE                     | 28        | 9.46%   |
| Lenovo                  | 24        | 8.11%   |
| Chimei Innolux          | 24        | 8.11%   |
| LG Display              | 23        | 7.77%   |
| Goldstar                | 17        | 5.74%   |
| Hewlett-Packard         | 14        | 4.73%   |
| Sharp                   | 8         | 2.7%    |
| Acer                    | 6         | 2.03%   |
| InfoVision              | 5         | 1.69%   |
| BenQ                    | 5         | 1.69%   |
| Philips                 | 4         | 1.35%   |
| Eizo                    | 4         | 1.35%   |
| Ancor Communications    | 3         | 1.01%   |
| ViewSonic               | 2         | 0.68%   |
| PANDA                   | 2         | 0.68%   |
| LGD                     | 2         | 0.68%   |
| Lenovo Group Limited    | 2         | 0.68%   |
| Iiyama                  | 2         | 0.68%   |
| Gigabyte Technology     | 2         | 0.68%   |
| BOE Technology Group    | 2         | 0.68%   |
| AOC                     | 2         | 0.68%   |
| Unknown                 | 1         | 0.34%   |
| Sun                     | 1         | 0.34%   |
| STD                     | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| Sceptre Tech            | 1         | 0.34%   |
| Planar                  | 1         | 0.34%   |
| OUT                     | 1         | 0.34%   |
| Microstep               | 1         | 0.34%   |
| LG Electronics          | 1         | 0.34%   |
| ITE                     | 1         | 0.34%   |
| Insignia                | 1         | 0.34%   |
| Haier                   | 1         | 0.34%   |
| EVE                     | 1         | 0.34%   |
| CSO                     | 1         | 0.34%   |
| Chi Mei Optoelectronics | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.19%   |
| Dell LCD Monitor DEL0001 1280x1024                                | 6         | 1.88%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.57%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 5         | 1.57%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 4         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 4         | 1.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3         | 0.94%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 0.94%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 0.94%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 3         | 0.94%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 0.94%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 0.94%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 0.94%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 3         | 0.94%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 0.94%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 2         | 0.63%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch           | 2         | 0.63%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.63%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.63%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.63%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch              | 2         | 0.63%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.63%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch        | 2         | 0.63%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.63%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.63%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch        | 2         | 0.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch    | 2         | 0.63%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch     | 1         | 0.31%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch     | 1         | 0.31%   |
| Unknown LCD Monitor SAMSUNG                                       | 1         | 0.31%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                 | 1         | 0.31%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                     | 1         | 0.31%   |
| Sony TV SNYD703 1360x768                                          | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 52.81%  |
| 1366x768 (WXGA)    | 23        | 8.61%   |
| 3840x2160 (4K)     | 21        | 7.87%   |
| 2560x1440 (QHD)    | 17        | 6.37%   |
| 1600x900 (HD+)     | 12        | 4.49%   |
| 1920x1200 (WUXGA)  | 7         | 2.62%   |
| 1280x1024 (SXGA)   | 7         | 2.62%   |
| 2560x1080          | 6         | 2.25%   |
| Unknown            | 6         | 2.25%   |
| 3440x1440          | 5         | 1.87%   |
| 3840x1080          | 4         | 1.5%    |
| 1680x1050 (WSXGA+) | 4         | 1.5%    |
| 1440x900 (WXGA+)   | 2         | 0.75%   |
| 9600x2160          | 1         | 0.37%   |
| 7680x2160          | 1         | 0.37%   |
| 7280x2160          | 1         | 0.37%   |
| 6400x2160          | 1         | 0.37%   |
| 3840x1600          | 1         | 0.37%   |
| 3840x1200          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2160x1350          | 1         | 0.37%   |
| 2048x1152          | 1         | 0.37%   |
| 1280x800 (WXGA)    | 1         | 0.37%   |
| 1280x768           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 17.57%  |
| 14      | 40        | 13.51%  |
| 13      | 32        | 10.81%  |
| 27      | 29        | 9.8%    |
| 24      | 27        | 9.12%   |
| Unknown | 22        | 7.43%   |
| 23      | 21        | 7.09%   |
| 21      | 15        | 5.07%   |
| 34      | 8         | 2.7%    |
| 31      | 7         | 2.36%   |
| 17      | 6         | 2.03%   |
| 20      | 5         | 1.69%   |
| 12      | 5         | 1.69%   |
| 54      | 3         | 1.01%   |
| 32      | 3         | 1.01%   |
| 72      | 2         | 0.68%   |
| 47      | 2         | 0.68%   |
| 22      | 2         | 0.68%   |
| 19      | 2         | 0.68%   |
| 18      | 2         | 0.68%   |
| 16      | 2         | 0.68%   |
| 64      | 1         | 0.34%   |
| 52      | 1         | 0.34%   |
| 49      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 39      | 1         | 0.34%   |
| 37      | 1         | 0.34%   |
| 28      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 11      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 40.28%  |
| 501-600     | 66        | 22.92%  |
| 401-500     | 24        | 8.33%   |
| Unknown     | 22        | 7.64%   |
| 201-300     | 16        | 5.56%   |
| 601-700     | 13        | 4.51%   |
| 701-800     | 11        | 3.82%   |
| 1001-1500   | 8         | 2.78%   |
| 351-400     | 7         | 2.43%   |
| 801-900     | 3         | 1.04%   |
| 1501-2000   | 2         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 189       | 78.1%   |
| 16/10   | 19        | 7.85%   |
| Unknown | 14        | 5.79%   |
| 21/9    | 10        | 4.13%   |
| 5/4     | 7         | 2.89%   |
| 4/3     | 1         | 0.41%   |
| 32/9    | 1         | 0.41%   |
| 3/2     | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 62        | 21.23%  |
| 101-110        | 52        | 17.81%  |
| 201-250        | 51        | 17.47%  |
| 301-350        | 29        | 9.93%   |
| Unknown        | 22        | 7.53%   |
| 351-500        | 17        | 5.82%   |
| 251-300        | 12        | 4.11%   |
| 71-80          | 10        | 3.42%   |
| 151-200        | 9         | 3.08%   |
| More than 1000 | 7         | 2.4%    |
| 121-130        | 6         | 2.05%   |
| 501-1000       | 6         | 2.05%   |
| 61-70          | 5         | 1.71%   |
| 51-60          | 1         | 0.34%   |
| 141-150        | 1         | 0.34%   |
| 131-140        | 1         | 0.34%   |
| 111-120        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 36.62%  |
| 51-100        | 81        | 28.52%  |
| 101-120       | 46        | 16.2%   |
| Unknown       | 22        | 7.75%   |
| 161-240       | 18        | 6.34%   |
| 1-50          | 7         | 2.46%   |
| More than 240 | 6         | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 170       | 62.5%   |
| 2     | 57        | 20.96%  |
| 0     | 30        | 11.03%  |
| 3     | 14        | 5.15%   |
| 4     | 1         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 199       | 51.55%  |
| Realtek Semiconductor             | 83        | 21.5%   |
| Lenovo                            | 19        | 4.92%   |
| Broadcom                          | 19        | 4.92%   |
| Qualcomm Atheros                  | 16        | 4.15%   |
| Dell                              | 5         | 1.3%    |
| Broadcom Limited                  | 5         | 1.3%    |
| MediaTek                          | 4         | 1.04%   |
| ASIX Electronics                  | 4         | 1.04%   |
| Sierra Wireless                   | 3         | 0.78%   |
| Ralink Technology                 | 2         | 0.52%   |
| Ralink                            | 2         | 0.52%   |
| Marvell Technology Group          | 2         | 0.52%   |
| Huawei Technologies               | 2         | 0.52%   |
| Ericsson Business Mobile Networks | 2         | 0.52%   |
| Xiaomi                            | 1         | 0.26%   |
| Tehuti Networks                   | 1         | 0.26%   |
| Samsung Electronics               | 1         | 0.26%   |
| Qualcomm Atheros Communications   | 1         | 0.26%   |
| QLogic                            | 1         | 0.26%   |
| Prolific Technology               | 1         | 0.26%   |
| OPPO Electronics                  | 1         | 0.26%   |
| Microchip Technology              | 1         | 0.26%   |
| Micro Star International          | 1         | 0.26%   |
| Mellanox Technologies             | 1         | 0.26%   |
| Luminary Micro                    | 1         | 0.26%   |
| ICS Advent                        | 1         | 0.26%   |
| IBM                               | 1         | 0.26%   |
| Emulex                            | 1         | 0.26%   |
| DisplayLink                       | 1         | 0.26%   |
| D-Link                            | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |
| Arduino SA                        | 1         | 0.26%   |
| Aquantia                          | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 9.83%   |
| Intel Wireless 8265 / 8275                                        | 18        | 3.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 3.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 2.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 2.31%   |
| Intel Wireless 8260                                               | 11        | 2.12%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 2.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 2.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 1.73%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 9         | 1.73%   |
| Intel I350 Gigabit Network Connection                             | 9         | 1.73%   |
| Intel Ethernet Connection (10) I219-LM                            | 8         | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 7         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 1.16%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 6         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.96%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.96%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.96%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 5         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.77%   |
| Intel Wireless-AC 9260                                            | 4         | 0.77%   |
| Intel Wireless 7265                                               | 4         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 144       | 72.73%  |
| Realtek Semiconductor           | 18        | 9.09%   |
| Qualcomm Atheros                | 13        | 6.57%   |
| Broadcom                        | 5         | 2.53%   |
| MediaTek                        | 4         | 2.02%   |
| Sierra Wireless                 | 3         | 1.52%   |
| Ralink Technology               | 2         | 1.01%   |
| Ralink                          | 2         | 1.01%   |
| Dell                            | 2         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| Micro Star International        | 1         | 0.51%   |
| D-Link                          | 1         | 0.51%   |
| Broadcom Limited                | 1         | 0.51%   |
| ASUSTek Computer                | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                   | 18        | 9.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                            | 17        | 8.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                     | 16        | 8.08%   |
| Intel Wi-Fi 6 AX200                                          | 12        | 6.06%   |
| Intel Comet Lake PCH CNVi WiFi                               | 12        | 6.06%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 12        | 6.06%   |
| Intel Wireless 8260                                          | 11        | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                 | 6         | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                       | 5         | 2.53%   |
| Intel Wi-Fi 6 AX201                                          | 5         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 4         | 2.02%   |
| Intel Wireless-AC 9260                                       | 4         | 2.02%   |
| Intel Wireless 7265                                          | 4         | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 4         | 2.02%   |
| Intel Centrino Ultimate-N 6300                               | 4         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 3         | 1.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter           | 3         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter              | 2         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 2         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 2         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 2         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 2         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter   | 2         | 1.01%   |
| Intel Wireless 7260                                          | 2         | 1.01%   |
| Intel Wireless 3165                                          | 2         | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                             | 2         | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                             | 2         | 1.01%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                         | 2         | 1.01%   |
| Sierra Wireless EM7565 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.51%   |
| Sierra Wireless EM7455                                       | 1         | 0.51%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem              | 1         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter     | 1         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                   | 1         | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 1         | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 1         | 0.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter              | 1         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 1         | 0.51%   |
| Realtek 802.11n WLAN Adapter                                 | 1         | 0.51%   |
| Ralink RT5572 Wireless Adapter                               | 1         | 0.51%   |
| Ralink RT5372 Wireless Adapter                               | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 149       | 52.28%  |
| Realtek Semiconductor    | 74        | 25.96%  |
| Lenovo                   | 19        | 6.67%   |
| Broadcom                 | 14        | 4.91%   |
| Qualcomm Atheros         | 4         | 1.4%    |
| Broadcom Limited         | 4         | 1.4%    |
| ASIX Electronics         | 4         | 1.4%    |
| Dell                     | 3         | 1.05%   |
| Marvell Technology Group | 2         | 0.7%    |
| Xiaomi                   | 1         | 0.35%   |
| Tehuti Networks          | 1         | 0.35%   |
| Samsung Electronics      | 1         | 0.35%   |
| QLogic                   | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| Mellanox Technologies    | 1         | 0.35%   |
| ICS Advent               | 1         | 0.35%   |
| IBM                      | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |
| Emulex                   | 1         | 0.35%   |
| DisplayLink              | 1         | 0.35%   |
| Aquantia                 | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 51        | 16.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 5.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 13        | 4.14%   |
| Intel Ethernet Connection (6) I219-LM                                          | 11        | 3.5%    |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 3.5%    |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 3.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 2.87%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 2.87%   |
| Intel I350 Gigabit Network Connection                                          | 9         | 2.87%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 2.55%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 2.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.23%   |
| Intel 82574L Gigabit Network Connection                                        | 6         | 1.91%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.91%   |
| Intel Ethernet Controller I225-V                                               | 5         | 1.59%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.59%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.27%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.27%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.27%   |
| Lenovo USB-C to LAN                                                            | 3         | 0.96%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.96%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.96%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.64%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.64%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.64%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.64%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.64%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.64%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 236       | 54.5%   |
| WiFi     | 190       | 43.88%  |
| Modem    | 7         | 1.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 53.62%  |
| WiFi     | 128       | 46.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 151       | 57.85%  |
| 1     | 71        | 27.2%   |
| 3     | 13        | 4.98%   |
| 4     | 12        | 4.6%    |
| 6     | 7         | 2.68%   |
| 0     | 2         | 0.77%   |
| 132   | 1         | 0.38%   |
| 22    | 1         | 0.38%   |
| 12    | 1         | 0.38%   |
| 8     | 1         | 0.38%   |
| 5     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 234       | 89.31%  |
| Yes  | 28        | 10.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 71.88%  |
| Cambridge Silicon Radio         | 10        | 6.25%   |
| Broadcom                        | 8         | 5%      |
| Realtek Semiconductor           | 6         | 3.75%   |
| Qualcomm Atheros Communications | 5         | 3.13%   |
| IMC Networks                    | 5         | 3.13%   |
| Foxconn / Hon Hai               | 3         | 1.88%   |
| ASUSTek Computer                | 3         | 1.88%   |
| Ralink                          | 1         | 0.63%   |
| Micro Star International        | 1         | 0.63%   |
| MediaTek                        | 1         | 0.63%   |
| Integrated System Solution      | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 37        | 23.13%  |
| Intel Bluetooth wireless interface                                                  | 30        | 18.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 25        | 15.63%  |
| Intel AX200 Bluetooth                                                               | 11        | 6.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 6.25%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.5%    |
| Intel AX210 Bluetooth                                                               | 4         | 2.5%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.25%   |
| ASUS BCM20702A0                                                                     | 2         | 1.25%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.63%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.63%   |
| MediaTek Wireless_Device                                                            | 1         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.63%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.63%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.63%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.63%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.63%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.63%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 200       | 53.05%  |
| Nvidia                                       | 68        | 18.04%  |
| AMD                                          | 34        | 9.02%   |
| Lenovo                                       | 17        | 4.51%   |
| Texas Instruments                            | 6         | 1.59%   |
| Plantronics                                  | 6         | 1.59%   |
| Realtek Semiconductor                        | 5         | 1.33%   |
| JMTek                                        | 5         | 1.33%   |
| GN Netcom                                    | 5         | 1.33%   |
| Creative Labs                                | 4         | 1.06%   |
| Logitech                                     | 3         | 0.8%    |
| Generalplus Technology                       | 3         | 0.8%    |
| Creative Technology                          | 3         | 0.8%    |
| Sennheiser Communications                    | 2         | 0.53%   |
| C-Media Electronics                          | 2         | 0.53%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.27%   |
| Tenx Technology                              | 1         | 0.27%   |
| SteelSeries ApS                              | 1         | 0.27%   |
| Sony                                         | 1         | 0.27%   |
| RODE Microphones                             | 1         | 0.27%   |
| LG Electronics                               | 1         | 0.27%   |
| Google                                       | 1         | 0.27%   |
| Giga-Byte Technology                         | 1         | 0.27%   |
| Focusrite-Novation                           | 1         | 0.27%   |
| Dynex                                        | 1         | 0.27%   |
| Dell                                         | 1         | 0.27%   |
| Corsair                                      | 1         | 0.27%   |
| Blue Microphones                             | 1         | 0.27%   |
| ASUSTek Computer                             | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 6.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 5.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 4.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 4.39%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 3.41%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 2.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.2%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.46%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6         | 1.46%   |
| Texas Instruments PCM2902 Audio Codec                                      | 5         | 1.22%   |
| Realtek Semiconductor USB Audio                                            | 5         | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.22%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.22%   |
| Plantronics BT600                                                          | 4         | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.98%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 0.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.73%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.73%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.71%  |
| SK hynix            | 37        | 26.81%  |
| Micron Technology   | 14        | 10.14%  |
| Crucial             | 11        | 7.97%   |
| Kingston            | 9         | 6.52%   |
| Unknown             | 5         | 3.62%   |
| Corsair             | 5         | 3.62%   |
| Transcend           | 2         | 1.45%   |
| Smart               | 2         | 1.45%   |
| Hewlett-Packard     | 2         | 1.45%   |
| GOODRAM             | 2         | 1.45%   |
| Elpida              | 2         | 1.45%   |
| Unknown (0x0B5E)    | 1         | 0.72%   |
| Unknown (0x0205)    | 1         | 0.72%   |
| Patriot             | 1         | 0.72%   |
| Innodisk            | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 2.72%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 4         | 2.72%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s         | 3         | 2.04%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s           | 3         | 2.04%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 3         | 2.04%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 2.04%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                    | 2         | 1.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 1.36%   |
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s        | 2         | 1.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 1.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 1.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 1.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.36%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s            | 2         | 1.36%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s            | 2         | 1.36%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s            | 2         | 1.36%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s            | 2         | 1.36%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s            | 2         | 1.36%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 1.36%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1         | 0.68%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 0.68%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 0.68%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 0.68%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s           | 1         | 0.68%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 0.68%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 0.68%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 0.68%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.68%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 0.68%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s           | 1         | 0.68%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 0.68%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 63.03%  |
| DDR3    | 30        | 25.21%  |
| SDRAM   | 3         | 2.52%   |
| LPDDR4  | 3         | 2.52%   |
| LPDDR3  | 2         | 1.68%   |
| DRAM    | 2         | 1.68%   |
| LPDDR5  | 1         | 0.84%   |
| DDR5    | 1         | 0.84%   |
| DDR2    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 59        | 50%     |
| SODIMM       | 52        | 44.07%  |
| Row Of Chips | 3         | 2.54%   |
| RIMM         | 2         | 1.69%   |
| Chip         | 2         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 47        | 37.6%   |
| 16384 | 35        | 28%     |
| 4096  | 24        | 19.2%   |
| 32768 | 13        | 10.4%   |
| 2048  | 3         | 2.4%    |
| 65536 | 2         | 1.6%    |
| 1024  | 1         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 17.32%  |
| 3200    | 21        | 16.54%  |
| 2400    | 20        | 15.75%  |
| 2667    | 16        | 12.6%   |
| 2133    | 14        | 11.02%  |
| 1333    | 8         | 6.3%    |
| 2666    | 5         | 3.94%   |
| 3600    | 4         | 3.15%   |
| 3266    | 3         | 2.36%   |
| 2933    | 3         | 2.36%   |
| 6400    | 2         | 1.57%   |
| 1867    | 2         | 1.57%   |
| 2472    | 1         | 0.79%   |
| 2048    | 1         | 0.79%   |
| 1866    | 1         | 0.79%   |
| 1334    | 1         | 0.79%   |
| 1066    | 1         | 0.79%   |
| 800     | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 3         | 33.33%  |
| Hewlett-Packard    | 3         | 33.33%  |
| Canon              | 2         | 22.22%  |
| Brother Industries | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series       | 1         | 11.11%  |
| Seiko Epson WF-3520 Series       | 1         | 11.11%  |
| Seiko Epson L3210 Series         | 1         | 11.11%  |
| HP LaserJet Professional P 1102w | 1         | 11.11%  |
| HP ENVY 4500 series              | 1         | 11.11%  |
| HP DeskJet 2600 series           | 1         | 11.11%  |
| Canon E560 series                | 1         | 11.11%  |
| Canon CanoScan LiDE 300          | 1         | 11.11%  |
| Brother DCP-1610W                | 1         | 11.11%  |

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
| Chicony Electronics                    | 47        | 27.33%  |
| IMC Networks                           | 25        | 14.53%  |
| Acer                                   | 13        | 7.56%   |
| Realtek Semiconductor                  | 12        | 6.98%   |
| Microdia                               | 11        | 6.4%    |
| Logitech                               | 10        | 5.81%   |
| Sunplus Innovation Technology          | 8         | 4.65%   |
| Suyin                                  | 4         | 2.33%   |
| Lite-On Technology                     | 4         | 2.33%   |
| Hopewin Electronic Material            | 4         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.33%   |
| Bison Electronics                      | 4         | 2.33%   |
| Samsung Electronics                    | 3         | 1.74%   |
| Microsoft                              | 3         | 1.74%   |
| Generalplus Technology                 | 3         | 1.74%   |
| Syntek                                 | 2         | 1.16%   |
| Ruision                                | 2         | 1.16%   |
| Quanta                                 | 2         | 1.16%   |
| Luxvisions Innotech Limited            | 2         | 1.16%   |
| Sonix Technology                       | 1         | 0.58%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.58%   |
| Remo Tech                              | 1         | 0.58%   |
| LG Electronics                         | 1         | 0.58%   |
| Lenovo                                 | 1         | 0.58%   |
| KYE Systems (Mouse Systems)            | 1         | 0.58%   |
| Jieli Technology                       | 1         | 0.58%   |
| Creative Technology                    | 1         | 0.58%   |
| ARC International                      | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 27        | 15.43%  |
| IMC Networks Integrated Camera                    | 20        | 11.43%  |
| Realtek Integrated_Webcam_HD                      | 9         | 5.14%   |
| Sunplus Integrated_Webcam_HD                      | 5         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 2.86%   |
| Acer SunplusIT Integrated Camera                  | 5         | 2.86%   |
| Acer Integrated Camera                            | 5         | 2.86%   |
| Microdia Integrated_Webcam_HD                     | 4         | 2.29%   |
| Logitech HD Pro Webcam C920                       | 4         | 2.29%   |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 4         | 2.29%   |
| Chicony HP HD Camera                              | 4         | 2.29%   |
| Samsung Galaxy A5 (MTP)                           | 3         | 1.71%   |
| Lite-On Integrated Camera                         | 3         | 1.71%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 1.71%   |
| Generalplus GENERAL WEBCAM                        | 3         | 1.71%   |
| Bison Integrated Camera                           | 3         | 1.71%   |
| Suyin Integrated_Webcam_HD                        | 2         | 1.14%   |
| Ruision UVC Camera                                | 2         | 1.14%   |
| Microdia Webcam                                   | 2         | 1.14%   |
| Microdia Integrated Webcam                        | 2         | 1.14%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 1.14%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.14%   |
| Acer Integrated IR Camera                         | 2         | 1.14%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.57%   |
| Syntek Integrated Camera                          | 1         | 0.57%   |
| Suyin RGBIR Camera                                | 1         | 0.57%   |
| Suyin HP Truevision HD                            | 1         | 0.57%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.57%   |
| Sunplus Integrated Webcam                         | 1         | 0.57%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.57%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.57%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.57%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.57%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.57%   |
| Realtek USB Camera                                | 1         | 0.57%   |
| Realtek NexiGo N960E FHD Webcam                   | 1         | 0.57%   |
| Quanta HP TrueVision HD Camera                    | 1         | 0.57%   |
| Quanta HP HD Camera                               | 1         | 0.57%   |
| Microsoft LifeCam VX-2000                         | 1         | 0.57%   |
| Microsoft LifeCam HD-3000                         | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 37        | 58.73%  |
| Validity Sensors           | 17        | 26.98%  |
| Shenzhen Goodix Technology | 5         | 7.94%   |
| Upek                       | 2         | 3.17%   |
| Samsung Electronics        | 1         | 1.59%   |
| Elan Microelectronics      | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 41.27%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 6.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.59%   |
| Validity Sensors VFS491                                                    | 1         | 1.59%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.59%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.59%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.59%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.59%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 10        | 45.45%  |
| Alcor Micro           | 5         | 22.73%  |
| Lenovo                | 2         | 9.09%   |
| Yubico.com            | 1         | 4.55%   |
| Upek                  | 1         | 4.55%   |
| SCM Microsystems      | 1         | 4.55%   |
| OmniKey               | 1         | 4.55%   |
| Gemalto (was Gemplus) | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 22.73%  |
| Broadcom 5880                                              | 4         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 13.64%  |
| Broadcom 58200                                             | 3         | 13.64%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 9.09%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 4.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.55%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 4.55%   |
| OmniKey CardMan 3121 (HID Technologies)                    | 1         | 4.55%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 132       | 49.81%  |
| 1     | 88        | 33.21%  |
| 2     | 28        | 10.57%  |
| 3     | 11        | 4.15%   |
| 5     | 4         | 1.51%   |
| 4     | 2         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 32.81%  |
| Graphics card            | 33        | 17.19%  |
| Unassigned class         | 24        | 12.5%   |
| Communication controller | 21        | 10.94%  |
| Net/wireless             | 11        | 5.73%   |
| Chipcard                 | 11        | 5.73%   |
| Multimedia controller    | 6         | 3.13%   |
| Card reader              | 6         | 3.13%   |
| Net/ethernet             | 4         | 2.08%   |
| Bluetooth                | 4         | 2.08%   |
| Storage/ide              | 2         | 1.04%   |
| Storage                  | 2         | 1.04%   |
| Camera                   | 2         | 1.04%   |
| Storage/raid             | 1         | 0.52%   |
| Sound                    | 1         | 0.52%   |
| Network                  | 1         | 0.52%   |

