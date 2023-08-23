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

Total: 845

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Dell          | Latitude E5570              | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Dell          | Precision 3571              | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | 250 G3                      | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Sony          | SVE1713X1EB                 | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| OriginPC      | EVO16-S                     | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | X455LJ                      | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| Dell          | Latitude E5470              | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| ASUSTek       | X455LJ                      | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude E5570              | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| Acer          | Aspire E5-575G              | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Acer          | Aspire E5-573G              | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Dell          | Inspiron 5577               | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | G560 0679                   | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| HUAWEI        | HLYL-WXX9                   | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Dell          | Precision 7720              | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| Dell          | Precision 7720              | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
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
| EndeavourOS Rolling | 529       | 86.16%  |
| EndeavourOS         | 85        | 13.84%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 608       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.2.8-arch1-1     | 15        | 2.21%   |
| 6.3.9-arch1-1     | 9         | 1.32%   |
| 6.3.4-arch1-1     | 8         | 1.18%   |
| 6.2.10-arch1-1    | 8         | 1.18%   |
| 5.19.7-arch1-1    | 8         | 1.18%   |
| 5.15.12-arch1-1   | 8         | 1.18%   |
| 6.3.1-arch1-1     | 7         | 1.03%   |
| 6.2.9-arch1-1     | 7         | 1.03%   |
| 6.1.12-arch1-1    | 7         | 1.03%   |
| 5.13.13-arch1-1   | 7         | 1.03%   |
| 6.4.7-arch1-1     | 6         | 0.88%   |
| 6.2.2-arch1-1     | 6         | 0.88%   |
| 6.2.13-arch1-1    | 6         | 0.88%   |
| 6.1.1-arch1-1     | 6         | 0.88%   |
| 6.0.9-arch1-1     | 6         | 0.88%   |
| 5.15.10-arch1-1   | 6         | 0.88%   |
| 6.4.3-arch1-2     | 5         | 0.74%   |
| 6.4.1-arch2-1     | 5         | 0.74%   |
| 6.2.12-arch1-1    | 5         | 0.74%   |
| 6.0.2-arch1-1     | 5         | 0.74%   |
| 6.0.12-arch1-1    | 5         | 0.74%   |
| 5.9.14-arch1-1    | 5         | 0.74%   |
| 5.19.13-arch1-1   | 5         | 0.74%   |
| 5.19.11-arch1-1   | 5         | 0.74%   |
| 5.18.16-arch1-1   | 5         | 0.74%   |
| 5.15.4-arch1-1    | 5         | 0.74%   |
| 6.3.5-arch1-1     | 4         | 0.59%   |
| 6.2.7-arch1-1     | 4         | 0.59%   |
| 6.2.5-arch1-1     | 4         | 0.59%   |
| 6.1.8-arch1-1     | 4         | 0.59%   |
| 6.1.7-arch1-1     | 4         | 0.59%   |
| 6.1.4-arch1-1     | 4         | 0.59%   |
| 6.1.11-arch1-1    | 4         | 0.59%   |
| 6.0.7-arch1-1     | 4         | 0.59%   |
| 6.0.10-arch2-1    | 4         | 0.59%   |
| 5.9.1-arch1-1     | 4         | 0.59%   |
| 5.7.8-arch1-1     | 4         | 0.59%   |
| 5.19.6-zen1-1-zen | 4         | 0.59%   |
| 5.19.12-arch1-1   | 4         | 0.59%   |
| 5.17.9-arch1-1    | 4         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.8   | 16        | 2.35%   |
| 6.3.1   | 14        | 2.06%   |
| 5.15.12 | 11        | 1.62%   |
| 6.3.9   | 10        | 1.47%   |
| 6.3.4   | 10        | 1.47%   |
| 6.1.1   | 10        | 1.47%   |
| 6.0.2   | 10        | 1.47%   |
| 5.19.7  | 10        | 1.47%   |
| 5.13.13 | 10        | 1.47%   |
| 6.4.7   | 9         | 1.32%   |
| 6.4.3   | 9         | 1.32%   |
| 6.4.1   | 9         | 1.32%   |
| 6.1.12  | 9         | 1.32%   |
| 6.0.9   | 9         | 1.32%   |
| 6.2.9   | 8         | 1.18%   |
| 6.2.10  | 8         | 1.18%   |
| 5.15.4  | 8         | 1.18%   |
| 6.2.2   | 7         | 1.03%   |
| 6.2.13  | 7         | 1.03%   |
| 6.0.12  | 7         | 1.03%   |
| 5.19.13 | 7         | 1.03%   |
| 5.15.2  | 7         | 1.03%   |
| 5.12.13 | 7         | 1.03%   |
| 5.11.16 | 7         | 1.03%   |
| 6.3.5   | 6         | 0.88%   |
| 6.2.12  | 6         | 0.88%   |
| 6.0.6   | 6         | 0.88%   |
| 5.19.6  | 6         | 0.88%   |
| 5.19.11 | 6         | 0.88%   |
| 5.17.5  | 6         | 0.88%   |
| 5.17.1  | 6         | 0.88%   |
| 5.15.10 | 6         | 0.88%   |
| 5.14.9  | 6         | 0.88%   |
| 6.3.6   | 5         | 0.74%   |
| 6.3.2   | 5         | 0.74%   |
| 6.2.7   | 5         | 0.74%   |
| 6.2.5   | 5         | 0.74%   |
| 6.1.9   | 5         | 0.74%   |
| 6.1.8   | 5         | 0.74%   |
| 6.1.7   | 5         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 72        | 10.89%  |
| 6.1     | 71        | 10.74%  |
| 6.2     | 70        | 10.59%  |
| 6.3     | 52        | 7.87%   |
| 5.19    | 52        | 7.87%   |
| 6.0     | 46        | 6.96%   |
| 6.4     | 40        | 6.05%   |
| 5.16    | 37        | 5.6%    |
| 5.14    | 30        | 4.54%   |
| 5.17    | 29        | 4.39%   |
| 5.18    | 24        | 3.63%   |
| 5.13    | 24        | 3.63%   |
| 5.12    | 24        | 3.63%   |
| 5.9     | 21        | 3.18%   |
| 5.11    | 21        | 3.18%   |
| 5.10    | 20        | 3.03%   |
| 5.8     | 9         | 1.36%   |
| 5.7     | 8         | 1.21%   |
| 5.4     | 6         | 0.91%   |
| 5.6     | 2         | 0.3%    |
| 4.19    | 2         | 0.3%    |
| 5.17.1  | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 607       | 99.84%  |
| aarch64 | 1         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 216       | 34.39%  |
| GNOME           | 148       | 23.57%  |
| XFCE            | 127       | 20.22%  |
| X-Cinnamon      | 22        | 3.5%    |
| i3              | 22        | 3.5%    |
| KDE             | 14        | 2.23%   |
| Budgie          | 14        | 2.23%   |
| Unknown         | 14        | 2.23%   |
| sway            | 9         | 1.43%   |
| Cinnamon        | 7         | 1.11%   |
| MATE            | 6         | 0.96%   |
| LXQt            | 5         | 0.8%    |
| Hyprland        | 4         | 0.64%   |
| openbox         | 3         | 0.48%   |
| GNOME Flashback | 3         | 0.48%   |
| bspwm           | 3         | 0.48%   |
| qtile           | 2         | 0.32%   |
| LXDE            | 2         | 0.32%   |
| Deepin          | 2         | 0.32%   |
| awesome         | 2         | 0.32%   |
| xmonad          | 1         | 0.16%   |
| LeftWM          | 1         | 0.16%   |
| GNOME Classic   | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 438       | 70.65%  |
| Wayland | 149       | 24.03%  |
| Tty     | 23        | 3.71%   |
| Unknown | 10        | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 204       | 32.59%  |
| SDDM    | 157       | 25.08%  |
| Unknown | 148       | 23.64%  |
| GDM     | 89        | 14.22%  |
| TDM     | 26        | 4.15%   |
| GREETD  | 2         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 316       | 51.63%  |
| en_GB   | 49        | 8.01%   |
| it_IT   | 40        | 6.54%   |
| de_DE   | 25        | 4.08%   |
| en_CA   | 22        | 3.59%   |
| ru_RU   | 14        | 2.29%   |
| en_IN   | 14        | 2.29%   |
| fr_FR   | 13        | 2.12%   |
| en_AU   | 9         | 1.47%   |
| pt_BR   | 8         | 1.31%   |
| es_ES   | 8         | 1.31%   |
| Unknown | 8         | 1.31%   |
| nl_NL   | 7         | 1.14%   |
| pl_PL   | 6         | 0.98%   |
| fi_FI   | 6         | 0.98%   |
| es_MX   | 6         | 0.98%   |
| en_NZ   | 6         | 0.98%   |
| tr_TR   | 5         | 0.82%   |
| en_PH   | 5         | 0.82%   |
| es_AR   | 4         | 0.65%   |
| sv_SE   | 3         | 0.49%   |
| pt_PT   | 3         | 0.49%   |
| en_DK   | 3         | 0.49%   |
| de_AT   | 3         | 0.49%   |
| zh_CN   | 2         | 0.33%   |
| ru_UA   | 2         | 0.33%   |
| en_SG   | 2         | 0.33%   |
| en_IL   | 2         | 0.33%   |
| en_HK   | 2         | 0.33%   |
| en_AG   | 2         | 0.33%   |
| sr_RS   | 1         | 0.16%   |
| nl_BE   | 1         | 0.16%   |
| ko_KR   | 1         | 0.16%   |
| id_ID   | 1         | 0.16%   |
| hu_HU   | 1         | 0.16%   |
| hr_HR   | 1         | 0.16%   |
| es_US   | 1         | 0.16%   |
| es_PY   | 1         | 0.16%   |
| es_CO   | 1         | 0.16%   |
| en_ZA   | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 411       | 66.61%  |
| BIOS | 206       | 33.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 419       | 68.24%  |
| Btrfs   | 160       | 26.06%  |
| Overlay | 17        | 2.77%   |
| Xfs     | 9         | 1.47%   |
| Tmpfs   | 5         | 0.81%   |
| F2fs    | 2         | 0.33%   |
| Ext2    | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 419       | 68.02%  |
| Unknown | 146       | 23.7%   |
| MBR     | 51        | 8.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 540       | 88.09%  |
| Yes       | 73        | 11.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 448       | 72.26%  |
| Yes       | 172       | 27.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 167       | 27.47%  |
| Hewlett-Packard     | 93        | 15.3%   |
| ASUSTek Computer    | 93        | 15.3%   |
| Dell                | 70        | 11.51%  |
| Acer                | 40        | 6.58%   |
| MSI                 | 24        | 3.95%   |
| Apple               | 21        | 3.45%   |
| HUAWEI              | 14        | 2.3%    |
| Google              | 11        | 1.81%   |
| Timi                | 10        | 1.64%   |
| Toshiba             | 8         | 1.32%   |
| Notebook            | 7         | 1.15%   |
| Sony                | 5         | 0.82%   |
| Samsung Electronics | 4         | 0.66%   |
| TUXEDO              | 3         | 0.49%   |
| Schenker            | 3         | 0.49%   |
| Gigabyte Technology | 3         | 0.49%   |
| Unknown             | 3         | 0.49%   |
| TrekStor            | 2         | 0.33%   |
| Razer               | 2         | 0.33%   |
| Positivo            | 2         | 0.33%   |
| Packard Bell        | 2         | 0.33%   |
| GPD                 | 2         | 0.33%   |
| Chuwi               | 2         | 0.33%   |
| VIT                 | 1         | 0.16%   |
| Teclast             | 1         | 0.16%   |
| Shinelon Computer   | 1         | 0.16%   |
| Radxa               | 1         | 0.16%   |
| Pine Microsystems   | 1         | 0.16%   |
| PC Specialist       | 1         | 0.16%   |
| OriginPC            | 1         | 0.16%   |
| Maibenben           | 1         | 0.16%   |
| ILLEGEAR            | 1         | 0.16%   |
| HONOR               | 1         | 0.16%   |
| Framework           | 1         | 0.16%   |
| eMachines           | 1         | 0.16%   |
| Eluktronics         | 1         | 0.16%   |
| Dynabook            | 1         | 0.16%   |
| AWOW                | 1         | 0.16%   |
| AMI                 | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBookAir7,2                   | 6         | 0.99%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.66%   |
| Unknown                               | 4         | 0.66%   |
| MSI Modern 14 B5M                     | 3         | 0.49%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.49%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.49%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.49%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 3         | 0.49%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.49%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.49%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.49%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.49%   |
| HP Laptop 15-db0xxx                   | 3         | 0.49%   |
| Apple MacBookPro16,2                  | 3         | 0.49%   |
| Acer Aspire E5-575G                   | 3         | 0.49%   |
| Timi TM1701                           | 2         | 0.33%   |
| Timi A35S                             | 2         | 0.33%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.33%   |
| Positivo S14BW01                      | 2         | 0.33%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.33%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.33%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.33%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG      | 2         | 0.33%   |
| Lenovo IdeaPad S340-14API 81NB        | 2         | 0.33%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.33%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.33%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 2         | 0.33%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.33%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 2         | 0.33%   |
| HUAWEI MACH-WX9                       | 2         | 0.33%   |
| HUAWEI HLYL-WXX9                      | 2         | 0.33%   |
| HP ZBook 15 G4                        | 2         | 0.33%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 2         | 0.33%   |
| HP Pavilion dv6                       | 2         | 0.33%   |
| HP Notebook                           | 2         | 0.33%   |
| HP Laptop 15s-eq2xxx                  | 2         | 0.33%   |
| HP Laptop 15-da0xxx                   | 2         | 0.33%   |
| HP ENVY Laptop 13-ba0xxx              | 2         | 0.33%   |
| HP EliteBook 8770w                    | 2         | 0.33%   |
| HP EliteBook 840 G5                   | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 80        | 13.16%  |
| Lenovo IdeaPad     | 45        | 7.4%    |
| ASUS ROG           | 27        | 4.44%   |
| Acer Aspire        | 25        | 4.11%   |
| Dell Latitude      | 24        | 3.95%   |
| HP Pavilion        | 20        | 3.29%   |
| Dell Inspiron      | 20        | 3.29%   |
| HP EliteBook       | 18        | 2.96%   |
| HP Laptop          | 16        | 2.63%   |
| Lenovo Legion      | 14        | 2.3%    |
| ASUS VivoBook      | 12        | 1.97%   |
| Lenovo ThinkBook   | 10        | 1.64%   |
| Dell XPS           | 9         | 1.48%   |
| ASUS ASUS          | 9         | 1.48%   |
| MSI Modern         | 8         | 1.32%   |
| Lenovo Yoga        | 8         | 1.32%   |
| Dell Precision     | 8         | 1.32%   |
| ASUS TUF           | 7         | 1.15%   |
| Toshiba Satellite  | 6         | 0.99%   |
| HP ENVY            | 6         | 0.99%   |
| Apple MacBookAir7  | 6         | 0.99%   |
| Acer Swift         | 6         | 0.99%   |
| HP 255             | 5         | 0.82%   |
| ASUS ZenBook       | 5         | 0.82%   |
| Apple MacBookPro16 | 5         | 0.82%   |
| HP ZBook           | 4         | 0.66%   |
| HP ProBook         | 4         | 0.66%   |
| HP 250             | 4         | 0.66%   |
| Unknown            | 4         | 0.66%   |
| Schenker XMG       | 3         | 0.49%   |
| Notebook NH5x      | 3         | 0.49%   |
| MSI Prestige       | 3         | 0.49%   |
| HUAWEI KLVL-WXX9   | 3         | 0.49%   |
| HP OMEN            | 3         | 0.49%   |
| Dell Vostro        | 3         | 0.49%   |
| Dell G3            | 3         | 0.49%   |
| Apple MacBookPro14 | 3         | 0.49%   |
| Acer TravelMate    | 3         | 0.49%   |
| Acer Extensa       | 3         | 0.49%   |
| Timi TM1701        | 2         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 95        | 15.63%  |
| 2020    | 85        | 13.98%  |
| 2019    | 62        | 10.2%   |
| 2022    | 60        | 9.87%   |
| 2018    | 52        | 8.55%   |
| 2017    | 43        | 7.07%   |
| 2015    | 38        | 6.25%   |
| 2016    | 34        | 5.59%   |
| 2013    | 31        | 5.1%    |
| 2012    | 28        | 4.61%   |
| 2014    | 25        | 4.11%   |
| 2011    | 18        | 2.96%   |
| 2010    | 14        | 2.3%    |
| 2008    | 9         | 1.48%   |
| 2009    | 6         | 0.99%   |
| 2023    | 4         | 0.66%   |
| 2007    | 3         | 0.49%   |
| Unknown | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 608       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 607       | 99.84%  |
| Enabled  | 1         | 0.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 596       | 98.03%  |
| Yes  | 12        | 1.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 175       | 28.69%  |
| 8.01-16.0   | 153       | 25.08%  |
| 16.01-24.0  | 121       | 19.84%  |
| 32.01-64.0  | 67        | 10.98%  |
| 3.01-4.0    | 64        | 10.49%  |
| 24.01-32.0  | 16        | 2.62%   |
| 64.01-256.0 | 8         | 1.31%   |
| 2.01-3.0    | 3         | 0.49%   |
| 1.01-2.0    | 3         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 172       | 26.3%   |
| 1.01-2.0   | 157       | 24.01%  |
| 4.01-8.0   | 136       | 20.8%   |
| 3.01-4.0   | 126       | 19.27%  |
| 8.01-16.0  | 34        | 5.2%    |
| 0.51-1.0   | 22        | 3.36%   |
| 16.01-24.0 | 4         | 0.61%   |
| 0.01-0.5   | 2         | 0.31%   |
| 24.01-32.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 432       | 70.02%  |
| 2      | 165       | 26.74%  |
| 3      | 15        | 2.43%   |
| 4      | 3         | 0.49%   |
| 0      | 2         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 485       | 79.64%  |
| Yes       | 124       | 20.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 451       | 73.81%  |
| No        | 160       | 26.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 604       | 99.18%  |
| No        | 5         | 0.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 557       | 91.16%  |
| No        | 54        | 8.84%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 124       | 20.26%  |
| Italy       | 59        | 9.64%   |
| Germany     | 47        | 7.68%   |
| Canada      | 23        | 3.76%   |
| Netherlands | 20        | 3.27%   |
| India       | 20        | 3.27%   |
| UK          | 19        | 3.1%    |
| Turkey      | 19        | 3.1%    |
| Poland      | 19        | 3.1%    |
| France      | 19        | 3.1%    |
| Russia      | 18        | 2.94%   |
| Brazil      | 18        | 2.94%   |
| Finland     | 16        | 2.61%   |
| Spain       | 13        | 2.12%   |
| Australia   | 9         | 1.47%   |
| Indonesia   | 8         | 1.31%   |
| Sweden      | 7         | 1.14%   |
| Mexico      | 7         | 1.14%   |
| Ukraine     | 6         | 0.98%   |
| Romania     | 6         | 0.98%   |
| New Zealand | 6         | 0.98%   |
| Austria     | 6         | 0.98%   |
| Argentina   | 6         | 0.98%   |
| Vietnam     | 5         | 0.82%   |
| Philippines | 5         | 0.82%   |
| Greece      | 5         | 0.82%   |
| Belgium     | 5         | 0.82%   |
| Bangladesh  | 5         | 0.82%   |
| Switzerland | 4         | 0.65%   |
| Portugal    | 4         | 0.65%   |
| Malaysia    | 4         | 0.65%   |
| Hong Kong   | 4         | 0.65%   |
| Denmark     | 4         | 0.65%   |
| Bahrain     | 4         | 0.65%   |
| Singapore   | 3         | 0.49%   |
| Serbia      | 3         | 0.49%   |
| Norway      | 3         | 0.49%   |
| Kazakhstan  | 3         | 0.49%   |
| Czechia     | 3         | 0.49%   |
| Croatia     | 3         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Helsinki          | 11        | 1.72%   |
| Toms River        | 7         | 1.1%    |
| Milan             | 7         | 1.1%    |
| Istanbul          | 7         | 1.1%    |
| Amsterdam         | 7         | 1.1%    |
| Montreal          | 6         | 0.94%   |
| Sydney            | 5         | 0.78%   |
| St Petersburg     | 5         | 0.78%   |
| Rome              | 5         | 0.78%   |
| Moscow            | 5         | 0.78%   |
| Frankfurt am Main | 5         | 0.78%   |
| Berlin            | 5         | 0.78%   |
| Barberton         | 5         | 0.78%   |
| Warsaw            | 4         | 0.63%   |
| Victoria          | 4         | 0.63%   |
| Portland          | 4         | 0.63%   |
| Paris             | 4         | 0.63%   |
| London            | 4         | 0.63%   |
| Florence          | 4         | 0.63%   |
| Wroclaw           | 3         | 0.47%   |
| Turin             | 3         | 0.47%   |
| Singapore         | 3         | 0.47%   |
| Poznan            | 3         | 0.47%   |
| Mesa              | 3         | 0.47%   |
| Manama            | 3         | 0.47%   |
| Madrid            | 3         | 0.47%   |
| Jacksonville      | 3         | 0.47%   |
| Ho Chi Minh City  | 3         | 0.47%   |
| Hamburg           | 3         | 0.47%   |
| Greeley           | 3         | 0.47%   |
| Dhaka             | 3         | 0.47%   |
| Dallas            | 3         | 0.47%   |
| Central           | 3         | 0.47%   |
| Brussels          | 3         | 0.47%   |
| Belgrade          | 3         | 0.47%   |
| Bandung           | 3         | 0.47%   |
| Auckland          | 3         | 0.47%   |
| Ankara            | 3         | 0.47%   |
| Zurich            | 2         | 0.31%   |
| Yerevan           | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 175       | 219    | 22.21%  |
| SanDisk                        | 69        | 76     | 8.76%   |
| Seagate                        | 60        | 65     | 7.61%   |
| SK hynix                       | 51        | 59     | 6.47%   |
| WDC                            | 50        | 58     | 6.35%   |
| Kingston                       | 43        | 48     | 5.46%   |
| Micron Technology              | 33        | 34     | 4.19%   |
| Toshiba                        | 28        | 31     | 3.55%   |
| Unknown                        | 26        | 34     | 3.3%    |
| Intel                          | 22        | 25     | 2.79%   |
| Crucial                        | 22        | 26     | 2.79%   |
| HGST                           | 20        | 24     | 2.54%   |
| Apple                          | 18        | 22     | 2.28%   |
| KIOXIA                         | 16        | 17     | 2.03%   |
| A-DATA Technology              | 11        | 13     | 1.4%    |
| Kingston Technology Company    | 9         | 11     | 1.14%   |
| Phison Electronics             | 7         | 7      | 0.89%   |
| LITEONIT                       | 7         | 8      | 0.89%   |
| Hitachi                        | 7         | 7      | 0.89%   |
| Phison                         | 6         | 6      | 0.76%   |
| China                          | 6         | 6      | 0.76%   |
| Micron/Crucial Technology      | 5         | 5      | 0.63%   |
| Union Memory (Shenzhen)        | 4         | 4      | 0.51%   |
| Mushkin                        | 4         | 4      | 0.51%   |
| Transcend                      | 3         | 3      | 0.38%   |
| SSSTC                          | 3         | 3      | 0.38%   |
| Solid State Storage Technology | 3         | 5      | 0.38%   |
| PNY                            | 3         | 4      | 0.38%   |
| OCZ                            | 3         | 3      | 0.38%   |
| LITEON                         | 3         | 5      | 0.38%   |
| Lenovo                         | 3         | 3      | 0.38%   |
| Fujitsu                        | 3         | 3      | 0.38%   |
| ADATA Technology               | 3         | 3      | 0.38%   |
| WDC WDS                        | 2         | 2      | 0.25%   |
| Teclast                        | 2         | 4      | 0.25%   |
| Solid State Storage            | 2         | 2      | 0.25%   |
| Silicon Motion                 | 2         | 2      | 0.25%   |
| Shenzhen Longsys Electronics   | 2         | 3      | 0.25%   |
| Realtek                        | 2         | 2      | 0.25%   |
| Patriot                        | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 25        | 3.08%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 17        | 2.09%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 10        | 1.23%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 9         | 1.11%   |
| HGST HTS721010A9E630 1TB                            | 9         | 1.11%   |
| Unknown MMC Card  64GB                              | 7         | 0.86%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.86%   |
| SK hynix HFM001TD3JX013N 1TB                        | 6         | 0.74%   |
| Samsung SSD 870 QVO 1TB                             | 6         | 0.74%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 0.74%   |
| Apple SSD SM0128G 121GB                             | 6         | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.62%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 5         | 0.62%   |
| Samsung SSD 970 EVO 500GB                           | 5         | 0.62%   |
| Samsung SSD 870 EVO 250GB                           | 5         | 0.62%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.62%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.62%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.62%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.62%   |
| KIOXIA KBG40ZNV512G 512GB                           | 5         | 0.62%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 0.62%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 5         | 0.62%   |
| Unknown MMC Card  32GB                              | 4         | 0.49%   |
| Unknown MMC Card  128GB                             | 4         | 0.49%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 4         | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB                      | 4         | 0.49%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 4         | 0.49%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 4         | 0.49%   |
| Samsung MZVLQ512HALU-00000 512GB                    | 4         | 0.49%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 4         | 0.49%   |
| Kingston OM8PCP3512F-AB 512GB                       | 4         | 0.49%   |
| Intel SSD 660P Series 1024GB                        | 4         | 0.49%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.49%   |
| China SSD 256GB                                     | 4         | 0.49%   |
| Apple ANS2 NVMe Controller 500GB                    | 4         | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                              | 3         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 57     | 40.77%  |
| WDC                 | 26        | 29     | 20%     |
| HGST                | 20        | 24     | 15.38%  |
| Toshiba             | 14        | 14     | 10.77%  |
| Hitachi             | 7         | 7      | 5.38%   |
| Fujitsu             | 3         | 3      | 2.31%   |
| Unknown             | 2         | 2      | 1.54%   |
| Maxone              | 2         | 2      | 1.54%   |
| USB3.0              | 1         | 1      | 0.77%   |
| Samsung Electronics | 1         | 1      | 0.77%   |
| Generic-            | 1         | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 93     | 27.8%   |
| Kingston            | 27        | 32     | 10.42%  |
| Crucial             | 19        | 22     | 7.34%   |
| SanDisk             | 18        | 19     | 6.95%   |
| WDC                 | 14        | 18     | 5.41%   |
| Apple               | 10        | 10     | 3.86%   |
| SK hynix            | 9         | 10     | 3.47%   |
| A-DATA Technology   | 8         | 9      | 3.09%   |
| Micron Technology   | 7         | 7      | 2.7%    |
| LITEONIT            | 7         | 8      | 2.7%    |
| China               | 6         | 6      | 2.32%   |
| Toshiba             | 5         | 5      | 1.93%   |
| Seagate             | 4         | 4      | 1.54%   |
| Intel               | 4         | 4      | 1.54%   |
| Transcend           | 3         | 3      | 1.16%   |
| OCZ                 | 3         | 3      | 1.16%   |
| Mushkin             | 3         | 3      | 1.16%   |
| WDC WDS             | 2         | 2      | 0.77%   |
| Teclast             | 2         | 4      | 0.77%   |
| PNY                 | 2         | 3      | 0.77%   |
| Patriot             | 2         | 2      | 0.77%   |
| Netac               | 2         | 3      | 0.77%   |
| LITEON              | 2         | 3      | 0.77%   |
| KingSpec            | 2         | 2      | 0.77%   |
| Gigabyte Technology | 2         | 3      | 0.77%   |
| Corsair             | 2         | 2      | 0.77%   |
| Zheino              | 1         | 1      | 0.39%   |
| WALTON              | 1         | 2      | 0.39%   |
| V-GeN               | 1         | 1      | 0.39%   |
| Unknown             | 1         | 2      | 0.39%   |
| Team                | 1         | 2      | 0.39%   |
| TAMMUZ              | 1         | 4      | 0.39%   |
| StoreJet            | 1         | 1      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| SPCC                | 1         | 1      | 0.39%   |
| OCZ-VERTEX          | 1         | 1      | 0.39%   |
| KingFast            | 1         | 1      | 0.39%   |
| KingDian            | 1         | 1      | 0.39%   |
| KINGBANK            | 1         | 1      | 0.39%   |
| HS-SSD-C100         | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 334       | 426    | 46.45%  |
| SSD     | 227       | 308    | 31.57%  |
| HDD     | 126       | 141    | 17.52%  |
| MMC     | 25        | 32     | 3.48%   |
| Unknown | 7         | 7      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 334       | 422    | 47.99%  |
| SATA | 307       | 420    | 44.11%  |
| SAS  | 30        | 40     | 4.31%   |
| MMC  | 25        | 32     | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 227       | 310    | 64.67%  |
| 0.51-1.0   | 111       | 123    | 31.62%  |
| 1.01-2.0   | 12        | 15     | 3.42%   |
| 3.01-4.0   | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 153       | 24.32%  |
| 251-500        | 125       | 19.87%  |
| 501-1000       | 89        | 14.15%  |
| 1001-2000      | 84        | 13.35%  |
| Unknown        | 44        | 7%      |
| 1-20           | 42        | 6.68%   |
| 51-100         | 30        | 4.77%   |
| More than 3000 | 29        | 4.61%   |
| 21-50          | 17        | 2.7%    |
| 2001-3000      | 16        | 2.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 172       | 26.46%  |
| 21-50          | 115       | 17.69%  |
| 101-250        | 106       | 16.31%  |
| 51-100         | 84        | 12.92%  |
| 251-500        | 61        | 9.38%   |
| Unknown        | 44        | 6.77%   |
| 501-1000       | 35        | 5.38%   |
| 1001-2000      | 23        | 3.54%   |
| More than 3000 | 4         | 0.62%   |
| 0              | 4         | 0.62%   |
| 2001-3000      | 2         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                      | 4         | 6      | 8.16%   |
| HGST HTS721010A9E630 1TB                                        | 3         | 3      | 6.12%   |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 2      | 4.08%   |
| WDC WD5000LPVT-22G33T0 500GB                                    | 1         | 1      | 2.04%   |
| WDC WD10SPZX-24Z10T0 1TB                                        | 1         | 1      | 2.04%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 1         | 1      | 2.04%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB                            | 1         | 1      | 2.04%   |
| Transcend TS240GMTS420S 240GB SSD                               | 1         | 1      | 2.04%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD                        | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD050 500GB                                        | 1         | 1      | 2.04%   |
| Toshiba MK5055GSXF 500GB                                        | 1         | 1      | 2.04%   |
| Toshiba MK2533GSG 250GB                                         | 1         | 1      | 2.04%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 1         | 1      | 2.04%   |
| SSSTC CV8-8E128-HP 128GB SSD                                    | 1         | 1      | 2.04%   |
| SK hynix SC308 SATA 128GB SSD                                   | 1         | 1      | 2.04%   |
| SK hynix PC711 HFS001TDE9X073N 1TB                              | 1         | 1      | 2.04%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                           | 1         | 1      | 2.04%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 1      | 2.04%   |
| SK hynix BC711 HFM001TD3JX013N 1TB                              | 1         | 1      | 2.04%   |
| Seagate ST9750420AS 752GB                                       | 1         | 1      | 2.04%   |
| Seagate ST9320325AS 320GB                                       | 1         | 1      | 2.04%   |
| Seagate ST500LX012-SSHD-8GB                                     | 1         | 1      | 2.04%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 2.04%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 1         | 1      | 2.04%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 2.04%   |
| SanDisk SSD PLUS 240GB                                          | 1         | 1      | 2.04%   |
| SanDisk SD8SNAT128G1002 128GB SSD                               | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 500GB                           | 1         | 1      | 2.04%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 2.04%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD                | 1         | 1      | 2.04%   |
| LITEONIT LCT-512M3S 2.5 7mm 512GB SSD                           | 1         | 1      | 2.04%   |
| Kingston SNS4151S332GD 32GB SSD                                 | 1         | 1      | 2.04%   |
| Intel SSDSCKKF256H6 SATA 256GB                                  | 1         | 1      | 2.04%   |
| Intel SSDSCKJF180A5L 180GB                                      | 1         | 1      | 2.04%   |
| HGST HTS545050A7E380 500GB                                      | 1         | 1      | 2.04%   |
| Fujitsu MHZ2320BH G2 320GB                                      | 1         | 1      | 2.04%   |
| China SSD 256GB                                                 | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 8         | 10     | 16.33%  |
| Seagate             | 7         | 7      | 14.29%  |
| Toshiba             | 6         | 6      | 12.24%  |
| SK hynix            | 5         | 5      | 10.2%   |
| WDC                 | 4         | 4      | 8.16%   |
| Samsung Electronics | 4         | 4      | 8.16%   |
| SanDisk             | 2         | 2      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| Hitachi             | 2         | 2      | 4.08%   |
| Apple               | 2         | 2      | 4.08%   |
| Transcend           | 1         | 1      | 2.04%   |
| SSSTC               | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| Kingston            | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 8         | 10     | 32%     |
| Seagate | 7         | 7      | 28%     |
| Toshiba | 4         | 4      | 16%     |
| WDC     | 3         | 3      | 12%     |
| Hitachi | 2         | 2      | 8%      |
| Fujitsu | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 27     | 51.02%  |
| SSD  | 19        | 19     | 38.78%  |
| NVMe | 5         | 5      | 10.2%   |

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
| Works    | 419       | 579    | 63.68%  |
| Detected | 190       | 282    | 28.88%  |
| Malfunc  | 48        | 51     | 7.29%   |
| Failed   | 1         | 2      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 332       | 42.62%  |
| Samsung Electronics            | 115       | 14.76%  |
| AMD                            | 87        | 11.17%  |
| SanDisk                        | 59        | 7.57%   |
| SK hynix                       | 41        | 5.26%   |
| Micron Technology              | 26        | 3.34%   |
| Kingston Technology Company    | 25        | 3.21%   |
| KIOXIA                         | 19        | 2.44%   |
| Phison Electronics             | 14        | 1.8%    |
| Micron/Crucial Technology      | 8         | 1.03%   |
| Apple                          | 8         | 1.03%   |
| Solid State Storage Technology | 7         | 0.9%    |
| Toshiba America Info Systems   | 6         | 0.77%   |
| ADATA Technology               | 6         | 0.77%   |
| Union Memory (Shenzhen)        | 4         | 0.51%   |
| Seagate Technology             | 3         | 0.39%   |
| Lenovo                         | 3         | 0.39%   |
| Silicon Motion                 | 2         | 0.26%   |
| Shenzhen Longsys Electronics   | 2         | 0.26%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.26%   |
| Lite-On Technology             | 2         | 0.26%   |
| JMicron Technology             | 2         | 0.26%   |
| Yangtze Memory Technologies    | 1         | 0.13%   |
| Realtek Semiconductor          | 1         | 0.13%   |
| Nvidia                         | 1         | 0.13%   |
| Marvell Technology Group       | 1         | 0.13%   |
| INNOGRIT                       | 1         | 0.13%   |
| Biwin Storage Technology       | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 85        | 10.52%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 52        | 6.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 51        | 6.31%   |
| Samsung NVMe SSD Controller 980                                                | 32        | 3.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 29        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 3.22%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 23        | 2.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 23        | 2.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 21        | 2.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 19        | 2.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 1.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 1.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 1.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 14        | 1.73%   |
| Intel Tiger Lake-LP SATA Controller                                            | 14        | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 1.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13        | 1.61%   |
| Intel SSD 660P Series                                                          | 11        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 1.36%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 10        | 1.24%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 8         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.99%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 7         | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 6         | 0.74%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 6         | 0.74%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5         | 0.62%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 5         | 0.62%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 5         | 0.62%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 5         | 0.62%   |
| Apple ANS2 NVMe Controller                                                     | 5         | 0.62%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 0.5%    |
| SK hynix BC511 NVMe SSD                                                        | 4         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 371       | 48.56%  |
| NVMe | 332       | 43.46%  |
| RAID | 53        | 6.94%   |
| IDE  | 8         | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 419       | 68.91%  |
| AMD    | 188       | 30.92%  |
| ARM    | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 1.97%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 1.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1.48%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 9         | 1.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.32%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.15%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 1.15%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 1.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.99%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.82%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.66%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 4         | 0.66%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.66%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 4         | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.66%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.66%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 147       | 24.18%  |
| Intel Core i7           | 129       | 21.22%  |
| Other                   | 70        | 11.51%  |
| AMD Ryzen 7             | 66        | 10.86%  |
| AMD Ryzen 5             | 52        | 8.55%   |
| Intel Core i3           | 30        | 4.93%   |
| Intel Celeron           | 23        | 3.78%   |
| AMD Ryzen 9             | 18        | 2.96%   |
| Intel Core 2 Duo        | 13        | 2.14%   |
| AMD Ryzen 7 PRO         | 13        | 2.14%   |
| AMD Ryzen 3             | 8         | 1.32%   |
| AMD A4                  | 8         | 1.32%   |
| Intel Pentium           | 5         | 0.82%   |
| AMD Ryzen 5 PRO         | 4         | 0.66%   |
| AMD A8                  | 3         | 0.49%   |
| AMD A10                 | 3         | 0.49%   |
| Intel Xeon              | 2         | 0.33%   |
| Intel Core m3           | 2         | 0.33%   |
| Intel Atom              | 2         | 0.33%   |
| AMD E1                  | 2         | 0.33%   |
| AMD Athlon              | 2         | 0.33%   |
| Intel Pentium Dual-Core | 1         | 0.16%   |
| Intel Core m5           | 1         | 0.16%   |
| Intel Core 2 Extreme    | 1         | 0.16%   |
| Intel Core 2            | 1         | 0.16%   |
| AMD E                   | 1         | 0.16%   |
| AMD Athlon II           | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 217       | 35.69%  |
| 4      | 201       | 33.06%  |
| 8      | 102       | 16.78%  |
| 6      | 67        | 11.02%  |
| 14     | 13        | 2.14%   |
| 12     | 4         | 0.66%   |
| 10     | 3         | 0.49%   |
| 1      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 607       | 99.84%  |
| 2      | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 524       | 86.18%  |
| 1      | 84        | 13.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 606       | 99.67%  |
| 64-bit         | 1         | 0.16%   |
| Unknown        | 1         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 237       | 38.35%  |
| 0x0a50000c | 29        | 4.69%   |
| 0x806ec    | 18        | 2.91%   |
| 0x406e3    | 18        | 2.91%   |
| 0x306a9    | 17        | 2.75%   |
| 0x806ea    | 15        | 2.43%   |
| 0x806c1    | 15        | 2.43%   |
| 0x40651    | 15        | 2.43%   |
| 0x08600106 | 14        | 2.27%   |
| 0x08108109 | 14        | 2.27%   |
| 0x906ea    | 13        | 2.1%    |
| 0x806e9    | 13        | 2.1%    |
| 0x08600104 | 13        | 2.1%    |
| 0x306c3    | 12        | 1.94%   |
| 0x08608103 | 12        | 1.94%   |
| 0x08108102 | 10        | 1.62%   |
| 0x906e9    | 9         | 1.46%   |
| 0x506e3    | 9         | 1.46%   |
| 0x306d4    | 9         | 1.46%   |
| 0x206a7    | 9         | 1.46%   |
| 0x0a404102 | 9         | 1.46%   |
| 0x906a3    | 8         | 1.29%   |
| 0x706e5    | 7         | 1.13%   |
| 0x1067a    | 7         | 1.13%   |
| 0x0a50000d | 7         | 1.13%   |
| 0xa0652    | 6         | 0.97%   |
| 0x806d1    | 6         | 0.97%   |
| 0x406c4    | 6         | 0.97%   |
| 0x706a1    | 5         | 0.81%   |
| 0x20655    | 5         | 0.81%   |
| 0x0a404101 | 5         | 0.81%   |
| 0x06006705 | 5         | 0.81%   |
| 0x906ed    | 2         | 0.32%   |
| 0x906c0    | 2         | 0.32%   |
| 0x806eb    | 2         | 0.32%   |
| 0x406c3    | 2         | 0.32%   |
| 0x10676    | 2         | 0.32%   |
| 0x0a50000b | 2         | 0.32%   |
| 0x08608104 | 2         | 0.32%   |
| 0x08608102 | 2         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 127       | 20.89%  |
| Zen 3            | 47        | 7.73%   |
| Unknown          | 47        | 7.73%   |
| Zen 2            | 43        | 7.07%   |
| Haswell          | 43        | 7.07%   |
| Skylake          | 39        | 6.41%   |
| TigerLake        | 32        | 5.26%   |
| Zen+             | 31        | 5.1%    |
| IvyBridge        | 31        | 5.1%    |
| Broadwell        | 22        | 3.62%   |
| SandyBridge      | 18        | 2.96%   |
| IceLake          | 18        | 2.96%   |
| Alderlake Hybrid | 18        | 2.96%   |
| Penryn           | 13        | 2.14%   |
| CometLake        | 13        | 2.14%   |
| Silvermont       | 12        | 1.97%   |
| Excavator        | 12        | 1.97%   |
| Westmere         | 11        | 1.81%   |
| Goldmont plus    | 8         | 1.32%   |
| Jaguar           | 6         | 0.99%   |
| Tremont          | 3         | 0.49%   |
| Piledriver       | 3         | 0.49%   |
| Core             | 3         | 0.49%   |
| Zen              | 2         | 0.33%   |
| Puma             | 2         | 0.33%   |
| Goldmont         | 2         | 0.33%   |
| K10              | 1         | 0.16%   |
| Bobcat           | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 392       | 48.94%  |
| AMD    | 208       | 25.97%  |
| Nvidia | 201       | 25.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 42        | 5.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 35        | 4.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 3.76%   |
| Intel UHD Graphics 620                                                                   | 29        | 3.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 3.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 2.91%   |
| AMD Rembrandt [Radeon 680M]                                                              | 21        | 2.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.31%   |
| AMD Lucienne                                                                             | 19        | 2.31%   |
| Intel HD Graphics 620                                                                    | 18        | 2.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 2.06%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 16        | 1.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 1.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.58%   |
| Intel HD Graphics 630                                                                    | 11        | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 10        | 1.21%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.21%   |
| Intel HD Graphics 530                                                                    | 9         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.97%   |
| AMD Barcelo                                                                              | 8         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.73%   |
| Nvidia GM108M [GeForce 940M]                                                             | 6         | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.73%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.73%   |
| Intel HD Graphics 6000                                                                   | 6         | 0.73%   |
| Nvidia TU117M                                                                            | 5         | 0.61%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 234       | 38.49%  |
| Intel + Nvidia | 137       | 22.53%  |
| 1 x AMD        | 132       | 21.71%  |
| AMD + Nvidia   | 40        | 6.58%   |
| 1 x Nvidia     | 23        | 3.78%   |
| 2 x AMD        | 20        | 3.29%   |
| Intel + AMD    | 16        | 2.63%   |
| 2 x Intel      | 4         | 0.66%   |
| Other          | 2         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 468       | 76.72%  |
| Proprietary | 141       | 23.11%  |
| Unknown     | 1         | 0.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 405       | 65.64%  |
| 0.01-0.5   | 87        | 14.1%   |
| 1.01-2.0   | 51        | 8.27%   |
| 3.01-4.0   | 28        | 4.54%   |
| 0.51-1.0   | 17        | 2.76%   |
| 7.01-8.0   | 11        | 1.78%   |
| 5.01-6.0   | 10        | 1.62%   |
| 2.01-3.0   | 6         | 0.97%   |
| 8.01-16.0  | 2         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 142       | 19.53%  |
| BOE                     | 108       | 14.86%  |
| Chimei Innolux          | 106       | 14.58%  |
| LG Display              | 83        | 11.42%  |
| Samsung Electronics     | 52        | 7.15%   |
| PANDA                   | 25        | 3.44%   |
| Apple                   | 21        | 2.89%   |
| Sharp                   | 18        | 2.48%   |
| Goldstar                | 18        | 2.48%   |
| Dell                    | 17        | 2.34%   |
| Lenovo                  | 15        | 2.06%   |
| Acer                    | 11        | 1.51%   |
| Philips                 | 9         | 1.24%   |
| InfoVision              | 9         | 1.24%   |
| AOC                     | 9         | 1.24%   |
| CSO                     | 8         | 1.1%    |
| TMX                     | 7         | 0.96%   |
| BenQ                    | 7         | 0.96%   |
| Chi Mei Optoelectronics | 6         | 0.83%   |
| Ancor Communications    | 6         | 0.83%   |
| Iiyama                  | 5         | 0.69%   |
| Hewlett-Packard         | 5         | 0.69%   |
| ViewSonic               | 4         | 0.55%   |
| Sony                    | 3         | 0.41%   |
| Pixio                   | 3         | 0.41%   |
| LG Philips              | 3         | 0.41%   |
| JDI                     | 3         | 0.41%   |
| Toshiba                 | 2         | 0.28%   |
| InnoLux Display         | 2         | 0.28%   |
| HKC                     | 2         | 0.28%   |
| Gigabyte Technology     | 2         | 0.28%   |
| ASUSTek Computer        | 2         | 0.28%   |
| Vizio                   | 1         | 0.14%   |
| Unknown (XXX)           | 1         | 0.14%   |
| Unknown                 | 1         | 0.14%   |
| Sun                     | 1         | 0.14%   |
| RTK                     | 1         | 0.14%   |
| Panasonic               | 1         | 0.14%   |
| MSI                     | 1         | 0.14%   |
| HUAWEI                  | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 1.09%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.95%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.82%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch          | 5         | 0.68%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.54%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 4         | 0.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.54%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.54%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.41%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 3         | 0.41%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.41%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 3         | 0.41%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 3         | 0.41%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.41%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.41%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 3         | 0.41%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 0.41%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.41%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch        | 3         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 353       | 51.99%  |
| 1366x768 (WXGA)    | 137       | 20.18%  |
| 2560x1440 (QHD)    | 32        | 4.71%   |
| 2560x1600          | 27        | 3.98%   |
| 3840x2160 (4K)     | 24        | 3.53%   |
| 1440x900 (WXGA+)   | 17        | 2.5%    |
| 2880x1800          | 11        | 1.62%   |
| 1920x1200 (WUXGA)  | 10        | 1.47%   |
| 1280x800 (WXGA)    | 9         | 1.33%   |
| 2160x1440          | 7         | 1.03%   |
| 1600x900 (HD+)     | 7         | 1.03%   |
| 2560x1080          | 6         | 0.88%   |
| 3840x2400          | 5         | 0.74%   |
| 3440x1440          | 4         | 0.59%   |
| 3200x2000          | 4         | 0.59%   |
| 1680x1050 (WSXGA+) | 4         | 0.59%   |
| 3456x2160          | 3         | 0.44%   |
| 3072x1920          | 3         | 0.44%   |
| 3200x1800 (QHD+)   | 2         | 0.29%   |
| 3000x2000          | 2         | 0.29%   |
| 1360x768           | 2         | 0.29%   |
| 1280x1024 (SXGA)   | 2         | 0.29%   |
| Unknown            | 2         | 0.29%   |
| 3840x1100          | 1         | 0.15%   |
| 3840x1080          | 1         | 0.15%   |
| 2520x1680          | 1         | 0.15%   |
| 2256x1504          | 1         | 0.15%   |
| 2240x1400          | 1         | 0.15%   |
| 1920x1280          | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 281       | 38.34%  |
| 13      | 109       | 14.87%  |
| 14      | 98        | 13.37%  |
| 17      | 39        | 5.32%   |
| 27      | 33        | 4.5%    |
| 16      | 26        | 3.55%   |
| 24      | 24        | 3.27%   |
| 23      | 19        | 2.59%   |
| 12      | 17        | 2.32%   |
| 21      | 14        | 1.91%   |
| 31      | 11        | 1.5%    |
| 11      | 11        | 1.5%    |
| 18      | 7         | 0.95%   |
| 34      | 5         | 0.68%   |
| 54      | 3         | 0.41%   |
| 29      | 3         | 0.41%   |
| Unknown | 3         | 0.41%   |
| 58      | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 35      | 2         | 0.27%   |
| 26      | 2         | 0.27%   |
| 25      | 2         | 0.27%   |
| 22      | 2         | 0.27%   |
| 20      | 2         | 0.27%   |
| 19      | 2         | 0.27%   |
| 10      | 2         | 0.27%   |
| 84      | 1         | 0.14%   |
| 74      | 1         | 0.14%   |
| 72      | 1         | 0.14%   |
| 65      | 1         | 0.14%   |
| 57      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 49      | 1         | 0.14%   |
| 46      | 1         | 0.14%   |
| 42      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |
| 28      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 449       | 61.93%  |
| 201-300     | 84        | 11.59%  |
| 501-600     | 76        | 10.48%  |
| 351-400     | 49        | 6.76%   |
| 401-500     | 26        | 3.59%   |
| 601-700     | 15        | 2.07%   |
| 1001-1500   | 8         | 1.1%    |
| 701-800     | 6         | 0.83%   |
| 801-900     | 4         | 0.55%   |
| 1501-2000   | 3         | 0.41%   |
| Unknown     | 3         | 0.41%   |
| 101-200     | 1         | 0.14%   |
| 901-1000    | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 510       | 80.95%  |
| 16/10   | 89        | 14.13%  |
| 3/2     | 14        | 2.22%   |
| 21/9    | 7         | 1.11%   |
| 2.65    | 3         | 0.48%   |
| 4/3     | 2         | 0.32%   |
| Unknown | 2         | 0.32%   |
| 5/4     | 1         | 0.16%   |
| 3.40    | 1         | 0.16%   |
| 0.62    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 283       | 38.87%  |
| 81-90          | 166       | 22.8%   |
| 201-250        | 48        | 6.59%   |
| 71-80          | 39        | 5.36%   |
| 301-350        | 35        | 4.81%   |
| 121-130        | 35        | 4.81%   |
| 111-120        | 24        | 3.3%    |
| 351-500        | 20        | 2.75%   |
| 61-70          | 15        | 2.06%   |
| 51-60          | 12        | 1.65%   |
| More than 1000 | 10        | 1.37%   |
| 251-300        | 10        | 1.37%   |
| 151-200        | 7         | 0.96%   |
| 141-150        | 7         | 0.96%   |
| 131-140        | 4         | 0.55%   |
| 501-1000       | 4         | 0.55%   |
| 91-100         | 3         | 0.41%   |
| Unknown        | 3         | 0.41%   |
| 41-50          | 2         | 0.27%   |
| 1-40           | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 343       | 47.97%  |
| 101-120       | 150       | 20.98%  |
| 51-100        | 91        | 12.73%  |
| 161-240       | 83        | 11.61%  |
| More than 240 | 35        | 4.9%    |
| 1-50          | 10        | 1.4%    |
| Unknown       | 3         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 489       | 78.87%  |
| 2     | 121       | 19.52%  |
| 3     | 8         | 1.29%   |
| 0     | 2         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 351       | 36.79%  |
| Realtek Semiconductor             | 347       | 36.37%  |
| Qualcomm Atheros                  | 95        | 9.96%   |
| MediaTek                          | 46        | 4.82%   |
| Broadcom                          | 31        | 3.25%   |
| Broadcom Limited                  | 11        | 1.15%   |
| ASIX Electronics                  | 11        | 1.15%   |
| TP-Link                           | 7         | 0.73%   |
| D-Link                            | 7         | 0.73%   |
| Lenovo                            | 5         | 0.52%   |
| Ralink                            | 4         | 0.42%   |
| Hewlett-Packard                   | 4         | 0.42%   |
| Apple                             | 4         | 0.42%   |
| Sierra Wireless                   | 3         | 0.31%   |
| DisplayLink                       | 3         | 0.31%   |
| Cypress Semiconductor             | 3         | 0.31%   |
| Samsung Electronics               | 2         | 0.21%   |
| Qualcomm                          | 2         | 0.21%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.21%   |
| Huawei Technologies               | 2         | 0.21%   |
| Ericsson Business Mobile Networks | 2         | 0.21%   |
| Quectel Wireless Solutions        | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| NetGear                           | 1         | 0.1%    |
| Microsoft                         | 1         | 0.1%    |
| Marvell Technology Group          | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Google                            | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Dell                              | 1         | 0.1%    |
| D-Link System                     | 1         | 0.1%    |
| Belkin Components                 | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 238       | 21.06%  |
| Intel Wi-Fi 6 AX200                                               | 51        | 4.51%   |
| Intel Wireless 8265 / 8275                                        | 31        | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 30        | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 2.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 23        | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 2.04%   |
| Intel Wireless 7265                                               | 23        | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 2.04%   |
| Intel Wireless 7260                                               | 21        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 18        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 1.42%   |
| Intel Wireless 8260                                               | 15        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.06%   |
| Intel Wireless 3165                                               | 12        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 11        | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 8         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 8         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.71%   |
| Realtek 802.11ac NIC                                              | 7         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 7         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 346       | 54.23%  |
| Realtek Semiconductor             | 100       | 15.67%  |
| Qualcomm Atheros                  | 81        | 12.7%   |
| MediaTek                          | 45        | 7.05%   |
| Broadcom                          | 25        | 3.92%   |
| Broadcom Limited                  | 11        | 1.72%   |
| D-Link                            | 7         | 1.1%    |
| TP-Link                           | 6         | 0.94%   |
| Ralink                            | 4         | 0.63%   |
| Sierra Wireless                   | 3         | 0.47%   |
| Qualcomm                          | 2         | 0.31%   |
| Quectel Wireless Solutions        | 1         | 0.16%   |
| Microsoft                         | 1         | 0.16%   |
| Linksys                           | 1         | 0.16%   |
| Fibocom                           | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| Belkin Components                 | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 51        | 7.92%   |
| Intel Wireless 8265 / 8275                                     | 31        | 4.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 30        | 4.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 4.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 23        | 3.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 3.57%   |
| Intel Wireless 7265                                            | 23        | 3.57%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 3.57%   |
| Intel Wireless 7260                                            | 21        | 3.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 2.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 18        | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 2.48%   |
| Intel Wireless 8260                                            | 15        | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 1.86%   |
| Intel Wireless 3165                                            | 12        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 1.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 1.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 1.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.24%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 8         | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.24%   |
| Realtek 802.11ac NIC                                           | 7         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 7         | 1.09%   |
| Intel Wireless-AC 9260                                         | 6         | 0.93%   |
| Intel Wireless 3160                                            | 6         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.93%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 0.93%   |
| D-Link 802.11ac NIC                                            | 6         | 0.93%   |
| TP-Link 802.11ac NIC                                           | 5         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 302       | 64.39%  |
| Intel                         | 98        | 20.9%   |
| Qualcomm Atheros              | 25        | 5.33%   |
| ASIX Electronics              | 11        | 2.35%   |
| Broadcom                      | 9         | 1.92%   |
| Lenovo                        | 4         | 0.85%   |
| Apple                         | 4         | 0.85%   |
| DisplayLink                   | 3         | 0.64%   |
| Cypress Semiconductor         | 3         | 0.64%   |
| TP-Link                       | 1         | 0.21%   |
| Samsung Electronics           | 1         | 0.21%   |
| OPPO Electronics              | 1         | 0.21%   |
| OnePlus Technology (Shenzhen) | 1         | 0.21%   |
| NetGear                       | 1         | 0.21%   |
| MediaTek                      | 1         | 0.21%   |
| Marvell Technology Group      | 1         | 0.21%   |
| ICS Advent                    | 1         | 0.21%   |
| Hewlett-Packard               | 1         | 0.21%   |
| Google                        | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 238       | 49.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 6.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.26%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.84%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.84%   |
| Apple iBridge                                                     | 4         | 0.84%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.63%   |
| Cypress USB-C Dock ETH                                            | 3         | 0.63%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.42%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.42%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.42%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.21%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 604       | 57.03%  |
| Ethernet | 446       | 42.12%  |
| Modem    | 8         | 0.76%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 539       | 83.44%  |
| Ethernet | 107       | 16.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 402       | 66.01%  |
| 1     | 197       | 32.35%  |
| 3     | 6         | 0.99%   |
| 0     | 4         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 485       | 78.73%  |
| Yes  | 131       | 21.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 303       | 53.06%  |
| Realtek Semiconductor           | 68        | 11.91%  |
| Qualcomm Atheros Communications | 39        | 6.83%   |
| IMC Networks                    | 31        | 5.43%   |
| Foxconn / Hon Hai               | 30        | 5.25%   |
| Lite-On Technology              | 24        | 4.2%    |
| Broadcom                        | 20        | 3.5%    |
| Apple                           | 13        | 2.28%   |
| Realtek                         | 7         | 1.23%   |
| MediaTek                        | 7         | 1.23%   |
| Cambridge Silicon Radio         | 6         | 1.05%   |
| Toshiba                         | 4         | 0.7%    |
| Ralink                          | 4         | 0.7%    |
| Dell                            | 4         | 0.7%    |
| Hewlett-Packard                 | 3         | 0.53%   |
| USI                             | 2         | 0.35%   |
| Opticis                         | 2         | 0.35%   |
| TP-Link                         | 1         | 0.18%   |
| Foxconn International           | 1         | 0.18%   |
| ASUSTek Computer                | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 115       | 20.1%   |
| Intel AX201 Bluetooth                               | 57        | 9.97%   |
| Intel AX200 Bluetooth                               | 51        | 8.92%   |
| Realtek Bluetooth Radio                             | 45        | 7.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 37        | 6.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 23        | 4.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 2.62%   |
| Intel Bluetooth Device                              | 15        | 2.62%   |
| Intel AX210 Bluetooth                               | 14        | 2.45%   |
| IMC Networks Wireless_Device                        | 13        | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 1.75%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 1.57%   |
| Apple Bluetooth USB Host Controller                 | 9         | 1.57%   |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.22%   |
| MediaTek Wireless_Device                            | 7         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.05%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.87%   |
| Lite-On Bluetooth Device                            | 5         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.87%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.7%    |
| IMC Networks Bluetooth Device                       | 4         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.7%    |
| Realtek RTL8821A Bluetooth                          | 3         | 0.52%   |
| Lite-On Wireless_Device                             | 3         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.52%   |
| USI Bluetooth Device                                | 2         | 0.35%   |
| Toshiba BCM43142A0                                  | 2         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.35%   |
| Opticis Bluetooth Radio                             | 2         | 0.35%   |
| Lite-On Bluetooth Radio                             | 2         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 414       | 50.99%  |
| AMD                                             | 196       | 24.14%  |
| Nvidia                                          | 117       | 14.41%  |
| C-Media Electronics                             | 10        | 1.23%   |
| Texas Instruments                               | 8         | 0.99%   |
| Lenovo                                          | 6         | 0.74%   |
| KORG                                            | 6         | 0.74%   |
| Apple                                           | 5         | 0.62%   |
| AKAI                                            | 5         | 0.62%   |
| Realtek Semiconductor                           | 4         | 0.49%   |
| Corsair                                         | 4         | 0.49%   |
| Sony                                            | 3         | 0.37%   |
| Logitech                                        | 3         | 0.37%   |
| Kingston Technology                             | 3         | 0.37%   |
| Creative Technology                             | 3         | 0.37%   |
| Samson Technologies                             | 2         | 0.25%   |
| JMTek                                           | 2         | 0.25%   |
| GYROCOM C&C                                     | 2         | 0.25%   |
| Generalplus Technology                          | 2         | 0.25%   |
| YZ Technology                                   | 1         | 0.12%   |
| XMOS                                            | 1         | 0.12%   |
| Tenx Technology                                 | 1         | 0.12%   |
| Tdlasunnic                                      | 1         | 0.12%   |
| ROCCAT                                          | 1         | 0.12%   |
| NAD Electronics                                 | 1         | 0.12%   |
| Micro Star International                        | 1         | 0.12%   |
| M-Audio                                         | 1         | 0.12%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.12%   |
| LG Electronics                                  | 1         | 0.12%   |
| Focusrite-Novation                              | 1         | 0.12%   |
| Conexant Systems                                | 1         | 0.12%   |
| Beyerdynamic                                    | 1         | 0.12%   |
| ASUSTek Computer                                | 1         | 0.12%   |
| Asahi Kasei Microsystems                        | 1         | 0.12%   |
| Anlya.cn                                        | 1         | 0.12%   |
| AKAI Professional M.I.                          | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 156       | 14.83%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 95        | 9.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 80        | 7.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 32        | 3.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 3.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 2.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 2.09%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 2.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 21        | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 1.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 18        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 1.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 15        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 1.33%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 12        | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 11        | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 1.05%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 10        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 9         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 8         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.67%   |
| Nvidia Audio device                                                                               | 6         | 0.57%   |
| AMD Navi 10 HDMI Audio                                                                            | 6         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 180       | 32.09%  |
| SK hynix            | 135       | 24.06%  |
| Micron Technology   | 86        | 15.33%  |
| Kingston            | 35        | 6.24%   |
| Crucial             | 26        | 4.63%   |
| Unknown             | 18        | 3.21%   |
| Ramaxel Technology  | 12        | 2.14%   |
| A-DATA Technology   | 9         | 1.6%    |
| Corsair             | 8         | 1.43%   |
| Elpida              | 7         | 1.25%   |
| G.Skill             | 6         | 1.07%   |
| Unknown (ABCD)      | 5         | 0.89%   |
| Team                | 4         | 0.71%   |
| Unknown             | 4         | 0.71%   |
| Nanya Technology    | 3         | 0.53%   |
| Kllisre             | 3         | 0.53%   |
| Teikon              | 2         | 0.36%   |
| Shenzhen Mic        | 2         | 0.36%   |
| Hikvision           | 2         | 0.36%   |
| V-GeN               | 1         | 0.18%   |
| Transcend           | 1         | 0.18%   |
| Toshiba             | 1         | 0.18%   |
| Smart Brazil        | 1         | 0.18%   |
| Sesame              | 1         | 0.18%   |
| Qimonda             | 1         | 0.18%   |
| Patriot             | 1         | 0.18%   |
| Magnum Tech         | 1         | 0.18%   |
| Juhor               | 1         | 0.18%   |
| GOODRAM             | 1         | 0.18%   |
| ff                  | 1         | 0.18%   |
| CSX                 | 1         | 0.18%   |
| Apacer              | 1         | 0.18%   |
| 4ea5                | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 2.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 1.83%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.66%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 1.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.16%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.16%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.16%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.16%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.16%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 6         | 1%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1%      |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.83%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.83%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.83%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.67%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.67%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.67%   |
| Unknown                                                          | 4         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.5%    |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 276       | 58.23%  |
| DDR3    | 116       | 24.47%  |
| LPDDR4  | 26        | 5.49%   |
| LPDDR3  | 17        | 3.59%   |
| DDR5    | 15        | 3.16%   |
| LPDDR5  | 11        | 2.32%   |
| DDR2    | 8         | 1.69%   |
| SDRAM   | 4         | 0.84%   |
| Unknown | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 408       | 84.82%  |
| Row Of Chips | 60        | 12.47%  |
| Chip         | 7         | 1.46%   |
| Unknown      | 4         | 0.83%   |
| DIMM         | 2         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 246       | 47.95%  |
| 4096  | 135       | 26.32%  |
| 16384 | 85        | 16.57%  |
| 2048  | 28        | 5.46%   |
| 32768 | 15        | 2.92%   |
| 1024  | 4         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 141       | 28.09%  |
| 2667    | 104       | 20.72%  |
| 1600    | 98        | 19.52%  |
| 2400    | 32        | 6.37%   |
| 2133    | 22        | 4.38%   |
| 3266    | 17        | 3.39%   |
| 4800    | 16        | 3.19%   |
| 6400    | 11        | 2.19%   |
| 1867    | 10        | 1.99%   |
| 1334    | 10        | 1.99%   |
| 4267    | 6         | 1.2%    |
| 1333    | 4         | 0.8%    |
| 1067    | 4         | 0.8%    |
| 667     | 4         | 0.8%    |
| Unknown | 4         | 0.8%    |
| 4266    | 3         | 0.6%    |
| 3733    | 2         | 0.4%    |
| 2933    | 2         | 0.4%    |
| 2048    | 2         | 0.4%    |
| 1066    | 2         | 0.4%    |
| 800     | 2         | 0.4%    |
| 5600    | 1         | 0.2%    |
| 4199    | 1         | 0.2%    |
| 3000    | 1         | 0.2%    |
| 1776    | 1         | 0.2%    |
| 1639    | 1         | 0.2%    |
| 1200    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 33.33%  |
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 1         | 33.33%  |
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| HP DeskJet 2130 series        | 1         | 33.33%  |

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
| Chicony Electronics                    | 128       | 23.19%  |
| IMC Networks                           | 85        | 15.4%   |
| Bison Electronics                      | 41        | 7.43%   |
| Microdia                               | 39        | 7.07%   |
| Realtek Semiconductor                  | 30        | 5.43%   |
| Quanta                                 | 30        | 5.43%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 5.07%   |
| Sunplus Innovation Technology          | 26        | 4.71%   |
| Lite-On Technology                     | 19        | 3.44%   |
| Apple                                  | 19        | 3.44%   |
| Acer                                   | 17        | 3.08%   |
| Syntek                                 | 16        | 2.9%    |
| Luxvisions Innotech Limited            | 15        | 2.72%   |
| Logitech                               | 13        | 2.36%   |
| Sonix Technology                       | 8         | 1.45%   |
| Suyin                                  | 7         | 1.27%   |
| Silicon Motion                         | 4         | 0.72%   |
| Alcor Micro                            | 4         | 0.72%   |
| Primax Electronics                     | 3         | 0.54%   |
| Lenovo                                 | 3         | 0.54%   |
| Samsung Electronics                    | 2         | 0.36%   |
| Ricoh                                  | 2         | 0.36%   |
| MacroSilicon                           | 2         | 0.36%   |
| Intel                                  | 2         | 0.36%   |
| Tripath Technology                     | 1         | 0.18%   |
| ShineTech                              | 1         | 0.18%   |
| OPPO Electronics                       | 1         | 0.18%   |
| LG Electronics                         | 1         | 0.18%   |
| GRANDSTREAM GUV3100                    | 1         | 0.18%   |
| Google                                 | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |
| GEMBIRD                                | 1         | 0.18%   |
| ALi                                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 39        | 7.04%   |
| IMC Networks Integrated Camera                                 | 34        | 6.14%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 29        | 5.23%   |
| Microdia Integrated_Webcam_HD                                  | 17        | 3.07%   |
| Chicony HD WebCam                                              | 17        | 3.07%   |
| Bison Integrated Camera                                        | 15        | 2.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 11        | 1.99%   |
| Syntek Integrated Camera                                       | 10        | 1.81%   |
| Realtek Integrated_Webcam_HD                                   | 10        | 1.81%   |
| Bison HD Webcam                                                | 10        | 1.81%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 1.26%   |
| Sonix USB2.0 HD UVC WebCam                                     | 7         | 1.26%   |
| Lite-On Integrated Camera                                      | 7         | 1.26%   |
| IMC Networks HD Camera                                         | 7         | 1.26%   |
| Quanta USB2.0 HD UVC WebCam                                    | 6         | 1.08%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 1.08%   |
| Microdia Integrated Webcam                                     | 6         | 1.08%   |
| Chicony USB2.0 HD UVC WebCam                                   | 6         | 1.08%   |
| Acer Integrated Camera                                         | 6         | 1.08%   |
| Sunplus HD WebCam                                              | 5         | 0.9%    |
| Quanta HP HD Camera                                            | 5         | 0.9%    |
| Chicony VGA WebCam                                             | 5         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 5         | 0.9%    |
| Chicony HP TrueVision HD Camera                                | 5         | 0.9%    |
| Chicony HD User Facing                                         | 5         | 0.9%    |
| Apple FaceTime HD Camera (Built-in)                            | 5         | 0.9%    |
| Acer BisonCam,NB Pro                                           | 5         | 0.9%    |
| Syntek Lenovo EasyCamera                                       | 4         | 0.72%   |
| Sunplus Asus Webcam                                            | 4         | 0.72%   |
| Luxvisions Innotech Limited Integrated RGB Camera              | 4         | 0.72%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 4         | 0.72%   |
| Lite-On HP Webcam                                              | 4         | 0.72%   |
| Chicony HP Wide Vision HD Camera                               | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam   | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 4         | 0.72%   |
| Bison SunplusIT Integrated Camera                              | 4         | 0.72%   |
| Bison EasyCamera                                               | 4         | 0.72%   |
| Sunplus XiaoMi USB 2.0 Webcam                                  | 3         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                                   | 3         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 35        | 30.43%  |
| Validity Sensors                   | 31        | 26.96%  |
| Shenzhen Goodix Technology         | 21        | 18.26%  |
| Elan Microelectronics              | 14        | 12.17%  |
| LighTuning Technology              | 6         | 5.22%   |
| Upek                               | 3         | 2.61%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.61%   |
| AuthenTec                          | 2         | 1.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 12.17%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 10.43%  |
| Elan ELAN:Fingerprint                                                      | 8         | 6.96%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 6.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 6.09%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 5.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 5.22%   |
| Elan ELAN:ARM-M4                                                           | 6         | 5.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.48%   |
| Validity Sensors VFS491                                                    | 3         | 2.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.61%   |
| Synaptics UWP WBDI                                                         | 3         | 2.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.74%   |
| Synaptics WBDI                                                             | 2         | 1.74%   |
| Synaptics  WBDI                                                            | 2         | 1.74%   |
| Unknown                                                                    | 2         | 1.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.87%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.87%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.87%   |
| AuthenTec AES2810                                                          | 1         | 0.87%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.87%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 53.85%  |
| Alcor Micro | 11        | 28.21%  |
| Lenovo      | 3         | 7.69%   |
| Upek        | 2         | 5.13%   |
| O2 Micro    | 2         | 5.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 27.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 25%     |
| Broadcom 5880                                                                | 5         | 12.5%   |
| Broadcom 58200                                                               | 4         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 364       | 58.33%  |
| 1     | 212       | 33.97%  |
| 2     | 47        | 7.53%   |
| 3     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 115       | 38.72%  |
| Net/ethernet             | 39        | 13.13%  |
| Chipcard                 | 37        | 12.46%  |
| Multimedia controller    | 33        | 11.11%  |
| Graphics card            | 31        | 10.44%  |
| Net/wireless             | 18        | 6.06%   |
| Camera                   | 11        | 3.7%    |
| Bluetooth                | 9         | 3.03%   |
| Storage                  | 2         | 0.67%   |
| Modem                    | 1         | 0.34%   |
| Communication controller | 1         | 0.34%   |

