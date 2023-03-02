Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 2929

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | Notebook    | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Intel         | NUC7i3DNB J57625-510        | Mini pc     | [aedbb176f7](https://linux-hardware.org/?probe=aedbb176f7) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [ef74f90ec1](https://linux-hardware.org/?probe=ef74f90ec1) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| Samsung       | 930QED                      | Convertible | [9e03711ee7](https://linux-hardware.org/?probe=9e03711ee7) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | Notebook    | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | 8653 A                      | Desktop     | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| HP            | ProBook 4720s               | Notebook    | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0ca0b99aa3](https://linux-hardware.org/?probe=0ca0b99aa3) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | Notebook    | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [97335b8723](https://linux-hardware.org/?probe=97335b8723) | Jan 07, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | Desktop     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | Notebook    | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| Acer          | Predator G9-591             | Notebook    | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0b9972387e](https://linux-hardware.org/?probe=0b9972387e) | Jan 05, 2023 |
| Medion        | MS-7728                     | Desktop     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | Desktop     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [cc24dc6f72](https://linux-hardware.org/?probe=cc24dc6f72) | Dec 31, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [bf3922e95d](https://linux-hardware.org/?probe=bf3922e95d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [907ca44afe](https://linux-hardware.org/?probe=907ca44afe) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| ASUSTek       | PN64                        | Mini pc     | [a5fdbdb0c8](https://linux-hardware.org/?probe=a5fdbdb0c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [62986b3426](https://linux-hardware.org/?probe=62986b3426) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [439e89b31f](https://linux-hardware.org/?probe=439e89b31f) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| HP            | ENVY dv7                    | Notebook    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | Notebook    | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | Notebook    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | Notebook    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [8d37e3e327](https://linux-hardware.org/?probe=8d37e3e327) | Nov 29, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [e41751f26a](https://linux-hardware.org/?probe=e41751f26a) | Nov 29, 2022 |
| Notebook      | L140PU                      | Notebook    | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Pegatron      | VIOLET                      | Desktop     | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [b565b4082e](https://linux-hardware.org/?probe=b565b4082e) | Nov 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [90f931841d](https://linux-hardware.org/?probe=90f931841d) | Nov 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [111f6a1fc2](https://linux-hardware.org/?probe=111f6a1fc2) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | Notebook    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| HP            | 212B                        | Desktop     | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | Desktop     | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | Notebook    | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | Notebook    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c6c7120833](https://linux-hardware.org/?probe=c6c7120833) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ff7014b9b8](https://linux-hardware.org/?probe=ff7014b9b8) | Nov 06, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| HP            | 3396                        | Desktop     | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [9a540d96f5](https://linux-hardware.org/?probe=9a540d96f5) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c55b37c393](https://linux-hardware.org/?probe=c55b37c393) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b81dd63334](https://linux-hardware.org/?probe=b81dd63334) | Oct 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55a46537f8](https://linux-hardware.org/?probe=55a46537f8) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a83d0f0ade](https://linux-hardware.org/?probe=a83d0f0ade) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| HP            | 829A                        | Mini pc     | [3470bd9a76](https://linux-hardware.org/?probe=3470bd9a76) | Oct 17, 2022 |
| HP            | 829A                        | Mini pc     | [3ab01040ef](https://linux-hardware.org/?probe=3ab01040ef) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | Notebook    | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [9d2cf83f81](https://linux-hardware.org/?probe=9d2cf83f81) | Oct 12, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [feb997ebfc](https://linux-hardware.org/?probe=feb997ebfc) | Oct 12, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [10e153f71e](https://linux-hardware.org/?probe=10e153f71e) | Oct 10, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [7f03ff4490](https://linux-hardware.org/?probe=7f03ff4490) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [24da875cf7](https://linux-hardware.org/?probe=24da875cf7) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a5067b548](https://linux-hardware.org/?probe=6a5067b548) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2044c11c98](https://linux-hardware.org/?probe=2044c11c98) | Oct 02, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| MSI           | 2A9C                        | Desktop     | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [5e38213b3b](https://linux-hardware.org/?probe=5e38213b3b) | Sep 30, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [6c3ab0f793](https://linux-hardware.org/?probe=6c3ab0f793) | Sep 27, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3c87156766](https://linux-hardware.org/?probe=3c87156766) | Sep 25, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6f492f55c3](https://linux-hardware.org/?probe=6f492f55c3) | Sep 24, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [75ed13ea90](https://linux-hardware.org/?probe=75ed13ea90) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| HP            | 8053                        | Desktop     | [d46ac6d7db](https://linux-hardware.org/?probe=d46ac6d7db) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ec15390099](https://linux-hardware.org/?probe=ec15390099) | Sep 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [6c5483e3f5](https://linux-hardware.org/?probe=6c5483e3f5) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Dell          | 0GN6JF A01                  | Desktop     | [390fbaaca7](https://linux-hardware.org/?probe=390fbaaca7) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39faa4acc5](https://linux-hardware.org/?probe=39faa4acc5) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | Notebook    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| HP            | 2B36                        | Desktop     | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [8f0f345242](https://linux-hardware.org/?probe=8f0f345242) | Aug 28, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [9edb57e041](https://linux-hardware.org/?probe=9edb57e041) | Aug 28, 2022 |
| Acer          | V3-771                      | Notebook    | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Shuttle       | DS437                       | Notebook    | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| Unknown       | Unknown                     | All in one  | [da8e3c67be](https://linux-hardware.org/?probe=da8e3c67be) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| HP            | 2B36                        | Desktop     | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| HP            | 212B                        | Desktop     | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| Acer          | Predator G9-791             | Notebook    | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8a48025d15](https://linux-hardware.org/?probe=8a48025d15) | Aug 18, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [d0c25e4ba8](https://linux-hardware.org/?probe=d0c25e4ba8) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | Desktop     | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [98ea1068a3](https://linux-hardware.org/?probe=98ea1068a3) | Aug 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fee71ca4bf](https://linux-hardware.org/?probe=fee71ca4bf) | Aug 15, 2022 |
| Acer          | Aspire XC-605               | Desktop     | [125a8c791a](https://linux-hardware.org/?probe=125a8c791a) | Aug 14, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| HP            | Unknown                     | Notebook    | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7d2cd4cc35](https://linux-hardware.org/?probe=7d2cd4cc35) | Aug 11, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7e2bf60517](https://linux-hardware.org/?probe=7e2bf60517) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASUSTek       | H81T                        | Desktop     | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [49098497d4](https://linux-hardware.org/?probe=49098497d4) | Aug 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| ASRock        | 880GM-LE FX                 | Desktop     | [957edc332a](https://linux-hardware.org/?probe=957edc332a) | Aug 06, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [283eb3c040](https://linux-hardware.org/?probe=283eb3c040) | Aug 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [e82d9ce558](https://linux-hardware.org/?probe=e82d9ce558) | Jul 29, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| Lenovo        | ThinkPad T470s 20HGS36K0... | Notebook    | [caf10d48a0](https://linux-hardware.org/?probe=caf10d48a0) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| Lenovo        | ThinkPad P51 20HH001RMZ     | Notebook    | [3fee9267ba](https://linux-hardware.org/?probe=3fee9267ba) | Jul 27, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [c086eb22b3](https://linux-hardware.org/?probe=c086eb22b3) | Jul 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [44a5e2107e](https://linux-hardware.org/?probe=44a5e2107e) | Jul 27, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [5b5fe46f75](https://linux-hardware.org/?probe=5b5fe46f75) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a3e446c9e](https://linux-hardware.org/?probe=9a3e446c9e) | Jul 26, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [e8da564bb8](https://linux-hardware.org/?probe=e8da564bb8) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [e80a3e71e2](https://linux-hardware.org/?probe=e80a3e71e2) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Alienware     | 17 R5                       | Notebook    | [29b538f1c0](https://linux-hardware.org/?probe=29b538f1c0) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| HP            | 1998                        | Desktop     | [8aa7e05c70](https://linux-hardware.org/?probe=8aa7e05c70) | Jul 17, 2022 |
| Acer          | V3-771                      | Notebook    | [809bd80b9a](https://linux-hardware.org/?probe=809bd80b9a) | Jul 17, 2022 |
| Lenovo        | ThinkPad T410 25379UG       | Notebook    | [00478c63ba](https://linux-hardware.org/?probe=00478c63ba) | Jul 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [41c6118825](https://linux-hardware.org/?probe=41c6118825) | Jul 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f5982952c2](https://linux-hardware.org/?probe=f5982952c2) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2435f08ee8](https://linux-hardware.org/?probe=2435f08ee8) | Jul 10, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [0e5d573899](https://linux-hardware.org/?probe=0e5d573899) | Jul 09, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [3dc1d7b18a](https://linux-hardware.org/?probe=3dc1d7b18a) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [c58559e78c](https://linux-hardware.org/?probe=c58559e78c) | Jul 09, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ee1a040981](https://linux-hardware.org/?probe=ee1a040981) | Jul 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5819973ca4](https://linux-hardware.org/?probe=5819973ca4) | Jul 05, 2022 |
| MSI           | GE62 2QF                    | Notebook    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Medion        | MS-7667                     | Desktop     | [22ac257e4a](https://linux-hardware.org/?probe=22ac257e4a) | Jul 02, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [0d40af60b2](https://linux-hardware.org/?probe=0d40af60b2) | Jul 01, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a2729b2e3b](https://linux-hardware.org/?probe=a2729b2e3b) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| MSI           | 2A9C                        | Desktop     | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [800f6f5802](https://linux-hardware.org/?probe=800f6f5802) | Jun 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | Desktop     | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7c3f1cd4c1](https://linux-hardware.org/?probe=7c3f1cd4c1) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [5cde38b27f](https://linux-hardware.org/?probe=5cde38b27f) | Jun 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [6ec8ece12d](https://linux-hardware.org/?probe=6ec8ece12d) | Jun 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [d84600d5b0](https://linux-hardware.org/?probe=d84600d5b0) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Clevo         | W150ER                      | Notebook    | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [26c417012f](https://linux-hardware.org/?probe=26c417012f) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| HP            | 3032h                       | Desktop     | [fee76c58db](https://linux-hardware.org/?probe=fee76c58db) | Jun 09, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Shuttle       | DS10U                       | Desktop     | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d8134fd2fe](https://linux-hardware.org/?probe=d8134fd2fe) | Jun 02, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [1fb17fc133](https://linux-hardware.org/?probe=1fb17fc133) | Jun 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Minix         | NEO Z83-4A V1.1             | Desktop     | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | Notebook    | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [6c7cfb5226](https://linux-hardware.org/?probe=6c7cfb5226) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [41529bd0e1](https://linux-hardware.org/?probe=41529bd0e1) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [da6bd78cdb](https://linux-hardware.org/?probe=da6bd78cdb) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| Timi          | TM1613                      | Notebook    | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [da6b66b74f](https://linux-hardware.org/?probe=da6b66b74f) | May 21, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Acer          | V3-771                      | Notebook    | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [625d790cde](https://linux-hardware.org/?probe=625d790cde) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d8b886317a](https://linux-hardware.org/?probe=d8b886317a) | May 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [c682455b49](https://linux-hardware.org/?probe=c682455b49) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [ef6a65832f](https://linux-hardware.org/?probe=ef6a65832f) | May 13, 2022 |
| Shuttle       | DS10U                       | Desktop     | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| TUXEDO        | N2x0WU                      | Notebook    | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| ASUSTek       | GA35DX                      | Desktop     | [f604073d1f](https://linux-hardware.org/?probe=f604073d1f) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | Notebook    | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| HP            | 870C                        | Desktop     | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | Desktop     | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Khadas        | VIM3                        | Soc         | [c17309ec68](https://linux-hardware.org/?probe=c17309ec68) | May 04, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [878c361636](https://linux-hardware.org/?probe=878c361636) | May 01, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [920d1b35ab](https://linux-hardware.org/?probe=920d1b35ab) | Apr 30, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| Acer          | Predator G3620              | Desktop     | [556a67d50d](https://linux-hardware.org/?probe=556a67d50d) | Apr 28, 2022 |
| NF541         | 1.0                         | Desktop     | [c0999696b6](https://linux-hardware.org/?probe=c0999696b6) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [99b46394bf](https://linux-hardware.org/?probe=99b46394bf) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [475131a6f4](https://linux-hardware.org/?probe=475131a6f4) | Apr 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [19d81a0ef0](https://linux-hardware.org/?probe=19d81a0ef0) | Apr 22, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [cd9c2dd8f9](https://linux-hardware.org/?probe=cd9c2dd8f9) | Apr 22, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [597940fbe8](https://linux-hardware.org/?probe=597940fbe8) | Apr 22, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6495b55188](https://linux-hardware.org/?probe=6495b55188) | Apr 21, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | Notebook    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| HP            | 3048h                       | Desktop     | [b35df4ed74](https://linux-hardware.org/?probe=b35df4ed74) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| System76      | Galago Pro                  | Notebook    | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| HP            | 8298                        | Desktop     | [a9796ddd8d](https://linux-hardware.org/?probe=a9796ddd8d) | Apr 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8e46ef2a00](https://linux-hardware.org/?probe=8e46ef2a00) | Apr 13, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | Notebook    | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| Dell          | Latitude D400               | Notebook    | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| PC Engines    | apu4                        | Desktop     | [601866ecaa](https://linux-hardware.org/?probe=601866ecaa) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [36e8e44760](https://linux-hardware.org/?probe=36e8e44760) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [50d7c349cd](https://linux-hardware.org/?probe=50d7c349cd) | Apr 10, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [b160291e93](https://linux-hardware.org/?probe=b160291e93) | Apr 09, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [d56d880fd1](https://linux-hardware.org/?probe=d56d880fd1) | Apr 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e7d599e001](https://linux-hardware.org/?probe=e7d599e001) | Apr 01, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [52d7f90956](https://linux-hardware.org/?probe=52d7f90956) | Apr 01, 2022 |
| Acer          | Aspire E5-773G              | Notebook    | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| HP            | Pavilion g7                 | Notebook    | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [85f4e6ff91](https://linux-hardware.org/?probe=85f4e6ff91) | Mar 26, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a9df37f3f0](https://linux-hardware.org/?probe=a9df37f3f0) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a1a39d622b](https://linux-hardware.org/?probe=a1a39d622b) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [18294dd367](https://linux-hardware.org/?probe=18294dd367) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f51c0bb134](https://linux-hardware.org/?probe=f51c0bb134) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [9c78b8d68b](https://linux-hardware.org/?probe=9c78b8d68b) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [bf629bc1a5](https://linux-hardware.org/?probe=bf629bc1a5) | Mar 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [e89b5b2495](https://linux-hardware.org/?probe=e89b5b2495) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [52c0b45697](https://linux-hardware.org/?probe=52c0b45697) | Mar 14, 2022 |
| Dell          | Latitude 5400               | Notebook    | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [f56d8f0fe4](https://linux-hardware.org/?probe=f56d8f0fe4) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [f4f7ab1aaf](https://linux-hardware.org/?probe=f4f7ab1aaf) | Mar 12, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| HP            | 806A                        | Desktop     | [60d334dbf5](https://linux-hardware.org/?probe=60d334dbf5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [566eee23f5](https://linux-hardware.org/?probe=566eee23f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [0046299935](https://linux-hardware.org/?probe=0046299935) | Mar 10, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [af17a2da6b](https://linux-hardware.org/?probe=af17a2da6b) | Mar 05, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [95d4a7b220](https://linux-hardware.org/?probe=95d4a7b220) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [7d5295d845](https://linux-hardware.org/?probe=7d5295d845) | Mar 03, 2022 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [ee54bb96c5](https://linux-hardware.org/?probe=ee54bb96c5) | Mar 03, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| HP            | 8592                        | Desktop     | [a34dbdb173](https://linux-hardware.org/?probe=a34dbdb173) | Mar 01, 2022 |
| Medion        | P6624                       | Notebook    | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [e996ec20ea](https://linux-hardware.org/?probe=e996ec20ea) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | Notebook    | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | Notebook    | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | Notebook    | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [98a6706e6a](https://linux-hardware.org/?probe=98a6706e6a) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b5b236f76](https://linux-hardware.org/?probe=1b5b236f76) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [0ab1ff409b](https://linux-hardware.org/?probe=0ab1ff409b) | Feb 20, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [40f1930253](https://linux-hardware.org/?probe=40f1930253) | Feb 19, 2022 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [6baa824f3a](https://linux-hardware.org/?probe=6baa824f3a) | Feb 17, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [1055dc7082](https://linux-hardware.org/?probe=1055dc7082) | Feb 14, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [91dbebb5dd](https://linux-hardware.org/?probe=91dbebb5dd) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [4583e687ca](https://linux-hardware.org/?probe=4583e687ca) | Feb 13, 2022 |
| HP            | Compaq 15                   | Notebook    | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c5b6cfb8bc](https://linux-hardware.org/?probe=c5b6cfb8bc) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [6312e054ab](https://linux-hardware.org/?probe=6312e054ab) | Feb 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [b32b83ff4b](https://linux-hardware.org/?probe=b32b83ff4b) | Feb 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b8a4437ef8](https://linux-hardware.org/?probe=b8a4437ef8) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | Notebook    | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [da25fcadb3](https://linux-hardware.org/?probe=da25fcadb3) | Feb 09, 2022 |
| HP            | 18E5                        | Desktop     | [85267de714](https://linux-hardware.org/?probe=85267de714) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | Notebook    | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [59a8e93ae4](https://linux-hardware.org/?probe=59a8e93ae4) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| ZOTAC         | ZBOXNANO-ID67               | Mini pc     | [7eab522138](https://linux-hardware.org/?probe=7eab522138) | Feb 05, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [091a9c467d](https://linux-hardware.org/?probe=091a9c467d) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [7ff1fc83fc](https://linux-hardware.org/?probe=7ff1fc83fc) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [dde47afaff](https://linux-hardware.org/?probe=dde47afaff) | Feb 03, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [03f9d9de62](https://linux-hardware.org/?probe=03f9d9de62) | Jan 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [08a04a280f](https://linux-hardware.org/?probe=08a04a280f) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [31a1c1d4ab](https://linux-hardware.org/?probe=31a1c1d4ab) | Jan 28, 2022 |
| Clevo         | W76x/M77xCUH                | Notebook    | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f5b79eabf](https://linux-hardware.org/?probe=5f5b79eabf) | Jan 25, 2022 |
| AMI           | Cherry Trail Tablet         | Notebook    | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [055decea61](https://linux-hardware.org/?probe=055decea61) | Jan 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [db3a3ddae1](https://linux-hardware.org/?probe=db3a3ddae1) | Jan 23, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a934945d5](https://linux-hardware.org/?probe=7a934945d5) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cf8776e11f](https://linux-hardware.org/?probe=cf8776e11f) | Jan 22, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4a0bd17330](https://linux-hardware.org/?probe=4a0bd17330) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c528c04bb7](https://linux-hardware.org/?probe=c528c04bb7) | Jan 22, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [328e103a74](https://linux-hardware.org/?probe=328e103a74) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0bb120993f](https://linux-hardware.org/?probe=0bb120993f) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [4b8a587819](https://linux-hardware.org/?probe=4b8a587819) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [d897de368d](https://linux-hardware.org/?probe=d897de368d) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| HP            | 3048h                       | Desktop     | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d508a12888](https://linux-hardware.org/?probe=d508a12888) | Jan 15, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2d14961843](https://linux-hardware.org/?probe=2d14961843) | Jan 14, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [0c991d9fae](https://linux-hardware.org/?probe=0c991d9fae) | Jan 14, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [88396d099b](https://linux-hardware.org/?probe=88396d099b) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0eb5cecbac](https://linux-hardware.org/?probe=0eb5cecbac) | Jan 12, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [bb65153cf2](https://linux-hardware.org/?probe=bb65153cf2) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [102e1371f8](https://linux-hardware.org/?probe=102e1371f8) | Jan 11, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [0c0a6589e8](https://linux-hardware.org/?probe=0c0a6589e8) | Jan 11, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [2cbbce1a0e](https://linux-hardware.org/?probe=2cbbce1a0e) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [993e94e5fd](https://linux-hardware.org/?probe=993e94e5fd) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [c908574f83](https://linux-hardware.org/?probe=c908574f83) | Jan 09, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [aad9837ee4](https://linux-hardware.org/?probe=aad9837ee4) | Jan 08, 2022 |
| Acer          | Aspire R7-572G              | Notebook    | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | Notebook    | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad5ae136c9](https://linux-hardware.org/?probe=ad5ae136c9) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| MSI           | 2A9Ch                       | Desktop     | [358b325347](https://linux-hardware.org/?probe=358b325347) | Jan 05, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [843345dfe6](https://linux-hardware.org/?probe=843345dfe6) | Jan 04, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [9980b9fb17](https://linux-hardware.org/?probe=9980b9fb17) | Jan 04, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [bb8b56ca21](https://linux-hardware.org/?probe=bb8b56ca21) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [6a1f7a20cf](https://linux-hardware.org/?probe=6a1f7a20cf) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [bd7de25478](https://linux-hardware.org/?probe=bd7de25478) | Jan 02, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [48524c94d1](https://linux-hardware.org/?probe=48524c94d1) | Jan 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c4103c8737](https://linux-hardware.org/?probe=c4103c8737) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [2e51628103](https://linux-hardware.org/?probe=2e51628103) | Dec 30, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | Notebook    | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1c36b4c1cd](https://linux-hardware.org/?probe=1c36b4c1cd) | Dec 29, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [997c8caab6](https://linux-hardware.org/?probe=997c8caab6) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | Notebook    | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| Gigabyte      | H55M-USB3                   | Desktop     | [6ae95f862e](https://linux-hardware.org/?probe=6ae95f862e) | Dec 28, 2021 |
| Intel         | MONTARA                     | Desktop     | [963db2e79c](https://linux-hardware.org/?probe=963db2e79c) | Dec 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [41edb1b55b](https://linux-hardware.org/?probe=41edb1b55b) | Dec 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a940c31cf7](https://linux-hardware.org/?probe=a940c31cf7) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [1afb1306eb](https://linux-hardware.org/?probe=1afb1306eb) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | Notebook    | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f113b07c3e](https://linux-hardware.org/?probe=f113b07c3e) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [527037fe8b](https://linux-hardware.org/?probe=527037fe8b) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0f19f19470](https://linux-hardware.org/?probe=0f19f19470) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Shuttle       | FZ87                        | Desktop     | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | Desktop     | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [d2ce6b29f7](https://linux-hardware.org/?probe=d2ce6b29f7) | Dec 23, 2021 |
| HP            | 3048h                       | Desktop     | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| HP            | ProBook 4740s               | Notebook    | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [da59408c08](https://linux-hardware.org/?probe=da59408c08) | Dec 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [72ba2d0d17](https://linux-hardware.org/?probe=72ba2d0d17) | Dec 22, 2021 |
| Lenovo        | 3176 SDK0J40697 WIN 3305... | Desktop     | [7ffa31df44](https://linux-hardware.org/?probe=7ffa31df44) | Dec 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [711a930635](https://linux-hardware.org/?probe=711a930635) | Dec 20, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [aa65cbb14e](https://linux-hardware.org/?probe=aa65cbb14e) | Dec 19, 2021 |
| HP            | 8056                        | Desktop     | [68992da248](https://linux-hardware.org/?probe=68992da248) | Dec 19, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [60db65ec3a](https://linux-hardware.org/?probe=60db65ec3a) | Dec 19, 2021 |
| HP            | 18E4                        | Desktop     | [b4a1d6b778](https://linux-hardware.org/?probe=b4a1d6b778) | Dec 19, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [3e25d6dd20](https://linux-hardware.org/?probe=3e25d6dd20) | Dec 18, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | Notebook    | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | Notebook    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [2d145ac87e](https://linux-hardware.org/?probe=2d145ac87e) | Dec 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c821efaed8](https://linux-hardware.org/?probe=c821efaed8) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [4fdfe223e0](https://linux-hardware.org/?probe=4fdfe223e0) | Dec 13, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [7abd85fdc5](https://linux-hardware.org/?probe=7abd85fdc5) | Dec 12, 2021 |
| ZOTAC         | ZBOX-EN1070/1060 Rev.00     | Mini pc     | [7348d34142](https://linux-hardware.org/?probe=7348d34142) | Dec 12, 2021 |
| HP            | 871A                        | Mini pc     | [fdbb17d3b2](https://linux-hardware.org/?probe=fdbb17d3b2) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | Notebook    | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [663a79c9de](https://linux-hardware.org/?probe=663a79c9de) | Dec 11, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [4166d874cc](https://linux-hardware.org/?probe=4166d874cc) | Dec 11, 2021 |
| ASRock        | B560M-HDV                   | Desktop     | [6390e2db9b](https://linux-hardware.org/?probe=6390e2db9b) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [892d6ba035](https://linux-hardware.org/?probe=892d6ba035) | Dec 09, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [64c5154edc](https://linux-hardware.org/?probe=64c5154edc) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [ca6047ef7c](https://linux-hardware.org/?probe=ca6047ef7c) | Dec 06, 2021 |
| HP            | ENVY dv7                    | Notebook    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [6a2129aabd](https://linux-hardware.org/?probe=6a2129aabd) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | Notebook    | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [585c81c884](https://linux-hardware.org/?probe=585c81c884) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [0e777fade8](https://linux-hardware.org/?probe=0e777fade8) | Dec 03, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e2e7015852](https://linux-hardware.org/?probe=e2e7015852) | Dec 03, 2021 |
| Unknown       | 1.0                         | Desktop     | [412614529f](https://linux-hardware.org/?probe=412614529f) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74dcac77ec](https://linux-hardware.org/?probe=74dcac77ec) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [9bbe9ad940](https://linux-hardware.org/?probe=9bbe9ad940) | Nov 27, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [3b55838cb6](https://linux-hardware.org/?probe=3b55838cb6) | Nov 27, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b7cb8d0193](https://linux-hardware.org/?probe=b7cb8d0193) | Nov 27, 2021 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b1147db572](https://linux-hardware.org/?probe=b1147db572) | Nov 27, 2021 |
| MSI           | MS-17G                      | Notebook    | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | Notebook    | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [51d432b698](https://linux-hardware.org/?probe=51d432b698) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [6c1248588e](https://linux-hardware.org/?probe=6c1248588e) | Nov 24, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [4ae4bcc876](https://linux-hardware.org/?probe=4ae4bcc876) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [2fbb75de6f](https://linux-hardware.org/?probe=2fbb75de6f) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [c70684a5e6](https://linux-hardware.org/?probe=c70684a5e6) | Nov 24, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0a637eba53](https://linux-hardware.org/?probe=0a637eba53) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [4c05633d40](https://linux-hardware.org/?probe=4c05633d40) | Nov 22, 2021 |
| HP            | Notebook                    | Notebook    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | Notebook    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ec72611685](https://linux-hardware.org/?probe=ec72611685) | Nov 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 294       | 14.24%  |
| Ubuntu 18.04                 | 271       | 13.13%  |
| Ubuntu 22.04                 | 85        | 4.12%   |
| Debian 11                    | 78        | 3.78%   |
| Linux Mint 20.3              | 50        | 2.42%   |
| OpenMandriva 4.3             | 42        | 2.03%   |
| Debian 10                    | 40        | 1.94%   |
| Ubuntu 21.10                 | 38        | 1.84%   |
| Linux Mint 20.1              | 36        | 1.74%   |
| KDE neon 20.04               | 36        | 1.74%   |
| Linux Mint 20.2              | 35        | 1.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 30        | 1.45%   |
| OpenMandriva 4.2             | 30        | 1.45%   |
| Arch Rolling                 | 28        | 1.36%   |
| Arch                         | 28        | 1.36%   |
| Zorin 16                     | 25        | 1.21%   |
| Ubuntu 20.10                 | 25        | 1.21%   |
| Pop!_OS 22.04                | 24        | 1.16%   |
| Fedora 32                    | 24        | 1.16%   |
| Ubuntu 21.04                 | 22        | 1.07%   |
| Ubuntu 19.10                 | 21        | 1.02%   |
| Pop!_OS 21.04                | 21        | 1.02%   |
| Pop!_OS 20.04                | 21        | 1.02%   |
| Fedora 33                    | 21        | 1.02%   |
| Ubuntu 19.04                 | 20        | 0.97%   |
| Pop!_OS 20.10                | 20        | 0.97%   |
| Manjaro                      | 20        | 0.97%   |
| Fedora 35                    | 20        | 0.97%   |
| Fedora 34                    | 20        | 0.97%   |
| ArcoLinux Rolling            | 20        | 0.97%   |
| OpenMandriva 23.01           | 19        | 0.92%   |
| Linux Mint 19.3              | 18        | 0.87%   |
| Ubuntu 22.10                 | 17        | 0.82%   |
| Fedora 37                    | 16        | 0.78%   |
| Fedora 36                    | 16        | 0.78%   |
| Zorin 15                     | 15        | 0.73%   |
| Kubuntu 20.04                | 15        | 0.73%   |
| Linux Mint 20                | 14        | 0.68%   |
| Linux Mint 21                | 13        | 0.63%   |
| Fedora 31                    | 13        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 752       | 39.04%  |
| Linux Mint    | 164       | 8.52%   |
| Debian        | 143       | 7.42%   |
| Fedora        | 123       | 6.39%   |
| OpenMandriva  | 103       | 5.35%   |
| Pop!_OS       | 87        | 4.52%   |
| Manjaro       | 60        | 3.12%   |
| Arch          | 55        | 2.86%   |
| Kubuntu       | 43        | 2.23%   |
| KDE neon      | 41        | 2.13%   |
| Zorin         | 40        | 2.08%   |
| openSUSE      | 39        | 2.02%   |
| ROSA          | 25        | 1.3%    |
| ArcoLinux     | 23        | 1.19%   |
| Xubuntu       | 19        | 0.99%   |
| Ubuntu MATE   | 17        | 0.88%   |
| Gentoo        | 16        | 0.83%   |
| Kali          | 15        | 0.78%   |
| Elementary    | 14        | 0.73%   |
| Lubuntu       | 13        | 0.67%   |
| CentOS        | 12        | 0.62%   |
| Ubuntu Budgie | 10        | 0.52%   |
| Feren OS      | 10        | 0.52%   |
| Clear Linux   | 8         | 0.42%   |
| Ubuntu Unity  | 7         | 0.36%   |
| LMDE          | 7         | 0.36%   |
| Endless       | 7         | 0.36%   |
| EndeavourOS   | 7         | 0.36%   |
| BlackPanther  | 7         | 0.36%   |
| MX            | 6         | 0.31%   |
| RHEL          | 4         | 0.21%   |
| Artix         | 4         | 0.21%   |
| Void Linux    | 3         | 0.16%   |
| Virtuozzo     | 3         | 0.16%   |
| Solus         | 3         | 0.16%   |
| NixOS         | 3         | 0.16%   |
| Garuda Linux  | 3         | 0.16%   |
| Ubuntu Studio | 2         | 0.1%    |
| Q4OS          | 2         | 0.1%    |
| PCS           | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.9%    |
| 5.16.7-desktop-1omv4003  | 38        | 1.64%   |
| 5.4.0-42-generic         | 32        | 1.38%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.25%   |
| 4.15.0-91-generic        | 27        | 1.17%   |
| 5.15.0-56-generic        | 25        | 1.08%   |
| 5.4.0-52-generic         | 22        | 0.95%   |
| 5.4.0-48-generic         | 22        | 0.95%   |
| 4.15.0-96-generic        | 22        | 0.95%   |
| 5.4.0-58-generic         | 21        | 0.91%   |
| 6.1.1-desktop-1omv2290   | 17        | 0.73%   |
| 5.15.0-46-generic        | 17        | 0.73%   |
| 5.10.0-8-arm64           | 17        | 0.73%   |
| 5.15.0-58-generic        | 16        | 0.69%   |
| 5.8.0-43-generic         | 15        | 0.65%   |
| 5.4.0-91-generic         | 15        | 0.65%   |
| 5.13.0-35-generic        | 14        | 0.6%    |
| 5.4.0-80-generic         | 13        | 0.56%   |
| 5.4.0-26-generic         | 13        | 0.56%   |
| 5.15.0-52-generic        | 13        | 0.56%   |
| 5.11.0-43-generic        | 13        | 0.56%   |
| 5.11.0-27-generic        | 13        | 0.56%   |
| 5.4.0-81-generic         | 12        | 0.52%   |
| 5.4.0-47-generic         | 12        | 0.52%   |
| 5.15.0-48-generic        | 12        | 0.52%   |
| 5.13.0-39-generic        | 12        | 0.52%   |
| 5.13.0-30-generic        | 12        | 0.52%   |
| 5.10.0-8-amd64           | 12        | 0.52%   |
| 5.0.0-37-generic         | 12        | 0.52%   |
| 5.8.0-55-generic         | 11        | 0.47%   |
| 5.8.0-53-generic         | 11        | 0.47%   |
| 5.8.0-48-generic         | 11        | 0.47%   |
| 5.8.0-44-generic         | 11        | 0.47%   |
| 5.4.0-72-generic         | 11        | 0.47%   |
| 5.4.0-66-generic         | 11        | 0.47%   |
| 5.15.0-60-generic        | 11        | 0.47%   |
| 5.8.0-59-generic         | 10        | 0.43%   |
| 5.4.0-70-generic         | 10        | 0.43%   |
| 5.4.0-65-generic         | 10        | 0.43%   |
| 5.4.0-37-generic         | 10        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 367       | 17.04%  |
| 4.15.0  | 205       | 9.52%   |
| 5.15.0  | 163       | 7.57%   |
| 5.8.0   | 127       | 5.9%    |
| 5.11.0  | 117       | 5.43%   |
| 5.13.0  | 104       | 4.83%   |
| 5.10.0  | 83        | 3.85%   |
| 5.3.0   | 72        | 3.34%   |
| 5.0.0   | 50        | 2.32%   |
| 4.18.0  | 41        | 1.9%    |
| 5.16.7  | 39        | 1.81%   |
| 4.19.0  | 37        | 1.72%   |
| 5.10.14 | 30        | 1.39%   |
| 5.19.0  | 29        | 1.35%   |
| 6.1.1   | 21        | 0.97%   |
| 5.14.0  | 15        | 0.7%    |
| 5.17.5  | 13        | 0.6%    |
| 5.6.0   | 11        | 0.51%   |
| 6.0.0   | 10        | 0.46%   |
| 5.7.0   | 9         | 0.42%   |
| 5.18.0  | 9         | 0.42%   |
| 3.10.0  | 8         | 0.37%   |
| 5.16.13 | 7         | 0.32%   |
| 5.10.7  | 7         | 0.32%   |
| 4.9.60  | 7         | 0.32%   |
| 6.0.15  | 6         | 0.28%   |
| 6.0.12  | 6         | 0.28%   |
| 5.6.14  | 6         | 0.28%   |
| 5.16.0  | 6         | 0.28%   |
| 4.18.16 | 6         | 0.28%   |
| 6.1.0   | 5         | 0.23%   |
| 5.9.16  | 5         | 0.23%   |
| 5.9.11  | 5         | 0.23%   |
| 5.7.1   | 5         | 0.23%   |
| 5.6.15  | 5         | 0.23%   |
| 5.3.18  | 5         | 0.23%   |
| 5.15.5  | 5         | 0.23%   |
| 5.14.14 | 5         | 0.23%   |
| 5.11.2  | 5         | 0.23%   |
| 5.11.16 | 5         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 386       | 18.24%  |
| 5.15    | 213       | 10.07%  |
| 4.15    | 206       | 9.74%   |
| 5.8     | 160       | 7.56%   |
| 5.10    | 153       | 7.23%   |
| 5.11    | 146       | 6.9%    |
| 5.13    | 121       | 5.72%   |
| 5.3     | 84        | 3.97%   |
| 5.16    | 74        | 3.5%    |
| 5.0     | 55        | 2.6%    |
| 4.18    | 49        | 2.32%   |
| 4.19    | 44        | 2.08%   |
| 6.0     | 43        | 2.03%   |
| 5.19    | 42        | 1.98%   |
| 5.6     | 41        | 1.94%   |
| 6.1     | 37        | 1.75%   |
| 5.14    | 36        | 1.7%    |
| 5.17    | 35        | 1.65%   |
| 5.9     | 29        | 1.37%   |
| 5.7     | 29        | 1.37%   |
| 5.18    | 28        | 1.32%   |
| 5.12    | 25        | 1.18%   |
| 4.9     | 23        | 1.09%   |
| 5.5     | 11        | 0.52%   |
| 3.10    | 8         | 0.38%   |
| 4.4     | 5         | 0.24%   |
| 4.14    | 4         | 0.19%   |
| 5.2     | 3         | 0.14%   |
| 4.20    | 3         | 0.14%   |
| 4.13    | 3         | 0.14%   |
| 4.1     | 3         | 0.14%   |
| 2.6     | 3         | 0.14%   |
| 6.2     | 2         | 0.09%   |
| 4.10    | 2         | 0.09%   |
| 3.16    | 2         | 0.09%   |
| 5.1     | 1         | 0.05%   |
| 5       | 1         | 0.05%   |
| 4.2     | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.12    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1790      | 96.29%  |
| aarch64 | 36        | 1.94%   |
| i686    | 31        | 1.67%   |
| armv8l  | 1         | 0.05%   |
| armv7l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 775       | 39.85%  |
| Unknown         | 295       | 15.17%  |
| KDE5            | 285       | 14.65%  |
| X-Cinnamon      | 132       | 6.79%   |
| GNUstep         | 113       | 5.81%   |
| XFCE            | 90        | 4.63%   |
| MATE            | 48        | 2.47%   |
| KDE             | 43        | 2.21%   |
| Cinnamon        | 32        | 1.65%   |
| LXQt            | 19        | 0.98%   |
| KDE4            | 16        | 0.82%   |
| Pantheon        | 15        | 0.77%   |
| Budgie          | 15        | 0.77%   |
| LXDE            | 14        | 0.72%   |
| i3              | 13        | 0.67%   |
| GNOME Flashback | 11        | 0.57%   |
| Unity           | 6         | 0.31%   |
| bspwm           | 5         | 0.26%   |
| qtile           | 4         | 0.21%   |
| Trinity         | 2         | 0.1%    |
| sway            | 2         | 0.1%    |
| GNOME Classic   | 2         | 0.1%    |
| DWM             | 2         | 0.1%    |
| xmonad          | 1         | 0.05%   |
| openbox         | 1         | 0.05%   |
| none+awesome    | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| herbstluftwm    | 1         | 0.05%   |
| fluxbox         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1382      | 71.2%   |
| Wayland | 314       | 16.18%  |
| Unknown | 167       | 8.6%    |
| Tty     | 75        | 3.86%   |
| Web     | 3         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 857       | 43.99%  |
| LightDM | 317       | 16.27%  |
| SDDM    | 255       | 13.09%  |
| GDM     | 247       | 12.68%  |
| GDM3    | 168       | 8.62%   |
| TDM     | 80        | 4.11%   |
| KDM     | 15        | 0.77%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 3         | 0.15%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 624       | 32.48%  |
| de_CH      | 444       | 23.11%  |
| Unknown    | 348       | 18.12%  |
| fr_CH      | 131       | 6.82%   |
| de_DE      | 116       | 6.04%   |
| en_GB      | 79        | 4.11%   |
| fr_FR      | 40        | 2.08%   |
| C          | 38        | 1.98%   |
| pt_PT      | 17        | 0.88%   |
| it_CH      | 17        | 0.88%   |
| it_IT      | 14        | 0.73%   |
| es_ES      | 7         | 0.36%   |
| ru_RU      | 6         | 0.31%   |
| pl_PL      | 6         | 0.31%   |
| en_CH      | 6         | 0.31%   |
| en_AU      | 4         | 0.21%   |
| POSIX      | 3         | 0.16%   |
| en_IE      | 3         | 0.16%   |
| de_AT      | 3         | 0.16%   |
| en_CA      | 2         | 0.1%    |
| tr_TR      | 1         | 0.05%   |
| sk_SK      | 1         | 0.05%   |
| ru_UA      | 1         | 0.05%   |
| nl_BE      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| gsw_CH     | 1         | 0.05%   |
| en_AG      | 1         | 0.05%   |
| de_LI      | 1         | 0.05%   |
| de_IT      | 1         | 0.05%   |
| de_CH.UTF8 | 1         | 0.05%   |
| cs_CZ      | 1         | 0.05%   |
| ca_ES      | 1         | 0.05%   |
| C.UTF8     | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1021      | 53.91%  |
| BIOS | 873       | 46.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1504      | 79.24%  |
| Btrfs   | 139       | 7.32%   |
| Overlay | 125       | 6.59%   |
| Unknown | 64        | 3.37%   |
| Xfs     | 38        | 2%      |
| Zfs     | 12        | 0.63%   |
| Ext2    | 6         | 0.32%   |
| F2fs    | 4         | 0.21%   |
| Ext3    | 3         | 0.16%   |
| Jfs     | 1         | 0.05%   |
| ExX4    | 1         | 0.05%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 880       | 46.32%  |
| GPT     | 800       | 42.11%  |
| MBR     | 220       | 11.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1596      | 84.09%  |
| Yes       | 302       | 15.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1418      | 74.91%  |
| Yes       | 475       | 25.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 325       | 17.5%   |
| ASUSTek Computer        | 315       | 16.96%  |
| Lenovo                  | 298       | 16.05%  |
| Dell                    | 148       | 7.97%   |
| Acer                    | 109       | 5.87%   |
| Gigabyte Technology     | 87        | 4.68%   |
| Apple                   | 67        | 3.61%   |
| MSI                     | 63        | 3.39%   |
| Intel                   | 63        | 3.39%   |
| ASRock                  | 55        | 2.96%   |
| Fujitsu                 | 34        | 1.83%   |
| Raspberry Pi Foundation | 31        | 1.67%   |
| Medion                  | 25        | 1.35%   |
| Supermicro              | 19        | 1.02%   |
| Toshiba                 | 17        | 0.92%   |
| Sony                    | 13        | 0.7%    |
| Microsoft               | 13        | 0.7%    |
| TUXEDO                  | 12        | 0.65%   |
| Samsung Electronics     | 11        | 0.59%   |
| Notebook                | 11        | 0.59%   |
| Unknown                 | 11        | 0.59%   |
| Shuttle                 | 9         | 0.48%   |
| HUAWEI                  | 9         | 0.48%   |
| ZOTAC                   | 8         | 0.43%   |
| TrekStor                | 7         | 0.38%   |
| Pegatron                | 7         | 0.38%   |
| PC Engines              | 7         | 0.38%   |
| Razer                   | 6         | 0.32%   |
| DALCO AG Switzerland    | 6         | 0.32%   |
| Packard Bell            | 5         | 0.27%   |
| Alienware               | 5         | 0.27%   |
| Schenker                | 4         | 0.22%   |
| GPD                     | 3         | 0.16%   |
| Clevo                   | 3         | 0.16%   |
| Biostar                 | 3         | 0.16%   |
| AMI                     | 3         | 0.16%   |
| whyopencomputing        | 2         | 0.11%   |
| Timi                    | 2         | 0.11%   |
| System76                | 2         | 0.11%   |
| PC Specialist           | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 32        | 1.72%   |
| Unknown                                    | 18        | 0.97%   |
| Fujitsu CELSIUS_W550                       | 12        | 0.65%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 9         | 0.48%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 8         | 0.43%   |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 8         | 0.43%   |
| HP Pavilion dv7                            | 8         | 0.43%   |
| ASUS ROG STRIX X570-E GAMING               | 8         | 0.43%   |
| ASUS STRIX Z270F GAMING                    | 7         | 0.38%   |
| ASUS P9X79 WS                              | 7         | 0.38%   |
| ASUS P8Z77-V LX                            | 7         | 0.38%   |
| MSI MS-7C02                                | 6         | 0.32%   |
| Microsoft Surface Pro 4                    | 6         | 0.32%   |
| DALCO AG Switzerland +41 44 908 38 38      | 6         | 0.32%   |
| PC Engines APU2                            | 5         | 0.27%   |
| Intel DP67BA AAG10219-303                  | 5         | 0.27%   |
| HP Pavilion dv6                            | 5         | 0.27%   |
| HP Notebook                                | 5         | 0.27%   |
| HP ENVY 15                                 | 5         | 0.27%   |
| HP EliteDesk 800 G1 SFF                    | 5         | 0.27%   |
| Dell XPS 15 9570                           | 5         | 0.27%   |
| Dell Latitude E7240                        | 5         | 0.27%   |
| Dell Latitude 7490                         | 5         | 0.27%   |
| ASUS ROG STRIX Z370-F GAMING               | 5         | 0.27%   |
| Apple iMac8,1                              | 5         | 0.27%   |
| Apple iMac12,2                             | 5         | 0.27%   |
| Supermicro X8DTN+-F                        | 4         | 0.22%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.22%   |
| Lenovo MIIX 310-10ICR 80SG                 | 4         | 0.22%   |
| Intel S4600LH                              | 4         | 0.22%   |
| Intel NUC8i7BEH                            | 4         | 0.22%   |
| Intel DP55WB AAE64798-207                  | 4         | 0.22%   |
| HP ProBook 440 G8 Notebook PC              | 4         | 0.22%   |
| HP Pavilion g7                             | 4         | 0.22%   |
| HP Laptop 15-bs1xx                         | 4         | 0.22%   |
| HP ENVY x360 Convertible 15-ee0xxx         | 4         | 0.22%   |
| HP EliteBook Folio 1040 G1                 | 4         | 0.22%   |
| Gigabyte X570 AORUS ELITE                  | 4         | 0.22%   |
| Gigabyte H97-HD3                           | 4         | 0.22%   |
| Fujitsu CELSIUS W570                       | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 196       | 10.55%  |
| Acer Aspire        | 66        | 3.55%   |
| HP EliteBook       | 61        | 3.28%   |
| ASUS ROG           | 56        | 3.02%   |
| HP Pavilion        | 54        | 2.91%   |
| Dell XPS           | 44        | 2.37%   |
| Dell Latitude      | 42        | 2.26%   |
| HP ProBook         | 34        | 1.83%   |
| HP ENVY            | 33        | 1.78%   |
| ASUS All           | 32        | 1.72%   |
| RPi Raspberry      | 31        | 1.67%   |
| ASUS PRIME         | 30        | 1.62%   |
| Lenovo Yoga        | 27        | 1.45%   |
| Dell OptiPlex      | 27        | 1.45%   |
| HP Compaq          | 25        | 1.35%   |
| Fujitsu CELSIUS    | 25        | 1.35%   |
| HP EliteDesk       | 23        | 1.24%   |
| Lenovo IdeaPad     | 18        | 0.97%   |
| Unknown            | 18        | 0.97%   |
| HP Laptop          | 17        | 0.92%   |
| ASUS TUF           | 15        | 0.81%   |
| Dell Inspiron      | 14        | 0.75%   |
| Microsoft Surface  | 13        | 0.7%    |
| Acer Swift         | 13        | 0.7%    |
| ASUS VivoBook      | 12        | 0.65%   |
| Toshiba Satellite  | 11        | 0.59%   |
| HP ZBook           | 11        | 0.59%   |
| Dell Precision     | 11        | 0.59%   |
| ASUS Zenbook       | 11        | 0.59%   |
| Gigabyte X570      | 9         | 0.48%   |
| Lenovo ThinkCentre | 8         | 0.43%   |
| HP Spectre         | 8         | 0.43%   |
| HP ProLiant        | 8         | 0.43%   |
| HP ProDesk         | 8         | 0.43%   |
| ASUS STRIX         | 8         | 0.43%   |
| ASUS P9X79         | 8         | 0.43%   |
| ASUS P8Z77-V       | 8         | 0.43%   |
| Apple iMac12       | 7         | 0.38%   |
| Acer Predator      | 7         | 0.38%   |
| Razer Blade        | 6         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 202       | 10.88%  |
| 2019    | 191       | 10.29%  |
| 2020    | 168       | 9.05%   |
| 2017    | 161       | 8.67%   |
| 2012    | 142       | 7.65%   |
| 2011    | 126       | 6.79%   |
| 2013    | 117       | 6.3%    |
| 2015    | 113       | 6.09%   |
| 2021    | 108       | 5.82%   |
| 2014    | 107       | 5.76%   |
| 2016    | 95        | 5.12%   |
| 2010    | 89        | 4.79%   |
| 2008    | 60        | 3.23%   |
| 2009    | 52        | 2.8%    |
| 2022    | 43        | 2.32%   |
| 2007    | 33        | 1.78%   |
| Unknown | 25        | 1.35%   |
| 2006    | 15        | 0.81%   |
| 2005    | 6         | 0.32%   |
| 2004    | 3         | 0.16%   |
| 2003    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 865       | 46.58%  |
| Desktop        | 693       | 37.32%  |
| Convertible    | 98        | 5.28%   |
| Mini pc        | 51        | 2.75%   |
| Server         | 44        | 2.37%   |
| All in one     | 37        | 1.99%   |
| System on chip | 35        | 1.88%   |
| Tablet         | 31        | 1.67%   |
| Phone          | 3         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1704      | 90.88%  |
| Enabled  | 171       | 9.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1844      | 99.3%   |
| Yes  | 13        | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 481       | 25.44%  |
| 4.01-8.0        | 320       | 16.92%  |
| 8.01-16.0       | 304       | 16.08%  |
| 32.01-64.0      | 296       | 15.65%  |
| 3.01-4.0        | 241       | 12.74%  |
| 64.01-256.0     | 103       | 5.45%   |
| 1.01-2.0        | 50        | 2.64%   |
| 24.01-32.0      | 38        | 2.01%   |
| 0.51-1.0        | 22        | 1.16%   |
| More than 256.0 | 21        | 1.11%   |
| 2.01-3.0        | 14        | 0.74%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 665       | 31.94%  |
| 2.01-3.0        | 477       | 22.91%  |
| 4.01-8.0        | 338       | 16.23%  |
| 3.01-4.0        | 241       | 11.58%  |
| 0.51-1.0        | 166       | 7.97%   |
| 8.01-16.0       | 110       | 5.28%   |
| 0.01-0.5        | 38        | 1.83%   |
| 16.01-24.0      | 19        | 0.91%   |
| 24.01-32.0      | 8         | 0.38%   |
| 32.01-64.0      | 7         | 0.34%   |
| 64.01-256.0     | 7         | 0.34%   |
| Unknown         | 4         | 0.19%   |
| More than 256.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1154      | 60.1%   |
| 2       | 452       | 23.54%  |
| 3       | 165       | 8.59%   |
| 4       | 53        | 2.76%   |
| 5       | 38        | 1.98%   |
| 0       | 20        | 1.04%   |
| 6       | 17        | 0.89%   |
| 7       | 15        | 0.78%   |
| 14      | 2         | 0.1%    |
| 11      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |
| 8       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1194      | 63.75%  |
| Yes       | 679       | 36.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1589      | 84.97%  |
| No        | 281       | 15.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1331      | 71.14%  |
| No        | 540       | 28.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1102      | 58.59%  |
| No        | 779       | 41.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 1857      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 527       | 26.11%  |
| Bern                               | 100       | 4.96%   |
| Geneva                             | 66        | 3.27%   |
| Lausanne                           | 37        | 1.83%   |
| Basel                              | 36        | 1.78%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.64%   |
| Winterthur                         | 31        | 1.54%   |
| Lucerne                            | 31        | 1.54%   |
| Neuchatel                          | 25        | 1.24%   |
| Thun                               | 23        | 1.14%   |
| Lyss                               | 18        | 0.89%   |
| Lugano                             | 16        | 0.79%   |
| Dietikon                           | 16        | 0.79%   |
| St. Gallen                         | 15        | 0.74%   |
| Wil                                | 14        | 0.69%   |
| Munchenstein                       | 12        | 0.59%   |
| Herrliberg                         | 12        | 0.59%   |
| Wettingen                          | 11        | 0.55%   |
| Sion                               | 10        | 0.5%    |
| Dubendorf                          | 10        | 0.5%    |
| Willisau                           | 9         | 0.45%   |
| Wallisellen                        | 9         | 0.45%   |
| Schaffhausen                       | 9         | 0.45%   |
| Oberwil-Lieli                      | 9         | 0.45%   |
| Aarau                              | 9         | 0.45%   |
| Zollikofen                         | 8         | 0.4%    |
| Wetzikon                           | 8         | 0.4%    |
| Morges                             | 8         | 0.4%    |
| Burgdorf                           | 8         | 0.4%    |
| Bosingen                           | 8         | 0.4%    |
| Uster                              | 7         | 0.35%   |
| Prilly                             | 7         | 0.35%   |
| Onex                               | 7         | 0.35%   |
| Le Mont-sur-Lausanne               | 7         | 0.35%   |
| Kloten                             | 7         | 0.35%   |
| Kilchberg                          | 7         | 0.35%   |
| Grabs                              | 7         | 0.35%   |
| Gossau                             | 7         | 0.35%   |
| Frauenfeld                         | 7         | 0.35%   |
| Diepoldsau                         | 7         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 681       | 1227   | 25.94%  |
| WDC                       | 374       | 602    | 14.25%  |
| Seagate                   | 314       | 440    | 11.96%  |
| SanDisk                   | 137       | 171    | 5.22%   |
| Toshiba                   | 131       | 178    | 4.99%   |
| Unknown                   | 128       | 189    | 4.88%   |
| Intel                     | 123       | 170    | 4.69%   |
| Hitachi                   | 83        | 113    | 3.16%   |
| SK hynix                  | 76        | 91     | 2.9%    |
| Crucial                   | 76        | 109    | 2.9%    |
| Kingston                  | 71        | 106    | 2.7%    |
| Micron Technology         | 42        | 54     | 1.6%    |
| Apple                     | 32        | 35     | 1.22%   |
| HGST                      | 29        | 38     | 1.1%    |
| Corsair                   | 25        | 30     | 0.95%   |
| OCZ                       | 23        | 28     | 0.88%   |
| A-DATA Technology         | 21        | 33     | 0.8%    |
| Phison                    | 19        | 30     | 0.72%   |
| LITEON                    | 18        | 24     | 0.69%   |
| Intenso                   | 17        | 17     | 0.65%   |
| Transcend                 | 13        | 23     | 0.5%    |
| LITEONIT                  | 13        | 15     | 0.5%    |
| KIOXIA                    | 13        | 16     | 0.5%    |
| China                     | 10        | 11     | 0.38%   |
| ASMT                      | 10        | 15     | 0.38%   |
| Phison Electronics        | 8         | 16     | 0.3%    |
| KingSpec                  | 8         | 13     | 0.3%    |
| Hewlett-Packard           | 8         | 9      | 0.3%    |
| Silicon Motion            | 6         | 7      | 0.23%   |
| LaCie                     | 6         | 6      | 0.23%   |
| JMicron Technology        | 6         | 6      | 0.23%   |
| Fujitsu                   | 6         | 9      | 0.23%   |
| SPCC                      | 5         | 5      | 0.19%   |
| Plextor                   | 5         | 5      | 0.19%   |
| Patriot                   | 5         | 6      | 0.19%   |
| HPE                       | 5         | 12     | 0.19%   |
| PNY                       | 4         | 9      | 0.15%   |
| Micron/Crucial Technology | 4         | 6      | 0.15%   |
| Maxtor                    | 4         | 5      | 0.15%   |
| Lenovo                    | 4         | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 39        | 1.32%   |
| Samsung SSD 850 EVO 250GB                           | 32        | 1.08%   |
| Samsung SSD 860 EVO 1TB                             | 30        | 1.02%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.85%   |
| Samsung SSD 860 EVO 250GB                           | 24        | 0.81%   |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.78%   |
| Samsung NVMe SSD Drive 1TB                          | 22        | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 22        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.71%   |
| Unknown MMC Card  32GB                              | 19        | 0.64%   |
| Seagate ST2000DM006-2DM164 2TB                      | 17        | 0.58%   |
| Samsung NVMe SSD Drive 500GB                        | 17        | 0.58%   |
| Unknown MMC Card  128GB                             | 16        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16        | 0.54%   |
| Unknown MMC Card  64GB                              | 15        | 0.51%   |
| Samsung SSD 850 EVO 1TB                             | 15        | 0.51%   |
| Samsung SSD 840 EVO 250GB                           | 15        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 15        | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.47%   |
| Samsung NVMe SSD Drive 1024GB                       | 14        | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.44%   |
| Seagate Expansion 1TB                               | 13        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                      | 13        | 0.44%   |
| Samsung SSD 860 QVO 1TB                             | 13        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.41%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.41%   |
| Samsung SSD 850 PRO 256GB                           | 12        | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 12        | 0.41%   |
| Samsung SSD 870 EVO 500GB                           | 11        | 0.37%   |
| Samsung HD103SJ 1TB                                 | 11        | 0.37%   |
| Intel SSDPEKNW512G8H 512GB                          | 11        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 11        | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 10        | 0.34%   |
| Unknown SD/MMC/MS PRO 16GB                          | 10        | 0.34%   |
| Samsung SSD 970 EVO Plus 2TB                        | 10        | 0.34%   |
| Samsung SSD 970 EVO 500GB                           | 10        | 0.34%   |
| Samsung SSD 850 PRO 512GB                           | 10        | 0.34%   |
| Samsung NVMe SSD Drive 2TB                          | 10        | 0.34%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 9         | 0.31%   |
| Toshiba DT01ACA200 2TB                              | 9         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 304       | 419    | 35.64%  |
| WDC                 | 278       | 456    | 32.59%  |
| Hitachi             | 83        | 113    | 9.73%   |
| Toshiba             | 69        | 86     | 8.09%   |
| Samsung Electronics | 40        | 56     | 4.69%   |
| HGST                | 29        | 38     | 3.4%    |
| Unknown             | 11        | 12     | 1.29%   |
| Fujitsu             | 6         | 9      | 0.7%    |
| Maxtor              | 4         | 5      | 0.47%   |
| JMicron Technology  | 4         | 4      | 0.47%   |
| Intenso             | 4         | 4      | 0.47%   |
| Apple               | 4         | 4      | 0.47%   |
| ASMT                | 3         | 4      | 0.35%   |
| HPE                 | 2         | 8      | 0.23%   |
| ASMedia             | 2         | 2      | 0.23%   |
| USB3.0              | 1         | 2      | 0.12%   |
| Unknown (CF)        | 1         | 1      | 0.12%   |
| SABRENT             | 1         | 1      | 0.12%   |
| MARVELL             | 1         | 1      | 0.12%   |
| IET                 | 1         | 1      | 0.12%   |
| ICY BOX             | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |
| ExcelStor           | 1         | 2      | 0.12%   |
| ASMT109x            | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 389       | 674    | 39.57%  |
| SanDisk             | 89        | 111    | 9.05%   |
| Crucial             | 72        | 105    | 7.32%   |
| WDC                 | 57        | 75     | 5.8%    |
| Intel               | 57        | 69     | 5.8%    |
| Kingston            | 53        | 85     | 5.39%   |
| Micron Technology   | 26        | 36     | 2.64%   |
| OCZ                 | 23        | 28     | 2.34%   |
| Toshiba             | 22        | 33     | 2.24%   |
| Apple               | 22        | 23     | 2.24%   |
| SK hynix            | 18        | 22     | 1.83%   |
| LITEON              | 18        | 24     | 1.83%   |
| A-DATA Technology   | 14        | 23     | 1.42%   |
| LITEONIT            | 13        | 15     | 1.32%   |
| Corsair             | 13        | 14     | 1.32%   |
| Transcend           | 12        | 22     | 1.22%   |
| Intenso             | 12        | 12     | 1.22%   |
| China               | 10        | 11     | 1.02%   |
| KingSpec            | 8         | 13     | 0.81%   |
| ASMT                | 6         | 10     | 0.61%   |
| Plextor             | 5         | 5      | 0.51%   |
| Patriot             | 5         | 6      | 0.51%   |
| SPCC                | 4         | 4      | 0.41%   |
| Seagate             | 3         | 3      | 0.31%   |
| Hewlett-Packard     | 3         | 4      | 0.31%   |
| PNY                 | 2         | 3      | 0.2%    |
| Mushkin             | 2         | 2      | 0.2%    |
| KIOXIA-EXCERIA      | 2         | 2      | 0.2%    |
| Initio              | 2         | 2      | 0.2%    |
| HPE                 | 2         | 2      | 0.2%    |
| Unknown             | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| Phison              | 1         | 3      | 0.1%    |
| Palit               | 1         | 1      | 0.1%    |
| OWC                 | 1         | 1      | 0.1%    |
| ORICO               | 1         | 1      | 0.1%    |
| NVME                | 1         | 2      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Leven               | 1         | 1      | 0.1%    |
| Kolink              | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 863       | 1462   | 35.66%  |
| HDD     | 730       | 1233   | 30.17%  |
| NVMe    | 678       | 1039   | 28.02%  |
| MMC     | 120       | 182    | 4.96%   |
| Unknown | 29        | 41     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1258      | 2586   | 57.92%  |
| NVMe | 677       | 1038   | 31.17%  |
| MMC  | 120       | 182    | 5.52%   |
| SAS  | 117       | 151    | 5.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 880       | 1411   | 51.89%  |
| 0.51-1.0   | 473       | 745    | 27.89%  |
| 1.01-2.0   | 195       | 309    | 11.5%   |
| 3.01-4.0   | 59        | 99     | 3.48%   |
| 2.01-3.0   | 46        | 68     | 2.71%   |
| 4.01-10.0  | 35        | 47     | 2.06%   |
| 10.01-20.0 | 8         | 16     | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 460       | 23.19%  |
| 251-500        | 376       | 18.95%  |
| 501-1000       | 309       | 15.57%  |
| 1001-2000      | 199       | 10.03%  |
| 1-20           | 149       | 7.51%   |
| More than 3000 | 130       | 6.55%   |
| 51-100         | 101       | 5.09%   |
| 2001-3000      | 94        | 4.74%   |
| Unknown        | 90        | 4.54%   |
| 21-50          | 76        | 3.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 731       | 35.45%  |
| 21-50          | 269       | 13.05%  |
| 101-250        | 250       | 12.12%  |
| 51-100         | 228       | 11.06%  |
| 251-500        | 182       | 8.83%   |
| 501-1000       | 144       | 6.98%   |
| 1001-2000      | 90        | 4.36%   |
| Unknown        | 90        | 4.36%   |
| More than 3000 | 51        | 2.47%   |
| 2001-3000      | 27        | 1.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB          | 2         | 2      | 1.59%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.59%   |
| Seagate ST3250310AS 250GB             | 2         | 2      | 1.59%   |
| Seagate ST31500341AS 1TB              | 2         | 5      | 1.59%   |
| Samsung Electronics SSD 850 EVO 1TB   | 2         | 2      | 1.59%   |
| Initio 3639S 160GB SSD                | 2         | 2      | 1.59%   |
| Hitachi HUA722020ALA330 2TB           | 2         | 2      | 1.59%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.59%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.79%   |
| WDC WD5000AAKS-65A7B0 500GB           | 1         | 1      | 0.79%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1         | 1      | 0.79%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 0.79%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 0.79%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 1         | 2      | 0.79%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 1      | 0.79%   |
| WDC WD3200AAJS-40VWA1 320GB           | 1         | 1      | 0.79%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 0.79%   |
| WDC WD2502ABYS-01B7A0 256GB           | 1         | 1      | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 1      | 0.79%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 2      | 0.79%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 0.79%   |
| WDC WD1600BEKT-60A25T1 160GB          | 1         | 1      | 0.79%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 0.79%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.79%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 0.79%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.79%   |
| WDC WD1001FALS-403AA0 1TB             | 1         | 1      | 0.79%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 1      | 0.79%   |
| Toshiba THNSN5256GPUK 256GB           | 1         | 1      | 0.79%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.79%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.79%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 0.79%   |
| Toshiba MK7575GSX 752GB               | 1         | 3      | 0.79%   |
| Toshiba MK1652GSX 160GB               | 1         | 1      | 0.79%   |
| Toshiba MK1255GSX H 120GB             | 1         | 1      | 0.79%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 0.79%   |
| SK hynix SC401 SATA 512GB SSD         | 1         | 2      | 0.79%   |
| SK hynix SC210 mSATA 256GB SSD        | 1         | 1      | 0.79%   |
| SK hynix HFS256GD9TNG-62A0A 256GB     | 1         | 1      | 0.79%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 17.6%   |
| Seagate             | 20        | 30     | 16%     |
| Samsung Electronics | 16        | 18     | 12.8%   |
| Hitachi             | 12        | 13     | 9.6%    |
| Toshiba             | 8         | 10     | 6.4%    |
| Intel               | 8         | 9      | 6.4%    |
| SK hynix            | 7         | 8      | 5.6%    |
| SanDisk             | 5         | 6      | 4%      |
| Kingston            | 5         | 6      | 4%      |
| HGST                | 4         | 4      | 3.2%    |
| OCZ                 | 3         | 4      | 2.4%    |
| Micron Technology   | 3         | 3      | 2.4%    |
| A-DATA Technology   | 3         | 5      | 2.4%    |
| Initio              | 2         | 2      | 1.6%    |
| Crucial             | 2         | 2      | 1.6%    |
| Patriot             | 1         | 2      | 0.8%    |
| LITEONIT            | 1         | 1      | 0.8%    |
| Intenso             | 1         | 1      | 0.8%    |
| China               | 1         | 1      | 0.8%    |
| ASMedia             | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 22     | 28.99%  |
| Seagate             | 20        | 30     | 28.99%  |
| Hitachi             | 12        | 13     | 17.39%  |
| Toshiba             | 7         | 9      | 10.14%  |
| Samsung Electronics | 5         | 5      | 7.25%   |
| HGST                | 4         | 4      | 5.8%    |
| ASMedia             | 1         | 1      | 1.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 84     | 52.94%  |
| SSD  | 46        | 55     | 38.66%  |
| NVMe | 10        | 11     | 8.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1020      | 2095   | 50.97%  |
| Works    | 868       | 1711   | 43.38%  |
| Malfunc  | 112       | 150    | 5.6%    |
| Failed   | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1248      | 52.28%  |
| Samsung Electronics            | 332       | 13.91%  |
| AMD                            | 268       | 11.23%  |
| SanDisk                        | 90        | 3.77%   |
| ASMedia Technology             | 56        | 2.35%   |
| SK hynix                       | 52        | 2.18%   |
| Marvell Technology Group       | 50        | 2.09%   |
| Toshiba America Info Systems   | 45        | 1.89%   |
| Phison Electronics             | 37        | 1.55%   |
| JMicron Technology             | 28        | 1.17%   |
| Nvidia                         | 27        | 1.13%   |
| Kingston Technology Company    | 21        | 0.88%   |
| Micron Technology              | 17        | 0.71%   |
| LSI Logic / Symbios Logic      | 14        | 0.59%   |
| Areca Technology               | 13        | 0.54%   |
| KIOXIA                         | 12        | 0.5%    |
| Silicon Motion                 | 11        | 0.46%   |
| Seagate Technology             | 10        | 0.42%   |
| ADATA Technology               | 8         | 0.34%   |
| Hewlett-Packard                | 7         | 0.29%   |
| Broadcom / LSI                 | 7         | 0.29%   |
| Micron/Crucial Technology      | 6         | 0.25%   |
| Apple                          | 5         | 0.21%   |
| Solid State Storage Technology | 4         | 0.17%   |
| Lenovo                         | 4         | 0.17%   |
| VIA Technologies               | 3         | 0.13%   |
| Realtek Semiconductor          | 3         | 0.13%   |
| Lite-On Technology             | 3         | 0.13%   |
| Adaptec                        | 2         | 0.08%   |
| Union Memory (Shenzhen)        | 1         | 0.04%   |
| Transcend                      | 1         | 0.04%   |
| Tekram Technology              | 1         | 0.04%   |
| Biwin Storage Technology       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 194       | 7.12%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 186       | 6.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 98        | 3.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 82        | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 79        | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 63        | 2.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 57        | 2.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 53        | 1.95%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 52        | 1.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 50        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 49        | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 47        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 46        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 43        | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 41        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 39        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 1.4%    |
| Intel SATA Controller [RAID mode]                                              | 37        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 1.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 31        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 31        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                | 29        | 1.06%   |
| Intel SSD 660P Series                                                          | 29        | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 26        | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 25        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 24        | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 20        | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 19        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 19        | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 18        | 0.66%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 18        | 0.66%   |
| AMD 500 Series Chipset SATA Controller                                         | 18        | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 0.62%   |
| Phison E12 NVMe Controller                                                     | 17        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1281      | 54.12%  |
| NVMe | 682       | 28.81%  |
| IDE  | 196       | 8.28%   |
| RAID | 186       | 7.86%   |
| SAS  | 21        | 0.89%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1478      | 79.59%  |
| AMD          | 339       | 18.26%  |
| ARM          | 35        | 1.88%   |
| QUALCOMM     | 2         | 0.11%   |
| CentaurHauls | 2         | 0.11%   |
| Unknown      | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 45        | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 40        | 2.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 36        | 1.94%   |
| ARM Processor                              | 35        | 1.88%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 21        | 1.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 20        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 20        | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 19        | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 18        | 0.97%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 18        | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 17        | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 16        | 0.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 15        | 0.81%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 15        | 0.81%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 14        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 14        | 0.75%   |
| AMD Ryzen 5 3600 6-Core Processor          | 14        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 13        | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor        | 13        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.65%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 12        | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 12        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 12        | 0.65%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 11        | 0.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 11        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 11        | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 11        | 0.59%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 10        | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 10        | 0.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 10        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 10        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 10        | 0.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 10        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 10        | 0.54%   |
| Intel 12th Gen Core i7-1260P               | 10        | 0.54%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 10        | 0.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 10        | 0.54%   |
| Intel Core i7-3770K CPU @ 3.50GHz          | 9         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 624       | 33.58%  |
| Intel Core i5           | 370       | 19.91%  |
| Other                   | 142       | 7.64%   |
| AMD Ryzen 7             | 81        | 4.36%   |
| AMD Ryzen 5             | 75        | 4.04%   |
| Intel Xeon              | 74        | 3.98%   |
| Intel Core 2 Duo        | 66        | 3.55%   |
| Intel Core i3           | 52        | 2.8%    |
| Intel Celeron           | 47        | 2.53%   |
| AMD Ryzen 9             | 37        | 1.99%   |
| Intel Atom              | 29        | 1.56%   |
| Intel Pentium           | 26        | 1.4%    |
| Intel Core i9           | 18        | 0.97%   |
| AMD FX                  | 18        | 0.97%   |
| AMD Ryzen 7 PRO         | 15        | 0.81%   |
| Intel Pentium Dual-Core | 14        | 0.75%   |
| Intel Core 2            | 14        | 0.75%   |
| Intel Core 2 Quad       | 13        | 0.7%    |
| AMD Ryzen Threadripper  | 12        | 0.65%   |
| AMD Ryzen 3             | 9         | 0.48%   |
| AMD Quad-Core Opteron   | 8         | 0.43%   |
| AMD GX                  | 8         | 0.43%   |
| AMD A8                  | 7         | 0.38%   |
| Intel Xeon Gold         | 6         | 0.32%   |
| AMD E                   | 6         | 0.32%   |
| AMD Opteron             | 5         | 0.27%   |
| AMD EPYC                | 5         | 0.27%   |
| AMD Athlon              | 5         | 0.27%   |
| Intel Pentium 4         | 4         | 0.22%   |
| AMD Phenom II X6        | 4         | 0.22%   |
| AMD Phenom II X4        | 4         | 0.22%   |
| AMD A10                 | 4         | 0.22%   |
| Intel Pentium Silver    | 3         | 0.16%   |
| Intel Pentium M         | 3         | 0.16%   |
| Intel Genuine           | 3         | 0.16%   |
| Intel Core M            | 3         | 0.16%   |
| AMD Ryzen 5 PRO         | 3         | 0.16%   |
| AMD E2                  | 3         | 0.16%   |
| AMD E1                  | 3         | 0.16%   |
| AMD Athlon II X2        | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 816       | 43.87%  |
| 2       | 535       | 28.76%  |
| 6       | 194       | 10.43%  |
| 8       | 171       | 9.19%   |
| 12      | 45        | 2.42%   |
| 16      | 24        | 1.29%   |
| 1       | 20        | 1.08%   |
| 10      | 10        | 0.54%   |
| 32      | 9         | 0.48%   |
| 24      | 6         | 0.32%   |
| 14      | 6         | 0.32%   |
| 3       | 6         | 0.32%   |
| Unknown | 6         | 0.32%   |
| 40      | 4         | 0.22%   |
| 128     | 3         | 0.16%   |
| 48      | 3         | 0.16%   |
| 20      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1797      | 96.72%  |
| 2       | 46        | 2.48%   |
| 4       | 10        | 0.54%   |
| Unknown | 4         | 0.22%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1352      | 72.45%  |
| 1       | 508       | 27.22%  |
| Unknown | 6         | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1819      | 97.64%  |
| Unknown        | 31        | 1.66%   |
| 32-bit         | 12        | 0.64%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 392       | 20.46%  |
| 0x306a9    | 117       | 6.11%   |
| 0x206a7    | 98        | 5.11%   |
| 0x306c3    | 94        | 4.91%   |
| 0x806ea    | 74        | 3.86%   |
| 0x506e3    | 63        | 3.29%   |
| 0x906ea    | 60        | 3.13%   |
| 0x806ec    | 53        | 2.77%   |
| 0x1067a    | 53        | 2.77%   |
| 0x40651    | 51        | 2.66%   |
| 0x806e9    | 49        | 2.56%   |
| 0x806c1    | 48        | 2.51%   |
| 0x306d4    | 32        | 1.67%   |
| 0x906e9    | 31        | 1.62%   |
| 0x406e3    | 27        | 1.41%   |
| 0x08701021 | 27        | 1.41%   |
| 0x20655    | 25        | 1.3%    |
| 0x30678    | 21        | 1.1%    |
| 0x0a50000c | 18        | 0.94%   |
| 0x706e5    | 17        | 0.89%   |
| 0x10676    | 17        | 0.89%   |
| 0x0800820d | 17        | 0.89%   |
| 0x806eb    | 16        | 0.84%   |
| 0xa0655    | 15        | 0.78%   |
| 0x206d7    | 15        | 0.78%   |
| 0xa0652    | 14        | 0.73%   |
| 0x50654    | 14        | 0.73%   |
| 0x20652    | 14        | 0.73%   |
| 0x406c4    | 13        | 0.68%   |
| 0x106e5    | 13        | 0.68%   |
| 0x906ed    | 12        | 0.63%   |
| 0x306e4    | 12        | 0.63%   |
| 0x08701013 | 12        | 0.63%   |
| 0x906a3    | 11        | 0.57%   |
| 0x706a1    | 11        | 0.57%   |
| 0x6fd      | 11        | 0.57%   |
| 0x306f2    | 11        | 0.57%   |
| 0x206c2    | 11        | 0.57%   |
| 0x08600106 | 10        | 0.52%   |
| 0x08600103 | 10        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 378       | 20.32%  |
| Haswell          | 189       | 10.16%  |
| IvyBridge        | 148       | 7.96%   |
| SandyBridge      | 135       | 7.26%   |
| Skylake          | 130       | 6.99%   |
| Zen 2            | 93        | 5%      |
| Unknown          | 82        | 4.41%   |
| Penryn           | 80        | 4.3%    |
| TigerLake        | 62        | 3.33%   |
| Westmere         | 57        | 3.06%   |
| Zen 3            | 51        | 2.74%   |
| Silvermont       | 45        | 2.42%   |
| CometLake        | 43        | 2.31%   |
| Broadwell        | 43        | 2.31%   |
| Zen+             | 38        | 2.04%   |
| Core             | 34        | 1.83%   |
| Zen              | 33        | 1.77%   |
| Nehalem          | 29        | 1.56%   |
| IceLake          | 28        | 1.51%   |
| K10              | 27        | 1.45%   |
| Piledriver       | 20        | 1.08%   |
| Alderlake Hybrid | 18        | 0.97%   |
| Goldmont plus    | 17        | 0.91%   |
| Goldmont         | 12        | 0.65%   |
| Bobcat           | 12        | 0.65%   |
| Puma             | 10        | 0.54%   |
| K8 Hammer        | 8         | 0.43%   |
| Jaguar           | 8         | 0.43%   |
| P6               | 6         | 0.32%   |
| Excavator        | 5         | 0.27%   |
| Bulldozer        | 5         | 0.27%   |
| Bonnell          | 5         | 0.27%   |
| NetBurst         | 4         | 0.22%   |
| K10 Llano        | 3         | 0.16%   |
| Steamroller      | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1039      | 48.99%  |
| Nvidia                                       | 638       | 30.08%  |
| AMD                                          | 390       | 18.39%  |
| Matrox Electronics Systems                   | 30        | 1.41%   |
| ASPEED Technology                            | 13        | 0.61%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.42%   |
| VIA Technologies                             | 2         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 79        | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 77        | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 76        | 3.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 62        | 2.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 60        | 2.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 2.65%   |
| Intel HD Graphics 620                                                                    | 52        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40        | 1.86%   |
| Intel HD Graphics 530                                                                    | 39        | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 1.76%   |
| AMD Renoir                                                                               | 35        | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 33        | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.39%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 1.07%   |
| Intel HD Graphics 630                                                                    | 22        | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 20        | 0.93%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 0.79%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 15        | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.65%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 14        | 0.65%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 13        | 0.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.6%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 0.56%   |
| AMD Lucienne                                                                             | 12        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.51%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 763       | 40.8%   |
| 1 x Nvidia               | 397       | 21.23%  |
| 1 x AMD                  | 326       | 17.43%  |
| Intel + Nvidia           | 214       | 11.44%  |
| Other                    | 48        | 2.57%   |
| Intel + AMD              | 36        | 1.93%   |
| 1 x Matrox               | 27        | 1.44%   |
| AMD + Nvidia             | 17        | 0.91%   |
| 2 x AMD                  | 9         | 0.48%   |
| 1 x XGI                  | 9         | 0.48%   |
| 1 x ASPEED               | 8         | 0.43%   |
| Nvidia + ASPEED          | 4         | 0.21%   |
| 2 x Nvidia               | 3         | 0.16%   |
| 2 x Intel                | 2         | 0.11%   |
| 1 x VIA                  | 2         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.11%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1394      | 74.35%  |
| Proprietary | 369       | 19.68%  |
| Unknown     | 112       | 5.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1019      | 53.46%  |
| 1.01-2.0   | 243       | 12.75%  |
| 0.01-0.5   | 177       | 9.29%   |
| 3.01-4.0   | 140       | 7.35%   |
| 0.51-1.0   | 133       | 6.98%   |
| 7.01-8.0   | 85        | 4.46%   |
| 8.01-16.0  | 60        | 3.15%   |
| 5.01-6.0   | 34        | 1.78%   |
| 2.01-3.0   | 13        | 0.68%   |
| 4.01-5.0   | 1         | 0.05%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 264       | 13.11%  |
| AU Optronics            | 233       | 11.57%  |
| LG Display              | 191       | 9.49%   |
| Dell                    | 136       | 6.76%   |
| Chimei Innolux          | 118       | 5.86%   |
| BOE                     | 99        | 4.92%   |
| Hewlett-Packard         | 97        | 4.82%   |
| Acer                    | 93        | 4.62%   |
| Philips                 | 80        | 3.97%   |
| Apple                   | 71        | 3.53%   |
| BenQ                    | 64        | 3.18%   |
| Ancor Communications    | 59        | 2.93%   |
| Sharp                   | 56        | 2.78%   |
| Lenovo                  | 51        | 2.53%   |
| Goldstar                | 47        | 2.33%   |
| AOC                     | 42        | 2.09%   |
| Eizo                    | 36        | 1.79%   |
| Chi Mei Optoelectronics | 22        | 1.09%   |
| ASUSTek Computer        | 21        | 1.04%   |
| Sony                    | 20        | 0.99%   |
| Unknown                 | 19        | 0.94%   |
| InfoVision              | 19        | 0.94%   |
| Iiyama                  | 13        | 0.65%   |
| CSO                     | 13        | 0.65%   |
| NEC Computers           | 11        | 0.55%   |
| Panasonic               | 9         | 0.45%   |
| Toshiba                 | 8         | 0.4%    |
| PANDA                   | 7         | 0.35%   |
| Medion                  | 7         | 0.35%   |
| ViewSonic               | 5         | 0.25%   |
| Vestel Elektronik       | 5         | 0.25%   |
| LG Philips              | 5         | 0.25%   |
| LG Electronics          | 5         | 0.25%   |
| Gigabyte Technology     | 5         | 0.25%   |
| AUS                     | 5         | 0.25%   |
| MSI                     | 4         | 0.2%    |
| JDI                     | 4         | 0.2%    |
| Fujitsu Siemens         | 4         | 0.2%    |
| ___                     | 3         | 0.15%   |
| LGD                     | 3         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 11        | 0.52%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 9         | 0.43%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.33%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.28%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 6         | 0.28%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 6         | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.28%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 6         | 0.28%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 6         | 0.28%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 6         | 0.28%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 5         | 0.24%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 5         | 0.24%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 5         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.24%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.24%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 5         | 0.24%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 4         | 0.19%   |
| Sharp HDMI SHP1022 1920x1080 820x460mm 37.0-inch                      | 4         | 0.19%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 4         | 0.19%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch    | 4         | 0.19%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 4         | 0.19%   |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                  | 4         | 0.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 4         | 0.19%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch              | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 819       | 42.02%  |
| 3840x2160 (4K)     | 176       | 9.03%   |
| 2560x1440 (QHD)    | 143       | 7.34%   |
| 1366x768 (WXGA)    | 141       | 7.23%   |
| 1920x1200 (WUXGA)  | 99        | 5.08%   |
| 1600x900 (HD+)     | 80        | 4.1%    |
| 1680x1050 (WSXGA+) | 72        | 3.69%   |
| 1280x1024 (SXGA)   | 60        | 3.08%   |
| Unknown            | 52        | 2.67%   |
| 1280x800 (WXGA)    | 34        | 1.74%   |
| 3440x1440          | 31        | 1.59%   |
| 1440x900 (WXGA+)   | 31        | 1.59%   |
| 2560x1600          | 22        | 1.13%   |
| 1600x1200          | 21        | 1.08%   |
| 3840x1080          | 20        | 1.03%   |
| 2880x1800          | 12        | 0.62%   |
| 3200x1800 (QHD+)   | 11        | 0.56%   |
| 2560x1080          | 10        | 0.51%   |
| 3840x2400          | 9         | 0.46%   |
| 2736x1824          | 9         | 0.46%   |
| 1360x768           | 7         | 0.36%   |
| 1024x768 (XGA)     | 7         | 0.36%   |
| 3840x1200          | 6         | 0.31%   |
| 3000x2000          | 6         | 0.31%   |
| 1920x540           | 6         | 0.31%   |
| 4480x1440          | 5         | 0.26%   |
| 3840x1600          | 5         | 0.26%   |
| 1024x600           | 5         | 0.26%   |
| 2160x1440          | 4         | 0.21%   |
| 3520x1200          | 3         | 0.15%   |
| 3360x1050          | 3         | 0.15%   |
| 2048x1152          | 3         | 0.15%   |
| 7680x2160          | 2         | 0.1%    |
| 6400x1440          | 2         | 0.1%    |
| 5120x1440          | 2         | 0.1%    |
| 3840x1100          | 2         | 0.1%    |
| 3456x2160          | 2         | 0.1%    |
| 3200x1080          | 2         | 0.1%    |
| 2560x1024          | 2         | 0.1%    |
| 2288x1287          | 2         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 379       | 18.93%  |
| 27      | 206       | 10.29%  |
| 13      | 180       | 8.99%   |
| 24      | 165       | 8.24%   |
| 14      | 164       | 8.19%   |
| Unknown | 164       | 8.19%   |
| 17      | 129       | 6.44%   |
| 23      | 106       | 5.29%   |
| 21      | 82        | 4.1%    |
| 12      | 55        | 2.75%   |
| 31      | 52        | 2.6%    |
| 19      | 35        | 1.75%   |
| 34      | 34        | 1.7%    |
| 22      | 34        | 1.7%    |
| 20      | 31        | 1.55%   |
| 32      | 18        | 0.9%    |
| 84      | 15        | 0.75%   |
| 40      | 15        | 0.75%   |
| 72      | 13        | 0.65%   |
| 25      | 13        | 0.65%   |
| 33      | 10        | 0.5%    |
| 16      | 10        | 0.5%    |
| 11      | 10        | 0.5%    |
| 46      | 8         | 0.4%    |
| 37      | 8         | 0.4%    |
| 54      | 7         | 0.35%   |
| 29      | 7         | 0.35%   |
| 18      | 7         | 0.35%   |
| 10      | 6         | 0.3%    |
| 28      | 5         | 0.25%   |
| 26      | 5         | 0.25%   |
| 49      | 4         | 0.2%    |
| 48      | 4         | 0.2%    |
| 55      | 3         | 0.15%   |
| 142     | 2         | 0.1%    |
| 65      | 2         | 0.1%    |
| 60      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 74      | 1         | 0.05%   |
| 59      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 621       | 31.52%  |
| 501-600        | 443       | 22.49%  |
| 201-300        | 188       | 9.54%   |
| Unknown        | 164       | 8.32%   |
| 401-500        | 158       | 8.02%   |
| 351-400        | 155       | 7.87%   |
| 601-700        | 85        | 4.31%   |
| 701-800        | 62        | 3.15%   |
| 1001-1500      | 32        | 1.62%   |
| 1501-2000      | 29        | 1.47%   |
| 801-900        | 26        | 1.32%   |
| 901-1000       | 3         | 0.15%   |
| More than 2000 | 2         | 0.1%    |
| 101-200        | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1225      | 67.83%  |
| 16/10   | 266       | 14.73%  |
| Unknown | 150       | 8.31%   |
| 5/4     | 52        | 2.88%   |
| 21/9    | 42        | 2.33%   |
| 3/2     | 29        | 1.61%   |
| 4/3     | 24        | 1.33%   |
| 32/9    | 7         | 0.39%   |
| 6/5     | 3         | 0.17%   |
| 1.00    | 3         | 0.17%   |
| 3.40    | 2         | 0.11%   |
| 3.73    | 1         | 0.06%   |
| 2.50    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 377       | 19.04%  |
| 201-250        | 274       | 13.84%  |
| 81-90          | 238       | 12.02%  |
| 301-350        | 210       | 10.61%  |
| Unknown        | 164       | 8.28%   |
| 351-500        | 125       | 6.31%   |
| 71-80          | 103       | 5.2%    |
| 121-130        | 99        | 5%      |
| 251-300        | 97        | 4.9%    |
| 151-200        | 86        | 4.34%   |
| 61-70          | 53        | 2.68%   |
| More than 1000 | 50        | 2.53%   |
| 501-1000       | 38        | 1.92%   |
| 141-150        | 19        | 0.96%   |
| 131-140        | 14        | 0.71%   |
| 51-60          | 12        | 0.61%   |
| 111-120        | 9         | 0.45%   |
| 41-50          | 6         | 0.3%    |
| 91-100         | 4         | 0.2%    |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 576       | 29.95%  |
| 121-160       | 517       | 26.89%  |
| 101-120       | 369       | 19.19%  |
| Unknown       | 164       | 8.53%   |
| 161-240       | 156       | 8.11%   |
| More than 240 | 94        | 4.89%   |
| 1-50          | 47        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1408      | 73.79%  |
| 2     | 315       | 16.51%  |
| 0     | 138       | 7.23%   |
| 3     | 45        | 2.36%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1145      | 42.02%  |
| Realtek Semiconductor             | 744       | 27.3%   |
| Qualcomm Atheros                  | 211       | 7.74%   |
| Broadcom                          | 160       | 5.87%   |
| Broadcom Limited                  | 38        | 1.39%   |
| Marvell Technology Group          | 34        | 1.25%   |
| Ralink                            | 31        | 1.14%   |
| MediaTek                          | 27        | 0.99%   |
| Aquantia                          | 25        | 0.92%   |
| Lenovo                            | 22        | 0.81%   |
| Nvidia                            | 21        | 0.77%   |
| ASIX Electronics                  | 19        | 0.7%    |
| Ralink Technology                 | 18        | 0.66%   |
| Sierra Wireless                   | 16        | 0.59%   |
| Hewlett-Packard                   | 14        | 0.51%   |
| Huawei Technologies               | 13        | 0.48%   |
| Dell                              | 13        | 0.48%   |
| TP-Link                           | 12        | 0.44%   |
| Edimax Technology                 | 12        | 0.44%   |
| Samsung Electronics               | 11        | 0.4%    |
| NetGear                           | 11        | 0.4%    |
| Ericsson Business Mobile Networks | 11        | 0.4%    |
| DisplayLink                       | 11        | 0.4%    |
| Microchip Technology              | 10        | 0.37%   |
| Xiaomi                            | 7         | 0.26%   |
| D-Link                            | 7         | 0.26%   |
| ASUSTek Computer                  | 7         | 0.26%   |
| Qualcomm                          | 6         | 0.22%   |
| Microsoft                         | 5         | 0.18%   |
| Fibocom                           | 5         | 0.18%   |
| IMC Networks                      | 4         | 0.15%   |
| ICS Advent                        | 4         | 0.15%   |
| D-Link System                     | 4         | 0.15%   |
| AVM                               | 4         | 0.15%   |
| Wilocity                          | 3         | 0.11%   |
| NetXen Incorporated               | 3         | 0.11%   |
| Mellanox Technologies             | 3         | 0.11%   |
| Linksys                           | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.07%   |
| Micro Star International          | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 526       | 16.13%  |
| Intel Wi-Fi 6 AX200                                               | 118       | 3.62%   |
| Intel Wireless 8265 / 8275                                        | 97        | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80        | 2.45%   |
| Intel I211 Gigabit Network Connection                             | 75        | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 2.18%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 49        | 1.5%    |
| Intel Wireless 7260                                               | 48        | 1.47%   |
| Intel Wireless 7265                                               | 44        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 38        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 37        | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 37        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 1.13%   |
| Intel Wireless 8260                                               | 35        | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 30        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 0.8%    |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 0.74%   |
| Intel Wireless 3165                                               | 23        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 0.58%   |
| Intel Wireless-AC 9260                                            | 19        | 0.58%   |
| Intel I350 Gigabit Network Connection                             | 19        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 789       | 56.08%  |
| Qualcomm Atheros                      | 175       | 12.44%  |
| Realtek Semiconductor                 | 141       | 10.02%  |
| Broadcom                              | 89        | 6.33%   |
| Ralink                                | 31        | 2.2%    |
| Broadcom Limited                      | 23        | 1.63%   |
| Ralink Technology                     | 18        | 1.28%   |
| MediaTek                              | 18        | 1.28%   |
| Sierra Wireless                       | 16        | 1.14%   |
| Edimax Technology                     | 12        | 0.85%   |
| TP-Link                               | 10        | 0.71%   |
| NetGear                               | 10        | 0.71%   |
| Marvell Technology Group              | 9         | 0.64%   |
| Hewlett-Packard                       | 7         | 0.5%    |
| Dell                                  | 7         | 0.5%    |
| ASUSTek Computer                      | 7         | 0.5%    |
| D-Link                                | 6         | 0.43%   |
| Qualcomm                              | 5         | 0.36%   |
| Fibocom                               | 5         | 0.36%   |
| IMC Networks                          | 4         | 0.28%   |
| AVM                                   | 4         | 0.28%   |
| Wilocity                              | 3         | 0.21%   |
| Microsoft                             | 3         | 0.21%   |
| D-Link System                         | 3         | 0.21%   |
| Qualcomm Atheros Communications       | 2         | 0.14%   |
| Micro Star International              | 2         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.14%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Netopia                               | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Ericsson Business Mobile Networks     | 1         | 0.07%   |
| CyberTAN Technology                   | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 118       | 8.33%   |
| Intel Wireless 8265 / 8275                                     | 97        | 6.85%   |
| Intel Wi-Fi 6 AX201                                            | 49        | 3.46%   |
| Intel Wireless 7260                                            | 48        | 3.39%   |
| Intel Wireless 7265                                            | 44        | 3.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 2.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 37        | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 37        | 2.61%   |
| Intel Wireless 8260                                            | 35        | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 28        | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 1.69%   |
| Intel Wireless 3165                                            | 23        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 1.34%   |
| Intel Wireless-AC 9260                                         | 19        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 1.27%   |
| Intel Centrino Ultimate-N 6300                                 | 18        | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 18        | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 16        | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.06%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 12        | 0.85%   |
| Intel Wireless 3160                                            | 12        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 0.71%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 0.71%   |
| Sierra Wireless EM7455                                         | 9         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 9         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 9         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 696       | 40.09%  |
| Realtek Semiconductor         | 679       | 39.11%  |
| Broadcom                      | 89        | 5.13%   |
| Qualcomm Atheros              | 61        | 3.51%   |
| Marvell Technology Group      | 25        | 1.44%   |
| Aquantia                      | 25        | 1.44%   |
| Lenovo                        | 22        | 1.27%   |
| Nvidia                        | 21        | 1.21%   |
| ASIX Electronics              | 19        | 1.09%   |
| Broadcom Limited              | 15        | 0.86%   |
| Samsung Electronics           | 11        | 0.63%   |
| DisplayLink                   | 11        | 0.63%   |
| MediaTek                      | 9         | 0.52%   |
| Microchip Technology          | 8         | 0.46%   |
| Huawei Technologies           | 8         | 0.46%   |
| Xiaomi                        | 7         | 0.4%    |
| ICS Advent                    | 4         | 0.23%   |
| NetXen Incorporated           | 3         | 0.17%   |
| TP-Link                       | 2         | 0.12%   |
| Microsoft                     | 2         | 0.12%   |
| Mellanox Technologies         | 2         | 0.12%   |
| Linksys                       | 2         | 0.12%   |
| Standard Microsystems         | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| QNAP System                   | 1         | 0.06%   |
| OnePlus Technology (Shenzhen) | 1         | 0.06%   |
| NetGear                       | 1         | 0.06%   |
| Netchip Technology            | 1         | 0.06%   |
| MosChip Semiconductor         | 1         | 0.06%   |
| JMicron Technology            | 1         | 0.06%   |
| HMD Global                    | 1         | 0.06%   |
| Hewlett-Packard               | 1         | 0.06%   |
| D-Link System                 | 1         | 0.06%   |
| D-Link                        | 1         | 0.06%   |
| Cypress Semiconductor         | 1         | 0.06%   |
| Apple                         | 1         | 0.06%   |
| ADMtek                        | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 526       | 29.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80        | 4.45%   |
| Intel I211 Gigabit Network Connection                             | 75        | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 3.95%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 2.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 2.28%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 2.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 37        | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 1.89%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 1.84%   |
| Intel 82574L Gigabit Network Connection                           | 30        | 1.67%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 1.45%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.11%   |
| Intel I350 Gigabit Network Connection                             | 19        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.06%   |
| Intel I210 Gigabit Network Connection                             | 18        | 1%      |
| Intel Ethernet Controller I225-V                                  | 18        | 1%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 18        | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                             | 15        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 9         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 9         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 8         | 0.45%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.45%   |
| Lenovo ThinkPad Lan                                               | 8         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.45%   |
| Intel 82576 Gigabit Network Connection                            | 8         | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.39%   |
| Nvidia MCP55 Ethernet                                             | 7         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1583      | 53.55%  |
| WiFi     | 1329      | 44.96%  |
| Modem    | 41        | 1.39%   |
| Unknown  | 3         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 956       | 51.07%  |
| Ethernet | 916       | 48.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 957       | 51.31%  |
| 1     | 728       | 39.03%  |
| 3     | 81        | 4.34%   |
| 0     | 61        | 3.27%   |
| 4     | 23        | 1.23%   |
| 6     | 8         | 0.43%   |
| 5     | 4         | 0.21%   |
| 10    | 1         | 0.05%   |
| 8     | 1         | 0.05%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1529      | 80.3%   |
| Yes  | 375       | 19.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 631       | 56.69%  |
| Realtek Semiconductor           | 67        | 6.02%   |
| Broadcom                        | 64        | 5.75%   |
| Apple                           | 60        | 5.39%   |
| Qualcomm Atheros Communications | 51        | 4.58%   |
| Cambridge Silicon Radio         | 50        | 4.49%   |
| Foxconn / Hon Hai               | 39        | 3.5%    |
| Lite-On Technology              | 30        | 2.7%    |
| IMC Networks                    | 28        | 2.52%   |
| ASUSTek Computer                | 24        | 2.16%   |
| Hewlett-Packard                 | 13        | 1.17%   |
| Dell                            | 12        | 1.08%   |
| Ralink                          | 9         | 0.81%   |
| Marvell Semiconductor           | 7         | 0.63%   |
| MediaTek                        | 5         | 0.45%   |
| Toshiba                         | 3         | 0.27%   |
| Realtek                         | 3         | 0.27%   |
| Micro Star International        | 3         | 0.27%   |
| Alps Electric                   | 3         | 0.27%   |
| Ralink Technology               | 2         | 0.18%   |
| Chicony Electronics             | 2         | 0.18%   |
| USI                             | 1         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 252       | 22.6%   |
| Intel AX200 Bluetooth                               | 111       | 9.96%   |
| Intel AX201 Bluetooth                               | 107       | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 73        | 6.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 4.48%   |
| Realtek Bluetooth Radio                             | 42        | 3.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 1.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.61%   |
| Intel Bluetooth Device                              | 18        | 1.61%   |
| Apple Bluetooth Host Controller                     | 18        | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.26%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.17%   |
| Apple Bluetooth USB Host Controller                 | 13        | 1.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 1.08%   |
| Intel AX210 Bluetooth                               | 11        | 0.99%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 0.99%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.72%   |
| Apple Bluetooth HCI                                 | 8         | 0.72%   |
| IMC Networks Wireless_Device                        | 7         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.63%   |
| Lite-On Bluetooth Device                            | 6         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.54%   |
| MediaTek Wireless_Device                            | 5         | 0.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.45%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.36%   |
| IMC Networks Bluetooth Device                       | 4         | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1394      | 54.75%  |
| Nvidia                    | 472       | 18.54%  |
| AMD                       | 411       | 16.14%  |
| Logitech                  | 28        | 1.1%    |
| GN Netcom                 | 28        | 1.1%    |
| C-Media Electronics       | 26        | 1.02%   |
| Lenovo                    | 14        | 0.55%   |
| Plantronics               | 10        | 0.39%   |
| Hewlett-Packard           | 10        | 0.39%   |
| ASUSTek Computer          | 10        | 0.39%   |
| Kingston Technology       | 9         | 0.35%   |
| SteelSeries ApS           | 8         | 0.31%   |
| RODE Microphones          | 8         | 0.31%   |
| Realtek Semiconductor     | 8         | 0.31%   |
| Creative Labs             | 8         | 0.31%   |
| BEHRINGER International   | 6         | 0.24%   |
| Apple                     | 6         | 0.24%   |
| Texas Instruments         | 5         | 0.2%    |
| Razer USA                 | 5         | 0.2%    |
| Samson Technologies       | 4         | 0.16%   |
| Generalplus Technology    | 4         | 0.16%   |
| Tenx Technology           | 3         | 0.12%   |
| Creative Technology       | 3         | 0.12%   |
| Corsair                   | 3         | 0.12%   |
| Conexant Systems          | 3         | 0.12%   |
| Yamaha                    | 2         | 0.08%   |
| XMOS                      | 2         | 0.08%   |
| VIA Technologies          | 2         | 0.08%   |
| TerraTec Electronic       | 2         | 0.08%   |
| Sennheiser Communications | 2         | 0.08%   |
| Roland                    | 2         | 0.08%   |
| ROCCAT                    | 2         | 0.08%   |
| Magic Control Technology  | 2         | 0.08%   |
| JMTek                     | 2         | 0.08%   |
| HiFiBerry                 | 2         | 0.08%   |
| GYROCOM C&C               | 2         | 0.08%   |
| Giga-Byte Technology      | 2         | 0.08%   |
| Focusrite-Novation        | 2         | 0.08%   |
| AudioQuest                | 2         | 0.08%   |
| Audinate                  | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 181       | 6.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 139       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 107       | 3.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 107       | 3.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 89        | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 80        | 2.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 74        | 2.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 70        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 69        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 67        | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 67        | 2.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 60        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 58        | 1.97%   |
| Intel 8 Series HD Audio Controller                                         | 58        | 1.97%   |
| Intel 200 Series PCH HD Audio                                              | 53        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 45        | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 43        | 1.46%   |
| Nvidia GK107 HDMI Audio Controller                                         | 41        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 38        | 1.29%   |
| Intel Broadwell-U Audio Controller                                         | 38        | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 38        | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 36        | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 29        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 26        | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                         | 26        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 26        | 0.88%   |
| Nvidia GP102 HDMI Audio Controller                                         | 25        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 24        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 24        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 24        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 24        | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 20        | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 20        | 0.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 310       | 25.2%   |
| SK hynix            | 227       | 18.46%  |
| Kingston            | 183       | 14.88%  |
| Micron Technology   | 129       | 10.49%  |
| Corsair             | 124       | 10.08%  |
| Unknown             | 92        | 7.48%   |
| Crucial             | 47        | 3.82%   |
| G.Skill             | 34        | 2.76%   |
| Elpida              | 17        | 1.38%   |
| A-DATA Technology   | 13        | 1.06%   |
| Ramaxel Technology  | 11        | 0.89%   |
| Nanya Technology    | 6         | 0.49%   |
| Unknown             | 6         | 0.49%   |
| Patriot             | 5         | 0.41%   |
| Unknown (ABCD)      | 3         | 0.24%   |
| Hewlett-Packard     | 3         | 0.24%   |
| Avant               | 3         | 0.24%   |
| Unknown (0x9801)    | 2         | 0.16%   |
| Apacer              | 2         | 0.16%   |
| Unknown (08AE)      | 1         | 0.08%   |
| Unifosa             | 1         | 0.08%   |
| Princeton           | 1         | 0.08%   |
| Patriot Memory      | 1         | 0.08%   |
| OnBoard             | 1         | 0.08%   |
| OCZ                 | 1         | 0.08%   |
| KANMEIQi            | 1         | 0.08%   |
| HPE                 | 1         | 0.08%   |
| G-Alantic           | 1         | 0.08%   |
| ASint Technology    | 1         | 0.08%   |
| Advantech           | 1         | 0.08%   |
| A-DA                | 1         | 0.08%   |
| 48spaces            | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 11        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.53%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 7         | 0.53%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.45%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.45%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s           | 6         | 0.45%   |
| Unknown                                                          | 6         | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.38%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.38%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 5         | 0.38%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 5         | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 4         | 0.3%    |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 4         | 0.3%    |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 544       | 48.79%  |
| DDR3    | 387       | 34.71%  |
| LPDDR3  | 52        | 4.66%   |
| LPDDR4  | 40        | 3.59%   |
| DDR2    | 36        | 3.23%   |
| Unknown | 19        | 1.7%    |
| SDRAM   | 17        | 1.52%   |
| DDR5    | 10        | 0.9%    |
| LPDDR5  | 5         | 0.45%   |
| DDR     | 5         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 566       | 50.99%  |
| DIMM         | 440       | 39.64%  |
| Row Of Chips | 89        | 8.02%   |
| Chip         | 8         | 0.72%   |
| RIMM         | 3         | 0.27%   |
| Unknown      | 3         | 0.27%   |
| FB-DIMM      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 488       | 41.01%  |
| 4096  | 270       | 22.69%  |
| 16384 | 246       | 20.67%  |
| 2048  | 112       | 9.41%   |
| 32768 | 44        | 3.7%    |
| 1024  | 26        | 2.18%   |
| 65536 | 3         | 0.25%   |
| 512   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 240       | 20.17%  |
| 2667    | 168       | 14.12%  |
| 3200    | 156       | 13.11%  |
| 2133    | 102       | 8.57%   |
| 1333    | 87        | 7.31%   |
| 2400    | 84        | 7.06%   |
| 1334    | 41        | 3.45%   |
| 800     | 25        | 2.1%    |
| 3600    | 23        | 1.93%   |
| 2666    | 20        | 1.68%   |
| 1867    | 20        | 1.68%   |
| 4267    | 19        | 1.6%    |
| 3400    | 17        | 1.43%   |
| 3000    | 17        | 1.43%   |
| 1067    | 16        | 1.34%   |
| 667     | 15        | 1.26%   |
| 3266    | 13        | 1.09%   |
| 4800    | 12        | 1.01%   |
| Unknown | 10        | 0.84%   |
| 1066    | 9         | 0.76%   |
| 3733    | 8         | 0.67%   |
| 3466    | 7         | 0.59%   |
| 3800    | 6         | 0.5%    |
| 8400    | 5         | 0.42%   |
| 6400    | 5         | 0.42%   |
| 2933    | 5         | 0.42%   |
| 2000    | 5         | 0.42%   |
| 4266    | 4         | 0.34%   |
| 4199    | 4         | 0.34%   |
| 3666    | 4         | 0.34%   |
| 3100    | 4         | 0.34%   |
| 2465    | 4         | 0.34%   |
| 2048    | 4         | 0.34%   |
| 1866    | 4         | 0.34%   |
| 333     | 3         | 0.25%   |
| 3534    | 2         | 0.17%   |
| 3500    | 2         | 0.17%   |
| 3334    | 2         | 0.17%   |
| 2800    | 2         | 0.17%   |
| 975     | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 23        | 46%     |
| Brother Industries       | 12        | 24%     |
| Samsung Electronics      | 4         | 8%      |
| Canon                    | 4         | 8%      |
| Oki Data                 | 2         | 4%      |
| Zhuhai Poskey Technology | 1         | 2%      |
| Seiko Epson              | 1         | 2%      |
| Prolific Technology      | 1         | 2%      |
| Konica Minolta           | 1         | 2%      |
| Dymo-CoStar              | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series                             | 2         | 4%      |
| Oki Data USB Device                                        | 2         | 4%      |
| HP OfficeJet Pro 7730 series                               | 2         | 4%      |
| HP OfficeJet 6950                                          | 2         | 4%      |
| HP LaserJet Pro M148f-M149f                                | 2         | 4%      |
| HP ENVY 5540 series                                        | 2         | 4%      |
| HP Deskjet 2540 series                                     | 2         | 4%      |
| Zhuhai Poskey Printer                                      | 1         | 2%      |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 2%      |
| Samsung M332x 382x 402x Series                             | 1         | 2%      |
| Samsung C48x Series                                        | 1         | 2%      |
| Prolific PL2305 Parallel Port                              | 1         | 2%      |
| Konica Minolta Printer                                     | 1         | 2%      |
| HP Smart Tank Plus 550 series                              | 1         | 2%      |
| HP Smart Tank 7000 series                                  | 1         | 2%      |
| HP Officejet 4630 series                                   | 1         | 2%      |
| HP LaserJet P3010 Series                                   | 1         | 2%      |
| HP LaserJet P2055 series                                   | 1         | 2%      |
| HP Laserjet P1505                                          | 1         | 2%      |
| HP LaserJet 3050                                           | 1         | 2%      |
| HP LaserJet 1320                                           | 1         | 2%      |
| HP LaserJet 1020                                           | 1         | 2%      |
| HP Laser 107w                                              | 1         | 2%      |
| HP ENVY Photo 6200 series                                  | 1         | 2%      |
| HP ENVY 4520 series                                        | 1         | 2%      |
| HP DeskJet F2100 Printer series                            | 1         | 2%      |
| Dymo-CoStar LabelWriter 450                                | 1         | 2%      |
| Canon TS3300 series                                        | 1         | 2%      |
| Canon PIXMA TS6250                                         | 1         | 2%      |
| Canon PIXMA MX450 Series                                   | 1         | 2%      |
| Canon iP7200 series                                        | 1         | 2%      |
| Brother Printer                                            | 1         | 2%      |
| Brother MFC-9320CW                                         | 1         | 2%      |
| Brother MFC Composite Device                               | 1         | 2%      |
| Brother HL-L2360D series                                   | 1         | 2%      |
| Brother HL-L2350DW series                                  | 1         | 2%      |
| Brother HL-3140CW series                                   | 1         | 2%      |
| Brother HL-3040CN series                                   | 1         | 2%      |
| Brother HL-2130 series                                     | 1         | 2%      |
| Brother HL-2030 Laser Printer                              | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 50%     |
| Seiko Epson       | 3         | 21.43%  |
| Hewlett-Packard   | 2         | 14.29%  |
| Fujitsu           | 1         | 7.14%   |
| Canon Electronics | 1         | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                 | 2         | 14.29%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 7.14%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 7.14%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 7.14%   |
| HP ScanJet 4070 PhotoSmart                              | 1         | 7.14%   |
| HP ScanJet 2400c                                        | 1         | 7.14%   |
| Fujitsu ScanSnap SV600                                  | 1         | 7.14%   |
| Canon P-150 Scanner                                     | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 7.14%   |
| Canon CanoScan N650U/N656U                              | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 200                                 | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                 | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 296       | 28.19%  |
| IMC Networks                           | 82        | 7.81%   |
| Acer                                   | 75        | 7.14%   |
| Logitech                               | 72        | 6.86%   |
| Microdia                               | 62        | 5.9%    |
| Apple                                  | 60        | 5.71%   |
| Realtek Semiconductor                  | 51        | 4.86%   |
| Quanta                                 | 47        | 4.48%   |
| Sunplus Innovation Technology          | 45        | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 3.9%    |
| Lite-On Technology                     | 33        | 3.14%   |
| Suyin                                  | 30        | 2.86%   |
| Syntek                                 | 17        | 1.62%   |
| Lenovo                                 | 16        | 1.52%   |
| Luxvisions Innotech Limited            | 14        | 1.33%   |
| Samsung Electronics                    | 11        | 1.05%   |
| Ricoh                                  | 11        | 1.05%   |
| Microsoft                              | 11        | 1.05%   |
| Alcor Micro                            | 11        | 1.05%   |
| Silicon Motion                         | 7         | 0.67%   |
| Z-Star Microelectronics                | 5         | 0.48%   |
| Primax Electronics                     | 5         | 0.48%   |
| Generalplus Technology                 | 4         | 0.38%   |
| ALi                                    | 4         | 0.38%   |
| Bison Electronics                      | 3         | 0.29%   |
| Xiaomi                                 | 2         | 0.19%   |
| Tripath Technology                     | 2         | 0.19%   |
| Sonix Technology                       | 2         | 0.19%   |
| OmniVision Technologies                | 2         | 0.19%   |
| MacroSilicon                           | 2         | 0.19%   |
| Genesys Logic                          | 2         | 0.19%   |
| DigiTech                               | 2         | 0.19%   |
| Creative Technology                    | 2         | 0.19%   |
| YGTek                                  | 1         | 0.1%    |
| WCM_USB                                | 1         | 0.1%    |
| Tobii Technology AB                    | 1         | 0.1%    |
| Pixart Imaging                         | 1         | 0.1%    |
| Novatek Microelectronics               | 1         | 0.1%    |
| Nikon                                  | 1         | 0.1%    |
| Mimaki Engineering                     | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 70        | 6.56%   |
| IMC Networks Integrated Camera          | 38        | 3.56%   |
| Microdia Integrated_Webcam_HD           | 34        | 3.19%   |
| Chicony HD Webcam                       | 32        | 3%      |
| Chicony HP HD Camera                    | 22        | 2.06%   |
| Acer Integrated Camera                  | 21        | 1.97%   |
| Apple Built-in iSight                   | 20        | 1.87%   |
| Realtek Integrated_Webcam_HD            | 17        | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam       | 17        | 1.59%   |
| Lite-On Integrated Camera               | 16        | 1.5%    |
| Apple FaceTime HD Camera (Built-in)     | 15        | 1.41%   |
| Quanta HP HD Camera                     | 14        | 1.31%   |
| Logitech HD Pro Webcam C920             | 14        | 1.31%   |
| Chicony HP Wide Vision HD Camera        | 14        | 1.31%   |
| Chicony USB2.0 Camera                   | 13        | 1.22%   |
| Sunplus HD WebCam                       | 12        | 1.12%   |
| Samsung Galaxy A5 (MTP)                 | 11        | 1.03%   |
| Chicony HP Truevision HD                | 11        | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE               | 10        | 0.94%   |
| Sunplus Integrated_Webcam_HD            | 9         | 0.84%   |
| Logitech Webcam C270                    | 9         | 0.84%   |
| Chicony Integrated Camera (1280x720@30) | 9         | 0.84%   |
| Acer Lenovo EasyCamera                  | 9         | 0.84%   |
| Syntek Integrated Camera                | 8         | 0.75%   |
| Microdia Integrated Webcam              | 8         | 0.75%   |
| Lite-On HP HD Camera                    | 8         | 0.75%   |
| Chicony HD User Facing                  | 8         | 0.75%   |
| Suyin HP Truevision HD                  | 7         | 0.66%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.66%   |
| Lenovo Integrated Webcam                | 7         | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 7         | 0.66%   |
| Chicony VGA WebCam                      | 7         | 0.66%   |
| Apple FaceTime HD Camera                | 7         | 0.66%   |
| Syntek Lenovo EasyCamera                | 6         | 0.56%   |
| Quanta HD Webcam                        | 6         | 0.56%   |
| Lenovo Integrated Webcam [R5U877]       | 6         | 0.56%   |
| Chicony TOSHIBA Web Camera - HD         | 6         | 0.56%   |
| Chicony HP HD Webcam                    | 6         | 0.56%   |
| Chicony CNF9055 Toshiba Webcam          | 6         | 0.56%   |
| Acer SunplusIT Integrated Camera        | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 121       | 37.12%  |
| Synaptics                  | 118       | 36.2%   |
| Shenzhen Goodix Technology | 27        | 8.28%   |
| Upek                       | 17        | 5.21%   |
| Elan Microelectronics      | 17        | 5.21%   |
| AuthenTec                  | 14        | 4.29%   |
| LighTuning Technology      | 10        | 3.07%   |
| STMicroelectronics         | 2         | 0.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 40        | 12.27%  |
| Unknown                                                                    | 29        | 8.9%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 7.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 4.29%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 3.99%   |
| Synaptics  WBDI                                                            | 12        | 3.68%   |
| Elan ELAN:ARM-M4                                                           | 12        | 3.68%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 3.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.76%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 2.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.76%   |
| Validity Sensors VFS491                                                    | 8         | 2.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.53%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.53%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.53%   |
| AuthenTec AES2810                                                          | 5         | 1.53%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.61%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.61%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.31%   |
| Synaptics WBDI Device                                                      | 1         | 0.31%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.31%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 44        | 41.12%  |
| Broadcom                  | 36        | 33.64%  |
| Upek                      | 10        | 9.35%   |
| Yubico.com                | 4         | 3.74%   |
| O2 Micro                  | 3         | 2.8%    |
| Lenovo                    | 3         | 2.8%    |
| Clay Logic                | 2         | 1.87%   |
| OmniKey                   | 1         | 0.93%   |
| Gemalto (was Gemplus)     | 1         | 0.93%   |
| BIT4ID                    | 1         | 0.93%   |
| Aladdin Knowledge Systems | 1         | 0.93%   |
| Advanced Card Systems     | 1         | 0.93%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 41.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 11.21%  |
| Broadcom 5880                                                                | 11        | 10.28%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 9.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.54%   |
| Broadcom 58200                                                               | 6         | 5.61%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 3         | 2.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.8%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.8%    |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.93%   |
| OmniKey CardMan 4321                                                         | 1         | 0.93%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.93%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.93%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.93%   |
| BIT4ID miniLector-S                                                          | 1         | 0.93%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.93%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.93%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1236      | 64.54%  |
| 1     | 522       | 27.26%  |
| 2     | 122       | 6.37%   |
| 3     | 22        | 1.15%   |
| 4     | 9         | 0.47%   |
| 7     | 2         | 0.1%    |
| 6     | 2         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 321       | 37.81%  |
| Graphics card            | 131       | 15.43%  |
| Chipcard                 | 90        | 10.6%   |
| Net/wireless             | 89        | 10.48%  |
| Multimedia controller    | 44        | 5.18%   |
| Communication controller | 43        | 5.06%   |
| Unassigned class         | 31        | 3.65%   |
| Camera                   | 23        | 2.71%   |
| Bluetooth                | 19        | 2.24%   |
| Sound                    | 12        | 1.41%   |
| Card reader              | 12        | 1.41%   |
| Net/ethernet             | 9         | 1.06%   |
| Storage                  | 6         | 0.71%   |
| Network                  | 5         | 0.59%   |
| Modem                    | 5         | 0.59%   |
| Dvb card                 | 3         | 0.35%   |
| Storage/raid             | 2         | 0.24%   |
| Storage/nvme             | 2         | 0.24%   |
| Wireless                 | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |

