Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 3777

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-B120                     | Mini pc     | [29451ebbbb](https://linux-hardware.org/?probe=29451ebbbb) | May 08, 2024 |
| MSI           | B650M GAMING PLUS WIFI      | Desktop     | [be715853f7](https://linux-hardware.org/?probe=be715853f7) | May 08, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [6ac93f82e9](https://linux-hardware.org/?probe=6ac93f82e9) | May 08, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d419afc35f](https://linux-hardware.org/?probe=d419afc35f) | May 08, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [ebd9696c7b](https://linux-hardware.org/?probe=ebd9696c7b) | May 07, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [ce0082648a](https://linux-hardware.org/?probe=ce0082648a) | May 06, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [276faea129](https://linux-hardware.org/?probe=276faea129) | May 06, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [9f866b203a](https://linux-hardware.org/?probe=9f866b203a) | May 06, 2024 |
| MSI           | B650M GAMING PLUS WIFI      | Desktop     | [afbc83ced8](https://linux-hardware.org/?probe=afbc83ced8) | May 06, 2024 |
| Dell          | 0478VN A00                  | Desktop     | [305f343c95](https://linux-hardware.org/?probe=305f343c95) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d73bdd4b76](https://linux-hardware.org/?probe=d73bdd4b76) | May 06, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [fba3144c06](https://linux-hardware.org/?probe=fba3144c06) | May 06, 2024 |
| Unknown       | Unknown                     | Soc         | [938f2c805c](https://linux-hardware.org/?probe=938f2c805c) | May 05, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| Dell          | 03RT16 A00                  | Desktop     | [e88cedcfb7](https://linux-hardware.org/?probe=e88cedcfb7) | May 05, 2024 |
| Fujitsu       | LIFEBOOK T900               | Notebook    | [d396d19b06](https://linux-hardware.org/?probe=d396d19b06) | May 05, 2024 |
| PC Engines    | apu4                        | Desktop     | [02cb7f9180](https://linux-hardware.org/?probe=02cb7f9180) | May 05, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [b950303950](https://linux-hardware.org/?probe=b950303950) | May 04, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [f4e6daf83f](https://linux-hardware.org/?probe=f4e6daf83f) | May 04, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [73f06a8daf](https://linux-hardware.org/?probe=73f06a8daf) | May 03, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [c1af86a1e6](https://linux-hardware.org/?probe=c1af86a1e6) | May 01, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [151ab0d8e9](https://linux-hardware.org/?probe=151ab0d8e9) | May 01, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6fce33dd2b](https://linux-hardware.org/?probe=6fce33dd2b) | Apr 30, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5b49b60b38](https://linux-hardware.org/?probe=5b49b60b38) | Apr 30, 2024 |
| HP            | 89B5 A                      | Desktop     | [bae1a00b46](https://linux-hardware.org/?probe=bae1a00b46) | Apr 30, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [836078acb2](https://linux-hardware.org/?probe=836078acb2) | Apr 29, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [03f63c8caf](https://linux-hardware.org/?probe=03f63c8caf) | Apr 29, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [5c699c7770](https://linux-hardware.org/?probe=5c699c7770) | Apr 29, 2024 |
| Dell          | Latitude 5540               | Notebook    | [71894c9703](https://linux-hardware.org/?probe=71894c9703) | Apr 29, 2024 |
| ASUSTek       | UX32VD                      | Notebook    | [1377417777](https://linux-hardware.org/?probe=1377417777) | Apr 29, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e906970294](https://linux-hardware.org/?probe=e906970294) | Apr 28, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [32e7e340cf](https://linux-hardware.org/?probe=32e7e340cf) | Apr 28, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [40c7e6e4a3](https://linux-hardware.org/?probe=40c7e6e4a3) | Apr 28, 2024 |
| Acer          | Swift SF314-41              | Notebook    | [240aeeb256](https://linux-hardware.org/?probe=240aeeb256) | Apr 28, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [952112efbd](https://linux-hardware.org/?probe=952112efbd) | Apr 27, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d25ca314d4](https://linux-hardware.org/?probe=d25ca314d4) | Apr 26, 2024 |
| HP            | 82FF                        | Desktop     | [a0e9cfd330](https://linux-hardware.org/?probe=a0e9cfd330) | Apr 26, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [af3e9393cf](https://linux-hardware.org/?probe=af3e9393cf) | Apr 26, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1ffca9d284](https://linux-hardware.org/?probe=1ffca9d284) | Apr 25, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [56b059f9ef](https://linux-hardware.org/?probe=56b059f9ef) | Apr 25, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [4cfb726ac6](https://linux-hardware.org/?probe=4cfb726ac6) | Apr 23, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [72b47f3d18](https://linux-hardware.org/?probe=72b47f3d18) | Apr 23, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8c52f15119](https://linux-hardware.org/?probe=8c52f15119) | Apr 23, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [7c88cac728](https://linux-hardware.org/?probe=7c88cac728) | Apr 22, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [500ffeec7b](https://linux-hardware.org/?probe=500ffeec7b) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| Dell          | XPS 9320                    | Notebook    | [162d7ddcd3](https://linux-hardware.org/?probe=162d7ddcd3) | Apr 22, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7d3fad530f](https://linux-hardware.org/?probe=7d3fad530f) | Apr 22, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [3a08b0b94e](https://linux-hardware.org/?probe=3a08b0b94e) | Apr 21, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [62fb9d9789](https://linux-hardware.org/?probe=62fb9d9789) | Apr 21, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [5b29bd1ecf](https://linux-hardware.org/?probe=5b29bd1ecf) | Apr 21, 2024 |
| Acer          | Swift SF514-52T             | Notebook    | [d89f8a89a9](https://linux-hardware.org/?probe=d89f8a89a9) | Apr 20, 2024 |
| Lenovo        | ThinkPad X270 20HN0016MX    | Notebook    | [cd5fff4dcd](https://linux-hardware.org/?probe=cd5fff4dcd) | Apr 20, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f83f880363](https://linux-hardware.org/?probe=f83f880363) | Apr 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [3c9edd18cd](https://linux-hardware.org/?probe=3c9edd18cd) | Apr 19, 2024 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ebc9dd41f4](https://linux-hardware.org/?probe=ebc9dd41f4) | Apr 19, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [4dbbe8a263](https://linux-hardware.org/?probe=4dbbe8a263) | Apr 18, 2024 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [50987e4554](https://linux-hardware.org/?probe=50987e4554) | Apr 18, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [3d43cbd697](https://linux-hardware.org/?probe=3d43cbd697) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [5701b91e63](https://linux-hardware.org/?probe=5701b91e63) | Apr 16, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [13b11b28fc](https://linux-hardware.org/?probe=13b11b28fc) | Apr 16, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [f2ebb6880e](https://linux-hardware.org/?probe=f2ebb6880e) | Apr 15, 2024 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [39d3eeda79](https://linux-hardware.org/?probe=39d3eeda79) | Apr 12, 2024 |
| HP            | 1589                        | Desktop     | [fd455c0623](https://linux-hardware.org/?probe=fd455c0623) | Apr 12, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [6fd7de9ca4](https://linux-hardware.org/?probe=6fd7de9ca4) | Apr 11, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [21e80243e1](https://linux-hardware.org/?probe=21e80243e1) | Apr 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1450416558](https://linux-hardware.org/?probe=1450416558) | Apr 11, 2024 |
| HP            | 1589                        | Desktop     | [bf38ba715e](https://linux-hardware.org/?probe=bf38ba715e) | Apr 10, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [cd38e8b3bd](https://linux-hardware.org/?probe=cd38e8b3bd) | Apr 09, 2024 |
| HP            | ProBook 430 G3              | Notebook    | [2dff62b8e0](https://linux-hardware.org/?probe=2dff62b8e0) | Apr 09, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [543136ea4b](https://linux-hardware.org/?probe=543136ea4b) | Apr 08, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| ASUSTek       | G752VSK                     | Notebook    | [49116bb834](https://linux-hardware.org/?probe=49116bb834) | Apr 08, 2024 |
| Dell          | Latitude E7450              | Notebook    | [80c9756b52](https://linux-hardware.org/?probe=80c9756b52) | Apr 08, 2024 |
| Acer          | Predator PH315-54           | Notebook    | [23dae5c2e2](https://linux-hardware.org/?probe=23dae5c2e2) | Apr 07, 2024 |
| Dell          | Latitude 5401               | Notebook    | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [de7f154293](https://linux-hardware.org/?probe=de7f154293) | Apr 07, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aa5bca8370](https://linux-hardware.org/?probe=aa5bca8370) | Apr 07, 2024 |
| Lenovo        | ThinkPad T490s 20NX0056M... | Notebook    | [3945b47d9b](https://linux-hardware.org/?probe=3945b47d9b) | Apr 07, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [b743bdc5b7](https://linux-hardware.org/?probe=b743bdc5b7) | Apr 06, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [6450686a24](https://linux-hardware.org/?probe=6450686a24) | Apr 05, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [9a68d90ab7](https://linux-hardware.org/?probe=9a68d90ab7) | Apr 05, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e16e4757cf](https://linux-hardware.org/?probe=e16e4757cf) | Apr 04, 2024 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [eb1f637530](https://linux-hardware.org/?probe=eb1f637530) | Apr 04, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a3ff48e7a2](https://linux-hardware.org/?probe=a3ff48e7a2) | Apr 03, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91906af7e3](https://linux-hardware.org/?probe=91906af7e3) | Apr 03, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [3ddde931c2](https://linux-hardware.org/?probe=3ddde931c2) | Apr 03, 2024 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [aedb7d1450](https://linux-hardware.org/?probe=aedb7d1450) | Apr 03, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [86bf1e5346](https://linux-hardware.org/?probe=86bf1e5346) | Apr 03, 2024 |
| Lenovo        | ThinkPad X280 20KF001RMX    | Notebook    | [0caddb11a4](https://linux-hardware.org/?probe=0caddb11a4) | Apr 02, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a7a78cd117](https://linux-hardware.org/?probe=a7a78cd117) | Apr 02, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6b8fa8191d](https://linux-hardware.org/?probe=6b8fa8191d) | Apr 01, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [fb59e4c861](https://linux-hardware.org/?probe=fb59e4c861) | Apr 01, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [7ccfbb7054](https://linux-hardware.org/?probe=7ccfbb7054) | Mar 31, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [63f04a080c](https://linux-hardware.org/?probe=63f04a080c) | Mar 31, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [391458688f](https://linux-hardware.org/?probe=391458688f) | Mar 30, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d332c9a931](https://linux-hardware.org/?probe=d332c9a931) | Mar 30, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [cff197ffbf](https://linux-hardware.org/?probe=cff197ffbf) | Mar 30, 2024 |
| Lenovo        | ThinkPad R400 7440WWQ       | Notebook    | [7c62efd0a5](https://linux-hardware.org/?probe=7c62efd0a5) | Mar 29, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [decc958edf](https://linux-hardware.org/?probe=decc958edf) | Mar 28, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a5f288ff0e](https://linux-hardware.org/?probe=a5f288ff0e) | Mar 28, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [400955763a](https://linux-hardware.org/?probe=400955763a) | Mar 28, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b5091fa59f](https://linux-hardware.org/?probe=b5091fa59f) | Mar 27, 2024 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [e9afd87037](https://linux-hardware.org/?probe=e9afd87037) | Mar 25, 2024 |
| Congatec      | conga-B7XD C.3              | Mini pc     | [ff584585fe](https://linux-hardware.org/?probe=ff584585fe) | Mar 25, 2024 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [42ab03e71f](https://linux-hardware.org/?probe=42ab03e71f) | Mar 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [eb09797dad](https://linux-hardware.org/?probe=eb09797dad) | Mar 25, 2024 |
| MSI           | Bravo 15 C7UDX              | Notebook    | [6fb8db02b9](https://linux-hardware.org/?probe=6fb8db02b9) | Mar 25, 2024 |
| Lenovo        | VIWGQ                       | Notebook    | [881674c100](https://linux-hardware.org/?probe=881674c100) | Mar 24, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [c9a90af50f](https://linux-hardware.org/?probe=c9a90af50f) | Mar 24, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [04f792e4fe](https://linux-hardware.org/?probe=04f792e4fe) | Mar 23, 2024 |
| HP            | 15                          | Notebook    | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [4629f81fff](https://linux-hardware.org/?probe=4629f81fff) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [4d1bc02be0](https://linux-hardware.org/?probe=4d1bc02be0) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [0f6120fef2](https://linux-hardware.org/?probe=0f6120fef2) | Mar 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a20d8894bd](https://linux-hardware.org/?probe=a20d8894bd) | Mar 23, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [61d0ee2736](https://linux-hardware.org/?probe=61d0ee2736) | Mar 22, 2024 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [f2e727e087](https://linux-hardware.org/?probe=f2e727e087) | Mar 22, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [2ba706d8c9](https://linux-hardware.org/?probe=2ba706d8c9) | Mar 21, 2024 |
| Dell          | Precision M4600             | Notebook    | [ae97b86b04](https://linux-hardware.org/?probe=ae97b86b04) | Mar 20, 2024 |
| HP            | ZBook 15 G4                 | Notebook    | [1752ff36c3](https://linux-hardware.org/?probe=1752ff36c3) | Mar 20, 2024 |
| Dell          | Precision M4800             | Notebook    | [a6e69c7950](https://linux-hardware.org/?probe=a6e69c7950) | Mar 20, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [d6c0c2ac98](https://linux-hardware.org/?probe=d6c0c2ac98) | Mar 20, 2024 |
| eMachines     | eME642G                     | Notebook    | [8759a11aca](https://linux-hardware.org/?probe=8759a11aca) | Mar 20, 2024 |
| HP            | ProBook 440 G6              | Notebook    | [15167e6cda](https://linux-hardware.org/?probe=15167e6cda) | Mar 19, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [bd22d0e0ca](https://linux-hardware.org/?probe=bd22d0e0ca) | Mar 18, 2024 |
| Dell          | 0JP3NX A02                  | Desktop     | [5f4cb3cc05](https://linux-hardware.org/?probe=5f4cb3cc05) | Mar 17, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4ade0c63a8](https://linux-hardware.org/?probe=4ade0c63a8) | Mar 17, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | Notebook    | [ca665b8165](https://linux-hardware.org/?probe=ca665b8165) | Mar 16, 2024 |
| System76      | Gazelle                     | Notebook    | [e4a975b366](https://linux-hardware.org/?probe=e4a975b366) | Mar 16, 2024 |
| ZOTAC         | ZBOX-MA320                  | Mini pc     | [3bcf60e328](https://linux-hardware.org/?probe=3bcf60e328) | Mar 16, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [77972070ac](https://linux-hardware.org/?probe=77972070ac) | Mar 16, 2024 |
| eMachines     | eME642G                     | Notebook    | [7d7230a747](https://linux-hardware.org/?probe=7d7230a747) | Mar 16, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [7ded8b5e80](https://linux-hardware.org/?probe=7ded8b5e80) | Mar 15, 2024 |
| MSI           | Bravo 15 C7UDX              | Notebook    | [4441dff3bf](https://linux-hardware.org/?probe=4441dff3bf) | Mar 15, 2024 |
| Unknown       | Unknown                     | Notebook    | [a4e49121d0](https://linux-hardware.org/?probe=a4e49121d0) | Mar 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [2d1ccd0458](https://linux-hardware.org/?probe=2d1ccd0458) | Mar 15, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [7f865ffb79](https://linux-hardware.org/?probe=7f865ffb79) | Mar 15, 2024 |
| Samsung       | 940XFG                      | Notebook    | [b60ac199c7](https://linux-hardware.org/?probe=b60ac199c7) | Mar 15, 2024 |
| Samsung       | 940XFG                      | Notebook    | [2698d3e097](https://linux-hardware.org/?probe=2698d3e097) | Mar 15, 2024 |
| HP            | Pavilion 15                 | Notebook    | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [dd00485e27](https://linux-hardware.org/?probe=dd00485e27) | Mar 13, 2024 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [15f445697d](https://linux-hardware.org/?probe=15f445697d) | Mar 12, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [944358baac](https://linux-hardware.org/?probe=944358baac) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [0a31a36586](https://linux-hardware.org/?probe=0a31a36586) | Mar 10, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [c22c7f9510](https://linux-hardware.org/?probe=c22c7f9510) | Mar 10, 2024 |
| Toshiba       | Satellite L650              | Notebook    | [46a8d42eaa](https://linux-hardware.org/?probe=46a8d42eaa) | Mar 10, 2024 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6a52290a2c](https://linux-hardware.org/?probe=6a52290a2c) | Mar 10, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8d182b3c8c](https://linux-hardware.org/?probe=8d182b3c8c) | Mar 09, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [48f8aa3173](https://linux-hardware.org/?probe=48f8aa3173) | Mar 09, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [2a6047cea9](https://linux-hardware.org/?probe=2a6047cea9) | Mar 09, 2024 |
| Dell          | Latitude E6420              | Notebook    | [7ae5cc22b0](https://linux-hardware.org/?probe=7ae5cc22b0) | Mar 09, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [d8f65f3687](https://linux-hardware.org/?probe=d8f65f3687) | Mar 08, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [96e1e8d964](https://linux-hardware.org/?probe=96e1e8d964) | Mar 07, 2024 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [849473581a](https://linux-hardware.org/?probe=849473581a) | Mar 07, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [92ee6b2bfe](https://linux-hardware.org/?probe=92ee6b2bfe) | Mar 06, 2024 |
| MSI           | MS-B120                     | Mini pc     | [18c75fd8f9](https://linux-hardware.org/?probe=18c75fd8f9) | Mar 05, 2024 |
| Dell          | Latitude 7390               | Notebook    | [7eed1415ba](https://linux-hardware.org/?probe=7eed1415ba) | Mar 05, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e64fb708fb](https://linux-hardware.org/?probe=e64fb708fb) | Mar 05, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6fd9429f1c](https://linux-hardware.org/?probe=6fd9429f1c) | Mar 05, 2024 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [dee02a2e0f](https://linux-hardware.org/?probe=dee02a2e0f) | Mar 04, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [73c6b84a00](https://linux-hardware.org/?probe=73c6b84a00) | Mar 04, 2024 |
| HP            | 8298                        | Desktop     | [8415c5628a](https://linux-hardware.org/?probe=8415c5628a) | Mar 03, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [15406e60cd](https://linux-hardware.org/?probe=15406e60cd) | Mar 03, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [78090262bb](https://linux-hardware.org/?probe=78090262bb) | Mar 02, 2024 |
| Acer          | Predator PT516-51s          | Notebook    | [f3e05a8ef2](https://linux-hardware.org/?probe=f3e05a8ef2) | Feb 29, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [10c92b676a](https://linux-hardware.org/?probe=10c92b676a) | Feb 29, 2024 |
| MSI           | B250M BAZOOKA               | Desktop     | [50879e8f1a](https://linux-hardware.org/?probe=50879e8f1a) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [88e7a5c628](https://linux-hardware.org/?probe=88e7a5c628) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a387b3439f](https://linux-hardware.org/?probe=a387b3439f) | Feb 29, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [7a9345dd2c](https://linux-hardware.org/?probe=7a9345dd2c) | Feb 28, 2024 |
| LG Electro... | 15Z980-A.AAS7U1             | Notebook    | [845caa9a4d](https://linux-hardware.org/?probe=845caa9a4d) | Feb 28, 2024 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [ac4a5c44a6](https://linux-hardware.org/?probe=ac4a5c44a6) | Feb 28, 2024 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [636e341039](https://linux-hardware.org/?probe=636e341039) | Feb 28, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bd84816ed8](https://linux-hardware.org/?probe=bd84816ed8) | Feb 28, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [fb0362344a](https://linux-hardware.org/?probe=fb0362344a) | Feb 27, 2024 |
| Dell          | 0VHWTR A01                  | Desktop     | [3606f71943](https://linux-hardware.org/?probe=3606f71943) | Feb 27, 2024 |
| Dell          | Latitude E6430              | Notebook    | [1121d113bf](https://linux-hardware.org/?probe=1121d113bf) | Feb 26, 2024 |
| Dell          | Latitude E6430              | Notebook    | [860bbdc112](https://linux-hardware.org/?probe=860bbdc112) | Feb 26, 2024 |
| MSI           | B360 GAMING PLUS            | Desktop     | [40619e4cc4](https://linux-hardware.org/?probe=40619e4cc4) | Feb 26, 2024 |
| MSI           | B360 GAMING PLUS            | Desktop     | [e3fe48b63c](https://linux-hardware.org/?probe=e3fe48b63c) | Feb 26, 2024 |
| Lenovo        | ThinkPad X260 20F6009SMS    | Notebook    | [027f3ceeb3](https://linux-hardware.org/?probe=027f3ceeb3) | Feb 26, 2024 |
| Lenovo        | ThinkPad L412 44034KG       | Notebook    | [93c5498399](https://linux-hardware.org/?probe=93c5498399) | Feb 25, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [075f3b55c8](https://linux-hardware.org/?probe=075f3b55c8) | Feb 25, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [00993d2a74](https://linux-hardware.org/?probe=00993d2a74) | Feb 24, 2024 |
| Supermicro    | X10DRH-CT                   | Desktop     | [085564adc0](https://linux-hardware.org/?probe=085564adc0) | Feb 24, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [aa4ccf4433](https://linux-hardware.org/?probe=aa4ccf4433) | Feb 24, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [614cef61c1](https://linux-hardware.org/?probe=614cef61c1) | Feb 23, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [7ed2cffcae](https://linux-hardware.org/?probe=7ed2cffcae) | Feb 23, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8808c41478](https://linux-hardware.org/?probe=8808c41478) | Feb 22, 2024 |
| Dell          | Latitude E5420              | Notebook    | [910bc98f57](https://linux-hardware.org/?probe=910bc98f57) | Feb 21, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [a91e05d878](https://linux-hardware.org/?probe=a91e05d878) | Feb 21, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [66e5edfad7](https://linux-hardware.org/?probe=66e5edfad7) | Feb 21, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [fc06ed6b10](https://linux-hardware.org/?probe=fc06ed6b10) | Feb 20, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [aef715ec84](https://linux-hardware.org/?probe=aef715ec84) | Feb 20, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [8287dc23bb](https://linux-hardware.org/?probe=8287dc23bb) | Feb 20, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [760267fc7e](https://linux-hardware.org/?probe=760267fc7e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [78587a5ad4](https://linux-hardware.org/?probe=78587a5ad4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b5e81cd1b4](https://linux-hardware.org/?probe=b5e81cd1b4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [04c342c7e3](https://linux-hardware.org/?probe=04c342c7e3) | Feb 20, 2024 |
| Dell          | Latitude E7250              | Notebook    | [4dbb95d349](https://linux-hardware.org/?probe=4dbb95d349) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | Notebook    | [3eb06482d0](https://linux-hardware.org/?probe=3eb06482d0) | Feb 19, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [24e5b8861c](https://linux-hardware.org/?probe=24e5b8861c) | Feb 19, 2024 |
| Dell          | 0PGKWF A00                  | Desktop     | [83c1da9c3c](https://linux-hardware.org/?probe=83c1da9c3c) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | Notebook    | [c00066136f](https://linux-hardware.org/?probe=c00066136f) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c3f8499095](https://linux-hardware.org/?probe=c3f8499095) | Feb 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | Notebook    | [5b768d1518](https://linux-hardware.org/?probe=5b768d1518) | Feb 18, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [7749f91798](https://linux-hardware.org/?probe=7749f91798) | Feb 18, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [76525a9fe9](https://linux-hardware.org/?probe=76525a9fe9) | Feb 17, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [4bca7ee01c](https://linux-hardware.org/?probe=4bca7ee01c) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [ff0a6068a5](https://linux-hardware.org/?probe=ff0a6068a5) | Feb 17, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [feeeddef54](https://linux-hardware.org/?probe=feeeddef54) | Feb 16, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [5ad9c09f49](https://linux-hardware.org/?probe=5ad9c09f49) | Feb 16, 2024 |
| Acer          | Aspire S3                   | Notebook    | [015a6bdb09](https://linux-hardware.org/?probe=015a6bdb09) | Feb 16, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [c9895bde68](https://linux-hardware.org/?probe=c9895bde68) | Feb 14, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [7fe1594df6](https://linux-hardware.org/?probe=7fe1594df6) | Feb 14, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [a829d5fb44](https://linux-hardware.org/?probe=a829d5fb44) | Feb 14, 2024 |
| Lenovo        | ThinkPad X280 20KF001JMX    | Notebook    | [d370fcec49](https://linux-hardware.org/?probe=d370fcec49) | Feb 13, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c002f0bfd4](https://linux-hardware.org/?probe=c002f0bfd4) | Feb 13, 2024 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [3ef8bbe2bf](https://linux-hardware.org/?probe=3ef8bbe2bf) | Feb 13, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [310c126d3c](https://linux-hardware.org/?probe=310c126d3c) | Feb 12, 2024 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [d9e2b0abde](https://linux-hardware.org/?probe=d9e2b0abde) | Feb 12, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [908b0efb23](https://linux-hardware.org/?probe=908b0efb23) | Feb 11, 2024 |
| MSI           | MS-B120                     | Mini pc     | [ea5bf7fa17](https://linux-hardware.org/?probe=ea5bf7fa17) | Feb 11, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4b31eb71f6](https://linux-hardware.org/?probe=4b31eb71f6) | Feb 11, 2024 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [5b06c8344c](https://linux-hardware.org/?probe=5b06c8344c) | Feb 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [166c275408](https://linux-hardware.org/?probe=166c275408) | Feb 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [e85583dafa](https://linux-hardware.org/?probe=e85583dafa) | Feb 10, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | Notebook    | [8e506a8c7e](https://linux-hardware.org/?probe=8e506a8c7e) | Feb 09, 2024 |
| Microsoft     | Surface Laptop 2            | Tablet      | [214f8e3efa](https://linux-hardware.org/?probe=214f8e3efa) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [8234b16b6a](https://linux-hardware.org/?probe=8234b16b6a) | Feb 08, 2024 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abf81b6db9](https://linux-hardware.org/?probe=abf81b6db9) | Feb 08, 2024 |
| HP            | 829A                        | Mini pc     | [1f310e0509](https://linux-hardware.org/?probe=1f310e0509) | Feb 08, 2024 |
| HP            | 829A                        | Mini pc     | [bbfbacc65d](https://linux-hardware.org/?probe=bbfbacc65d) | Feb 08, 2024 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [8fe3e3113c](https://linux-hardware.org/?probe=8fe3e3113c) | Feb 08, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [1c4b5365af](https://linux-hardware.org/?probe=1c4b5365af) | Feb 07, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [63843cbf43](https://linux-hardware.org/?probe=63843cbf43) | Feb 07, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [d29438d6d7](https://linux-hardware.org/?probe=d29438d6d7) | Feb 06, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [4a1938d727](https://linux-hardware.org/?probe=4a1938d727) | Feb 06, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [588998612d](https://linux-hardware.org/?probe=588998612d) | Feb 06, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [477975e863](https://linux-hardware.org/?probe=477975e863) | Feb 06, 2024 |
| HP            | ZBook 15u G2                | Notebook    | [28b76e7488](https://linux-hardware.org/?probe=28b76e7488) | Feb 06, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [69a19c7a1d](https://linux-hardware.org/?probe=69a19c7a1d) | Feb 06, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [72e1aa0f99](https://linux-hardware.org/?probe=72e1aa0f99) | Feb 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [82733ca802](https://linux-hardware.org/?probe=82733ca802) | Feb 05, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [481c817555](https://linux-hardware.org/?probe=481c817555) | Feb 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [34e9a5b730](https://linux-hardware.org/?probe=34e9a5b730) | Feb 04, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [848a81b0ad](https://linux-hardware.org/?probe=848a81b0ad) | Feb 04, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [57f28e0095](https://linux-hardware.org/?probe=57f28e0095) | Feb 04, 2024 |
| ASRock        | Q1900B-ITX                  | Desktop     | [7b33d8adaf](https://linux-hardware.org/?probe=7b33d8adaf) | Feb 04, 2024 |
| ASUSTek       | UX430UAR                    | Notebook    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| ASRock        | Q1900B-ITX                  | Desktop     | [0e96f23985](https://linux-hardware.org/?probe=0e96f23985) | Feb 04, 2024 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [ecde56e2bb](https://linux-hardware.org/?probe=ecde56e2bb) | Feb 04, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | Notebook    | [c16e6118de](https://linux-hardware.org/?probe=c16e6118de) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [47c6ea83ea](https://linux-hardware.org/?probe=47c6ea83ea) | Feb 03, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [f57c7238f4](https://linux-hardware.org/?probe=f57c7238f4) | Feb 03, 2024 |
| HP            | ZBook 15 G4                 | Notebook    | [72ea56fdbe](https://linux-hardware.org/?probe=72ea56fdbe) | Feb 03, 2024 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [cf8a09526d](https://linux-hardware.org/?probe=cf8a09526d) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [aecdf1facc](https://linux-hardware.org/?probe=aecdf1facc) | Jan 30, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d1d5004095](https://linux-hardware.org/?probe=d1d5004095) | Jan 30, 2024 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [72e109e02a](https://linux-hardware.org/?probe=72e109e02a) | Jan 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [80a5fb05a8](https://linux-hardware.org/?probe=80a5fb05a8) | Jan 28, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f5f922292c](https://linux-hardware.org/?probe=f5f922292c) | Jan 28, 2024 |
| MSI           | MAG B560M MORTAR            | Desktop     | [709499c177](https://linux-hardware.org/?probe=709499c177) | Jan 28, 2024 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5bccdbf478](https://linux-hardware.org/?probe=5bccdbf478) | Jan 28, 2024 |
| Dell          | G3 3590                     | Notebook    | [7fb3fcb32c](https://linux-hardware.org/?probe=7fb3fcb32c) | Jan 28, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [5aa0059c3f](https://linux-hardware.org/?probe=5aa0059c3f) | Jan 28, 2024 |
| ABIT          | AB9/AB9RPO                  | Desktop     | [01c28bcaa5](https://linux-hardware.org/?probe=01c28bcaa5) | Jan 27, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b5fb647895](https://linux-hardware.org/?probe=b5fb647895) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [57f2a52748](https://linux-hardware.org/?probe=57f2a52748) | Jan 27, 2024 |
| Dell          | Inspiron 13-5378            | Notebook    | [a742fdf96d](https://linux-hardware.org/?probe=a742fdf96d) | Jan 27, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [6e63b66aba](https://linux-hardware.org/?probe=6e63b66aba) | Jan 26, 2024 |
| HP            | 1998                        | Desktop     | [b1431c9048](https://linux-hardware.org/?probe=b1431c9048) | Jan 26, 2024 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [fc6193b5bf](https://linux-hardware.org/?probe=fc6193b5bf) | Jan 26, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| HP            | 8054                        | Desktop     | [0f5623dad4](https://linux-hardware.org/?probe=0f5623dad4) | Jan 24, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [0bc85e1b60](https://linux-hardware.org/?probe=0bc85e1b60) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [362ad8ae7e](https://linux-hardware.org/?probe=362ad8ae7e) | Jan 24, 2024 |
| Lenovo        | ThinkPad X270 20HN0012MX    | Notebook    | [ac867529fa](https://linux-hardware.org/?probe=ac867529fa) | Jan 24, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [aa46ef22c8](https://linux-hardware.org/?probe=aa46ef22c8) | Jan 24, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [873da1ef71](https://linux-hardware.org/?probe=873da1ef71) | Jan 24, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [15666b6776](https://linux-hardware.org/?probe=15666b6776) | Jan 23, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [18a98466b2](https://linux-hardware.org/?probe=18a98466b2) | Jan 23, 2024 |
| MSI           | MAG B560M MORTAR            | Desktop     | [2637ed4a7c](https://linux-hardware.org/?probe=2637ed4a7c) | Jan 23, 2024 |
| Foxconn       | 2AAF                        | Desktop     | [aa481d37c8](https://linux-hardware.org/?probe=aa481d37c8) | Jan 22, 2024 |
| Intel         | D54250WYK H13922-303        | Desktop     | [0c54cab119](https://linux-hardware.org/?probe=0c54cab119) | Jan 22, 2024 |
| Acer          | Aspire E5-551G              | Notebook    | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| HP            | Pavilion g6                 | Notebook    | [bac27c78e2](https://linux-hardware.org/?probe=bac27c78e2) | Jan 19, 2024 |
| HP            | Pavilion g6                 | Notebook    | [30da02f122](https://linux-hardware.org/?probe=30da02f122) | Jan 19, 2024 |
| HP            | 1998                        | Desktop     | [b54abe0bef](https://linux-hardware.org/?probe=b54abe0bef) | Jan 18, 2024 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1d9bce4a06](https://linux-hardware.org/?probe=1d9bce4a06) | Jan 18, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [d39ea787aa](https://linux-hardware.org/?probe=d39ea787aa) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [187a8a84af](https://linux-hardware.org/?probe=187a8a84af) | Jan 18, 2024 |
| Dell          | Precision 5680              | Notebook    | [f52bddf877](https://linux-hardware.org/?probe=f52bddf877) | Jan 18, 2024 |
| Dell          | Precision 5680              | Notebook    | [2585a4f840](https://linux-hardware.org/?probe=2585a4f840) | Jan 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S0NV00    | Notebook    | [cda7600532](https://linux-hardware.org/?probe=cda7600532) | Jan 18, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [694f38f139](https://linux-hardware.org/?probe=694f38f139) | Jan 16, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6ddfddee65](https://linux-hardware.org/?probe=6ddfddee65) | Jan 15, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [f6ed1d1cc4](https://linux-hardware.org/?probe=f6ed1d1cc4) | Jan 15, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [dce09bb097](https://linux-hardware.org/?probe=dce09bb097) | Jan 14, 2024 |
| Unknown       | A70M                        | Notebook    | [b6a6c2e947](https://linux-hardware.org/?probe=b6a6c2e947) | Jan 14, 2024 |
| Dell          | 0PU052                      | Desktop     | [0614dd448b](https://linux-hardware.org/?probe=0614dd448b) | Jan 14, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [043258f53d](https://linux-hardware.org/?probe=043258f53d) | Jan 14, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [4602c5c446](https://linux-hardware.org/?probe=4602c5c446) | Jan 12, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | Notebook    | [d2db433ab2](https://linux-hardware.org/?probe=d2db433ab2) | Jan 12, 2024 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [629a19283f](https://linux-hardware.org/?probe=629a19283f) | Jan 11, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [0d7230b853](https://linux-hardware.org/?probe=0d7230b853) | Jan 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [ab13227de0](https://linux-hardware.org/?probe=ab13227de0) | Jan 10, 2024 |
| Acer          | Aspire 6530G                | Notebook    | [184836d752](https://linux-hardware.org/?probe=184836d752) | Jan 09, 2024 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [c1a58de14d](https://linux-hardware.org/?probe=c1a58de14d) | Jan 09, 2024 |
| HP            | ZBook 17 G4                 | Notebook    | [5dc1550956](https://linux-hardware.org/?probe=5dc1550956) | Jan 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [50ff3c4620](https://linux-hardware.org/?probe=50ff3c4620) | Jan 08, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [96d648fbd8](https://linux-hardware.org/?probe=96d648fbd8) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [8ea07db45a](https://linux-hardware.org/?probe=8ea07db45a) | Jan 07, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [c24ea3ef71](https://linux-hardware.org/?probe=c24ea3ef71) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [c0b1de838b](https://linux-hardware.org/?probe=c0b1de838b) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | Desktop     | [cfba81369c](https://linux-hardware.org/?probe=cfba81369c) | Jan 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [36f9070500](https://linux-hardware.org/?probe=36f9070500) | Jan 04, 2024 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [a37ab2b577](https://linux-hardware.org/?probe=a37ab2b577) | Jan 04, 2024 |
| Gigabyte      | MZAPLEP-00                  | Desktop     | [ba4a6b1f72](https://linux-hardware.org/?probe=ba4a6b1f72) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [50570b932a](https://linux-hardware.org/?probe=50570b932a) | Jan 03, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [913b232ab9](https://linux-hardware.org/?probe=913b232ab9) | Jan 03, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [64a74fbec3](https://linux-hardware.org/?probe=64a74fbec3) | Jan 03, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [6b5ef78cce](https://linux-hardware.org/?probe=6b5ef78cce) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [91413e5760](https://linux-hardware.org/?probe=91413e5760) | Jan 02, 2024 |
| Gigabyte      | MZAPLEP-00                  | Desktop     | [3c3b4ce0db](https://linux-hardware.org/?probe=3c3b4ce0db) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| ASUSTek       | P6T                         | Desktop     | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [d47bc3897f](https://linux-hardware.org/?probe=d47bc3897f) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | Notebook    | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bf4f14e416](https://linux-hardware.org/?probe=bf4f14e416) | Dec 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3f7e7324a4](https://linux-hardware.org/?probe=3f7e7324a4) | Dec 29, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [42460d0cd3](https://linux-hardware.org/?probe=42460d0cd3) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [68c1102e98](https://linux-hardware.org/?probe=68c1102e98) | Dec 25, 2023 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [f22547b26f](https://linux-hardware.org/?probe=f22547b26f) | Dec 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0972c678d9](https://linux-hardware.org/?probe=0972c678d9) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [34f80ef918](https://linux-hardware.org/?probe=34f80ef918) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [bf542378eb](https://linux-hardware.org/?probe=bf542378eb) | Dec 25, 2023 |
| PC Special... | N150CU                      | Notebook    | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Biostar       | A320MH                      | Desktop     | [0898691249](https://linux-hardware.org/?probe=0898691249) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | Notebook    | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| pine64,pin... | Pinebook Pro                | Soc         | [8e5ebecea9](https://linux-hardware.org/?probe=8e5ebecea9) | Dec 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6484f4217b](https://linux-hardware.org/?probe=6484f4217b) | Dec 24, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [a7194ce97c](https://linux-hardware.org/?probe=a7194ce97c) | Dec 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [18ef14b687](https://linux-hardware.org/?probe=18ef14b687) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [ff8ded7ff8](https://linux-hardware.org/?probe=ff8ded7ff8) | Dec 22, 2023 |
| HP            | 83E0                        | Desktop     | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8bce457975](https://linux-hardware.org/?probe=8bce457975) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Neousys Te... | NVS-10000 Rev. A2           | Server      | [cde616cde3](https://linux-hardware.org/?probe=cde616cde3) | Dec 21, 2023 |
| MSI           | B85M-G43                    | Desktop     | [f2b41e4ce3](https://linux-hardware.org/?probe=f2b41e4ce3) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [83ef4dd286](https://linux-hardware.org/?probe=83ef4dd286) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | Notebook    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4a6ea199e2](https://linux-hardware.org/?probe=4a6ea199e2) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [adced59500](https://linux-hardware.org/?probe=adced59500) | Dec 17, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [171e1a6bbb](https://linux-hardware.org/?probe=171e1a6bbb) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3324746751](https://linux-hardware.org/?probe=3324746751) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [78ef6792a1](https://linux-hardware.org/?probe=78ef6792a1) | Dec 16, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [059715d1bf](https://linux-hardware.org/?probe=059715d1bf) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| HP            | Unknown                     | Notebook    | [6a46b87d41](https://linux-hardware.org/?probe=6a46b87d41) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Lenovo        | 1031 SDK0J40697 WIN 3305... | Desktop     | [f04b854d78](https://linux-hardware.org/?probe=f04b854d78) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [6a4ff9d940](https://linux-hardware.org/?probe=6a4ff9d940) | Dec 11, 2023 |
| Acer          | Extensa 2509                | Notebook    | [ee00581b3a](https://linux-hardware.org/?probe=ee00581b3a) | Dec 11, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [41f57147de](https://linux-hardware.org/?probe=41f57147de) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| Dell          | XPS 9320                    | Notebook    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| MSI           | MS-B120                     | Mini pc     | [51a1cc9143](https://linux-hardware.org/?probe=51a1cc9143) | Dec 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [9c55ae59fe](https://linux-hardware.org/?probe=9c55ae59fe) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [8446d618a7](https://linux-hardware.org/?probe=8446d618a7) | Dec 06, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [3f2a30851e](https://linux-hardware.org/?probe=3f2a30851e) | Dec 05, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8c397afeca](https://linux-hardware.org/?probe=8c397afeca) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| HP            | 1998                        | Desktop     | [14cb2b69d2](https://linux-hardware.org/?probe=14cb2b69d2) | Dec 03, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [af649a6096](https://linux-hardware.org/?probe=af649a6096) | Dec 03, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [720eead0a5](https://linux-hardware.org/?probe=720eead0a5) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| HP            | 304Bh                       | Desktop     | [3cb20d232f](https://linux-hardware.org/?probe=3cb20d232f) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [d254031e43](https://linux-hardware.org/?probe=d254031e43) | Nov 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [535c1fe9e0](https://linux-hardware.org/?probe=535c1fe9e0) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3397e49e8a](https://linux-hardware.org/?probe=3397e49e8a) | Nov 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [38e71449be](https://linux-hardware.org/?probe=38e71449be) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [24e86fc568](https://linux-hardware.org/?probe=24e86fc568) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [288151e67d](https://linux-hardware.org/?probe=288151e67d) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [dc0fce7e4a](https://linux-hardware.org/?probe=dc0fce7e4a) | Nov 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94927ee986](https://linux-hardware.org/?probe=94927ee986) | Nov 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0c52ef42c9](https://linux-hardware.org/?probe=0c52ef42c9) | Nov 24, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8ff45d7c99](https://linux-hardware.org/?probe=8ff45d7c99) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8cb9c3b0a7](https://linux-hardware.org/?probe=8cb9c3b0a7) | Nov 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7aa3c32e86](https://linux-hardware.org/?probe=7aa3c32e86) | Nov 24, 2023 |
| HP            | Presario CQ61               | Notebook    | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [4a18f0945f](https://linux-hardware.org/?probe=4a18f0945f) | Nov 23, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [0ea9603f31](https://linux-hardware.org/?probe=0ea9603f31) | Nov 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [bc7df67b84](https://linux-hardware.org/?probe=bc7df67b84) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [8ea017cbfe](https://linux-hardware.org/?probe=8ea017cbfe) | Nov 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [b95977fce2](https://linux-hardware.org/?probe=b95977fce2) | Nov 20, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [72b1a867da](https://linux-hardware.org/?probe=72b1a867da) | Nov 20, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [03c5ac12be](https://linux-hardware.org/?probe=03c5ac12be) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [88e978f447](https://linux-hardware.org/?probe=88e978f447) | Nov 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4230260e34](https://linux-hardware.org/?probe=4230260e34) | Nov 18, 2023 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [e9e9d46316](https://linux-hardware.org/?probe=e9e9d46316) | Nov 17, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [63c8984ac3](https://linux-hardware.org/?probe=63c8984ac3) | Nov 16, 2023 |
| Lenovo        | 1064 SDK0T76530 WIN 3556... | Desktop     | [0c6d21ae8f](https://linux-hardware.org/?probe=0c6d21ae8f) | Nov 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e42bab7bfa](https://linux-hardware.org/?probe=e42bab7bfa) | Nov 15, 2023 |
| Lenovo        | 1064 SDK0T76530 WIN 3556... | Desktop     | [58692dde45](https://linux-hardware.org/?probe=58692dde45) | Nov 15, 2023 |
| System76      | Adder WS                    | Notebook    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [5ef7be7906](https://linux-hardware.org/?probe=5ef7be7906) | Nov 12, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bee917829a](https://linux-hardware.org/?probe=bee917829a) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| ASUSTek       | TS10                        | Desktop     | [c35ca1dadb](https://linux-hardware.org/?probe=c35ca1dadb) | Nov 11, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [cb1e3547f7](https://linux-hardware.org/?probe=cb1e3547f7) | Nov 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d9873e127d](https://linux-hardware.org/?probe=d9873e127d) | Nov 10, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [224a0992ae](https://linux-hardware.org/?probe=224a0992ae) | Nov 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [9a3d616dad](https://linux-hardware.org/?probe=9a3d616dad) | Nov 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [de38771bec](https://linux-hardware.org/?probe=de38771bec) | Nov 08, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c035e0367f](https://linux-hardware.org/?probe=c035e0367f) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5191c2b469](https://linux-hardware.org/?probe=5191c2b469) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| HP            | 8431                        | All in one  | [00262f7c56](https://linux-hardware.org/?probe=00262f7c56) | Nov 06, 2023 |
| HP            | 8431                        | All in one  | [1d1dbab0f0](https://linux-hardware.org/?probe=1d1dbab0f0) | Nov 06, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| HP            | Unknown                     | Notebook    | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | Notebook    | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [62a859fb72](https://linux-hardware.org/?probe=62a859fb72) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| HP            | 2B01                        | Desktop     | [a345333330](https://linux-hardware.org/?probe=a345333330) | Oct 31, 2023 |
| HP            | 2B01                        | Desktop     | [b3a75824f5](https://linux-hardware.org/?probe=b3a75824f5) | Oct 31, 2023 |
| Dell          | Precision 5570              | Notebook    | [fb83199260](https://linux-hardware.org/?probe=fb83199260) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| Dell          | Latitude 7370               | Notebook    | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| HP            | Unknown                     | Notebook    | [3aadbc5c33](https://linux-hardware.org/?probe=3aadbc5c33) | Oct 30, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b61ad8059a](https://linux-hardware.org/?probe=b61ad8059a) | Oct 30, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [261e5240fe](https://linux-hardware.org/?probe=261e5240fe) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| HP            | G62                         | Notebook    | [bd714e9671](https://linux-hardware.org/?probe=bd714e9671) | Oct 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| HP            | 8433 11                     | Desktop     | [f4b0e9190f](https://linux-hardware.org/?probe=f4b0e9190f) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c1078c11fb](https://linux-hardware.org/?probe=c1078c11fb) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b05283573c](https://linux-hardware.org/?probe=b05283573c) | Oct 26, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [101037a3e1](https://linux-hardware.org/?probe=101037a3e1) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [c505d21099](https://linux-hardware.org/?probe=c505d21099) | Oct 25, 2023 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [ad7033d138](https://linux-hardware.org/?probe=ad7033d138) | Oct 24, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | Desktop     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Dell          | 06FW8P A01                  | Desktop     | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| HP            | ML150 G3                    | Desktop     | [eb5a4bfed8](https://linux-hardware.org/?probe=eb5a4bfed8) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [cceff4e3b1](https://linux-hardware.org/?probe=cceff4e3b1) | Oct 20, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0feec3b3ab](https://linux-hardware.org/?probe=0feec3b3ab) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [0944131c12](https://linux-hardware.org/?probe=0944131c12) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d5febd2212](https://linux-hardware.org/?probe=d5febd2212) | Oct 17, 2023 |
| HP            | 8433 11                     | Desktop     | [24fdb6f03a](https://linux-hardware.org/?probe=24fdb6f03a) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [1568dbcf9b](https://linux-hardware.org/?probe=1568dbcf9b) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [c6c5b8dc5c](https://linux-hardware.org/?probe=c6c5b8dc5c) | Oct 15, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [02141519f7](https://linux-hardware.org/?probe=02141519f7) | Oct 15, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [10b572c94a](https://linux-hardware.org/?probe=10b572c94a) | Oct 14, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a646cc1cc1](https://linux-hardware.org/?probe=a646cc1cc1) | Oct 10, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [d731fb0868](https://linux-hardware.org/?probe=d731fb0868) | Oct 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [f010d626da](https://linux-hardware.org/?probe=f010d626da) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a07ec0ee55](https://linux-hardware.org/?probe=a07ec0ee55) | Oct 08, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c360c7552a](https://linux-hardware.org/?probe=c360c7552a) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7b6ad19193](https://linux-hardware.org/?probe=7b6ad19193) | Oct 07, 2023 |
| Dell          | 0PU052                      | Desktop     | [c32b862792](https://linux-hardware.org/?probe=c32b862792) | Oct 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [dcc7e8da51](https://linux-hardware.org/?probe=dcc7e8da51) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| HP            | ZBook 14u G4                | Notebook    | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [071eee1057](https://linux-hardware.org/?probe=071eee1057) | Oct 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [8076ad493d](https://linux-hardware.org/?probe=8076ad493d) | Oct 03, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [6a2fa93249](https://linux-hardware.org/?probe=6a2fa93249) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f80a538f2a](https://linux-hardware.org/?probe=f80a538f2a) | Oct 02, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [76f023476d](https://linux-hardware.org/?probe=76f023476d) | Oct 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | Notebook    | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | Notebook    | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [de5a55aa7b](https://linux-hardware.org/?probe=de5a55aa7b) | Sep 23, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9e6874d35c](https://linux-hardware.org/?probe=9e6874d35c) | Sep 20, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [51c58cd13a](https://linux-hardware.org/?probe=51c58cd13a) | Sep 19, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [64618297ff](https://linux-hardware.org/?probe=64618297ff) | Sep 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [293bc3eab9](https://linux-hardware.org/?probe=293bc3eab9) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [118c76cef1](https://linux-hardware.org/?probe=118c76cef1) | Sep 12, 2023 |
| Samsung       | R530/R730/P590              | Notebook    | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [03b8175690](https://linux-hardware.org/?probe=03b8175690) | Sep 10, 2023 |
| ASUSTek       | TS10                        | Desktop     | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [03ce2f9b74](https://linux-hardware.org/?probe=03ce2f9b74) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [0c2dda2476](https://linux-hardware.org/?probe=0c2dda2476) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [72516e7752](https://linux-hardware.org/?probe=72516e7752) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [26448cf759](https://linux-hardware.org/?probe=26448cf759) | Sep 07, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [5dca7c7315](https://linux-hardware.org/?probe=5dca7c7315) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Dell          | Latitude 7440               | Notebook    | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | Notebook    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [19bf85f553](https://linux-hardware.org/?probe=19bf85f553) | Sep 01, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | Notebook    | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [3740c90267](https://linux-hardware.org/?probe=3740c90267) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6f5a767b7e](https://linux-hardware.org/?probe=6f5a767b7e) | Aug 29, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [577d9d5dc1](https://linux-hardware.org/?probe=577d9d5dc1) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6736188e61](https://linux-hardware.org/?probe=6736188e61) | Aug 26, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [6a55471f69](https://linux-hardware.org/?probe=6a55471f69) | Aug 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| HP            | 845A                        | Desktop     | [4a8699daad](https://linux-hardware.org/?probe=4a8699daad) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| HP            | 212B                        | Desktop     | [ee20bd40d8](https://linux-hardware.org/?probe=ee20bd40d8) | Aug 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| ASUSTek       | M3N                         | Notebook    | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [3135a88431](https://linux-hardware.org/?probe=3135a88431) | Aug 17, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| HP            | Unknown                     | Notebook    | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | Notebook    | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a06a335d70](https://linux-hardware.org/?probe=a06a335d70) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Acer          | Spin SP111-31               | Convertible | [003fa350a2](https://linux-hardware.org/?probe=003fa350a2) | Jul 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | Notebook    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | Notebook    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b1a5c8b10d](https://linux-hardware.org/?probe=b1a5c8b10d) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [805d981913](https://linux-hardware.org/?probe=805d981913) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e707b1595f](https://linux-hardware.org/?probe=e707b1595f) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [21950296b4](https://linux-hardware.org/?probe=21950296b4) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [6758dfb731](https://linux-hardware.org/?probe=6758dfb731) | Jul 15, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [c3b936e87a](https://linux-hardware.org/?probe=c3b936e87a) | Jul 12, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [2992a0aea9](https://linux-hardware.org/?probe=2992a0aea9) | Jul 10, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [57cc83ff44](https://linux-hardware.org/?probe=57cc83ff44) | Jul 10, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [5f28888f0d](https://linux-hardware.org/?probe=5f28888f0d) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e2c9e04a7c](https://linux-hardware.org/?probe=e2c9e04a7c) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | Notebook    | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | Notebook    | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [165584477b](https://linux-hardware.org/?probe=165584477b) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0c5693c658](https://linux-hardware.org/?probe=0c5693c658) | Jun 18, 2023 |
| OEM           | ALDER LAKE JHS64S           | Desktop     | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [ff01549321](https://linux-hardware.org/?probe=ff01549321) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d58405f7c1](https://linux-hardware.org/?probe=d58405f7c1) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [86b377710d](https://linux-hardware.org/?probe=86b377710d) | Jun 10, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [48eb50cc43](https://linux-hardware.org/?probe=48eb50cc43) | Jun 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| congatec      | conga-TA7 A.4               | Mini pc     | [686699557a](https://linux-hardware.org/?probe=686699557a) | May 24, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f2477906c7](https://linux-hardware.org/?probe=f2477906c7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| MSI           | Z87-G43                     | Desktop     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| HP            | Compaq 6730s                | Notebook    | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | Notebook    | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [3ac194e77a](https://linux-hardware.org/?probe=3ac194e77a) | May 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [1c84c61678](https://linux-hardware.org/?probe=1c84c61678) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0b217b3ccc](https://linux-hardware.org/?probe=0b217b3ccc) | May 04, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [973f9c6467](https://linux-hardware.org/?probe=973f9c6467) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [92f7217eb7](https://linux-hardware.org/?probe=92f7217eb7) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| Dell          | Latitude 5430               | Notebook    | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [cb9c80dbba](https://linux-hardware.org/?probe=cb9c80dbba) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3f12350d47](https://linux-hardware.org/?probe=3f12350d47) | Apr 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | Notebook    | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| Unknown       | Unknown                     | Phone       | [3d8d71ba51](https://linux-hardware.org/?probe=3d8d71ba51) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 277       | 10.17%  |
| Ubuntu 22.04                 | 202       | 7.42%   |
| Ubuntu 18.04                 | 132       | 4.85%   |
| Arch Rolling                 | 79        | 2.9%    |
| Pop!_OS 22.04                | 73        | 2.68%   |
| Debian 12                    | 59        | 2.17%   |
| Debian 11                    | 57        | 2.09%   |
| Manjaro                      | 54        | 1.98%   |
| Pop!_OS 21.04                | 48        | 1.76%   |
| ArcoLinux Rolling            | 47        | 1.73%   |
| Zorin 16                     | 46        | 1.69%   |
| OpenMandriva 4.3             | 41        | 1.51%   |
| Arch                         | 40        | 1.47%   |
| OpenMandriva 4.2             | 39        | 1.43%   |
| KDE neon 20.04               | 38        | 1.4%    |
| openSUSE Tumbleweed-XXXXXXXX | 33        | 1.21%   |
| Linux Mint 21.1              | 33        | 1.21%   |
| Ubuntu 23.10                 | 32        | 1.18%   |
| Linux Mint 20.3              | 32        | 1.18%   |
| Pop!_OS 20.04                | 31        | 1.14%   |
| Fedora 39                    | 31        | 1.14%   |
| Fedora 38                    | 30        | 1.1%    |
| Ubuntu 21.10                 | 29        | 1.07%   |
| Ubuntu 21.04                 | 29        | 1.07%   |
| Pop!_OS 20.10                | 29        | 1.07%   |
| Fedora 37                    | 29        | 1.07%   |
| Fedora 35                    | 29        | 1.07%   |
| EndeavourOS Rolling          | 28        | 1.03%   |
| Ubuntu 19.04                 | 27        | 0.99%   |
| Fedora 34                    | 25        | 0.92%   |
| Ubuntu 19.10                 | 24        | 0.88%   |
| Linux Mint 21.2              | 23        | 0.84%   |
| Fedora 36                    | 23        | 0.84%   |
| Fedora 32                    | 23        | 0.84%   |
| Zorin 15                     | 22        | 0.81%   |
| Ubuntu 23.04                 | 22        | 0.81%   |
| Xubuntu 20.04                | 20        | 0.73%   |
| Linux Mint 20.2              | 20        | 0.73%   |
| Linux Mint 20                | 20        | 0.73%   |
| Ubuntu 20.10                 | 19        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 792       | 30.6%   |
| Fedora        | 215       | 8.31%   |
| Linux Mint    | 195       | 7.53%   |
| Pop!_OS       | 186       | 7.19%   |
| Debian        | 150       | 5.8%    |
| OpenMandriva  | 130       | 5.02%   |
| Arch          | 118       | 4.56%   |
| Manjaro       | 109       | 4.21%   |
| Zorin         | 77        | 2.98%   |
| KDE neon      | 56        | 2.16%   |
| ArcoLinux     | 52        | 2.01%   |
| Xubuntu       | 49        | 1.89%   |
| openSUSE      | 40        | 1.55%   |
| Kubuntu       | 39        | 1.51%   |
| Gentoo        | 38        | 1.47%   |
| EndeavourOS   | 32        | 1.24%   |
| Kali          | 27        | 1.04%   |
| Elementary    | 22        | 0.85%   |
| ROSA          | 21        | 0.81%   |
| Ubuntu MATE   | 16        | 0.62%   |
| Nobara        | 15        | 0.58%   |
| CentOS        | 14        | 0.54%   |
| SteamOS       | 12        | 0.46%   |
| Garuda Linux  | 12        | 0.46%   |
| Clear Linux   | 12        | 0.46%   |
| LMDE          | 11        | 0.43%   |
| MX            | 10        | 0.39%   |
| Lubuntu       | 10        | 0.39%   |
| Endless       | 10        | 0.39%   |
| Ubuntu Unity  | 8         | 0.31%   |
| Parrot        | 8         | 0.31%   |
| NixOS         | 8         | 0.31%   |
| BunsenLabs    | 8         | 0.31%   |
| Ubuntu Budgie | 6         | 0.23%   |
| Peppermint    | 6         | 0.23%   |
| Solus         | 5         | 0.19%   |
| Raspbian      | 5         | 0.19%   |
| Alpine        | 5         | 0.19%   |
| Ubuntu Studio | 4         | 0.15%   |
| Slackware     | 4         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 39        | 1.3%    |
| 5.10.14-desktop-1omv4002 | 39        | 1.3%    |
| 5.4.0-42-generic         | 33        | 1.1%    |
| 5.15.0-56-generic        | 28        | 0.93%   |
| 5.4.0-58-generic         | 21        | 0.7%    |
| 5.4.0-48-generic         | 20        | 0.67%   |
| 6.5.0-14-generic         | 19        | 0.63%   |
| 5.15.0-52-generic        | 19        | 0.63%   |
| 5.11.0-7620-generic      | 19        | 0.63%   |
| 5.3.0-40-generic         | 17        | 0.57%   |
| 5.13.0-7614-generic      | 17        | 0.57%   |
| 5.4.0-52-generic         | 16        | 0.53%   |
| 5.15.0-46-generic        | 15        | 0.5%    |
| 5.13.0-30-generic        | 15        | 0.5%    |
| 5.4.0-40-generic         | 14        | 0.47%   |
| 5.15.0-91-generic        | 14        | 0.47%   |
| 5.15.0-58-generic        | 14        | 0.47%   |
| 5.13.0-39-generic        | 14        | 0.47%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.43%   |
| 6.2.6-76060206-generic   | 13        | 0.43%   |
| 5.4.0-7634-generic       | 13        | 0.43%   |
| 5.15.0-60-generic        | 13        | 0.43%   |
| 5.15.0-48-generic        | 13        | 0.43%   |
| 6.5.0-26-generic         | 12        | 0.4%    |
| 5.4.0-33-generic         | 12        | 0.4%    |
| 5.15.0-78-generic        | 12        | 0.4%    |
| 5.15.0-53-generic        | 12        | 0.4%    |
| 5.11.0-37-generic        | 12        | 0.4%    |
| 6.6.2-desktop-1omv2390   | 11        | 0.37%   |
| 6.4.11-desktop-1omv2390  | 11        | 0.37%   |
| 6.1.0-7-amd64            | 11        | 0.37%   |
| 6.1.0-18-amd64           | 11        | 0.37%   |
| 5.8.0-48-generic         | 11        | 0.37%   |
| 5.4.0-70-generic         | 11        | 0.37%   |
| 5.4.0-54-generic         | 11        | 0.37%   |
| 5.19.0-35-generic        | 11        | 0.37%   |
| 5.15.0-76-generic        | 11        | 0.37%   |
| 5.15.0-50-generic        | 11        | 0.37%   |
| 5.11.0-7614-generic      | 11        | 0.37%   |
| 5.10.0-8-amd64           | 11        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 341       | 11.93%  |
| 5.15.0  | 264       | 9.24%   |
| 5.11.0  | 131       | 4.58%   |
| 5.13.0  | 121       | 4.23%   |
| 5.8.0   | 97        | 3.39%   |
| 6.5.0   | 95        | 3.32%   |
| 4.15.0  | 83        | 2.9%    |
| 6.1.0   | 81        | 2.83%   |
| 5.10.0  | 78        | 2.73%   |
| 5.3.0   | 76        | 2.66%   |
| 5.19.0  | 75        | 2.62%   |
| 6.2.0   | 71        | 2.48%   |
| 5.0.0   | 59        | 2.06%   |
| 4.18.0  | 47        | 1.64%   |
| 5.16.7  | 40        | 1.4%    |
| 5.10.14 | 40        | 1.4%    |
| 6.2.6   | 27        | 0.94%   |
| 6.5.6   | 16        | 0.56%   |
| 5.14.0  | 15        | 0.52%   |
| 6.4.11  | 14        | 0.49%   |
| 6.6.2   | 13        | 0.45%   |
| 5.17.5  | 13        | 0.45%   |
| 6.6.10  | 12        | 0.42%   |
| 6.1.1   | 12        | 0.42%   |
| 6.6.7   | 11        | 0.38%   |
| 4.19.0  | 11        | 0.38%   |
| 6.8.7   | 10        | 0.35%   |
| 6.2.9   | 10        | 0.35%   |
| 6.0.12  | 10        | 0.35%   |
| 5.18.0  | 10        | 0.35%   |
| 5.12.4  | 10        | 0.35%   |
| 5.17.1  | 9         | 0.31%   |
| 6.7.6   | 8         | 0.28%   |
| 6.7.0   | 8         | 0.28%   |
| 6.4.0   | 8         | 0.28%   |
| 5.16.0  | 8         | 0.28%   |
| 6.6.6   | 7         | 0.24%   |
| 6.5.7   | 7         | 0.24%   |
| 6.3.1   | 7         | 0.24%   |
| 6.1.12  | 7         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 371       | 13.22%  |
| 5.15    | 330       | 11.76%  |
| 5.10    | 166       | 5.92%   |
| 5.11    | 160       | 5.7%    |
| 6.1     | 149       | 5.31%   |
| 6.5     | 143       | 5.1%    |
| 5.13    | 141       | 5.02%   |
| 5.8     | 134       | 4.78%   |
| 6.2     | 129       | 4.6%    |
| 5.19    | 93        | 3.31%   |
| 5.3     | 88        | 3.14%   |
| 4.15    | 83        | 2.96%   |
| 5.16    | 81        | 2.89%   |
| 6.6     | 73        | 2.6%    |
| 5.0     | 62        | 2.21%   |
| 6.4     | 55        | 1.96%   |
| 4.18    | 54        | 1.92%   |
| 5.17    | 48        | 1.71%   |
| 6.0     | 46        | 1.64%   |
| 6.3     | 42        | 1.5%    |
| 6.7     | 38        | 1.35%   |
| 5.18    | 37        | 1.32%   |
| 5.14    | 37        | 1.32%   |
| 5.12    | 36        | 1.28%   |
| 6.8     | 35        | 1.25%   |
| 5.9     | 33        | 1.18%   |
| 5.6     | 28        | 1%      |
| 5.7     | 24        | 0.86%   |
| 4.19    | 23        | 0.82%   |
| 4.9     | 16        | 0.57%   |
| 5.5     | 15        | 0.53%   |
| 5.1     | 7         | 0.25%   |
| 5.2     | 6         | 0.21%   |
| 4.4     | 6         | 0.21%   |
| 4.14    | 4         | 0.14%   |
| 4.1     | 3         | 0.11%   |
| 4.20    | 2         | 0.07%   |
| 4.12    | 2         | 0.07%   |
| 3.10    | 2         | 0.07%   |
| 5       | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2420      | 97.86%  |
| i686    | 26        | 1.05%   |
| aarch64 | 19        | 0.77%   |
| armv7l  | 6         | 0.24%   |
| i586    | 1         | 0.04%   |
| armv8l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1215      | 46.53%  |
| KDE5            | 386       | 14.78%  |
| Unknown         | 303       | 11.6%   |
| XFCE            | 205       | 7.85%   |
| X-Cinnamon      | 166       | 6.36%   |
| KDE             | 75        | 2.87%   |
| MATE            | 53        | 2.03%   |
| i3              | 24        | 0.92%   |
| LXQt            | 22        | 0.84%   |
| Pantheon        | 21        | 0.8%    |
| Cinnamon        | 20        | 0.77%   |
| LXDE            | 14        | 0.54%   |
| KDE6            | 12        | 0.46%   |
| KDE4            | 11        | 0.42%   |
| Budgie          | 11        | 0.42%   |
| GNOME Flashback | 10        | 0.38%   |
| Unity           | 9         | 0.34%   |
| Deepin          | 7         | 0.27%   |
| sway            | 6         | 0.23%   |
| awesome         | 6         | 0.23%   |
| GNOME Classic   | 5         | 0.19%   |
| BunsenLabs      | 5         | 0.19%   |
| Openbox         | 4         | 0.15%   |
| Hyprland        | 4         | 0.15%   |
| DWM             | 3         | 0.11%   |
| qtile           | 2         | 0.08%   |
| LeftWM          | 2         | 0.08%   |
| xmonad          | 1         | 0.04%   |
| Trinity         | 1         | 0.04%   |
| spectrwm        | 1         | 0.04%   |
| none+i3         | 1         | 0.04%   |
| none+awesome    | 1         | 0.04%   |
| niri            | 1         | 0.04%   |
| GNOME-Flashback | 1         | 0.04%   |
| Enlightenment   | 1         | 0.04%   |
| DDE             | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1753      | 68.58%  |
| Wayland     | 561       | 21.95%  |
| Unknown     | 150       | 5.87%   |
| Tty         | 91        | 3.56%   |
| Unspecified | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1242      | 47.86%  |
| GDM3    | 364       | 14.03%  |
| SDDM    | 351       | 13.53%  |
| LightDM | 272       | 10.48%  |
| GDM     | 269       | 10.37%  |
| TDM     | 63        | 2.43%   |
| KDM     | 11        | 0.42%   |
| LXDM    | 8         | 0.31%   |
| XDM     | 7         | 0.27%   |
| Ly      | 6         | 0.23%   |
| LY-DM   | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1255      | 49.31%  |
| sv_SE       | 690       | 27.11%  |
| Unknown     | 237       | 9.31%   |
| en_GB       | 165       | 6.48%   |
| C           | 68        | 2.67%   |
| de_DE       | 20        | 0.79%   |
| ru_RU       | 18        | 0.71%   |
| pl_PL       | 10        | 0.39%   |
| en_SE       | 8         | 0.31%   |
| en_DK       | 7         | 0.28%   |
| en_CA       | 6         | 0.24%   |
| uk_UA       | 4         | 0.16%   |
| nb_NO       | 4         | 0.16%   |
| fr_FR       | 4         | 0.16%   |
| en_IE       | 4         | 0.16%   |
| C.UTF8      | 4         | 0.16%   |
| POSIX       | 3         | 0.12%   |
| it_IT       | 3         | 0.12%   |
| fi_FI       | 3         | 0.12%   |
| en_AG       | 3         | 0.12%   |
| el_GR       | 3         | 0.12%   |
| bg_BG       | 3         | 0.12%   |
| zh_CN       | 2         | 0.08%   |
| sv_FI       | 2         | 0.08%   |
| lt_LT       | 2         | 0.08%   |
| en_US.UTf-8 | 2         | 0.08%   |
| UTF-8       | 1         | 0.04%   |
| tr_TR       | 1         | 0.04%   |
| sv_SE.UTF8  | 1         | 0.04%   |
| sma_SE      | 1         | 0.04%   |
| nn_NO       | 1         | 0.04%   |
| hu_HU       | 1         | 0.04%   |
| hr_HR       | 1         | 0.04%   |
| gl_ES       | 1         | 0.04%   |
| es_VE       | 1         | 0.04%   |
| es_ES       | 1         | 0.04%   |
| en_IN       | 1         | 0.04%   |
| en_GB.UTF8  | 1         | 0.04%   |
| en_GB.utf-8 | 1         | 0.04%   |
| en_AU       | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1331      | 52.24%  |
| BIOS | 1217      | 47.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1800      | 70.2%   |
| Btrfs    | 330       | 12.87%  |
| Overlay  | 160       | 6.24%   |
| Tmpfs    | 134       | 5.23%   |
| Unknown  | 60        | 2.34%   |
| Xfs      | 42        | 1.64%   |
| Zfs      | 21        | 0.82%   |
| Ext2     | 7         | 0.27%   |
| F2fs     | 6         | 0.23%   |
| Ext3     | 2         | 0.08%   |
| XXXXXXX  | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1227      | 47.97%  |
| GPT     | 1118      | 43.71%  |
| MBR     | 213       | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2211      | 87.5%   |
| Yes       | 316       | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1914      | 76.04%  |
| Yes       | 603       | 23.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 538       | 21.75%  |
| Lenovo                  | 383       | 15.49%  |
| Hewlett-Packard         | 370       | 14.96%  |
| Dell                    | 260       | 10.51%  |
| MSI                     | 173       | 7%      |
| Gigabyte Technology     | 149       | 6.03%   |
| Acer                    | 123       | 4.97%   |
| Apple                   | 88        | 3.56%   |
| ASRock                  | 54        | 2.18%   |
| Intel                   | 30        | 1.21%   |
| Fujitsu                 | 24        | 0.97%   |
| Toshiba                 | 18        | 0.73%   |
| Raspberry Pi Foundation | 18        | 0.73%   |
| Unknown                 | 16        | 0.65%   |
| Sony                    | 15        | 0.61%   |
| Samsung Electronics     | 13        | 0.53%   |
| Packard Bell            | 13        | 0.53%   |
| Microsoft               | 12        | 0.49%   |
| Valve                   | 10        | 0.4%    |
| Supermicro              | 10        | 0.4%    |
| Notebook                | 10        | 0.4%    |
| Google                  | 9         | 0.36%   |
| Fujitsu Siemens         | 9         | 0.36%   |
| Foxconn                 | 7         | 0.28%   |
| Pegatron                | 6         | 0.24%   |
| HUAWEI                  | 5         | 0.2%    |
| AAEON                   | 5         | 0.2%    |
| Maxtang                 | 4         | 0.16%   |
| Alienware               | 4         | 0.16%   |
| TUXEDO                  | 3         | 0.12%   |
| System76                | 3         | 0.12%   |
| Star Labs               | 3         | 0.12%   |
| LG Electronics          | 3         | 0.12%   |
| eMachines               | 3         | 0.12%   |
| Congatec                | 3         | 0.12%   |
| Clevo                   | 3         | 0.12%   |
| AMI                     | 3         | 0.12%   |
| Timi                    | 2         | 0.08%   |
| Shuttle                 | 2         | 0.08%   |
| Schenker                | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 24        | 0.97%   |
| Unknown                          | 21        | 0.85%   |
| ASUS ROG STRIX B450-F GAMING     | 13        | 0.53%   |
| ASUS ROG STRIX B550-F GAMING     | 11        | 0.44%   |
| Valve Jupiter                    | 10        | 0.4%    |
| ASUS ROG STRIX X570-F GAMING     | 10        | 0.4%    |
| MSI MS-7C37                      | 9         | 0.36%   |
| ASUS PRIME X470-PRO              | 9         | 0.36%   |
| Dell XPS 13 9370                 | 8         | 0.32%   |
| MSI MS-7C02                      | 7         | 0.28%   |
| HP EliteBook 840 G3              | 7         | 0.28%   |
| Dell XPS 13 9310                 | 7         | 0.28%   |
| ASUS Z170 PRO GAMING             | 7         | 0.28%   |
| Apple MacBookAir7,2              | 7         | 0.28%   |
| HP Pavilion 15                   | 6         | 0.24%   |
| HP EliteBook Folio 9470m         | 6         | 0.24%   |
| Dell Precision 5540              | 6         | 0.24%   |
| Apple MacBookPro9,2              | 6         | 0.24%   |
| Acer Aspire V3-571               | 6         | 0.24%   |
| MSI MS-7C52                      | 5         | 0.2%    |
| MSI MS-7817                      | 5         | 0.2%    |
| Lenovo Yoga C740-14IML 81TC      | 5         | 0.2%    |
| Lenovo MIIX 310-10ICR 80SG       | 5         | 0.2%    |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.2%    |
| HP ProBook 640 G1                | 5         | 0.2%    |
| HP Pavilion dv7                  | 5         | 0.2%    |
| HP EliteBook 840 G2              | 5         | 0.2%    |
| HP EliteBook 820 G3              | 5         | 0.2%    |
| Gigabyte B550 AORUS ELITE V2     | 5         | 0.2%    |
| Gigabyte B450M DS3H              | 5         | 0.2%    |
| Dell XPS 15 9570                 | 5         | 0.2%    |
| Dell OptiPlex 7010               | 5         | 0.2%    |
| ASUS TUF Gaming X570-PLUS        | 5         | 0.2%    |
| ASUS ROG STRIX Z390-F GAMING     | 5         | 0.2%    |
| ASUS ROG STRIX B550-I GAMING     | 5         | 0.2%    |
| ASUS ROG STRIX B350-F GAMING     | 5         | 0.2%    |
| ASUS PRIME X370-PRO              | 5         | 0.2%    |
| ASUS M5A97 R2.0                  | 5         | 0.2%    |
| Apple MacBookPro8,1              | 5         | 0.2%    |
| Apple MacBookPro12,1             | 5         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 208       | 8.41%   |
| ASUS ROG              | 128       | 5.18%   |
| HP EliteBook          | 104       | 4.21%   |
| Dell Latitude         | 78        | 3.15%   |
| Acer Aspire           | 73        | 2.95%   |
| ASUS PRIME            | 65        | 2.63%   |
| Dell Precision        | 57        | 2.3%    |
| Dell XPS              | 53        | 2.14%   |
| Lenovo IdeaPad        | 52        | 2.1%    |
| HP Pavilion           | 49        | 1.98%   |
| HP ProBook            | 46        | 1.86%   |
| Dell OptiPlex         | 38        | 1.54%   |
| Lenovo Yoga           | 30        | 1.21%   |
| ASUS TUF              | 30        | 1.21%   |
| HP Compaq             | 29        | 1.17%   |
| HP ZBook              | 27        | 1.09%   |
| ASUS All              | 24        | 0.97%   |
| ASUS VivoBook         | 23        | 0.93%   |
| Unknown               | 21        | 0.85%   |
| HP Laptop             | 19        | 0.77%   |
| HP ENVY               | 19        | 0.77%   |
| RPi Raspberry         | 18        | 0.73%   |
| HP EliteDesk          | 17        | 0.69%   |
| ASUS Zenbook          | 17        | 0.69%   |
| Acer Swift            | 17        | 0.69%   |
| Toshiba Satellite     | 15        | 0.61%   |
| Lenovo Legion         | 15        | 0.61%   |
| Dell Inspiron         | 15        | 0.61%   |
| Gigabyte X570         | 14        | 0.57%   |
| Lenovo ThinkCentre    | 13        | 0.53%   |
| Microsoft Surface     | 12        | 0.49%   |
| Dell Vostro           | 11        | 0.44%   |
| Acer Predator         | 11        | 0.44%   |
| Valve Jupiter         | 10        | 0.4%    |
| Fujitsu LIFEBOOK      | 10        | 0.4%    |
| ASUS P8Z77-V          | 10        | 0.4%    |
| ASUS ASUS             | 10        | 0.4%    |
| Acer Nitro            | 10        | 0.4%    |
| Packard Bell EasyNote | 9         | 0.36%   |
| MSI MS-7C37           | 9         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 245       | 9.91%   |
| 2019    | 239       | 9.66%   |
| 2020    | 218       | 8.82%   |
| 2021    | 196       | 7.93%   |
| 2013    | 172       | 6.96%   |
| 2012    | 171       | 6.91%   |
| 2017    | 170       | 6.87%   |
| 2011    | 163       | 6.59%   |
| 2014    | 143       | 5.78%   |
| 2015    | 137       | 5.54%   |
| 2016    | 132       | 5.34%   |
| 2022    | 110       | 4.45%   |
| 2010    | 107       | 4.33%   |
| 2008    | 69        | 2.79%   |
| 2009    | 59        | 2.39%   |
| 2007    | 49        | 1.98%   |
| 2023    | 48        | 1.94%   |
| Unknown | 19        | 0.77%   |
| 2006    | 12        | 0.49%   |
| 2005    | 8         | 0.32%   |
| 2024    | 3         | 0.12%   |
| 2004    | 2         | 0.08%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1291      | 52.2%   |
| Desktop        | 966       | 39.06%  |
| Convertible    | 72        | 2.91%   |
| Mini pc        | 54        | 2.18%   |
| All in one     | 25        | 1.01%   |
| Tablet         | 24        | 0.97%   |
| System on chip | 22        | 0.89%   |
| Server         | 16        | 0.65%   |
| Phone          | 3         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2268      | 91.16%  |
| Enabled  | 220       | 8.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2458      | 99.39%  |
| Yes  | 15        | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 584       | 23.26%  |
| 4.01-8.0        | 537       | 21.39%  |
| 8.01-16.0       | 428       | 17.05%  |
| 32.01-64.0      | 404       | 16.09%  |
| 3.01-4.0        | 305       | 12.15%  |
| 64.01-256.0     | 93        | 3.7%    |
| 1.01-2.0        | 64        | 2.55%   |
| 24.01-32.0      | 57        | 2.27%   |
| 2.01-3.0        | 17        | 0.68%   |
| 0.51-1.0        | 17        | 0.68%   |
| More than 256.0 | 4         | 0.16%   |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 816       | 29.76%  |
| 2.01-3.0    | 648       | 23.63%  |
| 4.01-8.0    | 546       | 19.91%  |
| 3.01-4.0    | 396       | 14.44%  |
| 8.01-16.0   | 151       | 5.51%   |
| 0.51-1.0    | 115       | 4.19%   |
| 16.01-24.0  | 33        | 1.2%    |
| 0.01-0.5    | 26        | 0.95%   |
| 24.01-32.0  | 6         | 0.22%   |
| 32.01-64.0  | 3         | 0.11%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1529      | 59.82%  |
| 2      | 543       | 21.24%  |
| 3      | 218       | 8.53%   |
| 4      | 122       | 4.77%   |
| 5      | 50        | 1.96%   |
| 6      | 35        | 1.37%   |
| 0      | 25        | 0.98%   |
| 7      | 22        | 0.86%   |
| 8      | 6         | 0.23%   |
| 10     | 2         | 0.08%   |
| 26     | 1         | 0.04%   |
| 12     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |
| 9      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1742      | 70.04%  |
| Yes       | 745       | 29.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2111      | 85.12%  |
| No        | 369       | 14.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1835      | 73.55%  |
| No        | 660       | 26.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1591      | 63.34%  |
| No        | 921       | 36.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 2473      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 508       | 18.95%  |
| Gothenburg              | 264       | 9.85%   |
| Malmo                   | 131       | 4.89%   |
| Uppsala                 | 77        | 2.87%   |
| Lund                    | 55        | 2.05%   |
| Västerås              | 46        | 1.72%   |
| Linköping              | 45        | 1.68%   |
| Umeå                   | 35        | 1.31%   |
| Bromma                  | 35        | 1.31%   |
| Sollentuna              | 33        | 1.23%   |
| Sundsvall               | 31        | 1.16%   |
| Solna                   | 30        | 1.12%   |
| Örebro                 | 29        | 1.08%   |
| Norrköping             | 28        | 1.04%   |
| Vaxjo                   | 27        | 1.01%   |
| Saltsjoe-Boo            | 25        | 0.93%   |
| Karlstad                | 23        | 0.86%   |
| Sundbyberg              | 22        | 0.82%   |
| Helsingborg             | 22        | 0.82%   |
| Karlskrona              | 20        | 0.75%   |
| Huddinge                | 20        | 0.75%   |
| Gävle                  | 20        | 0.75%   |
| Vaestra Froelunda       | 19        | 0.71%   |
| Haegersten              | 19        | 0.71%   |
| Bandhagen               | 19        | 0.71%   |
| Taby                    | 17        | 0.63%   |
| Södertälje            | 17        | 0.63%   |
| Halmstad                | 17        | 0.63%   |
| Nyköping               | 15        | 0.56%   |
| Norsborg                | 14        | 0.52%   |
| Kista                   | 14        | 0.52%   |
| Staffanstorp            | 13        | 0.48%   |
| Spanga                  | 13        | 0.48%   |
| Moelndal                | 13        | 0.48%   |
| Jönköping             | 13        | 0.48%   |
| Borlänge               | 13        | 0.48%   |
| Skövde                 | 12        | 0.45%   |
| Katrineholm             | 12        | 0.45%   |
| Järfälla Municipality | 12        | 0.45%   |
| Arboga                  | 12        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 833       | 1356   | 22.58%  |
| WDC                         | 463       | 759    | 12.55%  |
| Seagate                     | 421       | 682    | 11.41%  |
| Kingston                    | 288       | 420    | 7.81%   |
| Intel                       | 199       | 255    | 5.39%   |
| Sandisk                     | 192       | 251    | 5.2%    |
| Toshiba                     | 175       | 237    | 4.74%   |
| Unknown                     | 126       | 163    | 3.42%   |
| SK hynix                    | 115       | 131    | 3.12%   |
| Hitachi                     | 99        | 140    | 2.68%   |
| Crucial                     | 92        | 131    | 2.49%   |
| Micron Technology           | 86        | 101    | 2.33%   |
| HGST                        | 57        | 68     | 1.55%   |
| Apple                       | 51        | 62     | 1.38%   |
| Kingston Technology Company | 42        | 56     | 1.14%   |
| Corsair                     | 29        | 40     | 0.79%   |
| KIOXIA                      | 27        | 29     | 0.73%   |
| A-DATA Technology           | 25        | 26     | 0.68%   |
| Phison                      | 23        | 28     | 0.62%   |
| OCZ                         | 23        | 29     | 0.62%   |
| LITEON                      | 21        | 29     | 0.57%   |
| Phison Electronics          | 20        | 30     | 0.54%   |
| Transcend                   | 16        | 19     | 0.43%   |
| Micron/Crucial Technology   | 15        | 20     | 0.41%   |
| Intenso                     | 14        | 20     | 0.38%   |
| LITEONIT                    | 13        | 22     | 0.35%   |
| Fujitsu                     | 13        | 19     | 0.35%   |
| China                       | 12        | 13     | 0.33%   |
| Silicon Motion              | 11        | 30     | 0.3%    |
| Unknown                     | 11        | 11     | 0.3%    |
| PNY                         | 10        | 14     | 0.27%   |
| Maxtor                      | 7         | 7      | 0.19%   |
| JMicron Technology          | 7         | 8      | 0.19%   |
| Hewlett-Packard             | 7         | 16     | 0.19%   |
| Verbatim                    | 6         | 12     | 0.16%   |
| SPCC                        | 6         | 20     | 0.16%   |
| LaCie                       | 6         | 7      | 0.16%   |
| ASMT                        | 6         | 6      | 0.16%   |
| Lenovo                      | 5         | 5      | 0.14%   |
| Patriot                     | 4         | 6      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 65        | 1.54%   |
| Samsung SSD 850 EVO 250GB                          | 59        | 1.4%    |
| Samsung SSD 850 EVO 500GB                          | 49        | 1.16%   |
| Kingston SA400S37120G 120GB SSD                    | 41        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                   | 35        | 0.83%   |
| Kingston SA400S37480G 480GB SSD                    | 35        | 0.83%   |
| Kingston SA400S37240G 240GB SSD                    | 35        | 0.83%   |
| Samsung SSD 860 EVO 500GB                          | 29        | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 27        | 0.64%   |
| Samsung SSD 860 EVO 250GB                          | 26        | 0.62%   |
| Samsung SSD 840 EVO 250GB                          | 26        | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB                     | 25        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                       | 25        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 23        | 0.55%   |
| Samsung SSD 860 EVO 1TB                            | 21        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                     | 20        | 0.47%   |
| Samsung NVMe SSD Drive 512GB                       | 20        | 0.47%   |
| Unknown MMC Card  32GB                             | 19        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                     | 19        | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                         | 18        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                     | 17        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 16        | 0.38%   |
| Samsung NVMe SSD Drive 1TB                         | 16        | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB                        | 15        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                    | 15        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                     | 15        | 0.36%   |
| SanDisk NVMe SSD Drive 512GB                       | 15        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                       | 15        | 0.36%   |
| Samsung SSD 840 EVO 500GB                          | 15        | 0.36%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 15        | 0.36%   |
| HGST HTS721010A9E630 1TB                           | 15        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 14        | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 14        | 0.33%   |
| Seagate ST2000DM006-2DM164 2TB                     | 14        | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 14        | 0.33%   |
| Kingston Company A2000 NVMe SSD 500GB              | 14        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 13        | 0.31%   |
| Seagate ST4000VN008-2DR166 4TB                     | 13        | 0.31%   |
| Seagate Expansion 2TB                              | 13        | 0.31%   |
| Samsung SSD 870 QVO 1TB                            | 13        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 414       | 665    | 35.66%  |
| WDC                 | 359       | 609    | 30.92%  |
| Hitachi             | 99        | 140    | 8.53%   |
| Toshiba             | 92        | 132    | 7.92%   |
| Samsung Electronics | 65        | 103    | 5.6%    |
| HGST                | 57        | 68     | 4.91%   |
| Unknown             | 16        | 19     | 1.38%   |
| Fujitsu             | 13        | 19     | 1.12%   |
| Apple               | 13        | 13     | 1.12%   |
| Maxtor              | 6         | 6      | 0.52%   |
| JMicron Technology  | 5         | 6      | 0.43%   |
| Hewlett-Packard     | 5         | 14     | 0.43%   |
| Intenso             | 3         | 3      | 0.26%   |
| ASMedia             | 3         | 3      | 0.26%   |
| ASMT                | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| SABRENT             | 1         | 1      | 0.09%   |
| MARVELL             | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| IB                  | 1         | 2      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 447       | 694    | 32.7%   |
| Kingston            | 219       | 317    | 16.02%  |
| Intel               | 114       | 145    | 8.34%   |
| SanDisk             | 88        | 110    | 6.44%   |
| Crucial             | 87        | 123    | 6.36%   |
| WDC                 | 68        | 91     | 4.97%   |
| Micron Technology   | 48        | 60     | 3.51%   |
| Apple               | 35        | 41     | 2.56%   |
| SK hynix            | 30        | 34     | 2.19%   |
| Toshiba             | 23        | 32     | 1.68%   |
| OCZ                 | 23        | 29     | 1.68%   |
| LITEON              | 20        | 28     | 1.46%   |
| Corsair             | 17        | 21     | 1.24%   |
| A-DATA Technology   | 16        | 17     | 1.17%   |
| Transcend           | 14        | 17     | 1.02%   |
| LITEONIT            | 13        | 22     | 0.95%   |
| China               | 12        | 13     | 0.88%   |
| Intenso             | 8         | 9      | 0.59%   |
| PNY                 | 7         | 11     | 0.51%   |
| Verbatim            | 6         | 12     | 0.44%   |
| SPCC                | 6         | 20     | 0.44%   |
| Patriot             | 4         | 6      | 0.29%   |
| ASMT                | 4         | 4      | 0.29%   |
| Netac               | 3         | 3      | 0.22%   |
| M4-CT128            | 3         | 3      | 0.22%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.22%   |
| Emtec               | 3         | 3      | 0.22%   |
| Team                | 2         | 2      | 0.15%   |
| Seagate             | 2         | 4      | 0.15%   |
| OCZ-VERTEX3         | 2         | 2      | 0.15%   |
| KingSpec            | 2         | 2      | 0.15%   |
| KingFast            | 2         | 2      | 0.15%   |
| INTEL SS            | 2         | 3      | 0.15%   |
| GOODRAM             | 2         | 3      | 0.15%   |
| Apacer              | 2         | 2      | 0.15%   |
| XSTAR               | 1         | 2      | 0.07%   |
| WDC WDS2            | 1         | 1      | 0.07%   |
| WDC WDS1            | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| tigo                | 1         | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1161      | 1923   | 35.2%   |
| NVMe    | 1029      | 1473   | 31.2%   |
| HDD     | 950       | 1812   | 28.81%  |
| MMC     | 120       | 143    | 3.64%   |
| Unknown | 38        | 53     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1673      | 3556   | 56.39%  |
| NVMe | 1027      | 1467   | 34.61%  |
| SAS  | 147       | 238    | 4.95%   |
| MMC  | 120       | 143    | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1373      | 2288   | 59.93%  |
| 0.51-1.0   | 487       | 747    | 21.26%  |
| 1.01-2.0   | 207       | 330    | 9.04%   |
| 3.01-4.0   | 98        | 162    | 4.28%   |
| 2.01-3.0   | 66        | 104    | 2.88%   |
| 4.01-10.0  | 47        | 85     | 2.05%   |
| 10.01-20.0 | 13        | 19     | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 705       | 26.71%  |
| 251-500        | 563       | 21.33%  |
| 501-1000       | 365       | 13.83%  |
| 1001-2000      | 217       | 8.22%   |
| 1-20           | 207       | 7.84%   |
| More than 3000 | 204       | 7.73%   |
| 51-100         | 128       | 4.85%   |
| Unknown        | 102       | 3.87%   |
| 2001-3000      | 80        | 3.03%   |
| 21-50          | 68        | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 964       | 35.57%  |
| 21-50          | 426       | 15.72%  |
| 101-250        | 366       | 13.51%  |
| 51-100         | 293       | 10.81%  |
| 251-500        | 183       | 6.75%   |
| 501-1000       | 159       | 5.87%   |
| Unknown        | 102       | 3.76%   |
| 1001-2000      | 87        | 3.21%   |
| More than 3000 | 74        | 2.73%   |
| 2001-3000      | 53        | 1.96%   |
| 0              | 3         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 2.4%    |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 1.44%   |
| Samsung Electronics SSD 870 EVO 1TB            | 3         | 3      | 1.44%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 3         | 4      | 1.44%   |
| Intel SSDSC2BW240A4 240GB                      | 3         | 4      | 1.44%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 2         | 2      | 0.96%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 0.96%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 2         | 2      | 0.96%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 2         | 3      | 0.96%   |
| WDC WD10EALX-009BA0 1TB                        | 2         | 5      | 0.96%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 0.96%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 0.96%   |
| Seagate ST3500418AS 500GB                      | 2         | 3      | 0.96%   |
| Seagate ST2000DX001-1CM164 2TB                 | 2         | 2      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB                 | 2         | 4      | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 0.96%   |
| Samsung Electronics SP2504C 250GB              | 2         | 2      | 0.96%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 0.96%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 0.96%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 3      | 0.96%   |
| Intel SSDSC2CW120A3 120GB                      | 2         | 2      | 0.96%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 0.96%   |
| Hitachi HTS725025A9A364 250GB                  | 2         | 2      | 0.96%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 0.96%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 0.96%   |
| HGST HTS725032A7E630 320GB                     | 2         | 2      | 0.96%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 0.96%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.48%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.48%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.48%   |
| WDC WD6400AAKS-00A7B2 640GB                    | 1         | 1      | 0.48%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.48%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.48%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.48%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.48%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.48%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 58     | 21.89%  |
| WDC                 | 34        | 59     | 16.92%  |
| Samsung Electronics | 22        | 22     | 10.95%  |
| Hitachi             | 20        | 24     | 9.95%   |
| Intel               | 17        | 20     | 8.46%   |
| HGST                | 9         | 10     | 4.48%   |
| Toshiba             | 7         | 9      | 3.48%   |
| Kingston            | 7         | 8      | 3.48%   |
| Micron Technology   | 6         | 7      | 2.99%   |
| Crucial             | 6         | 8      | 2.99%   |
| Corsair             | 4         | 4      | 1.99%   |
| OCZ                 | 3         | 5      | 1.49%   |
| SK hynix            | 2         | 2      | 1%      |
| SanDisk             | 2         | 2      | 1%      |
| LITEONIT            | 2         | 2      | 1%      |
| Fujitsu             | 2         | 2      | 1%      |
| China               | 2         | 2      | 1%      |
| Apple               | 2         | 2      | 1%      |
| Union Memory        | 1         | 1      | 0.5%    |
| Transcend           | 1         | 1      | 0.5%    |
| Team                | 1         | 1      | 0.5%    |
| Silicon Motion      | 1         | 1      | 0.5%    |
| PNY                 | 1         | 2      | 0.5%    |
| KingFast            | 1         | 1      | 0.5%    |
| Hewlett-Packard     | 1         | 1      | 0.5%    |
| ADATA Technology    | 1         | 1      | 0.5%    |
| A-DATA Technology   | 1         | 1      | 0.5%    |
| Unknown             | 1         | 1      | 0.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 58     | 34.11%  |
| WDC                 | 32        | 57     | 24.81%  |
| Hitachi             | 20        | 24     | 15.5%   |
| Samsung Electronics | 12        | 12     | 9.3%    |
| HGST                | 9         | 10     | 6.98%   |
| Toshiba             | 6         | 8      | 4.65%   |
| Fujitsu             | 2         | 2      | 1.55%   |
| Apple               | 2         | 2      | 1.55%   |
| Hewlett-Packard     | 1         | 1      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 124       | 175    | 64.25%  |
| SSD  | 59        | 72     | 30.57%  |
| NVMe | 10        | 10     | 5.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| Transcend TS120GSSD220S 120GB                                 | 1         | 1      | 25%     |
| Samsung Electronics SSD 980 1TB                               | 1         | 1      | 25%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1TB | 1         | 1      | 25%     |
| Hitachi HTS727575A9E364 752GB                                 | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| Transcend           | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1533      | 3305   | 56.38%  |
| Works    | 997       | 1838   | 36.67%  |
| Malfunc  | 185       | 257    | 6.8%    |
| Failed   | 4         | 4      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1491      | 45.6%   |
| AMD                              | 535       | 16.36%  |
| Samsung Electronics              | 442       | 13.52%  |
| SanDisk                          | 145       | 4.43%   |
| Kingston Technology Company      | 114       | 3.49%   |
| SK hynix                         | 83        | 2.54%   |
| Toshiba America Info Systems     | 65        | 1.99%   |
| Phison Electronics               | 56        | 1.71%   |
| ASMedia Technology               | 54        | 1.65%   |
| Marvell Technology Group         | 41        | 1.25%   |
| JMicron Technology               | 41        | 1.25%   |
| Micron Technology                | 39        | 1.19%   |
| Nvidia                           | 25        | 0.76%   |
| KIOXIA                           | 25        | 0.76%   |
| Micron/Crucial Technology        | 19        | 0.58%   |
| Silicon Motion                   | 14        | 0.43%   |
| ADATA Technology                 | 13        | 0.4%    |
| Silicon Image                    | 7         | 0.21%   |
| VIA Technologies                 | 5         | 0.15%   |
| Union Memory (Shenzhen)          | 5         | 0.15%   |
| Realtek Semiconductor            | 5         | 0.15%   |
| LSI Logic / Symbios Logic        | 5         | 0.15%   |
| Lite-On Technology               | 5         | 0.15%   |
| Lenovo                           | 5         | 0.15%   |
| Broadcom / LSI                   | 5         | 0.15%   |
| Apple                            | 5         | 0.15%   |
| Solid State Storage Technology   | 4         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Seagate Technology               | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Transcend                        | 2         | 0.06%   |
| O2 Micro                         | 2         | 0.06%   |
| Integrated Technology Express    | 1         | 0.03%   |
| Innodisk                         | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Adaptec                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 333       | 8.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 226       | 6.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 117       | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 106       | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 89        | 2.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 88        | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 73        | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 66        | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 64        | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 63        | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 60        | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 57        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 57        | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                         | 53        | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 52        | 1.4%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 52        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 50        | 1.35%   |
| Intel SATA Controller [RAID Mode]                                              | 46        | 1.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 45        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 45        | 1.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.19%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 42        | 1.13%   |
| Intel SSD 660P Series                                                          | 41        | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 40        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 39        | 1.05%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 38        | 1.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 33        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 30        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 29        | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 28        | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 27        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 26        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 26        | 0.7%    |
| AMD 600 Series Chipset SATA Controller                                         | 26        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 25        | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 24        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1745      | 53.78%  |
| NVMe | 1034      | 31.86%  |
| IDE  | 262       | 8.07%   |
| RAID | 191       | 5.89%   |
| SAS  | 9         | 0.28%   |
| SCSI | 4         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1780      | 71.98%  |
| AMD      | 667       | 26.97%  |
| ARM      | 24        | 0.97%   |
| QUALCOMM | 1         | 0.04%   |
| Unknown  | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 35        | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 33        | 1.33%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 30        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 26        | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor           | 26        | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 25        | 1.01%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 22        | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 19        | 0.77%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 19        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 19        | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 19        | 0.77%   |
| ARM Processor                               | 17        | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 16        | 0.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 16        | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 14        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 14        | 0.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 14        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 13        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 0.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 13        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 13        | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 12        | 0.48%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12        | 0.48%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 12        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 12        | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 12        | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 11        | 0.44%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 11        | 0.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 11        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.44%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 11        | 0.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 11        | 0.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.44%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11        | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 10        | 0.4%    |
| Intel Core i5-8350U CPU @ 1.70GHz           | 10        | 0.4%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 10        | 0.4%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 10        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 583       | 23.56%  |
| Intel Core i7           | 528       | 21.33%  |
| Other                   | 228       | 9.21%   |
| AMD Ryzen 5             | 170       | 6.87%   |
| AMD Ryzen 7             | 153       | 6.18%   |
| Intel Core i3           | 100       | 4.04%   |
| Intel Celeron           | 86        | 3.47%   |
| AMD Ryzen 9             | 78        | 3.15%   |
| Intel Core 2 Duo        | 68        | 2.75%   |
| Intel Xeon              | 57        | 2.3%    |
| Intel Pentium           | 40        | 1.62%   |
| AMD FX                  | 34        | 1.37%   |
| Intel Atom              | 30        | 1.21%   |
| AMD Ryzen 3             | 21        | 0.85%   |
| AMD A8                  | 20        | 0.81%   |
| Intel Core i9           | 18        | 0.73%   |
| Intel Core 2 Quad       | 18        | 0.73%   |
| Intel Core 2            | 16        | 0.65%   |
| AMD A6                  | 14        | 0.57%   |
| AMD Ryzen 7 PRO         | 13        | 0.53%   |
| AMD Ryzen Threadripper  | 12        | 0.48%   |
| Intel Genuine           | 11        | 0.44%   |
| AMD Phenom II X4        | 11        | 0.44%   |
| AMD A4                  | 11        | 0.44%   |
| AMD A10                 | 11        | 0.44%   |
| AMD E1                  | 10        | 0.4%    |
| Intel Pentium Dual-Core | 9         | 0.36%   |
| AMD E                   | 8         | 0.32%   |
| Intel Pentium Silver    | 7         | 0.28%   |
| ARM BCM                 | 7         | 0.28%   |
| AMD Ryzen 5 PRO         | 7         | 0.28%   |
| AMD Phenom II X6        | 7         | 0.28%   |
| AMD Athlon II X2        | 7         | 0.28%   |
| AMD Athlon 64 X2        | 7         | 0.28%   |
| Intel Pentium Dual      | 6         | 0.24%   |
| AMD Ryzen Embedded      | 5         | 0.2%    |
| Intel Pentium M         | 4         | 0.16%   |
| Intel Core m3           | 3         | 0.12%   |
| Intel Celeron Dual-Core | 3         | 0.12%   |
| AMD Turion 64 X2 Mobile | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 920       | 37.13%  |
| 2       | 785       | 31.68%  |
| 6       | 301       | 12.15%  |
| 8       | 242       | 9.77%   |
| 12      | 71        | 2.87%   |
| 16      | 39        | 1.57%   |
| 1       | 34        | 1.37%   |
| 10      | 24        | 0.97%   |
| 14      | 22        | 0.89%   |
| 3       | 19        | 0.77%   |
| Unknown | 5         | 0.2%    |
| 24      | 4         | 0.16%   |
| 18      | 4         | 0.16%   |
| 32      | 3         | 0.12%   |
| 64      | 2         | 0.08%   |
| 20      | 2         | 0.08%   |
| 28      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2440      | 98.67%  |
| 2       | 28        | 1.13%   |
| Unknown | 4         | 0.16%   |
| 3       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1739      | 70.15%  |
| 1       | 735       | 29.65%  |
| Unknown | 5         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2420      | 97.7%   |
| Unknown        | 43        | 1.74%   |
| 32-bit         | 12        | 0.48%   |
| 64-bit         | 2         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 895       | 34.42%  |
| 0x306c3    | 108       | 4.15%   |
| 0x206a7    | 99        | 3.81%   |
| 0x306a9    | 95        | 3.65%   |
| 0x806ea    | 54        | 2.08%   |
| 0x906ea    | 52        | 2%      |
| 0x806c1    | 52        | 2%      |
| 0x40651    | 52        | 2%      |
| 0x806ec    | 50        | 1.92%   |
| 0x1067a    | 50        | 1.92%   |
| 0x406e3    | 48        | 1.85%   |
| 0x506e3    | 47        | 1.81%   |
| 0x306d4    | 47        | 1.81%   |
| 0x906e9    | 46        | 1.77%   |
| 0x08701021 | 46        | 1.77%   |
| 0x806e9    | 43        | 1.65%   |
| 0x20655    | 28        | 1.08%   |
| 0x0a50000c | 25        | 0.96%   |
| 0x08108109 | 23        | 0.88%   |
| 0x08701013 | 22        | 0.85%   |
| 0x0800820d | 22        | 0.85%   |
| 0x406c4    | 19        | 0.73%   |
| 0x08600106 | 18        | 0.69%   |
| 0x906ed    | 16        | 0.62%   |
| 0x6fd      | 15        | 0.58%   |
| 0x30678    | 15        | 0.58%   |
| 0x06000852 | 15        | 0.58%   |
| 0x010000c8 | 15        | 0.58%   |
| 0x806eb    | 14        | 0.54%   |
| 0x306f2    | 14        | 0.54%   |
| 0x106e5    | 14        | 0.54%   |
| 0x0a201009 | 14        | 0.54%   |
| 0x0810100b | 14        | 0.54%   |
| 0xa0652    | 13        | 0.5%    |
| 0x906a3    | 13        | 0.5%    |
| 0x08608103 | 13        | 0.5%    |
| 0x08001138 | 13        | 0.5%    |
| 0x06001119 | 13        | 0.5%    |
| 0x6f6      | 12        | 0.46%   |
| 0x0a50000d | 12        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 424       | 17.1%   |
| Haswell           | 246       | 9.92%   |
| SandyBridge       | 158       | 6.37%   |
| Unknown           | 158       | 6.37%   |
| IvyBridge         | 147       | 5.93%   |
| Skylake           | 146       | 5.89%   |
| Zen 2             | 141       | 5.69%   |
| Zen 3             | 117       | 4.72%   |
| Penryn            | 81        | 3.27%   |
| TigerLake         | 74        | 2.99%   |
| Zen+              | 73        | 2.94%   |
| Broadwell         | 67        | 2.7%    |
| Silvermont        | 62        | 2.5%    |
| Zen               | 59        | 2.38%   |
| Westmere          | 59        | 2.38%   |
| Core              | 57        | 2.3%    |
| Alderlake Hybrid  | 56        | 2.26%   |
| K10               | 45        | 1.82%   |
| Piledriver        | 42        | 1.69%   |
| CometLake         | 41        | 1.65%   |
| Icelake           | 31        | 1.25%   |
| Nehalem           | 26        | 1.05%   |
| Goldmont plus     | 25        | 1.01%   |
| Excavator         | 20        | 0.81%   |
| K8 Hammer         | 14        | 0.56%   |
| Goldmont          | 14        | 0.56%   |
| Jaguar            | 13        | 0.52%   |
| Puma              | 12        | 0.48%   |
| K10 Llano         | 12        | 0.48%   |
| Bobcat            | 12        | 0.48%   |
| Bulldozer         | 10        | 0.4%    |
| Bonnell           | 9         | 0.36%   |
| Tremont           | 6         | 0.24%   |
| Steamroller       | 6         | 0.24%   |
| P6                | 6         | 0.24%   |
| K8 & K10 hybrid   | 4         | 0.16%   |
| NetBurst          | 3         | 0.12%   |
| Meteorlake Hybrid | 1         | 0.04%   |
| K6                | 1         | 0.04%   |
| Geode             | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1295      | 45.14%  |
| Nvidia                           | 890       | 31.02%  |
| AMD                              | 661       | 23.04%  |
| Matrox Electronics Systems       | 11        | 0.38%   |
| ASPEED Technology                | 9         | 0.31%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 107       | 3.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 2.62%   |
| Intel UHD Graphics 620                                                                   | 77        | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 65        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 55        | 1.85%   |
| Intel HD Graphics 620                                                                    | 52        | 1.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 49        | 1.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 49        | 1.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.45%   |
| Intel HD Graphics 5500                                                                   | 42        | 1.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 42        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 1.38%   |
| Intel HD Graphics 630                                                                    | 40        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 34        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 0.98%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 27        | 0.91%   |
| Intel HD Graphics 530                                                                    | 27        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 27        | 0.91%   |
| AMD Lucienne                                                                             | 26        | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 0.74%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 22        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 21        | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 21        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 19        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 19        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 19        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 0.64%   |
| AMD Raphael                                                                              | 19        | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.61%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 18        | 0.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 943       | 37.81%  |
| 1 x Nvidia               | 553       | 22.17%  |
| 1 x AMD                  | 511       | 20.49%  |
| Intel + Nvidia           | 270       | 10.83%  |
| 2 x AMD                  | 55        | 2.21%   |
| AMD + Nvidia             | 55        | 2.21%   |
| Intel + AMD              | 40        | 1.6%    |
| Other                    | 29        | 1.16%   |
| 1 x Matrox               | 9         | 0.36%   |
| 1 x ASPEED               | 8         | 0.32%   |
| 2 x Intel                | 6         | 0.24%   |
| 2 x Nvidia               | 5         | 0.2%    |
| 1 x SiS                  | 3         | 0.12%   |
| Intel + 2 x Nvidia       | 2         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.08%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.04%   |
| Nvidia + Matrox          | 1         | 0.04%   |
| Nvidia + ASPEED          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1844      | 73.32%  |
| Proprietary | 552       | 21.95%  |
| Unknown     | 119       | 4.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1456      | 56.99%  |
| 1.01-2.0   | 255       | 9.98%   |
| 0.01-0.5   | 239       | 9.35%   |
| 7.01-8.0   | 154       | 6.03%   |
| 3.01-4.0   | 144       | 5.64%   |
| 0.51-1.0   | 143       | 5.6%    |
| 5.01-6.0   | 70        | 2.74%   |
| 8.01-16.0  | 56        | 2.19%   |
| 2.01-3.0   | 27        | 1.06%   |
| 16.01-24.0 | 11        | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 347       | 12.28%  |
| Samsung Electronics     | 342       | 12.1%   |
| LG Display              | 208       | 7.36%   |
| Chimei Innolux          | 202       | 7.15%   |
| Dell                    | 164       | 5.8%    |
| BenQ                    | 139       | 4.92%   |
| BOE                     | 131       | 4.64%   |
| Philips                 | 120       | 4.25%   |
| Hewlett-Packard         | 115       | 4.07%   |
| Ancor Communications    | 113       | 4%      |
| Acer                    | 102       | 3.61%   |
| AOC                     | 101       | 3.57%   |
| Goldstar                | 76        | 2.69%   |
| Apple                   | 72        | 2.55%   |
| Sharp                   | 70        | 2.48%   |
| Lenovo                  | 68        | 2.41%   |
| ASUSTek Computer        | 44        | 1.56%   |
| MSI                     | 29        | 1.03%   |
| InfoVision              | 29        | 1.03%   |
| Chi Mei Optoelectronics | 25        | 0.88%   |
| Eizo                    | 24        | 0.85%   |
| CSO                     | 22        | 0.78%   |
| Sony                    | 18        | 0.64%   |
| LG Philips              | 18        | 0.64%   |
| Vestel Elektronik       | 17        | 0.6%    |
| Unknown                 | 17        | 0.6%    |
| Panasonic               | 17        | 0.6%    |
| PANDA                   | 14        | 0.5%    |
| Fujitsu Siemens         | 13        | 0.46%   |
| LG Electronics          | 11        | 0.39%   |
| ViewSonic               | 10        | 0.35%   |
| Gigabyte Technology     | 8         | 0.28%   |
| Valve                   | 7         | 0.25%   |
| Toshiba                 | 6         | 0.21%   |
| VOXICON                 | 5         | 0.18%   |
| Positivo                | 5         | 0.18%   |
| Microstep               | 5         | 0.18%   |
| LGD                     | 5         | 0.18%   |
| BOE Technology Group    | 5         | 0.18%   |
| Quanta Display          | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 17        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 0.58%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 13        | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 12        | 0.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 12        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 12        | 0.41%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 11        | 0.37%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                  | 9         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.31%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                     | 9         | 0.31%   |
| Ancor Communications ASUS PB278 ACI27A3 1920x1080 597x336mm 27.0-inch | 9         | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.27%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 8         | 0.27%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 797x333mm 34.0-inch                  | 8         | 0.27%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.27%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 8         | 0.27%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.24%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch      | 7         | 0.24%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7         | 0.24%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 7         | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.2%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 6         | 0.2%    |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 6         | 0.2%    |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 6         | 0.2%    |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 6         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 6         | 0.2%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1169      | 43.26%  |
| 1366x768 (WXGA)    | 309       | 11.44%  |
| 3840x2160 (4K)     | 237       | 8.77%   |
| 2560x1440 (QHD)    | 236       | 8.73%   |
| 1920x1200 (WUXGA)  | 98        | 3.63%   |
| 1680x1050 (WSXGA+) | 88        | 3.26%   |
| 3440x1440          | 73        | 2.7%    |
| 1600x900 (HD+)     | 55        | 2.04%   |
| 1280x1024 (SXGA)   | 53        | 1.96%   |
| 1280x800 (WXGA)    | 51        | 1.89%   |
| Unknown            | 41        | 1.52%   |
| 2560x1600          | 40        | 1.48%   |
| 1440x900 (WXGA+)   | 36        | 1.33%   |
| 2880x1800          | 29        | 1.07%   |
| 3840x2400          | 21        | 0.78%   |
| 3840x1080          | 20        | 0.74%   |
| 1360x768           | 15        | 0.56%   |
| 1024x768 (XGA)     | 13        | 0.48%   |
| 1920x540           | 10        | 0.37%   |
| 800x1280           | 9         | 0.33%   |
| 3200x1800 (QHD+)   | 8         | 0.3%    |
| 2736x1824          | 8         | 0.3%    |
| 2560x1080          | 8         | 0.3%    |
| 1280x720 (HD)      | 8         | 0.3%    |
| 2160x1440          | 7         | 0.26%   |
| 2288x1287          | 6         | 0.22%   |
| 3840x1600          | 5         | 0.19%   |
| 1024x600           | 5         | 0.19%   |
| 3200x2000          | 4         | 0.15%   |
| 6400x2160          | 3         | 0.11%   |
| 5760x2160          | 3         | 0.11%   |
| 5760x1080          | 3         | 0.11%   |
| 3200x1200          | 3         | 0.11%   |
| 4480x1440          | 2         | 0.07%   |
| 3840x1200          | 2         | 0.07%   |
| 1920x1280          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 7280x2160          | 1         | 0.04%   |
| 5520x2160          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 497       | 17.79%  |
| 13      | 325       | 11.63%  |
| 27      | 303       | 10.84%  |
| 24      | 296       | 10.59%  |
| 14      | 224       | 8.02%   |
| 23      | 153       | 5.48%   |
| Unknown | 153       | 5.48%   |
| 17      | 98        | 3.51%   |
| 31      | 85        | 3.04%   |
| 12      | 84        | 3.01%   |
| 21      | 77        | 2.76%   |
| 34      | 68        | 2.43%   |
| 22      | 62        | 2.22%   |
| 19      | 52        | 1.86%   |
| 84      | 40        | 1.43%   |
| 16      | 32        | 1.15%   |
| 11      | 29        | 1.04%   |
| 32      | 22        | 0.79%   |
| 20      | 17        | 0.61%   |
| 72      | 15        | 0.54%   |
| 25      | 14        | 0.5%    |
| 54      | 13        | 0.47%   |
| 40      | 13        | 0.47%   |
| 65      | 11        | 0.39%   |
| 18      | 10        | 0.36%   |
| 42      | 9         | 0.32%   |
| 48      | 8         | 0.29%   |
| 39      | 8         | 0.29%   |
| 35      | 7         | 0.25%   |
| 37      | 6         | 0.21%   |
| 29      | 6         | 0.21%   |
| 7       | 6         | 0.21%   |
| 10      | 5         | 0.18%   |
| 142     | 4         | 0.14%   |
| 50      | 4         | 0.14%   |
| 49      | 4         | 0.14%   |
| 46      | 4         | 0.14%   |
| 26      | 4         | 0.14%   |
| 47      | 3         | 0.11%   |
| 33      | 3         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 891       | 32.67%  |
| 501-600        | 680       | 24.94%  |
| 201-300        | 303       | 11.11%  |
| 401-500        | 177       | 6.49%   |
| Unknown        | 153       | 5.61%   |
| 351-400        | 137       | 5.02%   |
| 601-700        | 123       | 4.51%   |
| 701-800        | 93        | 3.41%   |
| 1501-2000      | 58        | 2.13%   |
| 1001-1500      | 51        | 1.87%   |
| 801-900        | 32        | 1.17%   |
| 901-1000       | 15        | 0.55%   |
| 1-100          | 9         | 0.33%   |
| More than 2000 | 4         | 0.15%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1774      | 70.73%  |
| 16/10   | 393       | 15.67%  |
| Unknown | 137       | 5.46%   |
| 21/9    | 84        | 3.35%   |
| 5/4     | 56        | 2.23%   |
| 3/2     | 23        | 0.92%   |
| 4/3     | 14        | 0.56%   |
| 32/9    | 8         | 0.32%   |
| 6/5     | 6         | 0.24%   |
| 0.67    | 6         | 0.24%   |
| 1.00    | 4         | 0.16%   |
| 3.40    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |
| 0.45    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 490       | 17.8%   |
| 201-250        | 433       | 15.73%  |
| 81-90          | 397       | 14.42%  |
| 301-350        | 305       | 11.08%  |
| 351-500        | 185       | 6.72%   |
| 71-80          | 154       | 5.59%   |
| Unknown        | 153       | 5.56%   |
| 251-300        | 128       | 4.65%   |
| More than 1000 | 100       | 3.63%   |
| 151-200        | 82        | 2.98%   |
| 61-70          | 76        | 2.76%   |
| 121-130        | 76        | 2.76%   |
| 501-1000       | 54        | 1.96%   |
| 111-120        | 33        | 1.2%    |
| 51-60          | 30        | 1.09%   |
| 141-150        | 21        | 0.76%   |
| 131-140        | 14        | 0.51%   |
| 1-40           | 9         | 0.33%   |
| 91-100         | 7         | 0.25%   |
| 41-50          | 6         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 828       | 31.15%  |
| 121-160       | 708       | 26.64%  |
| 101-120       | 575       | 21.63%  |
| 161-240       | 224       | 8.43%   |
| Unknown       | 153       | 5.76%   |
| More than 240 | 101       | 3.8%    |
| 1-50          | 69        | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1887      | 74.35%  |
| 2     | 463       | 18.24%  |
| 0     | 122       | 4.81%   |
| 3     | 56        | 2.21%   |
| 4     | 9         | 0.35%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1397      | 39.14%  |
| Realtek Semiconductor             | 1077      | 30.18%  |
| Qualcomm Atheros                  | 314       | 8.8%    |
| Broadcom                          | 217       | 6.08%   |
| MediaTek                          | 73        | 2.05%   |
| Broadcom Limited                  | 55        | 1.54%   |
| Marvell Technology Group          | 39        | 1.09%   |
| ASIX Electronics                  | 25        | 0.7%    |
| Ralink                            | 23        | 0.64%   |
| Hewlett-Packard                   | 21        | 0.59%   |
| TP-Link                           | 19        | 0.53%   |
| Nvidia                            | 19        | 0.53%   |
| Ralink Technology                 | 18        | 0.5%    |
| Lenovo                            | 18        | 0.5%    |
| ASUSTek Computer                  | 18        | 0.5%    |
| Sierra Wireless                   | 17        | 0.48%   |
| Microsoft                         | 16        | 0.45%   |
| NetGear                           | 14        | 0.39%   |
| Dell                              | 14        | 0.39%   |
| D-Link System                     | 14        | 0.39%   |
| DisplayLink                       | 12        | 0.34%   |
| D-Link                            | 12        | 0.34%   |
| Qualcomm                          | 9         | 0.25%   |
| Huawei Technologies               | 9         | 0.25%   |
| Ericsson Business Mobile Networks | 9         | 0.25%   |
| Qualcomm Atheros Communications   | 8         | 0.22%   |
| Aquantia                          | 8         | 0.22%   |
| FIBOCOM                           | 7         | 0.2%    |
| Samsung Electronics               | 6         | 0.17%   |
| Microchip Technology              | 5         | 0.14%   |
| Arduino SA                        | 5         | 0.14%   |
| Xiaomi                            | 4         | 0.11%   |
| Mellanox Technologies             | 4         | 0.11%   |
| STMicroelectronics                | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| JMicron Technology                | 3         | 0.08%   |
| Belkin Components                 | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Wacom                             | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 726       | 16.86%  |
| Intel Wi-Fi 6 AX200                                                    | 123       | 2.86%   |
| Intel Wireless 8265 / 8275                                             | 120       | 2.79%   |
| Intel I211 Gigabit Network Connection                                  | 120       | 2.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 94        | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 84        | 1.95%   |
| Realtek RTL8125 2.5GbE Controller                                      | 76        | 1.76%   |
| Intel Wireless 7260                                                    | 74        | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 65        | 1.51%   |
| Intel Wireless 8260                                                    | 65        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                                   | 61        | 1.42%   |
| Intel Wi-Fi 6 AX201                                                    | 60        | 1.39%   |
| Intel Wireless 7265                                                    | 56        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 45        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 44        | 1.02%   |
| Intel Ethernet Controller I225-V                                       | 44        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 40        | 0.93%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 38        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 36        | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 36        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 36        | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 34        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 33        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                   | 32        | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 31        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 30        | 0.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 29        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 29        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 29        | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 28        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 28        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 26        | 0.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 25        | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 25        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 25        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 25        | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 24        | 0.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 24        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1002      | 51.73%  |
| Qualcomm Atheros                | 246       | 12.7%   |
| Realtek Semiconductor           | 235       | 12.13%  |
| Broadcom                        | 146       | 7.54%   |
| MediaTek                        | 72        | 3.72%   |
| Broadcom Limited                | 36        | 1.86%   |
| Ralink                          | 23        | 1.19%   |
| Ralink Technology               | 18        | 0.93%   |
| ASUSTek Computer                | 18        | 0.93%   |
| Sierra Wireless                 | 17        | 0.88%   |
| TP-Link                         | 16        | 0.83%   |
| NetGear                         | 14        | 0.72%   |
| Microsoft                       | 11        | 0.57%   |
| D-Link                          | 11        | 0.57%   |
| Marvell Technology Group        | 10        | 0.52%   |
| D-Link System                   | 10        | 0.52%   |
| Qualcomm Atheros Communications | 8         | 0.41%   |
| Dell                            | 8         | 0.41%   |
| Qualcomm                        | 7         | 0.36%   |
| FIBOCOM                         | 7         | 0.36%   |
| Hewlett-Packard                 | 4         | 0.21%   |
| Belkin Components               | 3         | 0.15%   |
| Wacom                           | 2         | 0.1%    |
| Micro Star International        | 2         | 0.1%    |
| Linksys                         | 2         | 0.1%    |
| Edimax Technology               | 2         | 0.1%    |
| ZyXEL Communications            | 1         | 0.05%   |
| Wilocity                        | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| Chu Yuen Enterprise             | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 123       | 6.31%   |
| Intel Wireless 8265 / 8275                                           | 120       | 6.15%   |
| Intel Wireless 7260                                                  | 74        | 3.79%   |
| Intel Wireless 8260                                                  | 65        | 3.33%   |
| Intel Wi-Fi 6 AX201                                                  | 60        | 3.08%   |
| Intel Wireless 7265                                                  | 56        | 2.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 45        | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 44        | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 40        | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 38        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 36        | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 36        | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 36        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 33        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 31        | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 29        | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 29        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 29        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 28        | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 26        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 26        | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 25        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 25        | 1.28%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 24        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 23        | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 21        | 1.08%   |
| Intel Wireless 3160                                                  | 21        | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 20        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 20        | 1.03%   |
| Intel Wireless 3165                                                  | 19        | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 19        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 18        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 17        | 0.87%   |
| Intel Centrino Advanced-N 6200                                       | 16        | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 16        | 0.82%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 16        | 0.82%   |
| Intel Centrino Advanced-N 6235                                       | 15        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 15        | 0.77%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 14        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 13        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 978       | 43.82%  |
| Intel                                  | 846       | 37.9%   |
| Broadcom                               | 104       | 4.66%   |
| Qualcomm Atheros                       | 103       | 4.61%   |
| Marvell Technology Group               | 29        | 1.3%    |
| ASIX Electronics                       | 25        | 1.12%   |
| Broadcom Limited                       | 20        | 0.9%    |
| Nvidia                                 | 19        | 0.85%   |
| Lenovo                                 | 17        | 0.76%   |
| DisplayLink                            | 12        | 0.54%   |
| Hewlett-Packard                        | 8         | 0.36%   |
| Aquantia                               | 8         | 0.36%   |
| Huawei Technologies                    | 7         | 0.31%   |
| Samsung Electronics                    | 6         | 0.27%   |
| Microsoft                              | 5         | 0.22%   |
| Xiaomi                                 | 4         | 0.18%   |
| Microchip Technology                   | 4         | 0.18%   |
| D-Link System                          | 4         | 0.18%   |
| TP-Link                                | 3         | 0.13%   |
| JMicron Technology                     | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.09%   |
| Standard Microsystems                  | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.09%   |
| Qualcomm                               | 2         | 0.09%   |
| Mellanox Technologies                  | 2         | 0.09%   |
| ICS Advent                             | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| Unknown                                | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Netchip Technology                     | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| Gemtek                                 | 1         | 0.04%   |
| D-Link                                 | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| 3Com                                   | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 726       | 31.66%  |
| Intel I211 Gigabit Network Connection                                  | 120       | 5.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 94        | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 84        | 3.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 76        | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 65        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                                   | 61        | 2.66%   |
| Intel Ethernet Controller I225-V                                       | 44        | 1.92%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 1.7%    |
| Intel 82579V Gigabit Network Connection                                | 34        | 1.48%   |
| Intel Ethernet Connection (4) I219-V                                   | 32        | 1.4%    |
| Intel Ethernet Connection (7) I219-V                                   | 30        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 28        | 1.22%   |
| Intel Ethernet Connection I218-LM                                      | 25        | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 25        | 1.09%   |
| Intel Ethernet Connection I219-LM                                      | 24        | 1.05%   |
| Intel Ethernet Connection (6) I219-V                                   | 22        | 0.96%   |
| Intel Ethernet Connection I219-V                                       | 21        | 0.92%   |
| Intel Ethernet Connection I217-V                                       | 21        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 20        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 18        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 18        | 0.78%   |
| Intel I210 Gigabit Network Connection                                  | 17        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 17        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                  | 15        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 13        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 12        | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 11        | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 11        | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                  | 10        | 0.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 10        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 10        | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 9         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2104      | 52.61%  |
| WiFi     | 1832      | 45.81%  |
| Modem    | 51        | 1.28%   |
| Unknown  | 12        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1364      | 52.93%  |
| Ethernet | 1211      | 46.99%  |
| Unknown  | 2         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1286      | 51.77%  |
| 1     | 1062      | 42.75%  |
| 3     | 67        | 2.7%    |
| 0     | 46        | 1.85%   |
| 4     | 15        | 0.6%    |
| 5     | 5         | 0.2%    |
| 11    | 1         | 0.04%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2328      | 93.38%  |
| Yes  | 165       | 6.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 834       | 52.06%  |
| Realtek Semiconductor           | 122       | 7.62%   |
| Apple                           | 82        | 5.12%   |
| Qualcomm Atheros Communications | 79        | 4.93%   |
| IMC Networks                    | 79        | 4.93%   |
| Cambridge Silicon Radio         | 69        | 4.31%   |
| ASUSTek Computer                | 68        | 4.24%   |
| Foxconn / Hon Hai               | 64        | 4%      |
| Broadcom                        | 62        | 3.87%   |
| Lite-On Technology              | 40        | 2.5%    |
| Hewlett-Packard                 | 21        | 1.31%   |
| Dell                            | 18        | 1.12%   |
| MediaTek                        | 16        | 1%      |
| Marvell Semiconductor           | 10        | 0.62%   |
| Ralink                          | 7         | 0.44%   |
| Toshiba                         | 6         | 0.37%   |
| USI                             | 3         | 0.19%   |
| Realtek                         | 3         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Ralink Technology               | 2         | 0.12%   |
| Micro Star International        | 2         | 0.12%   |
| HTC (High Tech Computer)        | 2         | 0.12%   |
| Chicony Electronics             | 2         | 0.12%   |
| Belkin Components               | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Foxconn International           | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |
| Alps Electric                   | 1         | 0.06%   |
| Actions                         | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 171       | 10.62%  |
| Intel Bluetooth Device                              | 168       | 10.43%  |
| Intel AX201 Bluetooth                               | 132       | 8.2%    |
| Intel AX200 Bluetooth                               | 120       | 7.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 89        | 5.53%   |
| Realtek Bluetooth Radio                             | 81        | 5.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 69        | 4.29%   |
| Intel AX211 Bluetooth                               | 48        | 2.98%   |
| Apple Bluetooth Host Controller                     | 40        | 2.48%   |
| IMC Networks Bluetooth Radio                        | 35        | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 1.8%    |
| Intel AX210 Bluetooth                               | 28        | 1.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 1.37%   |
| Apple Bluetooth USB Host Controller                 | 22        | 1.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 1.18%   |
| IMC Networks Wireless_Device                        | 19        | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 18        | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 14        | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 0.81%   |
| MediaTek Wireless_Device                            | 13        | 0.81%   |
| ASUS ASUS USB-BT500                                 | 13        | 0.81%   |
| Lite-On Bluetooth Device                            | 12        | 0.75%   |
| IMC Networks Bluetooth Device                       | 12        | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.68%   |
| Realtek 802.11ac WLAN Adapter                       | 10        | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.62%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.5%    |
| Ralink RT3290 Bluetooth                             | 7         | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1697      | 45.95%  |
| AMD                                  | 768       | 20.8%   |
| Nvidia                               | 689       | 18.66%  |
| C-Media Electronics                  | 69        | 1.87%   |
| Logitech                             | 45        | 1.22%   |
| SteelSeries ApS                      | 25        | 0.68%   |
| Creative Labs                        | 25        | 0.68%   |
| Kingston Technology                  | 23        | 0.62%   |
| GN Netcom                            | 21        | 0.57%   |
| ASUSTek Computer                     | 19        | 0.51%   |
| Realtek Semiconductor                | 16        | 0.43%   |
| Creative Technology                  | 16        | 0.43%   |
| Plantronics                          | 15        | 0.41%   |
| Focusrite-Novation                   | 15        | 0.41%   |
| Texas Instruments                    | 14        | 0.38%   |
| Lenovo                               | 13        | 0.35%   |
| Corsair                              | 12        | 0.32%   |
| Razer USA                            | 10        | 0.27%   |
| Micro Star International             | 10        | 0.27%   |
| SAVITECH                             | 8         | 0.22%   |
| RODE Microphones                     | 7         | 0.19%   |
| Hewlett-Packard                      | 7         | 0.19%   |
| GYROCOM C&C                          | 7         | 0.19%   |
| DSEA A/S                             | 7         | 0.19%   |
| Sony                                 | 6         | 0.16%   |
| Blue Microphones                     | 6         | 0.16%   |
| Apple                                | 6         | 0.16%   |
| Yamaha                               | 5         | 0.14%   |
| JMTek                                | 5         | 0.14%   |
| XMOS                                 | 4         | 0.11%   |
| Audio-Technica                       | 4         | 0.11%   |
| Antlion Audio                        | 4         | 0.11%   |
| VIA Technologies                     | 3         | 0.08%   |
| Unknown                              | 3         | 0.08%   |
| Trust                                | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.08%   |
| Samsung Electronics                  | 3         | 0.08%   |
| Samson Technologies                  | 3         | 0.08%   |
| PreSonus Audio Electronics           | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 232       | 5.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 204       | 4.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 147       | 3.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 144       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 141       | 3.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 122       | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 117       | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 99        | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 86        | 1.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 81        | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 74        | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 73        | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 73        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 67        | 1.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 65        | 1.49%   |
| Intel 200 Series PCH HD Audio                                              | 64        | 1.46%   |
| AMD FCH Azalia Controller                                                  | 63        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 62        | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 61        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 57        | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 57        | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 56        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 52        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 52        | 1.19%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 49        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 48        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 48        | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 46        | 1.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 42        | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 42        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 0.94%   |
| Intel CM238 HD Audio Controller                                            | 36        | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 33        | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 32        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 32        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 32        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 31        | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 31        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 30        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 30        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 339       | 22.6%   |
| SK hynix                     | 254       | 16.93%  |
| Corsair                      | 195       | 13%     |
| Kingston                     | 177       | 11.8%   |
| Micron Technology            | 174       | 11.6%   |
| Unknown                      | 112       | 7.47%   |
| Crucial                      | 73        | 4.87%   |
| G.Skill                      | 44        | 2.93%   |
| Elpida                       | 22        | 1.47%   |
| Ramaxel Technology           | 20        | 1.33%   |
| A-DATA Technology            | 17        | 1.13%   |
| Unknown                      | 12        | 0.8%    |
| Unknown (ABCD)               | 10        | 0.67%   |
| Nanya Technology             | 9         | 0.6%    |
| Patriot                      | 5         | 0.33%   |
| Team                         | 4         | 0.27%   |
| Transcend                    | 2         | 0.13%   |
| Qimonda                      | 2         | 0.13%   |
| Innodisk                     | 2         | 0.13%   |
| GSkill                       | 2         | 0.13%   |
| GOODRAM                      | 2         | 0.13%   |
| G-Alantic                    | 2         | 0.13%   |
| Avant                        | 2         | 0.13%   |
| Apacer                       | 2         | 0.13%   |
| Unknown (AB)                 | 1         | 0.07%   |
| Unknown (83DA)               | 1         | 0.07%   |
| Unknown (836D)               | 1         | 0.07%   |
| Unifosa                      | 1         | 0.07%   |
| TEXTORM                      | 1         | 0.07%   |
| SHARETRONIC                  | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Netlist                      | 1         | 0.07%   |
| Neo Forza                    | 1         | 0.07%   |
| KingSpec                     | 1         | 0.07%   |
| Hyundai lnc                  | 1         | 0.07%   |
| Hewlett-Packard              | 1         | 0.07%   |
| fef5                         | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |
| Ankowall                     | 1         | 0.07%   |
| 8CB900000080                 | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 25        | 1.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 0.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 12        | 0.75%   |
| Unknown                                                          | 12        | 0.75%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.62%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 10        | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 9         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 9         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 7         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.37%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 0.37%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.37%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.37%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.37%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.37%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s           | 6         | 0.37%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 6         | 0.37%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 5         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 5         | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 5         | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.31%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 5         | 0.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s             | 5         | 0.31%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.31%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 649       | 48.51%  |
| DDR3    | 398       | 29.75%  |
| LPDDR4  | 63        | 4.71%   |
| DDR5    | 49        | 3.66%   |
| LPDDR3  | 43        | 3.21%   |
| DDR2    | 42        | 3.14%   |
| SDRAM   | 27        | 2.02%   |
| LPDDR5  | 27        | 2.02%   |
| Unknown | 21        | 1.57%   |
| DRAM    | 10        | 0.75%   |
| DDR     | 9         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 711       | 53.26%  |
| DIMM         | 480       | 35.96%  |
| Row Of Chips | 124       | 9.29%   |
| Chip         | 12        | 0.9%    |
| Unknown      | 4         | 0.3%    |
| RIMM         | 3         | 0.22%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 563       | 39.04%  |
| 4096    | 331       | 22.95%  |
| 16384   | 305       | 21.15%  |
| 2048    | 154       | 10.68%  |
| 32768   | 45        | 3.12%   |
| 1024    | 35        | 2.43%   |
| 512     | 6         | 0.42%   |
| 65536   | 1         | 0.07%   |
| 49152   | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 260       | 18.09%  |
| 3200    | 201       | 13.99%  |
| 2667    | 159       | 11.06%  |
| 2400    | 106       | 7.38%   |
| 2133    | 94        | 6.54%   |
| 3600    | 76        | 5.29%   |
| 1333    | 68        | 4.73%   |
| 1334    | 37        | 2.57%   |
| 4267    | 34        | 2.37%   |
| 1867    | 31        | 2.16%   |
| 4800    | 29        | 2.02%   |
| 667     | 28        | 1.95%   |
| 6400    | 23        | 1.6%    |
| 3800    | 22        | 1.53%   |
| Unknown | 22        | 1.53%   |
| 800     | 20        | 1.39%   |
| 1067    | 18        | 1.25%   |
| 3733    | 14        | 0.97%   |
| 1800    | 13        | 0.9%    |
| 3000    | 12        | 0.84%   |
| 4266    | 11        | 0.77%   |
| 3266    | 10        | 0.7%    |
| 1066    | 10        | 0.7%    |
| 2666    | 9         | 0.63%   |
| 5600    | 8         | 0.56%   |
| 3866    | 8         | 0.56%   |
| 3400    | 8         | 0.56%   |
| 1866    | 8         | 0.56%   |
| 6000    | 7         | 0.49%   |
| 2933    | 7         | 0.49%   |
| 4199    | 6         | 0.42%   |
| 3466    | 6         | 0.42%   |
| 3534    | 5         | 0.35%   |
| 2747    | 5         | 0.35%   |
| 7500    | 4         | 0.28%   |
| 3066    | 4         | 0.28%   |
| 2000    | 4         | 0.28%   |
| 8400    | 3         | 0.21%   |
| 5200    | 3         | 0.21%   |
| 49926   | 2         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 15        | 44.12%  |
| Brother Industries    | 6         | 17.65%  |
| Samsung Electronics   | 5         | 14.71%  |
| Canon                 | 3         | 8.82%   |
| Seiko Epson           | 2         | 5.88%   |
| Prolific Technology   | 1         | 2.94%   |
| Oki Data              | 1         | 2.94%   |
| Lexmark International | 1         | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 5.88%   |
| HP LaserJet 1020                     | 2         | 5.88%   |
| Seiko Epson XP-4100 Series           | 1         | 2.94%   |
| Seiko Epson Printer                  | 1         | 2.94%   |
| Samsung SCX-3200 Series              | 1         | 2.94%   |
| Samsung M2070 Series                 | 1         | 2.94%   |
| Samsung Color Laser Printer          | 1         | 2.94%   |
| Prolific PL2305 Parallel Port        | 1         | 2.94%   |
| Oki Data USB Device                  | 1         | 2.94%   |
| Lexmark International MX310dn        | 1         | 2.94%   |
| HP OfficeJet Pro 8730                | 1         | 2.94%   |
| HP OfficeJet G55                     | 1         | 2.94%   |
| HP LaserJet Professional P 1102w     | 1         | 2.94%   |
| HP LaserJet 1320                     | 1         | 2.94%   |
| HP LaserJet 1010                     | 1         | 2.94%   |
| HP Laser 107w                        | 1         | 2.94%   |
| HP HP LaserJet P2035                 | 1         | 2.94%   |
| HP ENVY 4520 series                  | 1         | 2.94%   |
| HP DeskJet 5650c                     | 1         | 2.94%   |
| HP Deskjet 3050 J610 series          | 1         | 2.94%   |
| HP DeskJet 2700 series               | 1         | 2.94%   |
| HP DeskJet 2130 series               | 1         | 2.94%   |
| HP Color LaserJet CP1215             | 1         | 2.94%   |
| Canon LiDE 300                       | 1         | 2.94%   |
| Canon LBP7010C/7018C                 | 1         | 2.94%   |
| Canon LBP6200                        | 1         | 2.94%   |
| Brother QL-500 label printer         | 1         | 2.94%   |
| Brother HL-5150D series              | 1         | 2.94%   |
| Brother HL-2270DW Laser Printer      | 1         | 2.94%   |
| Brother HL-2130 series               | 1         | 2.94%   |
| Brother DCP-7055W                    | 1         | 2.94%   |
| Brother DCP-7040                     | 1         | 2.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 80%     |
| Seiko Epson     | 1         | 10%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                     | 2         | 20%     |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 10%     |
| HP ScanJet 2200c                            | 1         | 10%     |
| Canon CanoScan LiDE 700F                    | 1         | 10%     |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |
| Canon CanoScan LiDE 120                     | 1         | 10%     |
| Canon CanoScan LiDE 110                     | 1         | 10%     |
| Canon CanoScan 4400F                        | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 321       | 22.91%  |
| Microdia                               | 118       | 8.42%   |
| IMC Networks                           | 118       | 8.42%   |
| Logitech                               | 108       | 7.71%   |
| Realtek Semiconductor                  | 87        | 6.21%   |
| Bison Electronics                      | 85        | 6.07%   |
| Sunplus Innovation Technology          | 64        | 4.57%   |
| Apple                                  | 64        | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 58        | 4.14%   |
| Quanta                                 | 52        | 3.71%   |
| Lite-On Technology                     | 46        | 3.28%   |
| Syntek                                 | 37        | 2.64%   |
| Suyin                                  | 33        | 2.36%   |
| Acer                                   | 27        | 1.93%   |
| Luxvisions Innotech Limited            | 23        | 1.64%   |
| Samsung Electronics                    | 18        | 1.28%   |
| Microsoft                              | 18        | 1.28%   |
| Ricoh                                  | 11        | 0.79%   |
| Lenovo                                 | 10        | 0.71%   |
| Alcor Micro                            | 9         | 0.64%   |
| Z-Star Microelectronics                | 8         | 0.57%   |
| Silicon Motion                         | 7         | 0.5%    |
| Sonix Technology                       | 6         | 0.43%   |
| ALi                                    | 6         | 0.43%   |
| Creative Technology                    | 5         | 0.36%   |
| Trust                                  | 4         | 0.29%   |
| Primax Electronics                     | 4         | 0.29%   |
| DigiTech                               | 4         | 0.29%   |
| ShineTech                              | 3         | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.21%   |
| Razer USA                              | 3         | 0.21%   |
| Importek                               | 3         | 0.21%   |
| Generalplus Technology                 | 3         | 0.21%   |
| ARC International                      | 3         | 0.21%   |
| SunplusIT                              | 2         | 0.14%   |
| Sunplus Technology                     | 2         | 0.14%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.14%   |
| LG Electronics                         | 2         | 0.14%   |
| Hewlett-Packard                        | 2         | 0.14%   |
| Valve Software                         | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 84        | 5.92%   |
| Microdia Integrated_Webcam_HD                                            | 49        | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 46        | 3.24%   |
| IMC Networks Integrated Camera                                           | 38        | 2.68%   |
| Realtek Integrated_Webcam_HD                                             | 31        | 2.18%   |
| Syntek Integrated Camera                                                 | 28        | 1.97%   |
| Bison Integrated Camera                                                  | 28        | 1.97%   |
| Chicony HD WebCam                                                        | 27        | 1.9%    |
| Chicony HP HD Camera                                                     | 24        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 19        | 1.34%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 18        | 1.27%   |
| Logitech Webcam C270                                                     | 18        | 1.27%   |
| Logitech HD Pro Webcam C920                                              | 17        | 1.2%    |
| Lite-On HP HD Camera                                                     | 16        | 1.13%   |
| Apple Built-in iSight                                                    | 16        | 1.13%   |
| Quanta HP HD Camera                                                      | 15        | 1.06%   |
| Logitech C922 Pro Stream Webcam                                          | 14        | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 14        | 0.99%   |
| Sunplus Integrated_Webcam_HD                                             | 13        | 0.92%   |
| Sunplus HD WebCam                                                        | 13        | 0.92%   |
| Apple FaceTime HD Camera (Built-in)                                      | 13        | 0.92%   |
| Lite-On Integrated Camera                                                | 12        | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 0.85%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 0.85%   |
| Realtek USB Camera                                                       | 11        | 0.77%   |
| Microdia USB 2.0 Camera                                                  | 11        | 0.77%   |
| Chicony HP HD Webcam [Fixed]                                             | 11        | 0.77%   |
| Apple FaceTime HD Camera                                                 | 11        | 0.77%   |
| Quanta HD User Facing                                                    | 10        | 0.7%    |
| Lite-On HP HD Webcam                                                     | 10        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 10        | 0.7%    |
| Bison Lenovo EasyCamera                                                  | 10        | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 9         | 0.63%   |
| Chicony USB2.0 Camera                                                    | 9         | 0.63%   |
| Chicony HP Wide Vision HD Camera                                         | 9         | 0.63%   |
| Chicony HP HD Webcam                                                     | 9         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                                             | 8         | 0.56%   |
| Quanta HP TrueVision HD Camera                                           | 8         | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 8         | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 145       | 42.52%  |
| Synaptics                  | 106       | 31.09%  |
| Shenzhen Goodix Technology | 31        | 9.09%   |
| Elan Microelectronics      | 16        | 4.69%   |
| Upek                       | 14        | 4.11%   |
| AuthenTec                  | 12        | 3.52%   |
| LighTuning Technology      | 11        | 3.23%   |
| STMicroelectronics         | 6         | 1.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 14.66%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 7.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 5.28%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 4.4%    |
| Shenzhen Goodix FingerPrint                                                | 14        | 4.11%   |
| Validity Sensors VFS491                                                    | 13        | 3.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 3.52%   |
| Synaptics WBDI                                                             | 10        | 2.93%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 2.93%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 2.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.35%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 2.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.76%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.47%   |
| Synaptics UWP WBDI                                                         | 5         | 1.47%   |
| Synaptics  WBDI                                                            | 5         | 1.47%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.47%   |
| AuthenTec AES2810                                                          | 5         | 1.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.47%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 1.17%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.88%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.59%   |
| Unknown                                                                    | 2         | 0.59%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 86        | 45.5%   |
| Broadcom                          | 69        | 36.51%  |
| O2 Micro                          | 13        | 6.88%   |
| Lenovo                            | 7         | 3.7%    |
| Upek                              | 5         | 2.65%   |
| Gemalto (was Gemplus)             | 3         | 1.59%   |
| Yubico.com                        | 2         | 1.06%   |
| VASCO Data Security International | 1         | 0.53%   |
| Hewlett-Packard                   | 1         | 0.53%   |
| Chicony Electronics               | 1         | 0.53%   |
| CHERRY                            | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 43.92%  |
| Broadcom 58200                                                               | 21        | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 10.58%  |
| Broadcom 5880                                                                | 14        | 7.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 6.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 5.82%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 2.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.59%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.59%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.06%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.53%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.53%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.53%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1667      | 65.71%  |
| 1     | 659       | 25.98%  |
| 2     | 182       | 7.17%   |
| 3     | 20        | 0.79%   |
| 4     | 7         | 0.28%   |
| 7     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 339       | 31.22%  |
| Graphics card            | 199       | 18.32%  |
| Chipcard                 | 166       | 15.29%  |
| Net/wireless             | 98        | 9.02%   |
| Multimedia controller    | 77        | 7.09%   |
| Communication controller | 51        | 4.7%    |
| Camera                   | 36        | 3.31%   |
| Unassigned class         | 30        | 2.76%   |
| Bluetooth                | 25        | 2.3%    |
| Sound                    | 18        | 1.66%   |
| Card reader              | 14        | 1.29%   |
| Storage                  | 9         | 0.83%   |
| Net/ethernet             | 9         | 0.83%   |
| Firewire controller      | 3         | 0.28%   |
| Storage/ata              | 2         | 0.18%   |
| Network                  | 2         | 0.18%   |
| Modem                    | 2         | 0.18%   |
| Flash memory             | 2         | 0.18%   |
| Storage/raid             | 1         | 0.09%   |
| Storage/nvme             | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Dvb card                 | 1         | 0.09%   |

