Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 861

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-dw0xxx            | Notebook    | [b732d30db5](https://linux-hardware.org/?probe=b732d30db5) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [43bc3cd4bd](https://linux-hardware.org/?probe=43bc3cd4bd) | Jan 02, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [93ce6b9074](https://linux-hardware.org/?probe=93ce6b9074) | Jan 02, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [5cde8dcd78](https://linux-hardware.org/?probe=5cde8dcd78) | Jan 01, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [4c2ef0d59a](https://linux-hardware.org/?probe=4c2ef0d59a) | Dec 30, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [8ec110334b](https://linux-hardware.org/?probe=8ec110334b) | Dec 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| NZXT          | N7 B550                     | Desktop     | [2ce2b46a02](https://linux-hardware.org/?probe=2ce2b46a02) | Dec 27, 2023 |
| Intel         | X99-P4 V5.0                 | Desktop     | [875d756d73](https://linux-hardware.org/?probe=875d756d73) | Dec 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c3b34cdeb4](https://linux-hardware.org/?probe=c3b34cdeb4) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | Notebook    | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [7fcdc0004a](https://linux-hardware.org/?probe=7fcdc0004a) | Dec 25, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [0819197709](https://linux-hardware.org/?probe=0819197709) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [16f9dec3e0](https://linux-hardware.org/?probe=16f9dec3e0) | Dec 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [67c84a4903](https://linux-hardware.org/?probe=67c84a4903) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [30fc775598](https://linux-hardware.org/?probe=30fc775598) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | Notebook    | [19d43a41f8](https://linux-hardware.org/?probe=19d43a41f8) | Dec 17, 2023 |
| HP            | 2B18                        | Desktop     | [7015a76fe4](https://linux-hardware.org/?probe=7015a76fe4) | Dec 15, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [60461068e8](https://linux-hardware.org/?probe=60461068e8) | Dec 13, 2023 |
| HC            | HCAR357-MI                  | Notebook    | [daaf3e0f5f](https://linux-hardware.org/?probe=daaf3e0f5f) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [241c795a70](https://linux-hardware.org/?probe=241c795a70) | Dec 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [16c9e2b55c](https://linux-hardware.org/?probe=16c9e2b55c) | Dec 04, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [e099b86288](https://linux-hardware.org/?probe=e099b86288) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cf6dd1eb40](https://linux-hardware.org/?probe=cf6dd1eb40) | Dec 01, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d307e11a95](https://linux-hardware.org/?probe=d307e11a95) | Dec 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [d46afc319c](https://linux-hardware.org/?probe=d46afc319c) | Nov 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [f71053bf5c](https://linux-hardware.org/?probe=f71053bf5c) | Nov 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3aa5e4bed1](https://linux-hardware.org/?probe=3aa5e4bed1) | Nov 30, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [2ddc688d1d](https://linux-hardware.org/?probe=2ddc688d1d) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7077c34a71](https://linux-hardware.org/?probe=7077c34a71) | Nov 27, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9e97507512](https://linux-hardware.org/?probe=9e97507512) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [77db088b52](https://linux-hardware.org/?probe=77db088b52) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [a052f2ee36](https://linux-hardware.org/?probe=a052f2ee36) | Nov 25, 2023 |
| Supermicro    | H11DSi                      | Server      | [a1cf33e683](https://linux-hardware.org/?probe=a1cf33e683) | Nov 23, 2023 |
| Dell          | Latitude E5520              | Notebook    | [7c773e173a](https://linux-hardware.org/?probe=7c773e173a) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8ae454aca](https://linux-hardware.org/?probe=c8ae454aca) | Nov 20, 2023 |
| Supermicro    | H11DSi                      | Server      | [282df85b76](https://linux-hardware.org/?probe=282df85b76) | Nov 19, 2023 |
| HP            | ZBook 15                    | Notebook    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [89c0fabbb5](https://linux-hardware.org/?probe=89c0fabbb5) | Nov 17, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [e9e98d1041](https://linux-hardware.org/?probe=e9e98d1041) | Nov 14, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| Samsung       | R530/R730                   | Notebook    | [e1177626c4](https://linux-hardware.org/?probe=e1177626c4) | Nov 11, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [46261b27de](https://linux-hardware.org/?probe=46261b27de) | Nov 09, 2023 |
| HP            | 89E9 0100                   | All in one  | [fafa5e6c96](https://linux-hardware.org/?probe=fafa5e6c96) | Nov 07, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [dd143f192c](https://linux-hardware.org/?probe=dd143f192c) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4a6383e886](https://linux-hardware.org/?probe=4a6383e886) | Nov 04, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [b84c515650](https://linux-hardware.org/?probe=b84c515650) | Nov 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [d802042506](https://linux-hardware.org/?probe=d802042506) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [cdda6b5094](https://linux-hardware.org/?probe=cdda6b5094) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [5bec5815bb](https://linux-hardware.org/?probe=5bec5815bb) | Oct 31, 2023 |
| ASRock        | H77 Pro4-M                  | Desktop     | [83aeda3c64](https://linux-hardware.org/?probe=83aeda3c64) | Oct 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [0ff396f5c2](https://linux-hardware.org/?probe=0ff396f5c2) | Oct 29, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bf5f9098d7](https://linux-hardware.org/?probe=bf5f9098d7) | Oct 28, 2023 |
| Intel         | H55                         | Desktop     | [f8788bcc72](https://linux-hardware.org/?probe=f8788bcc72) | Oct 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [92c4516951](https://linux-hardware.org/?probe=92c4516951) | Oct 27, 2023 |
| Acer          | Predator PH317-51           | Notebook    | [941e333a3b](https://linux-hardware.org/?probe=941e333a3b) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [50b7d4272d](https://linux-hardware.org/?probe=50b7d4272d) | Oct 26, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4b2be75f68](https://linux-hardware.org/?probe=4b2be75f68) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4323d57b2f](https://linux-hardware.org/?probe=4323d57b2f) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [959fc54e2b](https://linux-hardware.org/?probe=959fc54e2b) | Oct 23, 2023 |
| Lenovo        | ThinkPad T460s 20F90060G... | Notebook    | [b44ed99aff](https://linux-hardware.org/?probe=b44ed99aff) | Oct 22, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [73fdacf30c](https://linux-hardware.org/?probe=73fdacf30c) | Oct 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [5902fdf35f](https://linux-hardware.org/?probe=5902fdf35f) | Oct 18, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [e30927f66e](https://linux-hardware.org/?probe=e30927f66e) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [52151555cb](https://linux-hardware.org/?probe=52151555cb) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [d1ce4588e7](https://linux-hardware.org/?probe=d1ce4588e7) | Oct 11, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [bc5016980d](https://linux-hardware.org/?probe=bc5016980d) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [49d0e884bb](https://linux-hardware.org/?probe=49d0e884bb) | Oct 08, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3d613c96a8](https://linux-hardware.org/?probe=3d613c96a8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [61579851ef](https://linux-hardware.org/?probe=61579851ef) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9410b590b4](https://linux-hardware.org/?probe=9410b590b4) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [2a6facae05](https://linux-hardware.org/?probe=2a6facae05) | Oct 05, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [e7906b9cd7](https://linux-hardware.org/?probe=e7906b9cd7) | Oct 04, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [1c7bef5950](https://linux-hardware.org/?probe=1c7bef5950) | Oct 04, 2023 |
| Intel         | X99                         | Desktop     | [67ec0ac8d0](https://linux-hardware.org/?probe=67ec0ac8d0) | Oct 02, 2023 |
| Unknown       | TB-5000                     | Desktop     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| AMI           | Intel                       | Notebook    | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| HP            | 1998                        | Desktop     | [60208f6be9](https://linux-hardware.org/?probe=60208f6be9) | Sep 22, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [5995975e04](https://linux-hardware.org/?probe=5995975e04) | Sep 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [623cd3e438](https://linux-hardware.org/?probe=623cd3e438) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [78ddadfb89](https://linux-hardware.org/?probe=78ddadfb89) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [3145861387](https://linux-hardware.org/?probe=3145861387) | Sep 12, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [b037f9322d](https://linux-hardware.org/?probe=b037f9322d) | Sep 10, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [647634e7fb](https://linux-hardware.org/?probe=647634e7fb) | Sep 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5330a96ef6](https://linux-hardware.org/?probe=5330a96ef6) | Sep 07, 2023 |
| Matsushita... | CF-74JCJBDAM                | Notebook    | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9441e027c6](https://linux-hardware.org/?probe=9441e027c6) | Sep 04, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [10951f0a65](https://linux-hardware.org/?probe=10951f0a65) | Sep 01, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [ac6c5c8969](https://linux-hardware.org/?probe=ac6c5c8969) | Sep 01, 2023 |
| MOTION        | NVX00                       | Notebook    | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5d571876c8](https://linux-hardware.org/?probe=5d571876c8) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fde9e1a454](https://linux-hardware.org/?probe=fde9e1a454) | Aug 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [4a81412fdd](https://linux-hardware.org/?probe=4a81412fdd) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [0657120653](https://linux-hardware.org/?probe=0657120653) | Aug 19, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | Notebook    | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [9c90e63339](https://linux-hardware.org/?probe=9c90e63339) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f0b1f6f364](https://linux-hardware.org/?probe=f0b1f6f364) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ef08441bc9](https://linux-hardware.org/?probe=ef08441bc9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [68fff65eee](https://linux-hardware.org/?probe=68fff65eee) | Aug 10, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [81a2d0415e](https://linux-hardware.org/?probe=81a2d0415e) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [de06cea570](https://linux-hardware.org/?probe=de06cea570) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [4275d43a74](https://linux-hardware.org/?probe=4275d43a74) | Aug 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [65343a7900](https://linux-hardware.org/?probe=65343a7900) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [af88e64084](https://linux-hardware.org/?probe=af88e64084) | Aug 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b736ced64](https://linux-hardware.org/?probe=6b736ced64) | Aug 03, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [4d98867c44](https://linux-hardware.org/?probe=4d98867c44) | Aug 02, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [675811747f](https://linux-hardware.org/?probe=675811747f) | Aug 02, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ba2cec8099](https://linux-hardware.org/?probe=ba2cec8099) | Aug 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [cdbcf58dcb](https://linux-hardware.org/?probe=cdbcf58dcb) | Jul 30, 2023 |
| HP            | ENVY Notebook               | Notebook    | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2dbda5ea48](https://linux-hardware.org/?probe=2dbda5ea48) | Jul 29, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| Alienware     | 13 R3                       | Notebook    | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| Biostar       | B350GT3                     | Desktop     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Alienware     | 07W25T A00                  | Desktop     | [24dade96af](https://linux-hardware.org/?probe=24dade96af) | Jul 21, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5d2c798252](https://linux-hardware.org/?probe=5d2c798252) | Jul 21, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [79ab32a714](https://linux-hardware.org/?probe=79ab32a714) | Jul 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [228fca7e43](https://linux-hardware.org/?probe=228fca7e43) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [eb85c87997](https://linux-hardware.org/?probe=eb85c87997) | Jul 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| HP            | 8053                        | Desktop     | [4241a715e6](https://linux-hardware.org/?probe=4241a715e6) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [5e8900dde2](https://linux-hardware.org/?probe=5e8900dde2) | Jul 02, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [b819a1fb21](https://linux-hardware.org/?probe=b819a1fb21) | Jul 02, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [fe1c9de1b6](https://linux-hardware.org/?probe=fe1c9de1b6) | Jul 02, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [529873f796](https://linux-hardware.org/?probe=529873f796) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [047aac4298](https://linux-hardware.org/?probe=047aac4298) | Jun 25, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [88e2f62c6d](https://linux-hardware.org/?probe=88e2f62c6d) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2278cd4d03](https://linux-hardware.org/?probe=2278cd4d03) | Jun 17, 2023 |
| Biostar       | B350GT3                     | Desktop     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| Dell          | Latitude E6510              | Notebook    | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Dell          | Precision 5520              | Notebook    | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | Desktop     | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| MICROBYTE     | ezbook                      | Notebook    | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Win elemen... | M600                        | Desktop     | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | Notebook    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | Notebook    | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [182acb48b9](https://linux-hardware.org/?probe=182acb48b9) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a0e44bf0d1](https://linux-hardware.org/?probe=a0e44bf0d1) | Apr 13, 2023 |
| Win elemen... | M600                        | Desktop     | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | 8053                        | Desktop     | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | 8053                        | Desktop     | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| HP            | 8053                        | Desktop     | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | Desktop     | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | Desktop     | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| HP            | Unknown                     | Notebook    | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| MobileDema... | xTablet T1200               | Notebook    | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | Notebook    | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | Notebook    | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | Notebook    | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | Notebook    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [1c406a3696](https://linux-hardware.org/?probe=1c406a3696) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [08ac155787](https://linux-hardware.org/?probe=08ac155787) | Dec 31, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Intel         | H61                         | Desktop     | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8fe5127ba0](https://linux-hardware.org/?probe=8fe5127ba0) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| Alienware     | m15 R7                      | Notebook    | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a7f86279b6](https://linux-hardware.org/?probe=a7f86279b6) | Dec 04, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [2a5b05500a](https://linux-hardware.org/?probe=2a5b05500a) | Nov 11, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [f0b3051737](https://linux-hardware.org/?probe=f0b3051737) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | Notebook    | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | Desktop     | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1c50c72b71](https://linux-hardware.org/?probe=1c50c72b71) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | Notebook    | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f9fbb00a0b](https://linux-hardware.org/?probe=f9fbb00a0b) | Aug 23, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [822e93c1db](https://linux-hardware.org/?probe=822e93c1db) | Aug 02, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Garuda_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 375       | 63.67%  |
| Garuda Linux Rolling | 107       | 18.17%  |
| Garuda Linux         | 107       | 18.17%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 580       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.1.1-zen1-1-zen   | 13        | 1.94%   |
| 6.5.9-zen2-1-zen   | 11        | 1.64%   |
| 6.0.2-zen1-1-zen   | 11        | 1.64%   |
| 6.4.12-zen1-1-zen  | 9         | 1.35%   |
| 6.2.13-zen-1-zen   | 9         | 1.35%   |
| 5.17.1-zen1-1-zen  | 9         | 1.35%   |
| 6.6.8-zen1-1-zen   | 7         | 1.05%   |
| 6.6.7-zen1-1-zen   | 7         | 1.05%   |
| 6.4.10-zen2-1-zen  | 7         | 1.05%   |
| 5.15.2-zen1-1-zen  | 7         | 1.05%   |
| 5.14.14-zen1-1-zen | 7         | 1.05%   |
| 6.2.10-zen1-1-zen  | 6         | 0.9%    |
| 5.17.9-zen1-1-zen  | 6         | 0.9%    |
| 5.16.4-zen1-1-zen  | 6         | 0.9%    |
| 6.6.3-zen1-1-zen   | 5         | 0.75%   |
| 6.6.2-zen1-1-zen   | 5         | 0.75%   |
| 6.5.5-zen1-1-zen   | 5         | 0.75%   |
| 6.3.8-zen1-1-zen   | 5         | 0.75%   |
| 6.2.7-zen1-1-zen   | 5         | 0.75%   |
| 6.2.12-zen1-1-zen  | 5         | 0.75%   |
| 6.1.7-zen1-1-zen   | 5         | 0.75%   |
| 6.0.9-zen1-1-zen   | 5         | 0.75%   |
| 6.0.8-zen1-1-zen   | 5         | 0.75%   |
| 6.0.12-zen1-1-zen  | 5         | 0.75%   |
| 5.18.16-zen1-1-zen | 5         | 0.75%   |
| 5.15.7-zen1-1-zen  | 5         | 0.75%   |
| 5.15.13-zen1-1-zen | 5         | 0.75%   |
| 5.15.12-zen1-1-zen | 5         | 0.75%   |
| 5.13.9-zen1-1-zen  | 5         | 0.75%   |
| 5.13.13-zen1-1-zen | 5         | 0.75%   |
| 5.11.16-zen1-1-zen | 5         | 0.75%   |
| 5.11.11-zen1-1-zen | 5         | 0.75%   |
| 6.6.1-zen1-1-zen   | 4         | 0.6%    |
| 6.5.7-zen2-1-zen   | 4         | 0.6%    |
| 6.5.2-zen1-1-zen   | 4         | 0.6%    |
| 6.4.9-zen1-1-zen   | 4         | 0.6%    |
| 6.4.11-zen2-1-zen  | 4         | 0.6%    |
| 6.3.2-zen1-1-zen   | 4         | 0.6%    |
| 6.1.12-zen1-1-zen  | 4         | 0.6%    |
| 6.0.6-zen1-1-zen   | 4         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.1   | 14        | 2.09%   |
| 6.5.9   | 12        | 1.79%   |
| 6.0.2   | 12        | 1.79%   |
| 5.17.1  | 11        | 1.64%   |
| 6.4.12  | 9         | 1.35%   |
| 6.2.13  | 9         | 1.35%   |
| 6.6.8   | 8         | 1.2%    |
| 6.4.10  | 8         | 1.2%    |
| 6.6.7   | 7         | 1.05%   |
| 6.5.5   | 7         | 1.05%   |
| 6.2.10  | 7         | 1.05%   |
| 5.15.2  | 7         | 1.05%   |
| 5.14.14 | 7         | 1.05%   |
| 6.6.3   | 6         | 0.9%    |
| 6.6.2   | 6         | 0.9%    |
| 6.2.7   | 6         | 0.9%    |
| 6.1.9   | 6         | 0.9%    |
| 6.0.8   | 6         | 0.9%    |
| 5.18.16 | 6         | 0.9%    |
| 5.17.9  | 6         | 0.9%    |
| 5.17.5  | 6         | 0.9%    |
| 5.17.3  | 6         | 0.9%    |
| 5.16.4  | 6         | 0.9%    |
| 5.15.7  | 6         | 0.9%    |
| 5.11.11 | 6         | 0.9%    |
| 5.10.4  | 6         | 0.9%    |
| 6.6.1   | 5         | 0.75%   |
| 6.5.7   | 5         | 0.75%   |
| 6.4.3   | 5         | 0.75%   |
| 6.4.11  | 5         | 0.75%   |
| 6.3.8   | 5         | 0.75%   |
| 6.3.1   | 5         | 0.75%   |
| 6.2.12  | 5         | 0.75%   |
| 6.1.7   | 5         | 0.75%   |
| 6.0.9   | 5         | 0.75%   |
| 6.0.12  | 5         | 0.75%   |
| 6.0.11  | 5         | 0.75%   |
| 6.0.10  | 5         | 0.75%   |
| 5.19.7  | 5         | 0.75%   |
| 5.16.5  | 5         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 63        | 9.74%   |
| 5.15    | 54        | 8.35%   |
| 6.4     | 50        | 7.73%   |
| 6.0     | 49        | 7.57%   |
| 6.2     | 41        | 6.34%   |
| 5.16    | 41        | 6.34%   |
| 6.6     | 39        | 6.03%   |
| 6.5     | 37        | 5.72%   |
| 5.18    | 36        | 5.56%   |
| 5.10    | 36        | 5.56%   |
| 5.19    | 32        | 4.95%   |
| 5.17    | 31        | 4.79%   |
| 5.14    | 27        | 4.17%   |
| 6.3     | 24        | 3.71%   |
| 5.12    | 23        | 3.55%   |
| 5.11    | 23        | 3.55%   |
| 5.13    | 21        | 3.25%   |
| 5.9     | 13        | 2.01%   |
| 5.8     | 5         | 0.77%   |
| 5.6     | 1         | 0.15%   |
| 5.4     | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 580       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 407       | 69.1%   |
| GNOME             | 68        | 11.54%  |
| KDE               | 36        | 6.11%   |
| XFCE              | 30        | 5.09%   |
| X-Cinnamon        | 13        | 2.21%   |
| sway              | 7         | 1.19%   |
| qtile-default     | 3         | 0.51%   |
| LXQt              | 3         | 0.51%   |
| i3                | 3         | 0.51%   |
| Deepin            | 3         | 0.51%   |
| Cinnamon          | 3         | 0.51%   |
| Unknown           | 3         | 0.51%   |
| qtile             | 2         | 0.34%   |
| MATE              | 2         | 0.34%   |
| Hyprland          | 2         | 0.34%   |
| Yaru:ubuntu:GNOME | 1         | 0.17%   |
| Unity             | 1         | 0.17%   |
| Budgie            | 1         | 0.17%   |
| awesome           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 502       | 85.23%  |
| Wayland | 67        | 11.38%  |
| Tty     | 10        | 1.7%    |
| Unknown | 10        | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 279       | 47.53%  |
| Unknown | 209       | 35.6%   |
| LightDM | 56        | 9.54%   |
| GDM     | 37        | 6.3%    |
| GREETD  | 6         | 1.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 297       | 50.86%  |
| en_GB | 57        | 9.76%   |
| de_DE | 43        | 7.36%   |
| en_IN | 25        | 4.28%   |
| it_IT | 20        | 3.42%   |
| en_CA | 20        | 3.42%   |
| pt_BR | 13        | 2.23%   |
| es_ES | 11        | 1.88%   |
| pl_PL | 9         | 1.54%   |
| nl_NL | 7         | 1.2%    |
| fr_FR | 7         | 1.2%    |
| ru_RU | 6         | 1.03%   |
| es_MX | 6         | 1.03%   |
| tr_TR | 5         | 0.86%   |
| en_AU | 5         | 0.86%   |
| sv_SE | 3         | 0.51%   |
| es_CO | 3         | 0.51%   |
| en_ZA | 3         | 0.51%   |
| en_DK | 3         | 0.51%   |
| de_AT | 3         | 0.51%   |
| sk_SK | 2         | 0.34%   |
| ja_JP | 2         | 0.34%   |
| fr_BE | 2         | 0.34%   |
| fi_FI | 2         | 0.34%   |
| es_VE | 2         | 0.34%   |
| es_EC | 2         | 0.34%   |
| es_AR | 2         | 0.34%   |
| en_AG | 2         | 0.34%   |
| da_DK | 2         | 0.34%   |
| zh_CN | 1         | 0.17%   |
| uk_UA | 1         | 0.17%   |
| sl_SI | 1         | 0.17%   |
| nl_BE | 1         | 0.17%   |
| nb_NO | 1         | 0.17%   |
| ko_KR | 1         | 0.17%   |
| iu_CA | 1         | 0.17%   |
| hu_HU | 1         | 0.17%   |
| fr_CA | 1         | 0.17%   |
| es_PE | 1         | 0.17%   |
| es_CL | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 354       | 60.62%  |
| BIOS | 230       | 39.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 561       | 96.72%  |
| Overlay | 9         | 1.55%   |
| Tmpfs   | 5         | 0.86%   |
| Ext4    | 2         | 0.34%   |
| XXXXX   | 1         | 0.17%   |
| Xfs     | 1         | 0.17%   |
| F2fs    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 358       | 61.3%   |
| Unknown | 205       | 35.1%   |
| MBR     | 21        | 3.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 505       | 85.88%  |
| Yes       | 83        | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 394       | 66.89%  |
| Yes       | 195       | 33.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 116       | 20%     |
| Lenovo                               | 85        | 14.66%  |
| Hewlett-Packard                      | 80        | 13.79%  |
| Dell                                 | 52        | 8.97%   |
| MSI                                  | 50        | 8.62%   |
| Gigabyte Technology                  | 40        | 6.9%    |
| Acer                                 | 37        | 6.38%   |
| ASRock                               | 23        | 3.97%   |
| Apple                                | 14        | 2.41%   |
| Intel                                | 6         | 1.03%   |
| HUAWEI                               | 6         | 1.03%   |
| Samsung Electronics                  | 5         | 0.86%   |
| Alienware                            | 5         | 0.86%   |
| Unknown                              | 5         | 0.86%   |
| Notebook                             | 4         | 0.69%   |
| Fujitsu                              | 4         | 0.69%   |
| AZW                                  | 4         | 0.69%   |
| Razer                                | 3         | 0.52%   |
| Medion                               | 3         | 0.52%   |
| XIAOMI                               | 2         | 0.34%   |
| Toshiba                              | 2         | 0.34%   |
| Sony                                 | 2         | 0.34%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.34%   |
| Pegatron                             | 2         | 0.34%   |
| HONOR                                | 2         | 0.34%   |
| Biostar                              | 2         | 0.34%   |
| Win element                          | 1         | 0.17%   |
| T-bao                                | 1         | 0.17%   |
| Supermicro                           | 1         | 0.17%   |
| Standard                             | 1         | 0.17%   |
| PC Specialist                        | 1         | 0.17%   |
| Panasonic                            | 1         | 0.17%   |
| OEM                                  | 1         | 0.17%   |
| NZXT                                 | 1         | 0.17%   |
| MOTION                               | 1         | 0.17%   |
| Monster                              | 1         | 0.17%   |
| MobileDemand                         | 1         | 0.17%   |
| Microsoft                            | 1         | 0.17%   |
| MICROBYTE                            | 1         | 0.17%   |
| Matsushita Electric Industrial       | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 9         | 1.55%   |
| ASUS TUF Gaming X570-PLUS             | 8         | 1.38%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 5         | 0.86%   |
| Apple MacBookPro9,2                   | 5         | 0.86%   |
| MSI MS-7C91                           | 3         | 0.52%   |
| MSI MS-7B86                           | 3         | 0.52%   |
| AZW SER                               | 3         | 0.52%   |
| ASUS All Series                       | 3         | 0.52%   |
| XIAOMI Redmi Book Pro 15 2023         | 2         | 0.34%   |
| MSI MS-7D75                           | 2         | 0.34%   |
| MSI MS-7C37                           | 2         | 0.34%   |
| MSI MS-7C02                           | 2         | 0.34%   |
| Lenovo ThinkPad W530 24474KG          | 2         | 0.34%   |
| HUAWEI HVY-WXX9                       | 2         | 0.34%   |
| HP ProDesk 600 G1 SFF                 | 2         | 0.34%   |
| HP ProBook 640 G1                     | 2         | 0.34%   |
| HP Pavilion Laptop 15-cc1xx           | 2         | 0.34%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 2         | 0.34%   |
| HP Pavilion Gaming Desktop 690-00xx   | 2         | 0.34%   |
| HP Pavilion dv6                       | 2         | 0.34%   |
| HP OMEN Laptop 15-en0xxx              | 2         | 0.34%   |
| HP OMEN by Laptop 15-dh1xxx           | 2         | 0.34%   |
| HP Notebook                           | 2         | 0.34%   |
| HP Laptop 15-ef2xxx                   | 2         | 0.34%   |
| HP Laptop 15-dy2xxx                   | 2         | 0.34%   |
| HP Laptop 15-da0xxx                   | 2         | 0.34%   |
| HP EliteDesk 800 G1 SFF               | 2         | 0.34%   |
| Gigabyte X570 AORUS PRO WIFI          | 2         | 0.34%   |
| Gigabyte G5 MD                        | 2         | 0.34%   |
| Gigabyte B550 AORUS PRO AC            | 2         | 0.34%   |
| Gigabyte B450 AORUS ELITE             | 2         | 0.34%   |
| Gigabyte AB350-Gaming 3               | 2         | 0.34%   |
| Dell XPS 15 9500                      | 2         | 0.34%   |
| Dell OptiPlex 7010                    | 2         | 0.34%   |
| Dell Latitude E6420                   | 2         | 0.34%   |
| Dell Inspiron 3668                    | 2         | 0.34%   |
| Dell Inspiron 15 7000 Gaming          | 2         | 0.34%   |
| ASUS TUF Gaming FX505DT_FX505DT       | 2         | 0.34%   |
| ASUS TUF Gaming B550-PLUS WIFI II     | 2         | 0.34%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 28        | 4.83%   |
| Lenovo ThinkPad    | 26        | 4.48%   |
| Lenovo IdeaPad     | 24        | 4.14%   |
| Acer Aspire        | 20        | 3.45%   |
| Dell Inspiron      | 19        | 3.28%   |
| ASUS TUF           | 19        | 3.28%   |
| HP Pavilion        | 18        | 3.1%    |
| ASUS PRIME         | 16        | 2.76%   |
| HP Laptop          | 13        | 2.24%   |
| ASUS VivoBook      | 13        | 2.24%   |
| Lenovo Legion      | 12        | 2.07%   |
| Dell Latitude      | 12        | 2.07%   |
| Unknown            | 9         | 1.55%   |
| HP OMEN            | 8         | 1.38%   |
| Dell XPS           | 7         | 1.21%   |
| Acer Nitro         | 7         | 1.21%   |
| Dell Precision     | 6         | 1.03%   |
| Apple MacBookPro9  | 6         | 1.03%   |
| Lenovo Yoga        | 5         | 0.86%   |
| Lenovo ThinkCentre | 5         | 0.86%   |
| HP EliteBook       | 5         | 0.86%   |
| Gigabyte X570      | 5         | 0.86%   |
| Dell OptiPlex      | 5         | 0.86%   |
| HP ProBook         | 4         | 0.69%   |
| HP ENVY            | 4         | 0.69%   |
| HP EliteDesk       | 4         | 0.69%   |
| Gigabyte B550      | 4         | 0.69%   |
| Gigabyte B450      | 4         | 0.69%   |
| ASUS Zenbook       | 4         | 0.69%   |
| Acer Swift         | 4         | 0.69%   |
| Razer Blade        | 3         | 0.52%   |
| MSI MS-7C91        | 3         | 0.52%   |
| MSI MS-7B86        | 3         | 0.52%   |
| HP Compaq          | 3         | 0.52%   |
| Gigabyte G5        | 3         | 0.52%   |
| AZW SER            | 3         | 0.52%   |
| ASUS ASUS          | 3         | 0.52%   |
| ASUS All           | 3         | 0.52%   |
| XIAOMI Redmi       | 2         | 0.34%   |
| Toshiba Satellite  | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 90        | 15.52%  |
| 2021    | 79        | 13.62%  |
| 2019    | 64        | 11.03%  |
| 2018    | 53        | 9.14%   |
| 2017    | 49        | 8.45%   |
| 2022    | 43        | 7.41%   |
| 2013    | 36        | 6.21%   |
| 2012    | 35        | 6.03%   |
| 2014    | 30        | 5.17%   |
| 2016    | 28        | 4.83%   |
| 2011    | 19        | 3.28%   |
| 2015    | 16        | 2.76%   |
| 2023    | 13        | 2.24%   |
| 2010    | 8         | 1.38%   |
| 2009    | 7         | 1.21%   |
| 2008    | 6         | 1.03%   |
| 2007    | 3         | 0.52%   |
| Unknown | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 321       | 55.34%  |
| Desktop     | 227       | 39.14%  |
| Convertible | 17        | 2.93%   |
| Mini pc     | 6         | 1.03%   |
| All in one  | 5         | 0.86%   |
| Tablet      | 3         | 0.52%   |
| Server      | 1         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 580       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 579       | 99.83%  |
| Yes  | 1         | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 149       | 25.47%  |
| 4.01-8.0    | 126       | 21.54%  |
| 8.01-16.0   | 120       | 20.51%  |
| 32.01-64.0  | 110       | 18.8%   |
| 3.01-4.0    | 32        | 5.47%   |
| 24.01-32.0  | 25        | 4.27%   |
| 64.01-256.0 | 22        | 3.76%   |
| 2.01-3.0    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 223       | 35.62%  |
| 3.01-4.0    | 148       | 23.64%  |
| 2.01-3.0    | 127       | 20.29%  |
| 8.01-16.0   | 64        | 10.22%  |
| 1.01-2.0    | 47        | 7.51%   |
| 16.01-24.0  | 13        | 2.08%   |
| 32.01-64.0  | 2         | 0.32%   |
| 64.01-256.0 | 1         | 0.16%   |
| 0.51-1.0    | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 263       | 44.2%   |
| 2      | 179       | 30.08%  |
| 3      | 77        | 12.94%  |
| 4      | 35        | 5.88%   |
| 5      | 22        | 3.7%    |
| 6      | 9         | 1.51%   |
| 9      | 4         | 0.67%   |
| 7      | 2         | 0.34%   |
| 18     | 1         | 0.17%   |
| 14     | 1         | 0.17%   |
| 11     | 1         | 0.17%   |
| 0      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 449       | 76.88%  |
| Yes       | 135       | 23.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 485       | 83.48%  |
| No        | 96        | 16.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 81.74%  |
| No        | 107       | 18.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 434       | 74.19%  |
| No        | 151       | 25.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 161       | 27.62%  |
| Germany      | 63        | 10.81%  |
| Italy        | 33        | 5.66%   |
| India        | 30        | 5.15%   |
| Canada       | 29        | 4.97%   |
| UK           | 28        | 4.8%    |
| Brazil       | 20        | 3.43%   |
| Poland       | 17        | 2.92%   |
| Spain        | 13        | 2.23%   |
| Netherlands  | 12        | 2.06%   |
| France       | 12        | 2.06%   |
| Turkey       | 9         | 1.54%   |
| Sweden       | 9         | 1.54%   |
| Mexico       | 9         | 1.54%   |
| Russia       | 8         | 1.37%   |
| Romania      | 7         | 1.2%    |
| Belgium      | 7         | 1.2%    |
| Australia    | 7         | 1.2%    |
| Denmark      | 6         | 1.03%   |
| Austria      | 5         | 0.86%   |
| Switzerland  | 4         | 0.69%   |
| South Africa | 4         | 0.69%   |
| Japan        | 4         | 0.69%   |
| Greece       | 4         | 0.69%   |
| Finland      | 4         | 0.69%   |
| Colombia     | 4         | 0.69%   |
| Slovenia     | 3         | 0.51%   |
| Singapore    | 3         | 0.51%   |
| Serbia       | 3         | 0.51%   |
| Norway       | 3         | 0.51%   |
| Latvia       | 3         | 0.51%   |
| Indonesia    | 3         | 0.51%   |
| Czechia      | 3         | 0.51%   |
| Argentina    | 3         | 0.51%   |
| Venezuela    | 2         | 0.34%   |
| Slovakia     | 2         | 0.34%   |
| Puerto Rico  | 2         | 0.34%   |
| Portugal     | 2         | 0.34%   |
| Philippines  | 2         | 0.34%   |
| Pakistan     | 2         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 7         | 1.15%   |
| Milan             | 6         | 0.99%   |
| Warsaw            | 5         | 0.82%   |
| London            | 5         | 0.82%   |
| Istanbul          | 5         | 0.82%   |
| Sydney            | 4         | 0.66%   |
| Mississauga       | 4         | 0.66%   |
| Hyderabad         | 4         | 0.66%   |
| Frankfurt am Main | 4         | 0.66%   |
| Düsseldorf       | 4         | 0.66%   |
| Drums             | 4         | 0.66%   |
| Dallas            | 4         | 0.66%   |
| Copenhagen        | 4         | 0.66%   |
| Cape Town         | 4         | 0.66%   |
| Toronto           | 3         | 0.49%   |
| Singapore         | 3         | 0.49%   |
| Sao Paulo         | 3         | 0.49%   |
| San Jose          | 3         | 0.49%   |
| Riga              | 3         | 0.49%   |
| Prague            | 3         | 0.49%   |
| Portland          | 3         | 0.49%   |
| Mumbai            | 3         | 0.49%   |
| Montreal          | 3         | 0.49%   |
| Los Angeles       | 3         | 0.49%   |
| Kansas City       | 3         | 0.49%   |
| Florence          | 3         | 0.49%   |
| Fayetteville      | 3         | 0.49%   |
| Columbus          | 3         | 0.49%   |
| Cologne           | 3         | 0.49%   |
| Chicago           | 3         | 0.49%   |
| Bengaluru         | 3         | 0.49%   |
| Belo Horizonte    | 3         | 0.49%   |
| Atlanta           | 3         | 0.49%   |
| Athens            | 3         | 0.49%   |
| Wroclaw           | 2         | 0.33%   |
| Wasmes            | 2         | 0.33%   |
| Victoria          | 2         | 0.33%   |
| Valencia          | 2         | 0.33%   |
| Turin             | 2         | 0.33%   |
| Timișoara        | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 175       | 295    | 16.42%  |
| Seagate                     | 136       | 192    | 12.76%  |
| WDC                         | 134       | 200    | 12.57%  |
| SanDisk                     | 74        | 91     | 6.94%   |
| Toshiba                     | 65        | 84     | 6.1%    |
| Kingston                    | 46        | 62     | 4.32%   |
| SK hynix                    | 40        | 53     | 3.75%   |
| Crucial                     | 39        | 49     | 3.66%   |
| Intel                       | 31        | 41     | 2.91%   |
| Unknown                     | 26        | 27     | 2.44%   |
| HGST                        | 22        | 28     | 2.06%   |
| Hitachi                     | 20        | 21     | 1.88%   |
| Micron Technology           | 19        | 21     | 1.78%   |
| Phison Electronics          | 15        | 19     | 1.41%   |
| Micron/Crucial Technology   | 15        | 19     | 1.41%   |
| Silicon Motion              | 13        | 13     | 1.22%   |
| SPCC                        | 11        | 12     | 1.03%   |
| China                       | 11        | 14     | 1.03%   |
| Phison                      | 10        | 11     | 0.94%   |
| A-DATA Technology           | 10        | 14     | 0.94%   |
| KIOXIA                      | 9         | 11     | 0.84%   |
| PNY                         | 8         | 8      | 0.75%   |
| ADATA Technology            | 8         | 10     | 0.75%   |
| MAXIO Technology (Hangzhou) | 7         | 7      | 0.66%   |
| Kingston Technology Company | 7         | 7      | 0.66%   |
| Apple                       | 6         | 7      | 0.56%   |
| Intenso                     | 5         | 6      | 0.47%   |
| Hewlett-Packard             | 5         | 5      | 0.47%   |
| Team                        | 4         | 5      | 0.38%   |
| SABRENT                     | 4         | 7      | 0.38%   |
| Realtek Semiconductor       | 4         | 6      | 0.38%   |
| Patriot                     | 4         | 8      | 0.38%   |
| OCZ                         | 4         | 4      | 0.38%   |
| LITEONIT                    | 4         | 4      | 0.38%   |
| LITEON                      | 4         | 4      | 0.38%   |
| Emtec                       | 4         | 6      | 0.38%   |
| Corsair                     | 4         | 7      | 0.38%   |
| XPG                         | 3         | 4      | 0.28%   |
| Transcend                   | 3         | 3      | 0.28%   |
| JMicron Technology          | 3         | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 27        | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB                | 16        | 1.34%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 14        | 1.17%   |
| Samsung NVMe SSD Drive 1TB                                        | 12        | 1%      |
| Seagate ST2000DM008-2FR102 2TB                                    | 10        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 10        | 0.84%   |
| Samsung SSD 860 EVO 500GB                                         | 10        | 0.84%   |
| Crucial CT1000MX500SSD1 1TB                                       | 10        | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 9         | 0.75%   |
| Samsung SSD 850 EVO 250GB                                         | 9         | 0.75%   |
| Samsung SSD 860 EVO 1TB                                           | 8         | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                               | 8         | 0.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB                    | 7         | 0.58%   |
| Samsung SSD 980 1TB                                               | 7         | 0.58%   |
| Intel SSD 660P Series 1TB                                         | 7         | 0.58%   |
| HGST HTS721010A9E630 1TB                                          | 7         | 0.58%   |
| Unknown MMC Card  64GB                                            | 6         | 0.5%    |
| Toshiba DT01ACA100 1TB                                            | 6         | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB                                    | 6         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                                    | 6         | 0.5%    |
| SanDisk SSD PLUS 1000GB                                           | 6         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB                                    | 6         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller 2TB                              | 6         | 0.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB                | 6         | 0.5%    |
| Kingston SA400S37240G 240GB SSD                                   | 6         | 0.5%    |
| Crucial CT500MX500SSD1 500GB                                      | 6         | 0.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 6         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                                          | 5         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                                          | 5         | 0.42%   |
| Toshiba HDWD110 1TB                                               | 5         | 0.42%   |
| SPCC Solid State Disk 512GB                                       | 5         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB             | 5         | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB                                    | 5         | 0.42%   |
| Samsung SSD 860 QVO 1TB                                           | 5         | 0.42%   |
| Samsung SSD 860 EVO 250GB                                         | 5         | 0.42%   |
| Samsung SSD 850 EVO 500GB                                         | 5         | 0.42%   |
| Samsung NVMe SSD Drive 500GB                                      | 5         | 0.42%   |
| Kingston SA400S37120G 120GB SSD                                   | 5         | 0.42%   |
| Intel SSDPEKNU512GZ 512GB                                         | 5         | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 181    | 37.14%  |
| WDC                 | 101       | 163    | 28.86%  |
| Toshiba             | 48        | 60     | 13.71%  |
| HGST                | 22        | 28     | 6.29%   |
| Hitachi             | 20        | 21     | 5.71%   |
| Samsung Electronics | 6         | 6      | 1.71%   |
| SABRENT             | 4         | 7      | 1.14%   |
| Unknown             | 3         | 3      | 0.86%   |
| Intenso             | 3         | 4      | 0.86%   |
| Apple               | 3         | 3      | 0.86%   |
| TO Exter            | 2         | 2      | 0.57%   |
| SSK                 | 1         | 1      | 0.29%   |
| LaCie               | 1         | 1      | 0.29%   |
| KESU                | 1         | 1      | 0.29%   |
| Inateck             | 1         | 1      | 0.29%   |
| Hewlett-Packard     | 1         | 1      | 0.29%   |
| External            | 1         | 1      | 0.29%   |
| ASMT                | 1         | 2      | 0.29%   |
| ASMedia             | 1         | 2      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 115    | 25.72%  |
| Crucial             | 34        | 42     | 10.93%  |
| Kingston            | 31        | 39     | 9.97%   |
| SanDisk             | 26        | 37     | 8.36%   |
| WDC                 | 16        | 17     | 5.14%   |
| China               | 11        | 14     | 3.54%   |
| SPCC                | 10        | 11     | 3.22%   |
| A-DATA Technology   | 10        | 14     | 3.22%   |
| Toshiba             | 9         | 13     | 2.89%   |
| SK hynix            | 9         | 13     | 2.89%   |
| PNY                 | 7         | 7      | 2.25%   |
| Micron Technology   | 6         | 7      | 1.93%   |
| Team                | 4         | 5      | 1.29%   |
| OCZ                 | 4         | 4      | 1.29%   |
| LITEONIT            | 4         | 4      | 1.29%   |
| LITEON              | 4         | 4      | 1.29%   |
| Emtec               | 4         | 6      | 1.29%   |
| Transcend           | 3         | 3      | 0.96%   |
| Patriot             | 3         | 7      | 0.96%   |
| Hewlett-Packard     | 3         | 3      | 0.96%   |
| Mushkin             | 2         | 2      | 0.64%   |
| Lexar               | 2         | 2      | 0.64%   |
| FORESEE             | 2         | 2      | 0.64%   |
| X12                 | 1         | 1      | 0.32%   |
| WODPOSIT            | 1         | 2      | 0.32%   |
| WDC WDS             | 1         | 1      | 0.32%   |
| VisionTek           | 1         | 2      | 0.32%   |
| USB30               | 1         | 2      | 0.32%   |
| Unknown             | 1         | 1      | 0.32%   |
| T-FORCE             | 1         | 1      | 0.32%   |
| SATAFIRM            | 1         | 1      | 0.32%   |
| Qumo                | 1         | 1      | 0.32%   |
| PNY CS90            | 1         | 1      | 0.32%   |
| Plextor             | 1         | 1      | 0.32%   |
| OWC                 | 1         | 1      | 0.32%   |
| Netac               | 1         | 1      | 0.32%   |
| Neo                 | 1         | 1      | 0.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.32%   |
| JMicron Technology  | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 335       | 515    | 36.61%  |
| HDD     | 276       | 488    | 30.16%  |
| SSD     | 260       | 401    | 28.42%  |
| MMC     | 22        | 23     | 2.4%    |
| Unknown | 22        | 22     | 2.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 383       | 826    | 47.93%  |
| NVMe | 335       | 515    | 41.93%  |
| SAS  | 59        | 85     | 7.38%   |
| MMC  | 22        | 23     | 2.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 245       | 380    | 41.46%  |
| 0.51-1.0   | 204       | 285    | 34.52%  |
| 1.01-2.0   | 87        | 140    | 14.72%  |
| 3.01-4.0   | 21        | 36     | 3.55%   |
| 4.01-10.0  | 17        | 21     | 2.88%   |
| 2.01-3.0   | 15        | 24     | 2.54%   |
| 10.01-20.0 | 2         | 3      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 265       | 44.76%  |
| 1001-2000      | 116       | 19.59%  |
| 501-1000       | 78        | 13.18%  |
| 2001-3000      | 62        | 10.47%  |
| 251-500        | 27        | 4.56%   |
| Unknown        | 23        | 3.89%   |
| 1-20           | 15        | 2.53%   |
| 101-250        | 6         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 142       | 23.13%  |
| 251-500        | 104       | 16.94%  |
| 501-1000       | 91        | 14.82%  |
| 1001-2000      | 70        | 11.4%   |
| 51-100         | 67        | 10.91%  |
| More than 3000 | 59        | 9.61%   |
| 2001-3000      | 38        | 6.19%   |
| Unknown        | 23        | 3.75%   |
| 1-20           | 16        | 2.61%   |
| 21-50          | 4         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB                                  | 2         | 2      | 2.99%   |
| Toshiba DT01ACA050 500GB                                  | 2         | 2      | 2.99%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 2         | 3      | 2.99%   |
| Intenso USB 3.0 device 1TB                                | 2         | 2      | 2.99%   |
| HGST HTS725050A7E630 500GB                                | 2         | 5      | 2.99%   |
| HGST HTS721010A9E630 1TB                                  | 2         | 2      | 2.99%   |
| WDC WD6400AAKS-65A7B0 640GB                               | 1         | 1      | 1.49%   |
| WDC WD5000BEVT-60A0RT0 500GB                              | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-60U6AA0 500GB                              | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-003CA0 500GB                               | 1         | 2      | 1.49%   |
| WDC WD5000AAKS-00E4A0 500GB                               | 1         | 1      | 1.49%   |
| WDC WD40EZRZ-00WN9B0 4TB                                  | 1         | 1      | 1.49%   |
| WDC WD30EZRX-00DC0B0 3TB                                  | 1         | 1      | 1.49%   |
| WDC WD30EFRX-68EUZN0 3TB                                  | 1         | 2      | 1.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                  | 1         | 1      | 1.49%   |
| WDC WD20EARX-00PASB0 2TB                                  | 1         | 1      | 1.49%   |
| WDC WD2002FAEX-007BA0 2TB                                 | 1         | 1      | 1.49%   |
| WDC WD15EADS-22P8B0 1TB                                   | 1         | 2      | 1.49%   |
| WDC WD10JPVX-22JC3T0 1TB                                  | 1         | 1      | 1.49%   |
| WDC WD10EZRX-00L4HB0 1TB                                  | 1         | 1      | 1.49%   |
| WDC WD10EZEX-75WN4A1 1TB                                  | 1         | 1      | 1.49%   |
| WDC WD10EZEX-60ZF5A0 1TB                                  | 1         | 1      | 1.49%   |
| WDC WD10EARS-00Y5B1 1TB                                   | 1         | 1      | 1.49%   |
| WDC WD10EALX-009BA0 1TB                                   | 1         | 1      | 1.49%   |
| WDC WD10EADS-22M2B0 1TB                                   | 1         | 1      | 1.49%   |
| WDC WD10EADS-00M2B0 1TB                                   | 1         | 1      | 1.49%   |
| Toshiba DT01ACA100 1TB                                    | 1         | 1      | 1.49%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                      | 1         | 1      | 1.49%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB                     | 1         | 3      | 1.49%   |
| Seagate ST9250827AS 250GB                                 | 1         | 1      | 1.49%   |
| Seagate ST500LT012-1DG142 500GB                           | 1         | 1      | 1.49%   |
| Seagate ST4000DM004-2CV104 4TB                            | 1         | 1      | 1.49%   |
| Seagate ST3000DM003-1F216N 3TB                            | 1         | 1      | 1.49%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                        | 1         | 1      | 1.49%   |
| Seagate ST2000DX002-2DV164 2TB                            | 1         | 2      | 1.49%   |
| Seagate ST2000DM006-2DM164 2TB                            | 1         | 1      | 1.49%   |
| Seagate ST2000DL003-9VT166 2TB                            | 1         | 1      | 1.49%   |
| Seagate ST1000LM048-2E7172 1TB                            | 1         | 1      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 1.49%   |
| Seagate ST1000LM014-1EJ164 1TB                            | 1         | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 20        | 25     | 31.75%  |
| Seagate                   | 11        | 12     | 17.46%  |
| Hitachi                   | 5         | 5      | 7.94%   |
| HGST                      | 5         | 11     | 7.94%   |
| Toshiba                   | 3         | 3      | 4.76%   |
| Samsung Electronics       | 3         | 16     | 4.76%   |
| SK hynix                  | 2         | 4      | 3.17%   |
| SanDisk                   | 2         | 2      | 3.17%   |
| Realtek Semiconductor     | 2         | 3      | 3.17%   |
| Kingston                  | 2         | 2      | 3.17%   |
| Intenso                   | 2         | 2      | 3.17%   |
| OCZ                       | 1         | 1      | 1.59%   |
| Micron/Crucial Technology | 1         | 1      | 1.59%   |
| Hewlett-Packard           | 1         | 1      | 1.59%   |
| Crucial                   | 1         | 1      | 1.59%   |
| Apple                     | 1         | 1      | 1.59%   |
| A-DATA Technology         | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 20        | 25     | 42.55%  |
| Seagate | 11        | 12     | 23.4%   |
| Hitachi | 5         | 5      | 10.64%  |
| HGST    | 5         | 11     | 10.64%  |
| Toshiba | 3         | 3      | 6.38%   |
| Intenso | 2         | 2      | 4.26%   |
| Apple   | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 59     | 71.93%  |
| SSD  | 9         | 10     | 15.79%  |
| NVMe | 7         | 22     | 12.28%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 312       | 674    | 46.36%  |
| Detected | 307       | 684    | 45.62%  |
| Malfunc  | 54        | 91     | 8.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 317       | 36.23%  |
| AMD                            | 183       | 20.91%  |
| Samsung Electronics            | 106       | 12.11%  |
| SanDisk                        | 64        | 7.31%   |
| SK hynix                       | 31        | 3.54%   |
| Phison Electronics             | 29        | 3.31%   |
| Kingston Technology Company    | 24        | 2.74%   |
| Micron/Crucial Technology      | 18        | 2.06%   |
| Silicon Motion                 | 14        | 1.6%    |
| ASMedia Technology             | 13        | 1.49%   |
| Micron Technology              | 12        | 1.37%   |
| ADATA Technology               | 10        | 1.14%   |
| Toshiba America Info Systems   | 9         | 1.03%   |
| KIOXIA                         | 8         | 0.91%   |
| MAXIO Technology (Hangzhou)    | 7         | 0.8%    |
| Marvell Technology Group       | 6         | 0.69%   |
| Union Memory (Shenzhen)        | 5         | 0.57%   |
| Realtek Semiconductor          | 5         | 0.57%   |
| Solid State Storage Technology | 2         | 0.23%   |
| Seagate Technology             | 2         | 0.23%   |
| JMicron Technology             | 2         | 0.23%   |
| Apple                          | 2         | 0.23%   |
| Yangtze Memory Technologies    | 1         | 0.11%   |
| Shenzhen Longsys Electronics   | 1         | 0.11%   |
| Nvidia                         | 1         | 0.11%   |
| LSI Logic / Symbios Logic      | 1         | 0.11%   |
| Lenovo                         | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 137       | 13.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 64        | 6.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 27        | 2.75%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 26        | 2.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 2.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 25        | 2.55%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 19        | 1.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 1.83%   |
| Phison E12 NVMe Controller                                                     | 14        | 1.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13        | 1.32%   |
| Intel SSD 660P Series                                                          | 12        | 1.22%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 11        | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.12%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 0.92%   |
| Phison E16 PCIe4 NVMe Controller                                               | 8         | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 8         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.71%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 7         | 0.71%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 0.71%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 7         | 0.71%   |
| AMD 300 Series Chipset SATA Controller                                         | 7         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 6         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 433       | 51.18%  |
| NVMe | 333       | 39.36%  |
| RAID | 55        | 6.5%    |
| IDE  | 24        | 2.84%   |
| SAS  | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 342       | 58.97%  |
| AMD    | 238       | 41.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 1.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8         | 1.38%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 1.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.03%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 6         | 1.03%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 1.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 1.03%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.86%   |
| Intel 12th Gen Core i5-12600K                 | 5         | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.86%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 5         | 0.86%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 5         | 0.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.86%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 5         | 0.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.69%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.69%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.69%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.69%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 0.69%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 4         | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.69%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.69%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 113       | 19.48%  |
| Intel Core i5           | 98        | 16.9%   |
| AMD Ryzen 7             | 81        | 13.97%  |
| AMD Ryzen 5             | 74        | 12.76%  |
| Other                   | 52        | 8.97%   |
| Intel Core i3           | 37        | 6.38%   |
| AMD Ryzen 9             | 29        | 5%      |
| Intel Celeron           | 13        | 2.24%   |
| AMD Ryzen 3             | 11        | 1.9%    |
| Intel Xeon              | 8         | 1.38%   |
| AMD FX                  | 8         | 1.38%   |
| Intel Pentium           | 6         | 1.03%   |
| Intel Core 2 Duo        | 6         | 1.03%   |
| AMD Ryzen 7 PRO         | 5         | 0.86%   |
| AMD A8                  | 5         | 0.86%   |
| AMD A10                 | 5         | 0.86%   |
| Intel Pentium Silver    | 3         | 0.52%   |
| Intel Pentium Dual-Core | 3         | 0.52%   |
| Intel Core i9           | 3         | 0.52%   |
| AMD Ryzen Threadripper  | 3         | 0.52%   |
| AMD A6                  | 3         | 0.52%   |
| AMD A4                  | 3         | 0.52%   |
| AMD Phenom II X6        | 2         | 0.34%   |
| AMD Athlon              | 2         | 0.34%   |
| Intel Core m3           | 1         | 0.17%   |
| Intel Core 2 Quad       | 1         | 0.17%   |
| AMD Turion              | 1         | 0.17%   |
| AMD Phenom II X4        | 1         | 0.17%   |
| AMD Phenom II X2        | 1         | 0.17%   |
| AMD EPYC                | 1         | 0.17%   |
| AMD Athlon X4           | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 182       | 31.38%  |
| 2      | 144       | 24.83%  |
| 8      | 110       | 18.97%  |
| 6      | 99        | 17.07%  |
| 12     | 18        | 3.1%    |
| 16     | 8         | 1.38%   |
| 10     | 8         | 1.38%   |
| 14     | 5         | 0.86%   |
| 24     | 2         | 0.34%   |
| 48     | 1         | 0.17%   |
| 20     | 1         | 0.17%   |
| 3      | 1         | 0.17%   |
| 1      | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 578       | 99.66%  |
| 2      | 2         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 489       | 84.31%  |
| 1      | 91        | 15.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 580       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 313       | 52.69%  |
| 0x306a9    | 18        | 3.03%   |
| 0x0a50000c | 17        | 2.86%   |
| 0x206a7    | 14        | 2.36%   |
| 0x08108109 | 13        | 2.19%   |
| 0x306c3    | 11        | 1.85%   |
| 0x08701021 | 11        | 1.85%   |
| 0x806c1    | 10        | 1.68%   |
| 0x0800820d | 10        | 1.68%   |
| 0x906ea    | 9         | 1.52%   |
| 0x0a601203 | 9         | 1.52%   |
| 0x0a50000d | 8         | 1.35%   |
| 0x08600106 | 8         | 1.35%   |
| 0x906e9    | 7         | 1.18%   |
| 0x506e3    | 7         | 1.18%   |
| 0xa0652    | 6         | 1.01%   |
| 0x0a404102 | 6         | 1.01%   |
| 0x0a20120a | 6         | 1.01%   |
| 0x806ea    | 5         | 0.84%   |
| 0x806e9    | 5         | 0.84%   |
| 0x08608103 | 5         | 0.84%   |
| 0x08600103 | 4         | 0.67%   |
| 0xa0653    | 3         | 0.51%   |
| 0x806ec    | 3         | 0.51%   |
| 0x406e3    | 3         | 0.51%   |
| 0x40651    | 3         | 0.51%   |
| 0x0a50000b | 3         | 0.51%   |
| 0x0a201025 | 3         | 0.51%   |
| 0x0a201009 | 3         | 0.51%   |
| 0x08600104 | 3         | 0.51%   |
| 0x08108102 | 3         | 0.51%   |
| 0x08001137 | 3         | 0.51%   |
| 0x06006705 | 3         | 0.51%   |
| 0x906ed    | 2         | 0.34%   |
| 0x906a3    | 2         | 0.34%   |
| 0x90672    | 2         | 0.34%   |
| 0x106e5    | 2         | 0.34%   |
| 0x1067a    | 2         | 0.34%   |
| 0x0a704103 | 2         | 0.34%   |
| 0x0a201204 | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 88        | 15.15%  |
| Zen 3            | 62        | 10.67%  |
| Zen 2            | 52        | 8.95%   |
| Unknown          | 51        | 8.78%   |
| Zen+             | 44        | 7.57%   |
| IvyBridge        | 40        | 6.88%   |
| Haswell          | 39        | 6.71%   |
| SandyBridge      | 28        | 4.82%   |
| Skylake          | 27        | 4.65%   |
| CometLake        | 23        | 3.96%   |
| TigerLake        | 19        | 3.27%   |
| Zen              | 14        | 2.41%   |
| Alderlake Hybrid | 12        | 2.07%   |
| Piledriver       | 10        | 1.72%   |
| Broadwell        | 10        | 1.72%   |
| Penryn           | 9         | 1.55%   |
| IceLake          | 8         | 1.38%   |
| Goldmont plus    | 6         | 1.03%   |
| Excavator        | 6         | 1.03%   |
| Westmere         | 5         | 0.86%   |
| Puma             | 5         | 0.86%   |
| Steamroller      | 4         | 0.69%   |
| Silvermont       | 4         | 0.69%   |
| Nehalem          | 4         | 0.69%   |
| K10              | 4         | 0.69%   |
| Goldmont         | 3         | 0.52%   |
| Jaguar           | 2         | 0.34%   |
| K8 & K10 hybrid  | 1         | 0.17%   |
| Core             | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 272       | 35.98%  |
| Nvidia | 252       | 33.33%  |
| AMD    | 232       | 30.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 28        | 3.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 26        | 3.35%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 24        | 3.09%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 23        | 2.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 20        | 2.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 20        | 2.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 17        | 2.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16        | 2.06%   |
| Intel UHD Graphics 620                                                      | 15        | 1.93%   |
| Intel HD Graphics 630                                                       | 15        | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 15        | 1.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 15        | 1.93%   |
| AMD Lucienne                                                                | 12        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11        | 1.42%   |
| Intel HD Graphics 620                                                       | 11        | 1.42%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11        | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 10        | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 10        | 1.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 10        | 1.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 10        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 10        | 1.29%   |
| AMD Rembrandt [Radeon 680M]                                                 | 9         | 1.16%   |
| AMD Raphael                                                                 | 9         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 8         | 1.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8         | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 1.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 7         | 0.9%    |
| Intel HD Graphics 5500                                                      | 7         | 0.9%    |
| Intel HD Graphics 530                                                       | 7         | 0.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 6         | 0.77%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 6         | 0.77%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 6         | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 5         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 5         | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                               | 5         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 0.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 0.64%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 160       | 27.35%  |
| 1 x Intel          | 147       | 25.13%  |
| 1 x Nvidia         | 99        | 16.92%  |
| Intel + Nvidia     | 99        | 16.92%  |
| AMD + Nvidia       | 49        | 8.38%   |
| Intel + AMD        | 13        | 2.22%   |
| 2 x AMD            | 11        | 1.88%   |
| 2 x Nvidia         | 3         | 0.51%   |
| 2 x Intel          | 2         | 0.34%   |
| Intel + 2 x Nvidia | 2         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 380       | 64.74%  |
| Proprietary | 206       | 35.09%  |
| Unknown     | 1         | 0.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 335       | 56.4%   |
| 0.01-0.5   | 59        | 9.93%   |
| 7.01-8.0   | 46        | 7.74%   |
| 1.01-2.0   | 43        | 7.24%   |
| 3.01-4.0   | 36        | 6.06%   |
| 8.01-16.0  | 32        | 5.39%   |
| 5.01-6.0   | 19        | 3.2%    |
| 0.51-1.0   | 14        | 2.36%   |
| 16.01-24.0 | 6         | 1.01%   |
| 2.01-3.0   | 4         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 78        | 11.05%  |
| AU Optronics            | 75        | 10.62%  |
| BOE                     | 61        | 8.64%   |
| Chimei Innolux          | 60        | 8.5%    |
| LG Display              | 48        | 6.8%    |
| Dell                    | 40        | 5.67%   |
| Goldstar                | 35        | 4.96%   |
| Acer                    | 33        | 4.67%   |
| AOC                     | 28        | 3.97%   |
| Hewlett-Packard         | 20        | 2.83%   |
| Sharp                   | 16        | 2.27%   |
| BenQ                    | 16        | 2.27%   |
| PANDA                   | 15        | 2.12%   |
| Ancor Communications    | 13        | 1.84%   |
| Philips                 | 12        | 1.7%    |
| Apple                   | 12        | 1.7%    |
| Lenovo                  | 11        | 1.56%   |
| ASUSTek Computer        | 10        | 1.42%   |
| ViewSonic               | 9         | 1.27%   |
| Unknown                 | 7         | 0.99%   |
| Sony                    | 7         | 0.99%   |
| MSI                     | 7         | 0.99%   |
| Iiyama                  | 6         | 0.85%   |
| Gigabyte Technology     | 6         | 0.85%   |
| NEC Computers           | 5         | 0.71%   |
| Mi                      | 5         | 0.71%   |
| InfoVision              | 4         | 0.57%   |
| Vizio                   | 3         | 0.42%   |
| Insignia                | 3         | 0.42%   |
| HKC                     | 3         | 0.42%   |
| CSO                     | 3         | 0.42%   |
| Chi Mei Optoelectronics | 3         | 0.42%   |
| Toshiba                 | 2         | 0.28%   |
| TMX                     | 2         | 0.28%   |
| Tianma XM               | 2         | 0.28%   |
| LGD                     | 2         | 0.28%   |
| LG Electronics          | 2         | 0.28%   |
| Eizo                    | 2         | 0.28%   |
| Unknown                 | 2         | 0.28%   |
| ___                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.55%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 4         | 0.55%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.41%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.41%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.41%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.41%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3         | 0.41%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                      | 3         | 0.41%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                    | 3         | 0.41%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 2         | 0.27%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch         | 2         | 0.27%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 2         | 0.27%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 2         | 0.27%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 2         | 0.27%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.27%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.27%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2         | 0.27%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 2         | 0.27%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.27%   |
| MSI G273 MSI3CA7 1920x1080 590x330mm 26.6-inch                        | 2         | 0.27%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 2         | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 330       | 49.33%  |
| 1366x768 (WXGA)    | 70        | 10.46%  |
| 3840x2160 (4K)     | 58        | 8.67%   |
| 2560x1440 (QHD)    | 45        | 6.73%   |
| 1920x1200 (WUXGA)  | 19        | 2.84%   |
| 1680x1050 (WSXGA+) | 19        | 2.84%   |
| 3440x1440          | 17        | 2.54%   |
| 1600x900 (HD+)     | 17        | 2.54%   |
| Unknown            | 11        | 1.64%   |
| 1440x900 (WXGA+)   | 9         | 1.35%   |
| 2560x1600          | 8         | 1.2%    |
| 1280x1024 (SXGA)   | 8         | 1.2%    |
| 2560x1080          | 7         | 1.05%   |
| 1280x800 (WXGA)    | 7         | 1.05%   |
| 3840x1080          | 5         | 0.75%   |
| 2880x1800          | 5         | 0.75%   |
| 1360x768           | 3         | 0.45%   |
| 7680x2160          | 2         | 0.3%    |
| 3840x1200          | 2         | 0.3%    |
| 3200x2000          | 2         | 0.3%    |
| 3000x2000          | 2         | 0.3%    |
| 2256x1504          | 2         | 0.3%    |
| 2160x1440          | 2         | 0.3%    |
| 1920x540           | 2         | 0.3%    |
| 1280x720 (HD)      | 2         | 0.3%    |
| 9600x2160          | 1         | 0.15%   |
| 4480x1440          | 1         | 0.15%   |
| 3840x2400          | 1         | 0.15%   |
| 3520x1080          | 1         | 0.15%   |
| 3360x1050          | 1         | 0.15%   |
| 3200x1800 (QHD+)   | 1         | 0.15%   |
| 2880x1440          | 1         | 0.15%   |
| 2736x1824          | 1         | 0.15%   |
| 2288x1287          | 1         | 0.15%   |
| 2240x1400          | 1         | 0.15%   |
| 2048x1152          | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1600x1200          | 1         | 0.15%   |
| 1400x1050          | 1         | 0.15%   |
| 1280x768           | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 197       | 28.39%  |
| 27      | 72        | 10.37%  |
| 24      | 47        | 6.77%   |
| 14      | 47        | 6.77%   |
| Unknown | 45        | 6.48%   |
| 13      | 40        | 5.76%   |
| 23      | 35        | 5.04%   |
| 21      | 29        | 4.18%   |
| 17      | 28        | 4.03%   |
| 31      | 23        | 3.31%   |
| 34      | 17        | 2.45%   |
| 22      | 14        | 2.02%   |
| 16      | 13        | 1.87%   |
| 19      | 11        | 1.59%   |
| 18      | 11        | 1.59%   |
| 20      | 9         | 1.3%    |
| 72      | 8         | 1.15%   |
| 40      | 4         | 0.58%   |
| 25      | 4         | 0.58%   |
| 54      | 3         | 0.43%   |
| 43      | 3         | 0.43%   |
| 28      | 3         | 0.43%   |
| 26      | 3         | 0.43%   |
| 84      | 2         | 0.29%   |
| 74      | 2         | 0.29%   |
| 65      | 2         | 0.29%   |
| 49      | 2         | 0.29%   |
| 48      | 2         | 0.29%   |
| 35      | 2         | 0.29%   |
| 32      | 2         | 0.29%   |
| 29      | 2         | 0.29%   |
| 12      | 2         | 0.29%   |
| 11      | 2         | 0.29%   |
| 142     | 1         | 0.14%   |
| 85      | 1         | 0.14%   |
| 58      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 50      | 1         | 0.14%   |
| 47      | 1         | 0.14%   |
| 46      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 262       | 38.7%   |
| 501-600        | 141       | 20.83%  |
| 401-500        | 66        | 9.75%   |
| Unknown        | 45        | 6.65%   |
| 351-400        | 37        | 5.47%   |
| 601-700        | 36        | 5.32%   |
| 201-300        | 33        | 4.87%   |
| 701-800        | 20        | 2.95%   |
| 1001-1500      | 15        | 2.22%   |
| 1501-2000      | 13        | 1.92%   |
| 801-900        | 6         | 0.89%   |
| 901-1000       | 2         | 0.3%    |
| More than 2000 | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 464       | 74.96%  |
| 16/10   | 72        | 11.63%  |
| Unknown | 39        | 6.3%    |
| 21/9    | 20        | 3.23%   |
| 5/4     | 8         | 1.29%   |
| 3/2     | 7         | 1.13%   |
| 4/3     | 3         | 0.48%   |
| 32/9    | 3         | 0.48%   |
| 3.20    | 1         | 0.16%   |
| 2.00    | 1         | 0.16%   |
| 1.00    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 198       | 29.07%  |
| 201-250        | 97        | 14.24%  |
| 301-350        | 74        | 10.87%  |
| 81-90          | 69        | 10.13%  |
| 351-500        | 49        | 7.2%    |
| Unknown        | 45        | 6.61%   |
| 121-130        | 27        | 3.96%   |
| 151-200        | 26        | 3.82%   |
| More than 1000 | 24        | 3.52%   |
| 251-300        | 18        | 2.64%   |
| 71-80          | 17        | 2.5%    |
| 141-150        | 11        | 1.62%   |
| 501-1000       | 11        | 1.62%   |
| 111-120        | 7         | 1.03%   |
| 91-100         | 3         | 0.44%   |
| 61-70          | 2         | 0.29%   |
| 51-60          | 2         | 0.29%   |
| 131-140        | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 201       | 30.78%  |
| 51-100        | 188       | 28.79%  |
| 101-120       | 137       | 20.98%  |
| Unknown       | 45        | 6.89%   |
| 161-240       | 44        | 6.74%   |
| More than 240 | 20        | 3.06%   |
| 1-50          | 18        | 2.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 437       | 73.82%  |
| 2     | 126       | 21.28%  |
| 3     | 22        | 3.72%   |
| 0     | 5         | 0.84%   |
| 4     | 2         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 351       | 38.28%  |
| Intel                             | 306       | 33.37%  |
| Qualcomm Atheros                  | 75        | 8.18%   |
| MediaTek                          | 45        | 4.91%   |
| Broadcom                          | 38        | 4.14%   |
| TP-Link                           | 10        | 1.09%   |
| NetGear                           | 8         | 0.87%   |
| Samsung Electronics               | 7         | 0.76%   |
| Ralink Technology                 | 7         | 0.76%   |
| DisplayLink                       | 6         | 0.65%   |
| Xiaomi                            | 5         | 0.55%   |
| ASIX Electronics                  | 5         | 0.55%   |
| Microsoft                         | 4         | 0.44%   |
| Linksys                           | 4         | 0.44%   |
| Qualcomm                          | 3         | 0.33%   |
| Dell                              | 3         | 0.33%   |
| Aquantia                          | 3         | 0.33%   |
| Wacom                             | 2         | 0.22%   |
| Ralink                            | 2         | 0.22%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.22%   |
| Ericsson Business Mobile Networks | 2         | 0.22%   |
| D-Link                            | 2         | 0.22%   |
| AVM                               | 2         | 0.22%   |
| ASUSTek Computer                  | 2         | 0.22%   |
| Unknown                           | 2         | 0.22%   |
| ZyXEL Communications              | 1         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.11%   |
| Sitecom Europe                    | 1         | 0.11%   |
| Sierra Wireless                   | 1         | 0.11%   |
| Shenzhen Goodix Technology        | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| Nvidia                            | 1         | 0.11%   |
| Motorola PCS                      | 1         | 0.11%   |
| Marvell Technology Group          | 1         | 0.11%   |
| Lenovo                            | 1         | 0.11%   |
| InterBiometrics                   | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Holtek Semiconductor              | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 234       | 22.03%  |
| Intel Wi-Fi 6 AX200                                               | 52        | 4.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 38        | 3.58%   |
| Intel I211 Gigabit Network Connection                             | 26        | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 2.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 2.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 18        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 1.69%   |
| Intel Wireless 7265                                               | 16        | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 1.41%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 12        | 1.13%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.04%   |
| Intel Wireless-AC 9260                                            | 10        | 0.94%   |
| Intel Wireless 7260                                               | 9         | 0.85%   |
| Intel Wireless 3165                                               | 9         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 9         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 8         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.56%   |
| Intel Wireless 8260                                               | 6         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 244       | 47.66%  |
| Realtek Semiconductor           | 84        | 16.41%  |
| Qualcomm Atheros                | 61        | 11.91%  |
| MediaTek                        | 40        | 7.81%   |
| Broadcom                        | 30        | 5.86%   |
| TP-Link                         | 9         | 1.76%   |
| NetGear                         | 8         | 1.56%   |
| Ralink Technology               | 7         | 1.37%   |
| Microsoft                       | 4         | 0.78%   |
| Linksys                         | 4         | 0.78%   |
| Wacom                           | 2         | 0.39%   |
| Ralink                          | 2         | 0.39%   |
| D-Link                          | 2         | 0.39%   |
| AVM                             | 2         | 0.39%   |
| ASUSTek Computer                | 2         | 0.39%   |
| Unknown                         | 2         | 0.39%   |
| ZyXEL Communications            | 1         | 0.2%    |
| Sitecom Europe                  | 1         | 0.2%    |
| Sierra Wireless                 | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Qualcomm                        | 1         | 0.2%    |
| Hewlett-Packard                 | 1         | 0.2%    |
| Dell                            | 1         | 0.2%    |
| Broadcom Limited                | 1         | 0.2%    |
| Accton Technology               | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 52        | 10.1%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 4.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 3.69%   |
| Intel Wireless 7265                                            | 16        | 3.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 3.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 15        | 2.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 2.91%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 2.91%   |
| Intel Wireless 8265 / 8275                                     | 13        | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 12        | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.14%   |
| Intel Wireless-AC 9260                                         | 10        | 1.94%   |
| Intel Wireless 7260                                            | 9         | 1.75%   |
| Intel Wireless 3165                                            | 9         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.17%   |
| Intel Wireless 8260                                            | 6         | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3         | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 3         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.58%   |
| NetGear A6210                                                  | 3         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 313       | 60.08%  |
| Intel                         | 127       | 24.38%  |
| Qualcomm Atheros              | 23        | 4.41%   |
| Broadcom                      | 19        | 3.65%   |
| DisplayLink                   | 6         | 1.15%   |
| Xiaomi                        | 5         | 0.96%   |
| MediaTek                      | 5         | 0.96%   |
| ASIX Electronics              | 5         | 0.96%   |
| Samsung Electronics           | 3         | 0.58%   |
| Aquantia                      | 3         | 0.58%   |
| Qualcomm                      | 2         | 0.38%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.19%   |
| TP-Link                       | 1         | 0.19%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| Nvidia                        | 1         | 0.19%   |
| Marvell Technology Group      | 1         | 0.19%   |
| Lenovo                        | 1         | 0.19%   |
| ICS Advent                    | 1         | 0.19%   |
| Google                        | 1         | 0.19%   |
| Belkin Components             | 1         | 0.19%   |
| Alteon Networks               | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 234       | 43.98%  |
| Realtek RTL8125 2.5GbE Controller                                 | 38        | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 26        | 4.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.14%   |
| Intel Ethernet Controller I225-V                                  | 18        | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.26%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 2.07%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 1.5%    |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.56%   |
| MediaTek M40Air_EEA                                               | 3         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.56%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.38%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.38%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.38%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 2         | 0.38%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.38%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 484       | 49.54%  |
| WiFi     | 478       | 48.93%  |
| Modem    | 11        | 1.13%   |
| Unknown  | 4         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 363       | 60%     |
| Ethernet | 241       | 39.83%  |
| Modem    | 1         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 318       | 54.45%  |
| 1     | 238       | 40.75%  |
| 3     | 21        | 3.6%    |
| 0     | 4         | 0.68%   |
| 6     | 2         | 0.34%   |
| 4     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 424       | 72.35%  |
| Yes  | 162       | 27.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 212       | 48.4%   |
| Realtek Semiconductor           | 60        | 13.7%   |
| Qualcomm Atheros Communications | 35        | 7.99%   |
| Cambridge Silicon Radio         | 22        | 5.02%   |
| IMC Networks                    | 21        | 4.79%   |
| MediaTek                        | 15        | 3.42%   |
| Foxconn / Hon Hai               | 15        | 3.42%   |
| Broadcom                        | 14        | 3.2%    |
| Lite-On Technology              | 12        | 2.74%   |
| Apple                           | 12        | 2.74%   |
| ASUSTek Computer                | 7         | 1.6%    |
| Dell                            | 4         | 0.91%   |
| Hewlett-Packard                 | 2         | 0.46%   |
| USI                             | 1         | 0.23%   |
| Realtek                         | 1         | 0.23%   |
| Edimax Technology               | 1         | 0.23%   |
| Dynex                           | 1         | 0.23%   |
| Alps Electric                   | 1         | 0.23%   |
| AboCom Systems                  | 1         | 0.23%   |
| Unknown                         | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 50        | 11.42%  |
| Intel Bluetooth wireless interface                  | 49        | 11.19%  |
| Intel AX200 Bluetooth                               | 47        | 10.73%  |
| Realtek Bluetooth Radio                             | 38        | 8.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 25        | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 5.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 3.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 3.65%   |
| MediaTek Wireless_Device                            | 14        | 3.2%    |
| Intel AX210 Bluetooth                               | 13        | 2.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 2.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 2.51%   |
| IMC Networks Wireless_Device                        | 11        | 2.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 2.28%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.83%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.91%   |
| Apple Bluetooth Host Controller                     | 4         | 0.91%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.68%   |
| Lite-On Wireless_Device                             | 3         | 0.68%   |
| Lite-On Bluetooth Device                            | 3         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.68%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.68%   |
| Realtek Bluetooth 5.1 Radio                         | 2         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.46%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.46%   |
| ASUS Bluetooth Radio                                | 2         | 0.46%   |
| ASUS Bluetooth Device                               | 2         | 0.46%   |
| USI Bluetooth Device                                | 1         | 0.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.23%   |
| Realtek Bluetooth Radio                             | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 341       | 37.27%  |
| AMD                       | 259       | 28.31%  |
| Nvidia                    | 182       | 19.89%  |
| C-Media Electronics       | 22        | 2.4%    |
| Logitech                  | 14        | 1.53%   |
| Kingston Technology       | 7         | 0.77%   |
| JMTek                     | 6         | 0.66%   |
| Texas Instruments         | 5         | 0.55%   |
| Sony                      | 5         | 0.55%   |
| Blue Microphones          | 5         | 0.55%   |
| RODE Microphones          | 4         | 0.44%   |
| Generalplus Technology    | 4         | 0.44%   |
| Creative Technology       | 4         | 0.44%   |
| Trust                     | 3         | 0.33%   |
| Focusrite-Novation        | 3         | 0.33%   |
| Corsair                   | 3         | 0.33%   |
| Yamaha                    | 2         | 0.22%   |
| Realtek Semiconductor     | 2         | 0.22%   |
| Razer USA                 | 2         | 0.22%   |
| Micro Star International  | 2         | 0.22%   |
| M-Audio                   | 2         | 0.22%   |
| GN Netcom                 | 2         | 0.22%   |
| DSEA A/S                  | 2         | 0.22%   |
| Digidesign                | 2         | 0.22%   |
| Creative Labs             | 2         | 0.22%   |
| ASUSTek Computer          | 2         | 0.22%   |
| XMOS                      | 1         | 0.11%   |
| Turtle Beach              | 1         | 0.11%   |
| Tenx Technology           | 1         | 0.11%   |
| SteelSeries ApS           | 1         | 0.11%   |
| Sennheiser Communications | 1         | 0.11%   |
| Samson Technologies       | 1         | 0.11%   |
| ROCCAT                    | 1         | 0.11%   |
| Plantronics               | 1         | 0.11%   |
| Phison Electronics        | 1         | 0.11%   |
| KORG                      | 1         | 0.11%   |
| Huawei Technologies       | 1         | 0.11%   |
| Hewlett-Packard           | 1         | 0.11%   |
| Harman International      | 1         | 0.11%   |
| FX200                     | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 124       | 10.84%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 4.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 53        | 4.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 41        | 3.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 3.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 31        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24        | 2.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 23        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 1.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19        | 1.66%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14        | 1.22%   |
| Nvidia GP104 High Definition Audio Controller                              | 13        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 13        | 1.14%   |
| AMD FCH Azalia Controller                                                  | 13        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 1.05%   |
| Nvidia Audio device                                                        | 12        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 11        | 0.96%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                     | 11        | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 0.87%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 9         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8         | 0.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 0.7%    |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 93        | 20.95%  |
| SK hynix                                | 79        | 17.79%  |
| Micron Technology                       | 47        | 10.59%  |
| Kingston                                | 34        | 7.66%   |
| G.Skill                                 | 34        | 7.66%   |
| Crucial                                 | 34        | 7.66%   |
| Corsair                                 | 29        | 6.53%   |
| Unknown                                 | 14        | 3.15%   |
| Ramaxel Technology                      | 11        | 2.48%   |
| A-DATA Technology                       | 11        | 2.48%   |
| Patriot                                 | 9         | 2.03%   |
| Unknown (ABCD)                          | 5         | 1.13%   |
| Team                                    | 5         | 1.13%   |
| Nanya Technology                        | 5         | 1.13%   |
| Unknown                                 | 5         | 1.13%   |
| Patriot Memory (PDP Systems)            | 4         | 0.9%    |
| Smart                                   | 3         | 0.68%   |
| Hewlett-Packard                         | 3         | 0.68%   |
| Transcend                               | 2         | 0.45%   |
| Timetec                                 | 2         | 0.45%   |
| Elpida                                  | 2         | 0.45%   |
| ASint Technology                        | 2         | 0.45%   |
| Wilk                                    | 1         | 0.23%   |
| Smart Brazil                            | 1         | 0.23%   |
| Silicon Power Computer & Communications | 1         | 0.23%   |
| Sesame                                  | 1         | 0.23%   |
| PNY                                     | 1         | 0.23%   |
| GOODRAM                                 | 1         | 0.23%   |
| Essencore                               | 1         | 0.23%   |
| CSX                                     | 1         | 0.23%   |
| Avant                                   | 1         | 0.23%   |
| Apacer                                  | 1         | 0.23%   |
| 48spaces                                | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.91%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.27%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 6         | 1.27%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.06%   |
| Unknown                                                          | 5         | 1.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.85%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 4         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.64%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 0.64%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s                       | 3         | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.64%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s              | 3         | 0.64%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 3         | 0.64%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.64%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 3         | 0.64%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.64%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 3         | 0.64%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2         | 0.42%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.42%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 2         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 245       | 63.97%  |
| DDR3    | 80        | 20.89%  |
| DDR5    | 21        | 5.48%   |
| LPDDR4  | 15        | 3.92%   |
| LPDDR3  | 6         | 1.57%   |
| LPDDR5  | 5         | 1.31%   |
| Unknown | 5         | 1.31%   |
| DDR2    | 4         | 1.04%   |
| SDRAM   | 1         | 0.26%   |
| DRAM    | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 233       | 60.21%  |
| DIMM         | 127       | 32.82%  |
| Row Of Chips | 25        | 6.46%   |
| Chip         | 1         | 0.26%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 208       | 49.17%  |
| 4096  | 97        | 22.93%  |
| 16384 | 86        | 20.33%  |
| 32768 | 21        | 4.96%   |
| 2048  | 10        | 2.36%   |
| 1024  | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 105       | 24.88%  |
| 2667  | 60        | 14.22%  |
| 1600  | 60        | 14.22%  |
| 2400  | 33        | 7.82%   |
| 3600  | 26        | 6.16%   |
| 2133  | 15        | 3.55%   |
| 4800  | 13        | 3.08%   |
| 1333  | 10        | 2.37%   |
| 2933  | 8         | 1.9%    |
| 3666  | 7         | 1.66%   |
| 1334  | 7         | 1.66%   |
| 4266  | 6         | 1.42%   |
| 6400  | 5         | 1.18%   |
| 3733  | 5         | 1.18%   |
| 5600  | 4         | 0.95%   |
| 3533  | 4         | 0.95%   |
| 3266  | 4         | 0.95%   |
| 2666  | 4         | 0.95%   |
| 1800  | 4         | 0.95%   |
| 4267  | 3         | 0.71%   |
| 3000  | 3         | 0.71%   |
| 1867  | 3         | 0.71%   |
| 1866  | 3         | 0.71%   |
| 800   | 3         | 0.71%   |
| 3866  | 2         | 0.47%   |
| 3800  | 2         | 0.47%   |
| 3466  | 2         | 0.47%   |
| 667   | 2         | 0.47%   |
| 8400  | 1         | 0.24%   |
| 7467  | 1         | 0.24%   |
| 6000  | 1         | 0.24%   |
| 5808  | 1         | 0.24%   |
| 5200  | 1         | 0.24%   |
| 4200  | 1         | 0.24%   |
| 4199  | 1         | 0.24%   |
| 4000  | 1         | 0.24%   |
| 3534  | 1         | 0.24%   |
| 3400  | 1         | 0.24%   |
| 3151  | 1         | 0.24%   |
| 2800  | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 35.71%  |
| Brother Industries  | 3         | 21.43%  |
| Samsung Electronics | 2         | 14.29%  |
| Dymo-CoStar         | 2         | 14.29%  |
| Kyocera             | 1         | 7.14%   |
| Fuji Xerox          | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450      | 2         | 14.29%  |
| Brother HL-5370DW series         | 2         | 14.29%  |
| Samsung M337x 387x 407x Series   | 1         | 7.14%   |
| Samsung M267x 287x Series        | 1         | 7.14%   |
| Kyocera FS-1030D printer         | 1         | 7.14%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 7.14%   |
| HP HP OfficeJet Pro 8020 series  | 1         | 7.14%   |
| HP DeskJet Plus 4100 series      | 1         | 7.14%   |
| HP Deskjet 2050 J510             | 1         | 7.14%   |
| HP Color LaserJet CP1215         | 1         | 7.14%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 7.14%   |
| Brother MFC Composite Device     | 1         | 7.14%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 72        | 20.06%  |
| IMC Networks                           | 45        | 12.53%  |
| Logitech                               | 28        | 7.8%    |
| Quanta                                 | 25        | 6.96%   |
| Realtek Semiconductor                  | 24        | 6.69%   |
| Microdia                               | 23        | 6.41%   |
| Sunplus Innovation Technology          | 21        | 5.85%   |
| Bison Electronics                      | 17        | 4.74%   |
| Luxvisions Innotech Limited            | 13        | 3.62%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.06%   |
| Syntek                                 | 10        | 2.79%   |
| Apple                                  | 10        | 2.79%   |
| Microsoft                              | 9         | 2.51%   |
| Suyin                                  | 7         | 1.95%   |
| Lite-On Technology                     | 5         | 1.39%   |
| Sonix Technology                       | 3         | 0.84%   |
| Silicon Motion                         | 3         | 0.84%   |
| Jieli Technology                       | 3         | 0.84%   |
| Creative Technology                    | 3         | 0.84%   |
| SunplusIT                              | 2         | 0.56%   |
| ShineTech                              | 2         | 0.56%   |
| Primax Electronics                     | 2         | 0.56%   |
| Lenovo                                 | 2         | 0.56%   |
| Generalplus Technology                 | 2         | 0.56%   |
| Alcor Micro                            | 2         | 0.56%   |
| Acer                                   | 2         | 0.56%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| WaveRider Communications               | 1         | 0.28%   |
| Trust                                  | 1         | 0.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.28%   |
| Samsung Electronics                    | 1         | 0.28%   |
| Razer USA                              | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| Importek                               | 1         | 0.28%   |
| Genesys Logic                          | 1         | 0.28%   |
| GEMBIRD                                | 1         | 0.28%   |
| ezcap                                  | 1         | 0.28%   |
| DigiTech                               | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 21        | 5.82%   |
| IMC Networks Integrated Camera                       | 15        | 4.16%   |
| Chicony HD WebCam                                    | 13        | 3.6%    |
| Microdia Integrated_Webcam_HD                        | 12        | 3.32%   |
| Chicony Integrated Camera                            | 12        | 3.32%   |
| Syntek Integrated Camera                             | 8         | 2.22%   |
| Sunplus Integrated_Webcam_HD                         | 8         | 2.22%   |
| Apple FaceTime HD Camera                             | 7         | 1.94%   |
| Quanta HD User Facing                                | 6         | 1.66%   |
| Logitech Webcam C270                                 | 6         | 1.66%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 1.66%   |
| Chicony HD User Facing                               | 6         | 1.66%   |
| Bison Integrated Camera                              | 6         | 1.66%   |
| Realtek Integrated_Webcam_HD                         | 5         | 1.39%   |
| Quanta HP Wide Vision HD Camera                      | 5         | 1.39%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 1.39%   |
| Logitech HD Pro Webcam C920                          | 5         | 1.39%   |
| Bison HD Webcam                                      | 5         | 1.39%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 1.11%   |
| Logitech BRIO Ultra HD Webcam                        | 4         | 1.11%   |
| Chicony USB2.0 Camera                                | 4         | 1.11%   |
| Sunplus FHD Camera                                   | 3         | 0.83%   |
| Realtek USB camera                                   | 3         | 0.83%   |
| Quanta HP TrueVision HD Camera                       | 3         | 0.83%   |
| Microsoft LifeCam HD-3000                            | 3         | 0.83%   |
| Logitech Webcam C930e                                | 3         | 0.83%   |
| Lite-On HP Wide Vision HD Camera                     | 3         | 0.83%   |
| Jieli USB PHY 2.0                                    | 3         | 0.83%   |
| IMC Networks HD Camera                               | 3         | 0.83%   |
| Chicony HP Truevision HD                             | 3         | 0.83%   |
| Chicony EasyCamera                                   | 3         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 3         | 0.83%   |
| SunplusIT XiaoMi USB 2.0 Webcam                      | 2         | 0.55%   |
| Sunplus USB Camera                                   | 2         | 0.55%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.55%   |
| Silicon Motion Web Camera                            | 2         | 0.55%   |
| ShineTech USB2.0 HD UVC WebCam                       | 2         | 0.55%   |
| Realtek Integrated Webcam HD                         | 2         | 0.55%   |
| Realtek HP Truevision HD                             | 2         | 0.55%   |
| Realtek Full HD webcam                               | 2         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 30.16%  |
| Synaptics                  | 15        | 23.81%  |
| Elan Microelectronics      | 10        | 15.87%  |
| Shenzhen Goodix Technology | 8         | 12.7%   |
| LighTuning Technology      | 5         | 7.94%   |
| AuthenTec                  | 4         | 6.35%   |
| Samsung Electronics        | 1         | 1.59%   |
| Focal-systems.Corp         | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 6         | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 6.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 6.35%   |
| Elan ELAN:Fingerprint                                                      | 4         | 6.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.76%   |
| Synaptics UWP WBDI                                                         | 3         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.17%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.17%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 3.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 3.17%   |
| AuthenTec AES2810                                                          | 2         | 3.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.59%   |
| Validity Sensors VFS491                                                    | 1         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.59%   |
| Synaptics WBDI Device                                                      | 1         | 1.59%   |
| Synaptics WBDI                                                             | 1         | 1.59%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.59%   |
| Synaptics  WBDI                                                            | 1         | 1.59%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.59%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.59%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 13        | 56.52%  |
| Alcor Micro      | 6         | 26.09%  |
| Upek             | 1         | 4.35%   |
| SCM Microsystems | 1         | 4.35%   |
| O2 Micro         | 1         | 4.35%   |
| Lenovo           | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 26.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 21.74%  |
| Broadcom 5880                                                                | 4         | 17.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.04%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.35%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 4.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 282       | 47.64%  |
| 0     | 203       | 34.29%  |
| 2     | 87        | 14.7%   |
| 3     | 19        | 3.21%   |
| 4     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 327       | 62.88%  |
| Fingerprint reader       | 62        | 11.92%  |
| Graphics card            | 33        | 6.35%   |
| Net/wireless             | 30        | 5.77%   |
| Chipcard                 | 22        | 4.23%   |
| Multimedia controller    | 14        | 2.69%   |
| Camera                   | 9         | 1.73%   |
| Net/ethernet             | 8         | 1.54%   |
| Unassigned class         | 4         | 0.77%   |
| Storage                  | 4         | 0.77%   |
| Network                  | 3         | 0.58%   |
| Bluetooth                | 2         | 0.38%   |
| Wireless                 | 1         | 0.19%   |
| Sound                    | 1         | 0.19%   |

