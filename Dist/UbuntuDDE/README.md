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

Total: 142

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | Notebook    | [1482125b7f](https://linux-hardware.org/?probe=1482125b7f) | Dec 10, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | Notebook    | [64809e77e6](https://linux-hardware.org/?probe=64809e77e6) | Dec 10, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1f9f468508](https://linux-hardware.org/?probe=1f9f468508) | Nov 28, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [abbc44e591](https://linux-hardware.org/?probe=abbc44e591) | Nov 06, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0a53e90c1](https://linux-hardware.org/?probe=f0a53e90c1) | Aug 25, 2024 |
| Samsung       | 730QED                      | Convertible | [4e455d2334](https://linux-hardware.org/?probe=4e455d2334) | Aug 10, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | Notebook    | [f25f2b97ef](https://linux-hardware.org/?probe=f25f2b97ef) | Aug 01, 2024 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [f9ce9e4174](https://linux-hardware.org/?probe=f9ce9e4174) | Jul 17, 2024 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [a97e21eb8a](https://linux-hardware.org/?probe=a97e21eb8a) | Apr 11, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b89a7c2325](https://linux-hardware.org/?probe=b89a7c2325) | Mar 14, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [103b3dc25f](https://linux-hardware.org/?probe=103b3dc25f) | Feb 25, 2024 |
| Chuwi         | HeroBook Pro                | Notebook    | [f34f3d183d](https://linux-hardware.org/?probe=f34f3d183d) | Feb 23, 2024 |
| HP            | 250 G3                      | Notebook    | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| HP            | 250 G3                      | Notebook    | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [c2dc388cd3](https://linux-hardware.org/?probe=c2dc388cd3) | Oct 25, 2023 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [f6389f0244](https://linux-hardware.org/?probe=f6389f0244) | Oct 06, 2023 |
| Dell          | Latitude E7450              | Notebook    | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [c8d399d95d](https://linux-hardware.org/?probe=c8d399d95d) | Jul 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
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
| UbuntuDDE 20.04 | 65        | 61.9%   |
| UbuntuDDE 22.04 | 9         | 8.57%   |
| UbuntuDDE 21.10 | 7         | 6.67%   |
| UbuntuDDE 23.04 | 6         | 5.71%   |
| UbuntuDDE 21.04 | 6         | 5.71%   |
| UbuntuDDE 20.10 | 5         | 4.76%   |
| UbuntuDDE 18.04 | 4         | 3.81%   |
| UbuntuDDE 24.04 | 2         | 1.9%    |
| UbuntuDDE 18.10 | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 105       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-29-generic    | 18        | 16.51%  |
| 5.4.0-42-generic    | 11        | 10.09%  |
| 5.4.0-21-generic    | 6         | 5.5%    |
| 5.4.0-37-generic    | 5         | 4.59%   |
| 6.2.0-39-generic    | 4         | 3.67%   |
| 5.4.0-48-generic    | 4         | 3.67%   |
| 5.8.0-33-generic    | 2         | 1.83%   |
| 5.4.0-52-generic    | 2         | 1.83%   |
| 5.4.0-39-generic    | 2         | 1.83%   |
| 5.3.0-40-generic    | 2         | 1.83%   |
| 5.15.0-88-generic   | 2         | 1.83%   |
| 5.15.0-53-generic   | 2         | 1.83%   |
| 5.15.0-48-generic   | 2         | 1.83%   |
| 5.11.0-17-generic   | 2         | 1.83%   |
| 6.8.0-49-generic    | 1         | 0.92%   |
| 6.8.0-45-generic    | 1         | 0.92%   |
| 6.2.0-35-generic    | 1         | 0.92%   |
| 6.2.0-34-generic    | 1         | 0.92%   |
| 6.2.0-27-generic    | 1         | 0.92%   |
| 5.8.0-53-generic    | 1         | 0.92%   |
| 5.8.0-50-generic    | 1         | 0.92%   |
| 5.8.0-48-generic    | 1         | 0.92%   |
| 5.8.0-41-generic    | 1         | 0.92%   |
| 5.8.0-23-generic    | 1         | 0.92%   |
| 5.6.0-1008-oem      | 1         | 0.92%   |
| 5.4.0-96-generic    | 1         | 0.92%   |
| 5.4.0-94-generic    | 1         | 0.92%   |
| 5.4.0-88-generic    | 1         | 0.92%   |
| 5.4.0-84-generic    | 1         | 0.92%   |
| 5.4.0-70-generic    | 1         | 0.92%   |
| 5.4.0-53-generic    | 1         | 0.92%   |
| 5.4.0-45-generic    | 1         | 0.92%   |
| 5.4.0-40-lowlatency | 1         | 0.92%   |
| 5.4.0-34-generic    | 1         | 0.92%   |
| 5.4.0-33-generic    | 1         | 0.92%   |
| 5.4.0-31-generic    | 1         | 0.92%   |
| 5.4.0-26-generic    | 1         | 0.92%   |
| 5.4.0-24-generic    | 1         | 0.92%   |
| 5.19.0-46-generic   | 1         | 0.92%   |
| 5.19.0-38-generic   | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 60        | 57.14%  |
| 5.15.0  | 8         | 7.62%   |
| 6.2.0   | 7         | 6.67%   |
| 5.8.0   | 7         | 6.67%   |
| 5.13.0  | 7         | 6.67%   |
| 5.11.0  | 6         | 5.71%   |
| 6.8.0   | 2         | 1.9%    |
| 5.3.0   | 2         | 1.9%    |
| 5.19.0  | 2         | 1.9%    |
| 4.15.0  | 2         | 1.9%    |
| 5.6.0   | 1         | 0.95%   |
| 5.0.0   | 1         | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 57.14%  |
| 5.15    | 8         | 7.62%   |
| 6.2     | 7         | 6.67%   |
| 5.8     | 7         | 6.67%   |
| 5.13    | 7         | 6.67%   |
| 5.11    | 6         | 5.71%   |
| 6.8     | 2         | 1.9%    |
| 5.3     | 2         | 1.9%    |
| 5.19    | 2         | 1.9%    |
| 4.15    | 2         | 1.9%    |
| 5.6     | 1         | 0.95%   |
| 5.0     | 1         | 0.95%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 105       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 105       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 96.19%  |
| Wayland | 3         | 2.86%   |
| Tty     | 1         | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 54.72%  |
| LightDM | 26        | 24.53%  |
| GDM     | 11        | 10.38%  |
| TDM     | 6         | 5.66%   |
| GDM3    | 4         | 3.77%   |
| SDDM    | 1         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 41        | 39.05%  |
| pt_BR   | 10        | 9.52%   |
| es_ES   | 5         | 4.76%   |
| en_GB   | 5         | 4.76%   |
| de_DE   | 5         | 4.76%   |
| C       | 5         | 4.76%   |
| fr_FR   | 4         | 3.81%   |
| ru_RU   | 3         | 2.86%   |
| es_AR   | 3         | 2.86%   |
| it_IT   | 2         | 1.9%    |
| fi_FI   | 2         | 1.9%    |
| es_MX   | 2         | 1.9%    |
| en_AU   | 2         | 1.9%    |
| uk_UA   | 1         | 0.95%   |
| tr_TR   | 1         | 0.95%   |
| th_TH   | 1         | 0.95%   |
| sr_RS   | 1         | 0.95%   |
| pl_PL   | 1         | 0.95%   |
| nl_NL   | 1         | 0.95%   |
| id_ID   | 1         | 0.95%   |
| es_CR   | 1         | 0.95%   |
| es_CO   | 1         | 0.95%   |
| en_ZA   | 1         | 0.95%   |
| en_IN   | 1         | 0.95%   |
| en_CA   | 1         | 0.95%   |
| en_BW   | 1         | 0.95%   |
| de_CH   | 1         | 0.95%   |
| cs_CZ   | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 56        | 52.83%  |
| EFI  | 50        | 47.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 82.86%  |
| Tmpfs   | 9         | 8.57%   |
| Overlay | 4         | 3.81%   |
| Btrfs   | 2         | 1.9%    |
| Zfs     | 1         | 0.95%   |
| Ext2    | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 59.05%  |
| GPT     | 36        | 34.29%  |
| MBR     | 7         | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 82.86%  |
| Yes       | 18        | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 50%     |
| No        | 53        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 19.05%  |
| Hewlett-Packard     | 18        | 17.14%  |
| Dell                | 14        | 13.33%  |
| Lenovo              | 9         | 8.57%   |
| MSI                 | 7         | 6.67%   |
| Gigabyte Technology | 6         | 5.71%   |
| Acer                | 5         | 4.76%   |
| Intel               | 4         | 3.81%   |
| Toshiba             | 2         | 1.9%    |
| Samsung Electronics | 2         | 1.9%    |
| HUAWEI              | 2         | 1.9%    |
| ASRock              | 2         | 1.9%    |
| Apple               | 2         | 1.9%    |
| Unknown             | 2         | 1.9%    |
| Medion              | 1         | 0.95%   |
| Google              | 1         | 0.95%   |
| Fujitsu Siemens     | 1         | 0.95%   |
| Fujitsu             | 1         | 0.95%   |
| Framework           | 1         | 0.95%   |
| eMachines           | 1         | 0.95%   |
| ECS                 | 1         | 0.95%   |
| Chuwi               | 1         | 0.95%   |
| BESSTAR Tech        | 1         | 0.95%   |
| BANGHO              | 1         | 0.95%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7592                                | 3         | 2.86%   |
| Unknown                                    | 2         | 1.9%    |
| Toshiba Satellite S55t-B                   | 1         | 0.95%   |
| Toshiba Satellite C55-B                    | 1         | 0.95%   |
| Samsung 730QED                             | 1         | 0.95%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.95%   |
| MSI MS-7B84                                | 1         | 0.95%   |
| MSI MS-7816                                | 1         | 0.95%   |
| MSI MS-7693                                | 1         | 0.95%   |
| MSI GS60 2QE                               | 1         | 0.95%   |
| Medion MS-7848                             | 1         | 0.95%   |
| Lenovo ThinkPad X200 Tablet 7449FWG        | 1         | 0.95%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJ0017US | 1         | 0.95%   |
| Lenovo ThinkPad T430 2349DS5               | 1         | 0.95%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300       | 1         | 0.95%   |
| Lenovo IdeaPad Pro 5 14IMH9 83D2           | 1         | 0.95%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 0.95%   |
| Lenovo IdeaPad 510-15IKB 80SV              | 1         | 0.95%   |
| Lenovo G480 20150                          | 1         | 0.95%   |
| Lenovo 100-14IBY 80R7                      | 1         | 0.95%   |
| Intel NUC8i7BEH                            | 1         | 0.95%   |
| Intel DQ45CB AAE30148-207                  | 1         | 0.95%   |
| Intel D33217CK G76541-302                  | 1         | 0.95%   |
| Intel B75                                  | 1         | 0.95%   |
| HUAWEI MACHC-WAX9                          | 1         | 0.95%   |
| HUAWEI MACH-WX9                            | 1         | 0.95%   |
| HP Spectre x360 Convertible 13-aw0xxx      | 1         | 0.95%   |
| HP ProBook 650 G3                          | 1         | 0.95%   |
| HP Presario CQ56                           | 1         | 0.95%   |
| HP Pavilion dv6                            | 1         | 0.95%   |
| HP Pavilion dm4                            | 1         | 0.95%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 0.95%   |
| HP Pavilion 14                             | 1         | 0.95%   |
| HP OMEN by Laptop 17-cb1xxx                | 1         | 0.95%   |
| HP Notebook                                | 1         | 0.95%   |
| HP Laptop 15-dy1xxx                        | 1         | 0.95%   |
| HP Laptop 15-da0xxx                        | 1         | 0.95%   |
| HP EliteBook 8570p                         | 1         | 0.95%   |
| HP EliteBook 820 G3                        | 1         | 0.95%   |
| HP EliteBook 2540p                         | 1         | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 6         | 5.71%   |
| Lenovo ThinkPad       | 4         | 3.81%   |
| HP Pavilion           | 4         | 3.81%   |
| Dell Latitude         | 4         | 3.81%   |
| MSI MS-7592           | 3         | 2.86%   |
| Lenovo IdeaPad        | 3         | 2.86%   |
| HP EliteBook          | 3         | 2.86%   |
| ASUS VivoBook         | 3         | 2.86%   |
| Acer Aspire           | 3         | 2.86%   |
| Toshiba Satellite     | 2         | 1.9%    |
| HP Laptop             | 2         | 1.9%    |
| HP Compaq             | 2         | 1.9%    |
| HP 250                | 2         | 1.9%    |
| ASUS PRIME            | 2         | 1.9%    |
| Unknown               | 2         | 1.9%    |
| Samsung 730QED        | 1         | 0.95%   |
| Samsung 355V4C        | 1         | 0.95%   |
| MSI MS-7B84           | 1         | 0.95%   |
| MSI MS-7816           | 1         | 0.95%   |
| MSI MS-7693           | 1         | 0.95%   |
| MSI GS60              | 1         | 0.95%   |
| Medion MS-7848        | 1         | 0.95%   |
| Lenovo G480           | 1         | 0.95%   |
| Lenovo 100-14IBY      | 1         | 0.95%   |
| Intel NUC8i7BEH       | 1         | 0.95%   |
| Intel DQ45CB          | 1         | 0.95%   |
| Intel D33217CK        | 1         | 0.95%   |
| Intel B75             | 1         | 0.95%   |
| HUAWEI MACHC-WAX9     | 1         | 0.95%   |
| HUAWEI MACH-WX9       | 1         | 0.95%   |
| HP Spectre            | 1         | 0.95%   |
| HP ProBook            | 1         | 0.95%   |
| HP Presario           | 1         | 0.95%   |
| HP OMEN               | 1         | 0.95%   |
| HP Notebook           | 1         | 0.95%   |
| Google Banon          | 1         | 0.95%   |
| Gigabyte GB-BXi7-5500 | 1         | 0.95%   |
| Gigabyte GA-MA74GM-S2 | 1         | 0.95%   |
| Gigabyte GA-970A-D3   | 1         | 0.95%   |
| Gigabyte GA-770TA-UD3 | 1         | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 13        | 12.38%  |
| 2018 | 12        | 11.43%  |
| 2012 | 9         | 8.57%   |
| 2011 | 9         | 8.57%   |
| 2013 | 8         | 7.62%   |
| 2010 | 8         | 7.62%   |
| 2008 | 8         | 7.62%   |
| 2020 | 7         | 6.67%   |
| 2019 | 5         | 4.76%   |
| 2016 | 5         | 4.76%   |
| 2021 | 4         | 3.81%   |
| 2015 | 4         | 3.81%   |
| 2009 | 4         | 3.81%   |
| 2017 | 3         | 2.86%   |
| 2023 | 2         | 1.9%    |
| 2007 | 2         | 1.9%    |
| 2024 | 1         | 0.95%   |
| 2022 | 1         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 55        | 52.38%  |
| Desktop     | 43        | 40.95%  |
| All in one  | 3         | 2.86%   |
| Convertible | 2         | 1.9%    |
| Tablet      | 1         | 0.95%   |
| Mini pc     | 1         | 0.95%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 98        | 92.45%  |
| Enabled  | 8         | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 99.05%  |
| Yes  | 1         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 26.67%  |
| 3.01-4.0    | 23        | 21.9%   |
| 16.01-24.0  | 23        | 21.9%   |
| 8.01-16.0   | 17        | 16.19%  |
| 32.01-64.0  | 8         | 7.62%   |
| 2.01-3.0    | 3         | 2.86%   |
| 24.01-32.0  | 1         | 0.95%   |
| 64.01-256.0 | 1         | 0.95%   |
| 1.01-2.0    | 1         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 41        | 37.96%  |
| 1.01-2.0  | 40        | 37.04%  |
| 4.01-8.0  | 12        | 11.11%  |
| 3.01-4.0  | 11        | 10.19%  |
| 8.01-16.0 | 2         | 1.85%   |
| 0.51-1.0  | 2         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 59.05%  |
| 2      | 36        | 34.29%  |
| 3      | 6         | 5.71%   |
| 4      | 1         | 0.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 59.05%  |
| Yes       | 43        | 40.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 85.71%  |
| No        | 15        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 80%     |
| No        | 21        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 63.81%  |
| No        | 38        | 36.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 22        | 20.75%  |
| Brazil       | 12        | 11.32%  |
| Germany      | 7         | 6.6%    |
| Argentina    | 6         | 5.66%   |
| UK           | 4         | 3.77%   |
| Portugal     | 4         | 3.77%   |
| France       | 4         | 3.77%   |
| Ukraine      | 3         | 2.83%   |
| Spain        | 3         | 2.83%   |
| Mexico       | 3         | 2.83%   |
| India        | 3         | 2.83%   |
| Turkey       | 2         | 1.89%   |
| Thailand     | 2         | 1.89%   |
| Poland       | 2         | 1.89%   |
| Indonesia    | 2         | 1.89%   |
| Hungary      | 2         | 1.89%   |
| Finland      | 2         | 1.89%   |
| Costa Rica   | 2         | 1.89%   |
| Austria      | 2         | 1.89%   |
| Australia    | 2         | 1.89%   |
| Uruguay      | 1         | 0.94%   |
| Sweden       | 1         | 0.94%   |
| South Africa | 1         | 0.94%   |
| Serbia       | 1         | 0.94%   |
| Russia       | 1         | 0.94%   |
| Netherlands  | 1         | 0.94%   |
| Luxembourg   | 1         | 0.94%   |
| Jamaica      | 1         | 0.94%   |
| Italy        | 1         | 0.94%   |
| Israel       | 1         | 0.94%   |
| Hong Kong    | 1         | 0.94%   |
| Georgia      | 1         | 0.94%   |
| Czechia      | 1         | 0.94%   |
| Colombia     | 1         | 0.94%   |
| Canada       | 1         | 0.94%   |
| Belgium      | 1         | 0.94%   |
| Algeria      | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Milwaukee                   | 2         | 1.89%   |
| Lisbon                      | 2         | 1.89%   |
| Las Vegas                   | 2         | 1.89%   |
| Helsinki                    | 2         | 1.89%   |
| Budapest                    | 2         | 1.89%   |
| Berlin                      | 2         | 1.89%   |
| Zaporizhzhia                | 1         | 0.94%   |
| Zapopan                     | 1         | 0.94%   |
| Yogyakarta                  | 1         | 0.94%   |
| Wolfheze                    | 1         | 0.94%   |
| Villahermosa                | 1         | 0.94%   |
| Vienna                      | 1         | 0.94%   |
| Tuen Mun                    | 1         | 0.94%   |
| Tomah                       | 1         | 0.94%   |
| Tiete                       | 1         | 0.94%   |
| Tbilisi                     | 1         | 0.94%   |
| Słubice                    | 1         | 0.94%   |
| Surabaya                    | 1         | 0.94%   |
| St Petersburg               | 1         | 0.94%   |
| Şişli                     | 1         | 0.94%   |
| Siquirres                   | 1         | 0.94%   |
| Seville                     | 1         | 0.94%   |
| Sao Paulo                   | 1         | 0.94%   |
| Sao Jose do Rio Preto       | 1         | 0.94%   |
| Sao Bernardo do Campo       | 1         | 0.94%   |
| Sankt Pölten               | 1         | 0.94%   |
| San Telmo                   | 1         | 0.94%   |
| San Nicolás de los Arroyos | 1         | 0.94%   |
| Salvador                    | 1         | 0.94%   |
| Rosario                     | 1         | 0.94%   |
| Rome                        | 1         | 0.94%   |
| Rodgau                      | 1         | 0.94%   |
| Ratingen                    | 1         | 0.94%   |
| Quilmes                     | 1         | 0.94%   |
| Porto                       | 1         | 0.94%   |
| Pontpierre                  | 1         | 0.94%   |
| Patna                       | 1         | 0.94%   |
| Paris                       | 1         | 0.94%   |
| Ostrava                     | 1         | 0.94%   |
| Oakville                    | 1         | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 35     | 19.86%  |
| Samsung Electronics | 21        | 21     | 14.89%  |
| WDC                 | 19        | 24     | 13.48%  |
| Toshiba             | 15        | 15     | 10.64%  |
| Kingston            | 8         | 8      | 5.67%   |
| Crucial             | 6         | 6      | 4.26%   |
| Unknown             | 4         | 5      | 2.84%   |
| SanDisk             | 4         | 4      | 2.84%   |
| Micron Technology   | 4         | 4      | 2.84%   |
| Hitachi             | 4         | 5      | 2.84%   |
| HGST                | 3         | 3      | 2.13%   |
| Fujitsu             | 2         | 2      | 1.42%   |
| China               | 2         | 2      | 1.42%   |
| Apple               | 2         | 2      | 1.42%   |
| XrayDisk            | 1         | 1      | 0.71%   |
| WDC WDS5            | 1         | 1      | 0.71%   |
| Vaseky              | 1         | 1      | 0.71%   |
| Timetec             | 1         | 1      | 0.71%   |
| SK hynix            | 1         | 3      | 0.71%   |
| PNY                 | 1         | 2      | 0.71%   |
| Plextor             | 1         | 1      | 0.71%   |
| Maxtor              | 1         | 1      | 0.71%   |
| Leven               | 1         | 1      | 0.71%   |
| KingSpec            | 1         | 1      | 0.71%   |
| KingFast            | 1         | 1      | 0.71%   |
| JMicron Technology  | 1         | 1      | 0.71%   |
| Intenso             | 1         | 1      | 0.71%   |
| Integral            | 1         | 1      | 0.71%   |
| Hoodisk             | 1         | 1      | 0.71%   |
| GOODRAM             | 1         | 1      | 0.71%   |
| Dahua               | 1         | 1      | 0.71%   |
| ADATA Technology    | 1         | 1      | 0.71%   |
| A-DATA Technology   | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB             | 4         | 2.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 2.01%   |
| Seagate ST1000DM010-2EP102 1TB     | 3         | 2.01%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 2.01%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 1.34%   |
| Toshiba MQ01ABF050 500GB           | 2         | 1.34%   |
| Toshiba MQ01ABD100 1TB             | 2         | 1.34%   |
| Seagate ST9500325AS 500GB          | 2         | 1.34%   |
| Seagate ST2000LM007-1R8174 2TB     | 2         | 1.34%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 1.34%   |
| Seagate ST1000LM014-1EJ164 1TB     | 2         | 1.34%   |
| Samsung SSD 850 EVO 250GB          | 2         | 1.34%   |
| Kingston SA400S37120G 120GB SSD    | 2         | 1.34%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 1.34%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 1.34%   |
| XrayDisk 240GB                     | 1         | 0.67%   |
| WDC WDS5 00G1B0A-00H9H0 500GB SSD  | 1         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.67%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1         | 0.67%   |
| WDC WDBNCE2500PNC 250GB SSD        | 1         | 0.67%   |
| WDC WD7501AALS-75J7B0 752GB        | 1         | 0.67%   |
| WDC WD7500BPKX-22HPJT0 752GB       | 1         | 0.67%   |
| WDC WD60EDAZ-11BMZB0 6TB           | 1         | 0.67%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.67%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1         | 0.67%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 0.67%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.67%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.67%   |
| WDC WD2500AAKX-001CA0 250GB        | 1         | 0.67%   |
| WDC WD20SPZX-00CRAT0 2TB           | 1         | 0.67%   |
| WDC WD2002FAEX-007BA0 2TB          | 1         | 0.67%   |
| WDC WD1200BEVS-00UST0 120GB        | 1         | 0.67%   |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB             | 1         | 0.67%   |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 0.67%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 1         | 0.67%   |
| Vaseky V800/128G 128GB SSD         | 1         | 0.67%   |
| Unknown SD16G  16GB                | 1         | 0.67%   |
| Unknown MMC Card  536GB            | 1         | 0.67%   |
| Unknown MMC Card  16GB             | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 34     | 36.99%  |
| WDC                 | 16        | 18     | 21.92%  |
| Toshiba             | 13        | 13     | 17.81%  |
| Samsung Electronics | 5         | 5      | 6.85%   |
| Hitachi             | 4         | 5      | 5.48%   |
| HGST                | 3         | 3      | 4.11%   |
| Fujitsu             | 2         | 2      | 2.74%   |
| Apple               | 2         | 2      | 2.74%   |
| Maxtor              | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 15.56%  |
| Samsung Electronics | 6         | 6      | 13.33%  |
| Crucial             | 5         | 5      | 11.11%  |
| WDC                 | 4         | 5      | 8.89%   |
| SanDisk             | 4         | 4      | 8.89%   |
| Micron Technology   | 2         | 2      | 4.44%   |
| China               | 2         | 2      | 4.44%   |
| WDC WDS5            | 1         | 1      | 2.22%   |
| Vaseky              | 1         | 1      | 2.22%   |
| Toshiba             | 1         | 1      | 2.22%   |
| Timetec             | 1         | 1      | 2.22%   |
| PNY                 | 1         | 2      | 2.22%   |
| Plextor             | 1         | 1      | 2.22%   |
| Leven               | 1         | 1      | 2.22%   |
| KingSpec            | 1         | 1      | 2.22%   |
| KingFast            | 1         | 1      | 2.22%   |
| Intenso             | 1         | 1      | 2.22%   |
| Integral            | 1         | 1      | 2.22%   |
| Hoodisk             | 1         | 1      | 2.22%   |
| GOODRAM             | 1         | 1      | 2.22%   |
| Dahua               | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 83     | 50.77%  |
| SSD     | 40        | 47     | 30.77%  |
| NVMe    | 18        | 21     | 13.85%  |
| MMC     | 4         | 5      | 3.08%   |
| Unknown | 2         | 2      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 128    | 77.19%  |
| NVMe | 18        | 21     | 15.79%  |
| SAS  | 4         | 4      | 3.51%   |
| MMC  | 4         | 5      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 71     | 53.64%  |
| 0.51-1.0   | 38        | 42     | 34.55%  |
| 1.01-2.0   | 8         | 10     | 7.27%   |
| 3.01-4.0   | 2         | 2      | 1.82%   |
| 2.01-3.0   | 2         | 3      | 1.82%   |
| 4.01-10.0  | 1         | 2      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 38.1%   |
| 251-500        | 17        | 16.19%  |
| 501-1000       | 17        | 16.19%  |
| 1001-2000      | 11        | 10.48%  |
| 51-100         | 10        | 9.52%   |
| 21-50          | 3         | 2.86%   |
| 1-20           | 3         | 2.86%   |
| More than 3000 | 2         | 1.9%    |
| Unknown        | 2         | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 53        | 49.53%  |
| 21-50     | 18        | 16.82%  |
| 101-250   | 14        | 13.08%  |
| 251-500   | 8         | 7.48%   |
| 51-100    | 6         | 5.61%   |
| 1001-2000 | 3         | 2.8%    |
| 501-1000  | 3         | 2.8%    |
| Unknown   | 2         | 1.87%   |

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
| Detected | 75        | 115    | 68.81%  |
| Works    | 31        | 40     | 28.44%  |
| Malfunc  | 3         | 3      | 2.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 62.81%  |
| AMD                              | 15        | 12.4%   |
| Samsung Electronics              | 12        | 9.92%   |
| Silicon Integrated Systems [SiS] | 2         | 1.65%   |
| Nvidia                           | 2         | 1.65%   |
| Micron Technology                | 2         | 1.65%   |
| Marvell Technology Group         | 2         | 1.65%   |
| ASMedia Technology               | 2         | 1.65%   |
| Toshiba America Info Systems     | 1         | 0.83%   |
| SK hynix                         | 1         | 0.83%   |
| Seagate Technology               | 1         | 0.83%   |
| SanDisk                          | 1         | 0.83%   |
| Micron/Crucial Technology        | 1         | 0.83%   |
| Kingston Technology Company      | 1         | 0.83%   |
| JMicron Technology               | 1         | 0.83%   |
| ADATA Technology                 | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 6.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 4.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 3.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 2.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.05%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.37%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.37%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 1.37%   |
| Nvidia MCP61 IDE                                                               | 2         | 1.37%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 2         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 2         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.37%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2         | 1.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.37%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.68%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.68%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 0.68%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 68        | 56.67%  |
| NVMe | 20        | 16.67%  |
| IDE  | 20        | 16.67%  |
| RAID | 12        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 87        | 82.86%  |
| AMD    | 18        | 17.14%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz               | 3         | 2.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.9%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 1.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz               | 2         | 1.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 1.9%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 1.9%    |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 1.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.9%    |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2         | 1.9%    |
| Intel Xeon E-2224G CPU @ 3.50GHz                | 1         | 0.95%   |
| Intel Xeon CPU E5450 @ 3.00GHz                  | 1         | 0.95%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1         | 0.95%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1         | 0.95%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz          | 1         | 0.95%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz          | 1         | 0.95%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 1         | 0.95%   |
| Intel Core Ultra 5 125H                         | 1         | 0.95%   |
| Intel Core i9-8950HK CPU @ 2.90GHz              | 1         | 0.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.95%   |
| Intel Core i7-8559U CPU @ 2.70GHz               | 1         | 0.95%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1         | 0.95%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 0.95%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.95%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 0.95%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.95%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 0.95%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 0.95%   |
| Intel Core i7-2700K CPU @ 3.50GHz               | 1         | 0.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 0.95%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 0.95%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.95%   |
| Intel Core i7 CPU 950 @ 3.07GHz                 | 1         | 0.95%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 0.95%   |
| Intel Core i5-5675R CPU @ 3.10GHz               | 1         | 0.95%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 23.81%  |
| Intel Core i7           | 21        | 20%     |
| Intel Core i3           | 13        | 12.38%  |
| Intel Celeron           | 6         | 5.71%   |
| Other                   | 5         | 4.76%   |
| Intel Core 2 Duo        | 4         | 3.81%   |
| Intel Core 2 Quad       | 3         | 2.86%   |
| AMD Ryzen 5             | 3         | 2.86%   |
| AMD A10                 | 3         | 2.86%   |
| Intel Xeon              | 2         | 1.9%    |
| Intel Pentium Dual-Core | 2         | 1.9%    |
| Intel Pentium Dual      | 2         | 1.9%    |
| AMD FX                  | 2         | 1.9%    |
| Intel Pentium           | 1         | 0.95%   |
| Intel Core i9           | 1         | 0.95%   |
| Intel Core 2            | 1         | 0.95%   |
| Intel Core              | 1         | 0.95%   |
| Intel Celeron Dual-Core | 1         | 0.95%   |
| AMD Ryzen 9             | 1         | 0.95%   |
| AMD Ryzen 7             | 1         | 0.95%   |
| AMD Phenom II X6        | 1         | 0.95%   |
| AMD Phenom II X4        | 1         | 0.95%   |
| AMD Phenom              | 1         | 0.95%   |
| AMD Athlon Dual Core    | 1         | 0.95%   |
| AMD Athlon 64 X2        | 1         | 0.95%   |
| AMD A8                  | 1         | 0.95%   |
| AMD A4                  | 1         | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 53.33%  |
| 4      | 35        | 33.33%  |
| 6      | 9         | 8.57%   |
| 8      | 2         | 1.9%    |
| 14     | 1         | 0.95%   |
| 10     | 1         | 0.95%   |
| 1      | 1         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 105       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 62.86%  |
| 1      | 39        | 37.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 105       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 29.25%  |
| 0x306a9    | 8         | 7.55%   |
| 0x206a7    | 7         | 6.6%    |
| 0x1067a    | 6         | 5.66%   |
| 0x806ea    | 5         | 4.72%   |
| 0x906ea    | 4         | 3.77%   |
| 0x40651    | 4         | 3.77%   |
| 0x306d4    | 4         | 3.77%   |
| 0x706e5    | 3         | 2.83%   |
| 0x306c3    | 3         | 2.83%   |
| 0x806c1    | 2         | 1.89%   |
| 0x6fd      | 2         | 1.89%   |
| 0x20655    | 2         | 1.89%   |
| 0x10677    | 2         | 1.89%   |
| 0x10676    | 2         | 1.89%   |
| 0x06000852 | 2         | 1.89%   |
| 0xa0652    | 1         | 0.94%   |
| 0x906ed    | 1         | 0.94%   |
| 0x906eb    | 1         | 0.94%   |
| 0x806e9    | 1         | 0.94%   |
| 0x6f6      | 1         | 0.94%   |
| 0x506e3    | 1         | 0.94%   |
| 0x406c4    | 1         | 0.94%   |
| 0x406c3    | 1         | 0.94%   |
| 0x40671    | 1         | 0.94%   |
| 0x30678    | 1         | 0.94%   |
| 0x106a5    | 1         | 0.94%   |
| 0x0a705203 | 1         | 0.94%   |
| 0x08701021 | 1         | 0.94%   |
| 0x08101016 | 1         | 0.94%   |
| 0x08001138 | 1         | 0.94%   |
| 0x0600611a | 1         | 0.94%   |
| 0x06003106 | 1         | 0.94%   |
| 0x010000dc | 1         | 0.94%   |
| 0x01000083 | 1         | 0.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 16        | 15.24%  |
| Penryn            | 10        | 9.52%   |
| IvyBridge         | 10        | 9.52%   |
| Haswell           | 10        | 9.52%   |
| SandyBridge       | 8         | 7.62%   |
| Broadwell         | 7         | 6.67%   |
| Silvermont        | 5         | 4.76%   |
| Westmere          | 4         | 3.81%   |
| Piledriver        | 4         | 3.81%   |
| Core              | 4         | 3.81%   |
| K10               | 3         | 2.86%   |
| IceLake           | 3         | 2.86%   |
| Zen               | 2         | 1.9%    |
| TigerLake         | 2         | 1.9%    |
| Steamroller       | 2         | 1.9%    |
| Skylake           | 2         | 1.9%    |
| K8 Hammer         | 2         | 1.9%    |
| Excavator         | 2         | 1.9%    |
| Unknown           | 2         | 1.9%    |
| Zen+              | 1         | 0.95%   |
| Zen 2             | 1         | 0.95%   |
| Nehalem           | 1         | 0.95%   |
| Meteorlake Hybrid | 1         | 0.95%   |
| Goldmont plus     | 1         | 0.95%   |
| CometLake         | 1         | 0.95%   |
| Alderlake Hybrid  | 1         | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 67        | 54.03%  |
| Nvidia                           | 33        | 26.61%  |
| AMD                              | 22        | 17.74%  |
| Silicon Integrated Systems [SiS] | 2         | 1.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 5.47%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.91%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 2.34%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 2.34%   |
| Intel HD Graphics 620                                                                    | 3         | 2.34%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.34%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 1.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.56%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2         | 1.56%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.78%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.78%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1         | 0.78%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.78%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.78%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.78%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1         | 0.78%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.78%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1         | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 45.71%  |
| 1 x Nvidia     | 19        | 18.1%   |
| 1 x AMD        | 16        | 15.24%  |
| Intel + Nvidia | 14        | 13.33%  |
| 2 x AMD        | 3         | 2.86%   |
| Intel + AMD    | 3         | 2.86%   |
| 1 x SiS        | 2         | 1.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 81        | 76.42%  |
| Proprietary | 19        | 17.92%  |
| Unknown     | 6         | 5.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 58.49%  |
| 0.51-1.0   | 15        | 14.15%  |
| 3.01-4.0   | 12        | 11.32%  |
| 1.01-2.0   | 11        | 10.38%  |
| 0.01-0.5   | 3         | 2.83%   |
| 7.01-8.0   | 2         | 1.89%   |
| 2.01-3.0   | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 22        | 20%     |
| LG Display              | 11        | 10%     |
| BOE                     | 11        | 10%     |
| AU Optronics            | 10        | 9.09%   |
| Hewlett-Packard         | 6         | 5.45%   |
| Goldstar                | 5         | 4.55%   |
| Dell                    | 4         | 3.64%   |
| Ancor Communications    | 4         | 3.64%   |
| ASUSTek Computer        | 3         | 2.73%   |
| Philips                 | 2         | 1.82%   |
| Lenovo                  | 2         | 1.82%   |
| JDI                     | 2         | 1.82%   |
| Chimei Innolux          | 2         | 1.82%   |
| Chi Mei Optoelectronics | 2         | 1.82%   |
| BenQ                    | 2         | 1.82%   |
| Apple                   | 2         | 1.82%   |
| Acer                    | 2         | 1.82%   |
| Vizio                   | 1         | 0.91%   |
| ViewSonic               | 1         | 0.91%   |
| Vestel Elektronik       | 1         | 0.91%   |
| Unknown                 | 1         | 0.91%   |
| Toshiba                 | 1         | 0.91%   |
| SKY                     | 1         | 0.91%   |
| Sharp                   | 1         | 0.91%   |
| MSI                     | 1         | 0.91%   |
| LG Electronics          | 1         | 0.91%   |
| ITE                     | 1         | 0.91%   |
| Insignia                | 1         | 0.91%   |
| InfoVision              | 1         | 0.91%   |
| Huion                   | 1         | 0.91%   |
| HPN                     | 1         | 0.91%   |
| HannStar                | 1         | 0.91%   |
| Fujitsu Siemens         | 1         | 0.91%   |
| Eizo                    | 1         | 0.91%   |
| AOC                     | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 2         | 1.74%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 1.74%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 1.74%   |
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch                | 1         | 0.87%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch         | 1         | 0.87%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1         | 0.87%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                             | 1         | 0.87%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                       | 1         | 0.87%   |
| SKY TV-monitor SKY0001 1920x1080 885x498mm 40.0-inch                  | 1         | 0.87%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.87%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.87%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.87%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1         | 0.87%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC419D 2880x1800 302x189mm 14.0-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0E4C 1366x768 522x293mm 23.6-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 0.87%   |
| Philips LCD Monitor 150C4 1024x768                                    | 1         | 0.87%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                    | 1         | 0.87%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.87%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 0.87%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 33.33%  |
| 1366x768 (WXGA)   | 28        | 25.23%  |
| 3840x2160 (4K)    | 9         | 8.11%   |
| 1920x1200 (WUXGA) | 5         | 4.5%    |
| 1600x900 (HD+)    | 5         | 4.5%    |
| 1440x900 (WXGA+)  | 4         | 3.6%    |
| 3000x2000         | 3         | 2.7%    |
| 1280x1024 (SXGA)  | 3         | 2.7%    |
| 3840x1080         | 2         | 1.8%    |
| 2880x1800         | 2         | 1.8%    |
| 2560x1080         | 2         | 1.8%    |
| 1280x800 (WXGA)   | 2         | 1.8%    |
| Unknown           | 2         | 1.8%    |
| 3440x1440         | 1         | 0.9%    |
| 2560x1440 (QHD)   | 1         | 0.9%    |
| 2256x1504         | 1         | 0.9%    |
| 1920x540          | 1         | 0.9%    |
| 1360x768          | 1         | 0.9%    |
| 1280x720 (HD)     | 1         | 0.9%    |
| 1024x768 (XGA)    | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 26.13%  |
| 14      | 13        | 11.71%  |
| 24      | 11        | 9.91%   |
| 27      | 9         | 8.11%   |
| 13      | 8         | 7.21%   |
| Unknown | 7         | 6.31%   |
| 17      | 6         | 5.41%   |
| 23      | 4         | 3.6%    |
| 21      | 4         | 3.6%    |
| 19      | 4         | 3.6%    |
| 20      | 3         | 2.7%    |
| 12      | 3         | 2.7%    |
| 34      | 2         | 1.8%    |
| 31      | 2         | 1.8%    |
| 84      | 1         | 0.9%    |
| 48      | 1         | 0.9%    |
| 46      | 1         | 0.9%    |
| 43      | 1         | 0.9%    |
| 40      | 1         | 0.9%    |
| 26      | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 38.74%  |
| 501-600     | 23        | 20.72%  |
| 401-500     | 10        | 9.01%   |
| 201-300     | 10        | 9.01%   |
| 351-400     | 7         | 6.31%   |
| Unknown     | 7         | 6.31%   |
| 601-700     | 4         | 3.6%    |
| 701-800     | 2         | 1.8%    |
| 1001-1500   | 2         | 1.8%    |
| 801-900     | 1         | 0.9%    |
| 1501-2000   | 1         | 0.9%    |
| 901-1000    | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 73        | 69.52%  |
| 16/10   | 14        | 13.33%  |
| Unknown | 7         | 6.67%   |
| 3/2     | 5         | 4.76%   |
| 5/4     | 3         | 2.86%   |
| 21/9    | 2         | 1.9%    |
| 1.96    | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 26.13%  |
| 81-90          | 17        | 15.32%  |
| 201-250        | 14        | 12.61%  |
| 301-350        | 9         | 8.11%   |
| 151-200        | 8         | 7.21%   |
| Unknown        | 7         | 6.31%   |
| 71-80          | 5         | 4.5%    |
| 251-300        | 5         | 4.5%    |
| 351-500        | 4         | 3.6%    |
| 121-130        | 4         | 3.6%    |
| 501-1000       | 4         | 3.6%    |
| 61-70          | 2         | 1.8%    |
| 141-150        | 2         | 1.8%    |
| More than 1000 | 1         | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 32.11%  |
| 101-120       | 31        | 28.44%  |
| 121-160       | 22        | 20.18%  |
| Unknown       | 7         | 6.42%   |
| More than 240 | 6         | 5.5%    |
| 1-50          | 4         | 3.67%   |
| 161-240       | 4         | 3.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 83.02%  |
| 2     | 13        | 12.26%  |
| 0     | 4         | 3.77%   |
| 3     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 53        | 33.54%  |
| Intel                            | 47        | 29.75%  |
| Qualcomm Atheros                 | 22        | 13.92%  |
| Broadcom                         | 9         | 5.7%    |
| TP-Link                          | 4         | 2.53%   |
| Marvell Technology Group         | 3         | 1.9%    |
| Silicon Integrated Systems [SiS] | 2         | 1.27%   |
| Ralink Technology                | 2         | 1.27%   |
| Ralink                           | 2         | 1.27%   |
| Qualcomm Atheros Communications  | 2         | 1.27%   |
| Nvidia                           | 2         | 1.27%   |
| Xiaomi                           | 1         | 0.63%   |
| T & A Mobile Phones              | 1         | 0.63%   |
| Qualcomm                         | 1         | 0.63%   |
| MediaTek                         | 1         | 0.63%   |
| Linksys                          | 1         | 0.63%   |
| Hewlett-Packard                  | 1         | 0.63%   |
| Dell                             | 1         | 0.63%   |
| Broadcom Limited                 | 1         | 0.63%   |
| ASUSTek Computer                 | 1         | 0.63%   |
| ASIX Electronics                 | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 20.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 3.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 3.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 2.15%   |
| Intel Wireless 3160                                                    | 4         | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.61%   |
| Intel Wireless 7265                                                    | 3         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 1.08%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 1.08%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.08%   |
| Intel Wireless 8260                                                    | 2         | 1.08%   |
| Intel Wireless 3165                                                    | 2         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 2         | 1.08%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 2         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.54%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1         | 0.54%   |
| TP-Link Archer T4U ver.3                                               | 1         | 0.54%   |
| TP-Link 802.11ac NIC                                                   | 1         | 0.54%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                             | 1         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 40.45%  |
| Qualcomm Atheros                | 16        | 17.98%  |
| Realtek Semiconductor           | 15        | 16.85%  |
| Broadcom                        | 8         | 8.99%   |
| TP-Link                         | 3         | 3.37%   |
| Ralink Technology               | 2         | 2.25%   |
| Ralink                          | 2         | 2.25%   |
| Qualcomm Atheros Communications | 2         | 2.25%   |
| MediaTek                        | 1         | 1.12%   |
| Linksys                         | 1         | 1.12%   |
| Dell                            | 1         | 1.12%   |
| Broadcom Limited                | 1         | 1.12%   |
| ASUSTek Computer                | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 5.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 4.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 4.49%   |
| Intel Wireless 3160                                                                           | 4         | 4.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.37%   |
| Intel Wireless 7265                                                                           | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 3.37%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 2.25%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 2.25%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.25%   |
| Intel Wireless 8260                                                                           | 2         | 2.25%   |
| Intel Wireless 3165                                                                           | 2         | 2.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 2.25%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 2         | 2.25%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 2.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.25%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.12%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 1.12%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.12%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1         | 1.12%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.12%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.12%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.12%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.12%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.12%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1         | 1.12%   |
| Intel Wireless 7260                                                                           | 1         | 1.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 51.06%  |
| Intel                            | 22        | 23.4%   |
| Qualcomm Atheros                 | 9         | 9.57%   |
| Marvell Technology Group         | 3         | 3.19%   |
| Broadcom                         | 3         | 3.19%   |
| Silicon Integrated Systems [SiS] | 2         | 2.13%   |
| Nvidia                           | 2         | 2.13%   |
| Xiaomi                           | 1         | 1.06%   |
| TP-Link                          | 1         | 1.06%   |
| T & A Mobile Phones              | 1         | 1.06%   |
| Qualcomm                         | 1         | 1.06%   |
| ASIX Electronics                 | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 39.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 7.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 7.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 2.08%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 2.08%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 1.04%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                             | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.04%   |
| Qualcomm MDM9207-MTP _SN:01E0290C                                      | 1         | 1.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.04%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.04%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 1.04%   |
| Intel 82583V Gigabit Network Connection                                | 1         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.04%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel 82562V-2 10/100 Network Connection                               | 1         | 1.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 90        | 51.43%  |
| WiFi     | 84        | 48%     |
| Modem    | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 59.29%  |
| Ethernet | 46        | 40.71%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 53.33%  |
| 1     | 44        | 41.9%   |
| 3     | 3         | 2.86%   |
| 0     | 2         | 1.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 89.52%  |
| Yes  | 11        | 10.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 43.28%  |
| Qualcomm Atheros Communications | 7         | 10.45%  |
| Cambridge Silicon Radio         | 7         | 10.45%  |
| Realtek Semiconductor           | 6         | 8.96%   |
| IMC Networks                    | 4         | 5.97%   |
| Broadcom                        | 3         | 4.48%   |
| Apple                           | 3         | 4.48%   |
| Dell                            | 2         | 2.99%   |
| Toshiba                         | 1         | 1.49%   |
| Ralink Technology               | 1         | 1.49%   |
| Ralink                          | 1         | 1.49%   |
| Integrated System Solution      | 1         | 1.49%   |
| Hewlett-Packard                 | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 22.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 10.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.48%   |
| Realtek Bluetooth Radio                             | 3         | 4.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 4.48%   |
| Intel AX201 Bluetooth                               | 3         | 4.48%   |
| IMC Networks Bluetooth Radio                        | 3         | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.99%   |
| Intel AX211 Bluetooth                               | 2         | 2.99%   |
| Toshiba Bluetooth Device                            | 1         | 1.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.49%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.49%   |
| Intel AX210 Bluetooth                               | 1         | 1.49%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.49%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.49%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.49%   |
| Dell Wireless 355 Bluetooth                         | 1         | 1.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.49%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.49%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.49%   |
| Apple Bluetooth Host Controller                     | 1         | 1.49%   |
| Apple Bluetooth HCI                                 | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 85        | 58.62%  |
| Nvidia                                          | 22        | 15.17%  |
| AMD                                             | 22        | 15.17%  |
| Logitech                                        | 4         | 2.76%   |
| Texas Instruments                               | 3         | 2.07%   |
| Silicon Integrated Systems [SiS]                | 2         | 1.38%   |
| C-Media Electronics                             | 2         | 1.38%   |
| Realtek Semiconductor                           | 1         | 0.69%   |
| Razer USA                                       | 1         | 0.69%   |
| M2Tech                                          | 1         | 0.69%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.69%   |
| Generalplus Technology                          | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 5.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.62%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 4.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.89%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 2.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.31%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.73%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.16%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.16%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.16%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.16%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.16%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2         | 1.16%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.16%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 2         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.16%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.58%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.58%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 29.41%  |
| SK hynix            | 8         | 15.69%  |
| Micron Technology   | 7         | 13.73%  |
| Kingston            | 6         | 11.76%  |
| Unknown             | 4         | 7.84%   |
| Crucial             | 2         | 3.92%   |
| Unknown (ABCD)      | 1         | 1.96%   |
| Unknown (2C0B)      | 1         | 1.96%   |
| Teikon              | 1         | 1.96%   |
| Ramaxel Technology  | 1         | 1.96%   |
| Patriot             | 1         | 1.96%   |
| Nanya Technology    | 1         | 1.96%   |
| G.Skill             | 1         | 1.96%   |
| Elpida              | 1         | 1.96%   |
| Corsair             | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                  | 2         | 3.85%   |
| Unknown RAM Module 4096MB DIMM SDRAM 800MT/s                           | 1         | 1.92%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM SDRAM 956MT/s                           | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                           | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                 | 1         | 1.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s       | 1         | 1.92%   |
| Unknown (2C0B) RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.92%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                  | 1         | 1.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                 | 1         | 1.92%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.92%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s                    | 1         | 1.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s           | 1         | 1.92%   |
| Samsung RAM K4U6E3S4AB-MGCL 1GB Row Of Chips LPDDR4 4267MT/s           | 1         | 1.92%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 1.92%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1GB DIMM DDR2 800MT/s | 1         | 1.92%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s               | 1         | 1.92%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                       | 1         | 1.92%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR 49926MT/s                     | 1         | 1.92%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s             | 1         | 1.92%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7467MT/s          | 1         | 1.92%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1         | 1.92%   |
| Micron RAM 8JTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.92%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s                 | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 36.59%  |
| DDR3    | 12        | 29.27%  |
| LPDDR4  | 3         | 7.32%   |
| DDR2    | 3         | 7.32%   |
| SDRAM   | 2         | 4.88%   |
| LPDDR5  | 2         | 4.88%   |
| LPDDR3  | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 58.54%  |
| DIMM         | 12        | 29.27%  |
| Row Of Chips | 4         | 9.76%   |
| Unknown      | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 28.26%  |
| 4096  | 13        | 28.26%  |
| 2048  | 9         | 19.57%  |
| 16384 | 8         | 17.39%  |
| 1024  | 2         | 4.35%   |
| 32768 | 1         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 12        | 27.27%  |
| 2667  | 7         | 15.91%  |
| 3200  | 4         | 9.09%   |
| 2400  | 4         | 9.09%   |
| 800   | 4         | 9.09%   |
| 2133  | 3         | 6.82%   |
| 4267  | 2         | 4.55%   |
| 1333  | 2         | 4.55%   |
| 49926 | 1         | 2.27%   |
| 7500  | 1         | 2.27%   |
| 7467  | 1         | 2.27%   |
| 3600  | 1         | 2.27%   |
| 1334  | 1         | 2.27%   |
| 956   | 1         | 2.27%   |

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
| Chicony Electronics           | 14        | 22.95%  |
| Microdia                      | 7         | 11.48%  |
| Suyin                         | 4         | 6.56%   |
| Sunplus Innovation Technology | 4         | 6.56%   |
| Realtek Semiconductor         | 3         | 4.92%   |
| Quanta                        | 3         | 4.92%   |
| IMC Networks                  | 3         | 4.92%   |
| Silicon Motion                | 2         | 3.28%   |
| Huawei Technologies           | 2         | 3.28%   |
| Bison Electronics             | 2         | 3.28%   |
| Apple                         | 2         | 3.28%   |
| Acer                          | 2         | 3.28%   |
| Z-Star Microelectronics       | 1         | 1.64%   |
| Syntek                        | 1         | 1.64%   |
| SunplusIT                     | 1         | 1.64%   |
| Shinetech                     | 1         | 1.64%   |
| Motorola PCS                  | 1         | 1.64%   |
| Luxvisions Innotech Limited   | 1         | 1.64%   |
| Logitech                      | 1         | 1.64%   |
| Lite-On Technology            | 1         | 1.64%   |
| kingcome                      | 1         | 1.64%   |
| Jieli Technology              | 1         | 1.64%   |
| Importek                      | 1         | 1.64%   |
| Cubeternet                    | 1         | 1.64%   |
| Alcor Micro                   | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                          | 2         | 3.28%   |
| Microdia Integrated_Webcam_HD                                         | 2         | 3.28%   |
| Microdia Integrated Webcam                                            | 2         | 3.28%   |
| Huawei HiCamera                                                       | 2         | 3.28%   |
| Chicony Integrated Camera                                             | 2         | 3.28%   |
| Chicony HP Webcam                                                     | 2         | 3.28%   |
| Z-Star Vimicro USB Camera (Altair)                                    | 1         | 1.64%   |
| Syntek Lenovo EasyCamera                                              | 1         | 1.64%   |
| Suyin WebCam                                                          | 1         | 1.64%   |
| Suyin HP Truevision HD                                                | 1         | 1.64%   |
| Suyin Asus Integrated Webcam                                          | 1         | 1.64%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 1.64%   |
| SunplusIT 720p HD Camera                                              | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 1.64%   |
| Sunplus HD WebCam                                                     | 1         | 1.64%   |
| Silicon Motion WebCam SC-13HDL11939N                                  | 1         | 1.64%   |
| Silicon Motion HP Webcam-101 Integrated Camera                        | 1         | 1.64%   |
| Shinetech USB2.0 FHD UVC WebCam                                       | 1         | 1.64%   |
| Realtek USB2.0 VGA UVC WebCam                                         | 1         | 1.64%   |
| Realtek Laptop Camera                                                 | 1         | 1.64%   |
| Realtek HP Truevision HD                                              | 1         | 1.64%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                  | 1         | 1.64%   |
| Quanta HP TrueVision HD Camera                                        | 1         | 1.64%   |
| Quanta HD Webcam                                                      | 1         | 1.64%   |
| Motorola PCS moto g power 5G - 2023                                   | 1         | 1.64%   |
| Microdia Sonix USB 2.0 Camera                                         | 1         | 1.64%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                        | 1         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.64%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 1.64%   |
| Logitech HD Pro Webcam C920                                           | 1         | 1.64%   |
| Lite-On HP HD Webcam                                                  | 1         | 1.64%   |
| kingcome HD Camera                                                    | 1         | 1.64%   |
| Jieli USB PHY 2.0                                                     | 1         | 1.64%   |
| Importek HP Truevision HD Integrated Webcam                           | 1         | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 1         | 1.64%   |
| IMC Networks USB2.0 UVC HD Webcam                                     | 1         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 1.64%   |
| Cubeternet HDMI to U3 capture                                         | 1         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 1         | 1.64%   |
| Chicony USB 2.0 Camera                                                | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 62.5%   |
| Synaptics                  | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 25%     |
| Validity Sensors Fingerprint scanner       | 2         | 25%     |
| Validity Sensors VFS491                    | 1         | 12.5%   |
| Synaptics UWP WBDI                         | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device        | 1         | 12.5%   |
| AuthenTec AES2810                          | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 78        | 74.29%  |
| 1     | 23        | 21.9%   |
| 2     | 4         | 3.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 8         | 28.57%  |
| Fingerprint reader | 8         | 28.57%  |
| Net/wireless       | 4         | 14.29%  |
| Chipcard           | 3         | 10.71%  |
| Bluetooth          | 2         | 7.14%   |
| Network            | 1         | 3.57%   |
| Net/ethernet       | 1         | 3.57%   |
| Camera             | 1         | 3.57%   |

