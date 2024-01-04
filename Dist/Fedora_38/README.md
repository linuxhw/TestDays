Fedora 38 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_38/Desktop/README.md) and [notebooks](/Dist/Fedora_38/Notebook/README.md).

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

Total: 4155

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [4a37a9b35c](https://linux-hardware.org/?probe=4a37a9b35c) | Jan 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS2291P    | Notebook    | [1a86f2a3d4](https://linux-hardware.org/?probe=1a86f2a3d4) | Jan 01, 2024 |
| Dell          | Inspiron 5748               | Notebook    | [20017233b9](https://linux-hardware.org/?probe=20017233b9) | Dec 30, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [53fc03e451](https://linux-hardware.org/?probe=53fc03e451) | Dec 29, 2023 |
| ASRock        | B85M Pro3                   | Desktop     | [f61d357d7f](https://linux-hardware.org/?probe=f61d357d7f) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6c5599855c](https://linux-hardware.org/?probe=6c5599855c) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [0be6e9ce52](https://linux-hardware.org/?probe=0be6e9ce52) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [bbce6fb229](https://linux-hardware.org/?probe=bbce6fb229) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [6ba5504a6f](https://linux-hardware.org/?probe=6ba5504a6f) | Dec 28, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [1003211f6d](https://linux-hardware.org/?probe=1003211f6d) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [034adc4ac8](https://linux-hardware.org/?probe=034adc4ac8) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [00e7af074b](https://linux-hardware.org/?probe=00e7af074b) | Dec 25, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [357709050e](https://linux-hardware.org/?probe=357709050e) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bd10b63ca1](https://linux-hardware.org/?probe=bd10b63ca1) | Dec 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5206fdfe7e](https://linux-hardware.org/?probe=5206fdfe7e) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [976944381c](https://linux-hardware.org/?probe=976944381c) | Dec 24, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b150280df5](https://linux-hardware.org/?probe=b150280df5) | Dec 24, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [c93fffc388](https://linux-hardware.org/?probe=c93fffc388) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5c4d1c7d64](https://linux-hardware.org/?probe=5c4d1c7d64) | Dec 23, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [9ad17d2d3c](https://linux-hardware.org/?probe=9ad17d2d3c) | Dec 23, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [dd2248530b](https://linux-hardware.org/?probe=dd2248530b) | Dec 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9858586a84](https://linux-hardware.org/?probe=9858586a84) | Dec 22, 2023 |
| Dell          | Precision M4800             | Notebook    | [ce7a9239f4](https://linux-hardware.org/?probe=ce7a9239f4) | Dec 22, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [e864a3cd22](https://linux-hardware.org/?probe=e864a3cd22) | Dec 21, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [4153ae7cc6](https://linux-hardware.org/?probe=4153ae7cc6) | Dec 21, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [1a7734c3ec](https://linux-hardware.org/?probe=1a7734c3ec) | Dec 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [85087e0568](https://linux-hardware.org/?probe=85087e0568) | Dec 20, 2023 |
| ASRock        | B650M Pro RS                | Desktop     | [df96c996dd](https://linux-hardware.org/?probe=df96c996dd) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [70ece5f797](https://linux-hardware.org/?probe=70ece5f797) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [84c183a024](https://linux-hardware.org/?probe=84c183a024) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5082c6046e](https://linux-hardware.org/?probe=5082c6046e) | Dec 18, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [288e976604](https://linux-hardware.org/?probe=288e976604) | Dec 17, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [047995ad80](https://linux-hardware.org/?probe=047995ad80) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f019c4e149](https://linux-hardware.org/?probe=f019c4e149) | Dec 16, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [34a66d3cef](https://linux-hardware.org/?probe=34a66d3cef) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | Notebook    | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [90804693a6](https://linux-hardware.org/?probe=90804693a6) | Dec 14, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [6cadf8d04e](https://linux-hardware.org/?probe=6cadf8d04e) | Dec 14, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [12c2204715](https://linux-hardware.org/?probe=12c2204715) | Dec 12, 2023 |
| Acer          | V5-171                      | Notebook    | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [070ba5c3c1](https://linux-hardware.org/?probe=070ba5c3c1) | Dec 10, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [a467dabfb7](https://linux-hardware.org/?probe=a467dabfb7) | Dec 10, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [78cb902abe](https://linux-hardware.org/?probe=78cb902abe) | Dec 09, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| Dell          | Precision M4700             | Notebook    | [54abe2ce35](https://linux-hardware.org/?probe=54abe2ce35) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [0ba74f97d0](https://linux-hardware.org/?probe=0ba74f97d0) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [665a5984d2](https://linux-hardware.org/?probe=665a5984d2) | Dec 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dc05a32f3d](https://linux-hardware.org/?probe=dc05a32f3d) | Dec 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [de12499622](https://linux-hardware.org/?probe=de12499622) | Dec 05, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [c53a3bf5e8](https://linux-hardware.org/?probe=c53a3bf5e8) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [8a8bfb131c](https://linux-hardware.org/?probe=8a8bfb131c) | Dec 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b3ebc9b0fc](https://linux-hardware.org/?probe=b3ebc9b0fc) | Dec 04, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [67b1cc2f69](https://linux-hardware.org/?probe=67b1cc2f69) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6189dc268f](https://linux-hardware.org/?probe=6189dc268f) | Dec 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9aa3882678](https://linux-hardware.org/?probe=9aa3882678) | Dec 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS09H0... | Notebook    | [94274c6313](https://linux-hardware.org/?probe=94274c6313) | Dec 02, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [974a2661e2](https://linux-hardware.org/?probe=974a2661e2) | Dec 01, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [f2dc650bdf](https://linux-hardware.org/?probe=f2dc650bdf) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [5dd27edbe4](https://linux-hardware.org/?probe=5dd27edbe4) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [4fb92d7fe0](https://linux-hardware.org/?probe=4fb92d7fe0) | Nov 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [130735940f](https://linux-hardware.org/?probe=130735940f) | Nov 28, 2023 |
| Google        | Eve                         | Convertible | [d6e1955713](https://linux-hardware.org/?probe=d6e1955713) | Nov 27, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [648a453b3f](https://linux-hardware.org/?probe=648a453b3f) | Nov 26, 2023 |
| Dell          | Precision M3800             | Notebook    | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [78b8e2f560](https://linux-hardware.org/?probe=78b8e2f560) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [1e704edcd6](https://linux-hardware.org/?probe=1e704edcd6) | Nov 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [5693d24a8d](https://linux-hardware.org/?probe=5693d24a8d) | Nov 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [75a5b58cb8](https://linux-hardware.org/?probe=75a5b58cb8) | Nov 25, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [2852a62f61](https://linux-hardware.org/?probe=2852a62f61) | Nov 24, 2023 |
| Dell          | Latitude E5450              | Notebook    | [fad9a32575](https://linux-hardware.org/?probe=fad9a32575) | Nov 23, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [27f6e938d0](https://linux-hardware.org/?probe=27f6e938d0) | Nov 23, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [ebab9eb8e2](https://linux-hardware.org/?probe=ebab9eb8e2) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| Acer          | Aspire Z5610                | All in one  | [1390f1811a](https://linux-hardware.org/?probe=1390f1811a) | Nov 23, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [bc7df67b84](https://linux-hardware.org/?probe=bc7df67b84) | Nov 22, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | Desktop     | [7930532d04](https://linux-hardware.org/?probe=7930532d04) | Nov 21, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | Notebook    | [541752a388](https://linux-hardware.org/?probe=541752a388) | Nov 21, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [84df454a40](https://linux-hardware.org/?probe=84df454a40) | Nov 21, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3844682c90](https://linux-hardware.org/?probe=3844682c90) | Nov 21, 2023 |
| Lenovo        | B580 20144                  | Notebook    | [634e12256a](https://linux-hardware.org/?probe=634e12256a) | Nov 21, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [7a09806e41](https://linux-hardware.org/?probe=7a09806e41) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [26ebeb2504](https://linux-hardware.org/?probe=26ebeb2504) | Nov 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [fd4876bdbc](https://linux-hardware.org/?probe=fd4876bdbc) | Nov 20, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| BTO           | 17X1183                     | Notebook    | [6cd57738ff](https://linux-hardware.org/?probe=6cd57738ff) | Nov 20, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [b72b8abe13](https://linux-hardware.org/?probe=b72b8abe13) | Nov 19, 2023 |
| MSI           | Z270I GAMING PRO CARBON ... | Desktop     | [855aed38cb](https://linux-hardware.org/?probe=855aed38cb) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d957a1a8c5](https://linux-hardware.org/?probe=d957a1a8c5) | Nov 19, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [09070d5842](https://linux-hardware.org/?probe=09070d5842) | Nov 18, 2023 |
| Timi          | TM1701                      | Notebook    | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| Acer          | Aspire A315-53G             | Notebook    | [7f9669bf0b](https://linux-hardware.org/?probe=7f9669bf0b) | Nov 18, 2023 |
| ASRock        | X99X Killer                 | Desktop     | [954fe7c236](https://linux-hardware.org/?probe=954fe7c236) | Nov 17, 2023 |
| Dell          | Inspiron 5482               | Convertible | [5b113f1b62](https://linux-hardware.org/?probe=5b113f1b62) | Nov 17, 2023 |
| Google        | Kano                        | Notebook    | [3a0f7846c4](https://linux-hardware.org/?probe=3a0f7846c4) | Nov 17, 2023 |
| Google        | Kano                        | Notebook    | [0c5e699794](https://linux-hardware.org/?probe=0c5e699794) | Nov 17, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [e087bb03c3](https://linux-hardware.org/?probe=e087bb03c3) | Nov 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [d1800f3356](https://linux-hardware.org/?probe=d1800f3356) | Nov 16, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [ff73a36695](https://linux-hardware.org/?probe=ff73a36695) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [9503e14877](https://linux-hardware.org/?probe=9503e14877) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [59ad7e7e27](https://linux-hardware.org/?probe=59ad7e7e27) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [6b1a5452f8](https://linux-hardware.org/?probe=6b1a5452f8) | Nov 14, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c33072abbc](https://linux-hardware.org/?probe=c33072abbc) | Nov 14, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [121f68381f](https://linux-hardware.org/?probe=121f68381f) | Nov 14, 2023 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [cd7b8b7a84](https://linux-hardware.org/?probe=cd7b8b7a84) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4b522b316d](https://linux-hardware.org/?probe=4b522b316d) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [bb0f5fe1e2](https://linux-hardware.org/?probe=bb0f5fe1e2) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [74c6e6efae](https://linux-hardware.org/?probe=74c6e6efae) | Nov 13, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [2ed7720fa6](https://linux-hardware.org/?probe=2ed7720fa6) | Nov 13, 2023 |
| Dell          | Inspiron 7306 2n1           | Convertible | [e5eb4dddfa](https://linux-hardware.org/?probe=e5eb4dddfa) | Nov 13, 2023 |
| ASUSTek       | F3Sv                        | Notebook    | [7cc246f28e](https://linux-hardware.org/?probe=7cc246f28e) | Nov 13, 2023 |
| HP            | 339B                        | Desktop     | [a3b2a52a12](https://linux-hardware.org/?probe=a3b2a52a12) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [ffb3d9547e](https://linux-hardware.org/?probe=ffb3d9547e) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [fb5cb725d6](https://linux-hardware.org/?probe=fb5cb725d6) | Nov 13, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [ae1a1c1e9b](https://linux-hardware.org/?probe=ae1a1c1e9b) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [2651393e60](https://linux-hardware.org/?probe=2651393e60) | Nov 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [530c444ea1](https://linux-hardware.org/?probe=530c444ea1) | Nov 12, 2023 |
| Acer          | Aspire Z5610                | All in one  | [509a290097](https://linux-hardware.org/?probe=509a290097) | Nov 12, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [edf208cfd3](https://linux-hardware.org/?probe=edf208cfd3) | Nov 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4779217105](https://linux-hardware.org/?probe=4779217105) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d86488ec6](https://linux-hardware.org/?probe=7d86488ec6) | Nov 11, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [5cc12c788a](https://linux-hardware.org/?probe=5cc12c788a) | Nov 10, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | Desktop     | [ea4b644bef](https://linux-hardware.org/?probe=ea4b644bef) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [cfc1427577](https://linux-hardware.org/?probe=cfc1427577) | Nov 10, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [98adaea6de](https://linux-hardware.org/?probe=98adaea6de) | Nov 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [60d38c4fae](https://linux-hardware.org/?probe=60d38c4fae) | Nov 09, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [431101ce2f](https://linux-hardware.org/?probe=431101ce2f) | Nov 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5c243dae6b](https://linux-hardware.org/?probe=5c243dae6b) | Nov 09, 2023 |
| Lenovo        | ThinkPad X250 20CLAOMLIN    | Notebook    | [88967f98bd](https://linux-hardware.org/?probe=88967f98bd) | Nov 09, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b1610ff76c](https://linux-hardware.org/?probe=b1610ff76c) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [80431017dc](https://linux-hardware.org/?probe=80431017dc) | Nov 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [2e7ed7b6c8](https://linux-hardware.org/?probe=2e7ed7b6c8) | Nov 09, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [f48a185656](https://linux-hardware.org/?probe=f48a185656) | Nov 08, 2023 |
| MSI           | H110M ECO                   | Desktop     | [850e3ac421](https://linux-hardware.org/?probe=850e3ac421) | Nov 08, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [13f2aeb42e](https://linux-hardware.org/?probe=13f2aeb42e) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [63e0b9fc88](https://linux-hardware.org/?probe=63e0b9fc88) | Nov 08, 2023 |
| Sony          | SVF15N17CXB                 | Notebook    | [e8497bf6f6](https://linux-hardware.org/?probe=e8497bf6f6) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [3d2ec07a57](https://linux-hardware.org/?probe=3d2ec07a57) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [eb27db3944](https://linux-hardware.org/?probe=eb27db3944) | Nov 08, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [dbe90ad5d6](https://linux-hardware.org/?probe=dbe90ad5d6) | Nov 08, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9e3d070f39](https://linux-hardware.org/?probe=9e3d070f39) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| ASRock        | B550M-C                     | Desktop     | [7d79d732ed](https://linux-hardware.org/?probe=7d79d732ed) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [e79bc70a0d](https://linux-hardware.org/?probe=e79bc70a0d) | Nov 07, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b0d207b140](https://linux-hardware.org/?probe=b0d207b140) | Nov 07, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [c85bdae7e5](https://linux-hardware.org/?probe=c85bdae7e5) | Nov 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e874ddf25c](https://linux-hardware.org/?probe=e874ddf25c) | Nov 07, 2023 |
| Dell          | Latitude E5470              | Notebook    | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [722c36be7f](https://linux-hardware.org/?probe=722c36be7f) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | X55A                        | Notebook    | [705bc0e6a5](https://linux-hardware.org/?probe=705bc0e6a5) | Nov 07, 2023 |
| Dell          | Precision M4600             | Notebook    | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [d63435f6d0](https://linux-hardware.org/?probe=d63435f6d0) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [53fd99e067](https://linux-hardware.org/?probe=53fd99e067) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [d8adc9ee0d](https://linux-hardware.org/?probe=d8adc9ee0d) | Nov 06, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [e07422acdd](https://linux-hardware.org/?probe=e07422acdd) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [dadc34f1bb](https://linux-hardware.org/?probe=dadc34f1bb) | Nov 06, 2023 |
| Lenovo        | 3750 SDK0T76461 WIN 3422... | Desktop     | [995234c08b](https://linux-hardware.org/?probe=995234c08b) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [b5b4c26e1e](https://linux-hardware.org/?probe=b5b4c26e1e) | Nov 06, 2023 |
| MSI           | H55M-E33                    | Desktop     | [09ba697574](https://linux-hardware.org/?probe=09ba697574) | Nov 06, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [a7c5843f17](https://linux-hardware.org/?probe=a7c5843f17) | Nov 06, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [a8a46eb495](https://linux-hardware.org/?probe=a8a46eb495) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [fe01dc6819](https://linux-hardware.org/?probe=fe01dc6819) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| HP            | G61                         | Notebook    | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [a8c249eafd](https://linux-hardware.org/?probe=a8c249eafd) | Nov 05, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a42da62572](https://linux-hardware.org/?probe=a42da62572) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | 1494                        | Desktop     | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| Dell          | Latitude E7440              | Notebook    | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| Lenovo        | S145-15IWL 81MV             | Notebook    | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | Notebook    | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [77f3748e01](https://linux-hardware.org/?probe=77f3748e01) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [a7f0f43604](https://linux-hardware.org/?probe=a7f0f43604) | Nov 04, 2023 |
| Sony          | VPCEH3J1E                   | Notebook    | [e0ae745034](https://linux-hardware.org/?probe=e0ae745034) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| POV           | I102A                       | Notebook    | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| HP            | 859C                        | Desktop     | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [36fb8d63bb](https://linux-hardware.org/?probe=36fb8d63bb) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| GreatWall     | W1011                       | Tablet      | [fe355d55c3](https://linux-hardware.org/?probe=fe355d55c3) | Nov 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf88c7f3db](https://linux-hardware.org/?probe=cf88c7f3db) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | Notebook    | [c6634f090f](https://linux-hardware.org/?probe=c6634f090f) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | Desktop     | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| MSI           | IONA                        | Desktop     | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [60c6e3a5d2](https://linux-hardware.org/?probe=60c6e3a5d2) | Nov 01, 2023 |
| ASUSTek       | M52AD_M12AD                 | Desktop     | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| Dell          | G3 3579                     | Notebook    | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [236c6c4f9a](https://linux-hardware.org/?probe=236c6c4f9a) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [b724e20965](https://linux-hardware.org/?probe=b724e20965) | Nov 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [636993569c](https://linux-hardware.org/?probe=636993569c) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| HP            | 8767 A                      | Desktop     | [618323a058](https://linux-hardware.org/?probe=618323a058) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Alienware     | 14                          | Notebook    | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [f7385ed51b](https://linux-hardware.org/?probe=f7385ed51b) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [ef58eef71a](https://linux-hardware.org/?probe=ef58eef71a) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3179102373](https://linux-hardware.org/?probe=3179102373) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | Notebook    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | Notebook    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Latitude 5414               | Notebook    | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a9a2e2ab03](https://linux-hardware.org/?probe=a9a2e2ab03) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | Notebook    | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | Notebook    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| Dell          | Latitude 5490               | Notebook    | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Dell          | Precision 3551              | Notebook    | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [261e5240fe](https://linux-hardware.org/?probe=261e5240fe) | Oct 30, 2023 |
| ASUSTek       | F3Sv                        | Notebook    | [3da2894228](https://linux-hardware.org/?probe=3da2894228) | Oct 30, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [b1adeb2f86](https://linux-hardware.org/?probe=b1adeb2f86) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [a526322459](https://linux-hardware.org/?probe=a526322459) | Oct 29, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [7d0eb8f922](https://linux-hardware.org/?probe=7d0eb8f922) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| HP            | Notebook                    | Notebook    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [519bf4fbae](https://linux-hardware.org/?probe=519bf4fbae) | Oct 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [deef4da5dc](https://linux-hardware.org/?probe=deef4da5dc) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [12d5c69b6a](https://linux-hardware.org/?probe=12d5c69b6a) | Oct 29, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [78ab56301b](https://linux-hardware.org/?probe=78ab56301b) | Oct 29, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [2aa83dbdfc](https://linux-hardware.org/?probe=2aa83dbdfc) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [da25874b12](https://linux-hardware.org/?probe=da25874b12) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [762e9a6d4d](https://linux-hardware.org/?probe=762e9a6d4d) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b4645667a4](https://linux-hardware.org/?probe=b4645667a4) | Oct 28, 2023 |
| HP            | 8053                        | Desktop     | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| HP            | 8053                        | Desktop     | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [4562f80268](https://linux-hardware.org/?probe=4562f80268) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [d78b4f6222](https://linux-hardware.org/?probe=d78b4f6222) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5591930fc0](https://linux-hardware.org/?probe=5591930fc0) | Oct 27, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | Notebook    | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| HP            | 843F                        | Desktop     | [c39418a5fe](https://linux-hardware.org/?probe=c39418a5fe) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [4eacfc5dd8](https://linux-hardware.org/?probe=4eacfc5dd8) | Oct 27, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [18938afb70](https://linux-hardware.org/?probe=18938afb70) | Oct 27, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [61da163866](https://linux-hardware.org/?probe=61da163866) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [51e6c3cef4](https://linux-hardware.org/?probe=51e6c3cef4) | Oct 27, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [570c03f594](https://linux-hardware.org/?probe=570c03f594) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [9650e62539](https://linux-hardware.org/?probe=9650e62539) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [82ba56a70d](https://linux-hardware.org/?probe=82ba56a70d) | Oct 26, 2023 |
| Dell          | Latitude 5440               | Notebook    | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | Notebook    | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | Desktop     | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [992a1810e2](https://linux-hardware.org/?probe=992a1810e2) | Oct 26, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [67b3859d9d](https://linux-hardware.org/?probe=67b3859d9d) | Oct 26, 2023 |
| Toshiba       | Satellite L75D-A            | Notebook    | [82efb2dd44](https://linux-hardware.org/?probe=82efb2dd44) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| Schenker      | VISION (M23)                | Notebook    | [64cead24ba](https://linux-hardware.org/?probe=64cead24ba) | Oct 26, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f4f5605117](https://linux-hardware.org/?probe=f4f5605117) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca40b148a0](https://linux-hardware.org/?probe=ca40b148a0) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| HP            | 8433 11                     | Desktop     | [902343e220](https://linux-hardware.org/?probe=902343e220) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Timi          | TM1701                      | Notebook    | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| Supermicro    | X8SAX                       | Desktop     | [5d90e1af8c](https://linux-hardware.org/?probe=5d90e1af8c) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [c9b5ffd5b8](https://linux-hardware.org/?probe=c9b5ffd5b8) | Oct 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d4a28890a5](https://linux-hardware.org/?probe=d4a28890a5) | Oct 24, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [2a476e881e](https://linux-hardware.org/?probe=2a476e881e) | Oct 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| TrekStor      | Primebook C11B              | Convertible | [7038c45f32](https://linux-hardware.org/?probe=7038c45f32) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | Notebook    | [52b5addead](https://linux-hardware.org/?probe=52b5addead) | Oct 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ed696b1c52](https://linux-hardware.org/?probe=ed696b1c52) | Oct 24, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [41fd350f12](https://linux-hardware.org/?probe=41fd350f12) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | Notebook    | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| GPD           | G1621-02                    | Notebook    | [ea3897be17](https://linux-hardware.org/?probe=ea3897be17) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Lenovo        | 371E SDK0J40709 WIN 3259... | All in one  | [47d70a6fcb](https://linux-hardware.org/?probe=47d70a6fcb) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Acer          | Aspire X1900                | Desktop     | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| Dell          | Latitude 5320               | Notebook    | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [4440cac740](https://linux-hardware.org/?probe=4440cac740) | Oct 23, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [6d63f6c5ba](https://linux-hardware.org/?probe=6d63f6c5ba) | Oct 23, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| ASRock        | D1800M                      | Desktop     | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2af156789d](https://linux-hardware.org/?probe=2af156789d) | Oct 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [eb9bba4f5c](https://linux-hardware.org/?probe=eb9bba4f5c) | Oct 23, 2023 |
| Dell          | G15 5515                    | Notebook    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| HP            | ProBook 4530s               | Notebook    | [104df79d8e](https://linux-hardware.org/?probe=104df79d8e) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | Notebook    | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [7190f336e0](https://linux-hardware.org/?probe=7190f336e0) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [fc5437cf30](https://linux-hardware.org/?probe=fc5437cf30) | Oct 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| MSI           | IONA                        | Desktop     | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [705aaea029](https://linux-hardware.org/?probe=705aaea029) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Lenovo        | ThinkPad L13 20R30005RT     | Notebook    | [23a9651432](https://linux-hardware.org/?probe=23a9651432) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| AZW           | SER V1                      | Desktop     | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [7105618a0a](https://linux-hardware.org/?probe=7105618a0a) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0b91bab038](https://linux-hardware.org/?probe=0b91bab038) | Oct 22, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [04a430e244](https://linux-hardware.org/?probe=04a430e244) | Oct 22, 2023 |
| HP            | 83E9                        | Desktop     | [c324d1ee0a](https://linux-hardware.org/?probe=c324d1ee0a) | Oct 22, 2023 |
| HP            | 83E9                        | Desktop     | [8102d00cdc](https://linux-hardware.org/?probe=8102d00cdc) | Oct 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9310d00e](https://linux-hardware.org/?probe=5d9310d00e) | Oct 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [7c383004b6](https://linux-hardware.org/?probe=7c383004b6) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | Notebook    | [863f309154](https://linux-hardware.org/?probe=863f309154) | Oct 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Dell          | Latitude E6320              | Notebook    | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [37389245cd](https://linux-hardware.org/?probe=37389245cd) | Oct 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ce517165dc](https://linux-hardware.org/?probe=ce517165dc) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [64148c88c0](https://linux-hardware.org/?probe=64148c88c0) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [f1b2f555ef](https://linux-hardware.org/?probe=f1b2f555ef) | Oct 21, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [3afdd1b0da](https://linux-hardware.org/?probe=3afdd1b0da) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [466e429ddd](https://linux-hardware.org/?probe=466e429ddd) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| ASUSTek       | X442UAR                     | Notebook    | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e0997ac78c](https://linux-hardware.org/?probe=e0997ac78c) | Oct 20, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8290e4c160](https://linux-hardware.org/?probe=8290e4c160) | Oct 20, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| BANGHO        | M7x0K                       | Notebook    | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| Dell          | Vostro 14 5410              | Notebook    | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [aa76e46b18](https://linux-hardware.org/?probe=aa76e46b18) | Oct 20, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [32d375b029](https://linux-hardware.org/?probe=32d375b029) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [fe5af0991d](https://linux-hardware.org/?probe=fe5af0991d) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [c96f9ccef3](https://linux-hardware.org/?probe=c96f9ccef3) | Oct 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [10fab445ad](https://linux-hardware.org/?probe=10fab445ad) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-P                | Notebook    | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| Acer          | Aspire A315-57G             | Notebook    | [7e39a647e3](https://linux-hardware.org/?probe=7e39a647e3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8d38f6e16d](https://linux-hardware.org/?probe=8d38f6e16d) | Oct 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [fbb4ce606d](https://linux-hardware.org/?probe=fbb4ce606d) | Oct 19, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| MACHINIST     | X99 G7 V1.0                 | Desktop     | [caca14cc52](https://linux-hardware.org/?probe=caca14cc52) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [b3cd8983eb](https://linux-hardware.org/?probe=b3cd8983eb) | Oct 18, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [064dc574bb](https://linux-hardware.org/?probe=064dc574bb) | Oct 18, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [1984a8305d](https://linux-hardware.org/?probe=1984a8305d) | Oct 18, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [305b104f83](https://linux-hardware.org/?probe=305b104f83) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| HP            | 2B52                        | Desktop     | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [bde071302f](https://linux-hardware.org/?probe=bde071302f) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| Dell          | Precision 7680              | Notebook    | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| HP            | 1589                        | Desktop     | [9fca3eb994](https://linux-hardware.org/?probe=9fca3eb994) | Oct 17, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4d69a046ff](https://linux-hardware.org/?probe=4d69a046ff) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [8cb8d0943c](https://linux-hardware.org/?probe=8cb8d0943c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [6f8e6d4251](https://linux-hardware.org/?probe=6f8e6d4251) | Oct 17, 2023 |
| MSI           | MS-1T31                     | Desktop     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [10c951fdee](https://linux-hardware.org/?probe=10c951fdee) | Oct 17, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| Samsung       | 930QCG                      | Convertible | [26595d7bc0](https://linux-hardware.org/?probe=26595d7bc0) | Oct 17, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [85e4efe1d3](https://linux-hardware.org/?probe=85e4efe1d3) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [efc4ad7803](https://linux-hardware.org/?probe=efc4ad7803) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | Notebook    | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e28562a4d2](https://linux-hardware.org/?probe=e28562a4d2) | Oct 17, 2023 |
| HP            | 8AB6 SMVB                   | Desktop     | [e88f9153df](https://linux-hardware.org/?probe=e88f9153df) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [3f87e6216a](https://linux-hardware.org/?probe=3f87e6216a) | Oct 16, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Dynabook E... | Satellite Pro ET10-G-106    | Tablet      | [e5a0e9fee3](https://linux-hardware.org/?probe=e5a0e9fee3) | Oct 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [55d07d6ee2](https://linux-hardware.org/?probe=55d07d6ee2) | Oct 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | Notebook    | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5651db5e36](https://linux-hardware.org/?probe=5651db5e36) | Oct 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| HP            | Notebook                    | Notebook    | [44730825fa](https://linux-hardware.org/?probe=44730825fa) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [d294330c51](https://linux-hardware.org/?probe=d294330c51) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | Notebook    | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [19ec3283fc](https://linux-hardware.org/?probe=19ec3283fc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1a38144f94](https://linux-hardware.org/?probe=1a38144f94) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| Dell          | Latitude 5591               | Notebook    | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [5330b349cb](https://linux-hardware.org/?probe=5330b349cb) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HP            | 1589                        | Desktop     | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | Desktop     | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | Notebook    | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Dell          | 0TY915                      | Desktop     | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | Desktop     | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [7e4e4b6a5d](https://linux-hardware.org/?probe=7e4e4b6a5d) | Oct 15, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [b5d7147862](https://linux-hardware.org/?probe=b5d7147862) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [642ecadbd2](https://linux-hardware.org/?probe=642ecadbd2) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | Notebook    | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4b4d5899fa](https://linux-hardware.org/?probe=4b4d5899fa) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [21de4b869f](https://linux-hardware.org/?probe=21de4b869f) | Oct 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [70b85fc17d](https://linux-hardware.org/?probe=70b85fc17d) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [039e898b5d](https://linux-hardware.org/?probe=039e898b5d) | Oct 13, 2023 |
| HPE           | ProLiant MicroServer Gen... | Server      | [62f56cc610](https://linux-hardware.org/?probe=62f56cc610) | Oct 13, 2023 |
| Google        | Morphius                    | Notebook    | [fd4be61654](https://linux-hardware.org/?probe=fd4be61654) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [2edd75be93](https://linux-hardware.org/?probe=2edd75be93) | Oct 13, 2023 |
| Dell          | Precision 7520              | Notebook    | [e9cb628c83](https://linux-hardware.org/?probe=e9cb628c83) | Oct 13, 2023 |
| Framework     | Laptop                      | Notebook    | [760f431061](https://linux-hardware.org/?probe=760f431061) | Oct 13, 2023 |
| Dell          | Precision 3580              | Notebook    | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1c1d7152a3](https://linux-hardware.org/?probe=1c1d7152a3) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| ASRock        | H87 Performance             | Desktop     | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | Notebook    | [4485ad6d0b](https://linux-hardware.org/?probe=4485ad6d0b) | Oct 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a4dfa6f17f](https://linux-hardware.org/?probe=a4dfa6f17f) | Oct 13, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [a93d337261](https://linux-hardware.org/?probe=a93d337261) | Oct 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f6dd5e142c](https://linux-hardware.org/?probe=f6dd5e142c) | Oct 13, 2023 |
| HP            | G61                         | Notebook    | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [1c10565d3f](https://linux-hardware.org/?probe=1c10565d3f) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f24ebc31a5](https://linux-hardware.org/?probe=f24ebc31a5) | Oct 13, 2023 |
| Dell          | Precision 7520              | Notebook    | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [f59286c03f](https://linux-hardware.org/?probe=f59286c03f) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fb8c320433](https://linux-hardware.org/?probe=fb8c320433) | Oct 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [f51db4d9ed](https://linux-hardware.org/?probe=f51db4d9ed) | Oct 12, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2598a9d29b](https://linux-hardware.org/?probe=2598a9d29b) | Oct 12, 2023 |
| Dell          | Latitude 3490               | Notebook    | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | Notebook    | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| Dell          | XPS 9320                    | Notebook    | [33d6205766](https://linux-hardware.org/?probe=33d6205766) | Oct 12, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [c6c1d1b3d1](https://linux-hardware.org/?probe=c6c1d1b3d1) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | Notebook    | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [87e16d607b](https://linux-hardware.org/?probe=87e16d607b) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | Notebook    | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [c7b68dbfe1](https://linux-hardware.org/?probe=c7b68dbfe1) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | Notebook    | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [3fe12fb88e](https://linux-hardware.org/?probe=3fe12fb88e) | Oct 11, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | Notebook    | [2659f02d19](https://linux-hardware.org/?probe=2659f02d19) | Oct 11, 2023 |
| HP            | 843B                        | Desktop     | [652027900b](https://linux-hardware.org/?probe=652027900b) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| Avell High... | B.ON                        | Notebook    | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e06a4e6c13](https://linux-hardware.org/?probe=e06a4e6c13) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| Dell          | Precision 3571              | Notebook    | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [87471871a7](https://linux-hardware.org/?probe=87471871a7) | Oct 10, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [19f6294d43](https://linux-hardware.org/?probe=19f6294d43) | Oct 10, 2023 |
| HP            | 89B5 A                      | Desktop     | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| ASRock        | B365M IB-R                  | Desktop     | [c1ac8c374a](https://linux-hardware.org/?probe=c1ac8c374a) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| AMI           | Intel                       | Convertible | [dd83e7aaf0](https://linux-hardware.org/?probe=dd83e7aaf0) | Oct 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5954b70bb9](https://linux-hardware.org/?probe=5954b70bb9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [28a78b32e5](https://linux-hardware.org/?probe=28a78b32e5) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Dell          | Latitude 9430               | Convertible | [c7e409eb50](https://linux-hardware.org/?probe=c7e409eb50) | Oct 10, 2023 |
| Teclast       | F7S                         | Notebook    | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4ef40bc57a](https://linux-hardware.org/?probe=4ef40bc57a) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [830730801b](https://linux-hardware.org/?probe=830730801b) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | Notebook    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [7aa0b01da6](https://linux-hardware.org/?probe=7aa0b01da6) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [b249985c20](https://linux-hardware.org/?probe=b249985c20) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [90b88ff378](https://linux-hardware.org/?probe=90b88ff378) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Google        | Lindar                      | Notebook    | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c2718a5c04](https://linux-hardware.org/?probe=c2718a5c04) | Oct 08, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0a2980430](https://linux-hardware.org/?probe=b0a2980430) | Oct 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d43dc626c0](https://linux-hardware.org/?probe=d43dc626c0) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [998f01f73b](https://linux-hardware.org/?probe=998f01f73b) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [173accc37f](https://linux-hardware.org/?probe=173accc37f) | Oct 08, 2023 |
| HP            | 158A                        | Desktop     | [a1c0d51b9d](https://linux-hardware.org/?probe=a1c0d51b9d) | Oct 08, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [bad231ff7d](https://linux-hardware.org/?probe=bad231ff7d) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [eac5ec9d19](https://linux-hardware.org/?probe=eac5ec9d19) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [3c93fdc206](https://linux-hardware.org/?probe=3c93fdc206) | Oct 07, 2023 |
| Framework     | Laptop                      | Notebook    | [92ced4e3c6](https://linux-hardware.org/?probe=92ced4e3c6) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [0d980c4a61](https://linux-hardware.org/?probe=0d980c4a61) | Oct 07, 2023 |
| Dell          | Latitude 3490               | Notebook    | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | Notebook    | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| Acer          | Aspire X1900                | Desktop     | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Lenovo        | Mullins-LarneML             | Notebook    | [73b6f496a3](https://linux-hardware.org/?probe=73b6f496a3) | Oct 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [3d434adf2c](https://linux-hardware.org/?probe=3d434adf2c) | Oct 06, 2023 |
| HP            | Notebook                    | Notebook    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [a41f086304](https://linux-hardware.org/?probe=a41f086304) | Oct 06, 2023 |
| HP            | Notebook                    | Notebook    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e8ae378997](https://linux-hardware.org/?probe=e8ae378997) | Oct 06, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [108728a0b6](https://linux-hardware.org/?probe=108728a0b6) | Oct 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [25612e7681](https://linux-hardware.org/?probe=25612e7681) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6bf5869cab](https://linux-hardware.org/?probe=6bf5869cab) | Oct 06, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [0b9d1772cd](https://linux-hardware.org/?probe=0b9d1772cd) | Oct 06, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [76c6fdfad6](https://linux-hardware.org/?probe=76c6fdfad6) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [676106fbb7](https://linux-hardware.org/?probe=676106fbb7) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [8ae84cb1dc](https://linux-hardware.org/?probe=8ae84cb1dc) | Oct 05, 2023 |
| Dell          | Precision 5480              | Notebook    | [3a87c7a065](https://linux-hardware.org/?probe=3a87c7a065) | Oct 05, 2023 |
| Medion        | MS-7707                     | Desktop     | [42bc6357f7](https://linux-hardware.org/?probe=42bc6357f7) | Oct 05, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [010c54ccaf](https://linux-hardware.org/?probe=010c54ccaf) | Oct 05, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [bfe115219f](https://linux-hardware.org/?probe=bfe115219f) | Oct 05, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [2ed7997cfe](https://linux-hardware.org/?probe=2ed7997cfe) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [01f88bafa7](https://linux-hardware.org/?probe=01f88bafa7) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| Google        | Magpie                      | Notebook    | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| Acer          | Spin SP314-21               | Convertible | [644e66499e](https://linux-hardware.org/?probe=644e66499e) | Oct 05, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | Notebook    | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Samsung       | 940Z5L                      | Notebook    | [120b5dac7e](https://linux-hardware.org/?probe=120b5dac7e) | Oct 04, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [135859015c](https://linux-hardware.org/?probe=135859015c) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | Notebook    | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | Latitude 7340               | Notebook    | [713640e574](https://linux-hardware.org/?probe=713640e574) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| MSI           | PR600                       | Notebook    | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | Notebook    | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [a98397577c](https://linux-hardware.org/?probe=a98397577c) | Oct 03, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [30a087cc37](https://linux-hardware.org/?probe=30a087cc37) | Oct 03, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [400e01b1bf](https://linux-hardware.org/?probe=400e01b1bf) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [452537ff56](https://linux-hardware.org/?probe=452537ff56) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0085d7a6ca](https://linux-hardware.org/?probe=0085d7a6ca) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a55f97899c](https://linux-hardware.org/?probe=a55f97899c) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420 4236BR4       | Notebook    | [002422b029](https://linux-hardware.org/?probe=002422b029) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b225569c1d](https://linux-hardware.org/?probe=b225569c1d) | Oct 02, 2023 |
| MSI           | VR630                       | Notebook    | [a9ce96c1ff](https://linux-hardware.org/?probe=a9ce96c1ff) | Oct 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [d78757ca20](https://linux-hardware.org/?probe=d78757ca20) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [59f53b1488](https://linux-hardware.org/?probe=59f53b1488) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [2452e6e54f](https://linux-hardware.org/?probe=2452e6e54f) | Oct 02, 2023 |
| Chuwi         | UBook X                     | Convertible | [dd61ba0953](https://linux-hardware.org/?probe=dd61ba0953) | Oct 02, 2023 |
| Chuwi         | UBook X                     | Convertible | [641ddde28b](https://linux-hardware.org/?probe=641ddde28b) | Oct 02, 2023 |
| Apple         | MacBookPro16,3              | Notebook    | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [4c5eef8118](https://linux-hardware.org/?probe=4c5eef8118) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | Notebook    | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f2e2a6b13](https://linux-hardware.org/?probe=1f2e2a6b13) | Oct 02, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [6f11536a5f](https://linux-hardware.org/?probe=6f11536a5f) | Oct 02, 2023 |
| Dell          | Inspiron 7573               | Convertible | [04d2b10c14](https://linux-hardware.org/?probe=04d2b10c14) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| Intel         | H110                        | Desktop     | [eaf6f0f81c](https://linux-hardware.org/?probe=eaf6f0f81c) | Oct 02, 2023 |
| Acer          | Aspire X1900                | Desktop     | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [17aca5008c](https://linux-hardware.org/?probe=17aca5008c) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b27cfa6ad6](https://linux-hardware.org/?probe=b27cfa6ad6) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [45b94d86b5](https://linux-hardware.org/?probe=45b94d86b5) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Google        | Magpie                      | Notebook    | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cd70d42de1](https://linux-hardware.org/?probe=cd70d42de1) | Oct 01, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [10e1561364](https://linux-hardware.org/?probe=10e1561364) | Oct 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [21a71fe352](https://linux-hardware.org/?probe=21a71fe352) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [e1945fe82f](https://linux-hardware.org/?probe=e1945fe82f) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [9dd550337d](https://linux-hardware.org/?probe=9dd550337d) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [9d3a95cfd5](https://linux-hardware.org/?probe=9d3a95cfd5) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| Dell          | Latitude 5520               | Notebook    | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [966636d4d1](https://linux-hardware.org/?probe=966636d4d1) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [5c4cae2a0b](https://linux-hardware.org/?probe=5c4cae2a0b) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | Latitude 7280               | Notebook    | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | Notebook    | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [751b4d268a](https://linux-hardware.org/?probe=751b4d268a) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | Notebook    | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| HP            | 8055                        | Desktop     | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [c69ab4bc0f](https://linux-hardware.org/?probe=c69ab4bc0f) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4a7b1ee936](https://linux-hardware.org/?probe=4a7b1ee936) | Sep 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [c822d38335](https://linux-hardware.org/?probe=c822d38335) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [222c45e72e](https://linux-hardware.org/?probe=222c45e72e) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [427ea0aa4f](https://linux-hardware.org/?probe=427ea0aa4f) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [fac4bb4863](https://linux-hardware.org/?probe=fac4bb4863) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [1210322d55](https://linux-hardware.org/?probe=1210322d55) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | Desktop     | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| ASUSTek       | ROG Flow X13 GV302XU_GV3... | Convertible | [abf12be6ff](https://linux-hardware.org/?probe=abf12be6ff) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Framework     | Laptop                      | Notebook    | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Samsung       | 550XDA                      | Notebook    | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [d237ab1a11](https://linux-hardware.org/?probe=d237ab1a11) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b6e832a4d8](https://linux-hardware.org/?probe=b6e832a4d8) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | Desktop     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| Dell          | Latitude E7450              | Notebook    | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Dell          | Latitude 7490               | Notebook    | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | Notebook    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | Desktop     | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [37fdb062e1](https://linux-hardware.org/?probe=37fdb062e1) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | Desktop     | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c665cddf99](https://linux-hardware.org/?probe=c665cddf99) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [1c1268d4e0](https://linux-hardware.org/?probe=1c1268d4e0) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4fbb517b71](https://linux-hardware.org/?probe=4fbb517b71) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2953047bfa](https://linux-hardware.org/?probe=2953047bfa) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| System76      | Pangolin                    | Notebook    | [3c56c50463](https://linux-hardware.org/?probe=3c56c50463) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Dell          | Latitude E7270              | Notebook    | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| HP            | ProBook 6570b               | Notebook    | [a67981aa91](https://linux-hardware.org/?probe=a67981aa91) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [88385cbacc](https://linux-hardware.org/?probe=88385cbacc) | Sep 25, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [4233a2e5e3](https://linux-hardware.org/?probe=4233a2e5e3) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e741b61807](https://linux-hardware.org/?probe=e741b61807) | Sep 25, 2023 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [e97a8fa2c7](https://linux-hardware.org/?probe=e97a8fa2c7) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [fac92f385c](https://linux-hardware.org/?probe=fac92f385c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [44784bdea7](https://linux-hardware.org/?probe=44784bdea7) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |
| Sony          | VAIO                        | All in one  | [75e484b949](https://linux-hardware.org/?probe=75e484b949) | Sep 24, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [53051aa7eb](https://linux-hardware.org/?probe=53051aa7eb) | Sep 24, 2023 |
| Dell          | Latitude 7400               | Notebook    | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [b3c890ec7a](https://linux-hardware.org/?probe=b3c890ec7a) | Sep 24, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| HP            | 350 G2                      | Notebook    | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [7c0eb47c16](https://linux-hardware.org/?probe=7c0eb47c16) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [eccabb6bc2](https://linux-hardware.org/?probe=eccabb6bc2) | Sep 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5ed3f9381a](https://linux-hardware.org/?probe=5ed3f9381a) | Sep 23, 2023 |
| HP            | 255 15.6 inch G10           | Notebook    | [9f02426c5d](https://linux-hardware.org/?probe=9f02426c5d) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [18b2a7026b](https://linux-hardware.org/?probe=18b2a7026b) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [60f81eeb50](https://linux-hardware.org/?probe=60f81eeb50) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f59df7021c](https://linux-hardware.org/?probe=f59df7021c) | Sep 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [1d032535e1](https://linux-hardware.org/?probe=1d032535e1) | Sep 23, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64        | 343       | 10.46%  |
| 6.2.15-300.fc38.x86_64       | 233       | 7.1%    |
| 6.3.8-200.fc38.x86_64        | 208       | 6.34%   |
| 6.4.15-200.fc38.x86_64       | 191       | 5.82%   |
| 6.5.5-200.fc38.x86_64        | 166       | 5.06%   |
| 6.2.14-300.fc38.x86_64       | 154       | 4.7%    |
| 6.2.11-300.fc38.x86_64       | 133       | 4.05%   |
| 6.3.12-200.fc38.x86_64       | 119       | 3.63%   |
| 6.5.8-200.fc38.x86_64        | 105       | 3.2%    |
| 6.5.6-200.fc38.x86_64        | 100       | 3.05%   |
| 6.5.7-200.fc38.x86_64        | 94        | 2.87%   |
| 6.4.11-200.fc38.x86_64       | 93        | 2.84%   |
| 6.4.6-200.fc38.x86_64        | 90        | 2.74%   |
| 6.3.11-200.fc38.x86_64       | 90        | 2.74%   |
| 6.4.12-200.fc38.x86_64       | 82        | 2.5%    |
| 6.4.14-200.fc38.x86_64       | 79        | 2.41%   |
| 6.4.7-200.fc38.x86_64        | 76        | 2.32%   |
| 6.3.5-200.fc38.x86_64        | 76        | 2.32%   |
| 6.4.13-200.fc38.x86_64       | 74        | 2.26%   |
| 6.2.13-300.fc38.x86_64       | 72        | 2.2%    |
| 6.4.10-200.fc38.x86_64       | 68        | 2.07%   |
| 6.3.6-200.fc38.x86_64        | 62        | 1.89%   |
| 6.2.12-300.fc38.x86_64       | 58        | 1.77%   |
| 6.4.4-200.fc38.x86_64        | 51        | 1.55%   |
| 6.3.4-201.fc38.x86_64        | 50        | 1.52%   |
| 6.3.7-200.fc38.x86_64        | 49        | 1.49%   |
| 6.4.9-200.fc38.x86_64        | 42        | 1.28%   |
| 6.5.9-200.fc38.x86_64        | 41        | 1.25%   |
| 6.5.10-200.fc38.x86_64       | 38        | 1.16%   |
| 6.2.8-300.fc38.x86_64        | 14        | 0.43%   |
| 6.4.8-200.fc38.x86_64        | 13        | 0.4%    |
| 6.2.6-300.fc38.x86_64        | 12        | 0.37%   |
| 6.6.6-100.fc38.x86_64        | 11        | 0.34%   |
| 6.5.12-200.fc38.x86_64       | 10        | 0.3%    |
| 6.2.10-300.fc38.x86_64       | 10        | 0.3%    |
| 6.2.2-301.fc38.x86_64        | 8         | 0.24%   |
| 6.2.15-703.inttf.fc38.x86_64 | 8         | 0.24%   |
| 6.2.7-300.fc38.x86_64        | 7         | 0.21%   |
| 6.3.3-200.fc38.x86_64        | 6         | 0.18%   |
| 6.6.7-100.fc38.x86_64        | 5         | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.9   | 345       | 10.52%  |
| 6.2.15  | 243       | 7.41%   |
| 6.3.8   | 210       | 6.4%    |
| 6.4.15  | 191       | 5.82%   |
| 6.5.5   | 169       | 5.15%   |
| 6.2.14  | 156       | 4.76%   |
| 6.2.11  | 135       | 4.12%   |
| 6.3.12  | 119       | 3.63%   |
| 6.5.8   | 107       | 3.26%   |
| 6.5.6   | 102       | 3.11%   |
| 6.5.7   | 94        | 2.87%   |
| 6.4.11  | 93        | 2.84%   |
| 6.4.6   | 91        | 2.78%   |
| 6.3.11  | 91        | 2.78%   |
| 6.4.12  | 83        | 2.53%   |
| 6.4.14  | 79        | 2.41%   |
| 6.4.7   | 78        | 2.38%   |
| 6.3.5   | 76        | 2.32%   |
| 6.4.13  | 75        | 2.29%   |
| 6.2.13  | 72        | 2.2%    |
| 6.4.10  | 70        | 2.13%   |
| 6.3.6   | 63        | 1.92%   |
| 6.2.12  | 58        | 1.77%   |
| 6.4.4   | 53        | 1.62%   |
| 6.3.4   | 50        | 1.52%   |
| 6.3.7   | 49        | 1.49%   |
| 6.4.9   | 42        | 1.28%   |
| 6.5.9   | 41        | 1.25%   |
| 6.5.10  | 38        | 1.16%   |
| 6.2.8   | 14        | 0.43%   |
| 6.4.8   | 13        | 0.4%    |
| 6.2.6   | 12        | 0.37%   |
| 6.2.10  | 12        | 0.37%   |
| 6.2.0   | 12        | 0.37%   |
| 6.6.6   | 11        | 0.34%   |
| 6.2.2   | 11        | 0.34%   |
| 6.5.12  | 10        | 0.3%    |
| 6.3.3   | 8         | 0.24%   |
| 6.2.7   | 7         | 0.21%   |
| 6.5.0   | 6         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1043      | 32.85%  |
| 6.4     | 844       | 26.58%  |
| 6.3     | 659       | 20.76%  |
| 6.5     | 563       | 17.73%  |
| 6.6     | 37        | 1.17%   |
| 6.1     | 11        | 0.35%   |
| 6.0     | 11        | 0.35%   |
| 5.19    | 2         | 0.06%   |
| 5.15    | 2         | 0.06%   |
| 5.4     | 1         | 0.03%   |
| 5.11    | 1         | 0.03%   |
| 5.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 2934      | 99.66%  |
| aarch64     | 8         | 0.27%   |
| ppc64le     | 1         | 0.03%   |
| loongarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 2296      | 77.25%  |
| KDE5          | 431       | 14.5%   |
| Unknown       | 56        | 1.88%   |
| XFCE          | 42        | 1.41%   |
| X-Cinnamon    | 33        | 1.11%   |
| Cinnamon      | 29        | 0.98%   |
| GNOME Classic | 21        | 0.71%   |
| MATE          | 15        | 0.5%    |
| sway          | 12        | 0.4%    |
| Hyprland      | 8         | 0.27%   |
| Budgie        | 8         | 0.27%   |
| LXDE          | 5         | 0.17%   |
| i3            | 5         | 0.17%   |
| LXQt          | 4         | 0.13%   |
| Unity         | 1         | 0.03%   |
| Pantheon      | 1         | 0.03%   |
| openbox       | 1         | 0.03%   |
| KDE4          | 1         | 0.03%   |
| KDE           | 1         | 0.03%   |
| e16-session   | 1         | 0.03%   |
| Deepin        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 2355      | 79%     |
| X11     | 537       | 18.01%  |
| Tty     | 60        | 2.01%   |
| Unknown | 28        | 0.94%   |
| Xcb     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1902      | 64.11%  |
| GDM     | 728       | 24.54%  |
| SDDM    | 206       | 6.94%   |
| LightDM | 126       | 4.25%   |
| LXDM    | 4         | 0.13%   |
| SLiM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1511      | 51.01%  |
| en_GB   | 214       | 7.22%   |
| de_DE   | 149       | 5.03%   |
| ru_RU   | 145       | 4.9%    |
| pt_BR   | 135       | 4.56%   |
| it_IT   | 78        | 2.63%   |
| fr_FR   | 77        | 2.6%    |
| en_AU   | 74        | 2.5%    |
| en_CA   | 72        | 2.43%   |
| es_ES   | 59        | 1.99%   |
| pl_PL   | 40        | 1.35%   |
| es_MX   | 40        | 1.35%   |
| en_IN   | 28        | 0.95%   |
| es_CL   | 23        | 0.78%   |
| es_CO   | 20        | 0.68%   |
| es_AR   | 17        | 0.57%   |
| en_DK   | 17        | 0.57%   |
| pt_PT   | 15        | 0.51%   |
| cs_CZ   | 15        | 0.51%   |
| tr_TR   | 14        | 0.47%   |
| zh_CN   | 13        | 0.44%   |
| de_AT   | 13        | 0.44%   |
| Unknown | 13        | 0.44%   |
| nl_NL   | 10        | 0.34%   |
| hu_HU   | 10        | 0.34%   |
| fr_CA   | 8         | 0.27%   |
| es_PE   | 8         | 0.27%   |
| en_NZ   | 8         | 0.27%   |
| en_IE   | 8         | 0.27%   |
| nl_BE   | 7         | 0.24%   |
| ru_UA   | 6         | 0.2%    |
| en_PH   | 6         | 0.2%    |
| de_CH   | 6         | 0.2%    |
| zh_TW   | 5         | 0.17%   |
| sk_SK   | 5         | 0.17%   |
| id_ID   | 5         | 0.17%   |
| en_ZA   | 5         | 0.17%   |
| da_DK   | 5         | 0.17%   |
| sv_SE   | 4         | 0.14%   |
| ja_JP   | 4         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2408      | 81.3%   |
| BIOS | 554       | 18.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 2466      | 83.56%  |
| Ext4    | 404       | 13.69%  |
| Xfs     | 72        | 2.44%   |
| Overlay | 4         | 0.14%   |
| Zfs     | 2         | 0.07%   |
| F2fs    | 1         | 0.03%   |
| Ext3    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1851      | 62.45%  |
| GPT     | 1054      | 35.56%  |
| MBR     | 59        | 1.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2710      | 91.55%  |
| Yes       | 250       | 8.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2499      | 84.68%  |
| Yes       | 452       | 15.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 575       | 19.53%  |
| ASUSTek Computer                     | 457       | 15.52%  |
| Hewlett-Packard                      | 377       | 12.81%  |
| Dell                                 | 369       | 12.53%  |
| MSI                                  | 212       | 7.2%    |
| Gigabyte Technology                  | 172       | 5.84%   |
| Acer                                 | 120       | 4.08%   |
| Apple                                | 111       | 3.77%   |
| ASRock                               | 89        | 3.02%   |
| HUAWEI                               | 48        | 1.63%   |
| Samsung Electronics                  | 36        | 1.22%   |
| Intel                                | 28        | 0.95%   |
| Unknown                              | 24        | 0.82%   |
| Microsoft                            | 23        | 0.78%   |
| Timi                                 | 20        | 0.68%   |
| Google                               | 20        | 0.68%   |
| Toshiba                              | 17        | 0.58%   |
| Sony                                 | 13        | 0.44%   |
| Fujitsu                              | 13        | 0.44%   |
| AZW                                  | 13        | 0.44%   |
| Pegatron                             | 10        | 0.34%   |
| Framework                            | 10        | 0.34%   |
| Notebook                             | 8         | 0.27%   |
| Chuwi                                | 7         | 0.24%   |
| System76                             | 6         | 0.2%    |
| Positivo                             | 6         | 0.2%    |
| TUXEDO                               | 5         | 0.17%   |
| Shenzhen Meigao Electronic Equipment | 5         | 0.17%   |
| Huanan                               | 5         | 0.17%   |
| Schenker                             | 4         | 0.14%   |
| Razer                                | 4         | 0.14%   |
| Positivo Bahia - VAIO                | 4         | 0.14%   |
| Packard Bell                         | 4         | 0.14%   |
| Medion                               | 4         | 0.14%   |
| Itautec                              | 4         | 0.14%   |
| HONOR                                | 4         | 0.14%   |
| AMI                                  | 4         | 0.14%   |
| Alienware                            | 4         | 0.14%   |
| raspberrypi,4-model-b                | 3         | 0.1%    |
| PC Specialist                        | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 28        | 0.95%   |
| ASUS All Series                      | 16        | 0.54%   |
| Apple MacBookPro9,2                  | 12        | 0.41%   |
| HP Notebook                          | 10        | 0.34%   |
| Dell OptiPlex 7010                   | 10        | 0.34%   |
| Apple MacBookPro8,1                  | 10        | 0.34%   |
| Framework Laptop                     | 8         | 0.27%   |
| MSI MS-7C37                          | 7         | 0.24%   |
| Dell XPS 13 9310                     | 7         | 0.24%   |
| MSI MS-7C95                          | 6         | 0.2%    |
| MSI MS-7C91                          | 6         | 0.2%    |
| MSI MS-7C56                          | 6         | 0.2%    |
| MSI MS-7B89                          | 6         | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8         | 6         | 0.2%    |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 6         | 0.2%    |
| Gigabyte X570 I AORUS PRO WIFI       | 6         | 0.2%    |
| AZW SER                              | 6         | 0.2%    |
| Samsung 550XDA                       | 5         | 0.17%   |
| MSI MS-7C02                          | 5         | 0.17%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU    | 5         | 0.17%   |
| HP EliteBook 840 G6                  | 5         | 0.17%   |
| Gigabyte B550 GAMING X V2            | 5         | 0.17%   |
| Dell OptiPlex 9020                   | 5         | 0.17%   |
| Dell Latitude 7490                   | 5         | 0.17%   |
| Dell Latitude 5420                   | 5         | 0.17%   |
| ASUS TUF Gaming X570-PRO             | 5         | 0.17%   |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.17%   |
| ASUS ROG STRIX X670E-I GAMING WIFI   | 5         | 0.17%   |
| ASRock B450M Pro4                    | 5         | 0.17%   |
| Apple MacBookPro12,1                 | 5         | 0.17%   |
| Apple MacBookPro11,1                 | 5         | 0.17%   |
| Apple MacBookAir7,2                  | 5         | 0.17%   |
| Timi Redmi Book Pro 14 2022          | 4         | 0.14%   |
| MSI MS-7C52                          | 4         | 0.14%   |
| MSI MS-7B79                          | 4         | 0.14%   |
| MSI MS-7A38                          | 4         | 0.14%   |
| Microsoft Surface Pro 7              | 4         | 0.14%   |
| Lenovo Yoga 6 13ALC6 82ND            | 4         | 0.14%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 4         | 0.14%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2    | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 262       | 8.9%    |
| Lenovo IdeaPad     | 109       | 3.7%    |
| Dell Latitude      | 106       | 3.6%    |
| ASUS ROG           | 99        | 3.36%   |
| Dell Inspiron      | 87        | 2.96%   |
| ASUS VivoBook      | 72        | 2.45%   |
| Acer Aspire        | 69        | 2.34%   |
| HP Pavilion        | 66        | 2.24%   |
| Dell XPS           | 58        | 1.97%   |
| ASUS PRIME         | 58        | 1.97%   |
| HP EliteBook       | 57        | 1.94%   |
| ASUS TUF           | 48        | 1.63%   |
| Dell OptiPlex      | 44        | 1.49%   |
| Lenovo Yoga        | 43        | 1.46%   |
| Lenovo Legion      | 38        | 1.29%   |
| HP Laptop          | 38        | 1.29%   |
| Dell Precision     | 37        | 1.26%   |
| HP ProBook         | 36        | 1.22%   |
| HP ENVY            | 34        | 1.15%   |
| Unknown            | 28        | 0.95%   |
| ASUS ASUS          | 27        | 0.92%   |
| Microsoft Surface  | 23        | 0.78%   |
| Lenovo ThinkBook   | 22        | 0.75%   |
| ASUS Zenbook       | 22        | 0.75%   |
| Lenovo ThinkCentre | 21        | 0.71%   |
| HP Compaq          | 20        | 0.68%   |
| Acer Nitro         | 19        | 0.65%   |
| Lenovo IdeaPadFlex | 18        | 0.61%   |
| ASUS All           | 16        | 0.54%   |
| Dell Vostro        | 15        | 0.51%   |
| HP OMEN            | 14        | 0.48%   |
| Toshiba Satellite  | 13        | 0.44%   |
| Apple MacBookPro9  | 13        | 0.44%   |
| Gigabyte B550M     | 12        | 0.41%   |
| Apple MacBookPro8  | 12        | 0.41%   |
| HP EliteDesk       | 11        | 0.37%   |
| Gigabyte X570      | 11        | 0.37%   |
| Gigabyte B550      | 11        | 0.37%   |
| HP ZBook           | 10        | 0.34%   |
| HP Notebook        | 10        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 395       | 13.42%  |
| 2020    | 387       | 13.15%  |
| 2022    | 380       | 12.91%  |
| 2018    | 283       | 9.61%   |
| 2019    | 256       | 8.7%    |
| 2017    | 178       | 6.05%   |
| 2023    | 166       | 5.64%   |
| 2012    | 150       | 5.1%    |
| 2013    | 132       | 4.48%   |
| 2015    | 128       | 4.35%   |
| 2014    | 120       | 4.08%   |
| 2016    | 107       | 3.63%   |
| 2011    | 93        | 3.16%   |
| 2010    | 66        | 2.24%   |
| 2009    | 42        | 1.43%   |
| 2008    | 33        | 1.12%   |
| 2007    | 19        | 0.65%   |
| 2006    | 4         | 0.14%   |
| Unknown | 4         | 0.14%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1753      | 59.54%  |
| Desktop        | 906       | 30.77%  |
| Convertible    | 137       | 4.65%   |
| Tablet         | 50        | 1.7%    |
| Mini pc        | 48        | 1.63%   |
| All in one     | 30        | 1.02%   |
| Server         | 14        | 0.48%   |
| System on chip | 6         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2300      | 77.55%  |
| Enabled  | 666       | 22.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2918      | 99.12%  |
| Yes  | 26        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 728       | 24.55%  |
| 4.01-8.0        | 664       | 22.39%  |
| 8.01-16.0       | 552       | 18.62%  |
| 32.01-64.0      | 462       | 15.58%  |
| 3.01-4.0        | 244       | 8.23%   |
| 64.01-256.0     | 156       | 5.26%   |
| 24.01-32.0      | 108       | 3.64%   |
| 1.01-2.0        | 38        | 1.28%   |
| 2.01-3.0        | 12        | 0.4%    |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 979       | 31.18%  |
| 2.01-3.0    | 803       | 25.57%  |
| 3.01-4.0    | 737       | 23.47%  |
| 1.01-2.0    | 309       | 9.84%   |
| 8.01-16.0   | 252       | 8.03%   |
| 0.51-1.0    | 26        | 0.83%   |
| 16.01-24.0  | 24        | 0.76%   |
| 32.01-64.0  | 5         | 0.16%   |
| 24.01-32.0  | 3         | 0.1%    |
| 64.01-256.0 | 1         | 0.03%   |
| 0.01-0.5    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1825      | 61.12%  |
| 2      | 741       | 24.82%  |
| 3      | 222       | 7.43%   |
| 4      | 101       | 3.38%   |
| 5      | 48        | 1.61%   |
| 6      | 26        | 0.87%   |
| 0      | 7         | 0.23%   |
| 7      | 6         | 0.2%    |
| 8      | 4         | 0.13%   |
| 10     | 3         | 0.1%    |
| 11     | 2         | 0.07%   |
| 9      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2365      | 80.14%  |
| Yes       | 586       | 19.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2279      | 77.15%  |
| No        | 675       | 22.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2493      | 84.45%  |
| No        | 459       | 15.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2202      | 74.42%  |
| No        | 757       | 25.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 545       | 18.45%  |
| Germany     | 229       | 7.75%   |
| Brazil      | 203       | 6.87%   |
| Russia      | 161       | 5.45%   |
| Italy       | 130       | 4.4%    |
| UK          | 114       | 3.86%   |
| Canada      | 112       | 3.79%   |
| France      | 94        | 3.18%   |
| India       | 89        | 3.01%   |
| Spain       | 84        | 2.84%   |
| Australia   | 82        | 2.78%   |
| Poland      | 77        | 2.61%   |
| Netherlands | 73        | 2.47%   |
| Mexico      | 73        | 2.47%   |
| Turkey      | 43        | 1.46%   |
| Czechia     | 37        | 1.25%   |
| Colombia    | 35        | 1.18%   |
| Chile       | 31        | 1.05%   |
| Sweden      | 30        | 1.02%   |
| Switzerland | 29        | 0.98%   |
| Austria     | 29        | 0.98%   |
| Belgium     | 28        | 0.95%   |
| Argentina   | 28        | 0.95%   |
| Portugal    | 26        | 0.88%   |
| Hungary     | 25        | 0.85%   |
| Indonesia   | 24        | 0.81%   |
| Denmark     | 22        | 0.74%   |
| Belarus     | 22        | 0.74%   |
| Bulgaria    | 21        | 0.71%   |
| Norway      | 20        | 0.68%   |
| Romania     | 18        | 0.61%   |
| Finland     | 17        | 0.58%   |
| China       | 17        | 0.58%   |
| Thailand    | 16        | 0.54%   |
| Philippines | 15        | 0.51%   |
| Israel      | 13        | 0.44%   |
| Serbia      | 12        | 0.41%   |
| Ireland     | 12        | 0.41%   |
| Egypt       | 12        | 0.41%   |
| Vietnam     | 11        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 38        | 1.26%   |
| Sydney            | 33        | 1.1%    |
| Berlin            | 26        | 0.86%   |
| Sao Paulo         | 23        | 0.76%   |
| Mexico City       | 21        | 0.7%    |
| Vienna            | 20        | 0.66%   |
| Santiago          | 18        | 0.6%    |
| Warsaw            | 17        | 0.56%   |
| St Petersburg     | 17        | 0.56%   |
| Minsk             | 17        | 0.56%   |
| Milan             | 16        | 0.53%   |
| Melbourne         | 16        | 0.53%   |
| Madrid            | 16        | 0.53%   |
| Sofia             | 14        | 0.47%   |
| Montreal          | 14        | 0.47%   |
| Delhi             | 14        | 0.47%   |
| Budapest          | 14        | 0.47%   |
| Prague            | 13        | 0.43%   |
| Paris             | 13        | 0.43%   |
| Helsinki          | 13        | 0.43%   |
| Brisbane          | 13        | 0.43%   |
| Amsterdam         | 13        | 0.43%   |
| Toronto           | 12        | 0.4%    |
| Rio de Janeiro    | 12        | 0.4%    |
| Munich            | 12        | 0.4%    |
| Istanbul          | 12        | 0.4%    |
| Bogotá           | 12        | 0.4%    |
| Singapore         | 11        | 0.37%   |
| Seattle           | 11        | 0.37%   |
| Lisbon            | 11        | 0.37%   |
| Hamburg           | 11        | 0.37%   |
| Brussels          | 11        | 0.37%   |
| Barcelona         | 11        | 0.37%   |
| Bangkok           | 11        | 0.37%   |
| San José         | 10        | 0.33%   |
| Frankfurt am Main | 10        | 0.33%   |
| Brasília         | 10        | 0.33%   |
| Palmas            | 9         | 0.3%    |
| New York          | 9         | 0.3%    |
| Los Angeles       | 9         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 842       | 1195   | 19.6%   |
| Sandisk                      | 387       | 458    | 9.01%   |
| WDC                          | 384       | 549    | 8.94%   |
| Seagate                      | 372       | 514    | 8.66%   |
| Kingston                     | 226       | 269    | 5.26%   |
| Toshiba                      | 198       | 258    | 4.61%   |
| SK hynix                     | 159       | 173    | 3.7%    |
| Unknown                      | 153       | 186    | 3.56%   |
| Crucial                      | 152       | 199    | 3.54%   |
| Intel                        | 151       | 204    | 3.51%   |
| Micron Technology            | 149       | 162    | 3.47%   |
| Phison Electronics           | 77        | 94     | 1.79%   |
| Micron/Crucial Technology    | 67        | 73     | 1.56%   |
| Apple                        | 59        | 78     | 1.37%   |
| KIOXIA                       | 57        | 68     | 1.33%   |
| Silicon Motion               | 53        | 62     | 1.23%   |
| A-DATA Technology            | 53        | 61     | 1.23%   |
| Hitachi                      | 51        | 69     | 1.19%   |
| Kingston Technology Company  | 49        | 58     | 1.14%   |
| HGST                         | 45        | 46     | 1.05%   |
| China                        | 41        | 53     | 0.95%   |
| ADATA Technology             | 32        | 38     | 0.74%   |
| PNY                          | 21        | 25     | 0.49%   |
| SPCC                         | 20        | 22     | 0.47%   |
| Patriot                      | 20        | 26     | 0.47%   |
| Netac                        | 20        | 21     | 0.47%   |
| Realtek Semiconductor        | 18        | 22     | 0.42%   |
| MAXIO Technology (Hangzhou)  | 18        | 21     | 0.42%   |
| JMicron Technology           | 17        | 21     | 0.4%    |
| Intenso                      | 17        | 19     | 0.4%    |
| Shenzhen Longsys Electronics | 12        | 14     | 0.28%   |
| Unknown                      | 12        | 14     | 0.28%   |
| KingSpec                     | 11        | 12     | 0.26%   |
| Union Memory                 | 10        | 10     | 0.23%   |
| Team                         | 10        | 12     | 0.23%   |
| Solid State Storage          | 10        | 11     | 0.23%   |
| SABRENT                      | 10        | 10     | 0.23%   |
| LITEON                       | 10        | 10     | 0.23%   |
| Lenovo                       | 10        | 10     | 0.23%   |
| GOODRAM                      | 10        | 14     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 199       | 4.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB                | 126       | 2.71%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 55        | 1.18%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                               | 49        | 1.05%   |
| Kingston SA400S37480G 480GB SSD                                   | 45        | 0.97%   |
| Kingston SA400S37240G 240GB SSD                                   | 45        | 0.97%   |
| Unknown MMC Card  64GB                                            | 41        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB               | 40        | 0.86%   |
| Samsung SSD 980 1TB                                               | 36        | 0.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB                    | 35        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB             | 34        | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 34        | 0.73%   |
| Phison E12 NVMe Controller 1TB                                    | 33        | 0.71%   |
| Crucial CT500MX500SSD1 500GB                                      | 33        | 0.71%   |
| Unknown MMC Card  128GB                                           | 31        | 0.67%   |
| Intel SSD 660P Series 1TB                                         | 31        | 0.67%   |
| Unknown MMC Card  32GB                                            | 30        | 0.65%   |
| Samsung SSD 850 EVO 250GB                                         | 27        | 0.58%   |
| Toshiba XG6 NVMe SSD Controller 512GB                             | 26        | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                                         | 26        | 0.56%   |
| Sandisk WD Black SN850 1024GB                                     | 25        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 24        | 0.52%   |
| Samsung SSD 870 EVO 1TB                                           | 24        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                                       | 23        | 0.49%   |
| Samsung SSD 860 EVO 500GB                                         | 22        | 0.47%   |
| Samsung SSD 860 EVO 1TB                                           | 22        | 0.47%   |
| Phison PS5013 E13 NVMe Controller 512GB                           | 21        | 0.45%   |
| Samsung SSD 850 EVO 500GB                                         | 19        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                                   | 18        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 18        | 0.39%   |
| Toshiba DT01ACA100 1TB                                            | 17        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                                    | 17        | 0.37%   |
| Toshiba MQ04ABF100 1TB                                            | 16        | 0.34%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                       | 16        | 0.34%   |
| Kingston SA400S37120G 120GB SSD                                   | 16        | 0.34%   |
| Crucial CT240BX500SSD1 240GB                                      | 16        | 0.34%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 16        | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 15        | 0.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 15        | 0.32%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB                   | 15        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 355       | 484    | 36.56%  |
| WDC                 | 299       | 432    | 30.79%  |
| Toshiba             | 126       | 170    | 12.98%  |
| Hitachi             | 51        | 69     | 5.25%   |
| HGST                | 45        | 46     | 4.63%   |
| Samsung Electronics | 29        | 38     | 2.99%   |
| Apple               | 18        | 21     | 1.85%   |
| Unknown             | 13        | 15     | 1.34%   |
| SABRENT             | 10        | 10     | 1.03%   |
| TO Exter            | 3         | 3      | 0.31%   |
| QNAP                | 3         | 6      | 0.31%   |
| Maxtor              | 3         | 3      | 0.31%   |
| Fujitsu             | 3         | 3      | 0.31%   |
| ASMT                | 2         | 3      | 0.21%   |
| XrayDisk            | 1         | 1      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| USB                 | 1         | 1      | 0.1%    |
| SAGE                | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| LIO-ORG             | 1         | 4      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| IB                  | 1         | 2      | 0.1%    |
| ACASIS              | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 302       | 424    | 22.93%  |
| Kingston            | 167       | 198    | 12.68%  |
| Crucial             | 149       | 193    | 11.31%  |
| SanDisk             | 106       | 121    | 8.05%   |
| WDC                 | 86        | 103    | 6.53%   |
| A-DATA Technology   | 44        | 50     | 3.34%   |
| Intel               | 41        | 64     | 3.11%   |
| China               | 41        | 53     | 3.11%   |
| Apple               | 27        | 29     | 2.05%   |
| Toshiba             | 24        | 29     | 1.82%   |
| Micron Technology   | 24        | 25     | 1.82%   |
| PNY                 | 21        | 25     | 1.59%   |
| SPCC                | 20        | 22     | 1.52%   |
| Patriot             | 20        | 26     | 1.52%   |
| Netac               | 12        | 12     | 0.91%   |
| JMicron Technology  | 12        | 14     | 0.91%   |
| SK hynix            | 10        | 12     | 0.76%   |
| LITEON              | 10        | 10     | 0.76%   |
| KingSpec            | 10        | 11     | 0.76%   |
| Intenso             | 10        | 10     | 0.76%   |
| GOODRAM             | 10        | 14     | 0.76%   |
| Team                | 9         | 11     | 0.68%   |
| LITEONIT            | 9         | 9      | 0.68%   |
| Transcend           | 8         | 10     | 0.61%   |
| OCZ                 | 7         | 11     | 0.53%   |
| Lexar               | 7         | 7      | 0.53%   |
| Hewlett-Packard     | 7         | 7      | 0.53%   |
| Gigabyte Technology | 7         | 9      | 0.53%   |
| Apacer              | 7         | 9      | 0.53%   |
| Mushkin             | 6         | 6      | 0.46%   |
| Emtec               | 5         | 6      | 0.38%   |
| AMD                 | 4         | 4      | 0.3%    |
| Unknown             | 4         | 6      | 0.3%    |
| XrayDisk            | 3         | 3      | 0.23%   |
| Smartbuy            | 3         | 3      | 0.23%   |
| MidasForce          | 3         | 3      | 0.23%   |
| Lenovo              | 3         | 3      | 0.23%   |
| Colorful            | 3         | 3      | 0.23%   |
| ASMT                | 3         | 3      | 0.23%   |
| Advantech           | 3         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1728      | 2278   | 43.87%  |
| SSD     | 1142      | 1647   | 28.99%  |
| HDD     | 851       | 1318   | 21.6%   |
| MMC     | 140       | 168    | 3.55%   |
| Unknown | 78        | 86     | 1.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1728      | 2272   | 48.08%  |
| SATA | 1573      | 2859   | 43.77%  |
| SAS  | 153       | 198    | 4.26%   |
| MMC  | 140       | 168    | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1075      | 1584   | 52.26%  |
| 0.51-1.0   | 649       | 869    | 31.55%  |
| 1.01-2.0   | 210       | 302    | 10.21%  |
| 3.01-4.0   | 62        | 95     | 3.01%   |
| 4.01-10.0  | 33        | 69     | 1.6%    |
| 2.01-3.0   | 21        | 26     | 1.02%   |
| 10.01-20.0 | 7         | 20     | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 687       | 22.8%   |
| 251-500        | 562       | 18.65%  |
| 1001-2000      | 491       | 16.3%   |
| 101-250        | 361       | 11.98%  |
| 1-20           | 233       | 7.73%   |
| Unknown        | 219       | 7.27%   |
| More than 3000 | 200       | 6.64%   |
| 2001-3000      | 125       | 4.15%   |
| 51-100         | 95        | 3.15%   |
| 21-50          | 39        | 1.29%   |
| 0              | 1         | 0.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 944       | 30.61%  |
| 21-50          | 507       | 16.44%  |
| 101-250        | 393       | 12.74%  |
| 51-100         | 333       | 10.8%   |
| 251-500        | 288       | 9.34%   |
| Unknown        | 219       | 7.1%    |
| 501-1000       | 198       | 6.42%   |
| 1001-2000      | 116       | 3.76%   |
| More than 3000 | 45        | 1.46%   |
| 2001-3000      | 40        | 1.3%    |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 5      | 3.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 2.31%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 2.31%   |
| Intel SSDSC2CT120A3 120GB             | 3         | 8      | 2.31%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 2.31%   |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 1.54%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.54%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 1.54%   |
| Seagate ST1000DX001-1NS162 1TB        | 2         | 2      | 1.54%   |
| SanDisk SSD PLUS 480GB                | 2         | 2      | 1.54%   |
| SanDisk SD8SBAT256G1122 256GB SSD     | 2         | 2      | 1.54%   |
| Samsung Electronics SSD 840 EVO 250GB | 2         | 2      | 1.54%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 3      | 1.54%   |
| Crucial CT120M500SSD1 120GB           | 2         | 7      | 1.54%   |
| YS SSD 240GB                          | 1         | 1      | 0.77%   |
| Wibtek W800S 512GB SSD                | 1         | 1      | 0.77%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1         | 1      | 0.77%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.77%   |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 0.77%   |
| WDC WD5000AVCS-632DY1 500GB           | 1         | 3      | 0.77%   |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 0.77%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 1         | 1      | 0.77%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.77%   |
| WDC WD40PURX-64GVNY0 4TB              | 1         | 1      | 0.77%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 1      | 0.77%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1         | 1      | 0.77%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 2      | 0.77%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 0.77%   |
| WDC WD20EZRZ-22Z5HB0 2TB              | 1         | 1      | 0.77%   |
| WDC WD20EARS-00J2GB0 2TB              | 1         | 1      | 0.77%   |
| WDC WD10JPVT-60A1YT0 1TB              | 1         | 1      | 0.77%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.77%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 0.77%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 0.77%   |
| SSSTC CVB-8D128-HP 128GB SSD          | 1         | 1      | 0.77%   |
| SPCC Solid State Disk 128GB           | 1         | 1      | 0.77%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 0.77%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.77%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 25        | 31     | 20%     |
| WDC                         | 20        | 26     | 16%     |
| Samsung Electronics         | 14        | 20     | 11.2%   |
| Intel                       | 9         | 14     | 7.2%    |
| Hitachi                     | 9         | 9      | 7.2%    |
| Toshiba                     | 6         | 6      | 4.8%    |
| SanDisk                     | 5         | 5      | 4%      |
| Kingston                    | 5         | 8      | 4%      |
| HGST                        | 5         | 5      | 4%      |
| Crucial                     | 4         | 9      | 3.2%    |
| SK hynix                    | 2         | 2      | 1.6%    |
| Micron Technology           | 2         | 2      | 1.6%    |
| Maxtor                      | 2         | 2      | 1.6%    |
| LITEONIT                    | 2         | 2      | 1.6%    |
| Intenso                     | 2         | 2      | 1.6%    |
| China                       | 2         | 2      | 1.6%    |
| A-DATA Technology           | 2         | 2      | 1.6%    |
| YS                          | 1         | 1      | 0.8%    |
| Wibtek                      | 1         | 1      | 0.8%    |
| SSSTC                       | 1         | 1      | 0.8%    |
| SPCC                        | 1         | 1      | 0.8%    |
| Netac                       | 1         | 1      | 0.8%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.8%    |
| LITEON                      | 1         | 1      | 0.8%    |
| HPE                         | 1         | 1      | 0.8%    |
| Apple                       | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 31     | 35.71%  |
| WDC                 | 17        | 22     | 24.29%  |
| Hitachi             | 9         | 9      | 12.86%  |
| Toshiba             | 6         | 6      | 8.57%   |
| Samsung Electronics | 5         | 10     | 7.14%   |
| HGST                | 5         | 5      | 7.14%   |
| Maxtor              | 2         | 2      | 2.86%   |
| Apple               | 1         | 1      | 1.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 86     | 54.62%  |
| SSD  | 49        | 65     | 41.18%  |
| NVMe | 5         | 5      | 4.2%    |

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
| Detected | 1993      | 3572   | 63.96%  |
| Works    | 1010      | 1769   | 32.41%  |
| Malfunc  | 113       | 156    | 3.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1543      | 37.87%  |
| AMD                                     | 628       | 15.41%  |
| Samsung Electronics                     | 589       | 14.45%  |
| SanDisk                                 | 294       | 7.21%   |
| SK hynix                                | 148       | 3.63%   |
| Micron Technology                       | 125       | 3.07%   |
| Kingston Technology Company             | 113       | 2.77%   |
| Phison Electronics                      | 84        | 2.06%   |
| Micron/Crucial Technology               | 69        | 1.69%   |
| ASMedia Technology                      | 56        | 1.37%   |
| Silicon Motion                          | 55        | 1.35%   |
| KIOXIA                                  | 55        | 1.35%   |
| Toshiba America Info Systems            | 52        | 1.28%   |
| ADATA Technology                        | 40        | 0.98%   |
| Marvell Technology Group                | 26        | 0.64%   |
| Solid State Storage Technology          | 20        | 0.49%   |
| Realtek Semiconductor                   | 18        | 0.44%   |
| MAXIO Technology (Hangzhou)             | 18        | 0.44%   |
| Union Memory (Shenzhen)                 | 17        | 0.42%   |
| Nvidia                                  | 15        | 0.37%   |
| Apple                                   | 15        | 0.37%   |
| Shenzhen Longsys Electronics            | 12        | 0.29%   |
| Seagate Technology                      | 12        | 0.29%   |
| JMicron Technology                      | 10        | 0.25%   |
| Netac Technology                        | 9         | 0.22%   |
| LSI Logic / Symbios Logic               | 7         | 0.17%   |
| Lenovo                                  | 7         | 0.17%   |
| Yangtze Memory Technologies             | 6         | 0.15%   |
| Solidigm                                | 5         | 0.12%   |
| VIA Technologies                        | 4         | 0.1%    |
| INNOGRIT                                | 4         | 0.1%    |
| Broadcom / LSI                          | 4         | 0.1%    |
| Silicon Image                           | 2         | 0.05%   |
| Shenzhen Unionmemory Information System | 2         | 0.05%   |
| Lite-On Technology                      | 2         | 0.05%   |
| Biwin Storage Technology                | 2         | 0.05%   |
| Adaptec                                 | 2         | 0.05%   |
| ULi Electronics                         | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.02%   |
| PMC-Sierra                              | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 444       | 9.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 211       | 4.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 156       | 3.51%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 152       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 133       | 2.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 131       | 2.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 92        | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                         | 91        | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 87        | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 1.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 82        | 1.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 67        | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 62        | 1.39%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 57        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 54        | 1.21%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 51        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 51        | 1.15%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 49        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 49        | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 48        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 43        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 43        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 43        | 0.97%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 41        | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 0.9%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 38        | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 37        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 36        | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 35        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 34        | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 0.72%   |
| Intel SSD 660P Series                                                          | 31        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 31        | 0.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 30        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 30        | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 29        | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 29        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1858      | 46.23%  |
| NVMe | 1719      | 42.77%  |
| RAID | 313       | 7.79%   |
| IDE  | 116       | 2.89%   |
| SAS  | 7         | 0.17%   |
| SCSI | 6         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 2023      | 68.72%  |
| AMD                      | 910       | 30.91%  |
| ARM                      | 7         | 0.24%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.03%   |
| Loongson                 | 1         | 0.03%   |
| CentaurHauls             | 1         | 0.03%   |
| Unknown                  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 68        | 2.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 48        | 1.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 36        | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 25        | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.78%   |
| Intel 12th Gen Core i7-12700H                 | 23        | 0.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 23        | 0.78%   |
| Intel 12th Gen Core i7-1255U                  | 22        | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 20        | 0.68%   |
| Intel 12th Gen Core i7-1260P                  | 20        | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 20        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 19        | 0.64%   |
| Intel 12th Gen Core i5-1235U                  | 19        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.61%   |
| Intel 12th Gen Core i5-12500H                 | 18        | 0.61%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.58%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 17        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 16        | 0.54%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 16        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.51%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 0.51%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 15        | 0.51%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 0.51%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 15        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 14        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 583       | 19.8%   |
| Other                   | 523       | 17.76%  |
| Intel Core i7           | 474       | 16.1%   |
| AMD Ryzen 5             | 295       | 10.02%  |
| AMD Ryzen 7             | 292       | 9.92%   |
| Intel Core i3           | 136       | 4.62%   |
| AMD Ryzen 9             | 114       | 3.87%   |
| Intel Celeron           | 85        | 2.89%   |
| Intel Xeon              | 61        | 2.07%   |
| Intel Core 2 Duo        | 44        | 1.49%   |
| Intel Atom              | 38        | 1.29%   |
| AMD Ryzen 3             | 33        | 1.12%   |
| AMD Ryzen 7 PRO         | 24        | 0.81%   |
| AMD FX                  | 23        | 0.78%   |
| Intel Pentium           | 20        | 0.68%   |
| Intel Core i9           | 18        | 0.61%   |
| AMD A10                 | 16        | 0.54%   |
| Intel Pentium Silver    | 15        | 0.51%   |
| AMD Ryzen 5 PRO         | 15        | 0.51%   |
| AMD Phenom II X4        | 13        | 0.44%   |
| AMD A6                  | 13        | 0.44%   |
| Intel Core 2 Quad       | 12        | 0.41%   |
| AMD A8                  | 10        | 0.34%   |
| AMD Ryzen Threadripper  | 8         | 0.27%   |
| AMD Athlon              | 7         | 0.24%   |
| AMD A4                  | 7         | 0.24%   |
| Intel Pentium Dual-Core | 6         | 0.2%    |
| Intel Pentium Gold      | 5         | 0.17%   |
| Intel Pentium Dual      | 5         | 0.17%   |
| AMD E2                  | 5         | 0.17%   |
| Intel Genuine           | 4         | 0.14%   |
| Intel Core m5           | 3         | 0.1%    |
| Intel Core 2            | 3         | 0.1%    |
| AMD Phenom II X6        | 3         | 0.1%    |
| AMD Phenom II X2        | 3         | 0.1%    |
| AMD E1                  | 3         | 0.1%    |
| AMD A12                 | 3         | 0.1%    |
| Intel Core m3           | 2         | 0.07%   |
| Intel Core M            | 2         | 0.07%   |
| Intel Celeron Dual-Core | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1012      | 34.38%  |
| 2       | 717       | 24.35%  |
| 8       | 428       | 14.54%  |
| 6       | 422       | 14.33%  |
| 12      | 124       | 4.21%   |
| 10      | 83        | 2.82%   |
| 14      | 65        | 2.21%   |
| 16      | 54        | 1.83%   |
| 24      | 12        | 0.41%   |
| 1       | 11        | 0.37%   |
| 3       | 6         | 0.2%    |
| Unknown | 3         | 0.1%    |
| 36      | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 20      | 2         | 0.07%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2922      | 99.25%  |
| 2       | 19        | 0.65%   |
| Unknown | 3         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2405      | 81.66%  |
| 1       | 536       | 18.2%   |
| Unknown | 3         | 0.1%    |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2936      | 99.73%  |
| 64-bit         | 6         | 0.2%    |
| Unknown        | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2081      | 70.4%   |
| 0x0a50000c | 87        | 2.94%   |
| 0x0a50000d | 74        | 2.5%    |
| 0x08108109 | 51        | 1.73%   |
| 0x0a601203 | 49        | 1.66%   |
| 0x0a404102 | 47        | 1.59%   |
| 0x08600106 | 47        | 1.59%   |
| 0x08608103 | 46        | 1.56%   |
| 0x0a20120a | 45        | 1.52%   |
| 0x08701021 | 40        | 1.35%   |
| 0x0800820d | 31        | 1.05%   |
| 0x0a201016 | 20        | 0.68%   |
| 0x08600104 | 20        | 0.68%   |
| 0x08701030 | 18        | 0.61%   |
| 0x08108102 | 18        | 0.61%   |
| 0x0a404101 | 15        | 0.51%   |
| 0x06006705 | 11        | 0.37%   |
| 0x010000c8 | 11        | 0.37%   |
| 0x08608104 | 10        | 0.34%   |
| 0x06001119 | 10        | 0.34%   |
| 0x08a00008 | 9         | 0.3%    |
| 0x08608102 | 9         | 0.3%    |
| 0x08701013 | 8         | 0.27%   |
| 0x08600103 | 8         | 0.27%   |
| 0x06000822 | 8         | 0.27%   |
| 0x0a704103 | 7         | 0.24%   |
| 0x0a201025 | 7         | 0.24%   |
| 0x0a201009 | 7         | 0.24%   |
| 0x08600109 | 7         | 0.24%   |
| 0x08101016 | 7         | 0.24%   |
| 0x08001137 | 7         | 0.24%   |
| 0x06000852 | 7         | 0.24%   |
| 0x0810100b | 6         | 0.2%    |
| 0x08001138 | 6         | 0.2%    |
| 0x0600611a | 6         | 0.2%    |
| 0x0a50000b | 5         | 0.17%   |
| 0x0a201205 | 5         | 0.17%   |
| 0x08101007 | 5         | 0.17%   |
| 0x0700010f | 5         | 0.17%   |
| 0x010000b6 | 5         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 490       | 16.63%  |
| Zen 3             | 272       | 9.23%   |
| Alderlake Hybrid  | 257       | 8.72%   |
| Unknown           | 245       | 8.31%   |
| TigerLake         | 186       | 6.31%   |
| Haswell           | 172       | 5.84%   |
| Zen 2             | 155       | 5.26%   |
| IvyBridge         | 153       | 5.19%   |
| Skylake           | 145       | 4.92%   |
| Zen+              | 107       | 3.63%   |
| SandyBridge       | 107       | 3.63%   |
| Icelake           | 85        | 2.88%   |
| CometLake         | 85        | 2.88%   |
| Silvermont        | 60        | 2.04%   |
| Broadwell         | 60        | 2.04%   |
| Penryn            | 55        | 1.87%   |
| Westmere          | 50        | 1.7%    |
| Zen               | 42        | 1.43%   |
| Goldmont plus     | 38        | 1.29%   |
| Piledriver        | 35        | 1.19%   |
| Excavator         | 25        | 0.85%   |
| K10               | 24        | 0.81%   |
| Core              | 21        | 0.71%   |
| Tremont           | 13        | 0.44%   |
| Goldmont          | 13        | 0.44%   |
| Nehalem           | 9         | 0.31%   |
| Puma              | 7         | 0.24%   |
| Steamroller       | 6         | 0.2%    |
| Jaguar            | 6         | 0.2%    |
| K8 Hammer         | 5         | 0.17%   |
| Bulldozer         | 5         | 0.17%   |
| Bonnell           | 5         | 0.17%   |
| Gracemont         | 4         | 0.14%   |
| K10 Llano         | 2         | 0.07%   |
| Meteorlake Hybrid | 1         | 0.03%   |
| K8 & K10 hybrid   | 1         | 0.03%   |
| Bobcat            | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1662      | 47.28%  |
| AMD                              | 944       | 26.86%  |
| Nvidia                           | 892       | 25.38%  |
| Matrox Electronics Systems       | 10        | 0.28%   |
| ASPEED Technology                | 3         | 0.09%   |
| Zhaoxin                          | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Loongson Technology              | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 174       | 4.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 120       | 3.32%   |
| Intel UHD Graphics 620                                                                   | 93        | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 81        | 2.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 81        | 2.24%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 80        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 70        | 1.94%   |
| AMD Rembrandt [Radeon 680M]                                                              | 68        | 1.88%   |
| AMD Lucienne                                                                             | 67        | 1.86%   |
| Intel HD Graphics 620                                                                    | 65        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 59        | 1.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 59        | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 55        | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 52        | 1.44%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 49        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.33%   |
| Intel HD Graphics 530                                                                    | 43        | 1.19%   |
| AMD Raphael                                                                              | 42        | 1.16%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 41        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.08%   |
| AMD Barcelo                                                                              | 39        | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 37        | 1.02%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 35        | 0.97%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 35        | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 34        | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 34        | 0.94%   |
| Intel HD Graphics 630                                                                    | 34        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 28        | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 0.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 27        | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 1179      | 39.87%  |
| 1 x AMD                 | 720       | 24.35%  |
| Intel + Nvidia          | 397       | 13.43%  |
| 1 x Nvidia              | 385       | 13.02%  |
| AMD + Nvidia            | 104       | 3.52%   |
| 2 x AMD                 | 65        | 2.2%    |
| Intel + AMD             | 56        | 1.89%   |
| 2 x Intel               | 14        | 0.47%   |
| Other                   | 11        | 0.37%   |
| 1 x Matrox              | 9         | 0.3%    |
| 2 x Nvidia              | 8         | 0.27%   |
| 1 x ASPEED              | 2         | 0.07%   |
| 1 x Zhaoxin             | 1         | 0.03%   |
| 1 x VIA                 | 1         | 0.03%   |
| 1 x SiS                 | 1         | 0.03%   |
| Nvidia + Matrox         | 1         | 0.03%   |
| 1 x Loongson Technology | 1         | 0.03%   |
| Intel + 2 x AMD         | 1         | 0.03%   |
| AMD + ASPEED            | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2463      | 83.1%   |
| Proprietary | 415       | 14%     |
| Unknown     | 86        | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1589      | 53.3%   |
| 0.01-0.5   | 346       | 11.61%  |
| 1.01-2.0   | 264       | 8.86%   |
| 3.01-4.0   | 236       | 7.92%   |
| 7.01-8.0   | 197       | 6.61%   |
| 0.51-1.0   | 164       | 5.5%    |
| 8.01-16.0  | 94        | 3.15%   |
| 5.01-6.0   | 52        | 1.74%   |
| 16.01-24.0 | 21        | 0.7%    |
| 2.01-3.0   | 17        | 0.57%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 425       | 12.38%  |
| Samsung Electronics     | 390       | 11.36%  |
| AU Optronics            | 363       | 10.57%  |
| Chimei Innolux          | 323       | 9.41%   |
| Goldstar                | 247       | 7.19%   |
| LG Display              | 227       | 6.61%   |
| Dell                    | 224       | 6.52%   |
| Hewlett-Packard         | 107       | 3.12%   |
| Apple                   | 99        | 2.88%   |
| Acer                    | 87        | 2.53%   |
| Sharp                   | 76        | 2.21%   |
| Lenovo                  | 74        | 2.15%   |
| AOC                     | 69        | 2.01%   |
| Philips                 | 63        | 1.83%   |
| BenQ                    | 56        | 1.63%   |
| Ancor Communications    | 46        | 1.34%   |
| ASUSTek Computer        | 44        | 1.28%   |
| PANDA                   | 39        | 1.14%   |
| CSO                     | 36        | 1.05%   |
| InfoVision              | 34        | 0.99%   |
| ViewSonic               | 25        | 0.73%   |
| Iiyama                  | 25        | 0.73%   |
| Chi Mei Optoelectronics | 22        | 0.64%   |
| MSI                     | 20        | 0.58%   |
| Gigabyte Technology     | 20        | 0.58%   |
| TMX                     | 18        | 0.52%   |
| Sceptre Tech            | 17        | 0.5%    |
| Unknown                 | 16        | 0.47%   |
| Sony                    | 14        | 0.41%   |
| Mi                      | 9         | 0.26%   |
| Toshiba                 | 8         | 0.23%   |
| LG Philips              | 8         | 0.23%   |
| Eizo                    | 8         | 0.23%   |
| Vizio                   | 7         | 0.2%    |
| Panasonic               | 7         | 0.2%    |
| Fujitsu Siemens         | 7         | 0.2%    |
| HUAWEI                  | 6         | 0.17%   |
| HKC                     | 6         | 0.17%   |
| Hitachi                 | 5         | 0.15%   |
| Belinea                 | 5         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 19        | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 15        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 14        | 0.4%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 13        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 12        | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 11        | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 11        | 0.31%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.31%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 10        | 0.28%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 9         | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9         | 0.25%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 9         | 0.25%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 9         | 0.25%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 9         | 0.25%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 9         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.25%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 9         | 0.25%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 9         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 8         | 0.23%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 8         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 0.23%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 8         | 0.23%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7         | 0.2%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 7         | 0.2%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 7         | 0.2%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 7         | 0.2%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 0.2%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 7         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1509      | 46.45%  |
| 1366x768 (WXGA)    | 369       | 11.36%  |
| 3840x2160 (4K)     | 267       | 8.22%   |
| 2560x1440 (QHD)    | 252       | 7.76%   |
| 1920x1200 (WUXGA)  | 109       | 3.35%   |
| 2560x1600          | 96        | 2.95%   |
| 1600x900 (HD+)     | 81        | 2.49%   |
| 3440x1440          | 67        | 2.06%   |
| 1680x1050 (WSXGA+) | 51        | 1.57%   |
| 2880x1800          | 48        | 1.48%   |
| 2560x1080          | 48        | 1.48%   |
| 1440x900 (WXGA+)   | 47        | 1.45%   |
| 1280x1024 (SXGA)   | 46        | 1.42%   |
| 1280x800 (WXGA)    | 45        | 1.39%   |
| 3840x2400          | 19        | 0.58%   |
| 2160x1440          | 18        | 0.55%   |
| 1360x768           | 17        | 0.52%   |
| 2256x1504          | 15        | 0.46%   |
| 3840x1080          | 12        | 0.37%   |
| 2736x1824          | 11        | 0.34%   |
| 2288x1287          | 10        | 0.31%   |
| 2880x1620          | 9         | 0.28%   |
| 1920x1280          | 9         | 0.28%   |
| 3200x2000          | 7         | 0.22%   |
| 2240x1400          | 7         | 0.22%   |
| 2520x1680          | 6         | 0.18%   |
| 1920x540           | 6         | 0.18%   |
| 3840x1600          | 5         | 0.15%   |
| 3200x1800 (QHD+)   | 5         | 0.15%   |
| 2160x1350          | 5         | 0.15%   |
| 3456x2160          | 4         | 0.12%   |
| 3072x1920          | 4         | 0.12%   |
| 3000x2000          | 4         | 0.12%   |
| 2048x1152          | 4         | 0.12%   |
| 1024x768 (XGA)     | 4         | 0.12%   |
| Unknown            | 4         | 0.12%   |
| 2880x1920          | 3         | 0.09%   |
| 2400x1600          | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 800x1280           | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 812       | 23.55%  |
| 13      | 394       | 11.43%  |
| 14      | 384       | 11.14%  |
| 27      | 351       | 10.18%  |
| 24      | 242       | 7.02%   |
| 23      | 184       | 5.34%   |
| 21      | 163       | 4.73%   |
| 34      | 104       | 3.02%   |
| 31      | 104       | 3.02%   |
| 17      | 95        | 2.76%   |
| 16      | 90        | 2.61%   |
| 12      | 61        | 1.77%   |
| 19      | 50        | 1.45%   |
| 20      | 46        | 1.33%   |
| 18      | 38        | 1.1%    |
| 22      | 37        | 1.07%   |
| Unknown | 28        | 0.81%   |
| 84      | 27        | 0.78%   |
| 11      | 24        | 0.7%    |
| 72      | 21        | 0.61%   |
| 32      | 20        | 0.58%   |
| 54      | 18        | 0.52%   |
| 28      | 17        | 0.49%   |
| 40      | 15        | 0.44%   |
| 48      | 12        | 0.35%   |
| 26      | 12        | 0.35%   |
| 25      | 11        | 0.32%   |
| 142     | 10        | 0.29%   |
| 10      | 10        | 0.29%   |
| 52      | 7         | 0.2%    |
| 49      | 6         | 0.17%   |
| 35      | 6         | 0.17%   |
| 65      | 5         | 0.15%   |
| 42      | 5         | 0.15%   |
| 37      | 5         | 0.15%   |
| 33      | 4         | 0.12%   |
| 29      | 4         | 0.12%   |
| 38      | 3         | 0.09%   |
| 7       | 3         | 0.09%   |
| 86      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1422      | 42.17%  |
| 501-600        | 697       | 20.67%  |
| 201-300        | 333       | 9.88%   |
| 401-500        | 296       | 8.78%   |
| 601-700        | 170       | 5.04%   |
| 351-400        | 138       | 4.09%   |
| 701-800        | 129       | 3.83%   |
| 1001-1500      | 55        | 1.63%   |
| 1501-2000      | 51        | 1.51%   |
| 801-900        | 32        | 0.95%   |
| Unknown        | 28        | 0.83%   |
| More than 2000 | 10        | 0.3%    |
| 901-1000       | 8         | 0.24%   |
| 1-100          | 2         | 0.06%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2271      | 74.8%   |
| 16/10   | 465       | 15.32%  |
| 21/9    | 120       | 3.95%   |
| 3/2     | 74        | 2.44%   |
| 5/4     | 40        | 1.32%   |
| 32/9    | 15        | 0.49%   |
| 4/3     | 14        | 0.46%   |
| 1.00    | 11        | 0.36%   |
| Unknown | 10        | 0.33%   |
| 6/5     | 6         | 0.2%    |
| 0.56    | 4         | 0.13%   |
| 3.40    | 2         | 0.07%   |
| 0.67    | 2         | 0.07%   |
| 2.12    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 820       | 23.98%  |
| 81-90          | 604       | 17.66%  |
| 201-250        | 479       | 14.01%  |
| 301-350        | 360       | 10.53%  |
| 351-500        | 249       | 7.28%   |
| 71-80          | 168       | 4.91%   |
| 151-200        | 149       | 4.36%   |
| More than 1000 | 104       | 3.04%   |
| 251-300        | 99        | 2.89%   |
| 121-130        | 79        | 2.31%   |
| 111-120        | 78        | 2.28%   |
| 61-70          | 50        | 1.46%   |
| 501-1000       | 48        | 1.4%    |
| 141-150        | 45        | 1.32%   |
| 51-60          | 28        | 0.82%   |
| Unknown        | 28        | 0.82%   |
| 91-100         | 17        | 0.5%    |
| 41-50          | 8         | 0.23%   |
| 131-140        | 4         | 0.12%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1059      | 31.99%  |
| 51-100        | 905       | 27.34%  |
| 101-120       | 708       | 21.39%  |
| 161-240       | 407       | 12.3%   |
| More than 240 | 127       | 3.84%   |
| 1-50          | 76        | 2.3%    |
| Unknown       | 28        | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2230      | 74.58%  |
| 2     | 578       | 19.33%  |
| 0     | 107       | 3.58%   |
| 3     | 68        | 2.27%   |
| 4     | 6         | 0.2%    |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1603      | 36.69%  |
| Realtek Semiconductor           | 1527      | 34.95%  |
| Qualcomm Atheros                | 270       | 6.18%   |
| Broadcom                        | 245       | 5.61%   |
| MediaTek                        | 195       | 4.46%   |
| TP-Link                         | 54        | 1.24%   |
| ASIX Electronics                | 42        | 0.96%   |
| Broadcom Limited                | 39        | 0.89%   |
| Ralink Technology               | 31        | 0.71%   |
| Samsung Electronics             | 28        | 0.64%   |
| Ralink                          | 25        | 0.57%   |
| Qualcomm                        | 25        | 0.57%   |
| Microsoft                       | 23        | 0.53%   |
| Lenovo                          | 22        | 0.5%    |
| Marvell Technology Group        | 20        | 0.46%   |
| Xiaomi                          | 18        | 0.41%   |
| DisplayLink                     | 17        | 0.39%   |
| Aquantia                        | 16        | 0.37%   |
| Google                          | 14        | 0.32%   |
| Nvidia                          | 12        | 0.27%   |
| Sierra Wireless                 | 11        | 0.25%   |
| NetGear                         | 9         | 0.21%   |
| Dell                            | 9         | 0.21%   |
| Qualcomm Atheros Communications | 8         | 0.18%   |
| OPPO Electronics                | 8         | 0.18%   |
| Hewlett-Packard                 | 8         | 0.18%   |
| D-Link                          | 8         | 0.18%   |
| ASUSTek Computer                | 7         | 0.16%   |
| Mellanox Technologies           | 6         | 0.14%   |
| Huawei Technologies             | 5         | 0.11%   |
| Motorola PCS                    | 3         | 0.07%   |
| JMicron Technology              | 3         | 0.07%   |
| ICS Advent                      | 3         | 0.07%   |
| D-Link System                   | 3         | 0.07%   |
| Apple                           | 3         | 0.07%   |
| ZyDAS                           | 2         | 0.05%   |
| Wilocity                        | 2         | 0.05%   |
| VIA Technologies                | 2         | 0.05%   |
| U-Blox                          | 2         | 0.05%   |
| STMicroelectronics              | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 971       | 18.76%  |
| Intel Wi-Fi 6 AX200                                               | 189       | 3.65%   |
| Intel Wi-Fi 6 AX201                                               | 150       | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 132       | 2.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 125       | 2.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 119       | 2.3%    |
| Intel Wireless 8265 / 8275                                        | 111       | 2.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 85        | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 82        | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 80        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 75        | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 73        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 69        | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 66        | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 61        | 1.18%   |
| Intel Wireless 7265                                               | 57        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 51        | 0.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 49        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 48        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 48        | 0.93%   |
| Intel Wireless 8260                                               | 46        | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 45        | 0.87%   |
| Intel Wireless 7260                                               | 44        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 40        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 39        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 39        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 36        | 0.7%    |
| Intel Wireless 3165                                               | 33        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 32        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                              | 32        | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                     | 31        | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 30        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 27        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1342      | 51.4%   |
| Realtek Semiconductor                 | 404       | 15.47%  |
| Qualcomm Atheros                      | 222       | 8.5%    |
| Broadcom                              | 197       | 7.55%   |
| MediaTek                              | 192       | 7.35%   |
| TP-Link                               | 51        | 1.95%   |
| Broadcom Limited                      | 32        | 1.23%   |
| Ralink Technology                     | 31        | 1.19%   |
| Ralink                                | 25        | 0.96%   |
| Microsoft                             | 19        | 0.73%   |
| Qualcomm                              | 18        | 0.69%   |
| Sierra Wireless                       | 11        | 0.42%   |
| NetGear                               | 9         | 0.34%   |
| Qualcomm Atheros Communications       | 8         | 0.31%   |
| Marvell Technology Group              | 7         | 0.27%   |
| Dell                                  | 7         | 0.27%   |
| ASUSTek Computer                      | 7         | 0.27%   |
| D-Link                                | 5         | 0.19%   |
| ZyDAS                                 | 2         | 0.08%   |
| Wilocity                              | 2         | 0.08%   |
| Edimax Technology                     | 2         | 0.08%   |
| D-Link System                         | 2         | 0.08%   |
| Belkin Components                     | 2         | 0.08%   |
| AVM                                   | 2         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.08%   |
| Wacom                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Quectel Wireless Solutions            | 1         | 0.04%   |
| Qualcomm Technologies                 | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Fibocom                               | 1         | 0.04%   |
| Unknown                               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 189       | 7.2%    |
| Intel Wi-Fi 6 AX201                                                  | 150       | 5.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 119       | 4.54%   |
| Intel Wireless 8265 / 8275                                           | 111       | 4.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 85        | 3.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 81        | 3.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 80        | 3.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 73        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 69        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 61        | 2.32%   |
| Intel Wireless 7265                                                  | 57        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 51        | 1.94%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 49        | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 48        | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 48        | 1.83%   |
| Intel Wireless 8260                                                  | 46        | 1.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 45        | 1.71%   |
| Intel Wireless 7260                                                  | 44        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 44        | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 42        | 1.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 40        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 39        | 1.49%   |
| Intel Wireless 3165                                                  | 33        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 32        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                        | 31        | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 30        | 1.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 27        | 1.03%   |
| Intel Wireless-AC 9260                                               | 26        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 25        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 25        | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 24        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 23        | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 22        | 0.84%   |
| Realtek 802.11ac NIC                                                 | 21        | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 21        | 0.8%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 21        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 19        | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 0.65%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 15        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 14        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1330      | 54.22%  |
| Intel                                  | 714       | 29.11%  |
| Broadcom                               | 95        | 3.87%   |
| Qualcomm Atheros                       | 66        | 2.69%   |
| ASIX Electronics                       | 42        | 1.71%   |
| Samsung Electronics                    | 23        | 0.94%   |
| Lenovo                                 | 21        | 0.86%   |
| Xiaomi                                 | 18        | 0.73%   |
| DisplayLink                            | 17        | 0.69%   |
| Aquantia                               | 16        | 0.65%   |
| Google                                 | 14        | 0.57%   |
| Marvell Technology Group               | 13        | 0.53%   |
| Nvidia                                 | 12        | 0.49%   |
| OPPO Electronics                       | 8         | 0.33%   |
| Qualcomm                               | 7         | 0.29%   |
| Broadcom Limited                       | 7         | 0.29%   |
| Mellanox Technologies                  | 5         | 0.2%    |
| Hewlett-Packard                        | 5         | 0.2%    |
| Microsoft                              | 4         | 0.16%   |
| Huawei Technologies                    | 4         | 0.16%   |
| TP-Link                                | 3         | 0.12%   |
| MediaTek                               | 3         | 0.12%   |
| JMicron Technology                     | 3         | 0.12%   |
| ICS Advent                             | 3         | 0.12%   |
| D-Link                                 | 3         | 0.12%   |
| Apple                                  | 3         | 0.12%   |
| VIA Technologies                       | 2         | 0.08%   |
| 3Com                                   | 2         | 0.08%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| IBM                                    | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Dell                                   | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 971       | 38.56%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 132       | 5.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 125       | 4.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 3.02%   |
| Intel Ethernet Controller I225-V                                  | 75        | 2.98%   |
| Intel I211 Gigabit Network Connection                             | 66        | 2.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 39        | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 36        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 32        | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.79%   |
| Intel Ethernet Connection (16) I219-V                             | 19        | 0.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 17        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                            | 11        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                             | 11        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 10        | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.4%    |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.4%    |
| Google Pixel 7 Pro                                                | 9         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2490      | 51.91%  |
| Ethernet | 2273      | 47.38%  |
| Modem    | 24        | 0.5%    |
| Unknown  | 10        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1948      | 63.21%  |
| Ethernet | 1134      | 36.79%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1533      | 51.91%  |
| 1     | 1275      | 43.18%  |
| 3     | 70        | 2.37%   |
| 0     | 55        | 1.86%   |
| 4     | 16        | 0.54%   |
| 6     | 2         | 0.07%   |
| 5     | 2         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2056      | 68.88%  |
| Yes  | 929       | 31.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1198      | 53.63%  |
| Realtek Semiconductor           | 250       | 11.19%  |
| Foxconn / Hon Hai               | 112       | 5.01%   |
| Qualcomm Atheros Communications | 111       | 4.97%   |
| IMC Networks                    | 97        | 4.34%   |
| Apple                           | 94        | 4.21%   |
| Broadcom                        | 75        | 3.36%   |
| Cambridge Silicon Radio         | 70        | 3.13%   |
| MediaTek                        | 46        | 2.06%   |
| Lite-On Technology              | 46        | 2.06%   |
| ASUSTek Computer                | 22        | 0.98%   |
| Realtek                         | 21        | 0.94%   |
| TP-Link                         | 12        | 0.54%   |
| Dell                            | 12        | 0.54%   |
| USI                             | 11        | 0.49%   |
| Toshiba                         | 8         | 0.36%   |
| Hewlett-Packard                 | 8         | 0.36%   |
| Marvell Semiconductor           | 7         | 0.31%   |
| Ralink                          | 6         | 0.27%   |
| Opticis                         | 6         | 0.27%   |
| Foxconn International           | 5         | 0.22%   |
| Dynex                           | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| Unknown                         | 2         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Syntek                          | 1         | 0.04%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Mobile Action Technology        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link                          | 1         | 0.04%   |
| AVM                             | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 441       | 19.72%  |
| Intel Bluetooth wireless interface                  | 271       | 12.12%  |
| Realtek Bluetooth Radio                             | 206       | 9.21%   |
| Intel AX200 Bluetooth                               | 182       | 8.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 139       | 6.22%   |
| Intel AX210 Bluetooth                               | 77        | 3.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 70        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 64        | 2.86%   |
| IMC Networks Wireless_Device                        | 53        | 2.37%   |
| MediaTek Wireless_Device                            | 46        | 2.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 40        | 1.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 39        | 1.74%   |
| Apple Bluetooth Host Controller                     | 39        | 1.74%   |
| Apple Bluetooth USB Host Controller                 | 37        | 1.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 1.43%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.16%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 1.12%   |
| Realtek Bluetooth Radio                             | 21        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 0.81%   |
| IMC Networks Bluetooth Device                       | 14        | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 14        | 0.63%   |
| TP-Link UB500 Adapter                               | 12        | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.54%   |
| USI Bluetooth Device                                | 11        | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.49%   |
| Lite-On Wireless_Device                             | 11        | 0.49%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 11        | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.45%   |
| ASUS Bluetooth Device                               | 10        | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.4%    |
| Lite-On Bluetooth Device                            | 8         | 0.36%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.31%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.31%   |
| Broadcom BCM20702A0                                 | 7         | 0.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.31%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.31%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1950      | 45.45%  |
| AMD                                          | 1016      | 23.68%  |
| Nvidia                                       | 678       | 15.8%   |
| C-Media Electronics                          | 88        | 2.05%   |
| Logitech                                     | 54        | 1.26%   |
| Lenovo                                       | 33        | 0.77%   |
| ASUSTek Computer                             | 30        | 0.7%    |
| Realtek Semiconductor                        | 25        | 0.58%   |
| Kingston Technology                          | 25        | 0.58%   |
| JMTek                                        | 25        | 0.58%   |
| GN Netcom                                    | 21        | 0.49%   |
| SteelSeries ApS                              | 18        | 0.42%   |
| Razer USA                                    | 18        | 0.42%   |
| Micro Star International                     | 18        | 0.42%   |
| Focusrite-Novation                           | 15        | 0.35%   |
| Creative Labs                                | 15        | 0.35%   |
| Generalplus Technology                       | 13        | 0.3%    |
| Sony                                         | 12        | 0.28%   |
| Hewlett-Packard                              | 12        | 0.28%   |
| Creative Technology                          | 12        | 0.28%   |
| Plantronics                                  | 10        | 0.23%   |
| Texas Instruments                            | 9         | 0.21%   |
| Dell                                         | 9         | 0.21%   |
| Apple                                        | 9         | 0.21%   |
| Corsair                                      | 8         | 0.19%   |
| RODE Microphones                             | 7         | 0.16%   |
| Microsoft                                    | 6         | 0.14%   |
| Audio-Technica                               | 6         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.12%   |
| Samson Technologies                          | 5         | 0.12%   |
| FIFINE Microphones                           | 5         | 0.12%   |
| Yamaha                                       | 4         | 0.09%   |
| KTMicro                                      | 4         | 0.09%   |
| JBL                                          | 4         | 0.09%   |
| DSEA A/S                                     | 4         | 0.09%   |
| BEHRINGER International                      | 4         | 0.09%   |
| XMOS                                         | 3         | 0.07%   |
| Schiit Audio                                 | 3         | 0.07%   |
| FiiO Electronics Technology                  | 3         | 0.07%   |
| Elgato Systems                               | 3         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 530       | 10.1%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 295       | 5.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 242       | 4.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 186       | 3.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 164       | 3.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 155       | 2.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 149       | 2.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 127       | 2.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 125       | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 105       | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 99        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 91        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 84        | 1.6%    |
| Nvidia Audio device                                                        | 79        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 75        | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 68        | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 65        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 61        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 61        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 61        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 60        | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                              | 60        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 57        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 57        | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 56        | 1.07%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 55        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 53        | 1.01%   |
| Intel 8 Series HD Audio Controller                                         | 53        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 53        | 1.01%   |
| Intel Broadwell-U Audio Controller                                         | 52        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 0.97%   |
| Intel Alder Lake-S HD Audio Controller                                     | 47        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 46        | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 44        | 0.84%   |
| AMD FCH Azalia Controller                                                  | 40        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 38        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 38        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 33        | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 332       | 24.87%  |
| SK hynix                     | 225       | 16.85%  |
| Micron Technology            | 169       | 12.66%  |
| Kingston                     | 123       | 9.21%   |
| Crucial                      | 91        | 6.82%   |
| Corsair                      | 82        | 6.14%   |
| Unknown                      | 60        | 4.49%   |
| G.Skill                      | 59        | 4.42%   |
| A-DATA Technology            | 29        | 2.17%   |
| Unknown                      | 29        | 2.17%   |
| Ramaxel Technology           | 21        | 1.57%   |
| Smart                        | 12        | 0.9%    |
| Team                         | 9         | 0.67%   |
| Elpida                       | 9         | 0.67%   |
| Unknown (ABCD)               | 7         | 0.52%   |
| Teikon                       | 6         | 0.45%   |
| Patriot                      | 5         | 0.37%   |
| Nanya Technology             | 5         | 0.37%   |
| Apacer                       | 5         | 0.37%   |
| Transcend                    | 4         | 0.3%    |
| Timetec                      | 4         | 0.3%    |
| V-GeN                        | 3         | 0.22%   |
| Lexar                        | 3         | 0.22%   |
| GOODRAM                      | 3         | 0.22%   |
| 4ea5                         | 3         | 0.22%   |
| Silicon Power                | 2         | 0.15%   |
| Qumo                         | 2         | 0.15%   |
| PNY                          | 2         | 0.15%   |
| ff                           | 2         | 0.15%   |
| CSX                          | 2         | 0.15%   |
| AMD                          | 2         | 0.15%   |
| Unknown (8A02)               | 1         | 0.07%   |
| Unknown (0x5846)             | 1         | 0.07%   |
| Unknown (0x0E9D)             | 1         | 0.07%   |
| Unknown (0x0CDC)             | 1         | 0.07%   |
| Unknown (0x0B5E)             | 1         | 0.07%   |
| Smart Brazil                 | 1         | 0.07%   |
| Sesame                       | 1         | 0.07%   |
| PUSKILL                      | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 29        | 2.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.79%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.79%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 10        | 0.72%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.5%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 0.5%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 7         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.43%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.43%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 6         | 0.43%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 6         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.36%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.36%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.36%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.36%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.36%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 630       | 54.88%  |
| DDR3    | 210       | 18.29%  |
| DDR5    | 90        | 7.84%   |
| LPDDR5  | 71        | 6.18%   |
| LPDDR4  | 59        | 5.14%   |
| LPDDR3  | 43        | 3.75%   |
| DDR2    | 15        | 1.31%   |
| Unknown | 14        | 1.22%   |
| SDRAM   | 9         | 0.78%   |
| DRAM    | 5         | 0.44%   |
| DDR     | 2         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 643       | 55.67%  |
| DIMM         | 313       | 27.1%   |
| Row Of Chips | 182       | 15.76%  |
| Unknown      | 10        | 0.87%   |
| Chip         | 6         | 0.52%   |
| RIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 517       | 41.96%  |
| 16384 | 277       | 22.48%  |
| 4096  | 249       | 20.21%  |
| 2048  | 91        | 7.39%   |
| 32768 | 79        | 6.41%   |
| 1024  | 17        | 1.38%   |
| 49152 | 1         | 0.08%   |
| 3072  | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 319       | 26.02%  |
| 2667    | 153       | 12.48%  |
| 1600    | 143       | 11.66%  |
| 6400    | 73        | 5.95%   |
| 2400    | 70        | 5.71%   |
| 4800    | 59        | 4.81%   |
| 2133    | 56        | 4.57%   |
| 3600    | 41        | 3.34%   |
| 1333    | 38        | 3.1%    |
| 4267    | 32        | 2.61%   |
| 1867    | 27        | 2.2%    |
| 1334    | 18        | 1.47%   |
| 5600    | 15        | 1.22%   |
| 3400    | 13        | 1.06%   |
| 3733    | 12        | 0.98%   |
| 1067    | 12        | 0.98%   |
| 3266    | 10        | 0.82%   |
| 667     | 10        | 0.82%   |
| Unknown | 9         | 0.73%   |
| 4266    | 8         | 0.65%   |
| 800     | 8         | 0.65%   |
| 3534    | 7         | 0.57%   |
| 6000    | 6         | 0.49%   |
| 3800    | 6         | 0.49%   |
| 3000    | 6         | 0.49%   |
| 1800    | 6         | 0.49%   |
| 1866    | 5         | 0.41%   |
| 3866    | 4         | 0.33%   |
| 3666    | 4         | 0.33%   |
| 2933    | 4         | 0.33%   |
| 2800    | 4         | 0.33%   |
| 2666    | 4         | 0.33%   |
| 8400    | 3         | 0.24%   |
| 7467    | 3         | 0.24%   |
| 2733    | 3         | 0.24%   |
| 2048    | 3         | 0.24%   |
| 5800    | 2         | 0.16%   |
| 5500    | 2         | 0.16%   |
| 5200    | 2         | 0.16%   |
| 3466    | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 18        | 45%     |
| Seiko Epson                   | 6         | 15%     |
| Brother Industries            | 5         | 12.5%   |
| Dymo-CoStar                   | 3         | 7.5%    |
| Canon                         | 3         | 7.5%    |
| Samsung Electronics           | 2         | 5%      |
| STMicroelectronics            | 1         | 2.5%    |
| Samsung Info. Systems America | 1         | 2.5%    |
| Pantum                        | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1102                                                     | 3         | 7.5%    |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 5%      |
| HP LaserJet 1010                                                      | 2         | 5%      |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 5%      |
| STMicroelectronics USB Printing Support                               | 1         | 2.5%    |
| Seiko Epson WF-2860 Series                                            | 1         | 2.5%    |
| Seiko Epson L3150 Series                                              | 1         | 2.5%    |
| Seiko Epson L120 Series                                               | 1         | 2.5%    |
| Seiko Epson AL-M310DN                                                 | 1         | 2.5%    |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 2.5%    |
| Samsung ML-216x Series Laser Printer                                  | 1         | 2.5%    |
| Samsung M2070 Series                                                  | 1         | 2.5%    |
| Pantum M6500W-series                                                  | 1         | 2.5%    |
| HP LaserJet Professional P1102w                                       | 1         | 2.5%    |
| HP LaserJet Pro M148-M149                                             | 1         | 2.5%    |
| HP LaserJet 1020                                                      | 1         | 2.5%    |
| HP Ink Tank 310 series                                                | 1         | 2.5%    |
| HP ENVY Photo 7800 series                                             | 1         | 2.5%    |
| HP ENVY Inspire 7200 series                                           | 1         | 2.5%    |
| HP ENVY 5000 series                                                   | 1         | 2.5%    |
| HP DeskJet 5650c                                                      | 1         | 2.5%    |
| HP DeskJet 3700 series                                                | 1         | 2.5%    |
| HP DeskJet 35xx                                                       | 1         | 2.5%    |
| HP DeskJet 2700 series                                                | 1         | 2.5%    |
| HP DeskJet 2600 series                                                | 1         | 2.5%    |
| HP Deskjet 2050 J510                                                  | 1         | 2.5%    |
| Dymo-CoStar LabelWriter 400                                           | 1         | 2.5%    |
| Canon TR4500 series                                                   | 1         | 2.5%    |
| Canon PIXMA MP250                                                     | 1         | 2.5%    |
| Canon MF3010                                                          | 1         | 2.5%    |
| Brother HL-L2390DW                                                    | 1         | 2.5%    |
| Brother HL-2130 series                                                | 1         | 2.5%    |
| Brother HL-1440 Laser Printer                                         | 1         | 2.5%    |
| Brother DCP-L3550CDW                                                  | 1         | 2.5%    |
| Brother DCP-1600                                                      | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 8         | 72.73%  |
| Seiko Epson | 3         | 27.27%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                       | 4         | 36.36%  |
| Seiko Epson Scanner                           | 1         | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]         | 1         | 9.09%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 9.09%   |
| Canon CanoScan LiDE 700F                      | 1         | 9.09%   |
| Canon CanoScan LiDE 220                       | 1         | 9.09%   |
| Canon CanoScan LiDE 110                       | 1         | 9.09%   |
| Canon CanoScan 4400F                          | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 342       | 17.21%  |
| IMC Networks                           | 225       | 11.32%  |
| Microdia                               | 152       | 7.65%   |
| Bison Electronics                      | 150       | 7.55%   |
| Logitech                               | 145       | 7.3%    |
| Quanta                                 | 134       | 6.74%   |
| Realtek Semiconductor                  | 129       | 6.49%   |
| Sunplus Innovation Technology          | 95        | 4.78%   |
| Apple                                  | 94        | 4.73%   |
| Cheng Uei Precision Industry (Foxlink) | 68        | 3.42%   |
| Syntek                                 | 54        | 2.72%   |
| Luxvisions Innotech Limited            | 52        | 2.62%   |
| Sonix Technology                       | 45        | 2.26%   |
| Lite-On Technology                     | 32        | 1.61%   |
| Suyin                                  | 27        | 1.36%   |
| Acer                                   | 24        | 1.21%   |
| Microsoft                              | 20        | 1.01%   |
| Silicon Motion                         | 15        | 0.75%   |
| Alcor Micro                            | 15        | 0.75%   |
| Samsung Electronics                    | 14        | 0.7%    |
| SunplusIT                              | 13        | 0.65%   |
| Shinetech                              | 10        | 0.5%    |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.4%    |
| Razer USA                              | 7         | 0.35%   |
| Lenovo                                 | 7         | 0.35%   |
| Ricoh                                  | 6         | 0.3%    |
| Unknown                                | 6         | 0.3%    |
| Trust                                  | 5         | 0.25%   |
| AVerMedia Technologies                 | 5         | 0.25%   |
| ARC International                      | 5         | 0.25%   |
| MacroSilicon                           | 4         | 0.2%    |
| Importek                               | 4         | 0.2%    |
| Generalplus Technology                 | 4         | 0.2%    |
| Creality 3D Technology                 | 4         | 0.2%    |
| Z-Star Microelectronics                | 3         | 0.15%   |
| Primax Electronics                     | 3         | 0.15%   |
| Jieli Technology                       | 3         | 0.15%   |
| Google                                 | 3         | 0.15%   |
| Cubeternet                             | 3         | 0.15%   |
| Creative Technology                    | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 118       | 5.89%   |
| IMC Networks Integrated Camera                      | 87        | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 83        | 4.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 73        | 3.65%   |
| Bison Integrated Camera                             | 67        | 3.35%   |
| Realtek Integrated_Webcam_HD                        | 61        | 3.05%   |
| Syntek Integrated Camera                            | 44        | 2.2%    |
| Sunplus Integrated_Webcam_HD                        | 33        | 1.65%   |
| Apple iPhone 5/5C/5S/6/SE                           | 30        | 1.5%    |
| Logitech Webcam C270                                | 26        | 1.3%    |
| Apple FaceTime HD Camera                            | 25        | 1.25%   |
| Quanta HD User Facing                               | 24        | 1.2%    |
| Sonix USB2.0 FHD UVC WebCam                         | 23        | 1.15%   |
| Chicony HD WebCam                                   | 23        | 1.15%   |
| Quanta HP Wide Vision HD Camera                     | 21        | 1.05%   |
| Sonix USB2.0 HD UVC WebCam                          | 20        | 1%      |
| Logitech HD Pro Webcam C920                         | 20        | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 0.9%    |
| Apple FaceTime HD Camera (Built-in)                 | 18        | 0.9%    |
| Lite-On Integrated Camera                           | 17        | 0.85%   |
| Bison HD Webcam                                     | 17        | 0.85%   |
| Chicony Integrated Camera (1280x720@30)             | 16        | 0.8%    |
| Quanta HP HD Camera                                 | 15        | 0.75%   |
| Chicony HP HD Camera                                | 15        | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)             | 14        | 0.7%    |
| Chicony HP TrueVision HD Camera                     | 14        | 0.7%    |
| Bison Integrated RGB Camera                         | 14        | 0.7%    |
| Apple Built-in iSight                               | 14        | 0.7%    |
| Microdia Integrated_Webcam_FHD                      | 13        | 0.65%   |
| Logitech C920 PRO HD Webcam                         | 13        | 0.65%   |
| IMC Networks HD Camera                              | 13        | 0.65%   |
| Quanta ACER HD User Facing                          | 12        | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.6%    |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.6%    |
| Chicony HP Wide Vision HD Camera                    | 12        | 0.6%    |
| Chicony HD User Facing                              | 12        | 0.6%    |
| Realtek USB Camera                                  | 11        | 0.55%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 11        | 0.55%   |
| Luxvisions Innotech Limited Integrated Camera       | 11        | 0.55%   |
| Chicony Integrated IR Camera                        | 11        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 145       | 33.49%  |
| Shenzhen Goodix Technology         | 101       | 23.33%  |
| Validity Sensors                   | 89        | 20.55%  |
| Elan Microelectronics              | 37        | 8.55%   |
| Realtek USB2.0 Finger Print Bridge | 15        | 3.46%   |
| Upek                               | 14        | 3.23%   |
| LighTuning Technology              | 12        | 2.77%   |
| AuthenTec                          | 11        | 2.54%   |
| Samsung Electronics                | 7         | 1.62%   |
| STMicroelectronics                 | 1         | 0.23%   |
| Focal-systems.Corp                 | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 66        | 15.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 9.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 6%      |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 5.08%   |
| Elan ELAN:ARM-M4                                                           | 22        | 5.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.16%   |
| Validity Sensors Synaptics WBDI                                            | 18        | 4.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 3.7%    |
| Synaptics WBDI                                                             | 16        | 3.7%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 15        | 3.46%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 3%      |
| Elan ELAN:Fingerprint                                                      | 13        | 3%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 2.77%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.31%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.08%   |
| Synaptics UWP WBDI                                                         | 8         | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.62%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.62%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 6         | 1.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.39%   |
| Validity Sensors VFS491                                                    | 5         | 1.15%   |
| Synaptics  WBDI                                                            | 5         | 1.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 0.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 0.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.92%   |
| Synaptics TouchPad                                                         | 3         | 0.69%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.46%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.46%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.46%   |
| AuthenTec AES2810                                                          | 2         | 0.46%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.46%   |
| AuthenTec AES1600                                                          | 2         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 81        | 52.94%  |
| Alcor Micro                       | 42        | 27.45%  |
| Upek                              | 6         | 3.92%   |
| Lenovo                            | 5         | 3.27%   |
| Gemalto (was Gemplus)             | 4         | 2.61%   |
| O2 Micro                          | 3         | 1.96%   |
| Yubico.com                        | 2         | 1.31%   |
| Realtek Semiconductor             | 2         | 1.31%   |
| Bit4id                            | 2         | 1.31%   |
| Aladdin Knowledge Systems         | 2         | 1.31%   |
| VASCO Data Security International | 1         | 0.65%   |
| Reiner SCT Kartensysteme          | 1         | 0.65%   |
| Cherry                            | 1         | 0.65%   |
| Advanced Card Systems             | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 27.45%  |
| Broadcom 58200                                                               | 37        | 24.18%  |
| Broadcom 5880                                                                | 19        | 12.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 9.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.19%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.92%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.27%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.31%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.31%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.31%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.31%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.31%   |
| Bit4id miniLector EVO                                                        | 2         | 1.31%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.31%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.65%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1946      | 65.17%  |
| 1     | 845       | 28.3%   |
| 2     | 163       | 5.46%   |
| 3     | 24        | 0.8%    |
| 6     | 3         | 0.1%    |
| 4     | 3         | 0.1%    |
| 8     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 426       | 34.49%  |
| Graphics card            | 310       | 25.1%   |
| Multimedia controller    | 177       | 14.33%  |
| Net/wireless             | 137       | 11.09%  |
| Camera                   | 33        | 2.67%   |
| Chipcard                 | 27        | 2.19%   |
| Sound                    | 21        | 1.7%    |
| Bluetooth                | 21        | 1.7%    |
| Unassigned class         | 19        | 1.54%   |
| Communication controller | 17        | 1.38%   |
| Storage                  | 13        | 1.05%   |
| Card reader              | 12        | 0.97%   |
| Net/ethernet             | 9         | 0.73%   |
| Network                  | 4         | 0.32%   |
| Modem                    | 3         | 0.24%   |
| Firewire controller      | 2         | 0.16%   |
| Storage/raid             | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Dvb card                 | 1         | 0.08%   |

