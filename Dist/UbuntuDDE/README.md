UbuntuDDE - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for UbuntuDDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/UbuntuDDE/Desktop/README.md) and [notebooks](/Dist/UbuntuDDE/Notebook/README.md).

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

Total: 121

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [65a009e9dd](https://linux-hardware.org/?probe=65a009e9dd) | Apr 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [7fe3f11f56](https://linux-hardware.org/?probe=7fe3f11f56) | Dec 22, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [7153762b68](https://linux-hardware.org/?probe=7153762b68) | Nov 23, 2022 |
| Dell          | Latitude E6430              | Notebook    | [60832751d1](https://linux-hardware.org/?probe=60832751d1) | Nov 16, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [d5d3ad3491](https://linux-hardware.org/?probe=d5d3ad3491) | Oct 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| ECS           | Nettle2                     | Desktop     | [7de5975b89](https://linux-hardware.org/?probe=7de5975b89) | Mar 20, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| ECS           | Nettle2                     | Desktop     | [cd98e7180c](https://linux-hardware.org/?probe=cd98e7180c) | Feb 12, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Framework     | Laptop                      | Notebook    | [081416685c](https://linux-hardware.org/?probe=081416685c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Google        | Banon                       | Notebook    | [a6febddf28](https://linux-hardware.org/?probe=a6febddf28) | Jan 06, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [71958172cf](https://linux-hardware.org/?probe=71958172cf) | Oct 08, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [661937dcfa](https://linux-hardware.org/?probe=661937dcfa) | Sep 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [a950c391ee](https://linux-hardware.org/?probe=a950c391ee) | Sep 12, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| Acer          | F672CR R01-B1               | Desktop     | [652ed79c86](https://linux-hardware.org/?probe=652ed79c86) | May 29, 2021 |
| MSI           | GS60 2QE                    | Notebook    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| MSI           | GS60 2QE                    | Notebook    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| Acer          | F672CR R01-B1               | Desktop     | [bd8067c8cf](https://linux-hardware.org/?probe=bd8067c8cf) | May 16, 2021 |
| Acer          | Predator PH317-52           | Notebook    | [5737732bb0](https://linux-hardware.org/?probe=5737732bb0) | May 15, 2021 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [1c51e0899d](https://linux-hardware.org/?probe=1c51e0899d) | Apr 06, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [d03bb12703](https://linux-hardware.org/?probe=d03bb12703) | Apr 06, 2021 |
| MSI           | G41M-S01                    | Desktop     | [fae5d5a101](https://linux-hardware.org/?probe=fae5d5a101) | Mar 31, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| MSI           | G41M-P26                    | Desktop     | [2b503c1c1d](https://linux-hardware.org/?probe=2b503c1c1d) | Jan 07, 2021 |
| Dell          | Latitude E6320              | Notebook    | [8e7c6ced02](https://linux-hardware.org/?probe=8e7c6ced02) | Dec 15, 2020 |
| BESSTAR Te... | VB9                         | All in one  | [c6c030bd9f](https://linux-hardware.org/?probe=c6c030bd9f) | Nov 28, 2020 |
| BANGHO        | MZBSWAP-00                  | Desktop     | [c0b3c1bae1](https://linux-hardware.org/?probe=c0b3c1bae1) | Nov 13, 2020 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [51733fd6ab](https://linux-hardware.org/?probe=51733fd6ab) | Nov 02, 2020 |
| MSI           | Z87-G43                     | Desktop     | [055e733f90](https://linux-hardware.org/?probe=055e733f90) | Nov 01, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8f5f5aba10](https://linux-hardware.org/?probe=8f5f5aba10) | Oct 31, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e070ae2fd4](https://linux-hardware.org/?probe=e070ae2fd4) | Oct 19, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [5e81f45485](https://linux-hardware.org/?probe=5e81f45485) | Oct 09, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [83adab7085](https://linux-hardware.org/?probe=83adab7085) | Oct 08, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [ae5665efc4](https://linux-hardware.org/?probe=ae5665efc4) | Oct 02, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [a316ca39ef](https://linux-hardware.org/?probe=a316ca39ef) | Sep 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1865dce38e](https://linux-hardware.org/?probe=1865dce38e) | Sep 24, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [006c313ab9](https://linux-hardware.org/?probe=006c313ab9) | Sep 13, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [8abc37bdcc](https://linux-hardware.org/?probe=8abc37bdcc) | Sep 06, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [ae07f658e9](https://linux-hardware.org/?probe=ae07f658e9) | Sep 04, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5779a0397d](https://linux-hardware.org/?probe=5779a0397d) | Aug 26, 2020 |
| HP            | Pavilion dm4                | Notebook    | [7ab3fbd60d](https://linux-hardware.org/?probe=7ab3fbd60d) | Aug 26, 2020 |
| HP            | Pavilion dm4                | Notebook    | [f3f1ea6d44](https://linux-hardware.org/?probe=f3f1ea6d44) | Aug 26, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [b7c774660b](https://linux-hardware.org/?probe=b7c774660b) | Aug 23, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [08bdddfbb1](https://linux-hardware.org/?probe=08bdddfbb1) | Aug 23, 2020 |
| Dell          | System XPS L502X            | Notebook    | [caa5473285](https://linux-hardware.org/?probe=caa5473285) | Aug 13, 2020 |
| Lenovo        | G480 20150                  | Notebook    | [4531dd50a5](https://linux-hardware.org/?probe=4531dd50a5) | Aug 11, 2020 |
| Lenovo        | G480 20150                  | Notebook    | [8e51b2cb2d](https://linux-hardware.org/?probe=8e51b2cb2d) | Aug 11, 2020 |
| Dell          | System XPS L502X            | Notebook    | [019fc71c57](https://linux-hardware.org/?probe=019fc71c57) | Aug 05, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [4cb4390fa3](https://linux-hardware.org/?probe=4cb4390fa3) | Aug 01, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [e273444401](https://linux-hardware.org/?probe=e273444401) | Aug 01, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [19876e9920](https://linux-hardware.org/?probe=19876e9920) | Jul 25, 2020 |
| Dell          | G7 7588                     | Notebook    | [34805cf5b8](https://linux-hardware.org/?probe=34805cf5b8) | Jul 24, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | Desktop     | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| Toshiba       | Satellite S55t-B            | Notebook    | [01aa2bca69](https://linux-hardware.org/?probe=01aa2bca69) | Jun 28, 2020 |
| Toshiba       | Satellite S55t-B            | Notebook    | [71ae60ebc0](https://linux-hardware.org/?probe=71ae60ebc0) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [2a82822b1d](https://linux-hardware.org/?probe=2a82822b1d) | Jun 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f58b08659](https://linux-hardware.org/?probe=9f58b08659) | Jun 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [75682d8cbd](https://linux-hardware.org/?probe=75682d8cbd) | Jun 23, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ffccba3844](https://linux-hardware.org/?probe=ffccba3844) | Jun 23, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [f01a10328b](https://linux-hardware.org/?probe=f01a10328b) | Jun 17, 2020 |
| HP            | Presario CQ56               | Notebook    | [211a5c9ec1](https://linux-hardware.org/?probe=211a5c9ec1) | Jun 17, 2020 |
| Intel         | B75                         | Desktop     | [cbfecb01d1](https://linux-hardware.org/?probe=cbfecb01d1) | Jun 14, 2020 |
| Acer          | Aspire V5-471               | Notebook    | [346de9f5d8](https://linux-hardware.org/?probe=346de9f5d8) | Jun 14, 2020 |
| Unknown       | Unknown                     | Notebook    | [1da538b1cf](https://linux-hardware.org/?probe=1da538b1cf) | Jun 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [950be7ae19](https://linux-hardware.org/?probe=950be7ae19) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [77d17289e7](https://linux-hardware.org/?probe=77d17289e7) | May 31, 2020 |
| Dell          | 0H4VK7 A01                  | Desktop     | [0d7b561033](https://linux-hardware.org/?probe=0d7b561033) | May 24, 2020 |
| Dell          | 0H4VK7 A01                  | Desktop     | [6c8989e6c6](https://linux-hardware.org/?probe=6c8989e6c6) | May 24, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ea23c3bbdb](https://linux-hardware.org/?probe=ea23c3bbdb) | May 16, 2020 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [7ec29f824e](https://linux-hardware.org/?probe=7ec29f824e) | May 16, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [d55c3ee4b0](https://linux-hardware.org/?probe=d55c3ee4b0) | May 16, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [5a566d4992](https://linux-hardware.org/?probe=5a566d4992) | May 12, 2020 |
| HP            | 8433 11                     | Desktop     | [e302f75c67](https://linux-hardware.org/?probe=e302f75c67) | May 12, 2020 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [31b70f1160](https://linux-hardware.org/?probe=31b70f1160) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [2a1a979433](https://linux-hardware.org/?probe=2a1a979433) | May 11, 2020 |
| HP            | Pavilion 14                 | Notebook    | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [ad8e2069c8](https://linux-hardware.org/?probe=ad8e2069c8) | May 11, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [2a575bf9f0](https://linux-hardware.org/?probe=2a575bf9f0) | May 11, 2020 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [6c9138359f](https://linux-hardware.org/?probe=6c9138359f) | May 10, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [0b99805df1](https://linux-hardware.org/?probe=0b99805df1) | May 09, 2020 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [9bad08782f](https://linux-hardware.org/?probe=9bad08782f) | May 09, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [628255b107](https://linux-hardware.org/?probe=628255b107) | May 08, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6f59de9a48](https://linux-hardware.org/?probe=6f59de9a48) | May 08, 2020 |
| MSI           | G41M-P25                    | Desktop     | [e1592a090c](https://linux-hardware.org/?probe=e1592a090c) | May 08, 2020 |
| Dell          | Inspiron N7010              | Notebook    | [2568ca0355](https://linux-hardware.org/?probe=2568ca0355) | May 07, 2020 |
| HP            | 3397                        | Desktop     | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| Medion        | MS-7848                     | Desktop     | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [7580875f9d](https://linux-hardware.org/?probe=7580875f9d) | May 06, 2020 |
| HP            | 3397                        | Desktop     | [d5693de014](https://linux-hardware.org/?probe=d5693de014) | May 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [46c69aad2a](https://linux-hardware.org/?probe=46c69aad2a) | Apr 30, 2020 |
| Dell          | 0FM586                      | Desktop     | [0d813a7cc7](https://linux-hardware.org/?probe=0d813a7cc7) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [76eb877783](https://linux-hardware.org/?probe=76eb877783) | Apr 26, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [e5ec721a65](https://linux-hardware.org/?probe=e5ec721a65) | Apr 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| eMachines     | WMCP61M                     | Desktop     | [0d3017399b](https://linux-hardware.org/?probe=0d3017399b) | Apr 16, 2020 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [a877d12e85](https://linux-hardware.org/?probe=a877d12e85) | Apr 14, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [76bbb57b26](https://linux-hardware.org/?probe=76bbb57b26) | Apr 11, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [f38f6111a4](https://linux-hardware.org/?probe=f38f6111a4) | Apr 07, 2020 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [ea7a9aa4f0](https://linux-hardware.org/?probe=ea7a9aa4f0) | Mar 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ed6853b51d](https://linux-hardware.org/?probe=ed6853b51d) | Feb 28, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d33696bceb](https://linux-hardware.org/?probe=d33696bceb) | Nov 24, 2019 |
| Dell          | Latitude E5440              | Notebook    | [6c3cb81d00](https://linux-hardware.org/?probe=6c3cb81d00) | Aug 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| UbuntuDDE 20.04 | 64        | 71.11%  |
| UbuntuDDE 21.10 | 7         | 7.78%   |
| UbuntuDDE 21.04 | 6         | 6.67%   |
| UbuntuDDE 20.10 | 5         | 5.56%   |
| UbuntuDDE 18.04 | 4         | 4.44%   |
| UbuntuDDE 22.04 | 3         | 3.33%   |
| UbuntuDDE 18.10 | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 90        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-29-generic    | 18        | 19.35%  |
| 5.4.0-42-generic    | 11        | 11.83%  |
| 5.4.0-21-generic    | 6         | 6.45%   |
| 5.4.0-37-generic    | 5         | 5.38%   |
| 5.4.0-48-generic    | 4         | 4.3%    |
| 5.8.0-33-generic    | 2         | 2.15%   |
| 5.4.0-52-generic    | 2         | 2.15%   |
| 5.4.0-39-generic    | 2         | 2.15%   |
| 5.3.0-40-generic    | 2         | 2.15%   |
| 5.15.0-53-generic   | 2         | 2.15%   |
| 5.11.0-17-generic   | 2         | 2.15%   |
| 5.8.0-53-generic    | 1         | 1.08%   |
| 5.8.0-50-generic    | 1         | 1.08%   |
| 5.8.0-48-generic    | 1         | 1.08%   |
| 5.8.0-41-generic    | 1         | 1.08%   |
| 5.8.0-23-generic    | 1         | 1.08%   |
| 5.6.0-1008-oem      | 1         | 1.08%   |
| 5.4.0-96-generic    | 1         | 1.08%   |
| 5.4.0-94-generic    | 1         | 1.08%   |
| 5.4.0-88-generic    | 1         | 1.08%   |
| 5.4.0-84-generic    | 1         | 1.08%   |
| 5.4.0-70-generic    | 1         | 1.08%   |
| 5.4.0-53-generic    | 1         | 1.08%   |
| 5.4.0-45-generic    | 1         | 1.08%   |
| 5.4.0-40-lowlatency | 1         | 1.08%   |
| 5.4.0-34-generic    | 1         | 1.08%   |
| 5.4.0-33-generic    | 1         | 1.08%   |
| 5.4.0-31-generic    | 1         | 1.08%   |
| 5.4.0-26-generic    | 1         | 1.08%   |
| 5.4.0-24-generic    | 1         | 1.08%   |
| 5.19.0-38-generic   | 1         | 1.08%   |
| 5.15.0-57-generic   | 1         | 1.08%   |
| 5.15.0-50-generic   | 1         | 1.08%   |
| 5.13.0-44-generic   | 1         | 1.08%   |
| 5.13.0-39-generic   | 1         | 1.08%   |
| 5.13.0-35-generic   | 1         | 1.08%   |
| 5.13.0-30-generic   | 1         | 1.08%   |
| 5.13.0-28-generic   | 1         | 1.08%   |
| 5.13.0-23-generic   | 1         | 1.08%   |
| 5.13.0-22-generic   | 1         | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 60        | 66.67%  |
| 5.8.0   | 7         | 7.78%   |
| 5.13.0  | 7         | 7.78%   |
| 5.11.0  | 6         | 6.67%   |
| 5.15.0  | 3         | 3.33%   |
| 5.3.0   | 2         | 2.22%   |
| 4.15.0  | 2         | 2.22%   |
| 5.6.0   | 1         | 1.11%   |
| 5.19.0  | 1         | 1.11%   |
| 5.0.0   | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 66.67%  |
| 5.8     | 7         | 7.78%   |
| 5.13    | 7         | 7.78%   |
| 5.11    | 6         | 6.67%   |
| 5.15    | 3         | 3.33%   |
| 5.3     | 2         | 2.22%   |
| 4.15    | 2         | 2.22%   |
| 5.6     | 1         | 1.11%   |
| 5.19    | 1         | 1.11%   |
| 5.0     | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 90        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 90        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 87        | 96.67%  |
| Wayland | 2         | 2.22%   |
| Tty     | 1         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 62.64%  |
| LightDM | 14        | 15.38%  |
| GDM     | 11        | 12.09%  |
| TDM     | 6         | 6.59%   |
| GDM3    | 2         | 2.2%    |
| SDDM    | 1         | 1.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 31        | 34.44%  |
| pt_BR   | 10        | 11.11%  |
| es_ES   | 5         | 5.56%   |
| en_GB   | 5         | 5.56%   |
| de_DE   | 5         | 5.56%   |
| C       | 5         | 5.56%   |
| fr_FR   | 4         | 4.44%   |
| ru_RU   | 3         | 3.33%   |
| es_AR   | 3         | 3.33%   |
| it_IT   | 2         | 2.22%   |
| uk_UA   | 1         | 1.11%   |
| th_TH   | 1         | 1.11%   |
| sr_RS   | 1         | 1.11%   |
| pl_PL   | 1         | 1.11%   |
| nl_NL   | 1         | 1.11%   |
| id_ID   | 1         | 1.11%   |
| fi_FI   | 1         | 1.11%   |
| es_MX   | 1         | 1.11%   |
| es_CR   | 1         | 1.11%   |
| es_CO   | 1         | 1.11%   |
| en_ZA   | 1         | 1.11%   |
| en_IN   | 1         | 1.11%   |
| en_CA   | 1         | 1.11%   |
| en_BW   | 1         | 1.11%   |
| en_AU   | 1         | 1.11%   |
| de_CH   | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 47        | 51.65%  |
| EFI  | 44        | 48.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 81        | 90%     |
| Overlay | 4         | 4.44%   |
| Zfs     | 1         | 1.11%   |
| Tmpfs   | 1         | 1.11%   |
| Ext2    | 1         | 1.11%   |
| Btrfs   | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 67.78%  |
| GPT     | 24        | 26.67%  |
| MBR     | 5         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 84.44%  |
| Yes       | 14        | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 50.55%  |
| No        | 45        | 49.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 18.89%  |
| Hewlett-Packard     | 15        | 16.67%  |
| Dell                | 13        | 14.44%  |
| MSI                 | 7         | 7.78%   |
| Lenovo              | 7         | 7.78%   |
| Gigabyte Technology | 5         | 5.56%   |
| Acer                | 5         | 5.56%   |
| Intel               | 4         | 4.44%   |
| Toshiba             | 2         | 2.22%   |
| Apple               | 2         | 2.22%   |
| Unknown             | 2         | 2.22%   |
| Samsung Electronics | 1         | 1.11%   |
| Medion              | 1         | 1.11%   |
| HUAWEI              | 1         | 1.11%   |
| Google              | 1         | 1.11%   |
| Fujitsu Siemens     | 1         | 1.11%   |
| Framework           | 1         | 1.11%   |
| eMachines           | 1         | 1.11%   |
| ECS                 | 1         | 1.11%   |
| BESSTAR Tech        | 1         | 1.11%   |
| BANGHO              | 1         | 1.11%   |
| ASRock              | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7592                                | 3         | 3.33%   |
| Unknown                                    | 2         | 2.22%   |
| Toshiba Satellite S55t-B                   | 1         | 1.11%   |
| Toshiba Satellite C55-B                    | 1         | 1.11%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 1.11%   |
| MSI MS-7B84                                | 1         | 1.11%   |
| MSI MS-7816                                | 1         | 1.11%   |
| MSI MS-7693                                | 1         | 1.11%   |
| MSI GS60 2QE                               | 1         | 1.11%   |
| Medion MS-7848                             | 1         | 1.11%   |
| Lenovo ThinkPad X200 Tablet 7449FWG        | 1         | 1.11%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJ0017US | 1         | 1.11%   |
| Lenovo ThinkPad T430 2349DS5               | 1         | 1.11%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300       | 1         | 1.11%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 1.11%   |
| Lenovo IdeaPad 510-15IKB 80SV              | 1         | 1.11%   |
| Lenovo G480 20150                          | 1         | 1.11%   |
| Intel NUC8i7BEH                            | 1         | 1.11%   |
| Intel DQ45CB AAE30148-207                  | 1         | 1.11%   |
| Intel D33217CK G76541-302                  | 1         | 1.11%   |
| Intel B75                                  | 1         | 1.11%   |
| HUAWEI MACH-WX9                            | 1         | 1.11%   |
| HP Spectre x360 Convertible 13-aw0xxx      | 1         | 1.11%   |
| HP ProBook 650 G3                          | 1         | 1.11%   |
| HP Presario CQ56                           | 1         | 1.11%   |
| HP Pavilion dv6                            | 1         | 1.11%   |
| HP Pavilion dm4                            | 1         | 1.11%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.11%   |
| HP Pavilion 14                             | 1         | 1.11%   |
| HP OMEN by Laptop 17-cb1xxx                | 1         | 1.11%   |
| HP Notebook                                | 1         | 1.11%   |
| HP Laptop 15-dy1xxx                        | 1         | 1.11%   |
| HP Laptop 15-da0xxx                        | 1         | 1.11%   |
| HP EliteBook 2540p                         | 1         | 1.11%   |
| HP Compaq Elite 8300 SFF                   | 1         | 1.11%   |
| HP Compaq Elite 8300 MT                    | 1         | 1.11%   |
| HP 250 G4 Notebook PC                      | 1         | 1.11%   |
| Google Banon                               | 1         | 1.11%   |
| Gigabyte GB-BXi7-5500                      | 1         | 1.11%   |
| Gigabyte GA-MA74GM-S2                      | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 6         | 6.67%   |
| Lenovo ThinkPad         | 4         | 4.44%   |
| HP Pavilion             | 4         | 4.44%   |
| MSI MS-7592             | 3         | 3.33%   |
| Dell Latitude           | 3         | 3.33%   |
| Acer Aspire             | 3         | 3.33%   |
| Toshiba Satellite       | 2         | 2.22%   |
| Lenovo IdeaPad          | 2         | 2.22%   |
| HP Laptop               | 2         | 2.22%   |
| HP Compaq               | 2         | 2.22%   |
| ASUS VivoBook           | 2         | 2.22%   |
| ASUS PRIME              | 2         | 2.22%   |
| Unknown                 | 2         | 2.22%   |
| Samsung 355V4C          | 1         | 1.11%   |
| MSI MS-7B84             | 1         | 1.11%   |
| MSI MS-7816             | 1         | 1.11%   |
| MSI MS-7693             | 1         | 1.11%   |
| MSI GS60                | 1         | 1.11%   |
| Medion MS-7848          | 1         | 1.11%   |
| Lenovo G480             | 1         | 1.11%   |
| Intel NUC8i7BEH         | 1         | 1.11%   |
| Intel DQ45CB            | 1         | 1.11%   |
| Intel D33217CK          | 1         | 1.11%   |
| Intel B75               | 1         | 1.11%   |
| HUAWEI MACH-WX9         | 1         | 1.11%   |
| HP Spectre              | 1         | 1.11%   |
| HP ProBook              | 1         | 1.11%   |
| HP Presario             | 1         | 1.11%   |
| HP OMEN                 | 1         | 1.11%   |
| HP Notebook             | 1         | 1.11%   |
| HP EliteBook            | 1         | 1.11%   |
| HP 250                  | 1         | 1.11%   |
| Google Banon            | 1         | 1.11%   |
| Gigabyte GB-BXi7-5500   | 1         | 1.11%   |
| Gigabyte GA-MA74GM-S2   | 1         | 1.11%   |
| Gigabyte GA-970A-D3     | 1         | 1.11%   |
| Gigabyte F2A55M-HD2     | 1         | 1.11%   |
| Gigabyte B75M-D3H       | 1         | 1.11%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.11%   |
| Framework Laptop        | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 12        | 13.33%  |
| 2014 | 10        | 11.11%  |
| 2013 | 8         | 8.89%   |
| 2012 | 8         | 8.89%   |
| 2011 | 8         | 8.89%   |
| 2010 | 8         | 8.89%   |
| 2008 | 8         | 8.89%   |
| 2020 | 6         | 6.67%   |
| 2019 | 6         | 6.67%   |
| 2016 | 4         | 4.44%   |
| 2021 | 3         | 3.33%   |
| 2009 | 3         | 3.33%   |
| 2017 | 2         | 2.22%   |
| 2015 | 2         | 2.22%   |
| 2007 | 2         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 45        | 50%     |
| Desktop     | 39        | 43.33%  |
| All in one  | 3         | 3.33%   |
| Tablet      | 1         | 1.11%   |
| Convertible | 1         | 1.11%   |
| Mini pc     | 1         | 1.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 84        | 92.31%  |
| Enabled  | 7         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 98.89%  |
| Yes  | 1         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 25.56%  |
| 3.01-4.0    | 21        | 23.33%  |
| 16.01-24.0  | 18        | 20%     |
| 8.01-16.0   | 16        | 17.78%  |
| 32.01-64.0  | 6         | 6.67%   |
| 2.01-3.0    | 3         | 3.33%   |
| 24.01-32.0  | 1         | 1.11%   |
| 64.01-256.0 | 1         | 1.11%   |
| 1.01-2.0    | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 34        | 36.96%  |
| 1.01-2.0  | 34        | 36.96%  |
| 4.01-8.0  | 11        | 11.96%  |
| 3.01-4.0  | 9         | 9.78%   |
| 8.01-16.0 | 2         | 2.17%   |
| 0.51-1.0  | 2         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 57.78%  |
| 2      | 33        | 36.67%  |
| 3      | 5         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 55.56%  |
| Yes       | 40        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 87.78%  |
| No        | 11        | 12.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 77.78%  |
| No        | 20        | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 62.22%  |
| No        | 34        | 37.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 17.58%  |
| Brazil       | 12        | 13.19%  |
| Germany      | 7         | 7.69%   |
| Argentina    | 5         | 5.49%   |
| UK           | 4         | 4.4%    |
| France       | 4         | 4.4%    |
| Ukraine      | 3         | 3.3%    |
| Spain        | 3         | 3.3%    |
| Portugal     | 3         | 3.3%    |
| India        | 3         | 3.3%    |
| Thailand     | 2         | 2.2%    |
| Poland       | 2         | 2.2%    |
| Mexico       | 2         | 2.2%    |
| Indonesia    | 2         | 2.2%    |
| Hungary      | 2         | 2.2%    |
| Costa Rica   | 2         | 2.2%    |
| Austria      | 2         | 2.2%    |
| Turkey       | 1         | 1.1%    |
| Sweden       | 1         | 1.1%    |
| South Africa | 1         | 1.1%    |
| Serbia       | 1         | 1.1%    |
| Russia       | 1         | 1.1%    |
| Netherlands  | 1         | 1.1%    |
| Luxembourg   | 1         | 1.1%    |
| Jamaica      | 1         | 1.1%    |
| Italy        | 1         | 1.1%    |
| Israel       | 1         | 1.1%    |
| Hong Kong    | 1         | 1.1%    |
| Finland      | 1         | 1.1%    |
| Colombia     | 1         | 1.1%    |
| Canada       | 1         | 1.1%    |
| Belgium      | 1         | 1.1%    |
| Australia    | 1         | 1.1%    |
| Algeria      | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lisbon                      | 2         | 2.2%    |
| Budapest                    | 2         | 2.2%    |
| Berlin                      | 2         | 2.2%    |
| Zaporizhzhia                | 1         | 1.1%    |
| Yogyakarta                  | 1         | 1.1%    |
| Wolfheze                    | 1         | 1.1%    |
| Villahermosa                | 1         | 1.1%    |
| Vienna                      | 1         | 1.1%    |
| Tuen Mun                    | 1         | 1.1%    |
| Tomah                       | 1         | 1.1%    |
| Tiete                       | 1         | 1.1%    |
| Słubice                    | 1         | 1.1%    |
| Surabaya                    | 1         | 1.1%    |
| St Petersburg               | 1         | 1.1%    |
| Siquirres                   | 1         | 1.1%    |
| Seville                     | 1         | 1.1%    |
| Sao Paulo                   | 1         | 1.1%    |
| Sao Jose do Rio Preto       | 1         | 1.1%    |
| Sao Bernardo do Campo       | 1         | 1.1%    |
| Sankt Pölten               | 1         | 1.1%    |
| San Telmo                   | 1         | 1.1%    |
| San Nicolás de los Arroyos | 1         | 1.1%    |
| Salvador                    | 1         | 1.1%    |
| Rosario                     | 1         | 1.1%    |
| Rome                        | 1         | 1.1%    |
| Rodgau                      | 1         | 1.1%    |
| Ratingen                    | 1         | 1.1%    |
| Quilmes                     | 1         | 1.1%    |
| Pontpierre                  | 1         | 1.1%    |
| Patna                       | 1         | 1.1%    |
| Paris                       | 1         | 1.1%    |
| Oakville                    | 1         | 1.1%    |
| Newburgh                    | 1         | 1.1%    |
| New York                    | 1         | 1.1%    |
| Nanterre                    | 1         | 1.1%    |
| Nakhon Pathom               | 1         | 1.1%    |
| Monterrey                   | 1         | 1.1%    |
| Monte Carmelo               | 1         | 1.1%    |
| Molesey                     | 1         | 1.1%    |
| Milan                       | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 19.67%  |
| WDC                 | 18        | 23     | 14.75%  |
| Samsung Electronics | 17        | 17     | 13.93%  |
| Toshiba             | 15        | 15     | 12.3%   |
| Kingston            | 8         | 8      | 6.56%   |
| Crucial             | 6         | 6      | 4.92%   |
| SanDisk             | 4         | 4      | 3.28%   |
| Hitachi             | 4         | 5      | 3.28%   |
| Unknown             | 3         | 3      | 2.46%   |
| Micron Technology   | 3         | 3      | 2.46%   |
| HGST                | 2         | 2      | 1.64%   |
| Fujitsu             | 2         | 2      | 1.64%   |
| XrayDisk            | 1         | 1      | 0.82%   |
| Vaseky              | 1         | 1      | 0.82%   |
| SK hynix            | 1         | 3      | 0.82%   |
| PNY                 | 1         | 2      | 0.82%   |
| Plextor             | 1         | 1      | 0.82%   |
| Maxtor              | 1         | 1      | 0.82%   |
| Leven               | 1         | 1      | 0.82%   |
| KingSpec            | 1         | 1      | 0.82%   |
| KingFast            | 1         | 1      | 0.82%   |
| Intenso             | 1         | 1      | 0.82%   |
| Integral            | 1         | 1      | 0.82%   |
| Hoodisk             | 1         | 1      | 0.82%   |
| GOODRAM             | 1         | 1      | 0.82%   |
| China               | 1         | 1      | 0.82%   |
| Apple               | 1         | 1      | 0.82%   |
| A-DATA Technology   | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB             | 4         | 3.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 2.36%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 2.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 1.57%   |
| Toshiba MQ01ABF050 500GB           | 2         | 1.57%   |
| Toshiba MQ01ABD100 1TB             | 2         | 1.57%   |
| Seagate ST9500325AS 500GB          | 2         | 1.57%   |
| Seagate ST2000LM007-1R8174 2TB     | 2         | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 1.57%   |
| Samsung SSD 850 EVO 250GB          | 2         | 1.57%   |
| Kingston SA400S37120G 120GB SSD    | 2         | 1.57%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 1.57%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 1.57%   |
| XrayDisk 240GB                     | 1         | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1         | 0.79%   |
| WDC WDBNCE2500PNC 250GB SSD        | 1         | 0.79%   |
| WDC WD7501AALS-75J7B0 752GB        | 1         | 0.79%   |
| WDC WD7500BPKX-22HPJT0 752GB       | 1         | 0.79%   |
| WDC WD60EDAZ-11BMZB0 6TB           | 1         | 0.79%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1         | 0.79%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 0.79%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.79%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.79%   |
| WDC WD2500AAKX-001CA0 250GB        | 1         | 0.79%   |
| WDC WD20SPZX-00CRAT0 2TB           | 1         | 0.79%   |
| WDC WD2002FAEX-007BA0 2TB          | 1         | 0.79%   |
| WDC WD1200BEVS-00UST0 120GB        | 1         | 0.79%   |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 0.79%   |
| WDC WD10SPZX-24Z10 1TB             | 1         | 0.79%   |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 0.79%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 1         | 0.79%   |
| Vaseky V800/128G 128GB             | 1         | 0.79%   |
| Unknown SD16G  16GB                | 1         | 0.79%   |
| Unknown MMC Card  16GB             | 1         | 0.79%   |
| Unknown HAG4a2  16GB               | 1         | 0.79%   |
| Toshiba THNSFC128GBSJ SSD          | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 256GB       | 1         | 0.79%   |
| Toshiba MQ04ABF100 1TB             | 1         | 0.79%   |
| Toshiba MQ01ABD075 752GB           | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 25     | 34.85%  |
| WDC                 | 15        | 17     | 22.73%  |
| Toshiba             | 13        | 13     | 19.7%   |
| Samsung Electronics | 5         | 5      | 7.58%   |
| Hitachi             | 4         | 5      | 6.06%   |
| HGST                | 2         | 2      | 3.03%   |
| Fujitsu             | 2         | 2      | 3.03%   |
| Maxtor              | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 17.5%   |
| Samsung Electronics | 5         | 5      | 12.5%   |
| Crucial             | 5         | 5      | 12.5%   |
| WDC                 | 4         | 5      | 10%     |
| SanDisk             | 4         | 4      | 10%     |
| Micron Technology   | 2         | 2      | 5%      |
| Vaseky              | 1         | 1      | 2.5%    |
| Toshiba             | 1         | 1      | 2.5%    |
| PNY                 | 1         | 2      | 2.5%    |
| Plextor             | 1         | 1      | 2.5%    |
| Leven               | 1         | 1      | 2.5%    |
| KingSpec            | 1         | 1      | 2.5%    |
| KingFast            | 1         | 1      | 2.5%    |
| Intenso             | 1         | 1      | 2.5%    |
| Integral            | 1         | 1      | 2.5%    |
| Hoodisk             | 1         | 1      | 2.5%    |
| GOODRAM             | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 59        | 71     | 53.15%  |
| SSD     | 35        | 42     | 31.53%  |
| NVMe    | 13        | 16     | 11.71%  |
| MMC     | 3         | 3      | 2.7%    |
| Unknown | 1         | 1      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 77        | 113    | 81.91%  |
| NVMe | 13        | 16     | 13.83%  |
| MMC  | 3         | 3      | 3.19%   |
| SAS  | 1         | 1      | 1.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 63     | 54.17%  |
| 0.51-1.0   | 34        | 38     | 35.42%  |
| 1.01-2.0   | 6         | 6      | 6.25%   |
| 2.01-3.0   | 2         | 3      | 2.08%   |
| 3.01-4.0   | 1         | 1      | 1.04%   |
| 4.01-10.0  | 1         | 2      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 41.11%  |
| 251-500        | 14        | 15.56%  |
| 501-1000       | 14        | 15.56%  |
| 1001-2000      | 9         | 10%     |
| 51-100         | 6         | 6.67%   |
| 21-50          | 3         | 3.33%   |
| 1-20           | 3         | 3.33%   |
| More than 3000 | 2         | 2.22%   |
| Unknown        | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 52.17%  |
| 21-50     | 12        | 13.04%  |
| 101-250   | 12        | 13.04%  |
| 251-500   | 7         | 7.61%   |
| 51-100    | 6         | 6.52%   |
| 1001-2000 | 3         | 3.26%   |
| 501-1000  | 2         | 2.17%   |
| Unknown   | 2         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST3320418AS 320GB      | 1         | 1      | 33.33%  |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS543232A7A384 320GB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

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
| HDD  | 3         | 3      | 100%    |

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
| Detected | 66        | 97     | 70.21%  |
| Works    | 25        | 33     | 26.6%   |
| Malfunc  | 3         | 3      | 3.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 68        | 66.67%  |
| AMD                              | 12        | 11.76%  |
| Samsung Electronics              | 9         | 8.82%   |
| Silicon Integrated Systems [SiS] | 2         | 1.96%   |
| Nvidia                           | 2         | 1.96%   |
| Toshiba America Info Systems     | 1         | 0.98%   |
| SK hynix                         | 1         | 0.98%   |
| Seagate Technology               | 1         | 0.98%   |
| SanDisk                          | 1         | 0.98%   |
| Micron/Crucial Technology        | 1         | 0.98%   |
| Micron Technology                | 1         | 0.98%   |
| Marvell Technology Group         | 1         | 0.98%   |
| Kingston Technology Company      | 1         | 0.98%   |
| ASMedia Technology               | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 7.2%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 5.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 4%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 4%      |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.4%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.6%    |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.6%    |
| Nvidia MCP61 SATA Controller                                                   | 2         | 1.6%    |
| Nvidia MCP61 IDE                                                               | 2         | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.6%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2         | 1.6%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 2         | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.6%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 2         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.8%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.8%    |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.8%    |
| Micron NVMe Storage Controller                                                 | 1         | 0.8%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 1         | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.8%    |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 57.28%  |
| IDE  | 18        | 17.48%  |
| NVMe | 15        | 14.56%  |
| RAID | 11        | 10.68%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 76        | 84.44%  |
| AMD    | 14        | 15.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 2.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 2.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 2.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 2.22%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.22%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 1.11%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.11%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.11%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1         | 1.11%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 1.11%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.11%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.11%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 1.11%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.11%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.11%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.11%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.11%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.11%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1         | 1.11%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.11%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.11%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1         | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-5675R CPU @ 3.10GHz           | 1         | 1.11%   |
| Intel Core i5-5257U CPU @ 2.70GHz           | 1         | 1.11%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1         | 1.11%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1         | 1.11%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.11%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 24.44%  |
| Intel Core i7           | 19        | 21.11%  |
| Intel Core i3           | 13        | 14.44%  |
| Intel Core 2 Duo        | 4         | 4.44%   |
| Intel Core 2 Quad       | 3         | 3.33%   |
| Intel Celeron           | 3         | 3.33%   |
| AMD Ryzen 5             | 3         | 3.33%   |
| Other                   | 2         | 2.22%   |
| Intel Xeon              | 2         | 2.22%   |
| Intel Pentium Dual-Core | 2         | 2.22%   |
| Intel Pentium Dual      | 2         | 2.22%   |
| AMD FX                  | 2         | 2.22%   |
| AMD A10                 | 2         | 2.22%   |
| Intel Pentium           | 1         | 1.11%   |
| Intel Core i9           | 1         | 1.11%   |
| Intel Core 2            | 1         | 1.11%   |
| Intel Celeron Dual-Core | 1         | 1.11%   |
| AMD Ryzen 7             | 1         | 1.11%   |
| AMD Phenom II X6        | 1         | 1.11%   |
| AMD Phenom              | 1         | 1.11%   |
| AMD Athlon Dual Core    | 1         | 1.11%   |
| AMD Athlon 64 X2        | 1         | 1.11%   |
| AMD A8                  | 1         | 1.11%   |
| AMD A4                  | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 53.33%  |
| 4      | 32        | 35.56%  |
| 6      | 8         | 8.89%   |
| 8      | 1         | 1.11%   |
| 1      | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 63.33%  |
| 1      | 33        | 36.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 90        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 18.68%  |
| 0x306a9    | 8         | 8.79%   |
| 0x206a7    | 7         | 7.69%   |
| 0x1067a    | 6         | 6.59%   |
| 0x806ea    | 5         | 5.49%   |
| 0x906ea    | 4         | 4.4%    |
| 0x40651    | 4         | 4.4%    |
| 0x306d4    | 4         | 4.4%    |
| 0x706e5    | 3         | 3.3%    |
| 0x306c3    | 3         | 3.3%    |
| 0x806c1    | 2         | 2.2%    |
| 0x6fd      | 2         | 2.2%    |
| 0x20655    | 2         | 2.2%    |
| 0x10677    | 2         | 2.2%    |
| 0x10676    | 2         | 2.2%    |
| 0x06000852 | 2         | 2.2%    |
| 0xa0652    | 1         | 1.1%    |
| 0x906ed    | 1         | 1.1%    |
| 0x906eb    | 1         | 1.1%    |
| 0x806e9    | 1         | 1.1%    |
| 0x6f6      | 1         | 1.1%    |
| 0x506e3    | 1         | 1.1%    |
| 0x406c4    | 1         | 1.1%    |
| 0x406c3    | 1         | 1.1%    |
| 0x40671    | 1         | 1.1%    |
| 0x30678    | 1         | 1.1%    |
| 0x106a5    | 1         | 1.1%    |
| 0x08701021 | 1         | 1.1%    |
| 0x08101016 | 1         | 1.1%    |
| 0x08001138 | 1         | 1.1%    |
| 0x0600611a | 1         | 1.1%    |
| 0x06003106 | 1         | 1.1%    |
| 0x010000dc | 1         | 1.1%    |
| 0x01000083 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 15        | 16.67%  |
| Penryn      | 10        | 11.11%  |
| Haswell     | 10        | 11.11%  |
| IvyBridge   | 9         | 10%     |
| SandyBridge | 7         | 7.78%   |
| Broadwell   | 6         | 6.67%   |
| Westmere    | 4         | 4.44%   |
| Piledriver  | 4         | 4.44%   |
| Core        | 4         | 4.44%   |
| Silvermont  | 3         | 3.33%   |
| IceLake     | 3         | 3.33%   |
| Zen         | 2         | 2.22%   |
| TigerLake   | 2         | 2.22%   |
| K8 Hammer   | 2         | 2.22%   |
| K10         | 2         | 2.22%   |
| Zen+        | 1         | 1.11%   |
| Zen 2       | 1         | 1.11%   |
| Steamroller | 1         | 1.11%   |
| Skylake     | 1         | 1.11%   |
| Nehalem     | 1         | 1.11%   |
| Excavator   | 1         | 1.11%   |
| CometLake   | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 57        | 52.78%  |
| Nvidia                           | 31        | 28.7%   |
| AMD                              | 18        | 16.67%  |
| Silicon Integrated Systems [SiS] | 2         | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.46%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.57%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 2.68%   |
| Intel HD Graphics 620                                                                    | 3         | 2.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.68%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 1.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.79%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2         | 1.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.89%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.89%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1         | 0.89%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.89%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.89%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.89%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1         | 0.89%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.89%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1         | 0.89%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.89%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1         | 0.89%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1         | 0.89%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 43.33%  |
| 1 x Nvidia     | 18        | 20%     |
| Intel + Nvidia | 13        | 14.44%  |
| 1 x AMD        | 12        | 13.33%  |
| 2 x AMD        | 3         | 3.33%   |
| Intel + AMD    | 3         | 3.33%   |
| 1 x SiS        | 2         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 68        | 74.73%  |
| Proprietary | 18        | 19.78%  |
| Unknown     | 5         | 5.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 56.04%  |
| 0.51-1.0   | 14        | 15.38%  |
| 3.01-4.0   | 11        | 12.09%  |
| 1.01-2.0   | 10        | 10.99%  |
| 7.01-8.0   | 2         | 2.2%    |
| 0.01-0.5   | 2         | 2.2%    |
| 2.01-3.0   | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 19.57%  |
| AU Optronics            | 9         | 9.78%   |
| LG Display              | 8         | 8.7%    |
| BOE                     | 8         | 8.7%    |
| Hewlett-Packard         | 5         | 5.43%   |
| Goldstar                | 5         | 5.43%   |
| Dell                    | 4         | 4.35%   |
| Ancor Communications    | 3         | 3.26%   |
| Philips                 | 2         | 2.17%   |
| Lenovo                  | 2         | 2.17%   |
| Chimei Innolux          | 2         | 2.17%   |
| Chi Mei Optoelectronics | 2         | 2.17%   |
| BenQ                    | 2         | 2.17%   |
| ASUSTek Computer        | 2         | 2.17%   |
| Apple                   | 2         | 2.17%   |
| Acer                    | 2         | 2.17%   |
| Vizio                   | 1         | 1.09%   |
| ViewSonic               | 1         | 1.09%   |
| Vestel Elektronik       | 1         | 1.09%   |
| Unknown                 | 1         | 1.09%   |
| Toshiba                 | 1         | 1.09%   |
| SKY                     | 1         | 1.09%   |
| Sharp                   | 1         | 1.09%   |
| MSI                     | 1         | 1.09%   |
| LG Electronics          | 1         | 1.09%   |
| JDI                     | 1         | 1.09%   |
| Insignia                | 1         | 1.09%   |
| Huion                   | 1         | 1.09%   |
| HPN                     | 1         | 1.09%   |
| HannStar                | 1         | 1.09%   |
| Eizo                    | 1         | 1.09%   |
| AOC                     | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 2         | 2.06%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch  | 2         | 2.06%   |
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch                 | 1         | 1.03%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch          | 1         | 1.03%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 1.03%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                              | 1         | 1.03%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                        | 1         | 1.03%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                    | 1         | 1.03%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 1.03%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1         | 1.03%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 1         | 1.03%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 1.03%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch   | 1         | 1.03%   |
| Philips LCD Monitor 150C4 1024x768                                     | 1         | 1.03%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                     | 1         | 1.03%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                     | 1         | 1.03%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1         | 1.03%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch            | 1         | 1.03%   |
| LG Display LCD Monitor LGD037C 1366x768 310x174mm 14.0-inch            | 1         | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 1.03%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 1.03%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch            | 1         | 1.03%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch                | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                | 1         | 1.03%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                  | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 32        | 34.04%  |
| 1366x768 (WXGA)   | 23        | 24.47%  |
| 3840x2160 (4K)    | 8         | 8.51%   |
| 1920x1200 (WUXGA) | 5         | 5.32%   |
| 1600x900 (HD+)    | 4         | 4.26%   |
| 1440x900 (WXGA+)  | 3         | 3.19%   |
| 3840x1080         | 2         | 2.13%   |
| 3000x2000         | 2         | 2.13%   |
| 2560x1080         | 2         | 2.13%   |
| 1280x800 (WXGA)   | 2         | 2.13%   |
| 1280x1024 (SXGA)  | 2         | 2.13%   |
| Unknown           | 2         | 2.13%   |
| 3440x1440         | 1         | 1.06%   |
| 2560x1440 (QHD)   | 1         | 1.06%   |
| 2256x1504         | 1         | 1.06%   |
| 1920x540          | 1         | 1.06%   |
| 1360x768          | 1         | 1.06%   |
| 1280x720 (HD)     | 1         | 1.06%   |
| 1024x768 (XGA)    | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 27.66%  |
| 27      | 9         | 9.57%   |
| 24      | 9         | 9.57%   |
| 14      | 8         | 8.51%   |
| Unknown | 7         | 7.45%   |
| 13      | 6         | 6.38%   |
| 17      | 5         | 5.32%   |
| 23      | 4         | 4.26%   |
| 21      | 4         | 4.26%   |
| 19      | 3         | 3.19%   |
| 34      | 2         | 2.13%   |
| 31      | 2         | 2.13%   |
| 20      | 2         | 2.13%   |
| 12      | 2         | 2.13%   |
| 84      | 1         | 1.06%   |
| 48      | 1         | 1.06%   |
| 43      | 1         | 1.06%   |
| 40      | 1         | 1.06%   |
| 26      | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 36.56%  |
| 501-600     | 20        | 21.51%  |
| 401-500     | 8         | 8.6%    |
| 351-400     | 7         | 7.53%   |
| 201-300     | 7         | 7.53%   |
| Unknown     | 7         | 7.53%   |
| 601-700     | 4         | 4.3%    |
| 701-800     | 2         | 2.15%   |
| 801-900     | 1         | 1.08%   |
| 1501-2000   | 1         | 1.08%   |
| 1001-1500   | 1         | 1.08%   |
| 901-1000    | 1         | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 69.32%  |
| 16/10   | 11        | 12.5%   |
| Unknown | 7         | 7.95%   |
| 3/2     | 4         | 4.55%   |
| 5/4     | 2         | 2.27%   |
| 21/9    | 2         | 2.27%   |
| 1.96    | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 26.88%  |
| 81-90          | 11        | 11.83%  |
| 201-250        | 11        | 11.83%  |
| 301-350        | 9         | 9.68%   |
| Unknown        | 7         | 7.53%   |
| 151-200        | 6         | 6.45%   |
| 251-300        | 5         | 5.38%   |
| 351-500        | 4         | 4.3%    |
| 121-130        | 4         | 4.3%    |
| 71-80          | 3         | 3.23%   |
| 501-1000       | 3         | 3.23%   |
| 61-70          | 2         | 2.15%   |
| More than 1000 | 1         | 1.08%   |
| 141-150        | 1         | 1.08%   |
| 91-100         | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 31.87%  |
| 101-120       | 27        | 29.67%  |
| 121-160       | 20        | 21.98%  |
| Unknown       | 7         | 7.69%   |
| More than 240 | 3         | 3.3%    |
| 1-50          | 3         | 3.3%    |
| 161-240       | 2         | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 83.52%  |
| 2     | 10        | 10.99%  |
| 0     | 4         | 4.4%    |
| 3     | 1         | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 46        | 33.33%  |
| Intel                            | 39        | 28.26%  |
| Qualcomm Atheros                 | 22        | 15.94%  |
| Broadcom                         | 8         | 5.8%    |
| TP-Link                          | 4         | 2.9%    |
| Marvell Technology Group         | 3         | 2.17%   |
| Silicon Integrated Systems [SiS] | 2         | 1.45%   |
| Ralink Technology                | 2         | 1.45%   |
| Qualcomm Atheros Communications  | 2         | 1.45%   |
| Nvidia                           | 2         | 1.45%   |
| Xiaomi                           | 1         | 0.72%   |
| T & A Mobile Phones              | 1         | 0.72%   |
| Ralink                           | 1         | 0.72%   |
| Qualcomm                         | 1         | 0.72%   |
| Linksys                          | 1         | 0.72%   |
| Dell                             | 1         | 0.72%   |
| Broadcom Limited                 | 1         | 0.72%   |
| ASUSTek Computer                 | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 36        | 22.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5         | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5         | 3.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 2.52%   |
| Intel Wireless 3160                                                                           | 4         | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                 | 2         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.26%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2         | 1.26%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 1.26%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2         | 1.26%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 1.26%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.26%   |
| Intel Wireless 7265                                                                           | 2         | 1.26%   |
| Intel Wireless 3165                                                                           | 2         | 1.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.26%   |
| Intel I211 Gigabit Network Connection                                                         | 2         | 1.26%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 2         | 1.26%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1         | 0.63%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.63%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 0.63%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 0.63%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                                                    | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.63%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.63%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 40%     |
| Qualcomm Atheros                | 16        | 21.33%  |
| Realtek Semiconductor           | 10        | 13.33%  |
| Broadcom                        | 7         | 9.33%   |
| TP-Link                         | 3         | 4%      |
| Ralink Technology               | 2         | 2.67%   |
| Qualcomm Atheros Communications | 2         | 2.67%   |
| Ralink                          | 1         | 1.33%   |
| Linksys                         | 1         | 1.33%   |
| Dell                            | 1         | 1.33%   |
| Broadcom Limited                | 1         | 1.33%   |
| ASUSTek Computer                | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 6.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 5.33%   |
| Intel Wireless 3160                                                                           | 4         | 5.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.67%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 2.67%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 2.67%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.67%   |
| Intel Wireless 7265                                                                           | 2         | 2.67%   |
| Intel Wireless 3165                                                                           | 2         | 2.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 2.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 2         | 2.67%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 2.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.67%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.33%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 1.33%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.33%   |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.33%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1         | 1.33%   |
| Intel Wireless 8260                                                                           | 1         | 1.33%   |
| Intel Wireless 7260                                                                           | 1         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.33%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 42        | 51.22%  |
| Intel                            | 17        | 20.73%  |
| Qualcomm Atheros                 | 9         | 10.98%  |
| Marvell Technology Group         | 3         | 3.66%   |
| Broadcom                         | 3         | 3.66%   |
| Silicon Integrated Systems [SiS] | 2         | 2.44%   |
| Nvidia                           | 2         | 2.44%   |
| Xiaomi                           | 1         | 1.22%   |
| TP-Link                          | 1         | 1.22%   |
| T & A Mobile Phones              | 1         | 1.22%   |
| Qualcomm                         | 1         | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 2.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 2.38%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.19%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.19%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.19%   |
| Qualcomm Android                                                  | 1         | 1.19%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.19%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.19%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.19%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.19%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1         | 1.19%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 1.19%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 53.02%  |
| WiFi     | 70        | 46.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 60.82%  |
| Ethernet | 38        | 39.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 55.56%  |
| 1     | 35        | 38.89%  |
| 3     | 3         | 3.33%   |
| 0     | 2         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 91.11%  |
| Yes  | 8         | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 41.07%  |
| Qualcomm Atheros Communications | 7         | 12.5%   |
| Cambridge Silicon Radio         | 7         | 12.5%   |
| Realtek Semiconductor           | 4         | 7.14%   |
| IMC Networks                    | 3         | 5.36%   |
| Apple                           | 3         | 5.36%   |
| Dell                            | 2         | 3.57%   |
| Broadcom                        | 2         | 3.57%   |
| Toshiba                         | 1         | 1.79%   |
| Ralink Technology               | 1         | 1.79%   |
| Integrated System Solution      | 1         | 1.79%   |
| Hewlett-Packard                 | 1         | 1.79%   |
| Foxconn / Hon Hai               | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 23.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 5.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 5.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.36%   |
| Intel AX201 Bluetooth                               | 3         | 5.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 3.57%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.57%   |
| Toshiba Bluetooth Device                            | 1         | 1.79%   |
| Realtek Bluetooth Radio                             | 1         | 1.79%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.79%   |
| Intel AX210 Bluetooth                               | 1         | 1.79%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.79%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.79%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.79%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.79%   |
| Dell Wireless 355 Bluetooth                         | 1         | 1.79%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.79%   |
| Apple Bluetooth Host Controller                     | 1         | 1.79%   |
| Apple Bluetooth HCI                                 | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 74        | 58.27%  |
| Nvidia                                          | 21        | 16.54%  |
| AMD                                             | 18        | 14.17%  |
| Logitech                                        | 4         | 3.15%   |
| Texas Instruments                               | 2         | 1.57%   |
| Silicon Integrated Systems [SiS]                | 2         | 1.57%   |
| C-Media Electronics                             | 2         | 1.57%   |
| Razer USA                                       | 1         | 0.79%   |
| M2Tech                                          | 1         | 0.79%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.79%   |
| Generalplus Technology                          | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 4%      |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2%      |
| AMD FCH Azalia Controller                                                                         | 3         | 2%      |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.33%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.33%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.33%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.33%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2         | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.33%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.67%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.67%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 30.23%  |
| SK hynix            | 7         | 16.28%  |
| Kingston            | 6         | 13.95%  |
| Micron Technology   | 5         | 11.63%  |
| Unknown             | 4         | 9.3%    |
| Crucial             | 2         | 4.65%   |
| Teikon              | 1         | 2.33%   |
| Ramaxel Technology  | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Nanya Technology    | 1         | 2.33%   |
| G.Skill             | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                      | 2         | 4.55%   |
| Unknown RAM Module 4096MB DIMM SDRAM 800MT/s                               | 1         | 2.27%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                    | 1         | 2.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM 956MT/s                               | 1         | 2.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                               | 1         | 2.27%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                     | 1         | 2.27%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                      | 1         | 2.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s                        | 1         | 2.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.27%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                      | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                      | 1         | 2.27%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s               | 1         | 2.27%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1024MB DIMM DDR2 800MT/s  | 1         | 2.27%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s                   | 1         | 2.27%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                           | 1         | 2.27%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 49926MT/s                     | 1         | 2.27%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 2.27%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s                   | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s                       | 1         | 2.27%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                      | 1         | 2.27%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                                  | 1         | 2.27%   |
| Kingston RAM KHX2133C13S4/4G 4GB SODIMM DDR4 2133MT/s                      | 1         | 2.27%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.27%   |
| Kingston RAM 9905734-018.A00G 16384MB DIMM DDR4 2667MT/s                   | 1         | 2.27%   |
| Kingston RAM 9905471-011.A00LF 4096MB DIMM DDR3 1600MT/s                   | 1         | 2.27%   |
| Kingston RAM 202020202020202020202020202020202020 2048MB DIMM DDR2 800MT/s | 1         | 2.27%   |
| G.Skill RAM F3-19200C10-8GBZHD 8GB DIMM DDR3 1333MT/s                      | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 41.18%  |
| DDR3    | 11        | 32.35%  |
| DDR2    | 3         | 8.82%   |
| SDRAM   | 2         | 5.88%   |
| Unknown | 2         | 5.88%   |
| LPDDR4  | 1         | 2.94%   |
| LPDDR3  | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 58.82%  |
| DIMM         | 12        | 35.29%  |
| Row Of Chips | 1         | 2.94%   |
| Unknown      | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 31.58%  |
| 4096  | 11        | 28.95%  |
| 2048  | 8         | 21.05%  |
| 16384 | 4         | 10.53%  |
| 1024  | 2         | 5.26%   |
| 32768 | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 29.73%  |
| 2667  | 7         | 18.92%  |
| 3200  | 4         | 10.81%  |
| 800   | 4         | 10.81%  |
| 2400  | 3         | 8.11%   |
| 1333  | 2         | 5.41%   |
| 49926 | 1         | 2.7%    |
| 4267  | 1         | 2.7%    |
| 3466  | 1         | 2.7%    |
| 2133  | 1         | 2.7%    |
| 1334  | 1         | 2.7%    |
| 956   | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |
| Fuji Xerox      | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson ET-2720 Series       | 1         | 20%     |
| HP Officejet 6600                | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Fuji Xerox DocuPrint M205 b      | 1         | 20%     |
| Canon MF240 Series UFRII LT      | 1         | 20%     |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 22.45%  |
| Microdia                      | 7         | 14.29%  |
| Suyin                         | 4         | 8.16%   |
| Sunplus Innovation Technology | 3         | 6.12%   |
| Realtek Semiconductor         | 3         | 6.12%   |
| Quanta                        | 3         | 6.12%   |
| IMC Networks                  | 3         | 6.12%   |
| Bison Electronics             | 3         | 6.12%   |
| Silicon Motion                | 2         | 4.08%   |
| Huawei Technologies           | 2         | 4.08%   |
| Apple                         | 2         | 4.08%   |
| Z-Star Microelectronics       | 1         | 2.04%   |
| Logitech                      | 1         | 2.04%   |
| Jieli Technology              | 1         | 2.04%   |
| Importek                      | 1         | 2.04%   |
| Cubeternet                    | 1         | 2.04%   |
| Acer                          | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                  | 2         | 4.08%   |
| Microdia Integrated Webcam                     | 2         | 4.08%   |
| Huawei HiCamera                                | 2         | 4.08%   |
| Chicony Integrated Camera                      | 2         | 4.08%   |
| Z-Star Vimicro USB Camera (Altair)             | 1         | 2.04%   |
| Suyin WebCam                                   | 1         | 2.04%   |
| Suyin HP Truevision HD                         | 1         | 2.04%   |
| Suyin Asus Integrated Webcam                   | 1         | 2.04%   |
| Suyin 1.3M HD WebCam                           | 1         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_HD            | 1         | 2.04%   |
| Sunplus Integrated_Webcam_HD                   | 1         | 2.04%   |
| Sunplus HD WebCam                              | 1         | 2.04%   |
| Silicon Motion WebCam SC-13HDL11939N           | 1         | 2.04%   |
| Silicon Motion HP Webcam-101 Integrated Camera | 1         | 2.04%   |
| Realtek USB2.0 VGA UVC WebCam                  | 1         | 2.04%   |
| Realtek Laptop Camera                          | 1         | 2.04%   |
| Realtek HP Truevision HD                       | 1         | 2.04%   |
| Quanta Laptop_Integrated_Webcam_2HDM           | 1         | 2.04%   |
| Quanta HP TrueVision HD Camera                 | 1         | 2.04%   |
| Quanta HD Webcam                               | 1         | 2.04%   |
| Microdia Sonix USB 2.0 Camera                  | 1         | 2.04%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_0.3M         | 1         | 2.04%   |
| Logitech HD Pro Webcam C920                    | 1         | 2.04%   |
| Jieli USB PHY 2.0                              | 1         | 2.04%   |
| Importek HP Truevision HD Integrated Webcam    | 1         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 1         | 2.04%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam              | 1         | 2.04%   |
| Cubeternet HDMI to U3 capture                  | 1         | 2.04%   |
| Chicony USB 2.0 Camera                         | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD                | 1         | 2.04%   |
| Chicony Lenovo EasyCamera                      | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera               | 1         | 2.04%   |
| Chicony HP Webcam [2 MP Macro]                 | 1         | 2.04%   |
| Chicony HP Webcam                              | 1         | 2.04%   |
| Chicony HP HD Camera                           | 1         | 2.04%   |
| Chicony HD WebCam                              | 1         | 2.04%   |
| Chicony EasyCamera                             | 1         | 2.04%   |
| Bison Integrated Camera                        | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner       | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Synaptics UWP WBDI                         | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 16.67%  |
| AuthenTec AES2810                          | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 70        | 77.78%  |
| 1     | 18        | 20%     |
| 2     | 2         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 7         | 36.84%  |
| Fingerprint reader | 6         | 31.58%  |
| Net/wireless       | 2         | 10.53%  |
| Chipcard           | 2         | 10.53%  |
| Net/ethernet       | 1         | 5.26%   |
| Bluetooth          | 1         | 5.26%   |

