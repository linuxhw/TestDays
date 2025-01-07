Q4OS - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Q4OS/Desktop/README.md) and [notebooks](/Dist/Q4OS/Notebook/README.md).

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

Total: 136

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Biostar       | H81MHV3                     | Desktop     | [4018e1961c](https://linux-hardware.org/?probe=4018e1961c) | Jan 05, 2025 |
| Acer          | AOD257                      | Notebook    | [cd57ba84bc](https://linux-hardware.org/?probe=cd57ba84bc) | Jan 03, 2025 |
| Apple         | MacBookAir5,1               | Notebook    | [3e859a02ef](https://linux-hardware.org/?probe=3e859a02ef) | Dec 26, 2024 |
| HP            | Stream Notebook PC 11       | Notebook    | [104ee26be6](https://linux-hardware.org/?probe=104ee26be6) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [341dc448fb](https://linux-hardware.org/?probe=341dc448fb) | Dec 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [597783d573](https://linux-hardware.org/?probe=597783d573) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [bbc531ab55](https://linux-hardware.org/?probe=bbc531ab55) | Nov 29, 2024 |
| MSI           | B75IA-E33                   | Desktop     | [8f135723bc](https://linux-hardware.org/?probe=8f135723bc) | Nov 16, 2024 |
| Toshiba       | Satellite M100              | Notebook    | [5e91fe5751](https://linux-hardware.org/?probe=5e91fe5751) | Nov 11, 2024 |
| Acer          | AOD270                      | Notebook    | [59b2793787](https://linux-hardware.org/?probe=59b2793787) | Nov 10, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [06e781c23c](https://linux-hardware.org/?probe=06e781c23c) | Nov 02, 2024 |
| Unknown       | E142                        | Notebook    | [e652a7e6d8](https://linux-hardware.org/?probe=e652a7e6d8) | Oct 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b6ac399c00](https://linux-hardware.org/?probe=b6ac399c00) | Oct 13, 2024 |
| Dell          | Latitude E5540              | Notebook    | [a59dfdcd62](https://linux-hardware.org/?probe=a59dfdcd62) | Oct 03, 2024 |
| Dell          | Latitude E5540              | Notebook    | [44955d2b3b](https://linux-hardware.org/?probe=44955d2b3b) | Oct 03, 2024 |
| MicroByte     | ezbook                      | Notebook    | [79104622de](https://linux-hardware.org/?probe=79104622de) | Sep 24, 2024 |
| Lenovo        | ThinkPad X201 3249MJJ       | Notebook    | [04987f2d0e](https://linux-hardware.org/?probe=04987f2d0e) | Sep 23, 2024 |
| ASUSTek       | M3A79-T DELUXE              | Desktop     | [1777d7b016](https://linux-hardware.org/?probe=1777d7b016) | Sep 23, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [aa75424421](https://linux-hardware.org/?probe=aa75424421) | Sep 19, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8c7a3cb9ec](https://linux-hardware.org/?probe=8c7a3cb9ec) | Sep 16, 2024 |
| Acer          | Aspire 5920G                | Notebook    | [611ba26507](https://linux-hardware.org/?probe=611ba26507) | Sep 04, 2024 |
| Acer          | Aspire E1-470G              | Notebook    | [fd457f673c](https://linux-hardware.org/?probe=fd457f673c) | Aug 25, 2024 |
| HP            | 2000                        | Notebook    | [28e8a84a4a](https://linux-hardware.org/?probe=28e8a84a4a) | Aug 18, 2024 |
| HP            | Notebook                    | Notebook    | [a1f1e83afe](https://linux-hardware.org/?probe=a1f1e83afe) | Jul 23, 2024 |
| HP            | Notebook                    | Notebook    | [1df59c0265](https://linux-hardware.org/?probe=1df59c0265) | Jul 23, 2024 |
| Toshiba       | NB100                       | Notebook    | [3ca4d2b945](https://linux-hardware.org/?probe=3ca4d2b945) | Jun 16, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [396846baeb](https://linux-hardware.org/?probe=396846baeb) | May 31, 2024 |
| GFAST         | N-140                       | Notebook    | [43195fd09f](https://linux-hardware.org/?probe=43195fd09f) | May 16, 2024 |
| Acer          | Aspire V5-121               | Notebook    | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Medion        | Cattle24 -1M                | Desktop     | [aa19188799](https://linux-hardware.org/?probe=aa19188799) | May 08, 2024 |
| Unknown       | HOTTAB                      | Desktop     | [aadecb497e](https://linux-hardware.org/?probe=aadecb497e) | May 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [708780fb6c](https://linux-hardware.org/?probe=708780fb6c) | May 05, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [d6fca9f7f5](https://linux-hardware.org/?probe=d6fca9f7f5) | Apr 13, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| Panasonic     | CF-S10CWHDS                 | Notebook    | [a4c273ab7b](https://linux-hardware.org/?probe=a4c273ab7b) | Mar 19, 2024 |
| MSI           | Alpha 17 C7VF               | Notebook    | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [ba11489894](https://linux-hardware.org/?probe=ba11489894) | Feb 23, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [08c95dbf39](https://linux-hardware.org/?probe=08c95dbf39) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c246a6b564](https://linux-hardware.org/?probe=c246a6b564) | Jan 30, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | Notebook    | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Matsushita... | CF-29LAQGZBM                | Notebook    | [433fd9b78e](https://linux-hardware.org/?probe=433fd9b78e) | Jan 11, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [a7ec902190](https://linux-hardware.org/?probe=a7ec902190) | Jan 10, 2024 |
| Irbis         | NB264                       | Notebook    | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | Notebook    | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [db6f924b29](https://linux-hardware.org/?probe=db6f924b29) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6df3bded78](https://linux-hardware.org/?probe=6df3bded78) | Nov 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | Notebook    | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [9ebfdab7fa](https://linux-hardware.org/?probe=9ebfdab7fa) | Aug 31, 2023 |
| Acer          | Aspire 1700                 | Notebook    | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | Notebook    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [5a968533da](https://linux-hardware.org/?probe=5a968533da) | Jul 28, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | Notebook    | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | Notebook    | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| ASUSTek       | ET1602                      | Desktop     | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [43fc15779a](https://linux-hardware.org/?probe=43fc15779a) | Apr 19, 2023 |
| HP            | 1850                        | Desktop     | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| Acer          | One S1003                   | Tablet      | [89fa2c4ac3](https://linux-hardware.org/?probe=89fa2c4ac3) | Mar 28, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | Notebook    | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6a033988f5](https://linux-hardware.org/?probe=6a033988f5) | Feb 07, 2023 |
| HP            | 1850                        | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| VXL           | M6V90AI-VL                  | Desktop     | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| MSI           | G41M4                       | Desktop     | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Unknown       | V00                         | Mini pc     | [15a2312211](https://linux-hardware.org/?probe=15a2312211) | Nov 26, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| Google        | Cave                        | Notebook    | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | Notebook    | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Medion        | P6620                       | Notebook    | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | Notebook    | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | Notebook    | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | Notebook    | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Compaq        | 07E4h                       | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| MSI           | U210                        | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | XP-M5S661GX                 | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| Phoenix/Si... | M720SR                      | Notebook    | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| TECO Elect... | TR53A0                      | Desktop     | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | Notebook    | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2               | Desktop     | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| HP            | ProBook 6550b               | Notebook    | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASUSTek       | A6JC                        | Notebook    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | Notebook    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | Notebook    | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | Notebook    | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | Notebook    | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | Notebook    | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                         | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Q4OS 4    | 45        | 41.67%  |
| Q4OS 5    | 41        | 37.96%  |
| Q4OS 3    | 16        | 14.81%  |
| Q4OS 2    | 5         | 4.63%   |
| Q4OS 4.11 | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.1.0-18-amd64       | 6         | 5.36%   |
| 5.10.0-21-amd64      | 6         | 5.36%   |
| 6.1.0-23-amd64       | 5         | 4.46%   |
| 6.1.0-27-amd64       | 4         | 3.57%   |
| 6.1.0-25-amd64       | 4         | 3.57%   |
| 6.1.0-13-amd64       | 4         | 3.57%   |
| 5.10.0-23-amd64      | 4         | 3.57%   |
| 5.10.0-19-amd64      | 4         | 3.57%   |
| 6.1.0-21-amd64       | 3         | 2.68%   |
| 5.10.0-21-686-pae    | 3         | 2.68%   |
| 5.10.0-12-amd64      | 3         | 2.68%   |
| 4.19.0-17-amd64      | 3         | 2.68%   |
| 6.1.0-28-amd64       | 2         | 1.79%   |
| 6.1.0-26-amd64       | 2         | 1.79%   |
| 6.1.0-17-686-pae     | 2         | 1.79%   |
| 5.10.0-8-amd64       | 2         | 1.79%   |
| 5.10.0-14-686-pae    | 2         | 1.79%   |
| 5.10.0-10-686-pae    | 2         | 1.79%   |
| 6.6.8-x64v1-xanmod1  | 1         | 0.89%   |
| 6.5.1-060501-generic | 1         | 0.89%   |
| 6.5.0-4-amd64        | 1         | 0.89%   |
| 6.1.0-26-686-pae     | 1         | 0.89%   |
| 6.1.0-21-686-pae     | 1         | 0.89%   |
| 6.1.0-17-amd64       | 1         | 0.89%   |
| 6.1.0-16-686-pae     | 1         | 0.89%   |
| 6.1.0-12-amd64       | 1         | 0.89%   |
| 6.1.0-12-686-pae     | 1         | 0.89%   |
| 6.1.0-11-686-pae     | 1         | 0.89%   |
| 6.1.0-10-amd64       | 1         | 0.89%   |
| 6.1.0-10-686-pae     | 1         | 0.89%   |
| 6.0.0-1-amd64        | 1         | 0.89%   |
| 5.9.0-5-amd64        | 1         | 0.89%   |
| 5.6.0-1-amd64        | 1         | 0.89%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 0.89%   |
| 5.10.0-9-amd64       | 1         | 0.89%   |
| 5.10.0-9-686-pae     | 1         | 0.89%   |
| 5.10.0-8-686-pae     | 1         | 0.89%   |
| 5.10.0-29-686-pae    | 1         | 0.89%   |
| 5.10.0-28-amd64      | 1         | 0.89%   |
| 5.10.0-25-amd64      | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 42        | 38.89%  |
| 6.1.0   | 38        | 35.19%  |
| 4.19.0  | 17        | 15.74%  |
| 4.9.0   | 4         | 3.7%    |
| 6.6.8   | 1         | 0.93%   |
| 6.5.1   | 1         | 0.93%   |
| 6.5.0   | 1         | 0.93%   |
| 6.0.0   | 1         | 0.93%   |
| 5.9.0   | 1         | 0.93%   |
| 5.6.0   | 1         | 0.93%   |
| 5.18.0  | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 42        | 38.89%  |
| 6.1     | 38        | 35.19%  |
| 4.19    | 17        | 15.74%  |
| 4.9     | 4         | 3.7%    |
| 6.5     | 2         | 1.85%   |
| 6.6     | 1         | 0.93%   |
| 6.0     | 1         | 0.93%   |
| 5.9     | 1         | 0.93%   |
| 5.6     | 1         | 0.93%   |
| 5.18    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 71.3%   |
| i686   | 31        | 28.7%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 60        | 55.05%  |
| KDE5     | 42        | 38.53%  |
| KDE      | 2         | 1.83%   |
| XFCE     | 1         | 0.92%   |
| MATE     | 1         | 0.92%   |
| LXDE     | 1         | 0.92%   |
| Cinnamon | 1         | 0.92%   |
| Budgie   | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 98.15%  |
| Wayland | 1         | 0.93%   |
| Tty     | 1         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 61        | 56.48%  |
| SDDM    | 45        | 41.67%  |
| LightDM | 2         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 38.89%  |
| de_DE   | 9         | 8.33%   |
| it_IT   | 8         | 7.41%   |
| en_GB   | 7         | 6.48%   |
| fr_FR   | 5         | 4.63%   |
| es_ES   | 5         | 4.63%   |
| hu_HU   | 4         | 3.7%    |
| ru_RU   | 3         | 2.78%   |
| ja_JP   | 3         | 2.78%   |
| Unknown | 3         | 2.78%   |
| pt_BR   | 2         | 1.85%   |
| pl_PL   | 2         | 1.85%   |
| sv_SE   | 1         | 0.93%   |
| sl_SI   | 1         | 0.93%   |
| sk_SK   | 1         | 0.93%   |
| hr_HR   | 1         | 0.93%   |
| fr_CA   | 1         | 0.93%   |
| es_VE   | 1         | 0.93%   |
| es_PE   | 1         | 0.93%   |
| es_AR   | 1         | 0.93%   |
| en_ZA   | 1         | 0.93%   |
| en_SG   | 1         | 0.93%   |
| en_IE   | 1         | 0.93%   |
| de_CH   | 1         | 0.93%   |
| de_AT   | 1         | 0.93%   |
| C       | 1         | 0.93%   |
| bg_BG   | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 65        | 60.19%  |
| EFI  | 43        | 39.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 105       | 97.22%  |
| Overlay | 2         | 1.85%   |
| Btrfs   | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 59        | 54.13%  |
| GPT     | 49        | 44.95%  |
| Unknown | 1         | 0.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 87.16%  |
| Yes       | 14        | 12.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 72.22%  |
| Yes       | 30        | 27.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 17        | 15.74%  |
| ASUSTek Computer               | 9         | 8.33%   |
| Acer                           | 8         | 7.41%   |
| MSI                            | 7         | 6.48%   |
| Lenovo                         | 7         | 6.48%   |
| Toshiba                        | 6         | 5.56%   |
| ASRock                         | 5         | 4.63%   |
| Apple                          | 5         | 4.63%   |
| Gigabyte Technology            | 4         | 3.7%    |
| Dell                           | 4         | 3.7%    |
| Medion                         | 3         | 2.78%   |
| Intel                          | 3         | 2.78%   |
| Unknown                        | 3         | 2.78%   |
| TrekStor                       | 2         | 1.85%   |
| Sony                           | 2         | 1.85%   |
| IBM                            | 2         | 1.85%   |
| Google                         | 2         | 1.85%   |
| VXL                            | 1         | 0.93%   |
| Visual Land                    | 1         | 0.93%   |
| TECO Electric and Machinery    | 1         | 0.93%   |
| Qilive                         | 1         | 0.93%   |
| Phoenix/SiS                    | 1         | 0.93%   |
| Philco                         | 1         | 0.93%   |
| Panasonic                      | 1         | 0.93%   |
| Packard Bell                   | 1         | 0.93%   |
| Matsushita Electric Industrial | 1         | 0.93%   |
| JVC                            | 1         | 0.93%   |
| Irbis                          | 1         | 0.93%   |
| Fujitsu Siemens                | 1         | 0.93%   |
| Framework                      | 1         | 0.93%   |
| Foxconn                        | 1         | 0.93%   |
| Compaq                         | 1         | 0.93%   |
| Chuwi                          | 1         | 0.93%   |
| Biostar                        | 1         | 0.93%   |
| BESSTAR Tech                   | 1         | 0.93%   |
| AMI                            | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 4         | 3.7%    |
| TrekStor SurfTab wintron 7.0                | 2         | 1.85%   |
| Toshiba Satellite C660                      | 2         | 1.85%   |
| HP ProBook 650 G1                           | 2         | 1.85%   |
| HP 2000                                     | 2         | 1.85%   |
| VXL TC7500D Series                          | 1         | 0.93%   |
| Visual Land Premier 10                      | 1         | 0.93%   |
| Toshiba Satellite Pro L500                  | 1         | 0.93%   |
| Toshiba Satellite M70                       | 1         | 0.93%   |
| Toshiba Satellite L515                      | 1         | 0.93%   |
| Toshiba NB100                               | 1         | 0.93%   |
| TECO Electric and Machinery FUTRO S400      | 1         | 0.93%   |
| Sony VGN-P11Z_Q                             | 1         | 0.93%   |
| Sony VGN-FW21Z                              | 1         | 0.93%   |
| Qilive QW19141AMSP                          | 1         | 0.93%   |
| Phoenix/SiS M720SR                          | 1         | 0.93%   |
| Philco 14I                                  | 1         | 0.93%   |
| Panasonic CF-S10CWHDS                       | 1         | 0.93%   |
| Packard Bell EasyNote LM81                  | 1         | 0.93%   |
| MSI U90/U100                                | 1         | 0.93%   |
| MSI U210                                    | 1         | 0.93%   |
| MSI MS-7C56                                 | 1         | 0.93%   |
| MSI MS-7733                                 | 1         | 0.93%   |
| MSI MS-7597                                 | 1         | 0.93%   |
| MSI MS-7592                                 | 1         | 0.93%   |
| MSI Alpha 17 C7VF                           | 1         | 0.93%   |
| Medion P961x                                | 1         | 0.93%   |
| Medion P6620                                | 1         | 0.93%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 0.93%   |
| Lenovo ThinkPad X201 3249MJJ                | 1         | 0.93%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 0.93%   |
| Lenovo ThinkPad 11e 20DAS0PS00              | 1         | 0.93%   |
| Lenovo IdeaPad S145-15AST 81N3              | 1         | 0.93%   |
| Lenovo IdeaPad 5 14IAL7 82SD                | 1         | 0.93%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 0.93%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 0.93%   |
| JVC J3N                                     | 1         | 0.93%   |
| Irbis NB264                                 | 1         | 0.93%   |
| Intel NUC5CPYB H61145-407                   | 1         | 0.93%   |
| Intel NUC12WSHi7                            | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite                           | 5         | 4.63%   |
| Acer Aspire                                 | 5         | 4.63%   |
| Lenovo IdeaPad                              | 4         | 3.7%    |
| HP ProBook                                  | 4         | 3.7%    |
| Dell Latitude                               | 4         | 3.7%    |
| Unknown                                     | 4         | 3.7%    |
| Lenovo ThinkPad                             | 3         | 2.78%   |
| TrekStor SurfTab                            | 2         | 1.85%   |
| IBM ThinkPad                                | 2         | 1.85%   |
| HP Pavilion                                 | 2         | 1.85%   |
| HP 2000                                     | 2         | 1.85%   |
| ASUS VivoBook                               | 2         | 1.85%   |
| VXL TC7500D                                 | 1         | 0.93%   |
| Visual Land Premier                         | 1         | 0.93%   |
| Toshiba NB100                               | 1         | 0.93%   |
| TECO Electric and Machinery FUTRO           | 1         | 0.93%   |
| Sony VGN-P11Z                               | 1         | 0.93%   |
| Sony VGN-FW21Z                              | 1         | 0.93%   |
| Qilive QW19141AMSP                          | 1         | 0.93%   |
| Phoenix/SiS M720SR                          | 1         | 0.93%   |
| Philco 14I                                  | 1         | 0.93%   |
| Panasonic CF-S10CWHDS                       | 1         | 0.93%   |
| Packard Bell EasyNote                       | 1         | 0.93%   |
| MSI U90                                     | 1         | 0.93%   |
| MSI U210                                    | 1         | 0.93%   |
| MSI MS-7C56                                 | 1         | 0.93%   |
| MSI MS-7733                                 | 1         | 0.93%   |
| MSI MS-7597                                 | 1         | 0.93%   |
| MSI MS-7592                                 | 1         | 0.93%   |
| MSI Alpha                                   | 1         | 0.93%   |
| Medion P961x                                | 1         | 0.93%   |
| Medion P6620                                | 1         | 0.93%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 0.93%   |
| JVC J3N                                     | 1         | 0.93%   |
| Irbis NB264                                 | 1         | 0.93%   |
| Intel NUC5CPYB                              | 1         | 0.93%   |
| Intel NUC12WSHi7                            | 1         | 0.93%   |
| Intel D845GRG                               | 1         | 0.93%   |
| HP Stream                                   | 1         | 0.93%   |
| HP Presario                                 | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 10        | 9.26%   |
| 2010    | 9         | 8.33%   |
| 2020    | 8         | 7.41%   |
| 2013    | 8         | 7.41%   |
| 2011    | 8         | 7.41%   |
| 2012    | 7         | 6.48%   |
| 2008    | 7         | 6.48%   |
| 2018    | 5         | 4.63%   |
| 2016    | 5         | 4.63%   |
| 2005    | 5         | 4.63%   |
| 2015    | 4         | 3.7%    |
| 2014    | 4         | 3.7%    |
| 2007    | 4         | 3.7%    |
| 2023    | 3         | 2.78%   |
| 2022    | 3         | 2.78%   |
| 2019    | 3         | 2.78%   |
| 2017    | 3         | 2.78%   |
| 2021    | 2         | 1.85%   |
| 2006    | 2         | 1.85%   |
| 2004    | 2         | 1.85%   |
| 2002    | 2         | 1.85%   |
| Unknown | 2         | 1.85%   |
| 2024    | 1         | 0.93%   |
| 2003    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 72        | 66.67%  |
| Desktop     | 26        | 24.07%  |
| Tablet      | 3         | 2.78%   |
| Convertible | 3         | 2.78%   |
| Mini pc     | 3         | 2.78%   |
| All in one  | 1         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 102       | 94.44%  |
| Enabled  | 6         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 98.15%  |
| Yes  | 2         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 34        | 31.48%  |
| 4.01-8.0    | 15        | 13.89%  |
| 2.01-3.0    | 14        | 12.96%  |
| 1.01-2.0    | 11        | 10.19%  |
| 8.01-16.0   | 9         | 8.33%   |
| 0.51-1.0    | 8         | 7.41%   |
| 16.01-24.0  | 6         | 5.56%   |
| 0.01-0.5    | 5         | 4.63%   |
| 64.01-256.0 | 3         | 2.78%   |
| 32.01-64.0  | 2         | 1.85%   |
| 24.01-32.0  | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 47        | 42.34%  |
| 0.51-1.0  | 24        | 21.62%  |
| 2.01-3.0  | 18        | 16.22%  |
| 0.01-0.5  | 10        | 9.01%   |
| 4.01-8.0  | 7         | 6.31%   |
| 3.01-4.0  | 4         | 3.6%    |
| 8.01-16.0 | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 74.55%  |
| 2      | 19        | 17.27%  |
| 3      | 8         | 7.27%   |
| 4      | 1         | 0.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 55.96%  |
| Yes       | 48        | 44.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 79.63%  |
| No        | 22        | 20.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 78.7%   |
| No        | 23        | 21.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 58.72%  |
| Yes       | 45        | 41.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 21        | 19.44%  |
| Italy        | 9         | 8.33%   |
| Germany      | 8         | 7.41%   |
| UK           | 7         | 6.48%   |
| Switzerland  | 4         | 3.7%    |
| Spain        | 4         | 3.7%    |
| Hungary      | 4         | 3.7%    |
| France       | 4         | 3.7%    |
| Russia       | 3         | 2.78%   |
| Poland       | 3         | 2.78%   |
| Kenya        | 3         | 2.78%   |
| Japan        | 3         | 2.78%   |
| Brazil       | 3         | 2.78%   |
| Venezuela    | 2         | 1.85%   |
| Turkey       | 2         | 1.85%   |
| Slovenia     | 2         | 1.85%   |
| Romania      | 2         | 1.85%   |
| Netherlands  | 2         | 1.85%   |
| Mexico       | 2         | 1.85%   |
| Croatia      | 2         | 1.85%   |
| Canada       | 2         | 1.85%   |
| Belgium      | 2         | 1.85%   |
| Argentina    | 2         | 1.85%   |
| Sweden       | 1         | 0.93%   |
| South Africa | 1         | 0.93%   |
| Slovakia     | 1         | 0.93%   |
| Singapore    | 1         | 0.93%   |
| Saudi Arabia | 1         | 0.93%   |
| Qatar        | 1         | 0.93%   |
| Peru         | 1         | 0.93%   |
| Egypt        | 1         | 0.93%   |
| Bulgaria     | 1         | 0.93%   |
| Belarus      | 1         | 0.93%   |
| Austria      | 1         | 0.93%   |
| Algeria      | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Jacksonville          | 11        | 10.19%  |
| Tokyo                 | 3         | 2.78%   |
| Nairobi               | 3         | 2.78%   |
| Zurich                | 2         | 1.85%   |
| Swindon               | 2         | 1.85%   |
| Rostock               | 2         | 1.85%   |
| Morelia               | 2         | 1.85%   |
| Mesa                  | 2         | 1.85%   |
| Ljubljana             | 2         | 1.85%   |
| Drobeta-Turnu Severin | 2         | 1.85%   |
| Budapest              | 2         | 1.85%   |
| Bologna               | 2         | 1.85%   |
| Zweidlen-Dorf         | 1         | 0.93%   |
| Zagreb                | 1         | 0.93%   |
| West Corinth          | 1         | 0.93%   |
| Volgograd             | 1         | 0.93%   |
| Vienna                | 1         | 0.93%   |
| Toalmas               | 1         | 0.93%   |
| The Hague             | 1         | 0.93%   |
| Tenbury Wells         | 1         | 0.93%   |
| Tellico Plains        | 1         | 0.93%   |
| Sosnowiec             | 1         | 0.93%   |
| Solingen              | 1         | 0.93%   |
| Sofia                 | 1         | 0.93%   |
| Sint-Pieters-Leeuw    | 1         | 0.93%   |
| Singapore             | 1         | 0.93%   |
| Sétif                | 1         | 0.93%   |
| Schermbeck            | 1         | 0.93%   |
| Savona                | 1         | 0.93%   |
| Sao Pedro da Aldeia   | 1         | 0.93%   |
| San Carlos del Zulia  | 1         | 0.93%   |
| Salsomaggiore Terme   | 1         | 0.93%   |
| Rostov-on-Don         | 1         | 0.93%   |
| Rome                  | 1         | 0.93%   |
| Rochdale              | 1         | 0.93%   |
| Rijeka                | 1         | 0.93%   |
| Puerto Cumarebo       | 1         | 0.93%   |
| Posadas               | 1         | 0.93%   |
| Osnabrück            | 1         | 0.93%   |
| Nasr                  | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 20     | 14.5%   |
| Seagate             | 15        | 18     | 11.45%  |
| Unknown             | 13        | 13     | 9.92%   |
| Samsung Electronics | 13        | 15     | 9.92%   |
| SanDisk             | 8         | 10     | 6.11%   |
| Kingston            | 8         | 9      | 6.11%   |
| Toshiba             | 6         | 6      | 4.58%   |
| Hitachi             | 6         | 7      | 4.58%   |
| China               | 5         | 6      | 3.82%   |
| SUNEAST             | 3         | 5      | 2.29%   |
| HGST                | 3         | 3      | 2.29%   |
| Fujitsu             | 3         | 3      | 2.29%   |
| Crucial             | 3         | 4      | 2.29%   |
| Apple               | 3         | 3      | 2.29%   |
| A-DATA Technology   | 3         | 3      | 2.29%   |
| KESU                | 2         | 2      | 1.53%   |
| Unknown             | 2         | 2      | 1.53%   |
| WDC WDS5            | 1         | 1      | 0.76%   |
| USB3.0              | 1         | 1      | 0.76%   |
| USB                 | 1         | 1      | 0.76%   |
| Unknown (CF)        | 1         | 1      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| Silicon Motion      | 1         | 1      | 0.76%   |
| PNY                 | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 1      | 0.76%   |
| Maxtor              | 1         | 1      | 0.76%   |
| KIOXIA              | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| KBG40ZNV            | 1         | 1      | 0.76%   |
| IBM/Hitachi         | 1         | 2      | 0.76%   |
| HEYGATE             | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 3         | 2.19%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.46%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.46%   |
| Unknown S0J59X  128GB                | 2         | 1.46%   |
| Unknown NCard  16GB                  | 2         | 1.46%   |
| Unknown G1J38E  64GB                 | 2         | 1.46%   |
| SUNEAST SE900 SSD 128GB              | 2         | 1.46%   |
| SanDisk SDSSDA120G 120GB             | 2         | 1.46%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.46%   |
| KESU USB 3.1 256GB                   | 2         | 1.46%   |
| A-DATA SU630 240GB SSD               | 2         | 1.46%   |
| Unknown                              | 2         | 1.46%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.73%   |
| WDC WDS5 00G2B0C-00PX 500GB SSD      | 1         | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.73%   |
| WDC WD800BD-22MRA1 80GB              | 1         | 0.73%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.73%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 0.73%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.73%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.73%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.73%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 0.73%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 0.73%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 0.73%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 0.73%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.73%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.73%   |
| USB3.0 Super Speed 500GB SSD         | 1         | 0.73%   |
| USB 3.1 320GB                        | 1         | 0.73%   |
| Unknown USDU1  32GB                  | 1         | 0.73%   |
| Unknown SLD64G  64GB                 | 1         | 0.73%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 0.73%   |
| Unknown MMC Card  64GB               | 1         | 0.73%   |
| Unknown MBG4GC  32GB                 | 1         | 0.73%   |
| Unknown HAG2e  16GB                  | 1         | 0.73%   |
| Unknown 064G38  64GB                 | 1         | 0.73%   |
| Unknown (CF) Card 4GB                | 1         | 0.73%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 0.73%   |
| Toshiba MK8032GAX 80GB               | 1         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 29.09%  |
| Seagate             | 13        | 16     | 23.64%  |
| Toshiba             | 6         | 6      | 10.91%  |
| Hitachi             | 6         | 7      | 10.91%  |
| HGST                | 3         | 3      | 5.45%   |
| Fujitsu             | 3         | 3      | 5.45%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| USB                 | 1         | 1      | 1.82%   |
| Unknown (CF)        | 1         | 1      | 1.82%   |
| Unknown             | 1         | 1      | 1.82%   |
| Maxtor              | 1         | 1      | 1.82%   |
| IBM/Hitachi         | 1         | 2      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 9      | 18.6%   |
| Samsung Electronics | 6         | 6      | 13.95%  |
| SanDisk             | 5         | 7      | 11.63%  |
| China               | 5         | 6      | 11.63%  |
| SUNEAST             | 3         | 5      | 6.98%   |
| WDC                 | 2         | 2      | 4.65%   |
| Crucial             | 2         | 2      | 4.65%   |
| Apple               | 2         | 2      | 4.65%   |
| A-DATA Technology   | 2         | 2      | 4.65%   |
| WDC WDS5            | 1         | 1      | 2.33%   |
| USB3.0              | 1         | 1      | 2.33%   |
| Transcend           | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| HEYGATE             | 1         | 1      | 2.33%   |
| Unknown             | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 61     | 41.46%  |
| SSD     | 40        | 49     | 32.52%  |
| MMC     | 16        | 16     | 13.01%  |
| NVMe    | 12        | 16     | 9.76%   |
| Unknown | 4         | 4      | 3.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 105    | 69.42%  |
| MMC  | 16        | 16     | 13.22%  |
| NVMe | 12        | 15     | 9.92%   |
| SAS  | 9         | 10     | 7.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 93     | 83.15%  |
| 0.51-1.0   | 12        | 14     | 13.48%  |
| 4.01-10.0  | 2         | 2      | 2.25%   |
| 1.01-2.0   | 1         | 1      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 28.44%  |
| 51-100         | 23        | 21.1%   |
| 251-500        | 19        | 17.43%  |
| 21-50          | 10        | 9.17%   |
| 1-20           | 10        | 9.17%   |
| 501-1000       | 8         | 7.34%   |
| 1001-2000      | 5         | 4.59%   |
| More than 3000 | 2         | 1.83%   |
| Unknown        | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 67.57%  |
| 21-50          | 18        | 16.22%  |
| 51-100         | 6         | 5.41%   |
| 251-500        | 5         | 4.5%    |
| 101-250        | 3         | 2.7%    |
| 501-1000       | 2         | 1.8%    |
| More than 3000 | 1         | 0.9%    |
| Unknown        | 1         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1         | 1      | 4%      |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 4%      |
| WDC WD400BD-23JMC0 40GB           | 1         | 1      | 4%      |
| WDC WD2500BEVT-60A23T0 250GB      | 1         | 1      | 4%      |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 4%      |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 4%      |
| WDC WD10EARS-00Y5B1 1TB           | 1         | 1      | 4%      |
| Toshiba MK3252GSX 320GB           | 1         | 1      | 4%      |
| Toshiba MK1252GSX 120GB           | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB         | 1         | 1      | 4%      |
| Seagate ST9120822AS 120GB         | 1         | 1      | 4%      |
| Seagate ST3320820SCE 320GB        | 1         | 2      | 4%      |
| Samsung Electronics HM080GC 80GB  | 1         | 1      | 4%      |
| PNY 1TB SATA SSD                  | 1         | 1      | 4%      |
| Maxtor 6Y080L0 82GB               | 1         | 1      | 4%      |
| Kingston SA400S37240G 240GB SSD   | 1         | 1      | 4%      |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1         | 2      | 4%      |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 4%      |
| Hitachi HTS543225L9SA00 250GB     | 1         | 1      | 4%      |
| Hitachi DK23CA-20 20GB            | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 4%      |
| HGST HTS545032A7E380 320GB        | 1         | 1      | 4%      |
| HGST HTS541075A9E680 752GB        | 1         | 1      | 4%      |
| Fujitsu MHZ2160BH G2 160GB        | 1         | 1      | 4%      |
| Fujitsu MHY2080BH 80GB            | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 28%     |
| Seagate             | 3         | 4      | 12%     |
| Hitachi             | 3         | 3      | 12%     |
| HGST                | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Fujitsu             | 2         | 2      | 8%      |
| Samsung Electronics | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| Maxtor              | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| IBM/Hitachi         | 1         | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 27.27%  |
| Seagate             | 3         | 4      | 13.64%  |
| Hitachi             | 3         | 3      | 13.64%  |
| HGST                | 3         | 3      | 13.64%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Fujitsu             | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Maxtor              | 1         | 1      | 4.55%   |
| IBM/Hitachi         | 1         | 2      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 87.5%   |
| SSD  | 3         | 3      | 12.5%   |

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
| Works    | 71        | 94     | 60.17%  |
| Malfunc  | 24        | 27     | 20.34%  |
| Detected | 23        | 25     | 19.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 71        | 62.83%  |
| AMD                              | 16        | 14.16%  |
| Silicon Integrated Systems [SiS] | 5         | 4.42%   |
| Samsung Electronics              | 4         | 3.54%   |
| SanDisk                          | 3         | 2.65%   |
| Marvell Technology Group         | 3         | 2.65%   |
| VIA Technologies                 | 2         | 1.77%   |
| Micron/Crucial Technology        | 2         | 1.77%   |
| Silicon Motion                   | 1         | 0.88%   |
| Phison Electronics               | 1         | 0.88%   |
| Nvidia                           | 1         | 0.88%   |
| KIOXIA                           | 1         | 0.88%   |
| JMicron Technology               | 1         | 0.88%   |
| ASMedia Technology               | 1         | 0.88%   |
| ADATA Technology                 | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 8.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 5.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 5.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 4.48%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 5         | 3.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 3.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.99%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 3         | 2.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 2.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.24%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 2.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.49%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.49%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.49%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 2         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 1.49%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 0.75%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 0.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.75%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 0.75%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.75%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.75%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.75%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.75%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 68        | 57.14%  |
| IDE  | 36        | 30.25%  |
| NVMe | 11        | 9.24%   |
| RAID | 4         | 3.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 84        | 77.78%  |
| AMD          | 23        | 21.3%   |
| CentaurHauls | 1         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 3.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 2.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.78%   |
| Intel Atom CPU Z3735G @ 1.33GHz             | 3         | 2.78%   |
| Intel Pentium M processor 1.70GHz           | 2         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.85%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 1.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.85%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 1.85%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.85%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 1.85%   |
| AMD Phenom II X6 1055T Processor            | 2         | 1.85%   |
| AMD E-300 APU with Radeon HD Graphics       | 2         | 1.85%   |
| AMD C-70 APU with Radeon HD Graphics        | 2         | 1.85%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.93%   |
| Intel Pentium M processor 1000MHz           | 1         | 0.93%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.93%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.93%   |
| Intel Pentium III (Coppermine)              | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.93%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 0.93%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.93%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 0.93%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 0.93%   |
| Intel Pentium 4 CPU 1.80GHz                 | 1         | 0.93%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.93%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 0.93%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 0.93%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.93%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 0.93%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.93%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 12.96%  |
| Intel Celeron           | 14        | 12.96%  |
| Intel Atom              | 14        | 12.96%  |
| Intel Core 2 Duo        | 10        | 9.26%   |
| Intel Core i3           | 6         | 5.56%   |
| Intel Pentium M         | 5         | 4.63%   |
| Other                   | 4         | 3.7%    |
| Intel Pentium Dual-Core | 4         | 3.7%    |
| Intel Pentium 4         | 4         | 3.7%    |
| AMD Ryzen 7             | 3         | 2.78%   |
| Intel Genuine           | 2         | 1.85%   |
| Intel Core i7           | 2         | 1.85%   |
| AMD Phenom II X6        | 2         | 1.85%   |
| AMD E                   | 2         | 1.85%   |
| AMD C-70                | 2         | 1.85%   |
| AMD Athlon              | 2         | 1.85%   |
| AMD A4                  | 2         | 1.85%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium III       | 1         | 0.93%   |
| Intel Pentium           | 1         | 0.93%   |
| Intel Core m3           | 1         | 0.93%   |
| Intel Core 2            | 1         | 0.93%   |
| CentaurHauls VIA Eden   | 1         | 0.93%   |
| AMD V120                | 1         | 0.93%   |
| AMD Ryzen 9             | 1         | 0.93%   |
| AMD Ryzen 7 PRO         | 1         | 0.93%   |
| AMD Ryzen 5 PRO         | 1         | 0.93%   |
| AMD Ryzen 5             | 1         | 0.93%   |
| AMD Mobile Sempron      | 1         | 0.93%   |
| AMD Athlon Neo          | 1         | 0.93%   |
| AMD Athlon II X2        | 1         | 0.93%   |
| AMD A8                  | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 52.78%  |
| 1      | 22        | 20.37%  |
| 4      | 19        | 17.59%  |
| 8      | 3         | 2.78%   |
| 6      | 3         | 2.78%   |
| 16     | 2         | 1.85%   |
| 12     | 2         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 62.04%  |
| 2      | 41        | 37.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 88        | 81.48%  |
| 32-bit         | 20        | 18.52%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 11.93%  |
| 0x106c2    | 7         | 6.42%   |
| 0x206a7    | 6         | 5.5%    |
| 0x1067a    | 6         | 5.5%    |
| 0x30678    | 5         | 4.59%   |
| 0x6fd      | 4         | 3.67%   |
| 0x40651    | 4         | 3.67%   |
| 0x306a9    | 4         | 3.67%   |
| 0x706a8    | 3         | 2.75%   |
| 0x706a1    | 3         | 2.75%   |
| 0x406c4    | 3         | 2.75%   |
| 0x306c3    | 3         | 2.75%   |
| 0x10676    | 3         | 2.75%   |
| 0x05000119 | 3         | 2.75%   |
| 0xf27      | 2         | 1.83%   |
| 0x906a3    | 2         | 1.83%   |
| 0x806e9    | 2         | 1.83%   |
| 0x6e8      | 2         | 1.83%   |
| 0x406c3    | 2         | 1.83%   |
| 0x20655    | 2         | 1.83%   |
| 0x0810100b | 2         | 1.83%   |
| 0x06006705 | 2         | 1.83%   |
| 0x010000dc | 2         | 1.83%   |
| 0x010000c8 | 2         | 1.83%   |
| 0xf49      | 1         | 0.92%   |
| 0xf12      | 1         | 0.92%   |
| 0xb0671    | 1         | 0.92%   |
| 0x806c1    | 1         | 0.92%   |
| 0x6fb      | 1         | 0.92%   |
| 0x6f6      | 1         | 0.92%   |
| 0x6d8      | 1         | 0.92%   |
| 0x6d6      | 1         | 0.92%   |
| 0x695      | 1         | 0.92%   |
| 0x68a      | 1         | 0.92%   |
| 0x506c9    | 1         | 0.92%   |
| 0x406e3    | 1         | 0.92%   |
| 0x30661    | 1         | 0.92%   |
| 0x0a704103 | 1         | 0.92%   |
| 0x0a601203 | 1         | 0.92%   |
| 0x08701013 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 11        | 10.19%  |
| Penryn           | 9         | 8.33%   |
| Bonnell          | 9         | 8.33%   |
| P6               | 8         | 7.41%   |
| SandyBridge      | 7         | 6.48%   |
| Haswell          | 7         | 6.48%   |
| Goldmont plus    | 7         | 6.48%   |
| Core             | 6         | 5.56%   |
| NetBurst         | 4         | 3.7%    |
| K10              | 4         | 3.7%    |
| IvyBridge        | 4         | 3.7%    |
| Bobcat           | 4         | 3.7%    |
| Unknown          | 4         | 3.7%    |
| Zen+             | 2         | 1.85%   |
| Zen 2            | 2         | 1.85%   |
| Zen              | 2         | 1.85%   |
| Westmere         | 2         | 1.85%   |
| KabyLake         | 2         | 1.85%   |
| K8 Hammer        | 2         | 1.85%   |
| Goldmont         | 2         | 1.85%   |
| Excavator        | 2         | 1.85%   |
| Alderlake Hybrid | 2         | 1.85%   |
| TigerLake        | 1         | 0.93%   |
| Skylake          | 1         | 0.93%   |
| Puma             | 1         | 0.93%   |
| Piledriver       | 1         | 0.93%   |
| Nehalem          | 1         | 0.93%   |
| K6               | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 60.53%  |
| AMD                              | 25        | 21.93%  |
| Nvidia                           | 13        | 11.4%   |
| Silicon Integrated Systems [SiS] | 5         | 4.39%   |
| VIA Technologies                 | 1         | 0.88%   |
| S3 Graphics                      | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 6         | 4.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                        | 6         | 4.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 6         | 4.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 6         | 4.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 5         | 4%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 4         | 3.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 4         | 3.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 4         | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 4         | 3.2%    |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 2.4%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 3         | 2.4%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                           | 3         | 2.4%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 2         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 2         | 1.6%    |
| Intel HD Graphics 500                                                                      | 2         | 1.6%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 2         | 1.6%    |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 2         | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 1.6%    |
| AMD Wrestler [Radeon HD 7290]                                                              | 2         | 1.6%    |
| AMD Wrestler [Radeon HD 6310]                                                              | 2         | 1.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 2         | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 1.6%    |
| AMD Juniper XT [Radeon HD 5770]                                                            | 2         | 1.6%    |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 0.8%    |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 0.8%    |
| Nvidia GT216M [GeForce GT 330M]                                                            | 1         | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                                            | 1         | 0.8%    |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 0.8%    |
| Nvidia GK107 [GeForce GT 640]                                                              | 1         | 0.8%    |
| Nvidia GK106 [GeForce GTX 660]                                                             | 1         | 0.8%    |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 0.8%    |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 0.8%    |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 0.8%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 56        | 51.38%  |
| 1 x AMD         | 22        | 20.18%  |
| 1 x Nvidia      | 10        | 9.17%   |
| 2 x Intel       | 8         | 7.34%   |
| 1 x SiS         | 5         | 4.59%   |
| Intel + Nvidia  | 2         | 1.83%   |
| Intel + AMD     | 2         | 1.83%   |
| Other           | 1         | 0.92%   |
| 1 x VIA         | 1         | 0.92%   |
| 1 x S3 Graphics | 1         | 0.92%   |
| AMD + Nvidia    | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 92        | 85.19%  |
| Unknown     | 9         | 8.33%   |
| Proprietary | 7         | 6.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 67.57%  |
| 0.01-0.5   | 22        | 19.82%  |
| 1.01-2.0   | 7         | 6.31%   |
| 0.51-1.0   | 5         | 4.5%    |
| 7.01-8.0   | 1         | 0.9%    |
| 3.01-4.0   | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 18.48%  |
| Samsung Electronics     | 13        | 14.13%  |
| Chimei Innolux          | 9         | 9.78%   |
| LG Display              | 7         | 7.61%   |
| BOE                     | 7         | 7.61%   |
| Dell                    | 5         | 5.43%   |
| Philips                 | 4         | 4.35%   |
| Apple                   | 4         | 4.35%   |
| NEC Computers           | 2         | 2.17%   |
| Hewlett-Packard         | 2         | 2.17%   |
| HannStar                | 2         | 2.17%   |
| CPT                     | 2         | 2.17%   |
| Chi Mei Optoelectronics | 2         | 2.17%   |
| AOC                     | 2         | 2.17%   |
| ViewSonic               | 1         | 1.09%   |
| VIE                     | 1         | 1.09%   |
| Orion                   | 1         | 1.09%   |
| MQP                     | 1         | 1.09%   |
| Medion                  | 1         | 1.09%   |
| LG Philips              | 1         | 1.09%   |
| Lenovo                  | 1         | 1.09%   |
| InfoVision              | 1         | 1.09%   |
| Iiyama                  | 1         | 1.09%   |
| Goldstar                | 1         | 1.09%   |
| Fujitsu Siemens         | 1         | 1.09%   |
| CSO                     | 1         | 1.09%   |
| Ancor Communications    | 1         | 1.09%   |
| Acer                    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 3.26%   |
| NEC Computers AS223WM NEC690A 1920x1080 476x267mm 21.5-inch             | 2         | 2.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 2         | 2.17%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 1.09%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 1.09%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1         | 1.09%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 1.09%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 1.09%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 340x190mm 15.3-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 1.09%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                     | 1         | 1.09%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 1.09%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                    | 1         | 1.09%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch              | 1         | 1.09%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 1.09%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD01E6 1366x768 309x174mm 14.0-inch             | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.09%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch            | 1         | 1.09%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1         | 1.09%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch              | 1         | 1.09%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1         | 1.09%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch               | 1         | 1.09%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 1.09%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 1.09%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch     | 1         | 1.09%   |
| Dell UP2715K DEL40B6 2560x1440 600x340mm 27.2-inch                      | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 30        | 32.97%  |
| 1920x1080 (FHD)    | 26        | 28.57%  |
| 1280x800 (WXGA)    | 8         | 8.79%   |
| 1920x1200 (WUXGA)  | 5         | 5.49%   |
| 1600x900 (HD+)     | 5         | 5.49%   |
| 1024x600           | 4         | 4.4%    |
| 3840x2160 (4K)     | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 800x600            | 1         | 1.1%    |
| 3440x1440          | 1         | 1.1%    |
| 2560x1440 (QHD)    | 1         | 1.1%    |
| 2256x1504          | 1         | 1.1%    |
| 2160x1440          | 1         | 1.1%    |
| 1920x540           | 1         | 1.1%    |
| 1680x1050 (WSXGA+) | 1         | 1.1%    |
| 1440x900 (WXGA+)   | 1         | 1.1%    |
| 1024x768 (XGA)     | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 28.26%  |
| 13      | 11        | 11.96%  |
| 11      | 9         | 9.78%   |
| 24      | 8         | 8.7%    |
| 21      | 6         | 6.52%   |
| 14      | 6         | 6.52%   |
| 17      | 4         | 4.35%   |
| 12      | 4         | 4.35%   |
| 10      | 3         | 3.26%   |
| 27      | 2         | 2.17%   |
| 23      | 2         | 2.17%   |
| 54      | 1         | 1.09%   |
| 46      | 1         | 1.09%   |
| 40      | 1         | 1.09%   |
| 34      | 1         | 1.09%   |
| 31      | 1         | 1.09%   |
| 22      | 1         | 1.09%   |
| 20      | 1         | 1.09%   |
| 19      | 1         | 1.09%   |
| 18      | 1         | 1.09%   |
| 8       | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 41.76%  |
| 201-300     | 21        | 23.08%  |
| 501-600     | 11        | 12.09%  |
| 401-500     | 9         | 9.89%   |
| 351-400     | 4         | 4.4%    |
| 601-700     | 2         | 2.2%    |
| 1001-1500   | 2         | 2.2%    |
| 801-900     | 1         | 1.1%    |
| 701-800     | 1         | 1.1%    |
| 101-200     | 1         | 1.1%    |
| Unknown     | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 73.86%  |
| 16/10 | 14        | 15.91%  |
| 3/2   | 3         | 3.41%   |
| 5/4   | 2         | 2.27%   |
| 4/3   | 2         | 2.27%   |
| 32/9  | 1         | 1.14%   |
| 21/9  | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 28.26%  |
| 81-90          | 15        | 16.3%   |
| 201-250        | 10        | 10.87%  |
| 51-60          | 9         | 9.78%   |
| 251-300        | 5         | 5.43%   |
| 151-200        | 4         | 4.35%   |
| 71-80          | 3         | 3.26%   |
| 61-70          | 3         | 3.26%   |
| 41-50          | 3         | 3.26%   |
| 141-150        | 3         | 3.26%   |
| 351-500        | 2         | 2.17%   |
| 301-350        | 2         | 2.17%   |
| 121-130        | 2         | 2.17%   |
| 501-1000       | 2         | 2.17%   |
| More than 1000 | 1         | 1.09%   |
| 1-40           | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 37        | 40.22%  |
| 51-100  | 25        | 27.17%  |
| 121-160 | 19        | 20.65%  |
| 161-240 | 7         | 7.61%   |
| 1-50    | 3         | 3.26%   |
| Unknown | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 89.81%  |
| 0     | 6         | 5.56%   |
| 2     | 4         | 3.7%    |
| 3     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 64        | 39.02%  |
| Intel                            | 32        | 19.51%  |
| Qualcomm Atheros                 | 21        | 12.8%   |
| Broadcom                         | 14        | 8.54%   |
| Marvell Technology Group         | 6         | 3.66%   |
| Broadcom Limited                 | 6         | 3.66%   |
| Silicon Integrated Systems [SiS] | 4         | 2.44%   |
| Ralink Technology                | 3         | 1.83%   |
| Samsung Electronics              | 2         | 1.22%   |
| Xiaomi                           | 1         | 0.61%   |
| Ralink                           | 1         | 0.61%   |
| Qualcomm Technologies            | 1         | 0.61%   |
| Motorola PCS                     | 1         | 0.61%   |
| MediaTek                         | 1         | 0.61%   |
| LG Electronics                   | 1         | 0.61%   |
| JMicron Technology               | 1         | 0.61%   |
| IBM                              | 1         | 0.61%   |
| Guillemot                        | 1         | 0.61%   |
| Google                           | 1         | 0.61%   |
| D-Link System                    | 1         | 0.61%   |
| Accton Technology                | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 24        | 12.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 9.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.15%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 1.61%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.08%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.08%   |
| Intel Wireless 7265                                                     | 2         | 1.08%   |
| Intel Wireless 3165                                                     | 2         | 1.08%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.54%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 31.03%  |
| Realtek Semiconductor | 21        | 24.14%  |
| Qualcomm Atheros      | 20        | 22.99%  |
| Broadcom              | 7         | 8.05%   |
| Broadcom Limited      | 4         | 4.6%    |
| Ralink Technology     | 3         | 3.45%   |
| Ralink                | 1         | 1.15%   |
| Qualcomm Technologies | 1         | 1.15%   |
| MediaTek              | 1         | 1.15%   |
| Guillemot             | 1         | 1.15%   |
| D-Link System         | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 6.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 5.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 5.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.6%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 4.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 2.3%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.3%    |
| Intel Wireless 7265                                                     | 2         | 2.3%    |
| Intel Wireless 3165                                                     | 2         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 2.3%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 2.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.15%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.15%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.15%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 1.15%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 1.15%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1         | 1.15%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.15%   |
| Intel Wireless 7260                                                     | 1         | 1.15%   |
| Intel WiFi Link 5100                                                    | 1         | 1.15%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.15%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 51        | 57.3%   |
| Intel                            | 12        | 13.48%  |
| Broadcom                         | 7         | 7.87%   |
| Marvell Technology Group         | 6         | 6.74%   |
| Silicon Integrated Systems [SiS] | 3         | 3.37%   |
| Qualcomm Atheros                 | 2         | 2.25%   |
| Broadcom Limited                 | 2         | 2.25%   |
| Xiaomi                           | 1         | 1.12%   |
| Motorola PCS                     | 1         | 1.12%   |
| LG Electronics                   | 1         | 1.12%   |
| JMicron Technology               | 1         | 1.12%   |
| Google                           | 1         | 1.12%   |
| Accton Technology                | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 26.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 20.22%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 3.37%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 2         | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 2.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 2.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 2.25%   |
| Intel Ethernet Connection I217-V                                       | 2         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.12%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.12%   |
| Motorola PCS moto g84 5G                                               | 1         | 1.12%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.12%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1         | 1.12%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.12%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                    | 1         | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.12%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.12%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.12%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.12%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                     | 1         | 1.12%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                     | 1         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.12%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.12%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 1         | 1.12%   |
| Google Pixel 6                                                         | 1         | 1.12%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.12%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.12%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.12%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.12%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 1         | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.12%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.12%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 86        | 47.78%  |
| WiFi     | 84        | 46.67%  |
| Modem    | 9         | 5%      |
| Unknown  | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 60.95%  |
| Ethernet | 41        | 39.05%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 52.78%  |
| 1     | 43        | 39.81%  |
| 0     | 6         | 5.56%   |
| 3     | 2         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 73.15%  |
| Yes  | 29        | 26.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 23.91%  |
| Realtek Semiconductor           | 9         | 19.57%  |
| Qualcomm Atheros Communications | 7         | 15.22%  |
| Apple                           | 4         | 8.7%    |
| IMC Networks                    | 3         | 6.52%   |
| Cambridge Silicon Radio         | 2         | 4.35%   |
| Alps Electric                   | 2         | 4.35%   |
| Toshiba                         | 1         | 2.17%   |
| MediaTek                        | 1         | 2.17%   |
| Lite-On Technology              | 1         | 2.17%   |
| Hewlett-Packard                 | 1         | 2.17%   |
| Foxconn / Hon Hai               | 1         | 2.17%   |
| Dell                            | 1         | 2.17%   |
| Broadcom                        | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 8         | 17.39%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 10.87%  |
| Intel Bluetooth wireless interface                  | 5         | 10.87%  |
| Intel AX200 Bluetooth                               | 3         | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.35%   |
| IMC Networks Bluetooth Radio                        | 2         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.35%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 4.35%   |
| Toshiba Askey for                                   | 1         | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.17%   |
| MediaTek Wireless_Device                            | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.17%   |
| Intel AX211 Bluetooth                               | 1         | 2.17%   |
| Intel AX210 Bluetooth                               | 1         | 2.17%   |
| IMC Networks Bluetooth Module                       | 1         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.17%   |
| Dell Wireless 360 Bluetooth                         | 1         | 2.17%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.17%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.17%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.17%   |
| Apple Bluetooth Host Controller                     | 1         | 2.17%   |
| Apple Bluetooth HCI                                 | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 74        | 63.25%  |
| AMD                              | 25        | 21.37%  |
| Nvidia                           | 10        | 8.55%   |
| Silicon Integrated Systems [SiS] | 4         | 3.42%   |
| VIA Technologies                 | 1         | 0.85%   |
| Shenzhen Rapoo Technology        | 1         | 0.85%   |
| Logitech                         | 1         | 0.85%   |
| ESS Technology                   | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 7.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 4.17%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 6         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.47%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.78%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 2.78%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.08%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 3         | 2.08%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 2.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.39%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.39%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.39%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 1.39%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.39%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.69%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.69%   |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1         | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 34        | 29.31%  |
| Samsung Electronics | 21        | 18.1%   |
| SK hynix            | 16        | 13.79%  |
| Kingston            | 10        | 8.62%   |
| Elpida              | 7         | 6.03%   |
| Unknown (ABCD)      | 5         | 4.31%   |
| Micron Technology   | 3         | 2.59%   |
| Crucial             | 3         | 2.59%   |
| A-DATA Technology   | 3         | 2.59%   |
| Unknown             | 3         | 2.59%   |
| Team                | 2         | 1.72%   |
| Corsair             | 2         | 1.72%   |
| Transcend           | 1         | 0.86%   |
| Toshiba             | 1         | 0.86%   |
| Teikon              | 1         | 0.86%   |
| S                   | 1         | 0.86%   |
| Ramaxel Technology  | 1         | 0.86%   |
| M                   | 1         | 0.86%   |
| G.Skill             | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 7         | 5.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 4.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.48%   |
| Unknown                                                          | 3         | 2.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.65%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.65%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 1.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.65%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 0.83%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.83%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.83%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.83%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 0.83%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.83%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.83%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 0.83%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 0.83%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 1         | 0.83%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 1         | 0.83%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 0.83%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.83%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 37.61%  |
| DDR4    | 19        | 17.43%  |
| DDR2    | 19        | 17.43%  |
| SDRAM   | 9         | 8.26%   |
| DDR     | 7         | 6.42%   |
| LPDDR4  | 5         | 4.59%   |
| Unknown | 3         | 2.75%   |
| LPDDR3  | 2         | 1.83%   |
| DRAM    | 2         | 1.83%   |
| DDR5    | 2         | 1.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 75%     |
| DIMM         | 23        | 21.3%   |
| Row Of Chips | 2         | 1.85%   |
| Unknown      | 2         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 33        | 28.7%   |
| 4096  | 30        | 26.09%  |
| 8192  | 22        | 19.13%  |
| 1024  | 17        | 14.78%  |
| 512   | 6         | 5.22%   |
| 32768 | 3         | 2.61%   |
| 16384 | 3         | 2.61%   |
| 256   | 1         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 19.09%  |
| Unknown | 19        | 17.27%  |
| 2400    | 8         | 7.27%   |
| 1333    | 8         | 7.27%   |
| 667     | 7         | 6.36%   |
| 3200    | 6         | 5.45%   |
| 1067    | 6         | 5.45%   |
| 2667    | 5         | 4.55%   |
| 1334    | 5         | 4.55%   |
| 1867    | 3         | 2.73%   |
| 533     | 3         | 2.73%   |
| 266     | 3         | 2.73%   |
| 5600    | 2         | 1.82%   |
| 3600    | 2         | 1.82%   |
| 3266    | 2         | 1.82%   |
| 1066    | 2         | 1.82%   |
| 800     | 2         | 1.82%   |
| 4199    | 1         | 0.91%   |
| 2666    | 1         | 0.91%   |
| 2133    | 1         | 0.91%   |
| 2048    | 1         | 0.91%   |
| 1800    | 1         | 0.91%   |
| 400     | 1         | 0.91%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon MF4100 series    | 1         | 50%     |
| Brother HL-1110 series | 1         | 50%     |

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
| Chicony Electronics                    | 7         | 12.96%  |
| IMC Networks                           | 6         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 6         | 11.11%  |
| Suyin                                  | 5         | 9.26%   |
| Microdia                               | 5         | 9.26%   |
| Bison Electronics                      | 5         | 9.26%   |
| Ricoh                                  | 3         | 5.56%   |
| Realtek Semiconductor                  | 2         | 3.7%    |
| Logitech                               | 2         | 3.7%    |
| Apple                                  | 2         | 3.7%    |
| Alcor Micro                            | 2         | 3.7%    |
| USB Camera CS                          | 1         | 1.85%   |
| Sunplus Innovation Technology          | 1         | 1.85%   |
| Silicon Motion                         | 1         | 1.85%   |
| Quanta                                 | 1         | 1.85%   |
| Luxvisions Innotech Limited            | 1         | 1.85%   |
| KYE Systems (Mouse Systems)            | 1         | 1.85%   |
| eMPIA Technology                       | 1         | 1.85%   |
| Cubeternet                             | 1         | 1.85%   |
| ALi                                    | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                                      | 2         | 3.64%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 3.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 3.64%   |
| Bison Integrated Camera                                     | 2         | 3.64%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 3.64%   |
| USB Camera CS USB Camera CS                                 | 1         | 1.82%   |
| Suyin HD WebCam                                             | 1         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.82%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.82%   |
| Sunplus HD WebCam                                           | 1         | 1.82%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 1.82%   |
| Ricoh Webcam 1000                                           | 1         | 1.82%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 1.82%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 1.82%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.82%   |
| Realtek HP Wide Vision HD Camera                            | 1         | 1.82%   |
| Quanta Chromebook HD Camera                                 | 1         | 1.82%   |
| Microdia Webcam Vitade AF                                   | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 1.82%   |
| Microdia Integrated Webcam                                  | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.82%   |
| Logitech HD Webcam C615                                     | 1         | 1.82%   |
| Logitech HD Webcam C525                                     | 1         | 1.82%   |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.82%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 1.82%   |
| IMC Networks Integrated Camera                              | 1         | 1.82%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 1.82%   |
| eMPIA Lenovo EasyCamera                                     | 1         | 1.82%   |
| Cubeternet USB2.0 Camera                                    | 1         | 1.82%   |
| Chicony WebCam                                              | 1         | 1.82%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 1.82%   |
| Chicony Integrated Camera                                   | 1         | 1.82%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 1.82%   |
| Chicony HP Webcam                                           | 1         | 1.82%   |
| Chicony HP HD Webcam                                        | 1         | 1.82%   |
| Chicony CNF8029                                             | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| Synaptics                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 14.29%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 14.29%  |
| Synaptics UWP WBDI                                          | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                       | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                         | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 85        | 78.7%   |
| 1     | 14        | 12.96%  |
| 2     | 8         | 7.41%   |
| 4     | 1         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 41.18%  |
| Fingerprint reader       | 7         | 20.59%  |
| Net/wireless             | 3         | 8.82%   |
| Flash memory             | 2         | 5.88%   |
| Communication controller | 2         | 5.88%   |
| Chipcard                 | 2         | 5.88%   |
| Camera                   | 2         | 5.88%   |
| Network                  | 1         | 2.94%   |
| Multimedia controller    | 1         | 2.94%   |

