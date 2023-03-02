EndeavourOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 612

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| Medion        | Akoya E6412T                | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Acer          | Aspire E5-575G              | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| MSI           | GS75 Stealth 8SG            | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| HP            | ENVY 17                     | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| Apple         | MacBookPro16,2              | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Timi          | RedmiBook Pro 15            | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| MSI           | Prestige 15 A11SCX          | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| MSI           | Prestige 14Evo A12M         | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| HP            | 650                         | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 250 G4                      | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | GF65 Thin 9SD               | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| HP            | EliteBook 745 G6            | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | 250 G4                      | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| ASUSTek       | G74Sx                       | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Gigabyte      | AORUS 15G XC                | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| HP            | Elite x2 1012 G1            | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| HP            | EliteBook 745 G6            | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HP            | Laptop 14-fq1xxx            | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Lenovo        | V330-14ARR 81B1             | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Acer          | Aspire E5-575G              | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Acer          | Aspire A515-43              | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| Dell          | Latitude 5289               | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Sony          | VPCCA17FX                   | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| HUAWEI        | MACH-WX9                    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Google        | Celes                       | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| TrekStor      | Notebook Slim S130          | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Google        | Akemi                       | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Eluktronic... | Prometheus XVII             | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| HP            | 250 G7 Notebook PC          | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Timi          | A35S                        | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| Dell          | Inspiron 3542               | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| HP            | Laptop 14-fq0xxx            | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| HP            | 255 G7 Notebook PC          | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Dell          | Latitude E6410              | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Dell          | Precision 3560              | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| AMI           | Intel                       | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Dell          | Latitude E7440              | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Dell          | Inspiron 5577               | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Notebook      | W65_67SZ                    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| Acer          | Nitro AN515-54              | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Dell          | G7 7588                     | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| HP            | 255 G7 Notebook PC          | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Notebook      | NS50MU                      | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| MSI           | GE72 6QD                    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Acer          | Extensa 2510                | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Toshiba       | Satellite P750              | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Dell          | G7 7588                     | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| Dell          | G5 5505                     | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| HP            | Laptop 15-da0xxx            | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| Apple         | MacBookPro7,1               | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| HP            | 255 G7 Notebook PC          | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Dell          | Precision M6600             | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| HP            | Laptop 14-dk1xxx            | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Dell          | Inspiron 3493               | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| Dell          | G3 3579                     | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| Dell          | Latitude E6440              | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| Dell          | Inspiron 5559               | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Lenovo        | G505s 20255                 | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| HP            | EliteBook 8770w             | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Shinelon C... | W65KJ1_KK1                  | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| Dell          | Inspiron 7520               | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 368       | 81.24%  |
| EndeavourOS         | 85        | 18.76%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 448       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.19.7-arch1-1    | 8         | 1.62%   |
| 5.15.12-arch1-1   | 8         | 1.62%   |
| 6.1.12-arch1-1    | 7         | 1.42%   |
| 5.13.13-arch1-1   | 7         | 1.42%   |
| 6.1.1-arch1-1     | 6         | 1.22%   |
| 6.0.9-arch1-1     | 6         | 1.22%   |
| 5.15.10-arch1-1   | 6         | 1.22%   |
| 6.0.2-arch1-1     | 5         | 1.01%   |
| 6.0.12-arch1-1    | 5         | 1.01%   |
| 5.9.14-arch1-1    | 5         | 1.01%   |
| 5.19.13-arch1-1   | 5         | 1.01%   |
| 5.19.11-arch1-1   | 5         | 1.01%   |
| 5.18.16-arch1-1   | 5         | 1.01%   |
| 5.15.4-arch1-1    | 5         | 1.01%   |
| 6.1.8-arch1-1     | 4         | 0.81%   |
| 6.1.7-arch1-1     | 4         | 0.81%   |
| 6.1.4-arch1-1     | 4         | 0.81%   |
| 6.0.7-arch1-1     | 4         | 0.81%   |
| 6.0.10-arch2-1    | 4         | 0.81%   |
| 5.9.1-arch1-1     | 4         | 0.81%   |
| 5.7.8-arch1-1     | 4         | 0.81%   |
| 5.19.6-zen1-1-zen | 4         | 0.81%   |
| 5.19.12-arch1-1   | 4         | 0.81%   |
| 5.17.9-arch1-1    | 4         | 0.81%   |
| 5.17.5-arch1-1    | 4         | 0.81%   |
| 5.17.1-arch1-1    | 4         | 0.81%   |
| 5.16.8-arch1-1    | 4         | 0.81%   |
| 5.16.4-arch1-1    | 4         | 0.81%   |
| 5.16.10-arch1-1   | 4         | 0.81%   |
| 5.15.2-arch1-1    | 4         | 0.81%   |
| 5.14.9-arch2-1    | 4         | 0.81%   |
| 5.12.14-arch1-1   | 4         | 0.81%   |
| 5.11.16-arch1-1   | 4         | 0.81%   |
| 5.11.11-arch1-1   | 4         | 0.81%   |
| 6.1.5-arch2-1     | 3         | 0.61%   |
| 6.1.11-arch1-1    | 3         | 0.61%   |
| 6.0.9-zen1-1-zen  | 3         | 0.61%   |
| 6.0.6-arch1-1     | 3         | 0.61%   |
| 6.0.2-zen1-1-zen  | 3         | 0.61%   |
| 5.9.8-arch1-1     | 3         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.12 | 11        | 2.23%   |
| 6.1.1   | 10        | 2.03%   |
| 6.0.2   | 10        | 2.03%   |
| 5.19.7  | 10        | 2.03%   |
| 5.13.13 | 10        | 2.03%   |
| 6.1.12  | 9         | 1.83%   |
| 6.0.9   | 9         | 1.83%   |
| 5.15.4  | 8         | 1.62%   |
| 6.0.12  | 7         | 1.42%   |
| 5.19.13 | 7         | 1.42%   |
| 5.15.2  | 7         | 1.42%   |
| 5.12.13 | 7         | 1.42%   |
| 5.11.16 | 7         | 1.42%   |
| 6.0.6   | 6         | 1.22%   |
| 5.19.6  | 6         | 1.22%   |
| 5.19.11 | 6         | 1.22%   |
| 5.17.5  | 6         | 1.22%   |
| 5.17.1  | 6         | 1.22%   |
| 5.15.10 | 6         | 1.22%   |
| 5.14.9  | 6         | 1.22%   |
| 6.1.8   | 5         | 1.01%   |
| 6.1.7   | 5         | 1.01%   |
| 6.0.7   | 5         | 1.01%   |
| 5.9.14  | 5         | 1.01%   |
| 5.9.1   | 5         | 1.01%   |
| 5.19.9  | 5         | 1.01%   |
| 5.19.12 | 5         | 1.01%   |
| 5.18.16 | 5         | 1.01%   |
| 5.18.12 | 5         | 1.01%   |
| 5.17.3  | 5         | 1.01%   |
| 5.16.8  | 5         | 1.01%   |
| 5.16.4  | 5         | 1.01%   |
| 5.15.6  | 5         | 1.01%   |
| 5.11.11 | 5         | 1.01%   |
| 6.1.9   | 4         | 0.81%   |
| 6.1.5   | 4         | 0.81%   |
| 6.1.4   | 4         | 0.81%   |
| 6.0.10  | 4         | 0.81%   |
| 5.7.8   | 4         | 0.81%   |
| 5.17.9  | 4         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 72        | 15.06%  |
| 5.19    | 52        | 10.88%  |
| 6.1     | 50        | 10.46%  |
| 6.0     | 46        | 9.62%   |
| 5.16    | 37        | 7.74%   |
| 5.14    | 30        | 6.28%   |
| 5.17    | 29        | 6.07%   |
| 5.18    | 24        | 5.02%   |
| 5.13    | 24        | 5.02%   |
| 5.12    | 24        | 5.02%   |
| 5.9     | 21        | 4.39%   |
| 5.11    | 21        | 4.39%   |
| 5.10    | 20        | 4.18%   |
| 5.8     | 9         | 1.88%   |
| 5.7     | 8         | 1.67%   |
| 5.4     | 6         | 1.26%   |
| 5.6     | 2         | 0.42%   |
| 4.19    | 2         | 0.42%   |
| 5.17.1  | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 447       | 99.78%  |
| aarch64 | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 154       | 33.41%  |
| GNOME           | 110       | 23.86%  |
| XFCE            | 98        | 21.26%  |
| X-Cinnamon      | 17        | 3.69%   |
| i3              | 15        | 3.25%   |
| KDE             | 10        | 2.17%   |
| Budgie          | 10        | 2.17%   |
| Unknown         | 10        | 2.17%   |
| Cinnamon        | 7         | 1.52%   |
| MATE            | 5         | 1.08%   |
| sway            | 4         | 0.87%   |
| LXQt            | 4         | 0.87%   |
| openbox         | 3         | 0.65%   |
| GNOME Flashback | 3         | 0.65%   |
| Deepin          | 2         | 0.43%   |
| bspwm           | 2         | 0.43%   |
| awesome         | 2         | 0.43%   |
| qtile           | 1         | 0.22%   |
| LXDE            | 1         | 0.22%   |
| LeftWM          | 1         | 0.22%   |
| Hyprland        | 1         | 0.22%   |
| GNOME Classic   | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 335       | 73.79%  |
| Wayland | 94        | 20.7%   |
| Tty     | 17        | 3.74%   |
| Unknown | 8         | 1.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 145       | 31.59%  |
| Unknown | 112       | 24.4%   |
| SDDM    | 107       | 23.31%  |
| GDM     | 68        | 14.81%  |
| TDM     | 26        | 5.66%   |
| GREETD  | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 225       | 50.11%  |
| en_GB   | 35        | 7.8%    |
| it_IT   | 30        | 6.68%   |
| en_CA   | 20        | 4.45%   |
| de_DE   | 17        | 3.79%   |
| fr_FR   | 13        | 2.9%    |
| en_IN   | 10        | 2.23%   |
| en_AU   | 7         | 1.56%   |
| ru_RU   | 6         | 1.34%   |
| pt_BR   | 6         | 1.34%   |
| fi_FI   | 6         | 1.34%   |
| es_ES   | 6         | 1.34%   |
| Unknown | 6         | 1.34%   |
| tr_TR   | 4         | 0.89%   |
| pl_PL   | 4         | 0.89%   |
| nl_NL   | 4         | 0.89%   |
| es_MX   | 4         | 0.89%   |
| en_PH   | 4         | 0.89%   |
| en_NZ   | 4         | 0.89%   |
| sv_SE   | 3         | 0.67%   |
| pt_PT   | 3         | 0.67%   |
| es_AR   | 3         | 0.67%   |
| en_DK   | 3         | 0.67%   |
| de_AT   | 3         | 0.67%   |
| ru_UA   | 2         | 0.45%   |
| en_AG   | 2         | 0.45%   |
| zh_CN   | 1         | 0.22%   |
| sr_RS   | 1         | 0.22%   |
| nl_BE   | 1         | 0.22%   |
| ko_KR   | 1         | 0.22%   |
| id_ID   | 1         | 0.22%   |
| hu_HU   | 1         | 0.22%   |
| hr_HR   | 1         | 0.22%   |
| es_US   | 1         | 0.22%   |
| es_PY   | 1         | 0.22%   |
| en_ZA   | 1         | 0.22%   |
| en_SG   | 1         | 0.22%   |
| en_MY   | 1         | 0.22%   |
| en_IL   | 1         | 0.22%   |
| en_HK   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 300       | 66.37%  |
| BIOS | 152       | 33.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 325       | 72.22%  |
| Btrfs   | 104       | 23.11%  |
| Overlay | 11        | 2.44%   |
| Xfs     | 6         | 1.33%   |
| Tmpfs   | 1         | 0.22%   |
| F2fs    | 1         | 0.22%   |
| Ext2    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 299       | 66.15%  |
| Unknown | 115       | 25.44%  |
| MBR     | 38        | 8.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 403       | 89.56%  |
| Yes       | 47        | 10.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 326       | 71.65%  |
| Yes       | 129       | 28.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 123       | 27.46%  |
| Hewlett-Packard     | 72        | 16.07%  |
| ASUSTek Computer    | 67        | 14.96%  |
| Dell                | 52        | 11.61%  |
| Acer                | 31        | 6.92%   |
| MSI                 | 19        | 4.24%   |
| Apple               | 15        | 3.35%   |
| HUAWEI              | 11        | 2.46%   |
| Google              | 8         | 1.79%   |
| Toshiba             | 6         | 1.34%   |
| Timi                | 6         | 1.34%   |
| Schenker            | 3         | 0.67%   |
| Gigabyte Technology | 3         | 0.67%   |
| Unknown             | 3         | 0.67%   |
| TrekStor            | 2         | 0.45%   |
| Sony                | 2         | 0.45%   |
| Samsung Electronics | 2         | 0.45%   |
| Razer               | 2         | 0.45%   |
| Positivo            | 2         | 0.45%   |
| Packard Bell        | 2         | 0.45%   |
| Notebook            | 2         | 0.45%   |
| Chuwi               | 2         | 0.45%   |
| TUXEDO              | 1         | 0.22%   |
| Shinelon Computer   | 1         | 0.22%   |
| Radxa               | 1         | 0.22%   |
| Pine Microsystems   | 1         | 0.22%   |
| PC Specialist       | 1         | 0.22%   |
| ILLEGEAR            | 1         | 0.22%   |
| HONOR               | 1         | 0.22%   |
| GPD                 | 1         | 0.22%   |
| Framework           | 1         | 0.22%   |
| Eluktronics         | 1         | 0.22%   |
| Dynabook            | 1         | 0.22%   |
| AMI                 | 1         | 0.22%   |
| Alienware           | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.89%   |
| Apple MacBookAir7,2                   | 4         | 0.89%   |
| MSI Modern 14 B5M                     | 3         | 0.67%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.67%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.67%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.67%   |
| Unknown                               | 3         | 0.67%   |
| Timi A35S                             | 2         | 0.45%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.45%   |
| Positivo S14BW01                      | 2         | 0.45%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.45%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.45%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.45%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 2         | 0.45%   |
| Lenovo Legion 5 15ACH6H 82JU          | 2         | 0.45%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 2         | 0.45%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.45%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 2         | 0.45%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.45%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 2         | 0.45%   |
| HUAWEI MACH-WX9                       | 2         | 0.45%   |
| HP ZBook 15 G4                        | 2         | 0.45%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 2         | 0.45%   |
| HP Notebook                           | 2         | 0.45%   |
| HP Laptop 15-da0xxx                   | 2         | 0.45%   |
| HP ENVY Laptop 13-ba0xxx              | 2         | 0.45%   |
| HP EliteBook 745 G6                   | 2         | 0.45%   |
| HP 255 G7 Notebook PC                 | 2         | 0.45%   |
| HP 250 G7 Notebook PC                 | 2         | 0.45%   |
| Dell XPS 15 7590                      | 2         | 0.45%   |
| Dell Latitude E6440                   | 2         | 0.45%   |
| Dell Inspiron 3542                    | 2         | 0.45%   |
| Dell Inspiron 15-3567                 | 2         | 0.45%   |
| Dell G7 7588                          | 2         | 0.45%   |
| Dell G3 3500                          | 2         | 0.45%   |
| Chuwi GemiBook Pro                    | 2         | 0.45%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR | 2         | 0.45%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR | 2         | 0.45%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 2         | 0.45%   |
| ASUS GL753VE                          | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 62        | 13.84%  |
| Lenovo IdeaPad     | 33        | 7.37%   |
| ASUS ROG           | 23        | 5.13%   |
| Dell Latitude      | 19        | 4.24%   |
| Acer Aspire        | 18        | 4.02%   |
| HP Pavilion        | 17        | 3.79%   |
| Dell Inspiron      | 16        | 3.57%   |
| HP Laptop          | 12        | 2.68%   |
| HP EliteBook       | 12        | 2.68%   |
| Lenovo ThinkBook   | 7         | 1.56%   |
| Lenovo Legion      | 7         | 1.56%   |
| HP ENVY            | 6         | 1.34%   |
| Dell Precision     | 6         | 1.34%   |
| ASUS ASUS          | 6         | 1.34%   |
| Toshiba Satellite  | 5         | 1.12%   |
| MSI Modern         | 5         | 1.12%   |
| Lenovo Yoga        | 5         | 1.12%   |
| ASUS TUF           | 5         | 1.12%   |
| Acer Swift         | 5         | 1.12%   |
| HP 255             | 4         | 0.89%   |
| Dell XPS           | 4         | 0.89%   |
| ASUS ZenBook       | 4         | 0.89%   |
| ASUS VivoBook      | 4         | 0.89%   |
| Apple MacBookAir7  | 4         | 0.89%   |
| Schenker XMG       | 3         | 0.67%   |
| MSI Prestige       | 3         | 0.67%   |
| HUAWEI KLVL-WXX9   | 3         | 0.67%   |
| HP ZBook           | 3         | 0.67%   |
| HP ProBook         | 3         | 0.67%   |
| HP 250             | 3         | 0.67%   |
| Dell G3            | 3         | 0.67%   |
| Apple MacBookPro16 | 3         | 0.67%   |
| Apple MacBookPro14 | 3         | 0.67%   |
| Acer Extensa       | 3         | 0.67%   |
| Unknown            | 3         | 0.67%   |
| Timi RedmiBook     | 2         | 0.45%   |
| Timi A35S          | 2         | 0.45%   |
| Samsung 340XAA     | 2         | 0.45%   |
| Razer Blade        | 2         | 0.45%   |
| Positivo S14BW01   | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 70        | 15.63%  |
| 2020    | 69        | 15.4%   |
| 2019    | 48        | 10.71%  |
| 2018    | 41        | 9.15%   |
| 2017    | 33        | 7.37%   |
| 2015    | 30        | 6.7%    |
| 2022    | 28        | 6.25%   |
| 2016    | 27        | 6.03%   |
| 2013    | 27        | 6.03%   |
| 2012    | 17        | 3.79%   |
| 2014    | 16        | 3.57%   |
| 2011    | 16        | 3.57%   |
| 2010    | 9         | 2.01%   |
| 2008    | 8         | 1.79%   |
| 2009    | 4         | 0.89%   |
| 2007    | 3         | 0.67%   |
| 2023    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 448       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 448       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 439       | 97.99%  |
| Yes  | 9         | 2.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 138       | 30.73%  |
| 8.01-16.0   | 108       | 24.05%  |
| 16.01-24.0  | 92        | 20.49%  |
| 3.01-4.0    | 52        | 11.58%  |
| 32.01-64.0  | 38        | 8.46%   |
| 24.01-32.0  | 11        | 2.45%   |
| 64.01-256.0 | 5         | 1.11%   |
| 1.01-2.0    | 3         | 0.67%   |
| 2.01-3.0    | 2         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 131       | 27.23%  |
| 1.01-2.0   | 128       | 26.61%  |
| 3.01-4.0   | 89        | 18.5%   |
| 4.01-8.0   | 88        | 18.3%   |
| 0.51-1.0   | 20        | 4.16%   |
| 8.01-16.0  | 18        | 3.74%   |
| 16.01-24.0 | 4         | 0.83%   |
| 0.01-0.5   | 2         | 0.42%   |
| 24.01-32.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 317       | 69.82%  |
| 2      | 121       | 26.65%  |
| 3      | 11        | 2.42%   |
| 4      | 3         | 0.66%   |
| 0      | 2         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 354       | 78.84%  |
| Yes       | 95        | 21.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 341       | 75.78%  |
| No        | 109       | 24.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 440       | 98%     |
| No        | 9         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 406       | 90.22%  |
| No        | 44        | 9.78%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 97        | 21.51%  |
| Italy       | 44        | 9.76%   |
| Germany     | 27        | 5.99%   |
| Canada      | 19        | 4.21%   |
| France      | 18        | 3.99%   |
| UK          | 15        | 3.33%   |
| India       | 15        | 3.33%   |
| Netherlands | 14        | 3.1%    |
| Finland     | 14        | 3.1%    |
| Brazil      | 14        | 3.1%    |
| Poland      | 11        | 2.44%   |
| Russia      | 10        | 2.22%   |
| Turkey      | 9         | 2%      |
| Spain       | 9         | 2%      |
| Sweden      | 7         | 1.55%   |
| Australia   | 7         | 1.55%   |
| Ukraine     | 6         | 1.33%   |
| Romania     | 6         | 1.33%   |
| Mexico      | 6         | 1.33%   |
| Argentina   | 6         | 1.33%   |
| Indonesia   | 5         | 1.11%   |
| Austria     | 5         | 1.11%   |
| Portugal    | 4         | 0.89%   |
| Philippines | 4         | 0.89%   |
| New Zealand | 4         | 0.89%   |
| Malaysia    | 4         | 0.89%   |
| Hong Kong   | 4         | 0.89%   |
| Denmark     | 4         | 0.89%   |
| Belgium     | 4         | 0.89%   |
| Bangladesh  | 4         | 0.89%   |
| Vietnam     | 3         | 0.67%   |
| Norway      | 3         | 0.67%   |
| Greece      | 3         | 0.67%   |
| Bahrain     | 3         | 0.67%   |
| Taiwan      | 2         | 0.44%   |
| Switzerland | 2         | 0.44%   |
| South Korea | 2         | 0.44%   |
| Slovenia    | 2         | 0.44%   |
| Singapore   | 2         | 0.44%   |
| Serbia      | 2         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Helsinki          | 11        | 2.36%   |
| Toms River        | 7         | 1.5%    |
| Amsterdam         | 6         | 1.29%   |
| Montreal          | 5         | 1.07%   |
| Barberton         | 5         | 1.07%   |
| Victoria          | 4         | 0.86%   |
| Sydney            | 4         | 0.86%   |
| Rome              | 4         | 0.86%   |
| London            | 4         | 0.86%   |
| Istanbul          | 4         | 0.86%   |
| Berlin            | 4         | 0.86%   |
| St Petersburg     | 3         | 0.64%   |
| Paris             | 3         | 0.64%   |
| Moscow            | 3         | 0.64%   |
| Manama            | 3         | 0.64%   |
| Jacksonville      | 3         | 0.64%   |
| Innsbruck         | 3         | 0.64%   |
| Greeley           | 3         | 0.64%   |
| Frankfurt am Main | 3         | 0.64%   |
| Florence          | 3         | 0.64%   |
| Central           | 3         | 0.64%   |
| Zurich            | 2         | 0.43%   |
| Warsaw            | 2         | 0.43%   |
| Villa Ballester   | 2         | 0.43%   |
| Turku             | 2         | 0.43%   |
| Tulsa             | 2         | 0.43%   |
| Toronto           | 2         | 0.43%   |
| Sterling          | 2         | 0.43%   |
| Sofia             | 2         | 0.43%   |
| Singapore         | 2         | 0.43%   |
| Severna Park      | 2         | 0.43%   |
| Portland          | 2         | 0.43%   |
| Omaha             | 2         | 0.43%   |
| Oldenburg         | 2         | 0.43%   |
| Naples            | 2         | 0.43%   |
| Milan             | 2         | 0.43%   |
| Mexico City       | 2         | 0.43%   |
| Mesa              | 2         | 0.43%   |
| Mérida           | 2         | 0.43%   |
| Mannheim          | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 134       | 167    | 23.1%   |
| Seagate                        | 48        | 51     | 8.28%   |
| SanDisk                        | 46        | 49     | 7.93%   |
| WDC                            | 42        | 47     | 7.24%   |
| SK hynix                       | 36        | 42     | 6.21%   |
| Kingston                       | 28        | 32     | 4.83%   |
| Toshiba                        | 21        | 23     | 3.62%   |
| Unknown                        | 19        | 26     | 3.28%   |
| Micron Technology              | 18        | 18     | 3.1%    |
| Intel                          | 17        | 19     | 2.93%   |
| HGST                           | 17        | 20     | 2.93%   |
| Crucial                        | 15        | 16     | 2.59%   |
| KIOXIA                         | 12        | 13     | 2.07%   |
| Apple                          | 12        | 15     | 2.07%   |
| A-DATA Technology              | 9         | 10     | 1.55%   |
| Phison                         | 6         | 6      | 1.03%   |
| Kingston Technology Company    | 6         | 8      | 1.03%   |
| Phison Electronics             | 5         | 5      | 0.86%   |
| LITEONIT                       | 5         | 6      | 0.86%   |
| Hitachi                        | 5         | 5      | 0.86%   |
| China                          | 5         | 5      | 0.86%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.52%   |
| Transcend                      | 3         | 3      | 0.52%   |
| PNY                            | 3         | 3      | 0.52%   |
| Mushkin                        | 3         | 3      | 0.52%   |
| Lenovo                         | 3         | 3      | 0.52%   |
| WDC WDS                        | 2         | 2      | 0.34%   |
| SSSTC                          | 2         | 2      | 0.34%   |
| Solid State Storage Technology | 2         | 3      | 0.34%   |
| Patriot                        | 2         | 2      | 0.34%   |
| OCZ                            | 2         | 2      | 0.34%   |
| Netac                          | 2         | 2      | 0.34%   |
| Micron/Crucial Technology      | 2         | 2      | 0.34%   |
| Maxone                         | 2         | 2      | 0.34%   |
| LITEON                         | 2         | 3      | 0.34%   |
| KingSpec                       | 2         | 2      | 0.34%   |
| HFS256G3                       | 2         | 2      | 0.34%   |
| Gigabyte Technology            | 2         | 3      | 0.34%   |
| Fujitsu                        | 2         | 2      | 0.34%   |
| Corsair                        | 2         | 2      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 15        | 2.49%   |
| Seagate ST1000LM035-1RK172 1TB                       | 12        | 1.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 10        | 1.66%   |
| HGST HTS721010A9E630 1TB                             | 8         | 1.33%   |
| Seagate ST500LT012-1DG142 500GB                      | 7         | 1.16%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 6         | 1%      |
| Samsung SSD 870 QVO 1TB                              | 6         | 1%      |
| Samsung NVMe SSD Drive 512GB                         | 6         | 1%      |
| SK hynix HFM001TD3JX013N 1TB                         | 5         | 0.83%   |
| Samsung SSD 870 EVO 250GB                            | 5         | 0.83%   |
| Samsung SSD 860 EVO 500GB                            | 5         | 0.83%   |
| Samsung SSD 860 EVO 250GB                            | 5         | 0.83%   |
| Samsung SSD 860 EVO 1TB                              | 5         | 0.83%   |
| Samsung SSD 850 EVO 500GB                            | 5         | 0.83%   |
| KIOXIA KBG40ZNV512G 512GB                            | 5         | 0.83%   |
| Kingston SA400S37240G 240GB SSD                      | 5         | 0.83%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 5         | 0.83%   |
| Unknown MMC Card  64GB                               | 4         | 0.66%   |
| Seagate ST1000LM049-2GH172 1TB                       | 4         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4         | 0.66%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 4         | 0.66%   |
| Samsung SSD 970 EVO 500GB                            | 4         | 0.66%   |
| Samsung MZVLQ512HBLU-00B00 512GB                     | 4         | 0.66%   |
| Samsung MZVLQ512HALU-000H1 512GB                     | 4         | 0.66%   |
| Apple SSD SM0128G 121GB                              | 4         | 0.66%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 3         | 0.5%    |
| WDC WD10SPZX-24Z10 1TB                               | 3         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                             | 3         | 0.5%    |
| Unknown MMC Card  32GB                               | 3         | 0.5%    |
| Transcend TS240GMTS420S 240GB SSD                    | 3         | 0.5%    |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                         | 3         | 0.5%    |
| Samsung NVMe SSD Drive 1TB                           | 3         | 0.5%    |
| Samsung MZVLQ512HALU-00000 512GB                     | 3         | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD 256GB          | 3         | 0.5%    |
| Kingston SA400S37480G 480GB SSD                      | 3         | 0.5%    |
| Kingston OM8PCP3512F-AB 512GB                        | 3         | 0.5%    |
| Intel SSD 660P Series 1024GB                         | 3         | 0.5%    |
| Intel NVMe SSD Drive 512GB                           | 3         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 45     | 40.95%  |
| WDC                 | 21        | 23     | 20%     |
| HGST                | 17        | 20     | 16.19%  |
| Toshiba             | 10        | 10     | 9.52%   |
| Hitachi             | 5         | 5      | 4.76%   |
| Unknown             | 2         | 2      | 1.9%    |
| Maxone              | 2         | 2      | 1.9%    |
| Fujitsu             | 2         | 2      | 1.9%    |
| USB3.0              | 1         | 1      | 0.95%   |
| Samsung Electronics | 1         | 1      | 0.95%   |
| Generic-            | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 77     | 30.54%  |
| Kingston            | 19        | 23     | 9.36%   |
| SanDisk             | 14        | 14     | 6.9%    |
| Crucial             | 13        | 13     | 6.4%    |
| WDC                 | 11        | 13     | 5.42%   |
| SK hynix            | 7         | 8      | 3.45%   |
| A-DATA Technology   | 7         | 8      | 3.45%   |
| Apple               | 6         | 6      | 2.96%   |
| Micron Technology   | 5         | 5      | 2.46%   |
| LITEONIT            | 5         | 6      | 2.46%   |
| China               | 5         | 5      | 2.46%   |
| Toshiba             | 4         | 4      | 1.97%   |
| Transcend           | 3         | 3      | 1.48%   |
| Seagate             | 3         | 3      | 1.48%   |
| Intel               | 3         | 3      | 1.48%   |
| WDC WDS             | 2         | 2      | 0.99%   |
| PNY                 | 2         | 2      | 0.99%   |
| Patriot             | 2         | 2      | 0.99%   |
| OCZ                 | 2         | 2      | 0.99%   |
| Netac               | 2         | 2      | 0.99%   |
| Mushkin             | 2         | 2      | 0.99%   |
| KingSpec            | 2         | 2      | 0.99%   |
| Gigabyte Technology | 2         | 3      | 0.99%   |
| Corsair             | 2         | 2      | 0.99%   |
| Zheino              | 1         | 1      | 0.49%   |
| WALTON              | 1         | 2      | 0.49%   |
| V-GeN               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 2      | 0.49%   |
| Teclast             | 1         | 3      | 0.49%   |
| Team                | 1         | 2      | 0.49%   |
| StoreJet            | 1         | 1      | 0.49%   |
| SPCC                | 1         | 1      | 0.49%   |
| OCZ-VERTEX          | 1         | 1      | 0.49%   |
| LITEON              | 1         | 1      | 0.49%   |
| KingFast            | 1         | 1      | 0.49%   |
| KingDian            | 1         | 1      | 0.49%   |
| KINGBANK            | 1         | 1      | 0.49%   |
| GOODRAM             | 1         | 1      | 0.49%   |
| FORESEE             | 1         | 1      | 0.49%   |
| Emtec               | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 236       | 290    | 43.78%  |
| SSD     | 177       | 233    | 32.84%  |
| HDD     | 102       | 112    | 18.92%  |
| MMC     | 17        | 23     | 3.15%   |
| Unknown | 7         | 7      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 239       | 320    | 46.05%  |
| NVMe | 236       | 288    | 45.47%  |
| SAS  | 27        | 34     | 5.2%    |
| MMC  | 17        | 23     | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 177       | 233    | 63.44%  |
| 0.51-1.0   | 92        | 102    | 32.97%  |
| 1.01-2.0   | 10        | 10     | 3.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 120       | 26.03%  |
| 251-500        | 103       | 22.34%  |
| 501-1000       | 65        | 14.1%   |
| 1001-2000      | 57        | 12.36%  |
| Unknown        | 30        | 6.51%   |
| 51-100         | 25        | 5.42%   |
| 1-20           | 22        | 4.77%   |
| More than 3000 | 19        | 4.12%   |
| 21-50          | 10        | 2.17%   |
| 2001-3000      | 10        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 119       | 25.05%  |
| 21-50          | 85        | 17.89%  |
| 101-250        | 81        | 17.05%  |
| 51-100         | 67        | 14.11%  |
| 251-500        | 43        | 9.05%   |
| Unknown        | 30        | 6.32%   |
| 501-1000       | 25        | 5.26%   |
| 1001-2000      | 17        | 3.58%   |
| More than 3000 | 4         | 0.84%   |
| 2001-3000      | 2         | 0.42%   |
| 0              | 2         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 9.38%   |
| HGST HTS545050A7E680 500GB                       | 3         | 4      | 9.38%   |
| Hitachi HTS545050A7E380 500GB                    | 2         | 2      | 6.25%   |
| WDC WD5000LPVT-22G33T0 500GB                     | 1         | 1      | 3.13%   |
| WDC WD10SPZX-24Z10T0 1TB                         | 1         | 1      | 3.13%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 3.13%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB             | 1         | 1      | 3.13%   |
| Transcend TS240GMTS420S 240GB SSD                | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.13%   |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 3.13%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD          | 1         | 1      | 3.13%   |
| SK hynix SC308 SATA 128GB SSD                    | 1         | 1      | 3.13%   |
| SK hynix HFS512G39TND-N210A 512GB SSD            | 1         | 1      | 3.13%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 3.13%   |
| Seagate ST500LX012-SSHD-8GB                      | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.13%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 3.13%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 3.13%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.13%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 1      | 3.13%   |
| Intel SSDSCKKF256H6 SATA 256GB                   | 1         | 1      | 3.13%   |
| Intel SSDSCKJF180A5L 180GB                       | 1         | 1      | 3.13%   |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 3.13%   |
| Apple SSD SM256C 256GB                           | 1         | 1      | 3.13%   |
| A-DATA Technology SP900 256GB SSD                | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 6         | 7      | 18.75%  |
| WDC                 | 4         | 4      | 12.5%   |
| Toshiba             | 3         | 3      | 9.38%   |
| SK hynix            | 3         | 3      | 9.38%   |
| Seagate             | 3         | 3      | 9.38%   |
| Samsung Electronics | 3         | 3      | 9.38%   |
| Intel               | 2         | 2      | 6.25%   |
| Hitachi             | 2         | 2      | 6.25%   |
| Transcend           | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 6         | 7      | 35.29%  |
| WDC     | 3         | 3      | 17.65%  |
| Seagate | 3         | 3      | 17.65%  |
| Toshiba | 2         | 2      | 11.76%  |
| Hitachi | 2         | 2      | 11.76%  |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 18     | 53.13%  |
| SSD  | 13        | 13     | 40.63%  |
| NVMe | 2         | 2      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 302       | 408    | 62.4%   |
| Detected | 149       | 222    | 30.79%  |
| Malfunc  | 32        | 33     | 6.61%   |
| Failed   | 1         | 2      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 254       | 45.12%  |
| Samsung Electronics            | 81        | 14.39%  |
| AMD                            | 65        | 11.55%  |
| SanDisk                        | 40        | 7.1%    |
| SK hynix                       | 28        | 4.97%   |
| KIOXIA                         | 15        | 2.66%   |
| Kingston Technology Company    | 15        | 2.66%   |
| Micron Technology              | 13        | 2.31%   |
| Phison Electronics             | 12        | 2.13%   |
| Apple                          | 6         | 1.07%   |
| Solid State Storage Technology | 5         | 0.89%   |
| Toshiba America Info Systems   | 4         | 0.71%   |
| Micron/Crucial Technology      | 4         | 0.71%   |
| ADATA Technology               | 4         | 0.71%   |
| Union Memory (Shenzhen)        | 3         | 0.53%   |
| Lenovo                         | 3         | 0.53%   |
| Seagate Technology             | 2         | 0.36%   |
| Lite-On Technology             | 2         | 0.36%   |
| Yangtze Memory Technologies    | 1         | 0.18%   |
| Shenzhen Longsys Electronics   | 1         | 0.18%   |
| Nvidia                         | 1         | 0.18%   |
| Marvell Technology Group       | 1         | 0.18%   |
| JMicron Technology             | 1         | 0.18%   |
| INNOGRIT                       | 1         | 0.18%   |
| Biwin Storage Technology       | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 63        | 10.84%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 45        | 7.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 40        | 6.88%   |
| Samsung NVMe SSD Controller 980                                                  | 23        | 3.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 23        | 3.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 2.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 16        | 2.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 2.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 2.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13        | 2.24%   |
| Micron Non-Volatile memory controller                                            | 13        | 2.24%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 13        | 2.24%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 2.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 12        | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 1.72%   |
| SanDisk Non-Volatile memory controller                                           | 10        | 1.72%   |
| Intel SSD 660P Series                                                            | 10        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.38%   |
| Kingston Company Company Non-Volatile memory controller                          | 8         | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 1.38%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.38%   |
| Phison E12 NVMe Controller                                                       | 6         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 1.03%   |
| Solid State Storage Non-Volatile memory controller                               | 5         | 0.86%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 5         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 0.86%   |
| SK hynix BC511                                                                   | 4         | 0.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.69%   |
| Samsung Electronics SATA controller                                              | 4         | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 282       | 50.54%  |
| NVMe | 234       | 41.94%  |
| RAID | 37        | 6.63%   |
| IDE  | 5         | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 314       | 70.09%  |
| AMD    | 133       | 29.69%  |
| ARM    | 1         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 2.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 2.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 2.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 1.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 1.56%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.34%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.34%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.34%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 1.34%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 1.12%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.12%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.12%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 1.12%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 1.12%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.89%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.89%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 4         | 0.89%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.89%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 3         | 0.67%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 3         | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.67%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 113       | 25.22%  |
| Intel Core i7           | 101       | 22.54%  |
| Other                   | 43        | 9.6%    |
| AMD Ryzen 7             | 41        | 9.15%   |
| AMD Ryzen 5             | 36        | 8.04%   |
| Intel Core i3           | 21        | 4.69%   |
| Intel Celeron           | 19        | 4.24%   |
| AMD Ryzen 9             | 15        | 3.35%   |
| Intel Core 2 Duo        | 11        | 2.46%   |
| AMD Ryzen 7 PRO         | 11        | 2.46%   |
| AMD A4                  | 8         | 1.79%   |
| AMD Ryzen 3             | 5         | 1.12%   |
| Intel Pentium           | 3         | 0.67%   |
| AMD Ryzen 5 PRO         | 3         | 0.67%   |
| AMD A8                  | 3         | 0.67%   |
| Intel Atom              | 2         | 0.45%   |
| AMD E1                  | 2         | 0.45%   |
| AMD A10                 | 2         | 0.45%   |
| Intel Xeon              | 1         | 0.22%   |
| Intel Pentium Dual-Core | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core m3           | 1         | 0.22%   |
| Intel Core 2 Extreme    | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |
| AMD Athlon II           | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 162       | 36.16%  |
| 4      | 158       | 35.27%  |
| 8      | 71        | 15.85%  |
| 6      | 47        | 10.49%  |
| 14     | 6         | 1.34%   |
| 12     | 2         | 0.45%   |
| 10     | 1         | 0.22%   |
| 1      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 447       | 99.78%  |
| 2      | 1         | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 379       | 84.6%   |
| 1      | 69        | 15.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 446       | 99.55%  |
| 64-bit         | 1         | 0.22%   |
| Unknown        | 1         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 27.81%  |
| 0x0a50000c | 21        | 4.64%   |
| 0x806ec    | 18        | 3.97%   |
| 0x406e3    | 18        | 3.97%   |
| 0x806c1    | 14        | 3.09%   |
| 0x40651    | 14        | 3.09%   |
| 0x306a9    | 14        | 3.09%   |
| 0x906ea    | 13        | 2.87%   |
| 0x806ea    | 13        | 2.87%   |
| 0x806e9    | 13        | 2.87%   |
| 0x306c3    | 12        | 2.65%   |
| 0x08600106 | 12        | 2.65%   |
| 0x08600104 | 11        | 2.43%   |
| 0x08608103 | 10        | 2.21%   |
| 0x08108109 | 10        | 2.21%   |
| 0x906e9    | 9         | 1.99%   |
| 0x506e3    | 9         | 1.99%   |
| 0x306d4    | 8         | 1.77%   |
| 0x206a7    | 8         | 1.77%   |
| 0x08108102 | 8         | 1.77%   |
| 0x706e5    | 7         | 1.55%   |
| 0xa0652    | 6         | 1.32%   |
| 0x906a3    | 6         | 1.32%   |
| 0x806d1    | 6         | 1.32%   |
| 0x406c4    | 6         | 1.32%   |
| 0x1067a    | 6         | 1.32%   |
| 0x706a1    | 5         | 1.1%    |
| 0x20655    | 5         | 1.1%    |
| 0x06006705 | 4         | 0.88%   |
| 0x0a404102 | 3         | 0.66%   |
| 0x906ed    | 2         | 0.44%   |
| 0x906c0    | 2         | 0.44%   |
| 0x806eb    | 2         | 0.44%   |
| 0x406c3    | 2         | 0.44%   |
| 0x10676    | 2         | 0.44%   |
| 0x0a50000b | 2         | 0.44%   |
| 0x08600103 | 2         | 0.44%   |
| 0x08600102 | 2         | 0.44%   |
| 0x07000110 | 2         | 0.44%   |
| 0x0700010f | 2         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 97        | 21.65%  |
| Zen 2            | 35        | 7.81%   |
| Skylake          | 33        | 7.37%   |
| Haswell          | 33        | 7.37%   |
| Zen 3            | 30        | 6.7%    |
| Unknown          | 27        | 6.03%   |
| Zen+             | 23        | 5.13%   |
| TigerLake        | 22        | 4.91%   |
| IvyBridge        | 20        | 4.46%   |
| IceLake          | 16        | 3.57%   |
| Broadwell        | 15        | 3.35%   |
| SandyBridge      | 13        | 2.9%    |
| Silvermont       | 12        | 2.68%   |
| Penryn           | 11        | 2.46%   |
| CometLake        | 11        | 2.46%   |
| Excavator        | 9         | 2.01%   |
| Westmere         | 8         | 1.79%   |
| Alderlake Hybrid | 7         | 1.56%   |
| Jaguar           | 6         | 1.34%   |
| Goldmont plus    | 6         | 1.34%   |
| Core             | 3         | 0.67%   |
| Zen              | 2         | 0.45%   |
| Tremont          | 2         | 0.45%   |
| Puma             | 2         | 0.45%   |
| Piledriver       | 2         | 0.45%   |
| K10              | 1         | 0.22%   |
| Goldmont         | 1         | 0.22%   |
| Bobcat           | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 291       | 48.99%  |
| Nvidia | 152       | 25.59%  |
| AMD    | 151       | 25.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 35        | 5.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26        | 4.26%   |
| Intel UHD Graphics 620                                                                   | 23        | 3.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 3.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 3.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 3.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 3.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 2.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.29%   |
| Intel HD Graphics 620                                                                    | 13        | 2.13%   |
| AMD Lucienne                                                                             | 13        | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.96%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.47%   |
| Intel HD Graphics 630                                                                    | 9         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.47%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 1.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.31%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 8         | 1.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 1.15%   |
| Intel HD Graphics 530                                                                    | 7         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.15%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.98%   |
| Nvidia TU117M                                                                            | 5         | 0.82%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.82%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.82%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 4         | 0.65%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                                             | 4         | 0.65%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 171       | 38.17%  |
| Intel + Nvidia | 106       | 23.66%  |
| 1 x AMD        | 96        | 21.43%  |
| AMD + Nvidia   | 27        | 6.03%   |
| 1 x Nvidia     | 18        | 4.02%   |
| 2 x AMD        | 15        | 3.35%   |
| Intel + AMD    | 13        | 2.9%    |
| Other          | 1         | 0.22%   |
| 2 x Intel      | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 340       | 75.72%  |
| Proprietary | 108       | 24.05%  |
| Unknown     | 1         | 0.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 65.42%  |
| 0.01-0.5   | 66        | 14.54%  |
| 1.01-2.0   | 35        | 7.71%   |
| 3.01-4.0   | 20        | 4.41%   |
| 0.51-1.0   | 14        | 3.08%   |
| 7.01-8.0   | 9         | 1.98%   |
| 5.01-6.0   | 6         | 1.32%   |
| 2.01-3.0   | 6         | 1.32%   |
| 8.01-16.0  | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 116       | 21.6%   |
| BOE                     | 78        | 14.53%  |
| Chimei Innolux          | 73        | 13.59%  |
| LG Display              | 63        | 11.73%  |
| Samsung Electronics     | 36        | 6.7%    |
| PANDA                   | 17        | 3.17%   |
| Apple                   | 15        | 2.79%   |
| Sharp                   | 14        | 2.61%   |
| Dell                    | 14        | 2.61%   |
| Goldstar                | 13        | 2.42%   |
| Lenovo                  | 11        | 2.05%   |
| AOC                     | 8         | 1.49%   |
| InfoVision              | 7         | 1.3%    |
| Philips                 | 6         | 1.12%   |
| BenQ                    | 6         | 1.12%   |
| Ancor Communications    | 6         | 1.12%   |
| Acer                    | 6         | 1.12%   |
| TMX                     | 4         | 0.74%   |
| CSO                     | 4         | 0.74%   |
| Chi Mei Optoelectronics | 4         | 0.74%   |
| ViewSonic               | 3         | 0.56%   |
| Sony                    | 3         | 0.56%   |
| LG Philips              | 3         | 0.56%   |
| Hewlett-Packard         | 3         | 0.56%   |
| Pixio                   | 2         | 0.37%   |
| JDI                     | 2         | 0.37%   |
| InnoLux Display         | 2         | 0.37%   |
| Iiyama                  | 2         | 0.37%   |
| ASUSTek Computer        | 2         | 0.37%   |
| Vizio                   | 1         | 0.19%   |
| Unknown                 | 1         | 0.19%   |
| Toshiba                 | 1         | 0.19%   |
| Sun                     | 1         | 0.19%   |
| Sceptre Tech            | 1         | 0.19%   |
| RTK                     | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| MSI                     | 1         | 0.19%   |
| HUAWEI                  | 1         | 0.19%   |
| HKC                     | 1         | 0.19%   |
| Gigabyte Technology     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 7         | 1.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 6         | 1.11%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 6         | 1.11%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 5         | 0.92%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 5         | 0.92%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 5         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 4         | 0.74%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 3         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch   | 3         | 0.55%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch           | 3         | 0.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 3         | 0.55%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 3         | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3         | 0.55%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 3         | 0.55%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 3         | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.55%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch          | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 3         | 0.55%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                | 2         | 0.37%   |
| TMX TL140ADXP01 TMX1481 2560x1600 301x188mm 14.0-inch                  | 2         | 0.37%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                | 2         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch | 2         | 0.37%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                       | 2         | 0.37%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 2         | 0.37%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 263       | 51.87%  |
| 1366x768 (WXGA)    | 108       | 21.3%   |
| 2560x1440 (QHD)    | 26        | 5.13%   |
| 3840x2160 (4K)     | 18        | 3.55%   |
| 2560x1600          | 14        | 2.76%   |
| 1440x900 (WXGA+)   | 12        | 2.37%   |
| 1920x1200 (WUXGA)  | 10        | 1.97%   |
| 1280x800 (WXGA)    | 8         | 1.58%   |
| 2880x1800          | 7         | 1.38%   |
| 2160x1440          | 7         | 1.38%   |
| 2560x1080          | 4         | 0.79%   |
| 1600x900 (HD+)     | 4         | 0.79%   |
| 1680x1050 (WSXGA+) | 3         | 0.59%   |
| 3840x2400          | 2         | 0.39%   |
| 3840x1080          | 2         | 0.39%   |
| 3456x2160          | 2         | 0.39%   |
| 3440x1440          | 2         | 0.39%   |
| 3200x2000          | 2         | 0.39%   |
| 3200x1800 (QHD+)   | 2         | 0.39%   |
| 3000x2000          | 2         | 0.39%   |
| 1360x768           | 2         | 0.39%   |
| 1280x1024 (SXGA)   | 2         | 0.39%   |
| 3072x1920          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 2240x1400          | 1         | 0.2%    |
| 1920x1280          | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 206       | 38.08%  |
| 13      | 89        | 16.45%  |
| 14      | 70        | 12.94%  |
| 17      | 33        | 6.1%    |
| 27      | 23        | 4.25%   |
| 24      | 17        | 3.14%   |
| 23      | 13        | 2.4%    |
| 12      | 12        | 2.22%   |
| 16      | 11        | 2.03%   |
| 21      | 10        | 1.85%   |
| 11      | 9         | 1.66%   |
| 31      | 7         | 1.29%   |
| 18      | 7         | 1.29%   |
| 34      | 4         | 0.74%   |
| Unknown | 3         | 0.55%   |
| 54      | 2         | 0.37%   |
| 49      | 2         | 0.37%   |
| 29      | 2         | 0.37%   |
| 26      | 2         | 0.37%   |
| 25      | 2         | 0.37%   |
| 22      | 2         | 0.37%   |
| 10      | 2         | 0.37%   |
| 84      | 1         | 0.18%   |
| 72      | 1         | 0.18%   |
| 65      | 1         | 0.18%   |
| 58      | 1         | 0.18%   |
| 57      | 1         | 0.18%   |
| 46      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 40      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 28      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |
| 19      | 1         | 0.18%   |
| 8       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 323       | 60.04%  |
| 201-300     | 70        | 13.01%  |
| 501-600     | 57        | 10.59%  |
| 351-400     | 39        | 7.25%   |
| 401-500     | 20        | 3.72%   |
| 601-700     | 10        | 1.86%   |
| 1001-1500   | 6         | 1.12%   |
| 701-800     | 5         | 0.93%   |
| Unknown     | 3         | 0.56%   |
| 1501-2000   | 2         | 0.37%   |
| 801-900     | 1         | 0.19%   |
| 101-200     | 1         | 0.19%   |
| 901-1000    | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 381       | 82.11%  |
| 16/10   | 58        | 12.5%   |
| 3/2     | 12        | 2.59%   |
| 21/9    | 4         | 0.86%   |
| 4/3     | 2         | 0.43%   |
| 2.65    | 2         | 0.43%   |
| Unknown | 2         | 0.43%   |
| 5/4     | 1         | 0.22%   |
| 32/9    | 1         | 0.22%   |
| 0.62    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 207       | 38.55%  |
| 81-90          | 126       | 23.46%  |
| 71-80          | 35        | 6.52%   |
| 201-250        | 35        | 6.52%   |
| 121-130        | 29        | 5.4%    |
| 301-350        | 25        | 4.66%   |
| 351-500        | 13        | 2.42%   |
| 61-70          | 10        | 1.86%   |
| 111-120        | 10        | 1.86%   |
| 51-60          | 9         | 1.68%   |
| 251-300        | 8         | 1.49%   |
| 141-150        | 7         | 1.3%    |
| More than 1000 | 6         | 1.12%   |
| 131-140        | 4         | 0.74%   |
| 501-1000       | 4         | 0.74%   |
| 151-200        | 3         | 0.56%   |
| Unknown        | 3         | 0.56%   |
| 41-50          | 2         | 0.37%   |
| 1-40           | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 251       | 47.45%  |
| 101-120       | 117       | 22.12%  |
| 51-100        | 68        | 12.85%  |
| 161-240       | 60        | 11.34%  |
| More than 240 | 23        | 4.35%   |
| 1-50          | 7         | 1.32%   |
| Unknown       | 3         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 357       | 78.46%  |
| 2     | 92        | 20.22%  |
| 3     | 5         | 1.1%    |
| 0     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 266       | 37.52%  |
| Realtek Semiconductor             | 258       | 36.39%  |
| Qualcomm Atheros                  | 68        | 9.59%   |
| MediaTek                          | 26        | 3.67%   |
| Broadcom                          | 26        | 3.67%   |
| Broadcom Limited                  | 8         | 1.13%   |
| ASIX Electronics                  | 8         | 1.13%   |
| TP-Link                           | 7         | 0.99%   |
| D-Link                            | 6         | 0.85%   |
| Lenovo                            | 4         | 0.56%   |
| Hewlett-Packard                   | 4         | 0.56%   |
| Sierra Wireless                   | 3         | 0.42%   |
| Apple                             | 3         | 0.42%   |
| Ralink                            | 2         | 0.28%   |
| Qualcomm                          | 2         | 0.28%   |
| Ericsson Business Mobile Networks | 2         | 0.28%   |
| DisplayLink                       | 2         | 0.28%   |
| Cypress Semiconductor             | 2         | 0.28%   |
| Samsung Electronics               | 1         | 0.14%   |
| OPPO                              | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.14%   |
| NetGear                           | 1         | 0.14%   |
| Marvell Technology Group          | 1         | 0.14%   |
| Linksys                           | 1         | 0.14%   |
| ICS Advent                        | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| FIBOCOM                           | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| Belkin Components                 | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 173       | 20.47%  |
| Intel Wi-Fi 6 AX200                                               | 44        | 5.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 3.08%   |
| Intel Wireless 8265 / 8275                                        | 24        | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 2.13%   |
| Intel Wireless 7260                                               | 18        | 2.13%   |
| Intel Wireless 7265                                               | 17        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.54%   |
| Intel Wireless 8260                                               | 12        | 1.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 1.18%   |
| Intel Wireless 3165                                               | 10        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.71%   |
| Realtek 802.11ac NIC                                              | 6         | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.71%   |
| D-Link 802.11ac NIC                                               | 6         | 0.71%   |
| TP-Link 802.11ac NIC                                              | 5         | 0.59%   |
| Realtek Realtek Network controller                                | 5         | 0.59%   |
| Intel Wireless 3160                                               | 5         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 264       | 56.41%  |
| Realtek Semiconductor             | 73        | 15.6%   |
| Qualcomm Atheros                  | 59        | 12.61%  |
| MediaTek                          | 20        | 4.27%   |
| Broadcom                          | 20        | 4.27%   |
| Broadcom Limited                  | 8         | 1.71%   |
| TP-Link                           | 6         | 1.28%   |
| D-Link                            | 6         | 1.28%   |
| Sierra Wireless                   | 3         | 0.64%   |
| Ralink                            | 2         | 0.43%   |
| Qualcomm                          | 2         | 0.43%   |
| Linksys                           | 1         | 0.21%   |
| FIBOCOM                           | 1         | 0.21%   |
| Ericsson Business Mobile Networks | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| Belkin Components                 | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 44        | 9.3%    |
| Intel Wireless 8265 / 8275                                     | 24        | 5.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 4.02%   |
| Intel Wireless 7260                                            | 18        | 3.81%   |
| Intel Wireless 7265                                            | 17        | 3.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 3.38%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 2.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 2.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 2.75%   |
| Intel Wireless 8260                                            | 12        | 2.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 10        | 2.11%   |
| Intel Wireless 3165                                            | 10        | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 8         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.48%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.27%   |
| Realtek 802.11ac NIC                                           | 6         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.27%   |
| D-Link 802.11ac NIC                                            | 6         | 1.27%   |
| TP-Link 802.11ac NIC                                           | 5         | 1.06%   |
| Realtek Realtek Network controller                             | 5         | 1.06%   |
| Intel Wireless 3160                                            | 5         | 1.06%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.06%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 227       | 63.23%  |
| Intel                    | 73        | 20.33%  |
| Qualcomm Atheros         | 18        | 5.01%   |
| Broadcom                 | 9         | 2.51%   |
| ASIX Electronics         | 8         | 2.23%   |
| MediaTek                 | 6         | 1.67%   |
| Lenovo                   | 3         | 0.84%   |
| Apple                    | 3         | 0.84%   |
| DisplayLink              | 2         | 0.56%   |
| Cypress Semiconductor    | 2         | 0.56%   |
| TP-Link                  | 1         | 0.28%   |
| Samsung Electronics      | 1         | 0.28%   |
| OPPO                     | 1         | 0.28%   |
| NetGear                  | 1         | 0.28%   |
| Marvell Technology Group | 1         | 0.28%   |
| ICS Advent               | 1         | 0.28%   |
| Hewlett-Packard          | 1         | 0.28%   |
| Google                   | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 173       | 47.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 7.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.74%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.92%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.37%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.1%    |
| Realtek Realtek Ethernet controller                               | 3         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.82%   |
| Apple T2 Controller                                               | 3         | 0.82%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.55%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.55%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.55%   |
| Cypress K38231_03                                                 | 2         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.27%   |
| OPPO CPH1923                                                      | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 440       | 56.05%  |
| Ethernet | 338       | 43.06%  |
| Modem    | 6         | 0.76%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 391       | 81.97%  |
| Ethernet | 86        | 18.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 301       | 67.19%  |
| 1     | 137       | 30.58%  |
| 3     | 6         | 1.34%   |
| 0     | 4         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 360       | 79.3%   |
| Yes  | 94        | 20.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 234       | 56.25%  |
| Realtek Semiconductor           | 50        | 12.02%  |
| Qualcomm Atheros Communications | 28        | 6.73%   |
| IMC Networks                    | 18        | 4.33%   |
| Lite-On Technology              | 17        | 4.09%   |
| Broadcom                        | 16        | 3.85%   |
| Foxconn / Hon Hai               | 15        | 3.61%   |
| Apple                           | 9         | 2.16%   |
| Realtek                         | 5         | 1.2%    |
| MediaTek                        | 4         | 0.96%   |
| Dell                            | 4         | 0.96%   |
| Cambridge Silicon Radio         | 3         | 0.72%   |
| USI                             | 2         | 0.48%   |
| Toshiba                         | 2         | 0.48%   |
| Ralink                          | 2         | 0.48%   |
| Hewlett-Packard                 | 2         | 0.48%   |
| TP-Link                         | 1         | 0.24%   |
| Opticis                         | 1         | 0.24%   |
| Foxconn International           | 1         | 0.24%   |
| ASUSTek Computer                | 1         | 0.24%   |
| Alps Electric                   | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 93        | 22.3%   |
| Intel AX200 Bluetooth                               | 44        | 10.55%  |
| Intel AX201 Bluetooth                               | 42        | 10.07%  |
| Realtek Bluetooth Radio                             | 33        | 7.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 6.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 4.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 2.88%   |
| Intel AX210 Bluetooth                               | 11        | 2.64%   |
| IMC Networks Wireless_Device                        | 8         | 1.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.44%   |
| Intel Bluetooth Device                              | 6         | 1.44%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.44%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 1.2%    |
| Lite-On Bluetooth Device                            | 5         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.96%   |
| MediaTek Wireless_Device                            | 4         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.96%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.72%   |
| USI Bluetooth Device                                | 2         | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.48%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.48%   |
| IMC Networks Bluetooth Device                       | 2         | 0.48%   |
| Foxconn / Hon Hai BT                                | 2         | 0.48%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.48%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.48%   |
| Apple Bluetooth Host Controller                     | 2         | 0.48%   |
| TP-Link TPuLink UB500 Adapter                       | 1         | 0.24%   |
| Toshiba BCM43142A0                                  | 1         | 0.24%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 310       | 51.32%  |
| AMD                                             | 139       | 23.01%  |
| Nvidia                                          | 89        | 14.74%  |
| C-Media Electronics                             | 10        | 1.66%   |
| Texas Instruments                               | 7         | 1.16%   |
| Lenovo                                          | 5         | 0.83%   |
| KORG                                            | 5         | 0.83%   |
| AKAI                                            | 5         | 0.83%   |
| Realtek Semiconductor                           | 4         | 0.66%   |
| Corsair                                         | 4         | 0.66%   |
| Logitech                                        | 3         | 0.5%    |
| Apple                                           | 3         | 0.5%    |
| JMTek                                           | 2         | 0.33%   |
| GYROCOM C&C                                     | 2         | 0.33%   |
| Creative Technology                             | 2         | 0.33%   |
| YZ Technology                                   | 1         | 0.17%   |
| XMOS                                            | 1         | 0.17%   |
| Tdlasunnic                                      | 1         | 0.17%   |
| Sony                                            | 1         | 0.17%   |
| Samson Technologies                             | 1         | 0.17%   |
| ROCCAT                                          | 1         | 0.17%   |
| NAD Electronics                                 | 1         | 0.17%   |
| Micro Star International                        | 1         | 0.17%   |
| M-Audio                                         | 1         | 0.17%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.17%   |
| Kingston Technology                             | 1         | 0.17%   |
| Generalplus Technology                          | 1         | 0.17%   |
| Focusrite-Novation                              | 1         | 0.17%   |
| AKAI Professional M.I.                          | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 107       | 13.75%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 69        | 8.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 8.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 2.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 2.31%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 1.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.93%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 1.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 1.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 1.29%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 7         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 6         | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 5         | 0.64%   |
| KORG nanoKONTROL2 MIDI Controller                                                                 | 5         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 135       | 33.17%  |
| SK hynix            | 99        | 24.32%  |
| Micron Technology   | 64        | 15.72%  |
| Kingston            | 19        | 4.67%   |
| Crucial             | 16        | 3.93%   |
| Unknown             | 15        | 3.69%   |
| A-DATA Technology   | 9         | 2.21%   |
| Ramaxel Technology  | 8         | 1.97%   |
| Corsair             | 6         | 1.47%   |
| Elpida              | 5         | 1.23%   |
| Unknown (ABCD)      | 4         | 0.98%   |
| G.Skill             | 4         | 0.98%   |
| Team                | 3         | 0.74%   |
| Unknown             | 3         | 0.74%   |
| Teikon              | 2         | 0.49%   |
| Shenzhen Mic        | 2         | 0.49%   |
| Nanya Technology    | 2         | 0.49%   |
| Kllisre             | 2         | 0.49%   |
| V-GeN               | 1         | 0.25%   |
| Toshiba             | 1         | 0.25%   |
| Smart Brazil        | 1         | 0.25%   |
| Sesame              | 1         | 0.25%   |
| Qimonda             | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| Magnum Tech         | 1         | 0.25%   |
| CSX                 | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 3.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 2.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 2.05%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.37%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.14%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.14%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.91%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.91%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.68%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.68%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 3         | 0.68%   |
| Unknown                                                          | 3         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 2         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.46%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 201       | 58.77%  |
| DDR3   | 88        | 25.73%  |
| LPDDR4 | 19        | 5.56%   |
| LPDDR3 | 14        | 4.09%   |
| DDR2   | 8         | 2.34%   |
| DDR5   | 5         | 1.46%   |
| SDRAM  | 4         | 1.17%   |
| LPDDR5 | 3         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 299       | 86.17%  |
| Row Of Chips | 39        | 11.24%  |
| Chip         | 7         | 2.02%   |
| DIMM         | 1         | 0.29%   |
| Unknown      | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 177       | 47.84%  |
| 4096  | 108       | 29.19%  |
| 16384 | 52        | 14.05%  |
| 2048  | 23        | 6.22%   |
| 32768 | 8         | 2.16%   |
| 1024  | 2         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 103       | 28.3%   |
| 1600    | 76        | 20.88%  |
| 2667    | 72        | 19.78%  |
| 2400    | 24        | 6.59%   |
| 2133    | 19        | 5.22%   |
| 3266    | 15        | 4.12%   |
| 1334    | 8         | 2.2%    |
| 4800    | 7         | 1.92%   |
| 1867    | 6         | 1.65%   |
| 667     | 4         | 1.1%    |
| 6400    | 3         | 0.82%   |
| 4267    | 3         | 0.82%   |
| 4266    | 3         | 0.82%   |
| 1333    | 3         | 0.82%   |
| Unknown | 3         | 0.82%   |
| 3733    | 2         | 0.55%   |
| 2048    | 2         | 0.55%   |
| 1067    | 2         | 0.55%   |
| 800     | 2         | 0.55%   |
| 4199    | 1         | 0.27%   |
| 3000    | 1         | 0.27%   |
| 2933    | 1         | 0.27%   |
| 1776    | 1         | 0.27%   |
| 1639    | 1         | 0.27%   |
| 1200    | 1         | 0.27%   |
| 1066    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 50%     |
| HP DeskJet 2130 series        | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 98        | 24.62%  |
| IMC Networks                           | 64        | 16.08%  |
| Acer                                   | 40        | 10.05%  |
| Microdia                               | 28        | 7.04%   |
| Realtek Semiconductor                  | 24        | 6.03%   |
| Quanta                                 | 20        | 5.03%   |
| Lite-On Technology                     | 19        | 4.77%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 4.77%   |
| Sunplus Innovation Technology          | 14        | 3.52%   |
| Syntek                                 | 13        | 3.27%   |
| Apple                                  | 12        | 3.02%   |
| Luxvisions Innotech Limited            | 9         | 2.26%   |
| Logitech                               | 7         | 1.76%   |
| Suyin                                  | 4         | 1.01%   |
| Silicon Motion                         | 3         | 0.75%   |
| Primax Electronics                     | 3         | 0.75%   |
| Lenovo                                 | 3         | 0.75%   |
| Alcor Micro                            | 3         | 0.75%   |
| Sonix Technology                       | 2         | 0.5%    |
| Samsung Electronics                    | 2         | 0.5%    |
| Ricoh                                  | 2         | 0.5%    |
| Intel                                  | 2         | 0.5%    |
| MacroSilicon                           | 1         | 0.25%   |
| GRANDSTREAM GUV3100                    | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| GEMBIRD                                | 1         | 0.25%   |
| DLEQNA19IFK6G2                         | 1         | 0.25%   |
| Bison Electronics                      | 1         | 0.25%   |
| ALi                                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 30        | 7.52%   |
| IMC Networks Integrated Camera                   | 24        | 6.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 23        | 5.76%   |
| Chicony HD WebCam                                | 16        | 4.01%   |
| Acer Integrated Camera                           | 15        | 3.76%   |
| Microdia Integrated_Webcam_HD                    | 10        | 2.51%   |
| Realtek Integrated_Webcam_HD                     | 9         | 2.26%   |
| Acer HD Webcam                                   | 8         | 2.01%   |
| Syntek Integrated Camera                         | 7         | 1.75%   |
| Lite-On Integrated Camera                        | 7         | 1.75%   |
| Microdia Integrated Webcam                       | 6         | 1.5%    |
| Chicony USB2.0 HD UVC WebCam                     | 6         | 1.5%    |
| Quanta HP TrueVision HD Camera                   | 5         | 1.25%   |
| Chicony VGA WebCam                               | 5         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE                        | 5         | 1.25%   |
| Syntek Lenovo EasyCamera                         | 4         | 1%      |
| Sunplus HD WebCam                                | 4         | 1%      |
| Quanta HP HD Camera                              | 4         | 1%      |
| Lite-On HP Webcam                                | 4         | 1%      |
| IMC Networks HD Camera                           | 4         | 1%      |
| Chicony HD User Facing                           | 4         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 4         | 1%      |
| Sunplus Integrated_Webcam_HD                     | 3         | 0.75%   |
| Quanta USB2.0 HD UVC WebCam                      | 3         | 0.75%   |
| Microdia Webcam Vitade AF                        | 3         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera    | 3         | 0.75%   |
| Lite-On HP HD Camera                             | 3         | 0.75%   |
| IMC Networks ov9734_azurewave_camera             | 3         | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                    | 3         | 0.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 0.75%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 0.75%   |
| Chicony HP Webcam                                | 3         | 0.75%   |
| Chicony HP TrueVision HD Camera                  | 3         | 0.75%   |
| Chicony HP Truevision HD                         | 3         | 0.75%   |
| Chicony EasyCamera                               | 3         | 0.75%   |
| Apple FaceTime HD Camera (Built-in)              | 3         | 0.75%   |
| Acer SunplusIT Integrated Camera                 | 3         | 0.75%   |
| Acer EasyCamera                                  | 3         | 0.75%   |
| Syntek EasyCamera                                | 2         | 0.5%    |
| Suyin HP TrueVision HD Integrated Webcam         | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 28        | 32.56%  |
| Validity Sensors           | 23        | 26.74%  |
| Shenzhen Goodix Technology | 15        | 17.44%  |
| Elan Microelectronics      | 11        | 12.79%  |
| LighTuning Technology      | 5         | 5.81%   |
| Upek                       | 3         | 3.49%   |
| AuthenTec                  | 1         | 1.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 10        | 11.63%  |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 10.47%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 9.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 6.98%   |
| Elan ELAN:Fingerprint                                                      | 6         | 6.98%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 5.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 5.81%   |
| Elan ELAN:ARM-M4                                                           | 5         | 5.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 4.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.33%   |
| Synaptics  WBDI                                                            | 2         | 2.33%   |
| Validity Sensors VFS491                                                    | 1         | 1.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.16%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.16%   |
| AuthenTec AES2810                                                          | 1         | 1.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 51.61%  |
| Alcor Micro | 10        | 32.26%  |
| O2 Micro    | 2         | 6.45%   |
| Lenovo      | 2         | 6.45%   |
| Upek        | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 31.25%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 31.25%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 9.38%   |
| Broadcom 58200                                                               | 3         | 9.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.13%   |
| Broadcom 5880                                                                | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 259       | 56.3%   |
| 1     | 164       | 35.65%  |
| 2     | 36        | 7.83%   |
| 3     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 86        | 37.55%  |
| Net/ethernet             | 35        | 15.28%  |
| Chipcard                 | 30        | 13.1%   |
| Multimedia controller    | 26        | 11.35%  |
| Graphics card            | 20        | 8.73%   |
| Net/wireless             | 12        | 5.24%   |
| Camera                   | 9         | 3.93%   |
| Bluetooth                | 7         | 3.06%   |
| Storage                  | 2         | 0.87%   |
| Modem                    | 1         | 0.44%   |
| Communication controller | 1         | 0.44%   |

