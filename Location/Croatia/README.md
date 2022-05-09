Linux in Croatia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Croatia/Desktop/README.md) and [notebooks](/Location/Croatia/Notebook/README.md).

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

Total: 567

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | Desktop     | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Razer         | Blade                       | Notebook    | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [2147b931e3](https://linux-hardware.org/?probe=2147b931e3) | Apr 22, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [2dcace1084](https://linux-hardware.org/?probe=2dcace1084) | Apr 21, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [f4ca737c25](https://linux-hardware.org/?probe=f4ca737c25) | Mar 31, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | Notebook    | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| HP            | ProBook 4530s               | Notebook    | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [e669f0a460](https://linux-hardware.org/?probe=e669f0a460) | Mar 06, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | Notebook    | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | Notebook    | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f7cce89284](https://linux-hardware.org/?probe=f7cce89284) | Feb 17, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [980b14c09a](https://linux-hardware.org/?probe=980b14c09a) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | Notebook    | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| HP            | 82DC 1100                   | All in one  | [e3a85b9aaf](https://linux-hardware.org/?probe=e3a85b9aaf) | Feb 09, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [ffb245749e](https://linux-hardware.org/?probe=ffb245749e) | Jan 12, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | Desktop     | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| ASRock        | 870 Extreme3                | Desktop     | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [247642d30f](https://linux-hardware.org/?probe=247642d30f) | Dec 16, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | Notebook    | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | Notebook    | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| MSI           | P55-CD53                    | Desktop     | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a62e03df32](https://linux-hardware.org/?probe=a62e03df32) | Sep 25, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8803020fce](https://linux-hardware.org/?probe=8803020fce) | Sep 11, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | Notebook    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | Notebook    | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0f1f02371d](https://linux-hardware.org/?probe=0f1f02371d) | Jul 19, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [40424da04c](https://linux-hardware.org/?probe=40424da04c) | Jul 08, 2021 |
| Dell          | Latitude 3190               | Notebook    | [6ca8a34d23](https://linux-hardware.org/?probe=6ca8a34d23) | Jul 05, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [ec46d1beb2](https://linux-hardware.org/?probe=ec46d1beb2) | Jun 28, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | Notebook    | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | Notebook    | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| Dell          | 06CV2N A01                  | Desktop     | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [84248bb07c](https://linux-hardware.org/?probe=84248bb07c) | May 03, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | Notebook    | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| ASRock        | P45DE                       | Desktop     | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | Notebook    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF GAMING Z490-PLUS        | Desktop     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | Notebook    | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | Notebook    | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Dell          | 0NNGP2 A00                  | Desktop     | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASRock        | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | Notebook    | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [c4e582f9c3](https://linux-hardware.org/?probe=c4e582f9c3) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| HP            | 18EA                        | All in one  | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| ASRock        | Z370 Pro4                   | Desktop     | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [f5bf5ee5fb](https://linux-hardware.org/?probe=f5bf5ee5fb) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| Acer          | Aspire 7739G                | Notebook    | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [72e2891df0](https://linux-hardware.org/?probe=72e2891df0) | Dec 11, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [9dd7d150b8](https://linux-hardware.org/?probe=9dd7d150b8) | Dec 08, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | Notebook    | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [ae2f02866d](https://linux-hardware.org/?probe=ae2f02866d) | Nov 22, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Nvidia        | Tegra                       | Soc         | [ef24e8c128](https://linux-hardware.org/?probe=ef24e8c128) | Oct 23, 2020 |
| Nvidia        | Tegra                       | Soc         | [003e82dbfb](https://linux-hardware.org/?probe=003e82dbfb) | Oct 23, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6e1e46a3cb](https://linux-hardware.org/?probe=6e1e46a3cb) | Oct 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| Toshiba       | Satellite C55-A-1M7         | Notebook    | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | Notebook    | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| ASUSTek       | M4A77                       | Desktop     | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | Desktop     | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [fdc95a9b5e](https://linux-hardware.org/?probe=fdc95a9b5e) | Aug 15, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [3a826b3414](https://linux-hardware.org/?probe=3a826b3414) | Aug 13, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | Notebook    | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Lenovo        | IdeaCentre Stick 300-01I... | Stick pc    | [28b902c9b7](https://linux-hardware.org/?probe=28b902c9b7) | Jul 21, 2020 |
| Dell          | Precision 5530              | Notebook    | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6a29cd065c](https://linux-hardware.org/?probe=6a29cd065c) | Jul 15, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | Notebook    | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [949f6cb34c](https://linux-hardware.org/?probe=949f6cb34c) | Jul 13, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ac52acb928](https://linux-hardware.org/?probe=ac52acb928) | Jun 24, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | Notebook    | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [2c0b3072ac](https://linux-hardware.org/?probe=2c0b3072ac) | Jun 09, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [44ea78341a](https://linux-hardware.org/?probe=44ea78341a) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d77566be76](https://linux-hardware.org/?probe=d77566be76) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [06f88752e5](https://linux-hardware.org/?probe=06f88752e5) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [15cf043276](https://linux-hardware.org/?probe=15cf043276) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [89935abc60](https://linux-hardware.org/?probe=89935abc60) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bbb1f5819f](https://linux-hardware.org/?probe=bbb1f5819f) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | Desktop     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| eMachines     | G725                        | Notebook    | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [e2ab63b529](https://linux-hardware.org/?probe=e2ab63b529) | May 02, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [33be21bf03](https://linux-hardware.org/?probe=33be21bf03) | May 02, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | Notebook    | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | Notebook    | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| HP            | 3031h                       | Desktop     | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | Desktop     | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| ASUSTek       | A8V-MQ                      | Desktop     | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| Medion        | P6618                       | Notebook    | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | Desktop     | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | Notebook    | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bdebb9000c](https://linux-hardware.org/?probe=bdebb9000c) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [65c38da632](https://linux-hardware.org/?probe=65c38da632) | Feb 20, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| HP            | Pavilion g6                 | Notebook    | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| ASRock        | B150M-HDV                   | Desktop     | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | 18E7                        | Desktop     | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | Desktop     | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [3317c231ea](https://linux-hardware.org/?probe=3317c231ea) | Jan 08, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | Notebook    | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | Desktop     | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | N68-S3 UCC                  | Desktop     | [86f93b71dd](https://linux-hardware.org/?probe=86f93b71dd) | Dec 24, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| ASRock        | H97 Killer                  | Desktop     | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | OMEN by HP Laptop 17-cb0... | Notebook    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | Notebook    | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| HP            | 18EA                        | All in one  | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [76af33f6a0](https://linux-hardware.org/?probe=76af33f6a0) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [83f979f993](https://linux-hardware.org/?probe=83f979f993) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [662f5b1284](https://linux-hardware.org/?probe=662f5b1284) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [b90ab9f1ac](https://linux-hardware.org/?probe=b90ab9f1ac) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| ASUSTek       | G750JZ                      | Notebook    | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [223de1d51b](https://linux-hardware.org/?probe=223de1d51b) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5dcbb1bf21](https://linux-hardware.org/?probe=5dcbb1bf21) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | Notebook    | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | Notebook    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [59a4b66b03](https://linux-hardware.org/?probe=59a4b66b03) | Jul 30, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | Desktop     | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [dd91a2582a](https://linux-hardware.org/?probe=dd91a2582a) | Jul 06, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | Notebook    | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | Notebook    | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | Notebook    | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | 83ED                        | Desktop     | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [ca189683d0](https://linux-hardware.org/?probe=ca189683d0) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [3fcf0f0723](https://linux-hardware.org/?probe=3fcf0f0723) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [31d91d2705](https://linux-hardware.org/?probe=31d91d2705) | Apr 30, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [784a5d3cb1](https://linux-hardware.org/?probe=784a5d3cb1) | Apr 30, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | Notebook    | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| Dell          | 00X7CK A02                  | Server      | [5b9ec879fc](https://linux-hardware.org/?probe=5b9ec879fc) | Mar 11, 2019 |
| Pegatron      | 2A99                        | Desktop     | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| HP            | Unknown                     | Notebook    | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | B150M-C                     | Desktop     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | Desktop     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | Desktop     | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [ae1021afdc](https://linux-hardware.org/?probe=ae1021afdc) | Dec 16, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | Notebook    | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| Unknown       | Grantsdale                  | Desktop     | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| HP            | ProBook 450 G4              | Notebook    | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | Desktop     | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |
| HP            | EliteBook 2540p             | Notebook    | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | Notebook    | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Dell          | Vostro 1700                 | Notebook    | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | Notebook    | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 70        | 17.95%  |
| Ubuntu 18.04        | 35        | 8.97%   |
| Linux Mint 20.2     | 10        | 2.56%   |
| Ubuntu 18.10        | 9         | 2.31%   |
| Pop!_OS 21.04       | 9         | 2.31%   |
| OpenMandriva 4.3    | 9         | 2.31%   |
| Debian 11           | 9         | 2.31%   |
| Zorin 16            | 7         | 1.79%   |
| Pop!_OS 20.04       | 7         | 1.79%   |
| Ubuntu 21.04        | 6         | 1.54%   |
| Ubuntu 19.10        | 6         | 1.54%   |
| Pop!_OS 21.10       | 6         | 1.54%   |
| Pop!_OS 20.10       | 6         | 1.54%   |
| OpenMandriva 4.2    | 6         | 1.54%   |
| Linux Mint 20.3     | 6         | 1.54%   |
| Debian 10           | 6         | 1.54%   |
| Ubuntu 19.04        | 5         | 1.28%   |
| Fedora 35           | 5         | 1.28%   |
| Endless 3.7.8       | 5         | 1.28%   |
| ArcoLinux Rolling   | 5         | 1.28%   |
| Zorin 15            | 4         | 1.03%   |
| Ubuntu 20.10        | 4         | 1.03%   |
| Manjaro             | 4         | 1.03%   |
| Linux Mint 20       | 4         | 1.03%   |
| KDE neon 20.04      | 4         | 1.03%   |
| Fedora 31           | 4         | 1.03%   |
| Arch Rolling        | 4         | 1.03%   |
| Ubuntu MATE 20.04   | 3         | 0.77%   |
| ROSA R10            | 3         | 0.77%   |
| OpenMandriva 4.50   | 3         | 0.77%   |
| Linux Mint 19.3     | 3         | 0.77%   |
| Kubuntu 20.04       | 3         | 0.77%   |
| Fedora 34           | 3         | 0.77%   |
| Endless 3.9.5       | 3         | 0.77%   |
| Endless 3.9.4       | 3         | 0.77%   |
| Arch                | 3         | 0.77%   |
| Xubuntu 20.04       | 2         | 0.51%   |
| Xubuntu 18.04       | 2         | 0.51%   |
| Ubuntu Budgie 20.04 | 2         | 0.51%   |
| Ubuntu 22.04        | 2         | 0.51%   |
| Ubuntu 21.10        | 2         | 0.51%   |
| openSUSE Leap-15.2  | 2         | 0.51%   |
| Manjaro 21.0.7      | 2         | 0.51%   |
| Manjaro 21.0        | 2         | 0.51%   |
| Manjaro 20.2.1      | 2         | 0.51%   |
| Manjaro 20.2        | 2         | 0.51%   |
| Manjaro 20.1.2      | 2         | 0.51%   |
| Manjaro 18.1.5      | 2         | 0.51%   |
| LMDE 4              | 2         | 0.51%   |
| Linux Mint 19       | 2         | 0.51%   |
| Kubuntu 21.04       | 2         | 0.51%   |
| Fedora 33           | 2         | 0.51%   |
| Endless 3.9.3       | 2         | 0.51%   |
| Endless 3.8.3       | 2         | 0.51%   |
| Elementary 6.1      | 2         | 0.51%   |
| Elementary 5.1.7    | 2         | 0.51%   |
| Ubuntu MATE 22.04   | 1         | 0.26%   |
| Ubuntu MATE 19.10   | 1         | 0.26%   |
| Ubuntu MATE 18.04   | 1         | 0.26%   |
| Ubuntu Budgie 18.04 | 1         | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 131       | 37.01%  |
| Pop!_OS       | 29        | 8.19%   |
| Linux Mint    | 28        | 7.91%   |
| Endless       | 23        | 6.5%    |
| OpenMandriva  | 18        | 5.08%   |
| Manjaro       | 18        | 5.08%   |
| Fedora        | 15        | 4.24%   |
| Debian        | 15        | 4.24%   |
| Zorin         | 11        | 3.11%   |
| Kubuntu       | 8         | 2.26%   |
| Arch          | 7         | 1.98%   |
| Ubuntu MATE   | 5         | 1.41%   |
| ROSA          | 5         | 1.41%   |
| openSUSE      | 5         | 1.41%   |
| Elementary    | 5         | 1.41%   |
| ArcoLinux     | 5         | 1.41%   |
| Xubuntu       | 4         | 1.13%   |
| KDE neon      | 4         | 1.13%   |
| Ubuntu Budgie | 3         | 0.85%   |
| LMDE          | 2         | 0.56%   |
| LinuxFX       | 2         | 0.56%   |
| Kali          | 2         | 0.56%   |
| EndeavourOS   | 2         | 0.56%   |
| Raspbian      | 1         | 0.28%   |
| Parrot        | 1         | 0.28%   |
| MX            | 1         | 0.28%   |
| Lubuntu       | 1         | 0.28%   |
| Gentoo        | 1         | 0.28%   |
| Clear Linux   | 1         | 0.28%   |
| CentOS        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 2.12%   |
| 5.4.0-42-generic         | 8         | 1.88%   |
| 5.11.0-38-generic        | 8         | 1.88%   |
| 5.8.0-14-generic         | 6         | 1.41%   |
| 5.3.0-28-generic         | 6         | 1.41%   |
| 5.11.0-7620-generic      | 6         | 1.41%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.41%   |
| 5.4.0-91-generic         | 5         | 1.18%   |
| 5.4.0-58-generic         | 5         | 1.18%   |
| 5.4.0-48-generic         | 5         | 1.18%   |
| 5.4.0-37-generic         | 5         | 1.18%   |
| 5.11.0-41-generic        | 5         | 1.18%   |
| 5.8.0-59-generic         | 4         | 0.94%   |
| 5.8.0-48-generic         | 4         | 0.94%   |
| 5.4.0-52-generic         | 4         | 0.94%   |
| 5.4.0-40-generic         | 4         | 0.94%   |
| 5.3.0-26-generic         | 4         | 0.94%   |
| 5.13.0-30-generic        | 4         | 0.94%   |
| 5.11.0-40-generic        | 4         | 0.94%   |
| 4.18.0-10-generic        | 4         | 0.94%   |
| 5.8.16-2-MANJARO         | 3         | 0.71%   |
| 5.8.0-7630-generic       | 3         | 0.71%   |
| 5.8.0-43-generic         | 3         | 0.71%   |
| 5.4.0-56-generic         | 3         | 0.71%   |
| 5.4.0-47-generic         | 3         | 0.71%   |
| 5.4.0-29-generic         | 3         | 0.71%   |
| 5.4.0-26-generic         | 3         | 0.71%   |
| 5.4.0-19-generic         | 3         | 0.71%   |
| 5.4.0-100-generic        | 3         | 0.71%   |
| 5.3.0-40-generic         | 3         | 0.71%   |
| 5.3.0-23-generic         | 3         | 0.71%   |
| 5.16.11-76051611-generic | 3         | 0.71%   |
| 5.13.0-7620-generic      | 3         | 0.71%   |
| 5.13.0-40-generic        | 3         | 0.71%   |
| 5.12.4-desktop-1omv4050  | 3         | 0.71%   |
| 5.11.0-37-generic        | 3         | 0.71%   |
| 5.11.0-34-generic        | 3         | 0.71%   |
| 5.11.0-27-generic        | 3         | 0.71%   |
| 5.0.0-27-generic         | 3         | 0.71%   |
| 4.18.0-18-generic        | 3         | 0.71%   |
| 4.18.0-15-generic        | 3         | 0.71%   |
| 4.15.0-20-generic        | 3         | 0.71%   |
| 5.9.16-1-MANJARO         | 2         | 0.47%   |
| 5.8.0-49-generic         | 2         | 0.47%   |
| 5.4.0-90-generic         | 2         | 0.47%   |
| 5.4.0-84-generic         | 2         | 0.47%   |
| 5.4.0-7642-generic       | 2         | 0.47%   |
| 5.4.0-60-generic         | 2         | 0.47%   |
| 5.4.0-54-generic         | 2         | 0.47%   |
| 5.4.0-33-generic         | 2         | 0.47%   |
| 5.4.0-31-generic         | 2         | 0.47%   |
| 5.4.0-109-generic        | 2         | 0.47%   |
| 5.3.0-42-generic         | 2         | 0.47%   |
| 5.3.0-24-generic         | 2         | 0.47%   |
| 5.15.8-76051508-generic  | 2         | 0.47%   |
| 5.15.15-76051515-generic | 2         | 0.47%   |
| 5.15.0-27-generic        | 2         | 0.47%   |
| 5.13.0-39-generic        | 2         | 0.47%   |
| 5.13.0-35-generic        | 2         | 0.47%   |
| 5.11.0-7633-generic      | 2         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 84        | 21.11%  |
| 5.11.0  | 46        | 11.56%  |
| 5.8.0   | 26        | 6.53%   |
| 5.3.0   | 24        | 6.03%   |
| 4.15.0  | 24        | 6.03%   |
| 4.18.0  | 19        | 4.77%   |
| 5.13.0  | 17        | 4.27%   |
| 5.0.0   | 14        | 3.52%   |
| 5.10.0  | 11        | 2.76%   |
| 5.16.7  | 10        | 2.51%   |
| 5.15.0  | 6         | 1.51%   |
| 5.10.14 | 6         | 1.51%   |
| 4.19.0  | 6         | 1.51%   |
| 5.9.16  | 4         | 1.01%   |
| 5.16.11 | 4         | 1.01%   |
| 5.12.4  | 4         | 1.01%   |
| 5.8.16  | 3         | 0.75%   |
| 5.3.18  | 3         | 0.75%   |
| 5.15.8  | 3         | 0.75%   |
| 4.9.60  | 3         | 0.75%   |
| 5.9.11  | 2         | 0.5%    |
| 5.7.11  | 2         | 0.5%    |
| 5.5.0   | 2         | 0.5%    |
| 5.17.4  | 2         | 0.5%    |
| 5.15.15 | 2         | 0.5%    |
| 5.10.79 | 2         | 0.5%    |
| 4.16.0  | 2         | 0.5%    |
| 5.9.9   | 1         | 0.25%   |
| 5.9.1   | 1         | 0.25%   |
| 5.9.0   | 1         | 0.25%   |
| 5.8.6   | 1         | 0.25%   |
| 5.7.0   | 1         | 0.25%   |
| 5.6.6   | 1         | 0.25%   |
| 5.6.2   | 1         | 0.25%   |
| 5.6.19  | 1         | 0.25%   |
| 5.6.12  | 1         | 0.25%   |
| 5.6.0   | 1         | 0.25%   |
| 5.4.74  | 1         | 0.25%   |
| 5.4.64  | 1         | 0.25%   |
| 5.4.20  | 1         | 0.25%   |
| 5.4.2   | 1         | 0.25%   |
| 5.4.18  | 1         | 0.25%   |
| 5.4.17  | 1         | 0.25%   |
| 5.4.13  | 1         | 0.25%   |
| 5.3.8   | 1         | 0.25%   |
| 5.3.16  | 1         | 0.25%   |
| 5.2.10  | 1         | 0.25%   |
| 5.17.5  | 1         | 0.25%   |
| 5.17.3  | 1         | 0.25%   |
| 5.17.1  | 1         | 0.25%   |
| 5.16.9  | 1         | 0.25%   |
| 5.16.8  | 1         | 0.25%   |
| 5.16.18 | 1         | 0.25%   |
| 5.16.15 | 1         | 0.25%   |
| 5.16.14 | 1         | 0.25%   |
| 5.16.13 | 1         | 0.25%   |
| 5.16.12 | 1         | 0.25%   |
| 5.15.7  | 1         | 0.25%   |
| 5.15.32 | 1         | 0.25%   |
| 5.15.3  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 91        | 23.27%  |
| 5.11    | 52        | 13.3%   |
| 5.8     | 30        | 7.67%   |
| 5.3     | 28        | 7.16%   |
| 5.10    | 26        | 6.65%   |
| 4.15    | 24        | 6.14%   |
| 5.13    | 20        | 5.12%   |
| 4.18    | 19        | 4.86%   |
| 5.16    | 18        | 4.6%    |
| 5.0     | 15        | 3.84%   |
| 5.15    | 14        | 3.58%   |
| 5.9     | 9         | 2.3%    |
| 4.19    | 6         | 1.53%   |
| 5.6     | 5         | 1.28%   |
| 5.17    | 5         | 1.28%   |
| 5.12    | 5         | 1.28%   |
| 4.9     | 5         | 1.28%   |
| 5.14    | 4         | 1.02%   |
| 5.7     | 3         | 0.77%   |
| 5.5     | 2         | 0.51%   |
| 4.16    | 2         | 0.51%   |
| 5.2     | 1         | 0.26%   |
| 5.1     | 1         | 0.26%   |
| 4.17    | 1         | 0.26%   |
| 4.14    | 1         | 0.26%   |
| 4.13    | 1         | 0.26%   |
| 4.12    | 1         | 0.26%   |
| 4.1     | 1         | 0.26%   |
| 3.10    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 338       | 97.69%  |
| i686    | 6         | 1.73%   |
| armv7l  | 1         | 0.29%   |
| aarch64 | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 168       | 46.28%  |
| Unknown         | 57        | 15.7%   |
| KDE5            | 49        | 13.5%   |
| X-Cinnamon      | 17        | 4.68%   |
| XFCE            | 13        | 3.58%   |
| MATE            | 10        | 2.75%   |
| KDE             | 10        | 2.75%   |
| Cinnamon        | 9         | 2.48%   |
| Unity           | 4         | 1.1%    |
| Pantheon        | 4         | 1.1%    |
| GNOME Flashback | 4         | 1.1%    |
| DWM             | 4         | 1.1%    |
| Budgie          | 4         | 1.1%    |
| KDE4            | 3         | 0.83%   |
| LXQt            | 2         | 0.55%   |
| openbox         | 1         | 0.28%   |
| LXDE            | 1         | 0.28%   |
| i3              | 1         | 0.28%   |
| Deepin          | 1         | 0.28%   |
| bspwm           | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 292       | 80.44%  |
| Unknown | 37        | 10.19%  |
| Wayland | 29        | 7.99%   |
| Tty     | 5         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 53.09%  |
| GDM     | 59        | 16.57%  |
| SDDM    | 47        | 13.2%   |
| LightDM | 27        | 7.58%   |
| GDM3    | 17        | 4.78%   |
| TDM     | 14        | 3.93%   |
| KDM     | 2         | 0.56%   |
| Ly      | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 179       | 50%     |
| hr_HR   | 91        | 25.42%  |
| Unknown | 59        | 16.48%  |
| en_GB   | 14        | 3.91%   |
| C       | 6         | 1.68%   |
| de_DE   | 5         | 1.4%    |
| ru_RU   | 1         | 0.28%   |
| hr_BA   | 1         | 0.28%   |
| fr_FR   | 1         | 0.28%   |
| en_DE   | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 192       | 54.08%  |
| BIOS | 163       | 45.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 285       | 79.83%  |
| Overlay | 25        | 7%      |
| Unknown | 20        | 5.6%    |
| Btrfs   | 12        | 3.36%   |
| Zfs     | 6         | 1.68%   |
| Xfs     | 5         | 1.4%    |
| Ext2    | 2         | 0.56%   |
| Jfs     | 1         | 0.28%   |
| F2fs    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 201       | 57.59%  |
| GPT     | 113       | 32.38%  |
| MBR     | 35        | 10.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 313       | 88.67%  |
| Yes       | 40        | 11.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 253       | 71.67%  |
| Yes       | 100       | 28.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 61        | 17.63%  |
| ASUSTek Computer                             | 56        | 16.18%  |
| Hewlett-Packard                              | 53        | 15.32%  |
| Acer                                         | 38        | 10.98%  |
| ASRock                                       | 31        | 8.96%   |
| Dell                                         | 29        | 8.38%   |
| Gigabyte Technology                          | 22        | 6.36%   |
| MSI                                          | 9         | 2.6%    |
| Toshiba                                      | 6         | 1.73%   |
| Apple                                        | 6         | 1.73%   |
| Pegatron                                     | 5         | 1.45%   |
| Intel                                        | 5         | 1.45%   |
| Fujitsu Siemens                              | 3         | 0.87%   |
| ECS                                          | 3         | 0.87%   |
| Samsung Electronics                          | 2         | 0.58%   |
| HUAWEI                                       | 2         | 0.58%   |
| eMachines                                    | 2         | 0.58%   |
| TUXEDO                                       | 1         | 0.29%   |
| System76                                     | 1         | 0.29%   |
| SHENZHEN X&F TECHNOLOGY                      | 1         | 0.29%   |
| Razer                                        | 1         | 0.29%   |
| Raspberry Pi Foundation                      | 1         | 0.29%   |
| Nvidia                                       | 1         | 0.29%   |
| Notebook                                     | 1         | 0.29%   |
| Medion                                       | 1         | 0.29%   |
| Foxconn                                      | 1         | 0.29%   |
| CHUWI Innovation And Technology(ShenZhen)c0. | 1         | 0.29%   |
| AMI                                          | 1         | 0.29%   |
| ABIT                                         | 1         | 0.29%   |
| Unknown                                      | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.16%   |
| Acer Aspire A315-21                        | 4         | 1.16%   |
| Lenovo G710 20252                          | 3         | 0.87%   |
| ASUS PRIME A320M-K                         | 3         | 0.87%   |
| Acer Aspire A515-51G                       | 3         | 0.87%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.58%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.58%   |
| HP ProBook 450 G7                          | 2         | 0.58%   |
| HP EliteBook 850 G6                        | 2         | 0.58%   |
| HP 2000                                    | 2         | 0.58%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.58%   |
| Dell XPS 13 9310                           | 2         | 0.58%   |
| ASUS X751NV                                | 2         | 0.58%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.58%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.58%   |
| ASUS P8H77-V LE                            | 2         | 0.58%   |
| ASUS M5A78L LE                             | 2         | 0.58%   |
| ASRock H61M-DGS                            | 2         | 0.58%   |
| ASRock B450M-HDV R4.0                      | 2         | 0.58%   |
| Acer Aspire A715-72G                       | 2         | 0.58%   |
| Acer Aspire 7739G                          | 2         | 0.58%   |
| Unknown                                    | 2         | 0.58%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.29%   |
| Toshiba Satellite P200                     | 1         | 0.29%   |
| Toshiba Satellite L750                     | 1         | 0.29%   |
| Toshiba Satellite L50-B                    | 1         | 0.29%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.29%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.29%   |
| Toshiba Satellite A300                     | 1         | 0.29%   |
| System76 Oryx Pro                          | 1         | 0.29%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.29%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.29%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.29%   |
| Razer Blade                                | 1         | 0.29%   |
| RPi Raspberry Pi                           | 1         | 0.29%   |
| Pegatron Pro 3010 Small Form Factor PC     | 1         | 0.29%   |
| Pegatron HPE-520ad                         | 1         | 0.29%   |
| Pegatron G5261de                           | 1         | 0.29%   |
| Pegatron Compaq dx2400 Microtower PC       | 1         | 0.29%   |
| Pegatron 27-1001eu                         | 1         | 0.29%   |
| Nvidia Tegra                               | 1         | 0.29%   |
| Notebook MAM2080                           | 1         | 0.29%   |
| MSI MS-7C02                                | 1         | 0.29%   |
| MSI MS-7B98                                | 1         | 0.29%   |
| MSI MS-7B84                                | 1         | 0.29%   |
| MSI MS-7B07                                | 1         | 0.29%   |
| MSI MS-7850                                | 1         | 0.29%   |
| MSI MS-7817                                | 1         | 0.29%   |
| MSI MS-7681                                | 1         | 0.29%   |
| MSI MS-7586                                | 1         | 0.29%   |
| MSI MS-7360                                | 1         | 0.29%   |
| Medion P6618                               | 1         | 0.29%   |
| Lenovo Z50-70 20354                        | 1         | 0.29%   |
| Lenovo Yoga 910-13IKB 80VF                 | 1         | 0.29%   |
| Lenovo Yoga 7 14ACN6 82N7                  | 1         | 0.29%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.29%   |
| Lenovo Y50-70 20378                        | 1         | 0.29%   |
| Lenovo V340-17IWL 81RG                     | 1         | 0.29%   |
| Lenovo ThinkPad X260 20F5S0JF00            | 1         | 0.29%   |
| Lenovo ThinkPad X240 20AMS30A01            | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 32        | 9.25%   |
| Lenovo ThinkPad               | 24        | 6.94%   |
| HP ProBook                    | 10        | 2.89%   |
| HP EliteBook                  | 10        | 2.89%   |
| Dell Vostro                   | 9         | 2.6%    |
| ASUS VivoBook                 | 8         | 2.31%   |
| Lenovo IdeaPad                | 7         | 2.02%   |
| Toshiba Satellite             | 6         | 1.73%   |
| HP Pavilion                   | 6         | 1.73%   |
| Dell XPS                      | 6         | 1.73%   |
| ASUS PRIME                    | 6         | 1.73%   |
| Lenovo ThinkBook              | 5         | 1.45%   |
| Lenovo Legion                 | 5         | 1.45%   |
| Dell Latitude                 | 5         | 1.45%   |
| HP Laptop                     | 4         | 1.16%   |
| HP Compaq                     | 4         | 1.16%   |
| Dell Inspiron                 | 4         | 1.16%   |
| ASUS TUF                      | 4         | 1.16%   |
| ASUS ROG                      | 4         | 1.16%   |
| ASUS All                      | 4         | 1.16%   |
| Lenovo IdeaCentre             | 3         | 0.87%   |
| Lenovo G710                   | 3         | 0.87%   |
| HP 250                        | 3         | 0.87%   |
| Acer Swift                    | 3         | 0.87%   |
| Lenovo Yoga                   | 2         | 0.58%   |
| Lenovo B590                   | 2         | 0.58%   |
| HP ProDesk                    | 2         | 0.58%   |
| HP OMEN                       | 2         | 0.58%   |
| HP 2000                       | 2         | 0.58%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.58%   |
| Dell OptiPlex                 | 2         | 0.58%   |
| ASUS ZenBook                  | 2         | 0.58%   |
| ASUS X751NV                   | 2         | 0.58%   |
| ASUS P8H77-V                  | 2         | 0.58%   |
| ASUS M5A78L                   | 2         | 0.58%   |
| ASRock H97                    | 2         | 0.58%   |
| ASRock H61M-DGS               | 2         | 0.58%   |
| ASRock B450M-HDV              | 2         | 0.58%   |
| ASRock A320M-HDV              | 2         | 0.58%   |
| Unknown                       | 2         | 0.58%   |
| TUXEDO Pulse                  | 1         | 0.29%   |
| System76 Oryx                 | 1         | 0.29%   |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.29%   |
| Samsung 300E4C                | 1         | 0.29%   |
| Samsung 300E4A                | 1         | 0.29%   |
| Razer Blade                   | 1         | 0.29%   |
| RPi Raspberry                 | 1         | 0.29%   |
| Pegatron Pro                  | 1         | 0.29%   |
| Pegatron HPE-520ad            | 1         | 0.29%   |
| Pegatron G5261de              | 1         | 0.29%   |
| Pegatron Compaq               | 1         | 0.29%   |
| Pegatron 27-1001eu            | 1         | 0.29%   |
| Nvidia Tegra                  | 1         | 0.29%   |
| Notebook MAM2080              | 1         | 0.29%   |
| MSI MS-7C02                   | 1         | 0.29%   |
| MSI MS-7B98                   | 1         | 0.29%   |
| MSI MS-7B84                   | 1         | 0.29%   |
| MSI MS-7B07                   | 1         | 0.29%   |
| MSI MS-7850                   | 1         | 0.29%   |
| MSI MS-7817                   | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 45        | 13.01%  |
| 2017    | 35        | 10.12%  |
| 2019    | 32        | 9.25%   |
| 2013    | 32        | 9.25%   |
| 2011    | 28        | 8.09%   |
| 2020    | 26        | 7.51%   |
| 2021    | 20        | 5.78%   |
| 2016    | 20        | 5.78%   |
| 2012    | 20        | 5.78%   |
| 2014    | 19        | 5.49%   |
| 2015    | 14        | 4.05%   |
| 2009    | 13        | 3.76%   |
| 2007    | 13        | 3.76%   |
| 2008    | 12        | 3.47%   |
| 2010    | 9         | 2.6%    |
| 2006    | 4         | 1.16%   |
| 2005    | 2         | 0.58%   |
| Unknown | 2         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 211       | 60.98%  |
| Desktop        | 119       | 34.39%  |
| All in one     | 7         | 2.02%   |
| Convertible    | 3         | 0.87%   |
| System on chip | 2         | 0.58%   |
| Mini pc        | 2         | 0.58%   |
| Stick pc       | 1         | 0.29%   |
| Server         | 1         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 318       | 91.12%  |
| Enabled  | 31        | 8.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 346       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 97        | 27.48%  |
| 8.01-16.0   | 78        | 22.1%   |
| 16.01-24.0  | 67        | 18.98%  |
| 3.01-4.0    | 57        | 16.15%  |
| 32.01-64.0  | 25        | 7.08%   |
| 1.01-2.0    | 16        | 4.53%   |
| 24.01-32.0  | 5         | 1.42%   |
| 2.01-3.0    | 4         | 1.13%   |
| 64.01-256.0 | 4         | 1.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 150       | 38.27%  |
| 2.01-3.0   | 101       | 25.77%  |
| 4.01-8.0   | 58        | 14.8%   |
| 3.01-4.0   | 43        | 10.97%  |
| 0.51-1.0   | 22        | 5.61%   |
| 8.01-16.0  | 11        | 2.81%   |
| 0.01-0.5   | 4         | 1.02%   |
| 16.01-24.0 | 3         | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 219       | 60.66%  |
| 2       | 92        | 25.48%  |
| 3       | 27        | 7.48%   |
| 5       | 9         | 2.49%   |
| 4       | 6         | 1.66%   |
| 0       | 5         | 1.39%   |
| 7       | 1         | 0.28%   |
| 6       | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 211       | 60.46%  |
| Yes       | 138       | 39.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 309       | 89.05%  |
| No        | 38        | 10.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 75.29%  |
| No        | 86        | 24.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 59.54%  |
| No        | 142       | 40.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Croatia | 346       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Zagreb              | 219       | 56.88%  |
| Split               | 23        | 5.97%   |
| Rijeka              | 13        | 3.38%   |
| Velika Gorica       | 8         | 2.08%   |
| Pula                | 8         | 2.08%   |
| Osijek              | 8         | 2.08%   |
| Samobor             | 7         | 1.82%   |
| Zadar               | 4         | 1.04%   |
| Karlovac            | 4         | 1.04%   |
| Vinkovci            | 3         | 0.78%   |
| VaraЕѕdin         | 3         | 0.78%   |
| Sesvete             | 3         | 0.78%   |
| Koprivnica          | 3         | 0.78%   |
| ДЊakovec          | 2         | 0.52%   |
| Zabok               | 2         | 0.52%   |
| Prelog              | 2         | 0.52%   |
| Opatija             | 2         | 0.52%   |
| Krk                 | 2         | 0.52%   |
| GJurgevac           | 2         | 0.52%   |
| Dubrovnik           | 2         | 0.52%   |
| Bjelovar            | 2         | 0.52%   |
| ZapreЕЎiД‡     | 1         | 0.26%   |
| ZapreÅ¡iÄ‡     | 1         | 0.26%   |
| Vrbovec             | 1         | 0.26%   |
| Vodnjan             | 1         | 0.26%   |
| Virovitica          | 1         | 0.26%   |
| Vele Mune           | 1         | 0.26%   |
| Varazdinske Toplice | 1         | 0.26%   |
| VaraÅ¾din         | 1         | 0.26%   |
| Trogir              | 1         | 0.26%   |
| Trenkovo            | 1         | 0.26%   |
| Supetar             | 1         | 0.26%   |
| Suhopolje           | 1         | 0.26%   |
| Strmec Samoborski   | 1         | 0.26%   |
| Stefanec            | 1         | 0.26%   |
| Slavonski Brod      | 1         | 0.26%   |
| Sisak               | 1         | 0.26%   |
| Sinj                | 1         | 0.26%   |
| Raslina             | 1         | 0.26%   |
| Pregrada            | 1         | 0.26%   |
| Povljana            | 1         | 0.26%   |
| Postira             | 1         | 0.26%   |
| PoreДЌ            | 1         | 0.26%   |
| PoÅ¾ega           | 1         | 0.26%   |
| Opuzen              | 1         | 0.26%   |
| Novska              | 1         | 0.26%   |
| Novo Selo Rok       | 1         | 0.26%   |
| Novi Marof          | 1         | 0.26%   |
| Nova Raca           | 1         | 0.26%   |
| Nova Gradiska       | 1         | 0.26%   |
| NaÅ¡ice           | 1         | 0.26%   |
| Motovun             | 1         | 0.26%   |
| Mirca               | 1         | 0.26%   |
| Medulin             | 1         | 0.26%   |
| Marusevec           | 1         | 0.26%   |
| Mala Subotica       | 1         | 0.26%   |
| Kutina              | 1         | 0.26%   |
| Krizevci            | 1         | 0.26%   |
| Krapina             | 1         | 0.26%   |
| KorДЌula          | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 93        | 143    | 19.1%   |
| Samsung Electronics   | 71        | 99     | 14.58%  |
| Kingston              | 49        | 68     | 10.06%  |
| Seagate               | 43        | 79     | 8.83%   |
| Toshiba               | 37        | 44     | 7.6%    |
| SK Hynix              | 22        | 32     | 4.52%   |
| Crucial               | 21        | 29     | 4.31%   |
| SanDisk               | 17        | 23     | 3.49%   |
| Intel                 | 15        | 22     | 3.08%   |
| Micron Technology     | 12        | 13     | 2.46%   |
| Hitachi               | 12        | 12     | 2.46%   |
| A-DATA Technology     | 12        | 14     | 2.46%   |
| Unknown               | 10        | 13     | 2.05%   |
| HGST                  | 9         | 9      | 1.85%   |
| Apple                 | 6         | 6      | 1.23%   |
| Patriot               | 5         | 8      | 1.03%   |
| Transcend             | 4         | 5      | 0.82%   |
| Silicon Motion        | 4         | 7      | 0.82%   |
| Fujitsu               | 4         | 4      | 0.82%   |
| Netac                 | 3         | 3      | 0.62%   |
| Corsair               | 3         | 3      | 0.62%   |
| StoreJet              | 2         | 2      | 0.41%   |
| Phison                | 2         | 2      | 0.41%   |
| OCZ                   | 2         | 3      | 0.41%   |
| MAXTOR                | 2         | 2      | 0.41%   |
| LITEON                | 2         | 3      | 0.41%   |
| KingFast              | 2         | 4      | 0.41%   |
| Intenso               | 2         | 3      | 0.41%   |
| Gigabyte Technology   | 2         | 2      | 0.41%   |
| AMD                   | 2         | 5      | 0.41%   |
| XPG                   | 1         | 3      | 0.21%   |
| Verbatim              | 1         | 1      | 0.21%   |
| UMIS                  | 1         | 1      | 0.21%   |
| Ugreen                | 1         | 1      | 0.21%   |
| TO Exter              | 1         | 1      | 0.21%   |
| Realtek Semiconductor | 1         | 3      | 0.21%   |
| Mushkin               | 1         | 1      | 0.21%   |
| Mass                  | 1         | 1      | 0.21%   |
| Lite-On               | 1         | 1      | 0.21%   |
| Lenovo                | 1         | 2      | 0.21%   |
| LaCie                 | 1         | 1      | 0.21%   |
| KingSpec              | 1         | 1      | 0.21%   |
| Kingmax               | 1         | 1      | 0.21%   |
| HPE                   | 1         | 2      | 0.21%   |
| GOODRAM               | 1         | 1      | 0.21%   |
| External              | 1         | 1      | 0.21%   |
| ASMedia               | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD         | 8         | 1.53%   |
| Samsung SSD 850 EVO 250GB               | 7         | 1.34%   |
| Kingston SA400S37240G 240GB SSD         | 7         | 1.34%   |
| Samsung NVMe SSD Drive 512GB            | 6         | 1.15%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 1.15%   |
| Kingston SA400S37120G 120GB SSD         | 6         | 1.15%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 0.96%   |
| Sandisk NVMe SSD Drive 512GB            | 5         | 0.96%   |
| Crucial CT240BX500SSD1 240GB            | 5         | 0.96%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 4         | 0.77%   |
| Toshiba HDWD130 3TB                     | 4         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 0.77%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 0.77%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.77%   |
| A-DATA SU650 240GB SSD                  | 4         | 0.77%   |
| WDC WD5000AAKX-001CA0 500GB             | 3         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.57%   |
| Toshiba HDWD110 1TB                     | 3         | 0.57%   |
| Toshiba DT01ACA100 1TB                  | 3         | 0.57%   |
| SK Hynix NVMe SSD Drive 512GB           | 3         | 0.57%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.57%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.57%   |
| Samsung HD103SI 1TB                     | 3         | 0.57%   |
| Patriot Burst 240GB SSD                 | 3         | 0.57%   |
| Intel SSDSC2BW120A4 120GB               | 3         | 0.57%   |
| A-DATA SU650 120GB SSD                  | 3         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.38%   |
| WDC WD6400AAKS-22A7B0 640GB             | 2         | 0.38%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 2         | 0.38%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2         | 0.38%   |
| WDC WD3200AAKS-00L9A0 320GB             | 2         | 0.38%   |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 0.38%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 0.38%   |
| WDC WD1600AAJS-07M0A0 160GB             | 2         | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.38%   |
| WDC WD10EZEX-08M2NA0 1TB                | 2         | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.38%   |
| Unknown MMC Card  64GB                  | 2         | 0.38%   |
| Unknown MMC Card  32GB                  | 2         | 0.38%   |
| Unknown MMC Card  128GB                 | 2         | 0.38%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.38%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.38%   |
| Toshiba HDWD120 2TB                     | 2         | 0.38%   |
| StoreJet Transcend 480GB SSD            | 2         | 0.38%   |
| SK Hynix SH920 2.5 7MM 256GB SSD        | 2         | 0.38%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.38%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.38%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.38%   |
| Silicon Motion NVMe SSD Drive 1024GB    | 2         | 0.38%   |
| Seagate ST31000524AS 1TB                | 2         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.38%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.38%   |
| Samsung SSD 870 QVO 1TB                 | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 79        | 119    | 41.58%  |
| Seagate             | 43        | 67     | 22.63%  |
| Toshiba             | 30        | 37     | 15.79%  |
| Hitachi             | 12        | 12     | 6.32%   |
| HGST                | 9         | 9      | 4.74%   |
| Samsung Electronics | 8         | 11     | 4.21%   |
| Fujitsu             | 4         | 4      | 2.11%   |
| Unknown             | 2         | 2      | 1.05%   |
| MAXTOR              | 2         | 2      | 1.05%   |
| Intenso             | 1         | 2      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 45        | 58     | 25.14%  |
| Samsung Electronics | 28        | 43     | 15.64%  |
| Crucial             | 20        | 27     | 11.17%  |
| A-DATA Technology   | 11        | 13     | 6.15%   |
| Micron Technology   | 10        | 11     | 5.59%   |
| SanDisk             | 9         | 14     | 5.03%   |
| Intel               | 8         | 10     | 4.47%   |
| WDC                 | 7         | 7      | 3.91%   |
| SK Hynix            | 7         | 12     | 3.91%   |
| Apple               | 5         | 5      | 2.79%   |
| Patriot             | 4         | 7      | 2.23%   |
| Transcend           | 3         | 4      | 1.68%   |
| Toshiba             | 2         | 2      | 1.12%   |
| StoreJet            | 2         | 2      | 1.12%   |
| OCZ                 | 2         | 3      | 1.12%   |
| Netac               | 2         | 2      | 1.12%   |
| Gigabyte Technology | 2         | 2      | 1.12%   |
| AMD                 | 2         | 5      | 1.12%   |
| TO Exter            | 1         | 1      | 0.56%   |
| Mushkin             | 1         | 1      | 0.56%   |
| LITEON              | 1         | 2      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| Kingmax             | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| External            | 1         | 1      | 0.56%   |
| Corsair             | 1         | 1      | 0.56%   |
| ASMedia             | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 168       | 265    | 37.92%  |
| SSD     | 157       | 238    | 35.44%  |
| NVMe    | 102       | 149    | 23.02%  |
| Unknown | 9         | 23     | 2.03%   |
| MMC     | 7         | 10     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 258       | 491    | 67.36%  |
| NVMe | 102       | 149    | 26.63%  |
| SAS  | 16        | 35     | 4.18%   |
| MMC  | 7         | 10     | 1.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 203       | 316    | 60.96%  |
| 0.51-1.0   | 94        | 129    | 28.23%  |
| 1.01-2.0   | 20        | 31     | 6.01%   |
| 2.01-3.0   | 10        | 20     | 3%      |
| 3.01-4.0   | 5         | 6      | 1.5%    |
| 4.01-10.0  | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 111       | 30.16%  |
| 251-500        | 79        | 21.47%  |
| 501-1000       | 55        | 14.95%  |
| 1001-2000      | 37        | 10.05%  |
| 51-100         | 24        | 6.52%   |
| 1-20           | 21        | 5.71%   |
| More than 3000 | 13        | 3.53%   |
| 21-50          | 12        | 3.26%   |
| Unknown        | 11        | 2.99%   |
| 2001-3000      | 5         | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 145       | 36.9%   |
| 21-50          | 75        | 19.08%  |
| 51-100         | 44        | 11.2%   |
| 101-250        | 38        | 9.67%   |
| 501-1000       | 31        | 7.89%   |
| 251-500        | 29        | 7.38%   |
| 1001-2000      | 11        | 2.8%    |
| Unknown        | 11        | 2.8%    |
| 2001-3000      | 6         | 1.53%   |
| More than 3000 | 3         | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 3.33%   |
| WDC WD6400AAKS-07A7B0 640GB         | 1         | 1      | 3.33%   |
| WDC WD600VE-75HDT0 64GB             | 1         | 1      | 3.33%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 1      | 3.33%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1         | 1      | 3.33%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 1      | 3.33%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 3.33%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1         | 1      | 3.33%   |
| Transcend TS480GSSD220S 480GB       | 1         | 1      | 3.33%   |
| Toshiba MK6459GSXP 640GB            | 1         | 1      | 3.33%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 3.33%   |
| SK Hynix SH920 2.5 7MM 256GB SSD    | 1         | 1      | 3.33%   |
| Seagate ST9250827AS 250GB           | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 3.33%   |
| Seagate ST31500341AS 1TB            | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 3.33%   |
| SanDisk SDSSDXPS960G 960GB          | 1         | 1      | 3.33%   |
| SanDisk SDSSDA240G 240GB            | 1         | 1      | 3.33%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD | 1         | 1      | 3.33%   |
| Intel SSDSC2KF256H6 SATA 256GB      | 1         | 1      | 3.33%   |
| Intel SSDSC2BW120A4 120GB           | 1         | 1      | 3.33%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 3.33%   |
| Hitachi HDS723020BLA642 2TB         | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 3.33%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 3.33%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 3.33%   |
| Crucial CT525MX300SSD1 528GB        | 1         | 1      | 3.33%   |
| Crucial CT120BX500SSD1 120GB        | 1         | 1      | 3.33%   |
| Crucial CT1024M550SSD1 1024GB       | 1         | 1      | 3.33%   |
| A-DATA Technology SU630 240GB SSD   | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 8         | 8      | 27.59%  |
| Seagate           | 4         | 4      | 13.79%  |
| HGST              | 3         | 3      | 10.34%  |
| Crucial           | 3         | 3      | 10.34%  |
| Toshiba           | 2         | 2      | 6.9%    |
| SanDisk           | 2         | 3      | 6.9%    |
| Intel             | 2         | 2      | 6.9%    |
| Hitachi           | 2         | 2      | 6.9%    |
| Transcend         | 1         | 1      | 3.45%   |
| SK Hynix          | 1         | 1      | 3.45%   |
| A-DATA Technology | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 38.89%  |
| Seagate | 4         | 4      | 22.22%  |
| HGST    | 3         | 3      | 16.67%  |
| Toshiba | 2         | 2      | 11.11%  |
| Hitachi | 2         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 64.29%  |
| SSD  | 10        | 12     | 35.71%  |

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
| Detected | 219       | 438    | 59.03%  |
| Works    | 127       | 217    | 34.23%  |
| Malfunc  | 25        | 30     | 6.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 234       | 54.04%  |
| AMD                              | 73        | 16.86%  |
| Samsung Electronics              | 40        | 9.24%   |
| Sandisk                          | 16        | 3.7%    |
| SK Hynix                         | 15        | 3.46%   |
| Toshiba America Info Systems     | 6         | 1.39%   |
| Kingston Technology Company      | 6         | 1.39%   |
| Phison Electronics               | 5         | 1.15%   |
| JMicron Technology               | 5         | 1.15%   |
| Silicon Motion                   | 4         | 0.92%   |
| Nvidia                           | 4         | 0.92%   |
| Marvell Technology Group         | 4         | 0.92%   |
| ASMedia Technology               | 3         | 0.69%   |
| VIA Technologies                 | 2         | 0.46%   |
| Silicon Integrated Systems [SiS] | 2         | 0.46%   |
| Micron Technology                | 2         | 0.46%   |
| Lite-On Technology               | 2         | 0.46%   |
| ADATA Technology                 | 2         | 0.46%   |
| Union Memory (Shenzhen)          | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| Micron/Crucial Technology        | 1         | 0.23%   |
| LSI Logic / Symbios Logic        | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| KIOXIA                           | 1         | 0.23%   |
| Broadcom / LSI                   | 1         | 0.23%   |
| Adaptec                          | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54        | 10.63%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 28        | 5.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26        | 5.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16        | 3.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 2.95%   |
| Samsung NVMe SSD Controller 980                                                         | 13        | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8         | 1.57%   |
| AMD FCH SATA Controller D                                                               | 8         | 1.57%   |
| SK Hynix Gold P31 SSD                                                                   | 7         | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.18%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 5         | 0.98%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5         | 0.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 0.98%   |
| Intel SSD 600P Series                                                                   | 4         | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4         | 0.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.79%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 0.79%   |
| AMD FCH IDE Controller                                                                  | 4         | 0.79%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.59%   |
| SK Hynix BC511                                                                          | 3         | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.59%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3         | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 3         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.59%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.39%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.39%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.39%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 262       | 58.48%  |
| NVMe | 104       | 23.21%  |
| IDE  | 64        | 14.29%  |
| RAID | 17        | 3.79%   |
| SAS  | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 255       | 73.7%   |
| AMD    | 89        | 25.72%  |
| ARM    | 2         | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 2.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 2.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.43%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 1.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 4         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.15%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.15%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 1.15%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.86%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.86%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.86%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.86%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 0.86%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.86%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 0.57%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.57%   |
| Intel Pentium 4 CPU 3.00GHz                   | 2         | 0.57%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.57%   |
| Intel Core i7-4771 CPU @ 3.50GHz              | 2         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.57%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.57%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.57%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.57%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.57%   |
| Intel Core i5-2300 CPU @ 2.80GHz              | 2         | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.57%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.57%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.57%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.57%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.57%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.57%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.57%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 2         | 0.57%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 2         | 0.57%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 2         | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.57%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.57%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 84        | 24.07%  |
| Intel Core i7           | 53        | 15.19%  |
| Intel Core i3           | 35        | 10.03%  |
| AMD Ryzen 5             | 23        | 6.59%   |
| Intel Core 2 Duo        | 19        | 5.44%   |
| Intel Pentium           | 17        | 4.87%   |
| AMD Ryzen 7             | 14        | 4.01%   |
| Other                   | 10        | 2.87%   |
| AMD Ryzen 3             | 8         | 2.29%   |
| Intel Celeron           | 7         | 2.01%   |
| Intel Pentium Dual      | 5         | 1.43%   |
| Intel Core i9           | 5         | 1.43%   |
| AMD Ryzen 9             | 5         | 1.43%   |
| AMD FX                  | 5         | 1.43%   |
| AMD A6                  | 5         | 1.43%   |
| Intel Pentium Silver    | 4         | 1.15%   |
| Intel Pentium Dual-Core | 4         | 1.15%   |
| Intel Atom              | 4         | 1.15%   |
| AMD Athlon II X4        | 4         | 1.15%   |
| Intel Xeon              | 3         | 0.86%   |
| AMD Phenom II X4        | 3         | 0.86%   |
| AMD E                   | 3         | 0.86%   |
| AMD Athlon X4           | 3         | 0.86%   |
| Intel Pentium M         | 2         | 0.57%   |
| Intel Pentium 4         | 2         | 0.57%   |
| Intel Core 2 Quad       | 2         | 0.57%   |
| Intel Core 2            | 2         | 0.57%   |
| AMD E1                  | 2         | 0.57%   |
| AMD Athlon 64 X2        | 2         | 0.57%   |
| AMD A8                  | 2         | 0.57%   |
| Intel Xeon Bronze       | 1         | 0.29%   |
| Intel Celeron M         | 1         | 0.29%   |
| ARM BCM                 | 1         | 0.29%   |
| AMD Turion 64 X2 Mobile | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen 7 PRO         | 1         | 0.29%   |
| AMD Ryzen 3 PRO         | 1         | 0.29%   |
| AMD Phenom II X6        | 1         | 0.29%   |
| AMD Phenom II X2        | 1         | 0.29%   |
| AMD Athlon 64           | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |
| AMD A4                  | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 145       | 41.55%  |
| 4      | 135       | 38.68%  |
| 6      | 30        | 8.6%    |
| 8      | 23        | 6.59%   |
| 1      | 8         | 2.29%   |
| 12     | 3         | 0.86%   |
| 3      | 2         | 0.57%   |
| 24     | 1         | 0.29%   |
| 16     | 1         | 0.29%   |
| 10     | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 345       | 99.71%  |
| 2      | 1         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 218       | 62.82%  |
| 1      | 129       | 37.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 331       | 95.11%  |
| Unknown        | 13        | 3.74%   |
| 32-bit         | 4         | 1.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 17.91%  |
| 0x306c3    | 30        | 8.26%   |
| 0x206a7    | 17        | 4.68%   |
| 0x906ea    | 15        | 4.13%   |
| 0x806ea    | 14        | 3.86%   |
| 0x306a9    | 14        | 3.86%   |
| 0x806e9    | 13        | 3.58%   |
| 0x6fd      | 11        | 3.03%   |
| 0x1067a    | 11        | 3.03%   |
| 0x806ec    | 10        | 2.75%   |
| 0x40651    | 8         | 2.2%    |
| 0x0a50000c | 7         | 1.93%   |
| 0x08600106 | 6         | 1.65%   |
| 0x0810100b | 6         | 1.65%   |
| 0xa0653    | 5         | 1.38%   |
| 0x306d4    | 5         | 1.38%   |
| 0x30678    | 5         | 1.38%   |
| 0x08108109 | 5         | 1.38%   |
| 0x0800820d | 5         | 1.38%   |
| 0x06006705 | 5         | 1.38%   |
| 0x906ed    | 4         | 1.1%    |
| 0x906e9    | 4         | 1.1%    |
| 0x806c1    | 4         | 1.1%    |
| 0x6fb      | 4         | 1.1%    |
| 0x506c9    | 4         | 1.1%    |
| 0x406e3    | 4         | 1.1%    |
| 0x20655    | 4         | 1.1%    |
| 0x010000db | 4         | 1.1%    |
| 0x010000c8 | 4         | 1.1%    |
| 0x706e5    | 3         | 0.83%   |
| 0x706a1    | 3         | 0.83%   |
| 0x506e3    | 3         | 0.83%   |
| 0x406c4    | 3         | 0.83%   |
| 0x08608103 | 3         | 0.83%   |
| 0x08600103 | 3         | 0.83%   |
| 0x06001119 | 3         | 0.83%   |
| 0x05000119 | 3         | 0.83%   |
| 0xf43      | 2         | 0.55%   |
| 0xa0655    | 2         | 0.55%   |
| 0x906eb    | 2         | 0.55%   |
| 0x806eb    | 2         | 0.55%   |
| 0x6d8      | 2         | 0.55%   |
| 0x306f2    | 2         | 0.55%   |
| 0x10676    | 2         | 0.55%   |
| 0x08600104 | 2         | 0.55%   |
| 0x08108102 | 2         | 0.55%   |
| 0x08001137 | 2         | 0.55%   |
| 0x06000852 | 2         | 0.55%   |
| 0x0600063e | 2         | 0.55%   |
| 0xa0671    | 1         | 0.28%   |
| 0xa0652    | 1         | 0.28%   |
| 0x906c0    | 1         | 0.28%   |
| 0x6fa      | 1         | 0.28%   |
| 0x6f6      | 1         | 0.28%   |
| 0x6e8      | 1         | 0.28%   |
| 0x50654    | 1         | 0.28%   |
| 0x40661    | 1         | 0.28%   |
| 0x106c2    | 1         | 0.28%   |
| 0x106a4    | 1         | 0.28%   |
| 0x0a201009 | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 72        | 20.81%  |
| Haswell       | 45        | 13.01%  |
| SandyBridge   | 19        | 5.49%   |
| IvyBridge     | 19        | 5.49%   |
| Core          | 18        | 5.2%    |
| Zen 2         | 14        | 4.05%   |
| Penryn        | 14        | 4.05%   |
| Zen+          | 13        | 3.76%   |
| Zen           | 12        | 3.47%   |
| Skylake       | 11        | 3.18%   |
| Zen 3         | 10        | 2.89%   |
| Silvermont    | 10        | 2.89%   |
| CometLake     | 9         | 2.6%    |
| Piledriver    | 8         | 2.31%   |
| K10           | 8         | 2.31%   |
| Excavator     | 7         | 2.02%   |
| Unknown       | 7         | 2.02%   |
| Westmere      | 6         | 1.73%   |
| TigerLake     | 6         | 1.73%   |
| Broadwell     | 6         | 1.73%   |
| K8 Hammer     | 4         | 1.16%   |
| IceLake       | 4         | 1.16%   |
| Goldmont plus | 4         | 1.16%   |
| Goldmont      | 4         | 1.16%   |
| Bobcat        | 4         | 1.16%   |
| P6            | 3         | 0.87%   |
| NetBurst      | 2         | 0.58%   |
| Bulldozer     | 2         | 0.58%   |
| Tremont       | 1         | 0.29%   |
| Puma          | 1         | 0.29%   |
| Nehalem       | 1         | 0.29%   |
| Jaguar        | 1         | 0.29%   |
| Bonnell       | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 44.44%  |
| Nvidia                           | 123       | 28.47%  |
| AMD                              | 112       | 25.93%  |
| Silicon Integrated Systems [SiS] | 2         | 0.46%   |
| VIA Technologies                 | 1         | 0.23%   |
| Matrox Electronics Systems       | 1         | 0.23%   |
| ATI Technologies                 | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 17        | 3.85%   |
| Intel HD Graphics 620                                                                    | 14        | 3.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.49%   |
| AMD Renoir                                                                               | 11        | 2.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 1.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.36%   |
| AMD Cezanne                                                                              | 6         | 1.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.13%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.13%   |
| AMD Lucienne                                                                             | 5         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.91%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.91%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 0.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.91%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.68%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.68%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.68%   |
| Intel HD Graphics 630                                                                    | 3         | 0.68%   |
| Intel HD Graphics 530                                                                    | 3         | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.68%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.68%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 0.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.45%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.45%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.45%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.45%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2         | 0.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 116       | 33.24%  |
| 1 x AMD        | 82        | 23.5%   |
| 1 x Nvidia     | 59        | 16.91%  |
| Intel + Nvidia | 56        | 16.05%  |
| Intel + AMD    | 16        | 4.58%   |
| AMD + Nvidia   | 8         | 2.29%   |
| 2 x AMD        | 6         | 1.72%   |
| Other          | 2         | 0.57%   |
| 1 x SiS        | 2         | 0.57%   |
| 1 x VIA        | 1         | 0.29%   |
| 1 x Matrox     | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 267       | 76.29%  |
| Proprietary | 71        | 20.29%  |
| Unknown     | 12        | 3.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 47.35%  |
| 1.01-2.0   | 60        | 16.71%  |
| 0.51-1.0   | 38        | 10.58%  |
| 3.01-4.0   | 37        | 10.31%  |
| 0.01-0.5   | 35        | 9.75%   |
| 7.01-8.0   | 12        | 3.34%   |
| 5.01-6.0   | 3         | 0.84%   |
| 2.01-3.0   | 3         | 0.84%   |
| 8.01-16.0  | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 56        | 14.36%  |
| LG Display              | 41        | 10.51%  |
| AU Optronics            | 39        | 10%     |
| Dell                    | 37        | 9.49%   |
| BOE                     | 36        | 9.23%   |
| Chimei Innolux          | 35        | 8.97%   |
| AOC                     | 20        | 5.13%   |
| Goldstar                | 17        | 4.36%   |
| Philips                 | 14        | 3.59%   |
| Acer                    | 13        | 3.33%   |
| Hewlett-Packard         | 9         | 2.31%   |
| Lenovo                  | 8         | 2.05%   |
| Ancor Communications    | 8         | 2.05%   |
| Sharp                   | 7         | 1.79%   |
| Apple                   | 6         | 1.54%   |
| Chi Mei Optoelectronics | 4         | 1.03%   |
| PANDA                   | 3         | 0.77%   |
| LG Philips              | 3         | 0.77%   |
| Fujitsu Siemens         | 3         | 0.77%   |
| CSO                     | 3         | 0.77%   |
| BenQ                    | 3         | 0.77%   |
| Unknown                 | 2         | 0.51%   |
| Quanta Display          | 2         | 0.51%   |
| Panasonic               | 2         | 0.51%   |
| LG Electronics          | 2         | 0.51%   |
| Vestel Elektronik       | 1         | 0.26%   |
| Sony                    | 1         | 0.26%   |
| RTK                     | 1         | 0.26%   |
| NOA VISION              | 1         | 0.26%   |
| NEC Computers           | 1         | 0.26%   |
| NCS                     | 1         | 0.26%   |
| MSI                     | 1         | 0.26%   |
| KTC                     | 1         | 0.26%   |
| InnoLux Display         | 1         | 0.26%   |
| InfoVision              | 1         | 0.26%   |
| Iiyama                  | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| Huion                   | 1         | 0.26%   |
| Grundig                 | 1         | 0.26%   |
| BOE Technology Group    | 1         | 0.26%   |
| ASUSTek Computer        | 1         | 0.26%   |
| Achieva Shimian         | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.23%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 0.99%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 0.99%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 0.74%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 0.74%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.74%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 3         | 0.74%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                         | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.74%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.49%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch      | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                         | 2         | 0.49%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.49%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                        | 2         | 0.49%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.49%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.49%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                       | 2         | 0.49%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                     | 2         | 0.49%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                         | 2         | 0.49%   |
| Dell LCD Monitor SE2416H 5760x1080                                        | 2         | 0.49%   |
| Dell LCD Monitor SE2416H                                                  | 2         | 0.49%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                         | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.49%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 2         | 0.49%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                           | 2         | 0.49%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                            | 2         | 0.49%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                           | 2         | 0.49%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                         | 2         | 0.49%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch      | 1         | 0.25%   |
| Unknown LCD Monitor SAMSUNG                                               | 1         | 0.25%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                               | 1         | 0.25%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                            | 1         | 0.25%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.25%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 0.25%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.25%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch         | 1         | 0.25%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch         | 1         | 0.25%   |
| Samsung Electronics SyncMaster SAM0626 1920x1080                          | 1         | 0.25%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch      | 1         | 0.25%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch      | 1         | 0.25%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch       | 1         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 180       | 48.39%  |
| 1366x768 (WXGA)    | 46        | 12.37%  |
| 1600x900 (HD+)     | 26        | 6.99%   |
| 2560x1440 (QHD)    | 20        | 5.38%   |
| 1680x1050 (WSXGA+) | 16        | 4.3%    |
| 3840x2160 (4K)     | 14        | 3.76%   |
| 1440x900 (WXGA+)   | 10        | 2.69%   |
| 1280x1024 (SXGA)   | 10        | 2.69%   |
| 1920x1200 (WUXGA)  | 9         | 2.42%   |
| Unknown            | 8         | 2.15%   |
| 1280x800 (WXGA)    | 6         | 1.61%   |
| 3840x1080          | 4         | 1.08%   |
| 1360x768           | 4         | 1.08%   |
| 2560x1600          | 3         | 0.81%   |
| 2160x1440          | 3         | 0.81%   |
| 5760x1080          | 2         | 0.54%   |
| 3840x2400          | 2         | 0.54%   |
| 2560x1080          | 2         | 0.54%   |
| 1400x1050          | 2         | 0.54%   |
| 4480x1440          | 1         | 0.27%   |
| 2880x1800          | 1         | 0.27%   |
| 2048x1152          | 1         | 0.27%   |
| 1280x720 (HD)      | 1         | 0.27%   |
| 1024x576           | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 29.05%  |
| 17      | 39        | 10.03%  |
| 23      | 33        | 8.48%   |
| 27      | 31        | 7.97%   |
| 24      | 26        | 6.68%   |
| 13      | 23        | 5.91%   |
| 14      | 21        | 5.4%    |
| 21      | 20        | 5.14%   |
| Unknown | 20        | 5.14%   |
| 22      | 9         | 2.31%   |
| 20      | 9         | 2.31%   |
| 31      | 8         | 2.06%   |
| 19      | 8         | 2.06%   |
| 12      | 5         | 1.29%   |
| 18      | 4         | 1.03%   |
| 26      | 3         | 0.77%   |
| 16      | 3         | 0.77%   |
| 84      | 2         | 0.51%   |
| 54      | 2         | 0.51%   |
| 25      | 2         | 0.51%   |
| 11      | 2         | 0.51%   |
| 72      | 1         | 0.26%   |
| 46      | 1         | 0.26%   |
| 34      | 1         | 0.26%   |
| 33      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| 10      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 37.63%  |
| 501-600     | 82        | 21.58%  |
| 401-500     | 44        | 11.58%  |
| 351-400     | 44        | 11.58%  |
| 201-300     | 24        | 6.32%   |
| Unknown     | 20        | 5.26%   |
| 601-700     | 14        | 3.68%   |
| 701-800     | 3         | 0.79%   |
| 1501-2000   | 3         | 0.79%   |
| 1001-1500   | 3         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 263       | 76.45%  |
| 16/10   | 47        | 13.66%  |
| Unknown | 16        | 4.65%   |
| 5/4     | 9         | 2.62%   |
| 3/2     | 5         | 1.45%   |
| 4/3     | 3         | 0.87%   |
| 21/9    | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 114       | 29.46%  |
| 201-250        | 65        | 16.8%   |
| 301-350        | 34        | 8.79%   |
| 81-90          | 32        | 8.27%   |
| 121-130        | 31        | 8.01%   |
| 151-200        | 28        | 7.24%   |
| Unknown        | 20        | 5.17%   |
| 251-300        | 12        | 3.1%    |
| 71-80          | 11        | 2.84%   |
| 351-500        | 11        | 2.84%   |
| 141-150        | 8         | 2.07%   |
| More than 1000 | 5         | 1.29%   |
| 61-70          | 4         | 1.03%   |
| 131-140        | 4         | 1.03%   |
| 51-60          | 2         | 0.52%   |
| 111-120        | 2         | 0.52%   |
| 91-100         | 2         | 0.52%   |
| 41-50          | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 122       | 32.71%  |
| 121-160       | 118       | 31.64%  |
| 101-120       | 88        | 23.59%  |
| Unknown       | 20        | 5.36%   |
| 161-240       | 15        | 4.02%   |
| 1-50          | 6         | 1.61%   |
| More than 240 | 4         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 275       | 76.6%   |
| 2     | 64        | 17.83%  |
| 0     | 13        | 3.62%   |
| 3     | 5         | 1.39%   |
| 4     | 2         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 213       | 39.66%  |
| Intel                             | 142       | 26.44%  |
| Qualcomm Atheros                  | 72        | 13.41%  |
| Broadcom                          | 26        | 4.84%   |
| MEDIATEK                          | 9         | 1.68%   |
| TP-Link                           | 8         | 1.49%   |
| Qualcomm Atheros Communications   | 7         | 1.3%    |
| Samsung Electronics               | 6         | 1.12%   |
| Ralink                            | 5         | 0.93%   |
| D-Link                            | 5         | 0.93%   |
| Broadcom Limited                  | 5         | 0.93%   |
| Marvell Technology Group          | 4         | 0.74%   |
| Xiaomi                            | 3         | 0.56%   |
| Ralink Technology                 | 3         | 0.56%   |
| Nvidia                            | 3         | 0.56%   |
| ASIX Electronics                  | 3         | 0.56%   |
| VIA Technologies                  | 2         | 0.37%   |
| Sundance Technology Inc / IC Plus | 2         | 0.37%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.37%   |
| Qualcomm                          | 2         | 0.37%   |
| Lenovo                            | 2         | 0.37%   |
| T & A Mobile Phones               | 1         | 0.19%   |
| Nokia Mobile Phones               | 1         | 0.19%   |
| Microsoft                         | 1         | 0.19%   |
| Linksys                           | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| HTC (High Tech Computer)          | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Fibocom                           | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Edimax Technology                 | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Aquantia                          | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 170       | 27.87%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 3.28%   |
| Intel Wireless 8265 / 8275                                              | 18        | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 2.79%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.15%   |
| Intel Wireless 3165                                                     | 7         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.98%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.98%   |
| Intel Wireless 7260                                                     | 6         | 0.98%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.82%   |
| Intel Wireless 7265                                                     | 5         | 0.82%   |
| Intel Wireless 3160                                                     | 5         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 0.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.66%   |
| Intel I211 Gigabit Network Connection                                   | 4         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                    | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.49%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.49%   |
| Intel WiFi Link 5100                                                    | 3         | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.49%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.49%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.33%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.33%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.33%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2         | 0.33%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 42.22%  |
| Qualcomm Atheros                | 59        | 21.85%  |
| Realtek Semiconductor           | 35        | 12.96%  |
| Broadcom                        | 17        | 6.3%    |
| TP-Link                         | 8         | 2.96%   |
| MEDIATEK                        | 8         | 2.96%   |
| Qualcomm Atheros Communications | 7         | 2.59%   |
| Ralink                          | 5         | 1.85%   |
| D-Link                          | 5         | 1.85%   |
| Ralink Technology               | 3         | 1.11%   |
| Qualcomm                        | 2         | 0.74%   |
| Broadcom Limited                | 2         | 0.74%   |
| Microsoft                       | 1         | 0.37%   |
| Linksys                         | 1         | 0.37%   |
| Fibocom                         | 1         | 0.37%   |
| Edimax Technology               | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 7.41%   |
| Intel Wireless 8265 / 8275                                              | 18        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 5.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 2.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.59%   |
| Intel Wireless 3165                                                     | 7         | 2.59%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.22%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.22%   |
| Intel Wireless 7260                                                     | 6         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.85%   |
| Intel Wireless 7265                                                     | 5         | 1.85%   |
| Intel Wireless 3160                                                     | 5         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.11%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.11%   |
| Intel WiFi Link 5100                                                    | 3         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.11%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.11%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.74%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.74%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2         | 0.74%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2         | 0.74%   |
| Intel Wireless 8260                                                     | 2         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.74%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.74%   |
| D-Link WLAN controller                                                  | 2         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.74%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.74%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.37%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 0.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.37%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.37%   |
| Realtek Realtek Network controller                                      | 1         | 0.37%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.37%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.37%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 0.37%   |
| Qualcomm Atheros AR5523                                                 | 1         | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 201       | 60.36%  |
| Intel                             | 64        | 19.22%  |
| Qualcomm Atheros                  | 22        | 6.61%   |
| Broadcom                          | 10        | 3%      |
| Samsung Electronics               | 6         | 1.8%    |
| Marvell Technology Group          | 4         | 1.2%    |
| Xiaomi                            | 3         | 0.9%    |
| Nvidia                            | 3         | 0.9%    |
| Broadcom Limited                  | 3         | 0.9%    |
| ASIX Electronics                  | 3         | 0.9%    |
| VIA Technologies                  | 2         | 0.6%    |
| Sundance Technology Inc / IC Plus | 2         | 0.6%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.6%    |
| Lenovo                            | 2         | 0.6%    |
| T & A Mobile Phones               | 1         | 0.3%    |
| MediaTek                          | 1         | 0.3%    |
| Huawei Technologies               | 1         | 0.3%    |
| HTC (High Tech Computer)          | 1         | 0.3%    |
| D-Link System                     | 1         | 0.3%    |
| Aquantia                          | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 170       | 50.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 17        | 5.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 7         | 2.08%   |
| Intel Ethernet Connection I217-LM                                          | 6         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                                       | 6         | 1.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                     | 5         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 4         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 4         | 1.19%   |
| Intel I211 Gigabit Network Connection                                      | 4         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                       | 4         | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                       | 4         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3         | 0.89%   |
| Intel Ethernet Connection I217-V                                           | 3         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 2         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 2         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.6%    |
| Nvidia MCP61 Ethernet                                                      | 2         | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2         | 0.6%    |
| Lenovo USB-C Dock Ethernet                                                 | 2         | 0.6%    |
| Intel I210 Gigabit Network Connection                                      | 2         | 0.6%    |
| Intel Ethernet Connection I219-LM                                          | 2         | 0.6%    |
| Intel Ethernet Connection I218-LM                                          | 2         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                      | 2         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                       | 2         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                       | 2         | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                                      | 2         | 0.6%    |
| Intel 82579V Gigabit Network Connection                                    | 2         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                   | 2         | 0.6%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                   | 2         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                              | 2         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.3%    |
| T & A Mobile Phones 9010X                                                  | 1         | 0.3%    |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.3%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1         | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1         | 0.3%    |
| Nvidia MCP67 Ethernet                                                      | 1         | 0.3%    |
| MediaTek NOA N2                                                            | 1         | 0.3%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                    | 1         | 0.3%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1         | 0.3%    |
| Intel Ethernet Controller I225-V                                           | 1         | 0.3%    |
| Intel Ethernet Connection (6) I219-LM                                      | 1         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                                      | 1         | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                                      | 1         | 0.3%    |
| Intel Ethernet Connection (3) I218-LM                                      | 1         | 0.3%    |
| Intel Ethernet Connection (13) I219-V                                      | 1         | 0.3%    |
| Intel Ethernet Connection (12) I219-V                                      | 1         | 0.3%    |
| Intel Ethernet Connection (11) I219-V                                      | 1         | 0.3%    |
| Intel Ethernet Connection (11) I219-LM                                     | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 309       | 53.74%  |
| WiFi     | 262       | 45.57%  |
| Modem    | 4         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 53.07%  |
| Ethernet | 198       | 46.7%   |
| Modem    | 1         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 201       | 57.93%  |
| 1     | 138       | 39.77%  |
| 0     | 5         | 1.44%   |
| 4     | 2         | 0.58%   |
| 3     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 336       | 96.83%  |
| Yes  | 11        | 3.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 44.02%  |
| Qualcomm Atheros Communications | 21        | 10.05%  |
| Realtek Semiconductor           | 20        | 9.57%   |
| Lite-On Technology              | 19        | 9.09%   |
| IMC Networks                    | 14        | 6.7%    |
| Broadcom                        | 9         | 4.31%   |
| Foxconn / Hon Hai               | 8         | 3.83%   |
| Cambridge Silicon Radio         | 7         | 3.35%   |
| Hewlett-Packard                 | 5         | 2.39%   |
| Apple                           | 5         | 2.39%   |
| Toshiba                         | 3         | 1.44%   |
| Foxconn International           | 2         | 0.96%   |
| Realtek                         | 1         | 0.48%   |
| Integrated System Solution      | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |
| ASUSTek Computer                | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 44        | 21.05%  |
| Realtek Bluetooth Radio                               | 16        | 7.66%   |
| Intel AX200 Bluetooth                                 | 15        | 7.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 14        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 9         | 4.31%   |
| Intel AX201 Bluetooth                                 | 9         | 4.31%   |
| Qualcomm Atheros  Bluetooth Device                    | 8         | 3.83%   |
| Intel Wireless-AC 3168 Bluetooth                      | 8         | 3.83%   |
| IMC Networks Bluetooth Radio                          | 7         | 3.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7         | 3.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 2.87%   |
| Foxconn / Hon Hai Bluetooth Device                    | 5         | 2.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.44%   |
| IMC Networks Wireless_Device                          | 3         | 1.44%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 0.96%   |
| Lite-On Bluetooth Device                              | 2         | 0.96%   |
| IMC Networks Bluetooth Device                         | 2         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 2         | 0.96%   |
| Foxconn International BCM43142A0 Bluetooth module     | 2         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 0.96%   |
| Broadcom HP Portable Bumble Bee                       | 2         | 0.96%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 0.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2         | 0.96%   |
| Apple Bluetooth USB Host Controller                   | 2         | 0.96%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.48%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)            | 1         | 0.48%   |
| Toshiba Bluetooth Device                              | 1         | 0.48%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.48%   |
| Realtek RTL8723B Bluetooth                            | 1         | 0.48%   |
| Realtek Bluetooth Radio                               | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.48%   |
| Lite-On Wireless_Device                               | 1         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.48%   |
| Intel Bluetooth Device                                | 1         | 0.48%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.48%   |
| IMC Networks BCM20702A0                               | 1         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.48%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]         | 1         | 0.48%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter            | 1         | 0.48%   |
| Foxconn / Hon Hai BT                                  | 1         | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.48%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.48%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1         | 0.48%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1         | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1         | 0.48%   |
| Apple Bluetooth Host Controller                       | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 246       | 50.51%  |
| AMD                              | 115       | 23.61%  |
| Nvidia                           | 73        | 14.99%  |
| C-Media Electronics              | 11        | 2.26%   |
| Logitech                         | 7         | 1.44%   |
| JMTek                            | 4         | 0.82%   |
| Lenovo                           | 3         | 0.62%   |
| Creative Labs                    | 3         | 0.62%   |
| VIA Technologies                 | 2         | 0.41%   |
| Trust                            | 2         | 0.41%   |
| Silicon Integrated Systems [SiS] | 2         | 0.41%   |
| Microsoft                        | 2         | 0.41%   |
| ZOOM                             | 1         | 0.21%   |
| Yamaha                           | 1         | 0.21%   |
| XMOS                             | 1         | 0.21%   |
| Texas Instruments                | 1         | 0.21%   |
| Tenx Technology                  | 1         | 0.21%   |
| SteelSeries ApS                  | 1         | 0.21%   |
| Realtek Semiconductor            | 1         | 0.21%   |
| Razer USA                        | 1         | 0.21%   |
| Plantronics                      | 1         | 0.21%   |
| Pioneer DJ                       | 1         | 0.21%   |
| Native Instruments               | 1         | 0.21%   |
| GN Netcom                        | 1         | 0.21%   |
| Focusrite-Novation               | 1         | 0.21%   |
| Ensoniq                          | 1         | 0.21%   |
| Cirrus Logic                     | 1         | 0.21%   |
| ATI Technologies                 | 1         | 0.21%   |
| Astro Gaming                     | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 4.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 3.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 3.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 3.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 1.88%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 10        | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.54%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.2%    |
| Nvidia Audio device                                                                               | 6         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.03%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.03%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 0.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.68%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.68%   |
| C-Media Electronics Audio Adapter                                                                 | 4         | 0.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.51%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.51%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 3         | 0.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.51%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.51%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.51%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.51%   |
| Trust GXT 232 Microphone                                                                          | 2         | 0.34%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 23.36%  |
| Kingston            | 42        | 19.63%  |
| SK Hynix            | 37        | 17.29%  |
| Micron Technology   | 21        | 9.81%   |
| Unknown             | 15        | 7.01%   |
| Crucial             | 10        | 4.67%   |
| Corsair             | 9         | 4.21%   |
| G.Skill             | 8         | 3.74%   |
| Transcend           | 4         | 1.87%   |
| Patriot             | 4         | 1.87%   |
| A-DATA Technology   | 4         | 1.87%   |
| Ramaxel Technology  | 3         | 1.4%    |
| Kingmax             | 2         | 0.93%   |
| Elpida              | 2         | 0.93%   |
| Qimonda             | 1         | 0.47%   |
| Mushkin             | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 2.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 1.71%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 3         | 1.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.28%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 3         | 1.28%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 3         | 1.28%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 0.85%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                        | 2         | 0.85%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 0.85%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s          | 2         | 0.85%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 2         | 0.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 0.85%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.85%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                | 2         | 0.85%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s      | 2         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.85%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.85%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s       | 2         | 0.85%   |
| Kingston RAM 9905700-047.A00G 16384MB SODIMM DDR4 2667MT/s    | 2         | 0.85%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                    | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                    | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                 | 1         | 0.43%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                    | 1         | 0.43%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s         | 1         | 0.43%   |
| Transcend RAM TS128MSQ64V6J 1024MB SODIMM DDR2 667MT/s        | 1         | 0.43%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s          | 1         | 0.43%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s             | 1         | 0.43%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s             | 1         | 0.43%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.43%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.43%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.43%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 0.43%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 0.43%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 0.43%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.43%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 0.43%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s              | 1         | 0.43%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s       | 1         | 0.43%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.43%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.43%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s          | 1         | 0.43%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.43%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s       | 1         | 0.43%   |
| SK Hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM 1600MT/s          | 1         | 0.43%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1333MT/s          | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 90        | 50.28%  |
| DDR3    | 58        | 32.4%   |
| DDR2    | 10        | 5.59%   |
| LPDDR3  | 7         | 3.91%   |
| LPDDR4  | 6         | 3.35%   |
| Unknown | 4         | 2.23%   |
| SDRAM   | 3         | 1.68%   |
| DDR     | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 59.55%  |
| DIMM         | 55        | 30.9%   |
| Row Of Chips | 16        | 8.99%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 40.51%  |
| 4096  | 58        | 29.74%  |
| 16384 | 26        | 13.33%  |
| 2048  | 20        | 10.26%  |
| 1024  | 8         | 4.1%    |
| 32768 | 3         | 1.54%   |
| 512   | 1         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 42        | 22.11%  |
| 2667  | 39        | 20.53%  |
| 3200  | 30        | 15.79%  |
| 1333  | 13        | 6.84%   |
| 2400  | 12        | 6.32%   |
| 2133  | 11        | 5.79%   |
| 667   | 7         | 3.68%   |
| 1334  | 4         | 2.11%   |
| 2666  | 3         | 1.58%   |
| 4267  | 2         | 1.05%   |
| 4266  | 2         | 1.05%   |
| 3466  | 2         | 1.05%   |
| 2933  | 2         | 1.05%   |
| 1800  | 2         | 1.05%   |
| 1067  | 2         | 1.05%   |
| 800   | 2         | 1.05%   |
| 533   | 2         | 1.05%   |
| 4000  | 1         | 0.53%   |
| 3600  | 1         | 0.53%   |
| 3533  | 1         | 0.53%   |
| 3400  | 1         | 0.53%   |
| 3334  | 1         | 0.53%   |
| 3333  | 1         | 0.53%   |
| 3266  | 1         | 0.53%   |
| 3000  | 1         | 0.53%   |
| 2048  | 1         | 0.53%   |
| 1867  | 1         | 0.53%   |
| 1066  | 1         | 0.53%   |
| 975   | 1         | 0.53%   |
| 400   | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 53.33%  |
| Canon               | 3         | 20%     |
| Prolific Technology | 2         | 13.33%  |
| Seiko Epson         | 1         | 6.67%   |
| Samsung Electronics | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 13.33%  |
| HP DeskJet 3630 series          | 2         | 13.33%  |
| Seiko Epson L395 Series         | 1         | 6.67%   |
| Samsung Composite Device        | 1         | 6.67%   |
| HP LaserJet M14-M17             | 1         | 6.67%   |
| HP LaserJet M101-M106           | 1         | 6.67%   |
| HP LaserJet 400 colorMFP M475dw | 1         | 6.67%   |
| HP Ink Tank Wireless 410 series | 1         | 6.67%   |
| HP DeskJet 2130 series          | 1         | 6.67%   |
| HP Deskjet 1050 J410            | 1         | 6.67%   |
| Canon PIXMA iP4300 Printer      | 1         | 6.67%   |
| Canon PIXMA iP1800 Printer      | 1         | 6.67%   |
| Canon LBP6670 UFR II            | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 50%     |
| Canon              | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ultima Artec Ultima 2000      | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 60        | 25.86%  |
| IMC Networks                           | 24        | 10.34%  |
| Realtek Semiconductor                  | 23        | 9.91%   |
| Quanta                                 | 18        | 7.76%   |
| Microdia                               | 16        | 6.9%    |
| Logitech                               | 12        | 5.17%   |
| Acer                                   | 12        | 5.17%   |
| Syntek                                 | 10        | 4.31%   |
| Sunplus Innovation Technology          | 10        | 4.31%   |
| Suyin                                  | 9         | 3.88%   |
| Lite-On Technology                     | 8         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.02%   |
| Apple                                  | 5         | 2.16%   |
| Luxvisions Innotech Limited            | 3         | 1.29%   |
| Silicon Motion                         | 2         | 0.86%   |
| Primax Electronics                     | 2         | 0.86%   |
| Anker                                  | 2         | 0.86%   |
| Trust                                  | 1         | 0.43%   |
| Samsung Electronics                    | 1         | 0.43%   |
| Jieli Technology                       | 1         | 0.43%   |
| Goertek Electronics                    | 1         | 0.43%   |
| GenesysLogic Technology                | 1         | 0.43%   |
| Genesys Logic                          | 1         | 0.43%   |
| Cubeternet                             | 1         | 0.43%   |
| AVerMedia Technologies                 | 1         | 0.43%   |
| Alcor Micro                            | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 5.15%   |
| Chicony HD WebCam                                   | 11        | 4.72%   |
| IMC Networks Integrated Camera                      | 8         | 3.43%   |
| Quanta VGA WebCam                                   | 7         | 3%      |
| Microdia Integrated_Webcam_HD                       | 7         | 3%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 3%      |
| Syntek Integrated Camera                            | 6         | 2.58%   |
| Lite-On HP HD Camera                                | 5         | 2.15%   |
| Sunplus Full HD webcam                              | 4         | 1.72%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.72%   |
| Quanta HD Webcam                                    | 4         | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.72%   |
| Acer Lenovo EasyCamera                              | 4         | 1.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.29%   |
| Realtek Integrated Webcam                           | 3         | 1.29%   |
| Logitech Webcam C270                                | 3         | 1.29%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.29%   |
| Chicony Integrated HP HD Webcam                     | 3         | 1.29%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.29%   |
| Chicony HP Webcam                                   | 3         | 1.29%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.29%   |
| Suyin WebCam                                        | 2         | 0.86%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.86%   |
| Sunplus HD WebCam                                   | 2         | 0.86%   |
| Realtek USB Camera                                  | 2         | 0.86%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.86%   |
| Realtek FULL HD 1080P Webcam                        | 2         | 0.86%   |
| Realtek EasyCamera                                  | 2         | 0.86%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.86%   |
| Quanta HP HD Camera                                 | 2         | 0.86%   |
| Quanta HD User Facing                               | 2         | 0.86%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.86%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 0.86%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.86%   |
| Microdia Camera                                     | 2         | 0.86%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.86%   |
| Lite-On Integrated Camera                           | 2         | 0.86%   |
| IMC Networks HD Camera                              | 2         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.86%   |
| Chicony USB 2.0 Camera                              | 2         | 0.86%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.86%   |
| Chicony EasyCamera                                  | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.86%   |
| Anker PowerConf C300                                | 2         | 0.86%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.86%   |
| Acer Integrated Camera                              | 2         | 0.86%   |
| Acer EasyCamera                                     | 2         | 0.86%   |
| Trust Full HD Webcam                                | 1         | 0.43%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.43%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.43%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.43%   |
| Syntek EasyCamera                                   | 1         | 0.43%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.43%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.43%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.43%   |
| Sunplus Integrated Camera                           | 1         | 0.43%   |
| Sunplus ASUS Webcam                                 | 1         | 0.43%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.43%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 32.69%  |
| Validity Sensors           | 14        | 26.92%  |
| Shenzhen Goodix Technology | 10        | 19.23%  |
| Elan Microelectronics      | 4         | 7.69%   |
| Upek                       | 3         | 5.77%   |
| LighTuning Technology      | 2         | 3.85%   |
| STMicroelectronics         | 1         | 1.92%   |
| AuthenTec                  | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 13.46%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 7.69%   |
| Unknown                                                                    | 4         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.77%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.85%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.92%   |
| Validity Sensors VFS491                                                    | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.92%   |
| Synaptics  WBDI                                                            | 1         | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.92%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.92%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 66.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 4         | 66.67%  |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 253       | 71.27%  |
| 1     | 81        | 22.82%  |
| 2     | 18        | 5.07%   |
| 3     | 3         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 41.8%   |
| Graphics card            | 27        | 22.13%  |
| Net/wireless             | 12        | 9.84%   |
| Multimedia controller    | 7         | 5.74%   |
| Chipcard                 | 5         | 4.1%    |
| Communication controller | 4         | 3.28%   |
| Unassigned class         | 3         | 2.46%   |
| Card reader              | 3         | 2.46%   |
| Bluetooth                | 3         | 2.46%   |
| Camera                   | 2         | 1.64%   |
| Storage/raid             | 1         | 0.82%   |
| Storage/ide              | 1         | 0.82%   |
| Storage                  | 1         | 0.82%   |
| Sound                    | 1         | 0.82%   |
| Modem                    | 1         | 0.82%   |

