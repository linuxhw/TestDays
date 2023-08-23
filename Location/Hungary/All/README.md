Linux in Hungary - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hungary/Desktop/README.md) and [notebooks](/Location/Hungary/Notebook/README.md).

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

Total: 8034

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E1-532               | Notebook    | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | 1495                        | Desktop     | [837afb7bfa](https://linux-hardware.org/?probe=837afb7bfa) | Aug 12, 2023 |
| ASUSTek       | K55A                        | Notebook    | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| HP            | 1495                        | Desktop     | [9e8b73f16e](https://linux-hardware.org/?probe=9e8b73f16e) | Aug 11, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [3c7140c389](https://linux-hardware.org/?probe=3c7140c389) | Aug 11, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [17e503622d](https://linux-hardware.org/?probe=17e503622d) | Aug 11, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [485a8bf15d](https://linux-hardware.org/?probe=485a8bf15d) | Aug 10, 2023 |
| HP            | 1495                        | Desktop     | [6c458bf059](https://linux-hardware.org/?probe=6c458bf059) | Aug 10, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [ae87c6938f](https://linux-hardware.org/?probe=ae87c6938f) | Aug 10, 2023 |
| HP            | 0AA4h                       | Desktop     | [e4da6a6aaf](https://linux-hardware.org/?probe=e4da6a6aaf) | Aug 09, 2023 |
| HP            | Notebook                    | Notebook    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [4081f7bbda](https://linux-hardware.org/?probe=4081f7bbda) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [6601d0d136](https://linux-hardware.org/?probe=6601d0d136) | Aug 07, 2023 |
| HP            | Notebook                    | Notebook    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [64dc45c007](https://linux-hardware.org/?probe=64dc45c007) | Aug 07, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [b62c8c40f5](https://linux-hardware.org/?probe=b62c8c40f5) | Aug 07, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f3644b56ad](https://linux-hardware.org/?probe=f3644b56ad) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9aaaaec131](https://linux-hardware.org/?probe=9aaaaec131) | Aug 05, 2023 |
| HP            | 1588h                       | Desktop     | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [96b8677500](https://linux-hardware.org/?probe=96b8677500) | Aug 05, 2023 |
| HP            | 1495                        | Desktop     | [17ae98cda8](https://linux-hardware.org/?probe=17ae98cda8) | Aug 05, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4f67a219dc](https://linux-hardware.org/?probe=4f67a219dc) | Aug 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [91b8e07f0d](https://linux-hardware.org/?probe=91b8e07f0d) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |
| HP            | 1495                        | Desktop     | [75dae4c3a6](https://linux-hardware.org/?probe=75dae4c3a6) | Aug 04, 2023 |
| MSI           | P43i                        | Desktop     | [683b26e344](https://linux-hardware.org/?probe=683b26e344) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [4c45ace98b](https://linux-hardware.org/?probe=4c45ace98b) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [b7ffeb681e](https://linux-hardware.org/?probe=b7ffeb681e) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [b8ece2fce1](https://linux-hardware.org/?probe=b8ece2fce1) | Aug 03, 2023 |
| Medion        | MS-7748                     | Desktop     | [413b9e74a6](https://linux-hardware.org/?probe=413b9e74a6) | Aug 03, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e47b01848a](https://linux-hardware.org/?probe=e47b01848a) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [99cae22846](https://linux-hardware.org/?probe=99cae22846) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [b73fa31837](https://linux-hardware.org/?probe=b73fa31837) | Aug 02, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [56573f8499](https://linux-hardware.org/?probe=56573f8499) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [6202f3b97e](https://linux-hardware.org/?probe=6202f3b97e) | Jul 31, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [9ce45f234a](https://linux-hardware.org/?probe=9ce45f234a) | Jul 31, 2023 |
| HP            | Notebook                    | Notebook    | [329c725795](https://linux-hardware.org/?probe=329c725795) | Jul 31, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [908f49c376](https://linux-hardware.org/?probe=908f49c376) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [250fc62328](https://linux-hardware.org/?probe=250fc62328) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [c3b01ce24d](https://linux-hardware.org/?probe=c3b01ce24d) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [8e26feba38](https://linux-hardware.org/?probe=8e26feba38) | Jul 30, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [7bcd0d7683](https://linux-hardware.org/?probe=7bcd0d7683) | Jul 30, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [6fd92e6150](https://linux-hardware.org/?probe=6fd92e6150) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [3c326304ab](https://linux-hardware.org/?probe=3c326304ab) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [4e19477a40](https://linux-hardware.org/?probe=4e19477a40) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [404f75d04c](https://linux-hardware.org/?probe=404f75d04c) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [19d341d49d](https://linux-hardware.org/?probe=19d341d49d) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [a7c322fa40](https://linux-hardware.org/?probe=a7c322fa40) | Jul 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [385c97c1d3](https://linux-hardware.org/?probe=385c97c1d3) | Jul 28, 2023 |
| HP            | 1495                        | Desktop     | [b4e2031d1e](https://linux-hardware.org/?probe=b4e2031d1e) | Jul 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ea550fb04c](https://linux-hardware.org/?probe=ea550fb04c) | Jul 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5b17937c10](https://linux-hardware.org/?probe=5b17937c10) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [ebaacb8057](https://linux-hardware.org/?probe=ebaacb8057) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [3988b909c7](https://linux-hardware.org/?probe=3988b909c7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [de48c51732](https://linux-hardware.org/?probe=de48c51732) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [f2bef973eb](https://linux-hardware.org/?probe=f2bef973eb) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [04a75d9e0c](https://linux-hardware.org/?probe=04a75d9e0c) | Jul 26, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | Notebook    | [180a80b4fe](https://linux-hardware.org/?probe=180a80b4fe) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [58d8bbebcd](https://linux-hardware.org/?probe=58d8bbebcd) | Jul 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [1711396786](https://linux-hardware.org/?probe=1711396786) | Jul 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [e367e06cac](https://linux-hardware.org/?probe=e367e06cac) | Jul 25, 2023 |
| HP            | 8265                        | Desktop     | [96a99f0e8f](https://linux-hardware.org/?probe=96a99f0e8f) | Jul 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [42ee46f6c4](https://linux-hardware.org/?probe=42ee46f6c4) | Jul 25, 2023 |
| ASUSTek       | UN45                        | Desktop     | [ea2bebc887](https://linux-hardware.org/?probe=ea2bebc887) | Jul 25, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [aef65d0501](https://linux-hardware.org/?probe=aef65d0501) | Jul 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4c5c8def02](https://linux-hardware.org/?probe=4c5c8def02) | Jul 24, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [828f20c8bb](https://linux-hardware.org/?probe=828f20c8bb) | Jul 24, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [516f42eb27](https://linux-hardware.org/?probe=516f42eb27) | Jul 23, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [57cdc7820f](https://linux-hardware.org/?probe=57cdc7820f) | Jul 23, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [91d19df4b4](https://linux-hardware.org/?probe=91d19df4b4) | Jul 23, 2023 |
| HP            | 8265                        | Desktop     | [0e5a193692](https://linux-hardware.org/?probe=0e5a193692) | Jul 23, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [441c83b694](https://linux-hardware.org/?probe=441c83b694) | Jul 23, 2023 |
| HP            | 1495                        | Desktop     | [a9bd3f59e8](https://linux-hardware.org/?probe=a9bd3f59e8) | Jul 23, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [11a6a3a607](https://linux-hardware.org/?probe=11a6a3a607) | Jul 23, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [8f2c838141](https://linux-hardware.org/?probe=8f2c838141) | Jul 22, 2023 |
| Dell          | 0PU052                      | Desktop     | [43454a5114](https://linux-hardware.org/?probe=43454a5114) | Jul 22, 2023 |
| Dell          | 0PU052                      | Desktop     | [b1ba2d4239](https://linux-hardware.org/?probe=b1ba2d4239) | Jul 22, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c4da72acde](https://linux-hardware.org/?probe=c4da72acde) | Jul 21, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [2d8ae98d9c](https://linux-hardware.org/?probe=2d8ae98d9c) | Jul 21, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [e022b7bd64](https://linux-hardware.org/?probe=e022b7bd64) | Jul 21, 2023 |
| Dell          | Latitude E6420              | Notebook    | [35d8d85f3c](https://linux-hardware.org/?probe=35d8d85f3c) | Jul 21, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [1faafe201d](https://linux-hardware.org/?probe=1faafe201d) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [08b6a97698](https://linux-hardware.org/?probe=08b6a97698) | Jul 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [4b0ce11ac5](https://linux-hardware.org/?probe=4b0ce11ac5) | Jul 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [4f7745f5de](https://linux-hardware.org/?probe=4f7745f5de) | Jul 18, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [fc1e32f937](https://linux-hardware.org/?probe=fc1e32f937) | Jul 17, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [8b9534387b](https://linux-hardware.org/?probe=8b9534387b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | Desktop     | [6d2ee4521b](https://linux-hardware.org/?probe=6d2ee4521b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | Desktop     | [a8bbbd8c49](https://linux-hardware.org/?probe=a8bbbd8c49) | Jul 17, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [b6925518be](https://linux-hardware.org/?probe=b6925518be) | Jul 16, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [05a330fa6c](https://linux-hardware.org/?probe=05a330fa6c) | Jul 16, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [60947b35a4](https://linux-hardware.org/?probe=60947b35a4) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [856a25b9d5](https://linux-hardware.org/?probe=856a25b9d5) | Jul 16, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [1ccdf38dfa](https://linux-hardware.org/?probe=1ccdf38dfa) | Jul 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [71045dea53](https://linux-hardware.org/?probe=71045dea53) | Jul 16, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [f04f199334](https://linux-hardware.org/?probe=f04f199334) | Jul 16, 2023 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [b4325e403a](https://linux-hardware.org/?probe=b4325e403a) | Jul 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | Notebook    | [8cc38e55a2](https://linux-hardware.org/?probe=8cc38e55a2) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | Notebook    | [c0101c7ae1](https://linux-hardware.org/?probe=c0101c7ae1) | Jul 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [b5588d7209](https://linux-hardware.org/?probe=b5588d7209) | Jul 15, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [a562b6518f](https://linux-hardware.org/?probe=a562b6518f) | Jul 15, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [655cb31a8a](https://linux-hardware.org/?probe=655cb31a8a) | Jul 14, 2023 |
| DFI           | WL051                       | Desktop     | [bfe00b9eeb](https://linux-hardware.org/?probe=bfe00b9eeb) | Jul 14, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [ba12b5ff3e](https://linux-hardware.org/?probe=ba12b5ff3e) | Jul 14, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0d773629f2](https://linux-hardware.org/?probe=0d773629f2) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [e695d46a05](https://linux-hardware.org/?probe=e695d46a05) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [93a455ac9b](https://linux-hardware.org/?probe=93a455ac9b) | Jul 14, 2023 |
| MSI           | B150M ECO                   | Desktop     | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [2b75a3a2b7](https://linux-hardware.org/?probe=2b75a3a2b7) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | Notebook    | [34e242c377](https://linux-hardware.org/?probe=34e242c377) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | Notebook    | [bc67d71f5f](https://linux-hardware.org/?probe=bc67d71f5f) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [5d1ed4c0a4](https://linux-hardware.org/?probe=5d1ed4c0a4) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [2f3da717f3](https://linux-hardware.org/?probe=2f3da717f3) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bfe4c07a40](https://linux-hardware.org/?probe=bfe4c07a40) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [c23f2219b4](https://linux-hardware.org/?probe=c23f2219b4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [e169b67c63](https://linux-hardware.org/?probe=e169b67c63) | Jul 12, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1c7a630efb](https://linux-hardware.org/?probe=1c7a630efb) | Jul 12, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [8528943b9e](https://linux-hardware.org/?probe=8528943b9e) | Jul 11, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [1f9c336539](https://linux-hardware.org/?probe=1f9c336539) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 4730s               | Notebook    | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| eMachines     | E725                        | Notebook    | [69e7b54469](https://linux-hardware.org/?probe=69e7b54469) | Jul 10, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [08ae4ea22e](https://linux-hardware.org/?probe=08ae4ea22e) | Jul 09, 2023 |
| eMachines     | E725                        | Notebook    | [307f75ef0a](https://linux-hardware.org/?probe=307f75ef0a) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [fe0bc25044](https://linux-hardware.org/?probe=fe0bc25044) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [70e2ac254a](https://linux-hardware.org/?probe=70e2ac254a) | Jul 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [657750190f](https://linux-hardware.org/?probe=657750190f) | Jul 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [69c5198a22](https://linux-hardware.org/?probe=69c5198a22) | Jul 08, 2023 |
| eMachines     | E725                        | Notebook    | [c70b217933](https://linux-hardware.org/?probe=c70b217933) | Jul 08, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [81dd9a0120](https://linux-hardware.org/?probe=81dd9a0120) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [6965fec932](https://linux-hardware.org/?probe=6965fec932) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [4e6e8dc45b](https://linux-hardware.org/?probe=4e6e8dc45b) | Jul 08, 2023 |
| Dell          | Latitude E6220              | Notebook    | [d853b49fc7](https://linux-hardware.org/?probe=d853b49fc7) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [393ad4fc5d](https://linux-hardware.org/?probe=393ad4fc5d) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [79166ca12f](https://linux-hardware.org/?probe=79166ca12f) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [de3ed49995](https://linux-hardware.org/?probe=de3ed49995) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Sony          | VPCYB3V1E                   | Notebook    | [2dd9b76ce0](https://linux-hardware.org/?probe=2dd9b76ce0) | Jul 06, 2023 |
| Intel         | NUC7i5BNB J31144-314        | Mini pc     | [8e5fbbccbf](https://linux-hardware.org/?probe=8e5fbbccbf) | Jul 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [5a62a75599](https://linux-hardware.org/?probe=5a62a75599) | Jul 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [713b52b0c5](https://linux-hardware.org/?probe=713b52b0c5) | Jul 05, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [d992b0a60f](https://linux-hardware.org/?probe=d992b0a60f) | Jul 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [bd3b079d0d](https://linux-hardware.org/?probe=bd3b079d0d) | Jul 04, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [11537fb0f5](https://linux-hardware.org/?probe=11537fb0f5) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | Notebook    | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [7390114024](https://linux-hardware.org/?probe=7390114024) | Jul 03, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [fe616ea0ed](https://linux-hardware.org/?probe=fe616ea0ed) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [84a32e1b42](https://linux-hardware.org/?probe=84a32e1b42) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [9393d317b6](https://linux-hardware.org/?probe=9393d317b6) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [22879dbc9e](https://linux-hardware.org/?probe=22879dbc9e) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [2a7725896c](https://linux-hardware.org/?probe=2a7725896c) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [496b83b6b8](https://linux-hardware.org/?probe=496b83b6b8) | Jul 03, 2023 |
| eMachines     | E725                        | Notebook    | [ca2b670023](https://linux-hardware.org/?probe=ca2b670023) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [efa8ecd790](https://linux-hardware.org/?probe=efa8ecd790) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [72af61849b](https://linux-hardware.org/?probe=72af61849b) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [eb7ec8410d](https://linux-hardware.org/?probe=eb7ec8410d) | Jul 02, 2023 |
| eMachines     | E725                        | Notebook    | [622425a84f](https://linux-hardware.org/?probe=622425a84f) | Jul 02, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ef1c856eb5](https://linux-hardware.org/?probe=ef1c856eb5) | Jul 02, 2023 |
| AOpen         | D1009 A1A4                  | Desktop     | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [b27b2b3825](https://linux-hardware.org/?probe=b27b2b3825) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [e50079b95e](https://linux-hardware.org/?probe=e50079b95e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [b98b20a82c](https://linux-hardware.org/?probe=b98b20a82c) | Jul 01, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b49269ab3c](https://linux-hardware.org/?probe=b49269ab3c) | Jul 01, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ca1817783e](https://linux-hardware.org/?probe=ca1817783e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [6484578658](https://linux-hardware.org/?probe=6484578658) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| HP            | 650                         | Notebook    | [279f48a7df](https://linux-hardware.org/?probe=279f48a7df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| HP            | Notebook                    | Notebook    | [552c6713e1](https://linux-hardware.org/?probe=552c6713e1) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [908af533fc](https://linux-hardware.org/?probe=908af533fc) | Jun 30, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [298a4bf290](https://linux-hardware.org/?probe=298a4bf290) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [344a5eda20](https://linux-hardware.org/?probe=344a5eda20) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [565c1ea1c2](https://linux-hardware.org/?probe=565c1ea1c2) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [545a2c4e26](https://linux-hardware.org/?probe=545a2c4e26) | Jun 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d3f7bcfb2c](https://linux-hardware.org/?probe=d3f7bcfb2c) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1efefadbdf](https://linux-hardware.org/?probe=1efefadbdf) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e304e9beeb](https://linux-hardware.org/?probe=e304e9beeb) | Jun 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [126187748f](https://linux-hardware.org/?probe=126187748f) | Jun 27, 2023 |
| eMachines     | E725                        | Notebook    | [e1ed487442](https://linux-hardware.org/?probe=e1ed487442) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| eMachines     | E725                        | Notebook    | [909f61c87a](https://linux-hardware.org/?probe=909f61c87a) | Jun 26, 2023 |
| HP            | Notebook                    | Notebook    | [ce52423528](https://linux-hardware.org/?probe=ce52423528) | Jun 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c463ab7b16](https://linux-hardware.org/?probe=c463ab7b16) | Jun 26, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [604d6b2b6f](https://linux-hardware.org/?probe=604d6b2b6f) | Jun 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [bf911964a8](https://linux-hardware.org/?probe=bf911964a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [b26a7fb008](https://linux-hardware.org/?probe=b26a7fb008) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [04f61a169e](https://linux-hardware.org/?probe=04f61a169e) | Jun 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [839490cb5a](https://linux-hardware.org/?probe=839490cb5a) | Jun 25, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [43849169cb](https://linux-hardware.org/?probe=43849169cb) | Jun 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e8f8b7e986](https://linux-hardware.org/?probe=e8f8b7e986) | Jun 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e218b300b7](https://linux-hardware.org/?probe=e218b300b7) | Jun 25, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [2b3a2327fb](https://linux-hardware.org/?probe=2b3a2327fb) | Jun 24, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [75cab0a675](https://linux-hardware.org/?probe=75cab0a675) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [186b2c5cb7](https://linux-hardware.org/?probe=186b2c5cb7) | Jun 24, 2023 |
| HP            | 8265                        | Desktop     | [863a585141](https://linux-hardware.org/?probe=863a585141) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [84239b2594](https://linux-hardware.org/?probe=84239b2594) | Jun 23, 2023 |
| HP            | Notebook                    | Notebook    | [6710ed8c9c](https://linux-hardware.org/?probe=6710ed8c9c) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [a3f0d3cbc6](https://linux-hardware.org/?probe=a3f0d3cbc6) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [8cfeb06220](https://linux-hardware.org/?probe=8cfeb06220) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [1d89edd254](https://linux-hardware.org/?probe=1d89edd254) | Jun 20, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5230b985a8](https://linux-hardware.org/?probe=5230b985a8) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6f14223ae](https://linux-hardware.org/?probe=a6f14223ae) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [076a78c151](https://linux-hardware.org/?probe=076a78c151) | Jun 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dca1fab41](https://linux-hardware.org/?probe=9dca1fab41) | Jun 20, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [d09be5d97c](https://linux-hardware.org/?probe=d09be5d97c) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| eMachines     | E725                        | Notebook    | [4317f04272](https://linux-hardware.org/?probe=4317f04272) | Jun 19, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [320272d785](https://linux-hardware.org/?probe=320272d785) | Jun 19, 2023 |
| Dell          | Latitude E7470              | Notebook    | [645538d81e](https://linux-hardware.org/?probe=645538d81e) | Jun 19, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0423e23a21](https://linux-hardware.org/?probe=0423e23a21) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [8ccea52f65](https://linux-hardware.org/?probe=8ccea52f65) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0cbbe081c8](https://linux-hardware.org/?probe=0cbbe081c8) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41c5ad600b](https://linux-hardware.org/?probe=41c5ad600b) | Jun 19, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [3dacc56dd5](https://linux-hardware.org/?probe=3dacc56dd5) | Jun 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [b90840dbba](https://linux-hardware.org/?probe=b90840dbba) | Jun 18, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [6bd02aa0f2](https://linux-hardware.org/?probe=6bd02aa0f2) | Jun 18, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [e0d2c8f040](https://linux-hardware.org/?probe=e0d2c8f040) | Jun 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bbc5301e6b](https://linux-hardware.org/?probe=bbc5301e6b) | Jun 17, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [77f7dcbc1d](https://linux-hardware.org/?probe=77f7dcbc1d) | Jun 17, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [a96d7f89ca](https://linux-hardware.org/?probe=a96d7f89ca) | Jun 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa9508da6e](https://linux-hardware.org/?probe=fa9508da6e) | Jun 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [a1bb681c50](https://linux-hardware.org/?probe=a1bb681c50) | Jun 17, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [24624ec732](https://linux-hardware.org/?probe=24624ec732) | Jun 17, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [6fd4c94830](https://linux-hardware.org/?probe=6fd4c94830) | Jun 16, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [4f97748920](https://linux-hardware.org/?probe=4f97748920) | Jun 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [11c34f6cde](https://linux-hardware.org/?probe=11c34f6cde) | Jun 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6d154340b0](https://linux-hardware.org/?probe=6d154340b0) | Jun 16, 2023 |
| eMachines     | E725                        | Notebook    | [c2ffc64913](https://linux-hardware.org/?probe=c2ffc64913) | Jun 15, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6adbb0811a](https://linux-hardware.org/?probe=6adbb0811a) | Jun 15, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [bab5e06a26](https://linux-hardware.org/?probe=bab5e06a26) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b560ba8109](https://linux-hardware.org/?probe=b560ba8109) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9111abbf0e](https://linux-hardware.org/?probe=9111abbf0e) | Jun 14, 2023 |
| eMachines     | E725                        | Notebook    | [6a88f4f2be](https://linux-hardware.org/?probe=6a88f4f2be) | Jun 14, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [817c9acfa2](https://linux-hardware.org/?probe=817c9acfa2) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [95a0297b20](https://linux-hardware.org/?probe=95a0297b20) | Jun 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [aad70ac5b5](https://linux-hardware.org/?probe=aad70ac5b5) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [76441700d5](https://linux-hardware.org/?probe=76441700d5) | Jun 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [b718d8d672](https://linux-hardware.org/?probe=b718d8d672) | Jun 14, 2023 |
| MSI           | MS-7309                     | Desktop     | [fc85dd07ed](https://linux-hardware.org/?probe=fc85dd07ed) | Jun 14, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [26493eeedc](https://linux-hardware.org/?probe=26493eeedc) | Jun 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [03f59dc88a](https://linux-hardware.org/?probe=03f59dc88a) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [807fe357c7](https://linux-hardware.org/?probe=807fe357c7) | Jun 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [e68c648de4](https://linux-hardware.org/?probe=e68c648de4) | Jun 13, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [058f5805e3](https://linux-hardware.org/?probe=058f5805e3) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8c939c89a3](https://linux-hardware.org/?probe=8c939c89a3) | Jun 13, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [6385fdf921](https://linux-hardware.org/?probe=6385fdf921) | Jun 13, 2023 |
| Dell          | Latitude E5520              | Notebook    | [a86c677685](https://linux-hardware.org/?probe=a86c677685) | Jun 13, 2023 |
| HP            | 250 G1                      | Notebook    | [f8406758e3](https://linux-hardware.org/?probe=f8406758e3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [9e5b8610e3](https://linux-hardware.org/?probe=9e5b8610e3) | Jun 13, 2023 |
| HP            | 339A                        | Desktop     | [a8e90edbdb](https://linux-hardware.org/?probe=a8e90edbdb) | Jun 13, 2023 |
| HP            | 250 G1                      | Notebook    | [477f9bbabd](https://linux-hardware.org/?probe=477f9bbabd) | Jun 13, 2023 |
| HP            | Notebook                    | Notebook    | [aa5016380c](https://linux-hardware.org/?probe=aa5016380c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [0c2fae415b](https://linux-hardware.org/?probe=0c2fae415b) | Jun 12, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a6333257c7](https://linux-hardware.org/?probe=a6333257c7) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7d188dbdfa](https://linux-hardware.org/?probe=7d188dbdfa) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [75b330369d](https://linux-hardware.org/?probe=75b330369d) | Jun 12, 2023 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [abc5444c45](https://linux-hardware.org/?probe=abc5444c45) | Jun 12, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [6d6fb0c276](https://linux-hardware.org/?probe=6d6fb0c276) | Jun 12, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4b84ec2ade](https://linux-hardware.org/?probe=4b84ec2ade) | Jun 12, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [9e9746b2bc](https://linux-hardware.org/?probe=9e9746b2bc) | Jun 12, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b2e6e1ed18](https://linux-hardware.org/?probe=b2e6e1ed18) | Jun 12, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [5e96ddeeac](https://linux-hardware.org/?probe=5e96ddeeac) | Jun 12, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6279cb0df](https://linux-hardware.org/?probe=e6279cb0df) | Jun 12, 2023 |
| Dell          | Latitude E6230              | Notebook    | [c46f103733](https://linux-hardware.org/?probe=c46f103733) | Jun 11, 2023 |
| Dell          | Latitude E6230              | Notebook    | [390606f3f6](https://linux-hardware.org/?probe=390606f3f6) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [43d52c8efe](https://linux-hardware.org/?probe=43d52c8efe) | Jun 11, 2023 |
| HP            | 250 G1                      | Notebook    | [e229888d41](https://linux-hardware.org/?probe=e229888d41) | Jun 11, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [aee2df0fb7](https://linux-hardware.org/?probe=aee2df0fb7) | Jun 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c1f065966d](https://linux-hardware.org/?probe=c1f065966d) | Jun 11, 2023 |
| HP            | 8265                        | Desktop     | [fb5cbd10fa](https://linux-hardware.org/?probe=fb5cbd10fa) | Jun 11, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [eff8eec9d8](https://linux-hardware.org/?probe=eff8eec9d8) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [6f58cbafdd](https://linux-hardware.org/?probe=6f58cbafdd) | Jun 10, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [068826c25b](https://linux-hardware.org/?probe=068826c25b) | Jun 10, 2023 |
| Gigabyte      | P35-S3G                     | Desktop     | [71339b40ec](https://linux-hardware.org/?probe=71339b40ec) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [c74a9048c0](https://linux-hardware.org/?probe=c74a9048c0) | Jun 10, 2023 |
| HP            | 250 G1                      | Notebook    | [1b9c881cae](https://linux-hardware.org/?probe=1b9c881cae) | Jun 10, 2023 |
| HP            | 250 G1                      | Notebook    | [0591407196](https://linux-hardware.org/?probe=0591407196) | Jun 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1388a433de](https://linux-hardware.org/?probe=1388a433de) | Jun 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [d2df298764](https://linux-hardware.org/?probe=d2df298764) | Jun 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [9c6db3b61d](https://linux-hardware.org/?probe=9c6db3b61d) | Jun 10, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [6eada916c0](https://linux-hardware.org/?probe=6eada916c0) | Jun 10, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dfac11ccad](https://linux-hardware.org/?probe=dfac11ccad) | Jun 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9cb24f9445](https://linux-hardware.org/?probe=9cb24f9445) | Jun 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [142fc47b59](https://linux-hardware.org/?probe=142fc47b59) | Jun 09, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [22e9021ae3](https://linux-hardware.org/?probe=22e9021ae3) | Jun 09, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [f8eb3278fe](https://linux-hardware.org/?probe=f8eb3278fe) | Jun 09, 2023 |
| HP            | 18E7                        | Desktop     | [d80810b7f8](https://linux-hardware.org/?probe=d80810b7f8) | Jun 08, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a707a562b8](https://linux-hardware.org/?probe=a707a562b8) | Jun 08, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [6f7077634a](https://linux-hardware.org/?probe=6f7077634a) | Jun 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [9de320e96f](https://linux-hardware.org/?probe=9de320e96f) | Jun 08, 2023 |
| Google        | Edgar                       | Notebook    | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a9ca37ac88](https://linux-hardware.org/?probe=a9ca37ac88) | Jun 07, 2023 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [328aaf23c9](https://linux-hardware.org/?probe=328aaf23c9) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [011dadb850](https://linux-hardware.org/?probe=011dadb850) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a1c7c69a05](https://linux-hardware.org/?probe=a1c7c69a05) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [e33a2ba9dc](https://linux-hardware.org/?probe=e33a2ba9dc) | Jun 07, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [3c89a2a6a2](https://linux-hardware.org/?probe=3c89a2a6a2) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [e05fc7beed](https://linux-hardware.org/?probe=e05fc7beed) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [26be42ecb8](https://linux-hardware.org/?probe=26be42ecb8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [26f1962805](https://linux-hardware.org/?probe=26f1962805) | Jun 07, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [96a6ae8f4d](https://linux-hardware.org/?probe=96a6ae8f4d) | Jun 07, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8ef73cacf2](https://linux-hardware.org/?probe=8ef73cacf2) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [6ba5aae544](https://linux-hardware.org/?probe=6ba5aae544) | Jun 07, 2023 |
| HP            | 250 G1                      | Notebook    | [f5c0548f17](https://linux-hardware.org/?probe=f5c0548f17) | Jun 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [a77a12f870](https://linux-hardware.org/?probe=a77a12f870) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bb5f9c1964](https://linux-hardware.org/?probe=bb5f9c1964) | Jun 06, 2023 |
| HP            | 250 G1                      | Notebook    | [f6cab30981](https://linux-hardware.org/?probe=f6cab30981) | Jun 06, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c33a9e5ccb](https://linux-hardware.org/?probe=c33a9e5ccb) | Jun 06, 2023 |
| eMachines     | E725                        | Notebook    | [4e50fbb5a2](https://linux-hardware.org/?probe=4e50fbb5a2) | Jun 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [fa3bffbe76](https://linux-hardware.org/?probe=fa3bffbe76) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0b48c563e5](https://linux-hardware.org/?probe=0b48c563e5) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6f1c2a6a61](https://linux-hardware.org/?probe=6f1c2a6a61) | Jun 05, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [6f15ff21e4](https://linux-hardware.org/?probe=6f15ff21e4) | Jun 05, 2023 |
| Dell          | Latitude E5520              | Notebook    | [ab87df9910](https://linux-hardware.org/?probe=ab87df9910) | Jun 05, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [4e11e5ab66](https://linux-hardware.org/?probe=4e11e5ab66) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | Desktop     | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e1fabecae3](https://linux-hardware.org/?probe=e1fabecae3) | Jun 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [66ed048f40](https://linux-hardware.org/?probe=66ed048f40) | Jun 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0fb6670b07](https://linux-hardware.org/?probe=0fb6670b07) | Jun 03, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c2c0ba92d5](https://linux-hardware.org/?probe=c2c0ba92d5) | Jun 03, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bcf794dd14](https://linux-hardware.org/?probe=bcf794dd14) | Jun 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [746c0d0644](https://linux-hardware.org/?probe=746c0d0644) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [c747f45c48](https://linux-hardware.org/?probe=c747f45c48) | Jun 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [c0d0a7cb50](https://linux-hardware.org/?probe=c0d0a7cb50) | Jun 01, 2023 |
| MSI           | U200                        | Notebook    | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [f7e3bde58c](https://linux-hardware.org/?probe=f7e3bde58c) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [871cbcbb88](https://linux-hardware.org/?probe=871cbcbb88) | May 31, 2023 |
| HP            | Notebook                    | Notebook    | [7d7934f727](https://linux-hardware.org/?probe=7d7934f727) | May 31, 2023 |
| HP            | Notebook                    | Notebook    | [161aaf4150](https://linux-hardware.org/?probe=161aaf4150) | May 31, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f0d7ab6b7e](https://linux-hardware.org/?probe=f0d7ab6b7e) | May 31, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [0005e56720](https://linux-hardware.org/?probe=0005e56720) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | Notebook    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [ac1e17e897](https://linux-hardware.org/?probe=ac1e17e897) | May 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [03d2cac76c](https://linux-hardware.org/?probe=03d2cac76c) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [54d3fad8f3](https://linux-hardware.org/?probe=54d3fad8f3) | May 29, 2023 |
| HP            | 8265                        | Desktop     | [a554e3bddf](https://linux-hardware.org/?probe=a554e3bddf) | May 29, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [62764248cb](https://linux-hardware.org/?probe=62764248cb) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [e681025f33](https://linux-hardware.org/?probe=e681025f33) | May 29, 2023 |
| HP            | 8265                        | Desktop     | [66f0a2d631](https://linux-hardware.org/?probe=66f0a2d631) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [68ec8b84a1](https://linux-hardware.org/?probe=68ec8b84a1) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | Notebook    | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8c6f8829e2](https://linux-hardware.org/?probe=8c6f8829e2) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [035161324d](https://linux-hardware.org/?probe=035161324d) | May 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8656657a77](https://linux-hardware.org/?probe=8656657a77) | May 28, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [82fa1dfa46](https://linux-hardware.org/?probe=82fa1dfa46) | May 28, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [c301857917](https://linux-hardware.org/?probe=c301857917) | May 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [1718d8d65e](https://linux-hardware.org/?probe=1718d8d65e) | May 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [0aac24410d](https://linux-hardware.org/?probe=0aac24410d) | May 27, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [fef3f47b89](https://linux-hardware.org/?probe=fef3f47b89) | May 27, 2023 |
| HP            | 8265                        | Desktop     | [33488b045e](https://linux-hardware.org/?probe=33488b045e) | May 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d26d09ef64](https://linux-hardware.org/?probe=d26d09ef64) | May 26, 2023 |
| Acer          | TravelMate 6292             | Notebook    | [0a4cb3e4b3](https://linux-hardware.org/?probe=0a4cb3e4b3) | May 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [512abef14b](https://linux-hardware.org/?probe=512abef14b) | May 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d93a5e7c70](https://linux-hardware.org/?probe=d93a5e7c70) | May 25, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [575d3814e9](https://linux-hardware.org/?probe=575d3814e9) | May 25, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d7d112d2f0](https://linux-hardware.org/?probe=d7d112d2f0) | May 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | Notebook    | [9f7a16aa7b](https://linux-hardware.org/?probe=9f7a16aa7b) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | Notebook    | [bbb23b2823](https://linux-hardware.org/?probe=bbb23b2823) | May 25, 2023 |
| HP            | Pavilion 17                 | Notebook    | [792ac6919d](https://linux-hardware.org/?probe=792ac6919d) | May 24, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [920a4901d9](https://linux-hardware.org/?probe=920a4901d9) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [da302bee4e](https://linux-hardware.org/?probe=da302bee4e) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5fff4f66c1](https://linux-hardware.org/?probe=5fff4f66c1) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5798ed934b](https://linux-hardware.org/?probe=5798ed934b) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9320baf9c8](https://linux-hardware.org/?probe=9320baf9c8) | May 22, 2023 |
| Medion        | MS-7748                     | Desktop     | [84765690f5](https://linux-hardware.org/?probe=84765690f5) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [88ffb8b020](https://linux-hardware.org/?probe=88ffb8b020) | May 22, 2023 |
| eMachines     | E725                        | Notebook    | [c75d7eb314](https://linux-hardware.org/?probe=c75d7eb314) | May 22, 2023 |
| eMachines     | E725                        | Notebook    | [f32fb866fa](https://linux-hardware.org/?probe=f32fb866fa) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5f83edfb1e](https://linux-hardware.org/?probe=5f83edfb1e) | May 22, 2023 |
| HP            | 8265                        | Desktop     | [5ce02f4648](https://linux-hardware.org/?probe=5ce02f4648) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c0330d366f](https://linux-hardware.org/?probe=c0330d366f) | May 21, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [2ab72e28d7](https://linux-hardware.org/?probe=2ab72e28d7) | May 21, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e859c48e1](https://linux-hardware.org/?probe=6e859c48e1) | May 21, 2023 |
| Medion        | MS-7748                     | Desktop     | [dc5431a93b](https://linux-hardware.org/?probe=dc5431a93b) | May 21, 2023 |
| MSI           | MS-7309                     | Desktop     | [0b5d330939](https://linux-hardware.org/?probe=0b5d330939) | May 21, 2023 |
| Medion        | MS-7748                     | Desktop     | [d2fa9ef11a](https://linux-hardware.org/?probe=d2fa9ef11a) | May 21, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [313fb9c88a](https://linux-hardware.org/?probe=313fb9c88a) | May 21, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [de2fc32d08](https://linux-hardware.org/?probe=de2fc32d08) | May 21, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [74122892bc](https://linux-hardware.org/?probe=74122892bc) | May 21, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [4e4024bced](https://linux-hardware.org/?probe=4e4024bced) | May 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [958b40f42c](https://linux-hardware.org/?probe=958b40f42c) | May 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5043ac245f](https://linux-hardware.org/?probe=5043ac245f) | May 21, 2023 |
| Sony          | VGN-FW21Z                   | Notebook    | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [562bec5076](https://linux-hardware.org/?probe=562bec5076) | May 20, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7db14b0f6f](https://linux-hardware.org/?probe=7db14b0f6f) | May 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [2e78e77fef](https://linux-hardware.org/?probe=2e78e77fef) | May 19, 2023 |
| eMachines     | E725                        | Notebook    | [517ba05822](https://linux-hardware.org/?probe=517ba05822) | May 19, 2023 |
| HP            | 250 G2                      | Notebook    | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [1d729ae4ea](https://linux-hardware.org/?probe=1d729ae4ea) | May 19, 2023 |
| Dell          | Latitude D630               | Notebook    | [9526ff1765](https://linux-hardware.org/?probe=9526ff1765) | May 19, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [c791e54f97](https://linux-hardware.org/?probe=c791e54f97) | May 19, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [edbc15eb75](https://linux-hardware.org/?probe=edbc15eb75) | May 18, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4587e40310](https://linux-hardware.org/?probe=4587e40310) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [411344a862](https://linux-hardware.org/?probe=411344a862) | May 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [75c2a22eb5](https://linux-hardware.org/?probe=75c2a22eb5) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [868d98e4f4](https://linux-hardware.org/?probe=868d98e4f4) | May 18, 2023 |
| HP            | 625                         | Notebook    | [8e34027a91](https://linux-hardware.org/?probe=8e34027a91) | May 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [7a7497a4b3](https://linux-hardware.org/?probe=7a7497a4b3) | May 18, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [b3b39b07a5](https://linux-hardware.org/?probe=b3b39b07a5) | May 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [400b91098c](https://linux-hardware.org/?probe=400b91098c) | May 18, 2023 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [a04e4c387e](https://linux-hardware.org/?probe=a04e4c387e) | May 17, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [ad477b9698](https://linux-hardware.org/?probe=ad477b9698) | May 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5d77e9825a](https://linux-hardware.org/?probe=5d77e9825a) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [0323142e79](https://linux-hardware.org/?probe=0323142e79) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [d734e52f59](https://linux-hardware.org/?probe=d734e52f59) | May 17, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a65ace49b0](https://linux-hardware.org/?probe=a65ace49b0) | May 17, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a7f0d5509c](https://linux-hardware.org/?probe=a7f0d5509c) | May 17, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [30c42f6f19](https://linux-hardware.org/?probe=30c42f6f19) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6856deb5d7](https://linux-hardware.org/?probe=6856deb5d7) | May 16, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [6b606c0c57](https://linux-hardware.org/?probe=6b606c0c57) | May 16, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [f9672e78a2](https://linux-hardware.org/?probe=f9672e78a2) | May 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e228d9926b](https://linux-hardware.org/?probe=e228d9926b) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e01dbddbd0](https://linux-hardware.org/?probe=e01dbddbd0) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [72db5ccefc](https://linux-hardware.org/?probe=72db5ccefc) | May 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f977ce9be3](https://linux-hardware.org/?probe=f977ce9be3) | May 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [f286932235](https://linux-hardware.org/?probe=f286932235) | May 15, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [d3bc261952](https://linux-hardware.org/?probe=d3bc261952) | May 15, 2023 |
| Dell          | Latitude 5490               | Notebook    | [0a6ee8c111](https://linux-hardware.org/?probe=0a6ee8c111) | May 14, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8661cb20d2](https://linux-hardware.org/?probe=8661cb20d2) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [32c12bfb05](https://linux-hardware.org/?probe=32c12bfb05) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ba63571489](https://linux-hardware.org/?probe=ba63571489) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [d72abd1f09](https://linux-hardware.org/?probe=d72abd1f09) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | Desktop     | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [8768af826f](https://linux-hardware.org/?probe=8768af826f) | May 14, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [f6cf41154f](https://linux-hardware.org/?probe=f6cf41154f) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [fed9273467](https://linux-hardware.org/?probe=fed9273467) | May 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ae4ee3c43d](https://linux-hardware.org/?probe=ae4ee3c43d) | May 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0ae54cb7c4](https://linux-hardware.org/?probe=0ae54cb7c4) | May 13, 2023 |
| Dell          | Latitude 5480               | Notebook    | [63cd615fa8](https://linux-hardware.org/?probe=63cd615fa8) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e172257a22](https://linux-hardware.org/?probe=e172257a22) | May 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [60ac4f3964](https://linux-hardware.org/?probe=60ac4f3964) | May 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [1e8aca1c49](https://linux-hardware.org/?probe=1e8aca1c49) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [9840f334f5](https://linux-hardware.org/?probe=9840f334f5) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [db9aaf4ce9](https://linux-hardware.org/?probe=db9aaf4ce9) | May 13, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [264720475a](https://linux-hardware.org/?probe=264720475a) | May 13, 2023 |
| eMachines     | E725                        | Notebook    | [52848aa6bd](https://linux-hardware.org/?probe=52848aa6bd) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [d06987bfd6](https://linux-hardware.org/?probe=d06987bfd6) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
| HP            | 8055                        | Desktop     | [7f692f60e6](https://linux-hardware.org/?probe=7f692f60e6) | May 12, 2023 |
| HP            | Notebook                    | Notebook    | [bc25329bce](https://linux-hardware.org/?probe=bc25329bce) | May 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9efa5d994b](https://linux-hardware.org/?probe=9efa5d994b) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [024b4d4f97](https://linux-hardware.org/?probe=024b4d4f97) | May 12, 2023 |
| Medion        | MS-7748                     | Desktop     | [c5b24a357f](https://linux-hardware.org/?probe=c5b24a357f) | May 12, 2023 |
| HP            | Notebook                    | Notebook    | [d527d781af](https://linux-hardware.org/?probe=d527d781af) | May 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [e69c9bb60f](https://linux-hardware.org/?probe=e69c9bb60f) | May 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [17cf022069](https://linux-hardware.org/?probe=17cf022069) | May 11, 2023 |
| eMachines     | E725                        | Notebook    | [94e51437e6](https://linux-hardware.org/?probe=94e51437e6) | May 11, 2023 |
| MSI           | A75MA-P35                   | Desktop     | [18b29879dd](https://linux-hardware.org/?probe=18b29879dd) | May 11, 2023 |
| MSI           | A75MA-P35                   | Desktop     | [abcfdbcbfc](https://linux-hardware.org/?probe=abcfdbcbfc) | May 11, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0c8d19bdf0](https://linux-hardware.org/?probe=0c8d19bdf0) | May 10, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [dbc75c5600](https://linux-hardware.org/?probe=dbc75c5600) | May 10, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [396be908b5](https://linux-hardware.org/?probe=396be908b5) | May 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [56d9faa756](https://linux-hardware.org/?probe=56d9faa756) | May 10, 2023 |
| HP            | 250 G1                      | Notebook    | [09879bd463](https://linux-hardware.org/?probe=09879bd463) | May 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [bd3934d526](https://linux-hardware.org/?probe=bd3934d526) | May 10, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [543cce00c7](https://linux-hardware.org/?probe=543cce00c7) | May 09, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [7a97cdf93b](https://linux-hardware.org/?probe=7a97cdf93b) | May 09, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [78b60f4ad9](https://linux-hardware.org/?probe=78b60f4ad9) | May 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [6c55bc2118](https://linux-hardware.org/?probe=6c55bc2118) | May 09, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [3d378ca82d](https://linux-hardware.org/?probe=3d378ca82d) | May 09, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [4d3e8cb0e9](https://linux-hardware.org/?probe=4d3e8cb0e9) | May 09, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [fc9004551b](https://linux-hardware.org/?probe=fc9004551b) | May 09, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [f900658289](https://linux-hardware.org/?probe=f900658289) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [65b039a3f5](https://linux-hardware.org/?probe=65b039a3f5) | May 08, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [e5c5cd0fcf](https://linux-hardware.org/?probe=e5c5cd0fcf) | May 08, 2023 |
| Acer          | V5-131                      | Notebook    | [d68eaead66](https://linux-hardware.org/?probe=d68eaead66) | May 08, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bd15eaa1e6](https://linux-hardware.org/?probe=bd15eaa1e6) | May 08, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [1d06735e36](https://linux-hardware.org/?probe=1d06735e36) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [d17791f116](https://linux-hardware.org/?probe=d17791f116) | May 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [ad9af07a7c](https://linux-hardware.org/?probe=ad9af07a7c) | May 08, 2023 |
| eMachines     | E725                        | Notebook    | [bb9c7992f8](https://linux-hardware.org/?probe=bb9c7992f8) | May 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [76748da9cd](https://linux-hardware.org/?probe=76748da9cd) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [3b40b9b869](https://linux-hardware.org/?probe=3b40b9b869) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [b0200f5262](https://linux-hardware.org/?probe=b0200f5262) | May 07, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1f677501c0](https://linux-hardware.org/?probe=1f677501c0) | May 07, 2023 |
| HP            | 650                         | Notebook    | [3ece9ca18a](https://linux-hardware.org/?probe=3ece9ca18a) | May 07, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [8c80fd3109](https://linux-hardware.org/?probe=8c80fd3109) | May 07, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [fd7a2486f2](https://linux-hardware.org/?probe=fd7a2486f2) | May 07, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b76e0e7397](https://linux-hardware.org/?probe=b76e0e7397) | May 06, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [5cad7b7e28](https://linux-hardware.org/?probe=5cad7b7e28) | May 06, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [58de65fdbd](https://linux-hardware.org/?probe=58de65fdbd) | May 06, 2023 |
| HP            | 3033h                       | Desktop     | [a322bec919](https://linux-hardware.org/?probe=a322bec919) | May 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [e9a4f752c5](https://linux-hardware.org/?probe=e9a4f752c5) | May 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [2bd846964e](https://linux-hardware.org/?probe=2bd846964e) | May 06, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [1495984c3f](https://linux-hardware.org/?probe=1495984c3f) | May 06, 2023 |
| ASUSTek       | K53BY                       | Notebook    | [6a9ae368ba](https://linux-hardware.org/?probe=6a9ae368ba) | May 06, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [78bb45767d](https://linux-hardware.org/?probe=78bb45767d) | May 06, 2023 |
| eMachines     | E725                        | Notebook    | [15807b1086](https://linux-hardware.org/?probe=15807b1086) | May 06, 2023 |
| eMachines     | E725                        | Notebook    | [290d356d4c](https://linux-hardware.org/?probe=290d356d4c) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e409298467](https://linux-hardware.org/?probe=e409298467) | May 05, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [9640ef7fa5](https://linux-hardware.org/?probe=9640ef7fa5) | May 05, 2023 |
| HP            | 339A                        | Desktop     | [920b722009](https://linux-hardware.org/?probe=920b722009) | May 05, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | Notebook    | [df56d361ef](https://linux-hardware.org/?probe=df56d361ef) | May 05, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [0e338f138d](https://linux-hardware.org/?probe=0e338f138d) | May 04, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [4114d6e81c](https://linux-hardware.org/?probe=4114d6e81c) | May 04, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b322652461](https://linux-hardware.org/?probe=b322652461) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [c2d5f80f6e](https://linux-hardware.org/?probe=c2d5f80f6e) | May 04, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [3678c25be6](https://linux-hardware.org/?probe=3678c25be6) | May 04, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [61d04b0e4c](https://linux-hardware.org/?probe=61d04b0e4c) | May 04, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6014477aa0](https://linux-hardware.org/?probe=6014477aa0) | May 04, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [aaad7b3a55](https://linux-hardware.org/?probe=aaad7b3a55) | May 04, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [ba51ad63e8](https://linux-hardware.org/?probe=ba51ad63e8) | May 04, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [45035a5981](https://linux-hardware.org/?probe=45035a5981) | May 04, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [77cbfa62cd](https://linux-hardware.org/?probe=77cbfa62cd) | May 04, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [b7b6981f65](https://linux-hardware.org/?probe=b7b6981f65) | May 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [438c1a31ea](https://linux-hardware.org/?probe=438c1a31ea) | May 04, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [182df1bb15](https://linux-hardware.org/?probe=182df1bb15) | May 04, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [6e2629de4d](https://linux-hardware.org/?probe=6e2629de4d) | May 03, 2023 |
| Lenovo        | E50-80 80J2                 | Notebook    | [c82dd5d579](https://linux-hardware.org/?probe=c82dd5d579) | May 03, 2023 |
| Lenovo        | ThinkStation C30 1097A34    | Desktop     | [0eb86a808a](https://linux-hardware.org/?probe=0eb86a808a) | May 03, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [117d914e84](https://linux-hardware.org/?probe=117d914e84) | May 03, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [3aed695405](https://linux-hardware.org/?probe=3aed695405) | May 03, 2023 |
| Dell          | Latitude E5520              | Notebook    | [0861e85947](https://linux-hardware.org/?probe=0861e85947) | May 03, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [8fab6deff5](https://linux-hardware.org/?probe=8fab6deff5) | May 03, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [7e731cb85c](https://linux-hardware.org/?probe=7e731cb85c) | May 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [c8a19f5567](https://linux-hardware.org/?probe=c8a19f5567) | May 02, 2023 |
| MSI           | MS-7817                     | Desktop     | [71aac2d171](https://linux-hardware.org/?probe=71aac2d171) | May 02, 2023 |
| MSI           | MS-7817                     | Desktop     | [b9689d9c27](https://linux-hardware.org/?probe=b9689d9c27) | May 02, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [bdb1e8c4a7](https://linux-hardware.org/?probe=bdb1e8c4a7) | May 02, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [735d6f53e9](https://linux-hardware.org/?probe=735d6f53e9) | May 02, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2280876e20](https://linux-hardware.org/?probe=2280876e20) | May 02, 2023 |
| HP            | 8265                        | Desktop     | [b2c0b909f0](https://linux-hardware.org/?probe=b2c0b909f0) | May 02, 2023 |
| HP            | 8265                        | Desktop     | [05641bda97](https://linux-hardware.org/?probe=05641bda97) | May 02, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [9fcb4f708c](https://linux-hardware.org/?probe=9fcb4f708c) | May 02, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [31e13940be](https://linux-hardware.org/?probe=31e13940be) | May 01, 2023 |
| HP            | 8265                        | Desktop     | [5fca5b8edd](https://linux-hardware.org/?probe=5fca5b8edd) | May 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [96a8ba3062](https://linux-hardware.org/?probe=96a8ba3062) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [856577ad04](https://linux-hardware.org/?probe=856577ad04) | May 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [f84a692777](https://linux-hardware.org/?probe=f84a692777) | Apr 30, 2023 |
| eMachines     | E725                        | Notebook    | [282c0c9f11](https://linux-hardware.org/?probe=282c0c9f11) | Apr 30, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [8bf9a1841e](https://linux-hardware.org/?probe=8bf9a1841e) | Apr 30, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7afb6268da](https://linux-hardware.org/?probe=7afb6268da) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| eMachines     | E725                        | Notebook    | [25da91560d](https://linux-hardware.org/?probe=25da91560d) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [25c6042b4e](https://linux-hardware.org/?probe=25c6042b4e) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [230f3dd04b](https://linux-hardware.org/?probe=230f3dd04b) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [9d5cd21a8f](https://linux-hardware.org/?probe=9d5cd21a8f) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [9bb7a9b712](https://linux-hardware.org/?probe=9bb7a9b712) | Apr 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [292f489feb](https://linux-hardware.org/?probe=292f489feb) | Apr 29, 2023 |
| HP            | 8265                        | Desktop     | [5cdb9f6a93](https://linux-hardware.org/?probe=5cdb9f6a93) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ada78ae33d](https://linux-hardware.org/?probe=ada78ae33d) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9c2dd52f1e](https://linux-hardware.org/?probe=9c2dd52f1e) | Apr 28, 2023 |
| HP            | 8265                        | Desktop     | [71a48b0229](https://linux-hardware.org/?probe=71a48b0229) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| eMachines     | E725                        | Notebook    | [668de483ca](https://linux-hardware.org/?probe=668de483ca) | Apr 27, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9dd9301581](https://linux-hardware.org/?probe=9dd9301581) | Apr 26, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [dd27aa0575](https://linux-hardware.org/?probe=dd27aa0575) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [e0eef23b19](https://linux-hardware.org/?probe=e0eef23b19) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |
| ASUSTek       | M3A                         | Desktop     | [c16000b1e4](https://linux-hardware.org/?probe=c16000b1e4) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [6b9130ca88](https://linux-hardware.org/?probe=6b9130ca88) | Apr 23, 2023 |
| Dell          | Latitude E6230              | Notebook    | [3ec9acadaa](https://linux-hardware.org/?probe=3ec9acadaa) | Apr 23, 2023 |
| Dell          | Latitude E6230              | Notebook    | [8114b606fb](https://linux-hardware.org/?probe=8114b606fb) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [f855722ff3](https://linux-hardware.org/?probe=f855722ff3) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [eeb69d730b](https://linux-hardware.org/?probe=eeb69d730b) | Apr 22, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [89464ddc07](https://linux-hardware.org/?probe=89464ddc07) | Apr 22, 2023 |
| Dell          | Inspiron M5040              | Notebook    | [ae29855106](https://linux-hardware.org/?probe=ae29855106) | Apr 22, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [174aa789ca](https://linux-hardware.org/?probe=174aa789ca) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [bf4fe08c1f](https://linux-hardware.org/?probe=bf4fe08c1f) | Apr 21, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [c0f35fa0d2](https://linux-hardware.org/?probe=c0f35fa0d2) | Apr 21, 2023 |
| MSI           | MS-7817                     | Desktop     | [337a6f2676](https://linux-hardware.org/?probe=337a6f2676) | Apr 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [201add17b6](https://linux-hardware.org/?probe=201add17b6) | Apr 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [12fa5cb019](https://linux-hardware.org/?probe=12fa5cb019) | Apr 20, 2023 |
| HP            | 8265                        | Desktop     | [edff983879](https://linux-hardware.org/?probe=edff983879) | Apr 20, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [b44e010551](https://linux-hardware.org/?probe=b44e010551) | Apr 20, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [6780931a5d](https://linux-hardware.org/?probe=6780931a5d) | Apr 19, 2023 |
| Dell          | Latitude D630               | Notebook    | [4e4c4f519b](https://linux-hardware.org/?probe=4e4c4f519b) | Apr 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bd73c6ceb9](https://linux-hardware.org/?probe=bd73c6ceb9) | Apr 18, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | Desktop     | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [211aa29e44](https://linux-hardware.org/?probe=211aa29e44) | Apr 18, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [f0a442ee36](https://linux-hardware.org/?probe=f0a442ee36) | Apr 17, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [fd7551020f](https://linux-hardware.org/?probe=fd7551020f) | Apr 17, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [264d99482b](https://linux-hardware.org/?probe=264d99482b) | Apr 17, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [6d8f13d1df](https://linux-hardware.org/?probe=6d8f13d1df) | Apr 16, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [40d1573897](https://linux-hardware.org/?probe=40d1573897) | Apr 16, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [a0d799e140](https://linux-hardware.org/?probe=a0d799e140) | Apr 16, 2023 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | Desktop     | [a8d5f3a546](https://linux-hardware.org/?probe=a8d5f3a546) | Apr 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5ef76fe165](https://linux-hardware.org/?probe=5ef76fe165) | Apr 15, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f9b8914504](https://linux-hardware.org/?probe=f9b8914504) | Apr 15, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [3c0ca40bc5](https://linux-hardware.org/?probe=3c0ca40bc5) | Apr 15, 2023 |
| Toshiba       | Satellite M50D-A            | Notebook    | [17fc6af63a](https://linux-hardware.org/?probe=17fc6af63a) | Apr 15, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [17beff29fa](https://linux-hardware.org/?probe=17beff29fa) | Apr 15, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [53070e97ae](https://linux-hardware.org/?probe=53070e97ae) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | Notebook    | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5efa4919ef](https://linux-hardware.org/?probe=5efa4919ef) | Apr 14, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [1a2b2a323f](https://linux-hardware.org/?probe=1a2b2a323f) | Apr 14, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c54473354b](https://linux-hardware.org/?probe=c54473354b) | Apr 14, 2023 |
| HP            | 8265                        | Desktop     | [d50c7e97cb](https://linux-hardware.org/?probe=d50c7e97cb) | Apr 13, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b821e02641](https://linux-hardware.org/?probe=b821e02641) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [ecefe27269](https://linux-hardware.org/?probe=ecefe27269) | Apr 13, 2023 |
| eMachines     | E725                        | Notebook    | [bd87462ced](https://linux-hardware.org/?probe=bd87462ced) | Apr 13, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [6d2971f926](https://linux-hardware.org/?probe=6d2971f926) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [a8184cfc25](https://linux-hardware.org/?probe=a8184cfc25) | Apr 13, 2023 |
| eMachines     | E725                        | Notebook    | [7cd5cba939](https://linux-hardware.org/?probe=7cd5cba939) | Apr 13, 2023 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | Desktop     | [ef975644ad](https://linux-hardware.org/?probe=ef975644ad) | Apr 12, 2023 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | Desktop     | [5394679f59](https://linux-hardware.org/?probe=5394679f59) | Apr 12, 2023 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | Desktop     | [ce3dac0358](https://linux-hardware.org/?probe=ce3dac0358) | Apr 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [e75be02a84](https://linux-hardware.org/?probe=e75be02a84) | Apr 12, 2023 |
| THD           | PX1 01                      | Notebook    | [c2c6b63123](https://linux-hardware.org/?probe=c2c6b63123) | Apr 12, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [203aeef6a1](https://linux-hardware.org/?probe=203aeef6a1) | Apr 12, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [50e64adbb3](https://linux-hardware.org/?probe=50e64adbb3) | Apr 12, 2023 |
| THD           | PX1 01                      | Notebook    | [f4efc1c20d](https://linux-hardware.org/?probe=f4efc1c20d) | Apr 12, 2023 |
| Dell          | Latitude D630               | Notebook    | [8c211bb7c5](https://linux-hardware.org/?probe=8c211bb7c5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | Inspiron M5030              | Notebook    | [a5dd0e262b](https://linux-hardware.org/?probe=a5dd0e262b) | Apr 10, 2023 |
| Dell          | Inspiron M5030              | Notebook    | [03fb4c2b22](https://linux-hardware.org/?probe=03fb4c2b22) | Apr 10, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | Notebook    | [f90c2d47c7](https://linux-hardware.org/?probe=f90c2d47c7) | Apr 10, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [28e5e7ba81](https://linux-hardware.org/?probe=28e5e7ba81) | Apr 09, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4688a4353a](https://linux-hardware.org/?probe=4688a4353a) | Apr 09, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [f36574c96a](https://linux-hardware.org/?probe=f36574c96a) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [280e9879aa](https://linux-hardware.org/?probe=280e9879aa) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [fd65306a4f](https://linux-hardware.org/?probe=fd65306a4f) | Apr 09, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [776313bab4](https://linux-hardware.org/?probe=776313bab4) | Apr 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1ae6e29131](https://linux-hardware.org/?probe=1ae6e29131) | Apr 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1fd391d90b](https://linux-hardware.org/?probe=1fd391d90b) | Apr 09, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [eca06b42fa](https://linux-hardware.org/?probe=eca06b42fa) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [0b2f9a23ee](https://linux-hardware.org/?probe=0b2f9a23ee) | Apr 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [57ed286290](https://linux-hardware.org/?probe=57ed286290) | Apr 09, 2023 |
| Shuttle       | B10IE01                     | Desktop     | [9888356d3d](https://linux-hardware.org/?probe=9888356d3d) | Apr 08, 2023 |
| HP            | 8055                        | Desktop     | [6eebbfc5bd](https://linux-hardware.org/?probe=6eebbfc5bd) | Apr 08, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [7ebca35151](https://linux-hardware.org/?probe=7ebca35151) | Apr 08, 2023 |
| HP            | 8055                        | Desktop     | [f937179590](https://linux-hardware.org/?probe=f937179590) | Apr 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Lenovo        | ThinkPad T60 2008VW7        | Notebook    | [de0d5654c0](https://linux-hardware.org/?probe=de0d5654c0) | Apr 07, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [0db60d0843](https://linux-hardware.org/?probe=0db60d0843) | Apr 06, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [9a6876e458](https://linux-hardware.org/?probe=9a6876e458) | Apr 06, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [ae224a45a1](https://linux-hardware.org/?probe=ae224a45a1) | Apr 06, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [37e8de5b1b](https://linux-hardware.org/?probe=37e8de5b1b) | Apr 06, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c8dd0aae14](https://linux-hardware.org/?probe=c8dd0aae14) | Apr 06, 2023 |
| HP            | 8265                        | Desktop     | [487cae97c1](https://linux-hardware.org/?probe=487cae97c1) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [a451cfcce3](https://linux-hardware.org/?probe=a451cfcce3) | Apr 05, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [eb106fa5d3](https://linux-hardware.org/?probe=eb106fa5d3) | Apr 05, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [1e40d6be20](https://linux-hardware.org/?probe=1e40d6be20) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [d8951b66b8](https://linux-hardware.org/?probe=d8951b66b8) | Apr 03, 2023 |
| HP            | Notebook                    | Notebook    | [05bdafdb5a](https://linux-hardware.org/?probe=05bdafdb5a) | Apr 03, 2023 |
| MSI           | H81M-E33                    | Desktop     | [34b04c305a](https://linux-hardware.org/?probe=34b04c305a) | Apr 03, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [024b88194a](https://linux-hardware.org/?probe=024b88194a) | Apr 03, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | Desktop     | [851f006807](https://linux-hardware.org/?probe=851f006807) | Apr 03, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [f83ac785da](https://linux-hardware.org/?probe=f83ac785da) | Apr 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1994529ccc](https://linux-hardware.org/?probe=1994529ccc) | Apr 02, 2023 |
| HP            | 2820h                       | Desktop     | [8303a62d9a](https://linux-hardware.org/?probe=8303a62d9a) | Apr 02, 2023 |
| HP            | 2820h                       | Desktop     | [142a0ab5b0](https://linux-hardware.org/?probe=142a0ab5b0) | Apr 02, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [b908036588](https://linux-hardware.org/?probe=b908036588) | Apr 02, 2023 |
| HP            | 8265                        | Desktop     | [b1e10a48ef](https://linux-hardware.org/?probe=b1e10a48ef) | Apr 01, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c32ab093ae](https://linux-hardware.org/?probe=c32ab093ae) | Apr 01, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4f9739adf7](https://linux-hardware.org/?probe=4f9739adf7) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [da86fa8f75](https://linux-hardware.org/?probe=da86fa8f75) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7b9f1f44c9](https://linux-hardware.org/?probe=7b9f1f44c9) | Mar 31, 2023 |
| HP            | Notebook                    | Notebook    | [ad90621225](https://linux-hardware.org/?probe=ad90621225) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [24b14fa9bb](https://linux-hardware.org/?probe=24b14fa9bb) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | Notebook    | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [ca97d61896](https://linux-hardware.org/?probe=ca97d61896) | Mar 29, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [4071aa0407](https://linux-hardware.org/?probe=4071aa0407) | Mar 29, 2023 |
| WinFast       | 6100M2MA FAB1.0             | Desktop     | [bed481b8ce](https://linux-hardware.org/?probe=bed481b8ce) | Mar 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [3f2f66842c](https://linux-hardware.org/?probe=3f2f66842c) | Mar 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [796d0b6775](https://linux-hardware.org/?probe=796d0b6775) | Mar 28, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [11c83c2356](https://linux-hardware.org/?probe=11c83c2356) | Mar 27, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ee7de6c56e](https://linux-hardware.org/?probe=ee7de6c56e) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [bc301a57a0](https://linux-hardware.org/?probe=bc301a57a0) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [e31b586083](https://linux-hardware.org/?probe=e31b586083) | Mar 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [fd675e2bf8](https://linux-hardware.org/?probe=fd675e2bf8) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [42f3323eed](https://linux-hardware.org/?probe=42f3323eed) | Mar 27, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [f24b69538d](https://linux-hardware.org/?probe=f24b69538d) | Mar 27, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [5006536f60](https://linux-hardware.org/?probe=5006536f60) | Mar 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2077f4f3ab](https://linux-hardware.org/?probe=2077f4f3ab) | Mar 27, 2023 |
| eMachines     | E725                        | Notebook    | [5212ab8375](https://linux-hardware.org/?probe=5212ab8375) | Mar 26, 2023 |
| eMachines     | E725                        | Notebook    | [8e1945a2c2](https://linux-hardware.org/?probe=8e1945a2c2) | Mar 26, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a663d3bc84](https://linux-hardware.org/?probe=a663d3bc84) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [bb1915d1c3](https://linux-hardware.org/?probe=bb1915d1c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [23df41ca86](https://linux-hardware.org/?probe=23df41ca86) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| MSI           | G41M-P26                    | Desktop     | [b51977b3e0](https://linux-hardware.org/?probe=b51977b3e0) | Mar 24, 2023 |
| MSI           | G41M-P26                    | Desktop     | [a3f7279278](https://linux-hardware.org/?probe=a3f7279278) | Mar 24, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [ed6328937a](https://linux-hardware.org/?probe=ed6328937a) | Mar 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5d056a33d2](https://linux-hardware.org/?probe=5d056a33d2) | Mar 24, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [a375452089](https://linux-hardware.org/?probe=a375452089) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Notebook    | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| eMachines     | E725                        | Notebook    | [a5d9ff191b](https://linux-hardware.org/?probe=a5d9ff191b) | Mar 23, 2023 |
| eMachines     | E725                        | Notebook    | [4204fbff83](https://linux-hardware.org/?probe=4204fbff83) | Mar 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6da9274d93](https://linux-hardware.org/?probe=6da9274d93) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7000eb0f54](https://linux-hardware.org/?probe=7000eb0f54) | Mar 22, 2023 |
| THD           | PX1 01                      | Notebook    | [d210243a53](https://linux-hardware.org/?probe=d210243a53) | Mar 20, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a5b4163b7b](https://linux-hardware.org/?probe=a5b4163b7b) | Mar 20, 2023 |
| THD           | PX1 01                      | Notebook    | [246c888564](https://linux-hardware.org/?probe=246c888564) | Mar 20, 2023 |
| HP            | 339A                        | Desktop     | [44b186c1a1](https://linux-hardware.org/?probe=44b186c1a1) | Mar 19, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [255de14ecc](https://linux-hardware.org/?probe=255de14ecc) | Mar 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [41d461b7c7](https://linux-hardware.org/?probe=41d461b7c7) | Mar 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [0b8157ef19](https://linux-hardware.org/?probe=0b8157ef19) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [79324bb5ca](https://linux-hardware.org/?probe=79324bb5ca) | Mar 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [aad9ecc316](https://linux-hardware.org/?probe=aad9ecc316) | Mar 19, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [338da8730f](https://linux-hardware.org/?probe=338da8730f) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [f955acfdcd](https://linux-hardware.org/?probe=f955acfdcd) | Mar 18, 2023 |
| HP            | Notebook                    | Notebook    | [aa27725a50](https://linux-hardware.org/?probe=aa27725a50) | Mar 18, 2023 |
| HP            | Notebook                    | Notebook    | [a3496c8509](https://linux-hardware.org/?probe=a3496c8509) | Mar 18, 2023 |
| MSI           | A55M-E33                    | Desktop     | [88511d02b5](https://linux-hardware.org/?probe=88511d02b5) | Mar 17, 2023 |
| MSI           | A55M-E33                    | Desktop     | [17422a4444](https://linux-hardware.org/?probe=17422a4444) | Mar 17, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [32fbf8242d](https://linux-hardware.org/?probe=32fbf8242d) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [b0fa0d95b6](https://linux-hardware.org/?probe=b0fa0d95b6) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [871677af38](https://linux-hardware.org/?probe=871677af38) | Mar 17, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [a2fe86f9f4](https://linux-hardware.org/?probe=a2fe86f9f4) | Mar 17, 2023 |
| eMachines     | E725                        | Notebook    | [0ea3d3a0ca](https://linux-hardware.org/?probe=0ea3d3a0ca) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [afb256fb37](https://linux-hardware.org/?probe=afb256fb37) | Mar 16, 2023 |
| Dell          | Inspiron 14 5425            | Notebook    | [1128b14745](https://linux-hardware.org/?probe=1128b14745) | Mar 16, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [63015b2f93](https://linux-hardware.org/?probe=63015b2f93) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [966cfad104](https://linux-hardware.org/?probe=966cfad104) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [b8585e81f9](https://linux-hardware.org/?probe=b8585e81f9) | Mar 15, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [c5b3c4f484](https://linux-hardware.org/?probe=c5b3c4f484) | Mar 15, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [809ad5e6ec](https://linux-hardware.org/?probe=809ad5e6ec) | Mar 15, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [0f5be9d999](https://linux-hardware.org/?probe=0f5be9d999) | Mar 15, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [2aa85f401e](https://linux-hardware.org/?probe=2aa85f401e) | Mar 15, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [cbb7c488cc](https://linux-hardware.org/?probe=cbb7c488cc) | Mar 15, 2023 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [992f5c7e77](https://linux-hardware.org/?probe=992f5c7e77) | Mar 15, 2023 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [fd4d8fac5f](https://linux-hardware.org/?probe=fd4d8fac5f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [d7fbdbbc9f](https://linux-hardware.org/?probe=d7fbdbbc9f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [34a0e74a78](https://linux-hardware.org/?probe=34a0e74a78) | Mar 15, 2023 |
| Sony          | VPCEB4L1E                   | Notebook    | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [aad6765ba3](https://linux-hardware.org/?probe=aad6765ba3) | Mar 14, 2023 |
| Acer          | Aspire C24-420              | All in one  | [04c483ee9b](https://linux-hardware.org/?probe=04c483ee9b) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0acca6eb92](https://linux-hardware.org/?probe=0acca6eb92) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [fbd3d08c57](https://linux-hardware.org/?probe=fbd3d08c57) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [c628d02374](https://linux-hardware.org/?probe=c628d02374) | Mar 13, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [93effe5e22](https://linux-hardware.org/?probe=93effe5e22) | Mar 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [2e04fad893](https://linux-hardware.org/?probe=2e04fad893) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| Insyde        | BayTrail                    | Notebook    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| eMachines     | E725                        | Notebook    | [9a49d6defc](https://linux-hardware.org/?probe=9a49d6defc) | Mar 12, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [f3354208de](https://linux-hardware.org/?probe=f3354208de) | Mar 11, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [dfe2fe939b](https://linux-hardware.org/?probe=dfe2fe939b) | Mar 11, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [9a0daebfc5](https://linux-hardware.org/?probe=9a0daebfc5) | Mar 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d8face90be](https://linux-hardware.org/?probe=d8face90be) | Mar 09, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [5bd46158a2](https://linux-hardware.org/?probe=5bd46158a2) | Mar 09, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [58123ca697](https://linux-hardware.org/?probe=58123ca697) | Mar 09, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [119aa3cec3](https://linux-hardware.org/?probe=119aa3cec3) | Mar 09, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [9d2a7db234](https://linux-hardware.org/?probe=9d2a7db234) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [eca94a98c0](https://linux-hardware.org/?probe=eca94a98c0) | Mar 09, 2023 |
| eMachines     | E725                        | Notebook    | [a4a1665906](https://linux-hardware.org/?probe=a4a1665906) | Mar 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fc2ee93757](https://linux-hardware.org/?probe=fc2ee93757) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [e1ce357347](https://linux-hardware.org/?probe=e1ce357347) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| eMachines     | E725                        | Notebook    | [8efce0fe6f](https://linux-hardware.org/?probe=8efce0fe6f) | Mar 08, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [cda5fafaf9](https://linux-hardware.org/?probe=cda5fafaf9) | Mar 07, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [c27eecca48](https://linux-hardware.org/?probe=c27eecca48) | Mar 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [85701c7290](https://linux-hardware.org/?probe=85701c7290) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [5f336adb00](https://linux-hardware.org/?probe=5f336adb00) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ee9717cba3](https://linux-hardware.org/?probe=ee9717cba3) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [77f0d6b014](https://linux-hardware.org/?probe=77f0d6b014) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [267c62f49a](https://linux-hardware.org/?probe=267c62f49a) | Mar 07, 2023 |
| MSI           | Katana GF66 11UD            | Notebook    | [f464d5be92](https://linux-hardware.org/?probe=f464d5be92) | Mar 07, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [c8cff8908f](https://linux-hardware.org/?probe=c8cff8908f) | Mar 07, 2023 |
| ASUSTek       | ASUS P1512CEA_P1512CEA      | Notebook    | [ef2488509b](https://linux-hardware.org/?probe=ef2488509b) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [57f7900a0d](https://linux-hardware.org/?probe=57f7900a0d) | Mar 06, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [f3cffe6df3](https://linux-hardware.org/?probe=f3cffe6df3) | Mar 06, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [da9dedfafa](https://linux-hardware.org/?probe=da9dedfafa) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [5d94a30450](https://linux-hardware.org/?probe=5d94a30450) | Mar 05, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [31d91c2f18](https://linux-hardware.org/?probe=31d91c2f18) | Mar 05, 2023 |
| Alcor         | SnugBook Q series           | Notebook    | [3b3c4fd9fd](https://linux-hardware.org/?probe=3b3c4fd9fd) | Mar 05, 2023 |
| HP            | 8597                        | Desktop     | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [c564adb32c](https://linux-hardware.org/?probe=c564adb32c) | Mar 04, 2023 |
| HP            | 650                         | Notebook    | [f595da7b8c](https://linux-hardware.org/?probe=f595da7b8c) | Mar 04, 2023 |
| HP            | 650                         | Notebook    | [9d0b38c967](https://linux-hardware.org/?probe=9d0b38c967) | Mar 04, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [4b6e4a874b](https://linux-hardware.org/?probe=4b6e4a874b) | Mar 04, 2023 |
| HP            | Compaq 6720s                | Notebook    | [b422954b5a](https://linux-hardware.org/?probe=b422954b5a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [4bab3eb831](https://linux-hardware.org/?probe=4bab3eb831) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ac82e74c8e](https://linux-hardware.org/?probe=ac82e74c8e) | Mar 02, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [f29ead8551](https://linux-hardware.org/?probe=f29ead8551) | Mar 01, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [9b0b5b79f0](https://linux-hardware.org/?probe=9b0b5b79f0) | Mar 01, 2023 |
| TCL Commun... | 8090                        | Notebook    | [d1f86443c7](https://linux-hardware.org/?probe=d1f86443c7) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [984b6e660d](https://linux-hardware.org/?probe=984b6e660d) | Feb 28, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [677c1ecc11](https://linux-hardware.org/?probe=677c1ecc11) | Feb 28, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [4f30a3b58d](https://linux-hardware.org/?probe=4f30a3b58d) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b4efb334ea](https://linux-hardware.org/?probe=b4efb334ea) | Feb 28, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [28e2b31136](https://linux-hardware.org/?probe=28e2b31136) | Feb 27, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ad2f612788](https://linux-hardware.org/?probe=ad2f612788) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [7e64e6bc1b](https://linux-hardware.org/?probe=7e64e6bc1b) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [9548586341](https://linux-hardware.org/?probe=9548586341) | Feb 27, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [9cdb0f865a](https://linux-hardware.org/?probe=9cdb0f865a) | Feb 27, 2023 |
| Dell          | 0UP453                      | Desktop     | [e45bff8252](https://linux-hardware.org/?probe=e45bff8252) | Feb 26, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [e5fa16c859](https://linux-hardware.org/?probe=e5fa16c859) | Feb 25, 2023 |
| HP            | Unknown                     | Notebook    | [18a8d556cb](https://linux-hardware.org/?probe=18a8d556cb) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | Notebook    | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| HP            | Unknown                     | Notebook    | [dc26b08a65](https://linux-hardware.org/?probe=dc26b08a65) | Feb 25, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [5f15361f57](https://linux-hardware.org/?probe=5f15361f57) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [3259617752](https://linux-hardware.org/?probe=3259617752) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [4d2d4ca208](https://linux-hardware.org/?probe=4d2d4ca208) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | Notebook    | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bf47e38ec4](https://linux-hardware.org/?probe=bf47e38ec4) | Feb 22, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [f2c76dc169](https://linux-hardware.org/?probe=f2c76dc169) | Feb 22, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [fab92ac66f](https://linux-hardware.org/?probe=fab92ac66f) | Feb 22, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [c2be84fb6c](https://linux-hardware.org/?probe=c2be84fb6c) | Feb 21, 2023 |
| HP            | 250 G3                      | Notebook    | [638d8fa72b](https://linux-hardware.org/?probe=638d8fa72b) | Feb 21, 2023 |
| HP            | 250 G3                      | Notebook    | [eaf1a8a9ca](https://linux-hardware.org/?probe=eaf1a8a9ca) | Feb 21, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [d282ac975d](https://linux-hardware.org/?probe=d282ac975d) | Feb 21, 2023 |
| eMachines     | E725                        | Notebook    | [d982b1aa72](https://linux-hardware.org/?probe=d982b1aa72) | Feb 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [5df682e5d6](https://linux-hardware.org/?probe=5df682e5d6) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | K52F                        | Notebook    | [2cbb8f3f38](https://linux-hardware.org/?probe=2cbb8f3f38) | Feb 20, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f1b85863bc](https://linux-hardware.org/?probe=f1b85863bc) | Feb 20, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [3d8b32f453](https://linux-hardware.org/?probe=3d8b32f453) | Feb 20, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [b9ddd17e6c](https://linux-hardware.org/?probe=b9ddd17e6c) | Feb 19, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [22dfb58516](https://linux-hardware.org/?probe=22dfb58516) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [5fc896968e](https://linux-hardware.org/?probe=5fc896968e) | Feb 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c96027c178](https://linux-hardware.org/?probe=c96027c178) | Feb 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [54d3430de9](https://linux-hardware.org/?probe=54d3430de9) | Feb 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [c2168db120](https://linux-hardware.org/?probe=c2168db120) | Feb 18, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [40f71233c4](https://linux-hardware.org/?probe=40f71233c4) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [44e9817292](https://linux-hardware.org/?probe=44e9817292) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4f7bc0d84](https://linux-hardware.org/?probe=a4f7bc0d84) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6bde6db60](https://linux-hardware.org/?probe=a6bde6db60) | Feb 17, 2023 |
| HP            | 3031h                       | Desktop     | [f3d2748999](https://linux-hardware.org/?probe=f3d2748999) | Feb 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [fb9eb2345d](https://linux-hardware.org/?probe=fb9eb2345d) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [4f0e88ce52](https://linux-hardware.org/?probe=4f0e88ce52) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [eac8d6ab9d](https://linux-hardware.org/?probe=eac8d6ab9d) | Feb 16, 2023 |
| HP            | 250 G1                      | Notebook    | [a673746c67](https://linux-hardware.org/?probe=a673746c67) | Feb 16, 2023 |
| Dell          | 0UT806                      | Desktop     | [0d1cdcdbe9](https://linux-hardware.org/?probe=0d1cdcdbe9) | Feb 16, 2023 |
| HP            | 250 G1                      | Notebook    | [cc5e272ca9](https://linux-hardware.org/?probe=cc5e272ca9) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | Desktop     | [9d197fed1d](https://linux-hardware.org/?probe=9d197fed1d) | Feb 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33b1f65ec0](https://linux-hardware.org/?probe=33b1f65ec0) | Feb 15, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [2ae439ec07](https://linux-hardware.org/?probe=2ae439ec07) | Feb 15, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [7b40745c7f](https://linux-hardware.org/?probe=7b40745c7f) | Feb 14, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [903deba17a](https://linux-hardware.org/?probe=903deba17a) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [fd6bd7275b](https://linux-hardware.org/?probe=fd6bd7275b) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| ZOTAC         | ZBOXNANO-AD12               | Mini pc     | [3a6297d90b](https://linux-hardware.org/?probe=3a6297d90b) | Feb 13, 2023 |
| ZOTAC         | ZBOXNANO-AD12               | Mini pc     | [fdc4af9146](https://linux-hardware.org/?probe=fdc4af9146) | Feb 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9538925092](https://linux-hardware.org/?probe=9538925092) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | Desktop     | [7901a0c0ec](https://linux-hardware.org/?probe=7901a0c0ec) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | Desktop     | [fc5af11584](https://linux-hardware.org/?probe=fc5af11584) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [65815ad972](https://linux-hardware.org/?probe=65815ad972) | Feb 13, 2023 |
| Gigabyte      | H55-UD3H                    | Desktop     | [0d0c742e0e](https://linux-hardware.org/?probe=0d0c742e0e) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Acer          | TravelMate 8571             | Notebook    | [609cc404fb](https://linux-hardware.org/?probe=609cc404fb) | Feb 12, 2023 |
| HP            | Compaq 6910p                | Notebook    | [328acaf5ee](https://linux-hardware.org/?probe=328acaf5ee) | Feb 12, 2023 |
| ASUSTek       | K52F                        | Notebook    | [ee35b00a7e](https://linux-hardware.org/?probe=ee35b00a7e) | Feb 12, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| ASUSTek       | K52F                        | Notebook    | [364c41f9aa](https://linux-hardware.org/?probe=364c41f9aa) | Feb 11, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [eb1f7dfd26](https://linux-hardware.org/?probe=eb1f7dfd26) | Feb 10, 2023 |
| GIADA         | SHARKBAY JHS60C             | Desktop     | [71ce3b4e41](https://linux-hardware.org/?probe=71ce3b4e41) | Feb 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [05a6c712af](https://linux-hardware.org/?probe=05a6c712af) | Feb 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [4c34dd05d8](https://linux-hardware.org/?probe=4c34dd05d8) | Feb 09, 2023 |
| Dell          | Latitude E6230              | Notebook    | [d0a04b130a](https://linux-hardware.org/?probe=d0a04b130a) | Feb 09, 2023 |
| Dell          | Latitude E6230              | Notebook    | [11a1ba46f3](https://linux-hardware.org/?probe=11a1ba46f3) | Feb 09, 2023 |
| GIADA         | SHARKBAY JHS60C             | Desktop     | [91ca210b25](https://linux-hardware.org/?probe=91ca210b25) | Feb 09, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| HP            | 2129                        | Desktop     | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| MSI           | GX70 3CC                    | Notebook    | [c9abc5f038](https://linux-hardware.org/?probe=c9abc5f038) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [dd6c2cbcc6](https://linux-hardware.org/?probe=dd6c2cbcc6) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [470857588f](https://linux-hardware.org/?probe=470857588f) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| ASUSTek       | P5G41-M SI/DVI              | Desktop     | [d7568a0cef](https://linux-hardware.org/?probe=d7568a0cef) | Feb 07, 2023 |
| HP            | Unknown                     | Notebook    | [eb01c0393d](https://linux-hardware.org/?probe=eb01c0393d) | Feb 07, 2023 |
| HP            | Unknown                     | Notebook    | [db607a1e03](https://linux-hardware.org/?probe=db607a1e03) | Feb 07, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [560142c79d](https://linux-hardware.org/?probe=560142c79d) | Feb 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0374aed4ef](https://linux-hardware.org/?probe=0374aed4ef) | Feb 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1031465bf3](https://linux-hardware.org/?probe=1031465bf3) | Feb 06, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a1aa0cc1e1](https://linux-hardware.org/?probe=a1aa0cc1e1) | Feb 06, 2023 |
| Lenovo        | ThinkPad T490 20N3S11B0V    | Notebook    | [3b35d51bfb](https://linux-hardware.org/?probe=3b35d51bfb) | Feb 06, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8884f6f6dd](https://linux-hardware.org/?probe=8884f6f6dd) | Feb 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [349dc10d17](https://linux-hardware.org/?probe=349dc10d17) | Feb 05, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8b6fbfa8f5](https://linux-hardware.org/?probe=8b6fbfa8f5) | Feb 04, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [4fd635a0c1](https://linux-hardware.org/?probe=4fd635a0c1) | Feb 04, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [62e5203c26](https://linux-hardware.org/?probe=62e5203c26) | Feb 04, 2023 |
| MSI           | MS-7817                     | Desktop     | [8ce9e243df](https://linux-hardware.org/?probe=8ce9e243df) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| MSI           | MS-7817                     | Desktop     | [bc7ccb9f9c](https://linux-hardware.org/?probe=bc7ccb9f9c) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [bb7b67d9ef](https://linux-hardware.org/?probe=bb7b67d9ef) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [a1ea4874cf](https://linux-hardware.org/?probe=a1ea4874cf) | Feb 03, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [b77d4e1211](https://linux-hardware.org/?probe=b77d4e1211) | Feb 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 2004      | 48.91%  |
| Ubuntu 20.04                 | 270       | 6.59%   |
| BlackPanther 16.2            | 223       | 5.44%   |
| Ubuntu 18.04                 | 156       | 3.81%   |
| Ubuntu 22.04                 | 99        | 2.42%   |
| OpenMandriva 4.2             | 59        | 1.44%   |
| Debian 11                    | 50        | 1.22%   |
| OpenMandriva 4.3             | 39        | 0.95%   |
| Linux Mint 20.2              | 32        | 0.78%   |
| Arch Rolling                 | 32        | 0.78%   |
| Zorin 16                     | 28        | 0.68%   |
| Linux Mint 21.1              | 27        | 0.66%   |
| Arch                         | 25        | 0.61%   |
| Linux Mint 19.3              | 24        | 0.59%   |
| Ubuntu 19.10                 | 23        | 0.56%   |
| Linux Mint 20.3              | 21        | 0.51%   |
| Fedora 38                    | 21        | 0.51%   |
| Debian 10                    | 21        | 0.51%   |
| Linux Mint 20                | 20        | 0.49%   |
| Kubuntu 20.04                | 20        | 0.49%   |
| Fedora 36                    | 20        | 0.49%   |
| ArcoLinux Rolling            | 20        | 0.49%   |
| Xubuntu 20.04                | 19        | 0.46%   |
| Ubuntu 21.10                 | 19        | 0.46%   |
| Ubuntu 19.04                 | 19        | 0.46%   |
| OpenMandriva 23.03           | 19        | 0.46%   |
| KDE neon 20.04               | 19        | 0.46%   |
| Ubuntu 21.04                 | 18        | 0.44%   |
| Pop!_OS 22.04                | 18        | 0.44%   |
| Xubuntu 18.04                | 17        | 0.41%   |
| Manjaro                      | 17        | 0.41%   |
| BlackPanther 22.1            | 17        | 0.41%   |
| openSUSE Tumbleweed-XXXXXXXX | 16        | 0.39%   |
| OpenMandriva 4.50            | 15        | 0.37%   |
| Linux Mint 20.1              | 15        | 0.37%   |
| Fedora 37                    | 15        | 0.37%   |
| Fedora 35                    | 15        | 0.37%   |
| OpenMandriva 23.01           | 14        | 0.34%   |
| Fedora 33                    | 14        | 0.34%   |
| Ubuntu 20.10                 | 13        | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| BlackPanther  | 2198      | 56.14%  |
| Ubuntu        | 614       | 15.68%  |
| OpenMandriva  | 151       | 3.86%   |
| Linux Mint    | 150       | 3.83%   |
| Fedora        | 94        | 2.4%    |
| Debian        | 90        | 2.3%    |
| Endless       | 83        | 2.12%   |
| Arch          | 56        | 1.43%   |
| Manjaro       | 52        | 1.33%   |
| Kubuntu       | 49        | 1.25%   |
| Xubuntu       | 44        | 1.12%   |
| Pop!_OS       | 41        | 1.05%   |
| Zorin         | 40        | 1.02%   |
| KDE neon      | 26        | 0.66%   |
| ArcoLinux     | 24        | 0.61%   |
| ROSA          | 22        | 0.56%   |
| openSUSE      | 22        | 0.56%   |
| Ubuntu MATE   | 19        | 0.49%   |
| Lubuntu       | 17        | 0.43%   |
| Ubuntu Unity  | 15        | 0.38%   |
| Kali          | 10        | 0.26%   |
| Elementary    | 10        | 0.26%   |
| Gentoo        | 9         | 0.23%   |
| EndeavourOS   | 7         | 0.18%   |
| Ubuntu Budgie | 6         | 0.15%   |
| SteamOS       | 5         | 0.13%   |
| Raspbian      | 5         | 0.13%   |
| Nobara        | 4         | 0.1%    |
| MX            | 4         | 0.1%    |
| LMDE          | 4         | 0.1%    |
| Clear Linux   | 4         | 0.1%    |
| Xero          | 3         | 0.08%   |
| Rocky Linux   | 3         | 0.08%   |
| Q4OS          | 3         | 0.08%   |
| UbuntuDDE     | 2         | 0.05%   |
| NixOS         | 2         | 0.05%   |
| Garuda Linux  | 2         | 0.05%   |
| Devuan        | 2         | 0.05%   |
| CentOS        | 2         | 0.05%   |
| antiX         | 2         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 1485      | 32.79%  |
| 5.6.14-desktop-2bP       | 641       | 14.15%  |
| 4.9.20-desktop-pae-1bP   | 206       | 4.55%   |
| 5.1.15-desktop-1bP       | 85        | 1.88%   |
| 5.10.14-desktop-1omv4002 | 55        | 1.21%   |
| 5.4.0-42-generic         | 42        | 0.93%   |
| 5.16.7-desktop-1omv4003  | 37        | 0.82%   |
| 5.15.85-desktop-1bP      | 33        | 0.73%   |
| 5.4.0-58-generic         | 27        | 0.6%    |
| 5.8.0-14-generic         | 24        | 0.53%   |
| 5.4.0-52-generic         | 21        | 0.46%   |
| 5.4.0-48-generic         | 19        | 0.42%   |
| 5.11.0-27-generic        | 19        | 0.42%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.4%    |
| 5.15.0-56-generic        | 15        | 0.33%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.31%   |
| 5.3.0-28-generic         | 14        | 0.31%   |
| 5.15.0-58-generic        | 14        | 0.31%   |
| 5.15.0-52-generic        | 14        | 0.31%   |
| 5.15.0-43-generic        | 14        | 0.31%   |
| 4.18.0-15-generic        | 14        | 0.31%   |
| 5.4.0-54-generic         | 13        | 0.29%   |
| 5.4.0-40-generic         | 13        | 0.29%   |
| 5.4.0-19-generic         | 13        | 0.29%   |
| 5.11.0-34-generic        | 13        | 0.29%   |
| 5.4.0-29-generic         | 12        | 0.26%   |
| 4.15.0-43-generic        | 12        | 0.26%   |
| 5.4.0-91-generic         | 11        | 0.24%   |
| 5.4.0-26-generic         | 11        | 0.24%   |
| 5.15.0-46-generic        | 11        | 0.24%   |
| 5.15.0-41-generic        | 11        | 0.24%   |
| 5.11.0-43-generic        | 11        | 0.24%   |
| 5.8.0-43-generic         | 10        | 0.22%   |
| 5.3.0-46-generic         | 10        | 0.22%   |
| 5.15.0-47-generic        | 10        | 0.22%   |
| 5.13.0-27-generic        | 10        | 0.22%   |
| 5.0.0-37-generic         | 10        | 0.22%   |
| 5.8.0-59-generic         | 9         | 0.2%    |
| 5.8.0-53-generic         | 9         | 0.2%    |
| 5.4.0-39-generic         | 9         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 1485      | 33.77%  |
| 5.6.14  | 643       | 14.62%  |
| 5.4.0   | 340       | 7.73%   |
| 4.9.20  | 217       | 4.93%   |
| 5.15.0  | 160       | 3.64%   |
| 4.15.0  | 117       | 2.66%   |
| 5.11.0  | 104       | 2.36%   |
| 5.8.0   | 102       | 2.32%   |
| 5.1.15  | 86        | 1.96%   |
| 5.3.0   | 81        | 1.84%   |
| 5.13.0  | 81        | 1.84%   |
| 5.10.0  | 61        | 1.39%   |
| 5.0.0   | 56        | 1.27%   |
| 5.10.14 | 55        | 1.25%   |
| 5.19.0  | 47        | 1.07%   |
| 4.18.0  | 40        | 0.91%   |
| 5.16.7  | 38        | 0.86%   |
| 5.15.85 | 34        | 0.77%   |
| 6.2.6   | 24        | 0.55%   |
| 4.19.0  | 22        | 0.5%    |
| 6.1.1   | 18        | 0.41%   |
| 6.2.0   | 13        | 0.3%    |
| 6.1.0   | 13        | 0.3%    |
| 5.14.0  | 11        | 0.25%   |
| 6.2.9   | 10        | 0.23%   |
| 6.0.12  | 9         | 0.2%    |
| 5.16.0  | 9         | 0.2%    |
| 5.12.4  | 9         | 0.2%    |
| 4.13.0  | 9         | 0.2%    |
| 5.18.12 | 8         | 0.18%   |
| 4.4.0   | 8         | 0.18%   |
| 6.4.3   | 7         | 0.16%   |
| 6.3.3   | 7         | 0.16%   |
| 5.13.13 | 7         | 0.16%   |
| 6.2.14  | 6         | 0.14%   |
| 5.9.16  | 6         | 0.14%   |
| 5.9.0   | 6         | 0.14%   |
| 6.3.8   | 5         | 0.11%   |
| 6.2.15  | 5         | 0.11%   |
| 6.0.0   | 5         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 1524      | 34.87%  |
| 5.6     | 658       | 15.05%  |
| 5.4     | 363       | 8.3%    |
| 5.15    | 233       | 5.33%   |
| 4.9     | 230       | 5.26%   |
| 5.10    | 143       | 3.27%   |
| 5.11    | 124       | 2.84%   |
| 5.8     | 118       | 2.7%    |
| 4.15    | 117       | 2.68%   |
| 5.13    | 93        | 2.13%   |
| 5.1     | 89        | 2.04%   |
| 5.3     | 87        | 1.99%   |
| 6.2     | 71        | 1.62%   |
| 5.19    | 70        | 1.6%    |
| 5.16    | 66        | 1.51%   |
| 5.0     | 56        | 1.28%   |
| 6.1     | 52        | 1.19%   |
| 6.0     | 30        | 0.69%   |
| 5.18    | 29        | 0.66%   |
| 6.3     | 28        | 0.64%   |
| 5.14    | 26        | 0.59%   |
| 5.9     | 25        | 0.57%   |
| 4.19    | 24        | 0.55%   |
| 5.12    | 23        | 0.53%   |
| 5.17    | 17        | 0.39%   |
| 5.7     | 16        | 0.37%   |
| 6.4     | 12        | 0.27%   |
| 4.13    | 9         | 0.21%   |
| 4.4     | 8         | 0.18%   |
| 5.5     | 7         | 0.16%   |
| 4.7     | 5         | 0.11%   |
| 4.16    | 4         | 0.09%   |
| 4.5     | 2         | 0.05%   |
| 4.20    | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 6.5     | 1         | 0.02%   |
| 6       | 1         | 0.02%   |
| 5.2     | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3529      | 92.36%  |
| i686    | 281       | 7.35%   |
| armv7l  | 4         | 0.1%    |
| aarch64 | 4         | 0.1%    |
| armv6l  | 2         | 0.05%   |
| unknow  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 2437      | 62.34%  |
| GNOME           | 727       | 18.6%   |
| Unknown         | 262       | 6.7%    |
| XFCE            | 132       | 3.38%   |
| X-Cinnamon      | 115       | 2.94%   |
| MATE            | 64        | 1.64%   |
| KDE             | 38        | 0.97%   |
| Cinnamon        | 29        | 0.74%   |
| LXQt            | 25        | 0.64%   |
| Unity           | 15        | 0.38%   |
| KDE4            | 14        | 0.36%   |
| Pantheon        | 9         | 0.23%   |
| i3              | 8         | 0.2%    |
| Deepin          | 7         | 0.18%   |
| Budgie          | 7         | 0.18%   |
| LXDE            | 6         | 0.15%   |
| GNOME Flashback | 5         | 0.13%   |
| GNOME Classic   | 2         | 0.05%   |
| Trinity         | 1         | 0.03%   |
| qtile           | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| Hyprland        | 1         | 0.03%   |
| Enlightenment   | 1         | 0.03%   |
| bspwm           | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3418      | 88.89%  |
| Wayland | 246       | 6.4%    |
| Unknown | 146       | 3.8%    |
| Tty     | 33        | 0.86%   |
| Web     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2435      | 62.5%   |
| Unknown | 826       | 21.2%   |
| GDM     | 187       | 4.8%    |
| GDM3    | 185       | 4.75%   |
| LightDM | 177       | 4.54%   |
| TDM     | 64        | 1.64%   |
| KDM     | 14        | 0.36%   |
| SLiM    | 5         | 0.13%   |
| XDM     | 3         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2369      | 61.01%  |
| hu_HU      | 904       | 23.28%  |
| en_US      | 489       | 12.59%  |
| en_GB      | 50        | 1.29%   |
| C          | 28        | 0.72%   |
| de_DE      | 17        | 0.44%   |
| ru_UA      | 3         | 0.08%   |
| ru_RU      | 3         | 0.08%   |
| POSIX      | 3         | 0.08%   |
| en_AU      | 3         | 0.08%   |
| nl_NL      | 2         | 0.05%   |
| hu_HU.UTF8 | 2         | 0.05%   |
| C.UTF8     | 2         | 0.05%   |
| it_IT      | 1         | 0.03%   |
| fr_FR      | 1         | 0.03%   |
| fr_BE      | 1         | 0.03%   |
| en_ZA      | 1         | 0.03%   |
| en_IN      | 1         | 0.03%   |
| en_IL      | 1         | 0.03%   |
| en_AG      | 1         | 0.03%   |
| de_AT      | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2473      | 62.69%  |
| EFI  | 1472      | 37.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2213      | 53.44%  |
| Overlay | 1652      | 39.89%  |
| Btrfs   | 130       | 3.14%   |
| Unknown | 80        | 1.93%   |
| Tmpfs   | 20        | 0.48%   |
| Xfs     | 18        | 0.43%   |
| Zfs     | 9         | 0.22%   |
| Ext2    | 9         | 0.22%   |
| Ext3    | 7         | 0.17%   |
| F2fs    | 2         | 0.05%   |
| XXXXXXX | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 1766      | 44.35%  |
| GPT     | 1328      | 33.35%  |
| Unknown | 888       | 22.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3022      | 73.92%  |
| Yes       | 1066      | 26.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2188      | 54.39%  |
| Yes       | 1835      | 45.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 642       | 16.99%  |
| Hewlett-Packard         | 571       | 15.11%  |
| Dell                    | 533       | 14.1%   |
| Lenovo                  | 523       | 13.84%  |
| Gigabyte Technology     | 314       | 8.31%   |
| Acer                    | 258       | 6.83%   |
| ASRock                  | 257       | 6.8%    |
| MSI                     | 120       | 3.18%   |
| Fujitsu                 | 84        | 2.22%   |
| Fujitsu Siemens         | 64        | 1.69%   |
| Toshiba                 | 58        | 1.53%   |
| Samsung Electronics     | 38        | 1.01%   |
| Intel                   | 30        | 0.79%   |
| Packard Bell            | 29        | 0.77%   |
| Medion                  | 22        | 0.58%   |
| eMachines               | 22        | 0.58%   |
| Unknown                 | 20        | 0.53%   |
| Apple                   | 19        | 0.5%    |
| Sony                    | 17        | 0.45%   |
| Foxconn                 | 15        | 0.4%    |
| Alcor                   | 8         | 0.21%   |
| Raspberry Pi Foundation | 7         | 0.19%   |
| Hungaro Flotta Kft      | 7         | 0.19%   |
| HUAWEI                  | 6         | 0.16%   |
| Valve                   | 5         | 0.13%   |
| Pegatron                | 5         | 0.13%   |
| Microsoft               | 5         | 0.13%   |
| Supermicro              | 4         | 0.11%   |
| Insyde                  | 4         | 0.11%   |
| Biostar                 | 4         | 0.11%   |
| ZOTAC                   | 3         | 0.08%   |
| Timi                    | 3         | 0.08%   |
| Shuttle                 | 3         | 0.08%   |
| Huanan                  | 3         | 0.08%   |
| Clevo                   | 3         | 0.08%   |
| AOpen                   | 3         | 0.08%   |
| AMI                     | 3         | 0.08%   |
| ABIT                    | 3         | 0.08%   |
| VXL                     | 2         | 0.05%   |
| TUXEDO                  | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 1.08%   |
| ASRock FM2A75M Pro4+                 | 33        | 0.87%   |
| Unknown                              | 30        | 0.79%   |
| ASUS All Series                      | 28        | 0.74%   |
| Dell OptiPlex 3020                   | 22        | 0.58%   |
| Dell Latitude E6410                  | 18        | 0.48%   |
| HP Notebook                          | 13        | 0.34%   |
| HP 650                               | 13        | 0.34%   |
| Gigabyte G31M-ES2L                   | 13        | 0.34%   |
| Dell OptiPlex 755                    | 12        | 0.32%   |
| ASUS P5KPL-AM EPU                    | 12        | 0.32%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 11        | 0.29%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 11        | 0.29%   |
| Lenovo G50-45 80E3                   | 11        | 0.29%   |
| HP 620                               | 10        | 0.26%   |
| Dell OptiPlex 780                    | 10        | 0.26%   |
| Dell Latitude E6400                  | 10        | 0.26%   |
| Lenovo ThinkPad T400 2768WGB         | 9         | 0.24%   |
| Dell OptiPlex 760                    | 9         | 0.24%   |
| HP Pavilion 15                       | 8         | 0.21%   |
| HP EliteBook 8460p                   | 8         | 0.21%   |
| Gigabyte H61M-S1                     | 8         | 0.21%   |
| Dell Precision WorkStation T3500     | 8         | 0.21%   |
| Dell OptiPlex 7010                   | 8         | 0.21%   |
| Dell Latitude E6530                  | 8         | 0.21%   |
| Dell Latitude E6420                  | 8         | 0.21%   |
| Dell Inspiron 15-3567                | 8         | 0.21%   |
| ASUS X541NA                          | 8         | 0.21%   |
| ASRock G41M-VS3                      | 8         | 0.21%   |
| Lenovo Z50-75 80EC                   | 7         | 0.19%   |
| Lenovo G580 20150                    | 7         | 0.19%   |
| Lenovo G550 20023                    | 7         | 0.19%   |
| HP ProDesk 600 G2 SFF                | 7         | 0.19%   |
| HP EliteBook 6930p                   | 7         | 0.19%   |
| Gigabyte 970A-DS3P                   | 7         | 0.19%   |
| Dell Latitude E6430                  | 7         | 0.19%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.19%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 7         | 0.19%   |
| ASRock N68C-S UCC                    | 7         | 0.19%   |
| MSI MS-7817                          | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 197       | 5.21%   |
| Dell Latitude           | 187       | 4.95%   |
| Acer Aspire             | 170       | 4.5%    |
| HP Compaq               | 130       | 3.44%   |
| Dell OptiPlex           | 128       | 3.39%   |
| Dell Inspiron           | 119       | 3.15%   |
| Lenovo IdeaPad          | 112       | 2.96%   |
| HP EliteBook            | 92        | 2.43%   |
| ASUS VivoBook           | 67        | 1.77%   |
| HP 250                  | 62        | 1.64%   |
| HP ProBook              | 58        | 1.53%   |
| Toshiba Satellite       | 52        | 1.38%   |
| HP Pavilion             | 51        | 1.35%   |
| Lenovo ThinkCentre      | 49        | 1.3%    |
| ASUS PRIME              | 44        | 1.16%   |
| Fujitsu ESPRIMO         | 38        | 1.01%   |
| Dell Vostro             | 35        | 0.93%   |
| ASRock FM2A75M          | 33        | 0.87%   |
| Fujitsu Siemens ESPRIMO | 32        | 0.85%   |
| ASUS ROG                | 32        | 0.85%   |
| Unknown                 | 30        | 0.79%   |
| Packard Bell EasyNote   | 29        | 0.77%   |
| Fujitsu LIFEBOOK        | 29        | 0.77%   |
| ASUS All                | 28        | 0.74%   |
| Dell Precision          | 27        | 0.71%   |
| ASUS TUF                | 23        | 0.61%   |
| Fujitsu Siemens AMILO   | 21        | 0.56%   |
| Acer TravelMate         | 21        | 0.56%   |
| HP Laptop               | 18        | 0.48%   |
| ASUS P5KPL-AM           | 17        | 0.45%   |
| Acer Veriton            | 16        | 0.42%   |
| Acer Swift              | 15        | 0.4%    |
| HP EliteDesk            | 14        | 0.37%   |
| Gigabyte B450           | 14        | 0.37%   |
| HP Notebook             | 13        | 0.34%   |
| HP 650                  | 13        | 0.34%   |
| Gigabyte G31M-ES2L      | 13        | 0.34%   |
| ASUS Zenbook            | 12        | 0.32%   |
| ASUS ASUS               | 12        | 0.32%   |
| Lenovo G50-45           | 11        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 351       | 9.29%   |
| 2011    | 342       | 9.05%   |
| 2010    | 324       | 8.57%   |
| 2012    | 323       | 8.55%   |
| 2018    | 284       | 7.52%   |
| 2014    | 272       | 7.2%    |
| 2008    | 265       | 7.01%   |
| 2009    | 256       | 6.77%   |
| 2017    | 210       | 5.56%   |
| 2015    | 210       | 5.56%   |
| 2007    | 189       | 5%      |
| 2016    | 188       | 4.97%   |
| 2019    | 163       | 4.31%   |
| 2020    | 135       | 3.57%   |
| 2021    | 84        | 2.22%   |
| 2006    | 82        | 2.17%   |
| 2022    | 47        | 1.24%   |
| 2005    | 28        | 0.74%   |
| Unknown | 13        | 0.34%   |
| 2023    | 6         | 0.16%   |
| 2004    | 4         | 0.11%   |
| 2003    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2121      | 56.13%  |
| Desktop        | 1549      | 40.99%  |
| Convertible    | 30        | 0.79%   |
| All in one     | 25        | 0.66%   |
| Mini pc        | 22        | 0.58%   |
| Tablet         | 11        | 0.29%   |
| Server         | 11        | 0.29%   |
| System on chip | 9         | 0.24%   |
| Phone          | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3665      | 96.55%  |
| Enabled  | 131       | 3.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3777      | 99.95%  |
| Yes  | 2         | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1214      | 31.06%  |
| 4.01-8.0    | 841       | 21.51%  |
| 8.01-16.0   | 667       | 17.06%  |
| 16.01-24.0  | 421       | 10.77%  |
| 1.01-2.0    | 372       | 9.52%   |
| 32.01-64.0  | 155       | 3.97%   |
| 2.01-3.0    | 130       | 3.33%   |
| 0.51-1.0    | 41        | 1.05%   |
| 24.01-32.0  | 34        | 0.87%   |
| 64.01-256.0 | 30        | 0.77%   |
| 0.01-0.5    | 3         | 0.08%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 1361      | 30.58%  |
| 1.01-2.0    | 1335      | 30%     |
| 0.01-0.5    | 689       | 15.48%  |
| 2.01-3.0    | 510       | 11.46%  |
| 3.01-4.0    | 240       | 5.39%   |
| 4.01-8.0    | 234       | 5.26%   |
| 8.01-16.0   | 65        | 1.46%   |
| 16.01-24.0  | 11        | 0.25%   |
| 32.01-64.0  | 2         | 0.04%   |
| Unknown     | 2         | 0.04%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2599      | 64.67%  |
| 2       | 903       | 22.47%  |
| 3       | 281       | 6.99%   |
| 4       | 109       | 2.71%   |
| 0       | 49        | 1.22%   |
| 5       | 46        | 1.14%   |
| 6       | 13        | 0.32%   |
| 8       | 6         | 0.15%   |
| 7       | 5         | 0.12%   |
| 9       | 3         | 0.07%   |
| 10      | 2         | 0.05%   |
| 14      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2100      | 54.45%  |
| No        | 1757      | 45.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3505      | 92.63%  |
| No        | 279       | 7.37%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2596      | 68.01%  |
| No        | 1221      | 31.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1948      | 50.68%  |
| Yes       | 1896      | 49.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Hungary | 3779      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 1483      | 33.45%  |
| Szeged            | 93        | 2.1%    |
| Pécs             | 90        | 2.03%   |
| Miskolc           | 84        | 1.89%   |
| Debrecen          | 84        | 1.89%   |
| Győr             | 80        | 1.8%    |
| Tatabánya        | 76        | 1.71%   |
| Székesfehérvár | 57        | 1.29%   |
| Kecskemét        | 53        | 1.2%    |
| Szombathely       | 52        | 1.17%   |
| Szigetszentmiklos | 47        | 1.06%   |
| Zalaegerszeg      | 45        | 1.02%   |
| Nyiregyhaza       | 42        | 0.95%   |
| Érd              | 42        | 0.95%   |
| Veszprém         | 37        | 0.83%   |
| Szekszárd        | 36        | 0.81%   |
| Szolnok           | 34        | 0.77%   |
| Karcag            | 32        | 0.72%   |
| Gödöllő        | 29        | 0.65%   |
| Oroshaza          | 26        | 0.59%   |
| Dunaújváros     | 26        | 0.59%   |
| Berettyóújfalu  | 25        | 0.56%   |
| Eger              | 24        | 0.54%   |
| Toeroekbalint     | 23        | 0.52%   |
| Nagykanizsa       | 22        | 0.5%    |
| Salgotarjan       | 21        | 0.47%   |
| Hodmezovasarhely  | 21        | 0.47%   |
| Gyomro            | 20        | 0.45%   |
| Toekoel           | 19        | 0.43%   |
| Sopron            | 19        | 0.43%   |
| Hatvan            | 19        | 0.43%   |
| Esztergom         | 19        | 0.43%   |
| Pomaz             | 18        | 0.41%   |
| Mosonmagyaróvár | 18        | 0.41%   |
| Ajka              | 18        | 0.41%   |
| Siófok           | 17        | 0.38%   |
| Cegled            | 17        | 0.38%   |
| Kazincbarcika     | 16        | 0.36%   |
| Békéscsaba      | 16        | 0.36%   |
| Veresegyhaz       | 15        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 919       | 1690   | 16.72%  |
| Seagate                     | 781       | 1218   | 14.21%  |
| Samsung Electronics         | 763       | 1250   | 13.88%  |
| Kingston                    | 662       | 1090   | 12.04%  |
| Toshiba                     | 479       | 775    | 8.71%   |
| Hitachi                     | 256       | 354    | 4.66%   |
| HGST                        | 162       | 259    | 2.95%   |
| SanDisk                     | 144       | 210    | 2.62%   |
| Unknown                     | 139       | 194    | 2.53%   |
| A-DATA Technology           | 119       | 185    | 2.16%   |
| Intel                       | 95        | 146    | 1.73%   |
| SK hynix                    | 91        | 129    | 1.66%   |
| Crucial                     | 76        | 129    | 1.38%   |
| Fujitsu                     | 65        | 77     | 1.18%   |
| Micron Technology           | 59        | 79     | 1.07%   |
| SPCC                        | 58        | 78     | 1.06%   |
| Maxtor                      | 51        | 67     | 0.93%   |
| Apacer                      | 41        | 61     | 0.75%   |
| China                       | 29        | 49     | 0.53%   |
| JMicron Technology          | 28        | 32     | 0.51%   |
| Intenso                     | 28        | 44     | 0.51%   |
| OCZ                         | 27        | 33     | 0.49%   |
| LITEON                      | 24        | 30     | 0.44%   |
| Patriot                     | 22        | 43     | 0.4%    |
| PNY                         | 21        | 35     | 0.38%   |
| Transcend                   | 20        | 23     | 0.36%   |
| Kingmax                     | 20        | 38     | 0.36%   |
| Gigabyte Technology         | 20        | 48     | 0.36%   |
| KIOXIA                      | 16        | 19     | 0.29%   |
| KingSpec                    | 15        | 17     | 0.27%   |
| Hewlett-Packard             | 13        | 17     | 0.24%   |
| Kingston Technology Company | 12        | 12     | 0.22%   |
| Team                        | 11        | 16     | 0.2%    |
| Phison                      | 11        | 15     | 0.2%    |
| Apple                       | 11        | 17     | 0.2%    |
| Unknown                     | 10        | 13     | 0.18%   |
| Verbatim                    | 9         | 19     | 0.16%   |
| LITEONIT                    | 9         | 11     | 0.16%   |
| GOODRAM                     | 9         | 10     | 0.16%   |
| Corsair                     | 9         | 11     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 145       | 2.41%   |
| Kingston SA400S37120G 120GB SSD    | 124       | 2.06%   |
| Kingston SV300S37A120G 120GB SSD   | 93        | 1.55%   |
| Kingston SA400S37480G 480GB SSD    | 67        | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB     | 61        | 1.01%   |
| Toshiba DT01ACA100 1TB             | 53        | 0.88%   |
| Toshiba MQ01ABF050 500GB           | 51        | 0.85%   |
| Seagate ST500DM002-1BD142 500GB    | 51        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 50        | 0.83%   |
| Toshiba MQ01ABD100 1TB             | 44        | 0.73%   |
| Samsung SSD 850 EVO 250GB          | 43        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB    | 41        | 0.68%   |
| Kingston SUV400S37120G 120GB SSD   | 39        | 0.65%   |
| HGST HTS545032A7E380 320GB         | 34        | 0.56%   |
| Toshiba DT01ACA050 500GB           | 33        | 0.55%   |
| Toshiba MQ04ABF100 1TB             | 31        | 0.52%   |
| A-DATA SU630 240GB SSD             | 31        | 0.52%   |
| Samsung SSD 860 EVO 500GB          | 30        | 0.5%    |
| HGST HTS545050A7E680 500GB         | 29        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 28        | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 26        | 0.43%   |
| Seagate ST380815AS 80GB            | 24        | 0.4%    |
| HGST HTS721010A9E630 1TB           | 24        | 0.4%    |
| Toshiba HDWD130 3TB                | 23        | 0.38%   |
| Samsung HD502HJ 500GB              | 23        | 0.38%   |
| Toshiba HDWD110 1TB                | 22        | 0.37%   |
| Toshiba DT01ACA200 2TB             | 22        | 0.37%   |
| Seagate ST9320325AS 320GB          | 22        | 0.37%   |
| A-DATA SU700 120GB SSD             | 22        | 0.37%   |
| Kingston SHFS37A120G 120GB SSD     | 21        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB           | 20        | 0.33%   |
| Samsung SSD 850 EVO 500GB          | 20        | 0.33%   |
| SPCC Solid State Disk 256GB        | 19        | 0.32%   |
| Seagate ST9500325AS 500GB          | 19        | 0.32%   |
| Kingston SV300S37A240G 240GB SSD   | 19        | 0.32%   |
| JMicron Generic 512GB              | 19        | 0.32%   |
| Unknown MMC Card  32GB             | 18        | 0.3%    |
| HGST HTS541010A9E680 1TB           | 18        | 0.3%    |
| SPCC Solid State Disk 128GB        | 17        | 0.28%   |
| Seagate ST9250315AS 250GB          | 17        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 815       | 1487   | 28.2%   |
| Seagate             | 766       | 1192   | 26.51%  |
| Toshiba             | 418       | 676    | 14.46%  |
| Samsung Electronics | 275       | 422    | 9.52%   |
| Hitachi             | 256       | 354    | 8.86%   |
| HGST                | 162       | 259    | 5.61%   |
| Fujitsu             | 65        | 77     | 2.25%   |
| Maxtor              | 51        | 67     | 1.76%   |
| JMicron Technology  | 20        | 23     | 0.69%   |
| Unknown             | 14        | 18     | 0.48%   |
| Hewlett-Packard     | 7         | 7      | 0.24%   |
| ASMT                | 7         | 9      | 0.24%   |
| HGST HTS            | 6         | 11     | 0.21%   |
| USB3.0              | 4         | 8      | 0.14%   |
| QUANTUM             | 4         | 4      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Apple               | 3         | 5      | 0.1%    |
| WD MediaMax         | 2         | 4      | 0.07%   |
| Initio              | 2         | 3      | 0.07%   |
| ICY BOX             | 2         | 3      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| External            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| CSD                 | 1         | 2      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 605       | 985    | 31.61%  |
| Samsung Electronics | 347       | 547    | 18.13%  |
| A-DATA Technology   | 110       | 170    | 5.75%   |
| SanDisk             | 98        | 136    | 5.12%   |
| WDC                 | 93        | 157    | 4.86%   |
| Crucial             | 70        | 121    | 3.66%   |
| Intel               | 60        | 96     | 3.13%   |
| SPCC                | 49        | 68     | 2.56%   |
| SK hynix            | 41        | 65     | 2.14%   |
| Micron Technology   | 41        | 55     | 2.14%   |
| Apacer              | 39        | 59     | 2.04%   |
| China               | 29        | 49     | 1.52%   |
| Toshiba             | 27        | 42     | 1.41%   |
| OCZ                 | 27        | 33     | 1.41%   |
| Intenso             | 25        | 40     | 1.31%   |
| LITEON              | 23        | 29     | 1.2%    |
| PNY                 | 21        | 35     | 1.1%    |
| Kingmax             | 20        | 38     | 1.04%   |
| Transcend           | 19        | 21     | 0.99%   |
| Patriot             | 19        | 38     | 0.99%   |
| Gigabyte Technology | 17        | 44     | 0.89%   |
| KingSpec            | 14        | 16     | 0.73%   |
| Team                | 10        | 15     | 0.52%   |
| Verbatim            | 9         | 19     | 0.47%   |
| LITEONIT            | 9         | 11     | 0.47%   |
| GOODRAM             | 9         | 10     | 0.47%   |
| Corsair             | 8         | 10     | 0.42%   |
| Apple               | 6         | 8      | 0.31%   |
| Netac               | 5         | 11     | 0.26%   |
| Hewlett-Packard     | 4         | 5      | 0.21%   |
| Unknown             | 3         | 6      | 0.16%   |
| SATAFIRM            | 3         | 3      | 0.16%   |
| Leven               | 3         | 3      | 0.16%   |
| KingDian            | 3         | 3      | 0.16%   |
| HS-SSD-C100         | 3         | 3      | 0.16%   |
| BHT                 | 3         | 3      | 0.16%   |
| AMD                 | 3         | 3      | 0.16%   |
| Unknown             | 3         | 3      | 0.16%   |
| WDC WDS             | 2         | 2      | 0.1%    |
| Union Memory        | 2         | 6      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2432      | 4642   | 50%     |
| SSD     | 1706      | 3013   | 35.07%  |
| NVMe    | 534       | 848    | 10.98%  |
| MMC     | 135       | 200    | 2.78%   |
| Unknown | 57        | 74     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3356      | 7472   | 80.15%  |
| NVMe | 534       | 848    | 12.75%  |
| SAS  | 162       | 257    | 3.87%   |
| MMC  | 135       | 200    | 3.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2902      | 5456   | 71.55%  |
| 0.51-1.0        | 856       | 1525   | 21.1%   |
| 1.01-2.0        | 168       | 290    | 4.14%   |
| 2.01-3.0        | 57        | 176    | 1.41%   |
| 3.01-4.0        | 45        | 129    | 1.11%   |
| 4.01-10.0       | 20        | 48     | 0.49%   |
| 10.01-20.0      | 6         | 29     | 0.15%   |
| More than 100.0 | 2         | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1516      | 34.58%  |
| 101-250        | 950       | 21.67%  |
| 251-500        | 615       | 14.03%  |
| 51-100         | 317       | 7.23%   |
| 501-1000       | 301       | 6.87%   |
| 1-20           | 204       | 4.65%   |
| 21-50          | 180       | 4.11%   |
| 1001-2000      | 164       | 3.74%   |
| More than 3000 | 74        | 1.69%   |
| 2001-3000      | 63        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1537      | 34.63%  |
| Unknown        | 1516      | 34.16%  |
| 21-50          | 417       | 9.4%    |
| 51-100         | 305       | 6.87%   |
| 101-250        | 273       | 6.15%   |
| 251-500        | 151       | 3.4%    |
| 501-1000       | 125       | 2.82%   |
| 1001-2000      | 73        | 1.64%   |
| More than 3000 | 26        | 0.59%   |
| 2001-3000      | 15        | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB         | 31        | 45     | 2.88%   |
| Kingston SV300S37A120G 120GB SSD   | 22        | 25     | 2.04%   |
| HGST HTS545050A7E680 500GB         | 19        | 29     | 1.76%   |
| Seagate ST500DM002-1BD142 500GB    | 18        | 33     | 1.67%   |
| A-DATA Technology SU630 240GB SSD  | 18        | 26     | 1.67%   |
| Seagate ST500LT012-9WS142 500GB    | 13        | 15     | 1.21%   |
| Seagate ST9320325AS 320GB          | 11        | 23     | 1.02%   |
| Seagate ST500LT012-1DG142 500GB    | 11        | 14     | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 15     | 1.02%   |
| Toshiba MQ01ABF050 500GB           | 10        | 27     | 0.93%   |
| Samsung Electronics HD103UJ 1TB    | 10        | 19     | 0.93%   |
| Toshiba DT01ACA050 500GB           | 9         | 10     | 0.83%   |
| Seagate ST9500325AS 500GB          | 9         | 15     | 0.83%   |
| Seagate ST9250315AS 250GB          | 9         | 14     | 0.83%   |
| Seagate ST9320423AS 320GB          | 8         | 9      | 0.74%   |
| Hitachi HTS545050B9A300 500GB      | 8         | 12     | 0.74%   |
| HGST HTS541010A9E680 1TB           | 8         | 17     | 0.74%   |
| WDC WD5000AADS-00S9B0 500GB        | 7         | 8      | 0.65%   |
| Toshiba MQ01ABD100 1TB             | 7         | 9      | 0.65%   |
| Samsung Electronics HM160HI 160GB  | 7         | 8      | 0.65%   |
| WDC WD5000AAKX-001CA0 500GB        | 6         | 6      | 0.56%   |
| Toshiba DT01ACA100 1TB             | 6         | 12     | 0.56%   |
| Samsung Electronics HD161HJ 160GB  | 6         | 6      | 0.56%   |
| Hitachi HTS545016B9A300 160GB      | 6         | 6      | 0.56%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 5         | 9      | 0.46%   |
| Toshiba MQ01ABD050 500GB           | 5         | 5      | 0.46%   |
| Seagate ST980811AS 80GB            | 5         | 5      | 0.46%   |
| Seagate ST3250318AS 250GB          | 5         | 9      | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 6      | 0.46%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 8      | 0.46%   |
| Samsung Electronics HD321KJ 320GB  | 5         | 5      | 0.46%   |
| Samsung Electronics HD103SI 1TB    | 5         | 5      | 0.46%   |
| Maxtor 6Y080M0 80GB                | 5         | 6      | 0.46%   |
| Hitachi HTS547550A9E384 500GB      | 5         | 17     | 0.46%   |
| Hitachi HTS545050A7E380 500GB      | 5         | 7      | 0.46%   |
| Hitachi HTS545032B9A300 320GB      | 5         | 6      | 0.46%   |
| Hitachi HTS541680J9SA00 80GB       | 5         | 5      | 0.46%   |
| HGST HTS725050A7E630 500GB         | 5         | 5      | 0.46%   |
| HGST HTS545050A7E380 500GB         | 5         | 9      | 0.46%   |
| WDC WD15EARS-00MVWB0 1TB           | 4         | 9      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 230       | 324    | 21.97%  |
| WDC                 | 213       | 332    | 20.34%  |
| Samsung Electronics | 118       | 176    | 11.27%  |
| Hitachi             | 112       | 165    | 10.7%   |
| Toshiba             | 105       | 160    | 10.03%  |
| HGST                | 76        | 115    | 7.26%   |
| Kingston            | 51        | 63     | 4.87%   |
| Maxtor              | 28        | 42     | 2.67%   |
| A-DATA Technology   | 26        | 39     | 2.48%   |
| Fujitsu             | 23        | 30     | 2.2%    |
| Intel               | 16        | 27     | 1.53%   |
| SK hynix            | 9         | 13     | 0.86%   |
| SanDisk             | 4         | 5      | 0.38%   |
| Intenso             | 3         | 3      | 0.29%   |
| IBM/Hitachi         | 3         | 3      | 0.29%   |
| Hewlett-Packard     | 3         | 3      | 0.29%   |
| WD MediaMax         | 2         | 4      | 0.19%   |
| LITEON              | 2         | 2      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| Kingmax             | 2         | 2      | 0.19%   |
| China               | 2         | 2      | 0.19%   |
| Apacer              | 2         | 3      | 0.19%   |
| SPCC                | 1         | 1      | 0.1%    |
| SATAFIRM            | 1         | 1      | 0.1%    |
| R580                | 1         | 1      | 0.1%    |
| QUANTUM             | 1         | 1      | 0.1%    |
| OCZ                 | 1         | 3      | 0.1%    |
| Micron Technology   | 1         | 1      | 0.1%    |
| Leven               | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| Initio              | 1         | 2      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| CSD                 | 1         | 2      | 0.1%    |
| Crucial             | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| Apple               | 1         | 3      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 230       | 324    | 25.67%  |
| WDC                 | 208       | 326    | 23.21%  |
| Hitachi             | 112       | 165    | 12.5%   |
| Samsung Electronics | 108       | 158    | 12.05%  |
| Toshiba             | 98        | 145    | 10.94%  |
| HGST                | 76        | 115    | 8.48%   |
| Maxtor              | 28        | 42     | 3.13%   |
| Fujitsu             | 23        | 30     | 2.57%   |
| IBM/Hitachi         | 3         | 3      | 0.33%   |
| WD MediaMax         | 2         | 4      | 0.22%   |
| Hewlett-Packard     | 2         | 2      | 0.22%   |
| QUANTUM             | 1         | 1      | 0.11%   |
| Initio              | 1         | 2      | 0.11%   |
| ICY BOX             | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| CSD                 | 1         | 2      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 821       | 1322   | 84.64%  |
| SSD     | 141       | 205    | 14.54%  |
| NVMe    | 7         | 8      | 0.72%   |
| Unknown | 1         | 1      | 0.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB  | 2         | 2      | 8.33%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 3      | 8.33%   |
| Zheino CHN-NGFFNV2280-256 256GB    | 1         | 1      | 4.17%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.17%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.17%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.17%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.17%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 4.17%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.17%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 4.17%   |
| Seagate ST380815AS 80GB            | 1         | 3      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.17%   |
| Samsung Electronics SP0802N 80GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HD204UI 2TB    | 1         | 1      | 4.17%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 4.17%   |
| Hitachi HDS721075CLA332 752GB      | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD EX900 250GB    | 1         | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 29.17%  |
| WDC                 | 6         | 12     | 25%     |
| Toshiba             | 3         | 3      | 12.5%   |
| Seagate             | 3         | 5      | 12.5%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Zheino              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2253      | 4932   | 51.64%  |
| Detected | 1146      | 2276   | 26.27%  |
| Malfunc  | 940       | 1536   | 21.54%  |
| Failed   | 24        | 33     | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2822      | 64.17%  |
| AMD                              | 682       | 15.51%  |
| Samsung Electronics              | 192       | 4.37%   |
| JMicron Technology               | 80        | 1.82%   |
| Nvidia                           | 77        | 1.75%   |
| Kingston Technology Company      | 77        | 1.75%   |
| SanDisk                          | 73        | 1.66%   |
| ASMedia Technology               | 65        | 1.48%   |
| SK hynix                         | 47        | 1.07%   |
| Marvell Technology Group         | 39        | 0.89%   |
| Toshiba America Info Systems     | 33        | 0.75%   |
| Phison Electronics               | 32        | 0.73%   |
| VIA Technologies                 | 21        | 0.48%   |
| KIOXIA                           | 21        | 0.48%   |
| Silicon Motion                   | 19        | 0.43%   |
| Micron Technology                | 19        | 0.43%   |
| Silicon Integrated Systems [SiS] | 14        | 0.32%   |
| Silicon Image                    | 13        | 0.3%    |
| LSI Logic / Symbios Logic        | 12        | 0.27%   |
| ADATA Technology                 | 11        | 0.25%   |
| Micron/Crucial Technology        | 8         | 0.18%   |
| Solid State Storage Technology   | 5         | 0.11%   |
| Realtek Semiconductor            | 5         | 0.11%   |
| Integrated Technology Express    | 5         | 0.11%   |
| Broadcom / LSI                   | 4         | 0.09%   |
| Seagate Technology               | 3         | 0.07%   |
| Union Memory (Shenzhen)          | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| Lite-On Technology               | 2         | 0.05%   |
| HighPoint Technologies           | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Initio                           | 1         | 0.02%   |
| Apple                            | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 413       | 7.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 206       | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 191       | 3.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 186       | 3.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 181       | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 169       | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 150       | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 130       | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 123       | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 110       | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 99        | 1.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 98        | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 95        | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 90        | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 89        | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 84        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 81        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 79        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 76        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 75        | 1.36%   |
| AMD FCH IDE Controller                                                                  | 73        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 71        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 65        | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 64        | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 57        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 56        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 51        | 0.93%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 51        | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 49        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 48        | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 48        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 48        | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 46        | 0.84%   |
| Samsung NVMe SSD Controller 980                                                         | 45        | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 45        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 39        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 39        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 38        | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 37        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2833      | 60.64%  |
| IDE  | 1031      | 22.07%  |
| NVMe | 541       | 11.58%  |
| RAID | 248       | 5.31%   |
| SAS  | 11        | 0.24%   |
| SCSI | 8         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2969      | 78.57%  |
| AMD          | 796       | 21.06%  |
| ARM          | 10        | 0.26%   |
| CentaurHauls | 4         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 48        | 1.26%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.11%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 39        | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 38        | 1%      |
| AMD A8-6600K APU with Radeon HD Graphics    | 36        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 34        | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 28        | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 0.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 26        | 0.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 26        | 0.69%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 25        | 0.66%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 22        | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 21        | 0.55%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 21        | 0.55%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 21        | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 21        | 0.55%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21        | 0.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 20        | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 20        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 19        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 18        | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 18        | 0.47%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 18        | 0.47%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 18        | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 17        | 0.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 17        | 0.45%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 16        | 0.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16        | 0.42%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 16        | 0.42%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 16        | 0.42%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16        | 0.42%   |
| AMD FX-8350 Eight-Core Processor            | 16        | 0.42%   |
| AMD FX-6300 Six-Core Processor              | 16        | 0.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15        | 0.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 15        | 0.4%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 15        | 0.4%    |
| Intel Core i3-3110M CPU @ 2.40GHz           | 15        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 791       | 20.87%  |
| Intel Core i3           | 442       | 11.66%  |
| Intel Core i7           | 353       | 9.31%   |
| Intel Core 2 Duo        | 331       | 8.73%   |
| Intel Celeron           | 279       | 7.36%   |
| Intel Pentium           | 161       | 4.25%   |
| AMD Ryzen 5             | 107       | 2.82%   |
| Intel Pentium Dual-Core | 100       | 2.64%   |
| Intel Atom              | 95        | 2.51%   |
| Other                   | 93        | 2.45%   |
| AMD A8                  | 81        | 2.14%   |
| Intel Xeon              | 72        | 1.9%    |
| AMD Ryzen 7             | 65        | 1.72%   |
| AMD FX                  | 56        | 1.48%   |
| Intel Core 2 Quad       | 54        | 1.42%   |
| AMD A4                  | 50        | 1.32%   |
| Intel Pentium Dual      | 48        | 1.27%   |
| Intel Core 2            | 47        | 1.24%   |
| AMD Ryzen 3             | 39        | 1.03%   |
| AMD Athlon II X2        | 38        | 1%      |
| AMD Athlon 64 X2        | 33        | 0.87%   |
| AMD A6                  | 33        | 0.87%   |
| AMD A10                 | 26        | 0.69%   |
| Intel Genuine           | 22        | 0.58%   |
| Intel Pentium 4         | 20        | 0.53%   |
| AMD Phenom II X4        | 19        | 0.5%    |
| AMD E1                  | 19        | 0.5%    |
| AMD E                   | 19        | 0.5%    |
| Intel Pentium Silver    | 15        | 0.4%    |
| AMD E2                  | 15        | 0.4%    |
| AMD Ryzen 9             | 14        | 0.37%   |
| Intel Celeron M         | 13        | 0.34%   |
| Intel Celeron Dual-Core | 13        | 0.34%   |
| Intel Pentium D         | 12        | 0.32%   |
| AMD Sempron             | 11        | 0.29%   |
| AMD Athlon II X4        | 11        | 0.29%   |
| AMD Athlon Dual Core    | 11        | 0.29%   |
| AMD Athlon              | 11        | 0.29%   |
| Intel Pentium M         | 9         | 0.24%   |
| AMD Athlon X4           | 9         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2208      | 58.14%  |
| 4       | 984       | 25.91%  |
| 1       | 234       | 6.16%   |
| 6       | 202       | 5.32%   |
| 8       | 99        | 2.61%   |
| 3       | 29        | 0.76%   |
| 12      | 15        | 0.39%   |
| 10      | 9         | 0.24%   |
| 16      | 7         | 0.18%   |
| 14      | 6         | 0.16%   |
| Unknown | 2         | 0.05%   |
| 36      | 1         | 0.03%   |
| 28      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3764      | 99.55%  |
| 2       | 16        | 0.42%   |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1912      | 50.32%  |
| 1       | 1886      | 49.63%  |
| Unknown | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3682      | 97.1%   |
| 32-bit         | 62        | 1.64%   |
| Unknown        | 48        | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 516       | 13.17%  |
| 0x1067a    | 321       | 8.19%   |
| 0x206a7    | 296       | 7.55%   |
| 0x306a9    | 271       | 6.92%   |
| 0x306c3    | 190       | 4.85%   |
| 0x20655    | 121       | 3.09%   |
| 0x6fd      | 105       | 2.68%   |
| 0x06001119 | 90        | 2.3%    |
| 0x40651    | 89        | 2.27%   |
| 0x10676    | 79        | 2.02%   |
| 0x306d4    | 78        | 1.99%   |
| 0x406e3    | 77        | 1.97%   |
| 0x506e3    | 72        | 1.84%   |
| 0x906ea    | 68        | 1.74%   |
| 0x806e9    | 65        | 1.66%   |
| 0x010000c8 | 60        | 1.53%   |
| 0x906e9    | 57        | 1.45%   |
| 0x806ea    | 55        | 1.4%    |
| 0x6fb      | 51        | 1.3%    |
| 0x406c4    | 51        | 1.3%    |
| 0x806ec    | 44        | 1.12%   |
| 0x20652    | 44        | 1.12%   |
| 0x106ca    | 38        | 0.97%   |
| 0x706a1    | 36        | 0.92%   |
| 0x30678    | 36        | 0.92%   |
| 0x806c1    | 33        | 0.84%   |
| 0x506c9    | 31        | 0.79%   |
| 0x0800820d | 31        | 0.79%   |
| 0x05000119 | 31        | 0.79%   |
| 0x6f2      | 27        | 0.69%   |
| 0x07030105 | 26        | 0.66%   |
| 0x06000852 | 26        | 0.66%   |
| 0x406c3    | 25        | 0.64%   |
| 0x6f6      | 24        | 0.61%   |
| 0x06003106 | 24        | 0.61%   |
| 0x106c2    | 23        | 0.59%   |
| 0x806eb    | 22        | 0.56%   |
| 0x0700010f | 22        | 0.56%   |
| 0x706e5    | 21        | 0.54%   |
| 0x106e5    | 20        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 425       | 11.24%  |
| KabyLake         | 399       | 10.55%  |
| SandyBridge      | 323       | 8.54%   |
| Haswell          | 320       | 8.46%   |
| IvyBridge        | 292       | 7.72%   |
| Core             | 240       | 6.35%   |
| Westmere         | 186       | 4.92%   |
| Skylake          | 183       | 4.84%   |
| Piledriver       | 139       | 3.68%   |
| Silvermont       | 125       | 3.31%   |
| K10              | 115       | 3.04%   |
| Broadwell        | 89        | 2.35%   |
| Zen 2            | 73        | 1.93%   |
| K8 Hammer        | 70        | 1.85%   |
| Bonnell          | 68        | 1.8%    |
| Zen+             | 61        | 1.61%   |
| Zen              | 50        | 1.32%   |
| Goldmont plus    | 50        | 1.32%   |
| Bobcat           | 47        | 1.24%   |
| NetBurst         | 45        | 1.19%   |
| Unknown          | 44        | 1.16%   |
| Puma             | 43        | 1.14%   |
| Zen 3            | 41        | 1.08%   |
| TigerLake        | 38        | 1.01%   |
| Excavator        | 38        | 1.01%   |
| Goldmont         | 37        | 0.98%   |
| Steamroller      | 36        | 0.95%   |
| IceLake          | 34        | 0.9%    |
| P6               | 33        | 0.87%   |
| Nehalem          | 31        | 0.82%   |
| Jaguar           | 27        | 0.71%   |
| CometLake        | 26        | 0.69%   |
| K10 Llano        | 19        | 0.5%    |
| Alderlake Hybrid | 16        | 0.42%   |
| Bulldozer        | 9         | 0.24%   |
| K8 & K10 hybrid  | 7         | 0.19%   |
| Tremont          | 1         | 0.03%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2247      | 51.44%  |
| Nvidia                                       | 1078      | 24.68%  |
| AMD                                          | 1010      | 23.12%  |
| VIA Technologies                             | 13        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 7         | 0.16%   |
| ASPEED Technology                            | 5         | 0.11%   |
| Matrox Electronics Systems                   | 4         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.05%   |
| ATI Technologies                             | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 237       | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 179       | 3.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 149       | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 113       | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 96        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 83        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 1.8%    |
| Intel HD Graphics 620                                                                    | 81        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 79        | 1.71%   |
| Intel HD Graphics 5500                                                                   | 78        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 76        | 1.65%   |
| Intel HD Graphics 530                                                                    | 64        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 60        | 1.3%    |
| Intel UHD Graphics 620                                                                   | 59        | 1.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 56        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 56        | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 53        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 0.93%   |
| Nvidia GT218 [GeForce 210]                                                               | 42        | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.84%   |
| Intel HD Graphics 630                                                                    | 37        | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.8%    |
| AMD Richland [Radeon HD 8570D]                                                           | 37        | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 37        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 0.78%   |
| AMD Renoir                                                                               | 35        | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 34        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 33        | 0.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 33        | 0.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 32        | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 30        | 0.65%   |
| Intel HD Graphics 500                                                                    | 29        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1720      | 44.96%  |
| 1 x AMD                  | 766       | 20.02%  |
| 1 x Nvidia               | 655       | 17.12%  |
| Intel + Nvidia           | 385       | 10.06%  |
| Intel + AMD              | 108       | 2.82%   |
| 2 x AMD                  | 106       | 2.77%   |
| AMD + Nvidia             | 31        | 0.81%   |
| 1 x VIA                  | 13        | 0.34%   |
| Other                    | 11        | 0.29%   |
| 1 x SiS                  | 7         | 0.18%   |
| 2 x Nvidia               | 5         | 0.13%   |
| 2 x Intel                | 5         | 0.13%   |
| 1 x Matrox               | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| AMD + XGI                | 2         | 0.05%   |
| 1 x Intel + 3 x AMD      | 1         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3428      | 89.71%  |
| Proprietary | 280       | 7.33%   |
| Unknown     | 113       | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1940      | 49.39%  |
| 0.01-0.5   | 678       | 17.26%  |
| 1.01-2.0   | 521       | 13.26%  |
| 0.51-1.0   | 444       | 11.3%   |
| 3.01-4.0   | 195       | 4.96%   |
| 7.01-8.0   | 72        | 1.83%   |
| 5.01-6.0   | 49        | 1.25%   |
| 2.01-3.0   | 21        | 0.53%   |
| 8.01-16.0  | 5         | 0.13%   |
| 16.01-24.0 | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 691       | 17.61%  |
| LG Display              | 458       | 11.67%  |
| AU Optronics            | 432       | 11.01%  |
| Goldstar                | 321       | 8.18%   |
| Chimei Innolux          | 281       | 7.16%   |
| BOE                     | 243       | 6.19%   |
| Dell                    | 151       | 3.85%   |
| Chi Mei Optoelectronics | 110       | 2.8%    |
| Philips                 | 103       | 2.62%   |
| Lenovo                  | 103       | 2.62%   |
| Ancor Communications    | 98        | 2.5%    |
| BenQ                    | 96        | 2.45%   |
| Acer                    | 90        | 2.29%   |
| Hewlett-Packard         | 84        | 2.14%   |
| Fujitsu Siemens         | 47        | 1.2%    |
| AOC                     | 44        | 1.12%   |
| LG Philips              | 38        | 0.97%   |
| HannStar                | 32        | 0.82%   |
| InfoVision              | 28        | 0.71%   |
| Sony                    | 27        | 0.69%   |
| Eizo                    | 25        | 0.64%   |
| ASUSTek Computer        | 25        | 0.64%   |
| LG Electronics          | 22        | 0.56%   |
| Vestel Elektronik       | 19        | 0.48%   |
| PANDA                   | 17        | 0.43%   |
| NEC Computers           | 17        | 0.43%   |
| HKC                     | 17        | 0.43%   |
| Apple                   | 17        | 0.43%   |
| ViewSonic               | 14        | 0.36%   |
| Medion                  | 14        | 0.36%   |
| IBM                     | 14        | 0.36%   |
| CPT                     | 14        | 0.36%   |
| Unknown                 | 13        | 0.33%   |
| Toshiba                 | 13        | 0.33%   |
| Sharp                   | 12        | 0.31%   |
| Belinea                 | 12        | 0.31%   |
| Panasonic               | 10        | 0.25%   |
| Arnos Instruments       | 10        | 0.25%   |
| Quanta Display          | 8         | 0.2%    |
| OEM                     | 8         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 50        | 1.25%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 38        | 0.95%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 36        | 0.9%    |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 31        | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.52%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 21        | 0.52%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 19        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.47%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 15        | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.35%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 14        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 13        | 0.32%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 12        | 0.3%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 12        | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 12        | 0.3%    |
| HKC LCD Monitor HKC1850 1360x768 304x228mm 15.0-inch                     | 12        | 0.3%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 12        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.3%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.3%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.3%    |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 11        | 0.27%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.27%   |
| HannStar Hanns.G HQ191 HSD0013 1280x1024 376x301mm 19.0-inch             | 11        | 0.27%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.27%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.27%   |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch          | 11        | 0.27%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 10        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 10        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1342      | 35.28%  |
| 1366x768 (WXGA)    | 953       | 25.05%  |
| 1280x1024 (SXGA)   | 289       | 7.6%    |
| 1280x800 (WXGA)    | 177       | 4.65%   |
| 1440x900 (WXGA+)   | 169       | 4.44%   |
| 1600x900 (HD+)     | 166       | 4.36%   |
| 1680x1050 (WSXGA+) | 152       | 4%      |
| 3840x2160 (4K)     | 125       | 3.29%   |
| 2560x1440 (QHD)    | 60        | 1.58%   |
| 1920x1200 (WUXGA)  | 59        | 1.55%   |
| 1360x768           | 41        | 1.08%   |
| 1024x768 (XGA)     | 40        | 1.05%   |
| 1024x600           | 39        | 1.03%   |
| 2560x1080          | 35        | 0.92%   |
| Unknown            | 22        | 0.58%   |
| 1920x540           | 18        | 0.47%   |
| 2880x1800          | 13        | 0.34%   |
| 3840x1080          | 10        | 0.26%   |
| 2560x1600          | 10        | 0.26%   |
| 1600x1200          | 10        | 0.26%   |
| 3440x1440          | 7         | 0.18%   |
| 1280x720 (HD)      | 7         | 0.18%   |
| 2288x1287          | 6         | 0.16%   |
| 1400x1050          | 5         | 0.13%   |
| 800x1280           | 4         | 0.11%   |
| 3840x2400          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 2160x1440          | 3         | 0.08%   |
| 1280x768           | 3         | 0.08%   |
| 5760x2160          | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |
| 3280x1080          | 2         | 0.05%   |
| 3200x2000          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2736x1824          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1152x864           | 2         | 0.05%   |
| 7680x2160          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1260      | 32.08%  |
| 14      | 284       | 7.23%   |
| 21      | 273       | 6.95%   |
| 17      | 273       | 6.95%   |
| 19      | 248       | 6.31%   |
| 23      | 206       | 5.24%   |
| 24      | 196       | 4.99%   |
| 13      | 186       | 4.74%   |
| 27      | 163       | 4.15%   |
| Unknown | 113       | 2.88%   |
| 22      | 110       | 2.8%    |
| 18      | 109       | 2.77%   |
| 12      | 96        | 2.44%   |
| 20      | 51        | 1.3%    |
| 10      | 49        | 1.25%   |
| 34      | 41        | 1.04%   |
| 11      | 41        | 1.04%   |
| 84      | 36        | 0.92%   |
| 31      | 35        | 0.89%   |
| 72      | 20        | 0.51%   |
| 40      | 19        | 0.48%   |
| 16      | 14        | 0.36%   |
| 32      | 13        | 0.33%   |
| 65      | 11        | 0.28%   |
| 54      | 11        | 0.28%   |
| 52      | 7         | 0.18%   |
| 42      | 7         | 0.18%   |
| 60      | 5         | 0.13%   |
| 46      | 5         | 0.13%   |
| 58      | 4         | 0.1%    |
| 49      | 4         | 0.1%    |
| 7       | 4         | 0.1%    |
| 142     | 3         | 0.08%   |
| 64      | 3         | 0.08%   |
| 48      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 25      | 3         | 0.08%   |
| 8       | 3         | 0.08%   |
| 75      | 2         | 0.05%   |
| 55      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1741      | 44.79%  |
| 401-500        | 620       | 15.95%  |
| 501-600        | 546       | 14.05%  |
| 351-400        | 342       | 8.8%    |
| 201-300        | 265       | 6.82%   |
| Unknown        | 113       | 2.91%   |
| 1001-1500      | 59        | 1.52%   |
| 1501-2000      | 58        | 1.49%   |
| 701-800        | 55        | 1.41%   |
| 601-700        | 44        | 1.13%   |
| 801-900        | 23        | 0.59%   |
| 901-1000       | 9         | 0.23%   |
| 101-200        | 5         | 0.13%   |
| 1-100          | 4         | 0.1%    |
| More than 2000 | 3         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2577      | 70.54%  |
| 16/10   | 557       | 15.25%  |
| 5/4     | 279       | 7.64%   |
| Unknown | 85        | 2.33%   |
| 4/3     | 77        | 2.11%   |
| 21/9    | 41        | 1.12%   |
| 3/2     | 23        | 0.63%   |
| 6/5     | 5         | 0.14%   |
| 32/9    | 3         | 0.08%   |
| 1.00    | 3         | 0.08%   |
| 0.67    | 3         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1244      | 31.88%  |
| 201-250        | 645       | 16.53%  |
| 81-90          | 399       | 10.23%  |
| 151-200        | 373       | 9.56%   |
| 141-150        | 225       | 5.77%   |
| 301-350        | 163       | 4.18%   |
| Unknown        | 113       | 2.9%    |
| More than 1000 | 109       | 2.79%   |
| 121-130        | 104       | 2.67%   |
| 351-500        | 90        | 2.31%   |
| 61-70          | 85        | 2.18%   |
| 71-80          | 74        | 1.9%    |
| 251-300        | 70        | 1.79%   |
| 41-50          | 47        | 1.2%    |
| 51-60          | 43        | 1.1%    |
| 501-1000       | 41        | 1.05%   |
| 131-140        | 32        | 0.82%   |
| 111-120        | 23        | 0.59%   |
| 91-100         | 13        | 0.33%   |
| 1-40           | 9         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1493      | 39.32%  |
| 101-120       | 1183      | 31.16%  |
| 121-160       | 799       | 21.04%  |
| Unknown       | 113       | 2.98%   |
| 161-240       | 101       | 2.66%   |
| 1-50          | 80        | 2.11%   |
| More than 240 | 28        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3361      | 86.51%  |
| 2     | 392       | 10.09%  |
| 0     | 99        | 2.55%   |
| 3     | 30        | 0.77%   |
| 4     | 3         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1990      | 35.59%  |
| Intel                             | 1485      | 26.56%  |
| Qualcomm Atheros                  | 824       | 14.74%  |
| Broadcom                          | 352       | 6.29%   |
| Broadcom Limited                  | 139       | 2.49%   |
| Ralink                            | 119       | 2.13%   |
| Marvell Technology Group          | 78        | 1.39%   |
| Qualcomm Atheros Communications   | 69        | 1.23%   |
| Ralink Technology                 | 62        | 1.11%   |
| TP-Link                           | 56        | 1%      |
| Nvidia                            | 51        | 0.91%   |
| MediaTek                          | 46        | 0.82%   |
| Dell                              | 27        | 0.48%   |
| Samsung Electronics               | 24        | 0.43%   |
| Hewlett-Packard                   | 21        | 0.38%   |
| Huawei Technologies               | 20        | 0.36%   |
| Ericsson Business Mobile Networks | 18        | 0.32%   |
| VIA Technologies                  | 17        | 0.3%    |
| Xiaomi                            | 16        | 0.29%   |
| Sierra Wireless                   | 16        | 0.29%   |
| JMicron Technology                | 14        | 0.25%   |
| ASUSTek Computer                  | 14        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.21%   |
| Attansic Technology               | 11        | 0.2%    |
| ASIX Electronics                  | 9         | 0.16%   |
| Aquantia                          | 9         | 0.16%   |
| Belkin Components                 | 7         | 0.13%   |
| Lenovo                            | 6         | 0.11%   |
| DisplayLink                       | 6         | 0.11%   |
| D-Link System                     | 6         | 0.11%   |
| Microsoft                         | 5         | 0.09%   |
| IMC Networks                      | 5         | 0.09%   |
| Edimax Technology                 | 5         | 0.09%   |
| D-Link                            | 5         | 0.09%   |
| Qualcomm                          | 4         | 0.07%   |
| Accton Technology                 | 4         | 0.07%   |
| Microchip Technology              | 3         | 0.05%   |
| ZyDAS                             | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1401      | 21.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 346       | 5.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 193       | 2.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 122       | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 117       | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 1.39%   |
| Intel Wireless 8265 / 8275                                              | 86        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 1.19%   |
| Intel Wireless 7260                                                     | 74        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 1.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 1.05%   |
| Intel Wireless 7265                                                     | 65        | 1%      |
| Intel 82577LM Gigabit Network Connection                                | 64        | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 63        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                         | 60        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                | 54        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 52        | 0.8%    |
| Intel Ethernet Connection I217-LM                                       | 52        | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 52        | 0.8%    |
| Intel Wireless 3165                                                     | 49        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                    | 49        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 49        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 48        | 0.74%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 0.62%   |
| Intel Wireless 8260                                                     | 39        | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 38        | 0.59%   |
| Intel Wireless 3160                                                     | 38        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 0.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 35        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 34        | 0.52%   |
| Intel I211 Gigabit Network Connection                                   | 34        | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 33        | 0.51%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1052      | 38.78%  |
| Qualcomm Atheros                  | 631       | 23.26%  |
| Realtek Semiconductor             | 357       | 13.16%  |
| Broadcom                          | 189       | 6.97%   |
| Ralink                            | 119       | 4.39%   |
| Qualcomm Atheros Communications   | 69        | 2.54%   |
| Ralink Technology                 | 62        | 2.29%   |
| TP-Link                           | 51        | 1.88%   |
| Broadcom Limited                  | 45        | 1.66%   |
| MediaTek                          | 43        | 1.58%   |
| Sierra Wireless                   | 16        | 0.59%   |
| Dell                              | 16        | 0.59%   |
| ASUSTek Computer                  | 14        | 0.52%   |
| Belkin Components                 | 7         | 0.26%   |
| Microsoft                         | 5         | 0.18%   |
| IMC Networks                      | 5         | 0.18%   |
| Edimax Technology                 | 5         | 0.18%   |
| Ericsson Business Mobile Networks | 4         | 0.15%   |
| D-Link                            | 4         | 0.15%   |
| Hewlett-Packard                   | 3         | 0.11%   |
| ZyDAS                             | 2         | 0.07%   |
| NetGear                           | 2         | 0.07%   |
| Marvell Technology Group          | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| VIA Technologies                  | 1         | 0.04%   |
| TRENDnet                          | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| Qualcomm                          | 1         | 0.04%   |
| Micro Star International          | 1         | 0.04%   |
| Mercucys                          | 1         | 0.04%   |
| Fujitsu Siemens Computers         | 1         | 0.04%   |
| Accton Technology                 | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 122       | 4.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 117       | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 3.3%    |
| Intel Wireless 8265 / 8275                                              | 86        | 3.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 2.82%   |
| Intel Wireless 7260                                                     | 74        | 2.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 2.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 2.49%   |
| Intel Wireless 7265                                                     | 65        | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 63        | 2.31%   |
| Qualcomm Atheros AR9271 802.11n                                         | 60        | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 2.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.98%   |
| Intel Centrino Advanced-N 6200                                          | 52        | 1.91%   |
| Intel Wireless 3165                                                     | 49        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                     | 42        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 1.47%   |
| Intel Wireless 8260                                                     | 39        | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 38        | 1.39%   |
| Intel Wireless 3160                                                     | 38        | 1.39%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 35        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 1.21%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 1.17%   |
| Intel WiFi Link 5100                                                    | 31        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 27        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                         | 27        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 0.99%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 24        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 23        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 0.73%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 20        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1874      | 51.44%  |
| Intel                                  | 906       | 24.87%  |
| Qualcomm Atheros                       | 281       | 7.71%   |
| Broadcom                               | 188       | 5.16%   |
| Broadcom Limited                       | 95        | 2.61%   |
| Marvell Technology Group               | 76        | 2.09%   |
| Nvidia                                 | 51        | 1.4%    |
| Huawei Technologies                    | 17        | 0.47%   |
| Xiaomi                                 | 16        | 0.44%   |
| VIA Technologies                       | 15        | 0.41%   |
| Samsung Electronics                    | 14        | 0.38%   |
| JMicron Technology                     | 14        | 0.38%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.33%   |
| Attansic Technology                    | 11        | 0.3%    |
| ASIX Electronics                       | 9         | 0.25%   |
| Aquantia                               | 9         | 0.25%   |
| Lenovo                                 | 6         | 0.16%   |
| DisplayLink                            | 6         | 0.16%   |
| TP-Link                                | 5         | 0.14%   |
| D-Link System                          | 4         | 0.11%   |
| Qualcomm                               | 3         | 0.08%   |
| Microchip Technology                   | 3         | 0.08%   |
| MediaTek                               | 3         | 0.08%   |
| Accton Technology                      | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| Hewlett-Packard                        | 2         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| HMD Global                             | 1         | 0.03%   |
| Hangzhou Silan Microelectronics        | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |
| Davicom Semiconductor                  | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1401      | 37.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 346       | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 193       | 5.23%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 1.74%   |
| Intel 82567LM Gigabit Network Connection                          | 54        | 1.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 52        | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 49        | 1.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 49        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 34        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 34        | 0.92%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 33        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 31        | 0.84%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 30        | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 28        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 0.57%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 19        | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.41%   |
| Huawei WLZ-AN00                                                   | 15        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 15        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3500      | 56.77%  |
| WiFi     | 2593      | 42.06%  |
| Modem    | 70        | 1.14%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2062      | 51.5%   |
| Ethernet | 1941      | 48.48%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2124      | 55.97%  |
| 1     | 1558      | 41.05%  |
| 0     | 66        | 1.74%   |
| 3     | 40        | 1.05%   |
| 4     | 6         | 0.16%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3256      | 82.68%  |
| Yes  | 682       | 17.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 657       | 34.43%  |
| Qualcomm Atheros Communications | 186       | 9.75%   |
| Broadcom                        | 160       | 8.39%   |
| Realtek Semiconductor           | 148       | 7.76%   |
| Cambridge Silicon Radio         | 131       | 6.87%   |
| Lite-On Technology              | 99        | 5.19%   |
| IMC Networks                    | 95        | 4.98%   |
| Dell                            | 80        | 4.19%   |
| Hewlett-Packard                 | 74        | 3.88%   |
| Foxconn / Hon Hai               | 69        | 3.62%   |
| Ralink                          | 68        | 3.56%   |
| Toshiba                         | 25        | 1.31%   |
| ASUSTek Computer                | 25        | 1.31%   |
| Apple                           | 16        | 0.84%   |
| Ralink Technology               | 10        | 0.52%   |
| Realtek                         | 8         | 0.42%   |
| Askey Computer                  | 7         | 0.37%   |
| Conwise Technology              | 6         | 0.31%   |
| Chicony Electronics             | 6         | 0.31%   |
| Belkin Components               | 5         | 0.26%   |
| Taiyo Yuden                     | 4         | 0.21%   |
| Logitech                        | 4         | 0.21%   |
| Integrated System Solution      | 4         | 0.21%   |
| Foxconn International           | 4         | 0.21%   |
| TP-Link                         | 3         | 0.16%   |
| Micro Star International        | 3         | 0.16%   |
| MediaTek                        | 3         | 0.16%   |
| Alps Electric                   | 3         | 0.16%   |
| Edimax Technology               | 2         | 0.1%    |
| Opticis                         | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 356       | 18.63%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 131       | 6.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 95        | 4.97%   |
| Realtek Bluetooth Radio                             | 83        | 4.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 79        | 4.13%   |
| Ralink RT3290 Bluetooth                             | 68        | 3.56%   |
| Intel AX201 Bluetooth                               | 66        | 3.45%   |
| Dell DW375 Bluetooth Module                         | 40        | 2.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 2.04%   |
| Intel AX200 Bluetooth                               | 38        | 1.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 1.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 34        | 1.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 1.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 28        | 1.47%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.47%   |
| IMC Networks Bluetooth Device                       | 28        | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 1.36%   |
| Broadcom HP Portable SoftSailing                    | 24        | 1.26%   |
| Realtek RTL8723B Bluetooth                          | 22        | 1.15%   |
| IMC Networks Wireless_Device                        | 22        | 1.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.1%    |
| Lite-On Bluetooth Device                            | 21        | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.05%   |
| Realtek RTL8821A Bluetooth                          | 19        | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.99%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 0.63%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 0.63%   |
| Toshiba Bluetooth Device                            | 11        | 0.58%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.58%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 10        | 0.52%   |
| Intel Bluetooth Device                              | 9         | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2847      | 58.81%  |
| AMD                                  | 984       | 20.33%  |
| Nvidia                               | 696       | 14.38%  |
| C-Media Electronics                  | 83        | 1.71%   |
| Creative Labs                        | 40        | 0.83%   |
| Logitech                             | 19        | 0.39%   |
| VIA Technologies                     | 16        | 0.33%   |
| Texas Instruments                    | 15        | 0.31%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.29%   |
| ASUSTek Computer                     | 13        | 0.27%   |
| Generalplus Technology               | 12        | 0.25%   |
| Plantronics                          | 7         | 0.14%   |
| Kingston Technology                  | 7         | 0.14%   |
| JMTek                                | 7         | 0.14%   |
| Creative Technology                  | 7         | 0.14%   |
| BEHRINGER International              | 6         | 0.12%   |
| Lenovo                               | 5         | 0.1%    |
| SteelSeries ApS                      | 4         | 0.08%   |
| GN Netcom                            | 4         | 0.08%   |
| Samson Technologies                  | 3         | 0.06%   |
| Focusrite-Novation                   | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Tenx Technology                      | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| Realtek Semiconductor                | 2         | 0.04%   |
| Promethean Limited                   | 2         | 0.04%   |
| Hewlett-Packard                      | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |
| D&M Holdings (Denon/Marantz)         | 2         | 0.04%   |
| ATI Technologies                     | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| TEAC                                 | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Superlux digit                       | 1         | 0.02%   |
| Sunplus Technology                   | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |
| SM950T Microphone                    | 1         | 0.02%   |
| Scarlett                             | 1         | 0.02%   |
| Rotel                                | 1         | 0.02%   |
| Reloop                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 314       | 5.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 281       | 4.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 268       | 4.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 250       | 4.33%   |
| AMD FCH Azalia Controller                                                                         | 240       | 4.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 235       | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 198       | 3.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 196       | 3.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 187       | 3.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 148       | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 133       | 2.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 114       | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 99        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 98        | 1.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 95        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 94        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 89        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 88        | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 88        | 1.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 82        | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 77        | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 67        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 66        | 1.14%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 63        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 62        | 1.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 62        | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 58        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 57        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 56        | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 55        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 54        | 0.94%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 54        | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 50        | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 48        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 46        | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 46        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 45        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 44        | 0.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 43        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 706       | 19.66%  |
| SK hynix                   | 673       | 18.74%  |
| Unknown                    | 629       | 17.52%  |
| Kingston                   | 578       | 16.1%   |
| Micron Technology          | 297       | 8.27%   |
| Nanya Technology           | 107       | 2.98%   |
| Elpida                     | 83        | 2.31%   |
| Crucial                    | 76        | 2.12%   |
| Kingmax                    | 75        | 2.09%   |
| Corsair                    | 64        | 1.78%   |
| Ramaxel Technology         | 52        | 1.45%   |
| G.Skill                    | 50        | 1.39%   |
| A-DATA Technology          | 39        | 1.09%   |
| CSX                        | 18        | 0.5%    |
| Team                       | 14        | 0.39%   |
| Qimonda                    | 12        | 0.33%   |
| Patriot                    | 12        | 0.33%   |
| Transcend                  | 11        | 0.31%   |
| 48spaces                   | 10        | 0.28%   |
| ASint Technology           | 9         | 0.25%   |
| Unknown (ABCD)             | 8         | 0.22%   |
| Melco                      | 8         | 0.22%   |
| Kingmax Semiconductor      | 6         | 0.17%   |
| Apacer                     | 5         | 0.14%   |
| Toshiba                    | 4         | 0.11%   |
| OCZ                        | 4         | 0.11%   |
| GeIL                       | 4         | 0.11%   |
| Unknown                    | 4         | 0.11%   |
| Unknown (09D5)             | 2         | 0.06%   |
| Silicon Power              | 2         | 0.06%   |
| Intersil                   | 2         | 0.06%   |
| Infineon                   | 2         | 0.06%   |
| Hikvision                  | 2         | 0.06%   |
| H                          | 2         | 0.06%   |
| Golden Empire              | 2         | 0.06%   |
| ZION                       | 1         | 0.03%   |
| Unknown (8A5B)             | 1         | 0.03%   |
| Unknown (7F7F7F7F7F970000) | 1         | 0.03%   |
| Unigen                     | 1         | 0.03%   |
| Toshiba-0098               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3                | 44        | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 43        | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 40        | 1%      |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 37        | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 35        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s  | 34        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 34        | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 33        | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 30        | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 29        | 0.73%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s  | 26        | 0.65%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 0.63%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 23        | 0.58%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 22        | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 22        | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 22        | 0.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 21        | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s          | 21        | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 21        | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 20        | 0.5%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 20        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 19        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 19        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 19        | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 19        | 0.48%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s  | 18        | 0.45%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 18        | 0.45%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 17        | 0.43%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 17        | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 17        | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.4%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 16        | 0.4%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 16        | 0.4%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 15        | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.38%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 15        | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 13        | 0.33%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 13        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1415      | 46.03%  |
| DDR4    | 686       | 22.32%  |
| DDR2    | 400       | 13.01%  |
| SDRAM   | 230       | 7.48%   |
| Unknown | 187       | 6.08%   |
| DDR     | 59        | 1.92%   |
| LPDDR4  | 49        | 1.59%   |
| LPDDR3  | 21        | 0.68%   |
| DDR5    | 13        | 0.42%   |
| DRAM    | 9         | 0.29%   |
| LPDDR5  | 5         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1676      | 56.3%   |
| DIMM         | 1241      | 41.69%  |
| Row Of Chips | 48        | 1.61%   |
| Chip         | 8         | 0.27%   |
| RIMM         | 2         | 0.07%   |
| FB-DIMM      | 1         | 0.03%   |
| Unknown      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 1193      | 35.16%  |
| 2048    | 903       | 26.61%  |
| 8192    | 698       | 20.57%  |
| 1024    | 343       | 10.11%  |
| 16384   | 164       | 4.83%   |
| 512     | 53        | 1.56%   |
| 32768   | 33        | 0.97%   |
| 256     | 4         | 0.12%   |
| Unknown | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 864       | 25.44%  |
| 1333    | 315       | 9.28%   |
| 2667    | 262       | 7.71%   |
| 667     | 225       | 6.63%   |
| 800     | 217       | 6.39%   |
| 1334    | 186       | 5.48%   |
| 2400    | 168       | 4.95%   |
| 3200    | 143       | 4.21%   |
| Unknown | 142       | 4.18%   |
| 2133    | 115       | 3.39%   |
| 1067    | 90        | 2.65%   |
| 1866    | 67        | 1.97%   |
| 1867    | 55        | 1.62%   |
| 533     | 51        | 1.5%    |
| 1066    | 50        | 1.47%   |
| 2048    | 45        | 1.33%   |
| 4199    | 44        | 1.3%    |
| 3600    | 42        | 1.24%   |
| 400     | 35        | 1.03%   |
| 3266    | 20        | 0.59%   |
| 1800    | 19        | 0.56%   |
| 975     | 19        | 0.56%   |
| 1639    | 18        | 0.53%   |
| 333     | 14        | 0.41%   |
| 3466    | 12        | 0.35%   |
| 3400    | 12        | 0.35%   |
| 2933    | 12        | 0.35%   |
| 3000    | 11        | 0.32%   |
| 2666    | 11        | 0.32%   |
| 4267    | 9         | 0.27%   |
| 4266    | 9         | 0.27%   |
| 2000    | 9         | 0.27%   |
| 4800    | 8         | 0.24%   |
| 3151    | 8         | 0.24%   |
| 49926   | 7         | 0.21%   |
| 1648    | 7         | 0.21%   |
| 6400    | 5         | 0.15%   |
| 5808    | 5         | 0.15%   |
| 3733    | 5         | 0.15%   |
| 1400    | 5         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 58        | 47.93%  |
| Samsung Electronics   | 25        | 20.66%  |
| Canon                 | 14        | 11.57%  |
| Brother Industries    | 9         | 7.44%   |
| Seiko Epson           | 6         | 4.96%   |
| QinHeng Electronics   | 2         | 1.65%   |
| Lexmark International | 2         | 1.65%   |
| Xerox                 | 1         | 0.83%   |
| STMicroelectronics    | 1         | 0.83%   |
| Ricoh                 | 1         | 0.83%   |
| Prolific Technology   | 1         | 0.83%   |
| Oki Data              | 1         | 0.83%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 8         | 6.5%    |
| HP LaserJet 1020                                          | 6         | 4.88%   |
| Samsung ML-2010P Mono Laser Printer                       | 5         | 4.07%   |
| Samsung M2020 Series                                      | 5         | 4.07%   |
| Samsung ML-1640 Series Laser Printer                      | 4         | 3.25%   |
| HP DeskJet 2130 series                                    | 4         | 3.25%   |
| HP LaserJet P1005                                         | 3         | 2.44%   |
| HP LaserJet 1018                                          | 3         | 2.44%   |
| HP Deskjet 2050 J510                                      | 3         | 2.44%   |
| Canon LiDE 400                                            | 3         | 2.44%   |
| Brother HL-1110 series                                    | 3         | 2.44%   |
| Samsung SCX-3400 Series                                   | 2         | 1.63%   |
| QinHeng CH340S                                            | 2         | 1.63%   |
| HP Officejet J4500 series                                 | 2         | 1.63%   |
| HP LaserJet P1102                                         | 2         | 1.63%   |
| HP LaserJet 1022                                          | 2         | 1.63%   |
| HP LaserJet 1010                                          | 2         | 1.63%   |
| HP LaserJet 1000                                          | 2         | 1.63%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.63%   |
| HP Deskjet F2280 series                                   | 2         | 1.63%   |
| HP DeskJet F2100 Printer series                           | 2         | 1.63%   |
| HP DeskJet 840c                                           | 2         | 1.63%   |
| HP Deskjet 3520 series                                    | 2         | 1.63%   |
| Canon TS5100 series                                       | 2         | 1.63%   |
| Brother HL-L2300D series                                  | 2         | 1.63%   |
| Xerox WorkCentre 3119 Series                              | 1         | 0.81%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.81%   |
| Seiko Epson XP-240 Series                                 | 1         | 0.81%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.81%   |
| Seiko Epson Printer                                       | 1         | 0.81%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.81%   |
| Seiko Epson L396 Series                                   | 1         | 0.81%   |
| Seiko Epson L120 Series                                   | 1         | 0.81%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 0.81%   |
| Samsung SCX-4650 4x21S Series                             | 1         | 0.81%   |
| Samsung SCX-4623 Series                                   | 1         | 0.81%   |
| Samsung SCX-4200 series                                   | 1         | 0.81%   |
| Samsung ML-1660 Series                                    | 1         | 0.81%   |
| Samsung ML-1630 Series                                    | 1         | 0.81%   |
| Samsung Composite Device                                  | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 15        | 62.5%   |
| Hewlett-Packard                                | 3         | 12.5%   |
| Mustek Systems                                 | 2         | 8.33%   |
| UMAX                                           | 1         | 4.17%   |
| Siemens Information and Communication Products | 1         | 4.17%   |
| Seiko Epson                                    | 1         | 4.17%   |
| KYE Systems (Mouse Systems)                    | 1         | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                                              | 4         | 16.67%  |
| Canon CanoScan LIDE 25                                                          | 3         | 12.5%   |
| Canon CanoScan LiDE 110                                                         | 3         | 12.5%   |
| Mustek Systems SNAPSCAN e22                                                     | 2         | 8.33%   |
| HP Scanjet 300                                                                  | 2         | 8.33%   |
| Canon CanoScan LiDE 120                                                         | 2         | 8.33%   |
| UMAX Astra 4400/4450                                                            | 1         | 4.17%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 4.17%   |
| Seiko Epson Stylus Photo RX500/510                                              | 1         | 4.17%   |
| KYE Systems (Mouse Systems) ColorPage-SF600                                     | 1         | 4.17%   |
| HP ScanJet 3770                                                                 | 1         | 4.17%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 4.17%   |
| Canon CanoScan LiDE 100                                                         | 1         | 4.17%   |
| Canon CanoScan 4200F                                                            | 1         | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 505       | 24.51%  |
| Microdia                               | 203       | 9.85%   |
| IMC Networks                           | 201       | 9.76%   |
| Realtek Semiconductor                  | 168       | 8.16%   |
| Sunplus Innovation Technology          | 131       | 6.36%   |
| Bison Electronics                      | 92        | 4.47%   |
| Suyin                                  | 90        | 4.37%   |
| Quanta                                 | 76        | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 69        | 3.35%   |
| Logitech                               | 56        | 2.72%   |
| Syntek                                 | 53        | 2.57%   |
| Lite-On Technology                     | 36        | 1.75%   |
| Silicon Motion                         | 35        | 1.7%    |
| Lenovo                                 | 32        | 1.55%   |
| Acer                                   | 29        | 1.41%   |
| Z-Star Microelectronics                | 24        | 1.17%   |
| Alcor Micro                            | 23        | 1.12%   |
| Apple                                  | 21        | 1.02%   |
| Primax Electronics                     | 20        | 0.97%   |
| Ricoh                                  | 19        | 0.92%   |
| KYE Systems (Mouse Systems)            | 18        | 0.87%   |
| Microsoft                              | 17        | 0.83%   |
| GEMBIRD                                | 15        | 0.73%   |
| Samsung Electronics                    | 14        | 0.68%   |
| Luxvisions Innotech Limited            | 13        | 0.63%   |
| ALi                                    | 11        | 0.53%   |
| Sonix Technology                       | 10        | 0.49%   |
| Importek                               | 9         | 0.44%   |
| OmniVision Technologies                | 7         | 0.34%   |
| Trust                                  | 6         | 0.29%   |
| Arkmicro Technologies                  | 5         | 0.24%   |
| Pixart Imaging                         | 4         | 0.19%   |
| LG Electronics                         | 4         | 0.19%   |
| Generalplus Technology                 | 4         | 0.19%   |
| Aveo Technology                        | 4         | 0.19%   |
| MacroSilicon                           | 3         | 0.15%   |
| Jieli Technology                       | 3         | 0.15%   |
| DigiTech                               | 3         | 0.15%   |
| Cubeternet                             | 3         | 0.15%   |
| Creative Technology                    | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 61        | 2.95%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 58        | 2.8%    |
| Chicony HD WebCam                             | 47        | 2.27%   |
| Microdia Integrated_Webcam_HD                 | 46        | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam             | 44        | 2.13%   |
| Chicony HP Truevision HD                      | 40        | 1.93%   |
| Sunplus Integrated_Webcam_HD                  | 33        | 1.6%    |
| Chicony USB2.0 VGA UVC WebCam                 | 30        | 1.45%   |
| Realtek Integrated_Webcam_HD                  | 27        | 1.31%   |
| Bison Lenovo EasyCamera                       | 27        | 1.31%   |
| Microdia Integrated Webcam                    | 25        | 1.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 24        | 1.16%   |
| Sunplus HP Truevision HD                      | 24        | 1.16%   |
| Chicony Lenovo EasyCamera                     | 24        | 1.16%   |
| Sunplus HD WebCam                             | 23        | 1.11%   |
| Realtek USB Camera                            | 21        | 1.02%   |
| IMC Networks Integrated Camera                | 20        | 0.97%   |
| Logitech Webcam C270                          | 19        | 0.92%   |
| IMC Networks EasyCamera                       | 19        | 0.92%   |
| Chicony FJ Camera                             | 19        | 0.92%   |
| Microdia Sonix USB 2.0 Camera                 | 18        | 0.87%   |
| Lenovo Integrated Webcam                      | 18        | 0.87%   |
| Chicony VGA Webcam                            | 18        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                  | 18        | 0.87%   |
| Chicony Integrated HP HD Webcam               | 18        | 0.87%   |
| Chicony EasyCamera                            | 18        | 0.87%   |
| Quanta VGA Webcam                             | 17        | 0.82%   |
| Realtek Integrated Webcam                     | 16        | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 16        | 0.77%   |
| Microdia Camera                               | 15        | 0.73%   |
| Syntek Lenovo EasyCamera                      | 14        | 0.68%   |
| Syntek Integrated Camera                      | 14        | 0.68%   |
| Realtek Integrated Webcam HD                  | 14        | 0.68%   |
| Primax HP HD Webcam [Fixed]                   | 14        | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.68%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.68%   |
| Syntek EasyCamera                             | 13        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)       | 13        | 0.63%   |
| Realtek Lenovo EasyCamera                     | 13        | 0.63%   |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 107       | 36.39%  |
| AuthenTec                          | 56        | 19.05%  |
| Synaptics                          | 40        | 13.61%  |
| Upek                               | 28        | 9.52%   |
| Shenzhen Goodix Technology         | 22        | 7.48%   |
| LighTuning Technology              | 17        | 5.78%   |
| STMicroelectronics                 | 11        | 3.74%   |
| Elan Microelectronics              | 10        | 3.4%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.02%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 9.18%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.84%   |
| AuthenTec AES2810                                                          | 23        | 7.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 6.46%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 4.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 4.08%   |
| Validity Sensors VFS491                                                    | 11        | 3.74%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 3.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.72%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.04%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.04%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.04%   |
| Synaptics  WBDI                                                            | 5         | 1.7%    |
| AuthenTec AES1600                                                          | 5         | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.36%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.36%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.02%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.02%   |
| Synaptics WBDI                                                             | 3         | 1.02%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.02%   |
| Synaptics Fingerprint scanner                                              | 3         | 1.02%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.02%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.68%   |
| Synaptics UWP WBDI                                                         | 2         | 0.68%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.34%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.34%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.34%   |
| Synaptics WBDI Device                                                      | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 122       | 54.71%  |
| Alcor Micro               | 34        | 15.25%  |
| Lenovo                    | 29        | 13%     |
| O2 Micro                  | 27        | 12.11%  |
| Upek                      | 3         | 1.35%   |
| Gemalto (was Gemplus)     | 3         | 1.35%   |
| Yubico.com                | 1         | 0.45%   |
| Reiner SCT Kartensysteme  | 1         | 0.45%   |
| Chicony Electronics       | 1         | 0.45%   |
| Aladdin Knowledge Systems | 1         | 0.45%   |
| Advanced Card Systems     | 1         | 0.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 28.7%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 15.25%  |
| Lenovo Integrated Smart Card Reader                                          | 29        | 13%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 11.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 25        | 11.21%  |
| Broadcom 5880                                                                | 17        | 7.62%   |
| Broadcom 58200                                                               | 16        | 7.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.35%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.45%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.45%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.45%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.45%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.45%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.45%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.45%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2874      | 73.94%  |
| 1     | 849       | 21.84%  |
| 2     | 140       | 3.6%    |
| 3     | 16        | 0.41%   |
| 4     | 4         | 0.1%    |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.03%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 293       | 25.06%  |
| Graphics card            | 278       | 23.78%  |
| Chipcard                 | 205       | 17.54%  |
| Net/wireless             | 95        | 8.13%   |
| Bluetooth                | 80        | 6.84%   |
| Multimedia controller    | 49        | 4.19%   |
| Storage                  | 38        | 3.25%   |
| Communication controller | 37        | 3.17%   |
| Camera                   | 27        | 2.31%   |
| Flash memory             | 18        | 1.54%   |
| Unassigned class         | 11        | 0.94%   |
| Card reader              | 9         | 0.77%   |
| Sound                    | 8         | 0.68%   |
| Net/ethernet             | 6         | 0.51%   |
| Storage/raid             | 4         | 0.34%   |
| Dvb card                 | 3         | 0.26%   |
| Storage/ata              | 2         | 0.17%   |
| Network                  | 2         | 0.17%   |
| Modem                    | 2         | 0.17%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

