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

Total: 381

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| RHEL 8 | 179       | 71.31%  |
| RHEL 7 | 39        | 15.54%  |
| RHEL 9 | 33        | 13.15%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 250       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64                 | 14        | 4.78%   |
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 4.78%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 12        | 4.1%    |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 3.75%   |
| 4.18.0-305.el8.x86_64                        | 10        | 3.41%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 3.07%   |
| 4.18.0-348.12.2.el8_5.x86_64                 | 9         | 3.07%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 9         | 3.07%   |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 2.73%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 2.73%   |
| 5.14.0-162.6.1.el9_1.x86_64                  | 7         | 2.39%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 2.39%   |
| 5.14.0-70.17.1.el9_0.x86_64                  | 6         | 2.05%   |
| 4.18.0-425.3.1.el8.x86_64                    | 6         | 2.05%   |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 2.05%   |
| 4.18.0-193.el8.x86_64                        | 6         | 2.05%   |
| 4.18.0-193.19.1.el8_2.x86_64                 | 6         | 2.05%   |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 2.05%   |
| 4.18.0-147.3.1.el8_1.x86_64                  | 6         | 2.05%   |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 2.05%   |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 1.71%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 1.71%   |
| 5.14.0-70.5.1.el9_0.x86_64                   | 4         | 1.37%   |
| 5.14.0-70.26.1.el9_0.x86_64                  | 4         | 1.37%   |
| 5.14.0-162.12.1.el9_1.x86_64                 | 4         | 1.37%   |
| 4.18.0-425.10.1.el8_7.x86_64                 | 4         | 1.37%   |
| 4.18.0-372.9.1.el8.x86_64                    | 4         | 1.37%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.37%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.37%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.37%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.37%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.37%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 3         | 1.02%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 1.02%   |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 1.02%   |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 1.02%   |
| 5.14.0-70.22.1.el9_0.x86_64                  | 2         | 0.68%   |
| 5.14.0-70.13.1.el9_0.x86_64                  | 2         | 0.68%   |
| 4.18.0-372.32.1.el8_6.x86_64                 | 2         | 0.68%   |
| 4.18.0-372.26.1.el8_6.x86_64                 | 2         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 173       | 68.92%  |
| 3.10.0   | 39        | 15.54%  |
| 5.14.0   | 33        | 13.15%  |
| 5.9.1    | 1         | 0.4%    |
| 5.13.13  | 1         | 0.4%    |
| 5.13.0   | 1         | 0.4%    |
| 5.10.6   | 1         | 0.4%    |
| 4.19.150 | 1         | 0.4%    |
| Unknown  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 173       | 68.92%  |
| 3.10    | 39        | 15.54%  |
| 5.14    | 33        | 13.15%  |
| 5.13    | 2         | 0.8%    |
| 5.9     | 1         | 0.4%    |
| 5.10    | 1         | 0.4%    |
| 4.19    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 248       | 99.2%   |
| aarch64 | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 190       | 73.36%  |
| Unknown       | 46        | 17.76%  |
| GNOME Classic | 14        | 5.41%   |
| KDE5          | 5         | 1.93%   |
| KDE           | 2         | 0.77%   |
| MATE          | 1         | 0.39%   |
| Cinnamon      | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 131       | 50.97%  |
| Wayland | 95        | 36.96%  |
| Unknown | 29        | 11.28%  |
| Tty     | 2         | 0.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 72.97%  |
| GDM     | 68        | 26.25%  |
| SDDM    | 1         | 0.39%   |
| LightDM | 1         | 0.39%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 169       | 66.27%  |
| Unknown | 26        | 10.2%   |
| en_GB   | 16        | 6.27%   |
| en_IN   | 6         | 2.35%   |
| ru_RU   | 4         | 1.57%   |
| pt_BR   | 4         | 1.57%   |
| pl_PL   | 4         | 1.57%   |
| fr_FR   | 4         | 1.57%   |
| de_DE   | 4         | 1.57%   |
| nl_NL   | 2         | 0.78%   |
| es_ES   | 2         | 0.78%   |
| es_AR   | 2         | 0.78%   |
| en_IE   | 2         | 0.78%   |
| sl_SI   | 1         | 0.39%   |
| ko_KR   | 1         | 0.39%   |
| ja_JP   | 1         | 0.39%   |
| it_IT   | 1         | 0.39%   |
| es_MX   | 1         | 0.39%   |
| es_EC   | 1         | 0.39%   |
| en_NZ   | 1         | 0.39%   |
| en_DK   | 1         | 0.39%   |
| de_CH   | 1         | 0.39%   |
| cs_CZ   | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 186       | 72.94%  |
| BIOS | 69        | 27.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 214       | 84.58%  |
| Ext4    | 27        | 10.67%  |
| Unknown | 12        | 4.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 59.85%  |
| GPT     | 85        | 32.82%  |
| MBR     | 19        | 7.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 221       | 87.01%  |
| Yes       | 33        | 12.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 231       | 90.94%  |
| Yes       | 23        | 9.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 90        | 36%     |
| Dell                    | 54        | 21.6%   |
| Hewlett-Packard         | 30        | 12%     |
| ASUSTek Computer        | 21        | 8.4%    |
| Gigabyte Technology     | 11        | 4.4%    |
| MSI                     | 7         | 2.8%    |
| ASRock                  | 6         | 2.4%    |
| Unknown                 | 5         | 2%      |
| Intel                   | 4         | 1.6%    |
| Supermicro              | 3         | 1.2%    |
| ZTSYSTEMS               | 2         | 0.8%    |
| Sony                    | 2         | 0.8%    |
| Acer                    | 2         | 0.8%    |
| TUXEDO                  | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| Timi                    | 1         | 0.4%    |
| Samsung Electronics     | 1         | 0.4%    |
| Razer                   | 1         | 0.4%    |
| Raspberry Pi Foundation | 1         | 0.4%    |
| MiTAC                   | 1         | 0.4%    |
| Hardkernel              | 1         | 0.4%    |
| Getac                   | 1         | 0.4%    |
| CX / Air Computers.     | 1         | 0.4%    |
| AZW                     | 1         | 0.4%    |
| AMI                     | 1         | 0.4%    |
| Alienware               | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 2.4%    |
| Unknown                                  | 6         | 2.4%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.6%    |
| Dell PowerEdge R230                      | 4         | 1.6%    |
| ASUS All Series                          | 4         | 1.6%    |
| Supermicro X10DRi                        | 2         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.8%    |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.8%    |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.8%    |
| Lenovo ThinkPad T480s 20L8S2N800         | 2         | 0.8%    |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.8%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.8%    |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 0.8%    |
| HP Z620 Workstation                      | 2         | 0.8%    |
| HP EliteBook 8460p                       | 2         | 0.8%    |
| Dell Precision 7560                      | 2         | 0.8%    |
| Dell Precision 7510                      | 2         | 0.8%    |
| Dell PowerEdge R740                      | 2         | 0.8%    |
| Dell OptiPlex 9020                       | 2         | 0.8%    |
| Dell Latitude E6430                      | 2         | 0.8%    |
| Dell Latitude 5300                       | 2         | 0.8%    |
| ZTSYSTEMS Z802                           | 1         | 0.4%    |
| ZTSYSTEMS Z801                           | 1         | 0.4%    |
| TUXEDO N13xWU                            | 1         | 0.4%    |
| Toshiba Satellite Pro R50-C              | 1         | 0.4%    |
| Timi TM1707                              | 1         | 0.4%    |
| Supermicro X7DW3                         | 1         | 0.4%    |
| Sony VPCEB4L1R                           | 1         | 0.4%    |
| Sony VPCEB23FM                           | 1         | 0.4%    |
| Samsung 730QCJ/730QCR                    | 1         | 0.4%    |
| Razer Blade 15 Mid 2019-Base             | 1         | 0.4%    |
| RPi Raspberry Pi 4 Model B               | 1         | 0.4%    |
| MSI MS-7C95                              | 1         | 0.4%    |
| MSI MS-7B51                              | 1         | 0.4%    |
| MSI MS-7B33                              | 1         | 0.4%    |
| MSI MS-7A37                              | 1         | 0.4%    |
| MSI MS-7752                              | 1         | 0.4%    |
| MSI GP75 Leopard 9SD                     | 1         | 0.4%    |
| MSI GE72VR 7RF                           | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 77        | 30.8%   |
| Dell Precision     | 15        | 6%      |
| Dell PowerEdge     | 14        | 5.6%    |
| Dell Latitude      | 12        | 4.8%    |
| Unknown            | 6         | 2.4%    |
| HP ProLiant        | 5         | 2%      |
| HP EliteBook       | 5         | 2%      |
| Dell Inspiron      | 4         | 1.6%    |
| ASUS PRIME         | 4         | 1.6%    |
| ASUS All           | 4         | 1.6%    |
| Lenovo ThinkCentre | 3         | 1.2%    |
| HP ZBook           | 3         | 1.2%    |
| Dell OptiPlex      | 3         | 1.2%    |
| Supermicro X10DRi  | 2         | 0.8%    |
| Lenovo 7X56CTO1WW  | 2         | 0.8%    |
| HP Z620            | 2         | 0.8%    |
| HP Z230            | 2         | 0.8%    |
| Dell XPS           | 2         | 0.8%    |
| ASUS TUF           | 2         | 0.8%    |
| ASUS ROG           | 2         | 0.8%    |
| ZTSYSTEMS Z802     | 1         | 0.4%    |
| ZTSYSTEMS Z801     | 1         | 0.4%    |
| TUXEDO N13xWU      | 1         | 0.4%    |
| Toshiba Satellite  | 1         | 0.4%    |
| Timi TM1707        | 1         | 0.4%    |
| Supermicro X7DW3   | 1         | 0.4%    |
| Sony VPCEB4L1R     | 1         | 0.4%    |
| Sony VPCEB23FM     | 1         | 0.4%    |
| Samsung 730QCJ     | 1         | 0.4%    |
| Razer Blade        | 1         | 0.4%    |
| RPi Raspberry      | 1         | 0.4%    |
| MSI MS-7C95        | 1         | 0.4%    |
| MSI MS-7B51        | 1         | 0.4%    |
| MSI MS-7B33        | 1         | 0.4%    |
| MSI MS-7A37        | 1         | 0.4%    |
| MSI MS-7752        | 1         | 0.4%    |
| MSI GP75           | 1         | 0.4%    |
| MSI GE72VR         | 1         | 0.4%    |
| MiTAC C4I          | 1         | 0.4%    |
| Lenovo Z40-70      | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 44        | 17.6%   |
| 2020 | 40        | 16%     |
| 2018 | 33        | 13.2%   |
| 2016 | 21        | 8.4%    |
| 2017 | 18        | 7.2%    |
| 2015 | 18        | 7.2%    |
| 2021 | 17        | 6.8%    |
| 2012 | 17        | 6.8%    |
| 2013 | 12        | 4.8%    |
| 2022 | 8         | 3.2%    |
| 2011 | 8         | 3.2%    |
| 2014 | 6         | 2.4%    |
| 2010 | 6         | 2.4%    |
| 2009 | 2         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 139       | 55.6%   |
| Desktop        | 75        | 30%     |
| Server         | 24        | 9.6%    |
| Convertible    | 5         | 2%      |
| Mini pc        | 5         | 2%      |
| System on chip | 1         | 0.4%    |
| All in one     | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 224       | 88.89%  |
| Enabled  | 28        | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 250       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 63        | 24.51%  |
| 8.01-16.0       | 48        | 18.68%  |
| 4.01-8.0        | 43        | 16.73%  |
| 64.01-256.0     | 39        | 15.18%  |
| 16.01-24.0      | 36        | 14.01%  |
| 24.01-32.0      | 11        | 4.28%   |
| 3.01-4.0        | 9         | 3.5%    |
| More than 256.0 | 6         | 2.33%   |
| 2.01-3.0        | 1         | 0.39%   |
| Unknown         | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 96        | 34.66%  |
| 2.01-3.0        | 56        | 20.22%  |
| 3.01-4.0        | 42        | 15.16%  |
| 8.01-16.0       | 41        | 14.8%   |
| 1.01-2.0        | 24        | 8.66%   |
| 24.01-32.0      | 6         | 2.17%   |
| 16.01-24.0      | 4         | 1.44%   |
| 0.51-1.0        | 3         | 1.08%   |
| 32.01-64.0      | 2         | 0.72%   |
| More than 256.0 | 1         | 0.36%   |
| 64.01-256.0     | 1         | 0.36%   |
| Unknown         | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 53.49%  |
| 2      | 58        | 22.48%  |
| 3      | 30        | 11.63%  |
| 5      | 10        | 3.88%   |
| 4      | 10        | 3.88%   |
| 12     | 3         | 1.16%   |
| 6      | 3         | 1.16%   |
| 8      | 2         | 0.78%   |
| 14     | 1         | 0.39%   |
| 11     | 1         | 0.39%   |
| 7      | 1         | 0.39%   |
| 0      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 198       | 78.57%  |
| Yes       | 54        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 90.84%  |
| No        | 23        | 9.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 72.8%   |
| No        | 68        | 27.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 58.98%  |
| No        | 105       | 41.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 64        | 25.6%   |
| India        | 23        | 9.2%    |
| Germany      | 17        | 6.8%    |
| UK           | 15        | 6%      |
| Czechia      | 13        | 5.2%    |
| Canada       | 8         | 3.2%    |
| Norway       | 7         | 2.8%    |
| France       | 6         | 2.4%    |
| Brazil       | 6         | 2.4%    |
| Spain        | 5         | 2%      |
| Poland       | 5         | 2%      |
| Switzerland  | 4         | 1.6%    |
| Russia       | 4         | 1.6%    |
| Netherlands  | 4         | 1.6%    |
| Mexico       | 4         | 1.6%    |
| Italy        | 4         | 1.6%    |
| Finland      | 4         | 1.6%    |
| South Africa | 3         | 1.2%    |
| Lithuania    | 3         | 1.2%    |
| Argentina    | 3         | 1.2%    |
| Ukraine      | 2         | 0.8%    |
| Turkey       | 2         | 0.8%    |
| South Korea  | 2         | 0.8%    |
| Singapore    | 2         | 0.8%    |
| Romania      | 2         | 0.8%    |
| Japan        | 2         | 0.8%    |
| Egypt        | 2         | 0.8%    |
| China        | 2         | 0.8%    |
| Chile        | 2         | 0.8%    |
| Austria      | 2         | 0.8%    |
| Australia    | 2         | 0.8%    |
| Turkmenistan | 1         | 0.4%    |
| Sweden       | 1         | 0.4%    |
| Sri Lanka    | 1         | 0.4%    |
| Slovenia     | 1         | 0.4%    |
| Saudi Arabia | 1         | 0.4%    |
| Portugal     | 1         | 0.4%    |
| Pakistan     | 1         | 0.4%    |
| New Zealand  | 1         | 0.4%    |
| Nepal        | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Prague           | 11        | 4.18%   |
| Quincy           | 8         | 3.04%   |
| Langgons         | 6         | 2.28%   |
| Turku            | 4         | 1.52%   |
| Tromsø          | 4         | 1.52%   |
| San Jose         | 3         | 1.14%   |
| Munich           | 3         | 1.14%   |
| Milan            | 3         | 1.14%   |
| Mexico City      | 3         | 1.14%   |
| Chicago          | 3         | 1.14%   |
| Chennai          | 3         | 1.14%   |
| Bengaluru        | 3         | 1.14%   |
| Toronto          | 2         | 0.76%   |
| Singapore        | 2         | 0.76%   |
| Oslo             | 2         | 0.76%   |
| Montreal         | 2         | 0.76%   |
| Madrid           | 2         | 0.76%   |
| Kyiv             | 2         | 0.76%   |
| Houston          | 2         | 0.76%   |
| Didcot           | 2         | 0.76%   |
| Des Moines       | 2         | 0.76%   |
| Berlin           | 2         | 0.76%   |
| Zaragoza         | 1         | 0.38%   |
| Yorktown Heights | 1         | 0.38%   |
| Yongin-si        | 1         | 0.38%   |
| Wroclaw          | 1         | 0.38%   |
| Wiesbaden        | 1         | 0.38%   |
| Webster          | 1         | 0.38%   |
| Vienna           | 1         | 0.38%   |
| Vardenis         | 1         | 0.38%   |
| Vaglio           | 1         | 0.38%   |
| Udaipur          | 1         | 0.38%   |
| Tiruchi          | 1         | 0.38%   |
| Temuco           | 1         | 0.38%   |
| Temara           | 1         | 0.38%   |
| Tauranga         | 1         | 0.38%   |
| Taringa          | 1         | 0.38%   |
| Talkha           | 1         | 0.38%   |
| Syracuse         | 1         | 0.38%   |
| Sutton           | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 105    | 16.58%  |
| Seagate             | 49        | 96     | 12.69%  |
| WDC                 | 48        | 78     | 12.44%  |
| Toshiba             | 34        | 47     | 8.81%   |
| SanDisk             | 21        | 31     | 5.44%   |
| SK hynix            | 20        | 25     | 5.18%   |
| Kingston            | 16        | 20     | 4.15%   |
| Intel               | 16        | 23     | 4.15%   |
| Micron Technology   | 13        | 21     | 3.37%   |
| Unknown             | 10        | 12     | 2.59%   |
| Crucial             | 10        | 13     | 2.59%   |
| HGST                | 7         | 10     | 1.81%   |
| A-DATA Technology   | 7         | 7      | 1.81%   |
| Phison              | 6         | 10     | 1.55%   |
| Dell                | 5         | 9      | 1.3%    |
| KIOXIA              | 4         | 4      | 1.04%   |
| Hitachi             | 4         | 4      | 1.04%   |
| Hewlett-Packard     | 4         | 13     | 1.04%   |
| Gigabyte Technology | 4         | 5      | 1.04%   |
| China               | 4         | 4      | 1.04%   |
| Silicon Motion      | 3         | 4      | 0.78%   |
| PNY                 | 3         | 4      | 0.78%   |
| Lenovo              | 3         | 3      | 0.78%   |
| Corsair             | 3         | 6      | 0.78%   |
| Western Digital     | 2         | 2      | 0.52%   |
| SSSTC               | 2         | 2      | 0.52%   |
| ADATA Technology    | 2         | 2      | 0.52%   |
| XUM                 | 1         | 1      | 0.26%   |
| XPG                 | 1         | 1      | 0.26%   |
| UMIS                | 1         | 1      | 0.26%   |
| Transcend           | 1         | 1      | 0.26%   |
| Team                | 1         | 2      | 0.26%   |
| T-FORCE             | 1         | 2      | 0.26%   |
| SMI                 | 1         | 2      | 0.26%   |
| SCST_FIO            | 1         | 9      | 0.26%   |
| SABRENT             | 1         | 1      | 0.26%   |
| Plextor             | 1         | 1      | 0.26%   |
| OCZ                 | 1         | 2      | 0.26%   |
| NVMe                | 1         | 1      | 0.26%   |
| Lite-On             | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB          | 10        | 2.3%    |
| Samsung NVMe SSD Drive 512GB           | 8         | 1.84%   |
| Toshiba NVMe SSD Drive 256GB           | 6         | 1.38%   |
| SanDisk NVMe SSD Drive 256GB           | 6         | 1.38%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 1.38%   |
| Samsung SSD 860 EVO 1TB                | 5         | 1.15%   |
| Samsung NVMe SSD Drive 1024GB          | 5         | 1.15%   |
| HGST HTS721010A9E630 1TB               | 5         | 1.15%   |
| Toshiba MG04ACA100NY 1TB               | 4         | 0.92%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.92%   |
| Intel NVMe SSD Drive 512GB             | 4         | 0.92%   |
| Dell MD34xx 26TB                       | 4         | 0.92%   |
| WDC WD5003ABYZ-011FA0 500GB            | 3         | 0.69%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.69%   |
| Seagate ST1000LM049-2GH172 1TB         | 3         | 0.69%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.69%   |
| Samsung NVMe SSD Drive 2TB             | 3         | 0.69%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.69%   |
| Micron NVMe SSD Drive 256GB            | 3         | 0.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.46%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 2         | 0.46%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 0.46%   |
| Unknown SD/MMC/MS PRO 16GB             | 2         | 0.46%   |
| Unknown NVMe SSD Drive 256GB           | 2         | 0.46%   |
| Toshiba NVMe SSD Drive 1024GB          | 2         | 0.46%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.46%   |
| Toshiba KXG6AZNV256G 256GB             | 2         | 0.46%   |
| Toshiba DT01ACA200 2TB                 | 2         | 0.46%   |
| Toshiba AL14SEB18EQ 1.8TB              | 2         | 0.46%   |
| SK hynix NVMe SSD Drive 1024GB         | 2         | 0.46%   |
| Seagate ST91000640NS 1TB               | 2         | 0.46%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.46%   |
| Seagate ST4000NM0033-9ZM170 4TB        | 2         | 0.46%   |
| Seagate ST300MP0026 304GB              | 2         | 0.46%   |
| Seagate ST2000NX0433 2TB               | 2         | 0.46%   |
| Seagate ST2000NX0273 2TB               | 2         | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB         | 2         | 0.46%   |
| Seagate ST1000DM003-9YN162 1TB         | 2         | 0.46%   |
| Seagate Expansion 1TB                  | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 95     | 37.69%  |
| WDC                 | 39        | 64     | 30%     |
| Toshiba             | 19        | 29     | 14.62%  |
| HGST                | 7         | 10     | 5.38%   |
| Hitachi             | 4         | 4      | 3.08%   |
| Dell                | 4         | 8      | 3.08%   |
| Unknown             | 2         | 2      | 1.54%   |
| Hewlett-Packard     | 2         | 9      | 1.54%   |
| SCST_FIO            | 1         | 9      | 0.77%   |
| Samsung Electronics | 1         | 2      | 0.77%   |
| SABRENT             | 1         | 1      | 0.77%   |
| DELLBOSS            | 1         | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 36     | 27.62%  |
| Kingston            | 11        | 15     | 10.48%  |
| Crucial             | 10        | 13     | 9.52%   |
| WDC                 | 7         | 9      | 6.67%   |
| Micron Technology   | 7         | 13     | 6.67%   |
| SanDisk             | 6         | 12     | 5.71%   |
| A-DATA Technology   | 5         | 5      | 4.76%   |
| SK hynix            | 4         | 8      | 3.81%   |
| Intel               | 4         | 5      | 3.81%   |
| China               | 4         | 4      | 3.81%   |
| PNY                 | 3         | 4      | 2.86%   |
| Corsair             | 3         | 6      | 2.86%   |
| XUM                 | 1         | 1      | 0.95%   |
| Transcend           | 1         | 1      | 0.95%   |
| Toshiba             | 1         | 1      | 0.95%   |
| Team                | 1         | 2      | 0.95%   |
| Seagate             | 1         | 1      | 0.95%   |
| Plextor             | 1         | 1      | 0.95%   |
| OCZ                 | 1         | 2      | 0.95%   |
| KingSpec            | 1         | 1      | 0.95%   |
| KINGBANK            | 1         | 1      | 0.95%   |
| Hoodisk             | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Anobit              | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 134       | 202    | 38.51%  |
| HDD     | 107       | 234    | 30.75%  |
| SSD     | 96        | 144    | 27.59%  |
| MMC     | 6         | 7      | 1.72%   |
| Unknown | 5         | 7      | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 148       | 351    | 47.9%   |
| NVMe | 134       | 202    | 43.37%  |
| SAS  | 21        | 34     | 6.8%    |
| MMC  | 6         | 7      | 1.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 154    | 42.99%  |
| 0.51-1.0   | 71        | 109    | 33.18%  |
| 1.01-2.0   | 25        | 51     | 11.68%  |
| 3.01-4.0   | 12        | 32     | 5.61%   |
| 4.01-10.0  | 7         | 20     | 3.27%   |
| 20.01-50.0 | 4         | 8      | 1.87%   |
| 10.01-20.0 | 2         | 3      | 0.93%   |
| 2.01-3.0   | 1         | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 84        | 32.18%  |
| 251-500        | 46        | 17.62%  |
| 501-1000       | 43        | 16.48%  |
| More than 3000 | 21        | 8.05%   |
| 1001-2000      | 20        | 7.66%   |
| Unknown        | 17        | 6.51%   |
| 51-100         | 11        | 4.21%   |
| 2001-3000      | 10        | 3.83%   |
| 1-20           | 6         | 2.3%    |
| 21-50          | 3         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 24.73%  |
| 21-50          | 58        | 21.09%  |
| 101-250        | 45        | 16.36%  |
| 51-100         | 39        | 14.18%  |
| 251-500        | 19        | 6.91%   |
| Unknown        | 17        | 6.18%   |
| 501-1000       | 11        | 4%      |
| 1001-2000      | 10        | 3.64%   |
| More than 3000 | 5         | 1.82%   |
| 2001-3000      | 3         | 1.09%   |

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
| Detected | 161       | 354    | 60.3%   |
| Works    | 95        | 223    | 35.58%  |
| Malfunc  | 11        | 17     | 4.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 161       | 46.13%  |
| Samsung Electronics            | 43        | 12.32%  |
| SanDisk                        | 18        | 5.16%   |
| AMD                            | 17        | 4.87%   |
| SK hynix                       | 16        | 4.58%   |
| Toshiba America Info Systems   | 14        | 4.01%   |
| Broadcom / LSI                 | 14        | 4.01%   |
| Phison Electronics             | 9         | 2.58%   |
| LSI Logic / Symbios Logic      | 7         | 2.01%   |
| Micron Technology              | 6         | 1.72%   |
| KIOXIA                         | 6         | 1.72%   |
| Silicon Motion                 | 5         | 1.43%   |
| Kingston Technology Company    | 5         | 1.43%   |
| ADATA Technology               | 5         | 1.43%   |
| Marvell Technology Group       | 4         | 1.15%   |
| Hewlett-Packard                | 4         | 1.15%   |
| ASMedia Technology             | 4         | 1.15%   |
| Lenovo                         | 3         | 0.86%   |
| Western Digital                | 2         | 0.57%   |
| Biwin Storage Technology       | 2         | 0.57%   |
| Union Memory (Shenzhen)        | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Lite-On Technology             | 1         | 0.29%   |
| HighPoint Technologies         | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 32        | 8.08%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 15        | 3.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 3.79%   |
| SK hynix Non-Volatile memory controller                                        | 13        | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 3.28%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 13        | 3.28%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 2.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.02%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 8         | 2.02%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.77%   |
| Micron Non-Volatile memory controller                                          | 6         | 1.52%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 6         | 1.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.26%   |
| Intel SSD 660P Series                                                          | 5         | 1.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.01%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 1.01%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.01%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                           | 4         | 1.01%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.01%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.01%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 4         | 1.01%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4         | 1.01%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 4         | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.01%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 4         | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.01%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 149       | 43.19%  |
| NVMe | 134       | 38.84%  |
| RAID | 44        | 12.75%  |
| SAS  | 10        | 2.9%    |
| IDE  | 8         | 2.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 227       | 90.8%   |
| AMD    | 22        | 8.8%    |
| ARM    | 1         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz     | 11        | 4.4%    |
| Intel Core i7-8665U CPU @ 1.90GHz      | 9         | 3.6%    |
| Intel Core i7-10610U CPU @ 1.80GHz     | 9         | 3.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz      | 6         | 2.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz     | 5         | 2%      |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz    | 4         | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz      | 4         | 1.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz       | 4         | 1.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz      | 4         | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz      | 4         | 1.6%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz    | 3         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz      | 3         | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 3         | 1.2%    |
| Intel Core i7-7600U CPU @ 2.80GHz      | 3         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz      | 3         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz      | 3         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz      | 3         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz      | 3         | 1.2%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 3         | 1.2%    |
| Intel Xeon Silver 4114 CPU @ 2.20GHz   | 2         | 0.8%    |
| Intel Xeon CPU E5620 @ 2.40GHz         | 2         | 0.8%    |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz    | 2         | 0.8%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 2         | 0.8%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 2         | 0.8%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 2         | 0.8%    |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 2         | 0.8%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 2         | 0.8%    |
| Intel Core i7-9850H CPU @ 2.60GHz      | 2         | 0.8%    |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 2         | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz      | 2         | 0.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz      | 2         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 0.8%    |
| Intel Core i5-8365U CPU @ 1.60GHz      | 2         | 0.8%    |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz      | 2         | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 0.8%    |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 94        | 37.6%   |
| Intel Core i5        | 48        | 19.2%   |
| Intel Xeon           | 42        | 16.8%   |
| Other                | 16        | 6.4%    |
| Intel Core i3        | 12        | 4.8%    |
| AMD Ryzen 7          | 7         | 2.8%    |
| AMD Ryzen 5          | 5         | 2%      |
| Intel Xeon Silver    | 3         | 1.2%    |
| Intel Core i9        | 3         | 1.2%    |
| AMD Ryzen 9          | 3         | 1.2%    |
| Intel Xeon Gold      | 2         | 0.8%    |
| Intel Pentium Gold   | 2         | 0.8%    |
| Intel Pentium        | 2         | 0.8%    |
| AMD Ryzen 3          | 2         | 0.8%    |
| AMD EPYC             | 2         | 0.8%    |
| Intel Xeon Platinum  | 1         | 0.4%    |
| Intel Pentium Silver | 1         | 0.4%    |
| Intel Core 2 Duo     | 1         | 0.4%    |
| Intel Celeron        | 1         | 0.4%    |
| AMD Ryzen 7 PRO      | 1         | 0.4%    |
| AMD FX               | 1         | 0.4%    |
| AMD A4               | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 107       | 42.8%   |
| 2      | 48        | 19.2%   |
| 6      | 38        | 15.2%   |
| 8      | 25        | 10%     |
| 12     | 11        | 4.4%    |
| 16     | 7         | 2.8%    |
| 20     | 4         | 1.6%    |
| 48     | 2         | 0.8%    |
| 36     | 2         | 0.8%    |
| 24     | 2         | 0.8%    |
| 96     | 1         | 0.4%    |
| 64     | 1         | 0.4%    |
| 32     | 1         | 0.4%    |
| 10     | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 222       | 88.8%   |
| 2      | 28        | 11.2%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 212       | 84.46%  |
| 1      | 39        | 15.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 242       | 96.03%  |
| Unknown        | 10        | 3.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 34        | 13.49%  |
| 0x906ea    | 16        | 6.35%   |
| 0x806ea    | 15        | 5.95%   |
| 0x306c3    | 14        | 5.56%   |
| 0x306a9    | 14        | 5.56%   |
| Unknown    | 13        | 5.16%   |
| 0xa0652    | 12        | 4.76%   |
| 0x506e3    | 10        | 3.97%   |
| 0x306f2    | 10        | 3.97%   |
| 0x206a7    | 9         | 3.57%   |
| 0x906ed    | 8         | 3.17%   |
| 0x906e9    | 7         | 2.78%   |
| 0x406e3    | 7         | 2.78%   |
| 0x806d1    | 6         | 2.38%   |
| 0x806e9    | 5         | 1.98%   |
| 0x806c1    | 5         | 1.98%   |
| 0x406f1    | 5         | 1.98%   |
| 0x306e4    | 4         | 1.59%   |
| 0x306d4    | 4         | 1.59%   |
| 0x206d7    | 4         | 1.59%   |
| 0xa0671    | 3         | 1.19%   |
| 0x40651    | 3         | 1.19%   |
| 0x206c2    | 3         | 1.19%   |
| 0x20655    | 3         | 1.19%   |
| 0x0a50000c | 3         | 1.19%   |
| 0x08600103 | 3         | 1.19%   |
| 0x08108102 | 3         | 1.19%   |
| 0x906c0    | 2         | 0.79%   |
| 0x50654    | 2         | 0.79%   |
| 0x08701021 | 2         | 0.79%   |
| 0xa0660    | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0x906eb    | 1         | 0.4%    |
| 0x906a4    | 1         | 0.4%    |
| 0x906a3    | 1         | 0.4%    |
| 0x90672    | 1         | 0.4%    |
| 0x706e5    | 1         | 0.4%    |
| 0x606a6    | 1         | 0.4%    |
| 0x50657    | 1         | 0.4%    |
| 0x20652    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 87        | 34.66%  |
| Haswell          | 29        | 11.55%  |
| Skylake          | 26        | 10.36%  |
| IvyBridge        | 19        | 7.57%   |
| CometLake        | 14        | 5.58%   |
| SandyBridge      | 13        | 5.18%   |
| Icelake          | 10        | 3.98%   |
| Zen 2            | 9         | 3.59%   |
| Broadwell        | 9         | 3.59%   |
| Westmere         | 7         | 2.79%   |
| TigerLake        | 5         | 1.99%   |
| Zen+             | 4         | 1.59%   |
| Unknown          | 4         | 1.59%   |
| Zen 3            | 3         | 1.2%    |
| Zen              | 3         | 1.2%    |
| Alderlake Hybrid | 3         | 1.2%    |
| Tremont          | 2         | 0.8%    |
| Penryn           | 2         | 0.8%    |
| Piledriver       | 1         | 0.4%    |
| Excavator        | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 156       | 51.32%  |
| Nvidia                     | 86        | 28.29%  |
| AMD                        | 33        | 10.86%  |
| Matrox Electronics Systems | 20        | 6.58%   |
| ASPEED Technology          | 9         | 2.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 18        | 5.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 16        | 5.21%   |
| Intel UHD Graphics 620                                                      | 15        | 4.89%   |
| Matrox Electronics Systems G200eR2                                          | 12        | 3.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 3.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 2.93%   |
| ASPEED Technology ASPEED Graphics Family                                    | 9         | 2.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 2.28%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 2.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 1.63%   |
| Intel HD Graphics 630                                                       | 5         | 1.63%   |
| Intel HD Graphics 530                                                       | 5         | 1.63%   |
| AMD Renoir                                                                  | 5         | 1.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 1.3%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 1.3%    |
| Intel HD Graphics 620                                                       | 4         | 1.3%    |
| Intel HD Graphics 5500                                                      | 4         | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.3%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 0.98%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 0.98%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 0.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.65%   |
| Nvidia GP107GLM [Quadro P620]                                               | 2         | 0.65%   |
| Nvidia GP106GL [Quadro P2200]                                               | 2         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.65%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 109       | 43.08%  |
| 1 x Nvidia              | 45        | 17.79%  |
| Intel + Nvidia          | 34        | 13.44%  |
| 1 x Matrox              | 19        | 7.51%   |
| 1 x AMD                 | 19        | 7.51%   |
| Intel + AMD             | 9         | 3.56%   |
| 1 x ASPEED              | 6         | 2.37%   |
| AMD + Nvidia            | 3         | 1.19%   |
| Other                   | 2         | 0.79%   |
| 2 x Nvidia              | 2         | 0.79%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.4%    |
| 2 x AMD                 | 1         | 0.4%    |
| Nvidia + Matrox         | 1         | 0.4%    |
| Nvidia + ASPEED         | 1         | 0.4%    |
| AMD + ASPEED            | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 196       | 77.17%  |
| Proprietary | 36        | 14.17%  |
| Unknown     | 22        | 8.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 62.65%  |
| 1.01-2.0   | 26        | 10.12%  |
| 3.01-4.0   | 18        | 7%      |
| 0.51-1.0   | 12        | 4.67%   |
| 7.01-8.0   | 11        | 4.28%   |
| 5.01-6.0   | 10        | 3.89%   |
| 0.01-0.5   | 9         | 3.5%    |
| 2.01-3.0   | 5         | 1.95%   |
| 4.01-5.0   | 2         | 0.78%   |
| 8.01-16.0  | 2         | 0.78%   |
| 16.01-24.0 | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 34        | 11.81%  |
| AU Optronics            | 32        | 11.11%  |
| Samsung Electronics     | 30        | 10.42%  |
| BOE                     | 27        | 9.38%   |
| Lenovo                  | 24        | 8.33%   |
| Chimei Innolux          | 23        | 7.99%   |
| LG Display              | 22        | 7.64%   |
| Goldstar                | 17        | 5.9%    |
| Hewlett-Packard         | 14        | 4.86%   |
| Sharp                   | 8         | 2.78%   |
| Acer                    | 6         | 2.08%   |
| InfoVision              | 5         | 1.74%   |
| Philips                 | 4         | 1.39%   |
| Eizo                    | 4         | 1.39%   |
| BenQ                    | 4         | 1.39%   |
| Ancor Communications    | 3         | 1.04%   |
| ViewSonic               | 2         | 0.69%   |
| PANDA                   | 2         | 0.69%   |
| LGD                     | 2         | 0.69%   |
| Lenovo Group Limited    | 2         | 0.69%   |
| Iiyama                  | 2         | 0.69%   |
| Gigabyte Technology     | 2         | 0.69%   |
| BOE Technology Group    | 2         | 0.69%   |
| AOC                     | 2         | 0.69%   |
| Unknown                 | 1         | 0.35%   |
| Sun                     | 1         | 0.35%   |
| STD                     | 1         | 0.35%   |
| Sceptre Tech            | 1         | 0.35%   |
| Planar                  | 1         | 0.35%   |
| OUT                     | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| ITE                     | 1         | 0.35%   |
| Insignia                | 1         | 0.35%   |
| Haier                   | 1         | 0.35%   |
| EVE                     | 1         | 0.35%   |
| CSO                     | 1         | 0.35%   |
| Chi Mei Optoelectronics | 1         | 0.35%   |
| ASUSTek Computer        | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 2.25%   |
| Dell IDRAC DEL0001 1280x1024                                      | 6         | 1.93%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch          | 5         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 5         | 1.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 5         | 1.61%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch      | 4         | 1.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 4         | 1.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3         | 0.96%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch      | 3         | 0.96%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch            | 3         | 0.96%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch          | 3         | 0.96%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 3         | 0.96%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 0.96%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch             | 3         | 0.96%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch             | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch    | 3         | 0.96%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 2         | 0.64%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch           | 2         | 0.64%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch           | 2         | 0.64%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.64%   |
| LGD LCD Monitor 1920x1080                                         | 2         | 0.64%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch       | 2         | 0.64%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch              | 2         | 0.64%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch          | 2         | 0.64%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch        | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch          | 2         | 0.64%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch              | 2         | 0.64%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch        | 2         | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch  | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch   | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch    | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch     | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 2         | 0.64%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch     | 1         | 0.32%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch     | 1         | 0.32%   |
| Unknown LCD Monitor SAMSUNG                                       | 1         | 0.32%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                 | 1         | 0.32%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                     | 1         | 0.32%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch           | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 137       | 52.9%   |
| 1366x768 (WXGA)    | 21        | 8.11%   |
| 3840x2160 (4K)     | 20        | 7.72%   |
| 2560x1440 (QHD)    | 17        | 6.56%   |
| 1600x900 (HD+)     | 12        | 4.63%   |
| 1920x1200 (WUXGA)  | 8         | 3.09%   |
| 1280x1024 (SXGA)   | 7         | 2.7%    |
| 2560x1080          | 6         | 2.32%   |
| Unknown            | 6         | 2.32%   |
| 3440x1440          | 5         | 1.93%   |
| 3840x1080          | 4         | 1.54%   |
| 1680x1050 (WSXGA+) | 3         | 1.16%   |
| 1440x900 (WXGA+)   | 2         | 0.77%   |
| 9600x2160          | 1         | 0.39%   |
| 7680x2160          | 1         | 0.39%   |
| 7280x2160          | 1         | 0.39%   |
| 6400x2160          | 1         | 0.39%   |
| 3840x1600          | 1         | 0.39%   |
| 3840x1200          | 1         | 0.39%   |
| 2160x1350          | 1         | 0.39%   |
| 2048x1152          | 1         | 0.39%   |
| 1280x800 (WXGA)    | 1         | 0.39%   |
| 1280x768           | 1         | 0.39%   |
| 1280x720 (HD)      | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 50        | 17.36%  |
| 14      | 40        | 13.89%  |
| 13      | 31        | 10.76%  |
| 24      | 28        | 9.72%   |
| 27      | 27        | 9.38%   |
| 23      | 21        | 7.29%   |
| Unknown | 21        | 7.29%   |
| 21      | 14        | 4.86%   |
| 34      | 8         | 2.78%   |
| 31      | 7         | 2.43%   |
| 17      | 6         | 2.08%   |
| 20      | 5         | 1.74%   |
| 12      | 5         | 1.74%   |
| 54      | 3         | 1.04%   |
| 32      | 3         | 1.04%   |
| 47      | 2         | 0.69%   |
| 22      | 2         | 0.69%   |
| 19      | 2         | 0.69%   |
| 18      | 2         | 0.69%   |
| 72      | 1         | 0.35%   |
| 64      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 49      | 1         | 0.35%   |
| 40      | 1         | 0.35%   |
| 39      | 1         | 0.35%   |
| 37      | 1         | 0.35%   |
| 28      | 1         | 0.35%   |
| 25      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 11      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 40%     |
| 501-600     | 65        | 23.21%  |
| 401-500     | 23        | 8.21%   |
| Unknown     | 21        | 7.5%    |
| 201-300     | 16        | 5.71%   |
| 601-700     | 13        | 4.64%   |
| 701-800     | 11        | 3.93%   |
| 1001-1500   | 8         | 2.86%   |
| 351-400     | 7         | 2.5%    |
| 801-900     | 3         | 1.07%   |
| 1501-2000   | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 77.87%  |
| 16/10   | 19        | 8.09%   |
| Unknown | 13        | 5.53%   |
| 21/9    | 10        | 4.26%   |
| 5/4     | 7         | 2.98%   |
| 4/3     | 1         | 0.43%   |
| 32/9    | 1         | 0.43%   |
| 3/2     | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 61        | 21.48%  |
| 201-250        | 50        | 17.61%  |
| 101-110        | 50        | 17.61%  |
| 301-350        | 27        | 9.51%   |
| Unknown        | 21        | 7.39%   |
| 351-500        | 17        | 5.99%   |
| 251-300        | 13        | 4.58%   |
| 71-80          | 10        | 3.52%   |
| 151-200        | 9         | 3.17%   |
| More than 1000 | 6         | 2.11%   |
| 121-130        | 6         | 2.11%   |
| 501-1000       | 6         | 2.11%   |
| 61-70          | 5         | 1.76%   |
| 51-60          | 1         | 0.35%   |
| 141-150        | 1         | 0.35%   |
| 131-140        | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 103       | 37.32%  |
| 51-100        | 79        | 28.62%  |
| 101-120       | 44        | 15.94%  |
| Unknown       | 21        | 7.61%   |
| 161-240       | 17        | 6.16%   |
| More than 240 | 6         | 2.17%   |
| 1-50          | 6         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 62.6%   |
| 2     | 55        | 20.99%  |
| 0     | 28        | 10.69%  |
| 3     | 14        | 5.34%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 194       | 52.01%  |
| Realtek Semiconductor             | 78        | 20.91%  |
| Broadcom                          | 19        | 5.09%   |
| Lenovo                            | 18        | 4.83%   |
| Qualcomm Atheros                  | 16        | 4.29%   |
| Dell                              | 5         | 1.34%   |
| Broadcom Limited                  | 5         | 1.34%   |
| ASIX Electronics                  | 4         | 1.07%   |
| Sierra Wireless                   | 3         | 0.8%    |
| MediaTek                          | 3         | 0.8%    |
| Ralink Technology                 | 2         | 0.54%   |
| Ralink                            | 2         | 0.54%   |
| Marvell Technology Group          | 2         | 0.54%   |
| Huawei Technologies               | 2         | 0.54%   |
| Ericsson Business Mobile Networks | 2         | 0.54%   |
| Xiaomi                            | 1         | 0.27%   |
| Tehuti Networks                   | 1         | 0.27%   |
| Samsung Electronics               | 1         | 0.27%   |
| Qualcomm Atheros Communications   | 1         | 0.27%   |
| QLogic                            | 1         | 0.27%   |
| Prolific Technology               | 1         | 0.27%   |
| Microchip Technology              | 1         | 0.27%   |
| Micro Star International          | 1         | 0.27%   |
| Mellanox Technologies             | 1         | 0.27%   |
| Luminary Micro                    | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| IBM                               | 1         | 0.27%   |
| Emulex                            | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| ASUSTek Computer                  | 1         | 0.27%   |
| Arduino SA                        | 1         | 0.27%   |
| Aquantia                          | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 9.56%   |
| Intel Wireless 8265 / 8275                                        | 18        | 3.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 2.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 2.39%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 2.19%   |
| Intel Wireless 8260                                               | 10        | 1.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.99%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 1.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 1.79%   |
| Intel I350 Gigabit Network Connection                             | 9         | 1.79%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 8         | 1.59%   |
| Intel Ethernet Connection (10) I219-LM                            | 8         | 1.59%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 1.39%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 7         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 6         | 1.2%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 6         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 1%      |
| Intel Ethernet Connection I217-LM                                 | 5         | 1%      |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1%      |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 5         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.8%    |
| Intel Wireless-AC 9260                                            | 4         | 0.8%    |
| Intel Wireless 7265                                               | 4         | 0.8%    |
| Intel I210 Gigabit Network Connection                             | 4         | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 4         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.6%    |
| Lenovo USB-C to LAN                                               | 3         | 0.6%    |
| Lenovo ThinkPad Lan                                               | 3         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 139       | 72.77%  |
| Realtek Semiconductor             | 17        | 8.9%    |
| Qualcomm Atheros                  | 13        | 6.81%   |
| Broadcom                          | 5         | 2.62%   |
| Sierra Wireless                   | 3         | 1.57%   |
| Ralink Technology                 | 2         | 1.05%   |
| Ralink                            | 2         | 1.05%   |
| MediaTek                          | 2         | 1.05%   |
| Dell                              | 2         | 1.05%   |
| Qualcomm Atheros Communications   | 1         | 0.52%   |
| Micro Star International          | 1         | 0.52%   |
| Ericsson Business Mobile Networks | 1         | 0.52%   |
| D-Link                            | 1         | 0.52%   |
| Broadcom Limited                  | 1         | 0.52%   |
| ASUSTek Computer                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                   | 18        | 9.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                            | 17        | 8.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                     | 16        | 8.38%   |
| Intel Comet Lake PCH CNVi WiFi                               | 12        | 6.28%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 12        | 6.28%   |
| Intel Wi-Fi 6 AX200                                          | 11        | 5.76%   |
| Intel Wireless 8260                                          | 10        | 5.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                 | 6         | 3.14%   |
| Intel Wi-Fi 6 AX201                                          | 5         | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 4         | 2.09%   |
| Intel Wireless-AC 9260                                       | 4         | 2.09%   |
| Intel Wireless 7265                                          | 4         | 2.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 4         | 2.09%   |
| Intel Centrino Ultimate-N 6300                               | 4         | 2.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                       | 3         | 1.57%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter           | 3         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter              | 2         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 2         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 2         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 2         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 2         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 2         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter   | 2         | 1.05%   |
| Intel Wireless 7260                                          | 2         | 1.05%   |
| Intel Wireless 3165                                          | 2         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                             | 2         | 1.05%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                         | 2         | 1.05%   |
| Sierra Wireless EM7565 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.52%   |
| Sierra Wireless EM7455                                       | 1         | 0.52%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem              | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter     | 1         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 1         | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 1         | 0.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter              | 1         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 1         | 0.52%   |
| Realtek 802.11n WLAN Adapter                                 | 1         | 0.52%   |
| Ralink RT5572 Wireless Adapter                               | 1         | 0.52%   |
| Ralink RT5372 Wireless Adapter                               | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                    | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 146       | 52.71%  |
| Realtek Semiconductor    | 70        | 25.27%  |
| Lenovo                   | 18        | 6.5%    |
| Broadcom                 | 14        | 5.05%   |
| Qualcomm Atheros         | 4         | 1.44%   |
| Broadcom Limited         | 4         | 1.44%   |
| ASIX Electronics         | 4         | 1.44%   |
| Dell                     | 3         | 1.08%   |
| Marvell Technology Group | 2         | 0.72%   |
| Xiaomi                   | 1         | 0.36%   |
| Tehuti Networks          | 1         | 0.36%   |
| Samsung Electronics      | 1         | 0.36%   |
| QLogic                   | 1         | 0.36%   |
| Mellanox Technologies    | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| ICS Advent               | 1         | 0.36%   |
| IBM                      | 1         | 0.36%   |
| Huawei Technologies      | 1         | 0.36%   |
| Emulex                   | 1         | 0.36%   |
| DisplayLink              | 1         | 0.36%   |
| Aquantia                 | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 48        | 15.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 5.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 3.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 3.61%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 3.28%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 2.95%   |
| Intel I350 Gigabit Network Connection                                          | 9         | 2.95%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 2.62%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 2.62%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.3%    |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 2.3%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.3%    |
| Intel 82574L Gigabit Network Connection                                        | 6         | 1.97%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.97%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.64%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.64%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.31%   |
| Intel Ethernet Controller I225-V                                               | 4         | 1.31%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.31%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.98%   |
| Lenovo USB-C to LAN                                                            | 3         | 0.98%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.98%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.98%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.98%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.66%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.66%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.66%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.66%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.66%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.66%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 228       | 54.81%  |
| WiFi     | 182       | 43.75%  |
| Modem    | 6         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 142       | 53.38%  |
| WiFi     | 124       | 46.62%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 146       | 58.17%  |
| 1     | 67        | 26.69%  |
| 3     | 13        | 5.18%   |
| 4     | 12        | 4.78%   |
| 6     | 7         | 2.79%   |
| 132   | 1         | 0.4%    |
| 22    | 1         | 0.4%    |
| 12    | 1         | 0.4%    |
| 8     | 1         | 0.4%    |
| 5     | 1         | 0.4%    |
| 0     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 226       | 89.68%  |
| Yes  | 26        | 10.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 72.37%  |
| Cambridge Silicon Radio         | 9         | 5.92%   |
| Broadcom                        | 8         | 5.26%   |
| Realtek Semiconductor           | 6         | 3.95%   |
| Qualcomm Atheros Communications | 5         | 3.29%   |
| IMC Networks                    | 4         | 2.63%   |
| ASUSTek Computer                | 3         | 1.97%   |
| Foxconn / Hon Hai               | 2         | 1.32%   |
| Ralink                          | 1         | 0.66%   |
| Micro Star International        | 1         | 0.66%   |
| MediaTek                        | 1         | 0.66%   |
| Integrated System Solution      | 1         | 0.66%   |
| Dell                            | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 36        | 23.68%  |
| Intel Bluetooth wireless interface                                                  | 29        | 19.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 25        | 16.45%  |
| Intel AX200 Bluetooth                                                               | 10        | 6.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 5.92%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.63%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.97%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.32%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.32%   |
| ASUS BCM20702A0                                                                     | 2         | 1.32%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.66%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.66%   |
| MediaTek Wireless_Device                                                            | 1         | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.66%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.66%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.66%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.66%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.66%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.66%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.66%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 195       | 54.02%  |
| Nvidia                                       | 66        | 18.28%  |
| AMD                                          | 30        | 8.31%   |
| Lenovo                                       | 16        | 4.43%   |
| Plantronics                                  | 6         | 1.66%   |
| Texas Instruments                            | 5         | 1.39%   |
| Realtek Semiconductor                        | 5         | 1.39%   |
| JMTek                                        | 4         | 1.11%   |
| GN Netcom                                    | 4         | 1.11%   |
| Creative Labs                                | 4         | 1.11%   |
| Logitech                                     | 3         | 0.83%   |
| Generalplus Technology                       | 3         | 0.83%   |
| Creative Technology                          | 3         | 0.83%   |
| C-Media Electronics                          | 2         | 0.55%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.28%   |
| Tenx Technology                              | 1         | 0.28%   |
| Sony                                         | 1         | 0.28%   |
| Sennheiser Communications                    | 1         | 0.28%   |
| RODE Microphones                             | 1         | 0.28%   |
| LG Electronics                               | 1         | 0.28%   |
| Google                                       | 1         | 0.28%   |
| Giga-Byte Technology                         | 1         | 0.28%   |
| Focusrite-Novation                           | 1         | 0.28%   |
| Dynex                                        | 1         | 0.28%   |
| DSEA A/S                                     | 1         | 0.28%   |
| Dell                                         | 1         | 0.28%   |
| Corsair                                      | 1         | 0.28%   |
| Blue Microphones                             | 1         | 0.28%   |
| ASUSTek Computer                             | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 27        | 6.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 5.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 4.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 4.35%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 3.32%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 3.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.3%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 8         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 1.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.53%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6         | 1.53%   |
| Realtek Semiconductor USB Audio                                            | 5         | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4         | 1.02%   |
| Plantronics BT600                                                          | 4         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.02%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.02%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.02%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.77%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.77%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 29.77%  |
| SK hynix            | 36        | 27.48%  |
| Micron Technology   | 13        | 9.92%   |
| Crucial             | 11        | 8.4%    |
| Kingston            | 9         | 6.87%   |
| Unknown             | 5         | 3.82%   |
| Corsair             | 4         | 3.05%   |
| Smart               | 2         | 1.53%   |
| Hewlett-Packard     | 2         | 1.53%   |
| GOODRAM             | 2         | 1.53%   |
| Elpida              | 2         | 1.53%   |
| Unknown (0x0B5E)    | 1         | 0.76%   |
| Unknown (0x0205)    | 1         | 0.76%   |
| Transcend           | 1         | 0.76%   |
| Patriot             | 1         | 0.76%   |
| Innodisk            | 1         | 0.76%   |
| Unknown             | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 4         | 2.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 2.14%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s         | 3         | 2.14%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s           | 3         | 2.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 2.14%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                    | 2         | 1.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 1.43%   |
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s        | 2         | 1.43%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 1.43%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 1.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 1.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 1.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s            | 2         | 1.43%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s            | 2         | 1.43%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s            | 2         | 1.43%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s            | 2         | 1.43%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s            | 2         | 1.43%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 1.43%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 0.71%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1         | 0.71%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 0.71%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 0.71%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 0.71%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 0.71%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 0.71%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.71%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 0.71%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 0.71%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 0.71%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s           | 1         | 0.71%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 0.71%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 70        | 62.5%   |
| DDR3    | 29        | 25.89%  |
| SDRAM   | 3         | 2.68%   |
| LPDDR4  | 3         | 2.68%   |
| LPDDR3  | 2         | 1.79%   |
| DRAM    | 2         | 1.79%   |
| LPDDR5  | 1         | 0.89%   |
| DDR2    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 56        | 50.45%  |
| SODIMM       | 48        | 43.24%  |
| Row Of Chips | 3         | 2.7%    |
| RIMM         | 2         | 1.8%    |
| Chip         | 2         | 1.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 37.29%  |
| 16384 | 34        | 28.81%  |
| 4096  | 23        | 19.49%  |
| 32768 | 11        | 9.32%   |
| 2048  | 3         | 2.54%   |
| 65536 | 2         | 1.69%   |
| 1024  | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 17.5%   |
| 2400    | 19        | 15.83%  |
| 3200    | 18        | 15%     |
| 2667    | 17        | 14.17%  |
| 2133    | 13        | 10.83%  |
| 1333    | 8         | 6.67%   |
| 2666    | 5         | 4.17%   |
| 3600    | 3         | 2.5%    |
| 3266    | 3         | 2.5%    |
| 2933    | 3         | 2.5%    |
| 1867    | 2         | 1.67%   |
| 6400    | 1         | 0.83%   |
| 2472    | 1         | 0.83%   |
| 2048    | 1         | 0.83%   |
| 1866    | 1         | 0.83%   |
| 1334    | 1         | 0.83%   |
| 1066    | 1         | 0.83%   |
| 800     | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

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
| Chicony Electronics                    | 47        | 28.48%  |
| IMC Networks                           | 25        | 15.15%  |
| Acer                                   | 17        | 10.3%   |
| Realtek Semiconductor                  | 11        | 6.67%   |
| Microdia                               | 10        | 6.06%   |
| Logitech                               | 10        | 6.06%   |
| Sunplus Innovation Technology          | 8         | 4.85%   |
| Unknown                                | 5         | 3.03%   |
| Suyin                                  | 4         | 2.42%   |
| Samsung Electronics                    | 3         | 1.82%   |
| Microsoft                              | 3         | 1.82%   |
| Lite-On Technology                     | 3         | 1.82%   |
| Generalplus Technology                 | 3         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.82%   |
| Syntek                                 | 2         | 1.21%   |
| Ruision                                | 2         | 1.21%   |
| Quanta                                 | 2         | 1.21%   |
| Remo Tech                              | 1         | 0.61%   |
| Luxvisions Innotech Limited            | 1         | 0.61%   |
| LG Electronics                         | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| KYE Systems (Mouse Systems)            | 1         | 0.61%   |
| Jieli Technology                       | 1         | 0.61%   |
| ARC International                      | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 24        | 14.29%  |
| IMC Networks Integrated Camera          | 20        | 11.9%   |
| Realtek Integrated_Webcam_HD            | 9         | 5.36%   |
| Acer Integrated Camera                  | 8         | 4.76%   |
| Sunplus Integrated_Webcam_HD            | 5         | 2.98%   |
| Chicony Integrated Camera (1280x720@30) | 5         | 2.98%   |
| Acer SunplusIT Integrated Camera        | 5         | 2.98%   |
| Unknown FULL HD 1080P Webcam            | 4         | 2.38%   |
| Microdia Integrated_Webcam_HD           | 4         | 2.38%   |
| Logitech HD Pro Webcam C920             | 4         | 2.38%   |
| Chicony HP HD Camera                    | 4         | 2.38%   |
| Samsung Galaxy A5 (MTP)                 | 3         | 1.79%   |
| Lite-On Integrated Camera               | 3         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3         | 1.79%   |
| Chicony ThinkPad T490 Webcam            | 3         | 1.79%   |
| Suyin Integrated_Webcam_HD              | 2         | 1.19%   |
| Ruision UVC Camera                      | 2         | 1.19%   |
| Microdia Webcam                         | 2         | 1.19%   |
| Microdia Integrated Webcam              | 2         | 1.19%   |
| Generalplus GENERAL WEBCAM              | 2         | 1.19%   |
| Chicony Integrated Camera [ThinkPad]    | 2         | 1.19%   |
| Acer Integrated IR Camera               | 2         | 1.19%   |
| Unknown 720p HD Camera                  | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                | 1         | 0.6%    |
| Syntek Integrated Camera                | 1         | 0.6%    |
| Suyin RGBIR Camera                      | 1         | 0.6%    |
| Suyin HP Truevision HD                  | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_FHD    | 1         | 0.6%    |
| Sunplus Integrated Webcam               | 1         | 0.6%    |
| Sunplus HP HD Webcam [Fixed]            | 1         | 0.6%    |
| Remo Tech OBSBOT Tiny 4K                | 1         | 0.6%    |
| Realtek USB2.0 VGA UVC WebCam           | 1         | 0.6%    |
| Realtek NexiGo N960E FHD Webcam         | 1         | 0.6%    |
| Quanta HP TrueVision HD Camera          | 1         | 0.6%    |
| Quanta HP HD Camera                     | 1         | 0.6%    |
| Microsoft LifeCam VX-2000               | 1         | 0.6%    |
| Microsoft LifeCam HD-3000               | 1         | 0.6%    |
| Microsoft LifeCam Cinema                | 1         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD    | 1         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_E4HD  | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 36        | 58.06%  |
| Validity Sensors           | 17        | 27.42%  |
| Shenzhen Goodix Technology | 5         | 8.06%   |
| Upek                       | 2         | 3.23%   |
| Samsung Electronics        | 1         | 1.61%   |
| Elan Microelectronics      | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 41.94%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 11.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 6.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.84%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.84%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.61%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.61%   |
| Validity Sensors VFS491                                                    | 1         | 1.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.61%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.61%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.61%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.61%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.61%   |

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
| 0     | 124       | 48.63%  |
| 1     | 89        | 34.9%   |
| 2     | 26        | 10.2%   |
| 3     | 11        | 4.31%   |
| 5     | 3         | 1.18%   |
| 4     | 2         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 33.33%  |
| Graphics card            | 33        | 17.74%  |
| Unassigned class         | 24        | 12.9%   |
| Communication controller | 20        | 10.75%  |
| Chipcard                 | 11        | 5.91%   |
| Net/wireless             | 9         | 4.84%   |
| Multimedia controller    | 6         | 3.23%   |
| Card reader              | 6         | 3.23%   |
| Net/ethernet             | 3         | 1.61%   |
| Bluetooth                | 3         | 1.61%   |
| Storage/ide              | 2         | 1.08%   |
| Storage                  | 2         | 1.08%   |
| Camera                   | 2         | 1.08%   |
| Storage/raid             | 1         | 0.54%   |
| Sound                    | 1         | 0.54%   |
| Network                  | 1         | 0.54%   |

