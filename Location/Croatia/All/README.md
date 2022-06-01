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

Total: 544

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | C7Z270-CG-M                 | Server      | [dbbe7457ff](https://linux-hardware.org/?probe=dbbe7457ff) | May 31, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [a9c593dd0b](https://linux-hardware.org/?probe=a9c593dd0b) | May 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [ac2e497963](https://linux-hardware.org/?probe=ac2e497963) | May 28, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | 0J37VM A01                  | Desktop     | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
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
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
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
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [980b14c09a](https://linux-hardware.org/?probe=980b14c09a) | Feb 11, 2022 |
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
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
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
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8803020fce](https://linux-hardware.org/?probe=8803020fce) | Sep 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
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
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
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
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
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
| MSI           | P67A-GD53/2.0               | Desktop     | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| HP            | 18EA                        | Desktop     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| ASRock        | Z370 Pro4                   | Desktop     | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| Acer          | Aspire 7739G                | Notebook    | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | Notebook    | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
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
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
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
| ASUSTek       | X751NV                      | Notebook    | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | Notebook    | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
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
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
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
| ASRock        | 990FX Extreme3              | Desktop     | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| ASRock        | H97 Killer                  | Desktop     | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | Notebook    | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| HP            | 18EA                        | Desktop     | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| ASUSTek       | G750JZ                      | Notebook    | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | Notebook    | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | Notebook    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | Desktop     | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
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
| HP            | Notebook                    | Notebook    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | Notebook    | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
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
| Samsung       | N150/N210/N220              | Notebook    | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | Notebook    | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | Notebook    | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 71        | 17.84%  |
| Ubuntu 18.04                 | 35        | 8.79%   |
| Debian 11                    | 12        | 3.02%   |
| Linux Mint 20.2              | 10        | 2.51%   |
| Ubuntu 18.10                 | 9         | 2.26%   |
| Pop!_OS 21.04                | 9         | 2.26%   |
| OpenMandriva 4.3             | 9         | 2.26%   |
| Zorin 16                     | 7         | 1.76%   |
| Ubuntu 21.04                 | 7         | 1.76%   |
| Pop!_OS 20.04                | 7         | 1.76%   |
| Ubuntu 19.10                 | 6         | 1.51%   |
| Pop!_OS 21.10                | 6         | 1.51%   |
| Pop!_OS 20.10                | 6         | 1.51%   |
| OpenMandriva 4.2             | 6         | 1.51%   |
| Linux Mint 20.3              | 6         | 1.51%   |
| Debian 10                    | 6         | 1.51%   |
| Ubuntu 19.04                 | 5         | 1.26%   |
| KDE neon 20.04               | 5         | 1.26%   |
| Fedora 35                    | 5         | 1.26%   |
| Endless 3.7.8                | 5         | 1.26%   |
| ArcoLinux Rolling            | 5         | 1.26%   |
| Zorin 15                     | 4         | 1.01%   |
| Ubuntu 20.10                 | 4         | 1.01%   |
| Manjaro                      | 4         | 1.01%   |
| Linux Mint 20                | 4         | 1.01%   |
| Fedora 31                    | 4         | 1.01%   |
| Arch Rolling                 | 4         | 1.01%   |
| Ubuntu MATE 20.04            | 3         | 0.75%   |
| ROSA R10                     | 3         | 0.75%   |
| OpenMandriva 4.50            | 3         | 0.75%   |
| Linux Mint 19.3              | 3         | 0.75%   |
| Kubuntu 20.04                | 3         | 0.75%   |
| Fedora 34                    | 3         | 0.75%   |
| Endless 3.9.5                | 3         | 0.75%   |
| Endless 3.9.4                | 3         | 0.75%   |
| Arch                         | 3         | 0.75%   |
| Xubuntu 20.04                | 2         | 0.5%    |
| Xubuntu 18.04                | 2         | 0.5%    |
| Ubuntu Budgie 20.04          | 2         | 0.5%    |
| Ubuntu 22.04                 | 2         | 0.5%    |
| Ubuntu 21.10                 | 2         | 0.5%    |
| Pop!_OS 22.04                | 2         | 0.5%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.5%    |
| openSUSE Leap-15.2           | 2         | 0.5%    |
| Manjaro 21.0.7               | 2         | 0.5%    |
| Manjaro 21.0                 | 2         | 0.5%    |
| Manjaro 20.2.1               | 2         | 0.5%    |
| Manjaro 20.2                 | 2         | 0.5%    |
| Manjaro 20.1.2               | 2         | 0.5%    |
| Manjaro 18.1.5               | 2         | 0.5%    |
| LMDE 4                       | 2         | 0.5%    |
| Linux Mint 19                | 2         | 0.5%    |
| Kubuntu 21.04                | 2         | 0.5%    |
| Fedora 36                    | 2         | 0.5%    |
| Fedora 33                    | 2         | 0.5%    |
| Endless 3.9.3                | 2         | 0.5%    |
| Endless 3.8.3                | 2         | 0.5%    |
| Elementary 6.1               | 2         | 0.5%    |
| Elementary 5.1.7             | 2         | 0.5%    |
| Ubuntu MATE 22.04            | 1         | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 133       | 36.74%  |
| Pop!_OS       | 30        | 8.29%   |
| Linux Mint    | 28        | 7.73%   |
| Endless       | 23        | 6.35%   |
| OpenMandriva  | 18        | 4.97%   |
| Manjaro       | 18        | 4.97%   |
| Fedora        | 16        | 4.42%   |
| Debian        | 16        | 4.42%   |
| Zorin         | 11        | 3.04%   |
| Kubuntu       | 8         | 2.21%   |
| ROSA          | 7         | 1.93%   |
| Arch          | 7         | 1.93%   |
| Ubuntu MATE   | 5         | 1.38%   |
| openSUSE      | 5         | 1.38%   |
| KDE neon      | 5         | 1.38%   |
| Elementary    | 5         | 1.38%   |
| ArcoLinux     | 5         | 1.38%   |
| Xubuntu       | 4         | 1.1%    |
| Ubuntu Budgie | 4         | 1.1%    |
| LMDE          | 2         | 0.55%   |
| LinuxFX       | 2         | 0.55%   |
| Kali          | 2         | 0.55%   |
| EndeavourOS   | 2         | 0.55%   |
| Raspbian      | 1         | 0.28%   |
| Parrot        | 1         | 0.28%   |
| Lubuntu       | 1         | 0.28%   |
| Gentoo        | 1         | 0.28%   |
| Clear Linux   | 1         | 0.28%   |
| CentOS        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 2.07%   |
| 5.4.0-42-generic         | 8         | 1.84%   |
| 5.11.0-38-generic        | 8         | 1.84%   |
| 5.8.0-14-generic         | 6         | 1.38%   |
| 5.4.0-58-generic         | 6         | 1.38%   |
| 5.3.0-28-generic         | 6         | 1.38%   |
| 5.11.0-7620-generic      | 6         | 1.38%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.38%   |
| 5.4.0-91-generic         | 5         | 1.15%   |
| 5.4.0-48-generic         | 5         | 1.15%   |
| 5.4.0-37-generic         | 5         | 1.15%   |
| 5.11.0-41-generic        | 5         | 1.15%   |
| 5.8.0-59-generic         | 4         | 0.92%   |
| 5.8.0-48-generic         | 4         | 0.92%   |
| 5.4.0-52-generic         | 4         | 0.92%   |
| 5.3.0-26-generic         | 4         | 0.92%   |
| 5.13.0-30-generic        | 4         | 0.92%   |
| 5.11.0-40-generic        | 4         | 0.92%   |
| 4.18.0-10-generic        | 4         | 0.92%   |
| 5.8.16-2-MANJARO         | 3         | 0.69%   |
| 5.8.0-7630-generic       | 3         | 0.69%   |
| 5.8.0-43-generic         | 3         | 0.69%   |
| 5.4.0-47-generic         | 3         | 0.69%   |
| 5.4.0-40-generic         | 3         | 0.69%   |
| 5.4.0-29-generic         | 3         | 0.69%   |
| 5.4.0-26-generic         | 3         | 0.69%   |
| 5.4.0-19-generic         | 3         | 0.69%   |
| 5.4.0-100-generic        | 3         | 0.69%   |
| 5.3.0-40-generic         | 3         | 0.69%   |
| 5.3.0-23-generic         | 3         | 0.69%   |
| 5.16.11-76051611-generic | 3         | 0.69%   |
| 5.13.0-7620-generic      | 3         | 0.69%   |
| 5.13.0-40-generic        | 3         | 0.69%   |
| 5.12.4-desktop-1omv4050  | 3         | 0.69%   |
| 5.11.0-37-generic        | 3         | 0.69%   |
| 5.11.0-34-generic        | 3         | 0.69%   |
| 5.11.0-27-generic        | 3         | 0.69%   |
| 5.10.0-13-amd64          | 3         | 0.69%   |
| 5.0.0-27-generic         | 3         | 0.69%   |
| 4.18.0-18-generic        | 3         | 0.69%   |
| 4.18.0-15-generic        | 3         | 0.69%   |
| 4.15.0-20-generic        | 3         | 0.69%   |
| 5.9.16-1-MANJARO         | 2         | 0.46%   |
| 5.8.0-49-generic         | 2         | 0.46%   |
| 5.4.0-90-generic         | 2         | 0.46%   |
| 5.4.0-84-generic         | 2         | 0.46%   |
| 5.4.0-7642-generic       | 2         | 0.46%   |
| 5.4.0-60-generic         | 2         | 0.46%   |
| 5.4.0-56-generic         | 2         | 0.46%   |
| 5.4.0-54-generic         | 2         | 0.46%   |
| 5.4.0-33-generic         | 2         | 0.46%   |
| 5.4.0-31-generic         | 2         | 0.46%   |
| 5.4.0-109-generic        | 2         | 0.46%   |
| 5.3.0-42-generic         | 2         | 0.46%   |
| 5.17.5-76051705-generic  | 2         | 0.46%   |
| 5.15.8-76051508-generic  | 2         | 0.46%   |
| 5.15.15-76051515-generic | 2         | 0.46%   |
| 5.15.0-27-generic        | 2         | 0.46%   |
| 5.13.0-41-generic        | 2         | 0.46%   |
| 5.13.0-39-generic        | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 84        | 20.54%  |
| 5.11.0  | 47        | 11.49%  |
| 5.8.0   | 26        | 6.36%   |
| 4.15.0  | 25        | 6.11%   |
| 5.3.0   | 24        | 5.87%   |
| 5.13.0  | 19        | 4.65%   |
| 4.18.0  | 19        | 4.65%   |
| 5.0.0   | 14        | 3.42%   |
| 5.10.0  | 12        | 2.93%   |
| 5.16.7  | 10        | 2.44%   |
| 5.15.0  | 7         | 1.71%   |
| 5.10.14 | 6         | 1.47%   |
| 4.19.0  | 6         | 1.47%   |
| 5.9.16  | 4         | 0.98%   |
| 5.16.11 | 4         | 0.98%   |
| 5.12.4  | 4         | 0.98%   |
| 5.8.16  | 3         | 0.73%   |
| 5.3.18  | 3         | 0.73%   |
| 5.15.8  | 3         | 0.73%   |
| 4.9.60  | 3         | 0.73%   |
| 5.9.11  | 2         | 0.49%   |
| 5.7.11  | 2         | 0.49%   |
| 5.5.0   | 2         | 0.49%   |
| 5.17.5  | 2         | 0.49%   |
| 5.17.4  | 2         | 0.49%   |
| 5.15.15 | 2         | 0.49%   |
| 5.14.0  | 2         | 0.49%   |
| 5.10.92 | 2         | 0.49%   |
| 5.10.79 | 2         | 0.49%   |
| 4.16.0  | 2         | 0.49%   |
| 5.9.9   | 1         | 0.24%   |
| 5.9.1   | 1         | 0.24%   |
| 5.9.0   | 1         | 0.24%   |
| 5.8.6   | 1         | 0.24%   |
| 5.7.0   | 1         | 0.24%   |
| 5.6.6   | 1         | 0.24%   |
| 5.6.2   | 1         | 0.24%   |
| 5.6.19  | 1         | 0.24%   |
| 5.6.12  | 1         | 0.24%   |
| 5.6.0   | 1         | 0.24%   |
| 5.4.74  | 1         | 0.24%   |
| 5.4.64  | 1         | 0.24%   |
| 5.4.20  | 1         | 0.24%   |
| 5.4.2   | 1         | 0.24%   |
| 5.4.18  | 1         | 0.24%   |
| 5.4.17  | 1         | 0.24%   |
| 5.4.13  | 1         | 0.24%   |
| 5.3.8   | 1         | 0.24%   |
| 5.3.16  | 1         | 0.24%   |
| 5.2.10  | 1         | 0.24%   |
| 5.17.7  | 1         | 0.24%   |
| 5.17.3  | 1         | 0.24%   |
| 5.17.1  | 1         | 0.24%   |
| 5.16.9  | 1         | 0.24%   |
| 5.16.8  | 1         | 0.24%   |
| 5.16.18 | 1         | 0.24%   |
| 5.16.15 | 1         | 0.24%   |
| 5.16.14 | 1         | 0.24%   |
| 5.16.13 | 1         | 0.24%   |
| 5.16.12 | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 91        | 22.64%  |
| 5.11    | 53        | 13.18%  |
| 5.8     | 30        | 7.46%   |
| 5.3     | 28        | 6.97%   |
| 5.10    | 28        | 6.97%   |
| 4.15    | 25        | 6.22%   |
| 5.13    | 22        | 5.47%   |
| 4.18    | 19        | 4.73%   |
| 5.16    | 18        | 4.48%   |
| 5.15    | 15        | 3.73%   |
| 5.0     | 15        | 3.73%   |
| 5.9     | 9         | 2.24%   |
| 5.17    | 7         | 1.74%   |
| 4.9     | 6         | 1.49%   |
| 4.19    | 6         | 1.49%   |
| 5.6     | 5         | 1.24%   |
| 5.14    | 5         | 1.24%   |
| 5.12    | 5         | 1.24%   |
| 5.7     | 3         | 0.75%   |
| 5.5     | 2         | 0.5%    |
| 4.16    | 2         | 0.5%    |
| 5.2     | 1         | 0.25%   |
| 5.1     | 1         | 0.25%   |
| 4.17    | 1         | 0.25%   |
| 4.14    | 1         | 0.25%   |
| 4.13    | 1         | 0.25%   |
| 4.12    | 1         | 0.25%   |
| 4.1     | 1         | 0.25%   |
| 3.10    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 345       | 97.46%  |
| i686    | 7         | 1.98%   |
| armv7l  | 1         | 0.28%   |
| aarch64 | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 171       | 46.09%  |
| Unknown         | 57        | 15.36%  |
| KDE5            | 53        | 14.29%  |
| X-Cinnamon      | 17        | 4.58%   |
| XFCE            | 12        | 3.23%   |
| MATE            | 10        | 2.7%    |
| KDE             | 10        | 2.7%    |
| Cinnamon        | 9         | 2.43%   |
| Budgie          | 5         | 1.35%   |
| Unity           | 4         | 1.08%   |
| Pantheon        | 4         | 1.08%   |
| KDE4            | 4         | 1.08%   |
| GNOME Flashback | 4         | 1.08%   |
| DWM             | 4         | 1.08%   |
| LXQt            | 2         | 0.54%   |
| openbox         | 1         | 0.27%   |
| LXDE            | 1         | 0.27%   |
| i3              | 1         | 0.27%   |
| Deepin          | 1         | 0.27%   |
| bspwm           | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 299       | 80.16%  |
| Unknown | 37        | 9.92%   |
| Wayland | 31        | 8.31%   |
| Tty     | 6         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 193       | 52.88%  |
| GDM     | 60        | 16.44%  |
| SDDM    | 49        | 13.42%  |
| LightDM | 27        | 7.4%    |
| GDM3    | 18        | 4.93%   |
| TDM     | 14        | 3.84%   |
| KDM     | 3         | 0.82%   |
| Ly      | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 183       | 50%     |
| hr_HR   | 92        | 25.14%  |
| Unknown | 62        | 16.94%  |
| en_GB   | 14        | 3.83%   |
| C       | 6         | 1.64%   |
| de_DE   | 5         | 1.37%   |
| ru_RU   | 1         | 0.27%   |
| hr_BA   | 1         | 0.27%   |
| fr_FR   | 1         | 0.27%   |
| en_DE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 195       | 53.72%  |
| BIOS | 168       | 46.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 290       | 79.45%  |
| Overlay | 25        | 6.85%   |
| Unknown | 21        | 5.75%   |
| Btrfs   | 15        | 4.11%   |
| Zfs     | 6         | 1.64%   |
| Xfs     | 5         | 1.37%   |
| Ext2    | 2         | 0.55%   |
| Jfs     | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 206       | 57.54%  |
| GPT     | 115       | 32.12%  |
| MBR     | 37        | 10.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 320       | 88.4%   |
| Yes       | 42        | 11.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 261       | 72.3%   |
| Yes       | 100       | 27.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 62        | 17.51%  |
| ASUSTek Computer        | 59        | 16.67%  |
| Hewlett-Packard         | 53        | 14.97%  |
| Acer                    | 38        | 10.73%  |
| ASRock                  | 31        | 8.76%   |
| Dell                    | 29        | 8.19%   |
| Gigabyte Technology     | 23        | 6.5%    |
| MSI                     | 9         | 2.54%   |
| Toshiba                 | 6         | 1.69%   |
| Apple                   | 6         | 1.69%   |
| Pegatron                | 5         | 1.41%   |
| Intel                   | 5         | 1.41%   |
| Samsung Electronics     | 3         | 0.85%   |
| Fujitsu Siemens         | 3         | 0.85%   |
| eMachines               | 3         | 0.85%   |
| ECS                     | 3         | 0.85%   |
| HUAWEI                  | 2         | 0.56%   |
| TUXEDO                  | 1         | 0.28%   |
| System76                | 1         | 0.28%   |
| Supermicro              | 1         | 0.28%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.28%   |
| Razer                   | 1         | 0.28%   |
| Raspberry Pi Foundation | 1         | 0.28%   |
| Nvidia                  | 1         | 0.28%   |
| Notebook                | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| Foxconn                 | 1         | 0.28%   |
| Chuwi                   | 1         | 0.28%   |
| AMI                     | 1         | 0.28%   |
| ABIT                    | 1         | 0.28%   |
| Unknown                 | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.13%   |
| Acer Aspire A315-21                        | 4         | 1.13%   |
| Lenovo G710 20252                          | 3         | 0.85%   |
| ASUS PRIME A320M-K                         | 3         | 0.85%   |
| Acer Aspire A515-51G                       | 3         | 0.85%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.56%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.56%   |
| Lenovo G40-30 80FY                         | 2         | 0.56%   |
| HP ProBook 450 G7                          | 2         | 0.56%   |
| HP EliteBook 850 G6                        | 2         | 0.56%   |
| HP 2000                                    | 2         | 0.56%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.56%   |
| Dell XPS 13 9310                           | 2         | 0.56%   |
| Dell Vostro 3500                           | 2         | 0.56%   |
| ASUS X751NV                                | 2         | 0.56%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.56%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.56%   |
| ASUS P8H77-V LE                            | 2         | 0.56%   |
| ASUS M5A78L LE                             | 2         | 0.56%   |
| ASRock H61M-DGS                            | 2         | 0.56%   |
| ASRock B450M-HDV R4.0                      | 2         | 0.56%   |
| Acer Aspire A715-72G                       | 2         | 0.56%   |
| Acer Aspire 7739G                          | 2         | 0.56%   |
| Unknown                                    | 2         | 0.56%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.28%   |
| Toshiba Satellite P200                     | 1         | 0.28%   |
| Toshiba Satellite L750                     | 1         | 0.28%   |
| Toshiba Satellite L50-B                    | 1         | 0.28%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.28%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.28%   |
| Toshiba Satellite A300                     | 1         | 0.28%   |
| System76 Oryx Pro                          | 1         | 0.28%   |
| Supermicro C7Z270-CG-M                     | 1         | 0.28%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.28%   |
| Samsung N150/N210/N220                     | 1         | 0.28%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.28%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.28%   |
| Razer Blade                                | 1         | 0.28%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 1         | 0.28%   |
| Pegatron Pro 3010 Small Form Factor PC     | 1         | 0.28%   |
| Pegatron HPE-520ad                         | 1         | 0.28%   |
| Pegatron G5261de                           | 1         | 0.28%   |
| Pegatron Compaq dx2400 Microtower PC       | 1         | 0.28%   |
| Pegatron 27-1001eu                         | 1         | 0.28%   |
| Nvidia Tegra                               | 1         | 0.28%   |
| Notebook MAM2080                           | 1         | 0.28%   |
| MSI MS-7C02                                | 1         | 0.28%   |
| MSI MS-7B98                                | 1         | 0.28%   |
| MSI MS-7B84                                | 1         | 0.28%   |
| MSI MS-7B07                                | 1         | 0.28%   |
| MSI MS-7850                                | 1         | 0.28%   |
| MSI MS-7817                                | 1         | 0.28%   |
| MSI MS-7681                                | 1         | 0.28%   |
| MSI MS-7586                                | 1         | 0.28%   |
| MSI MS-7360                                | 1         | 0.28%   |
| Medion P6618                               | 1         | 0.28%   |
| Lenovo Z50-70 20354                        | 1         | 0.28%   |
| Lenovo Yoga 910-13IKB 80VF                 | 1         | 0.28%   |
| Lenovo Yoga 7 14ACN6 82N7                  | 1         | 0.28%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 32        | 9.04%   |
| Lenovo ThinkPad               | 24        | 6.78%   |
| HP ProBook                    | 10        | 2.82%   |
| HP EliteBook                  | 10        | 2.82%   |
| Dell Vostro                   | 10        | 2.82%   |
| ASUS VivoBook                 | 8         | 2.26%   |
| ASUS PRIME                    | 8         | 2.26%   |
| Toshiba Satellite             | 6         | 1.69%   |
| Lenovo IdeaPad                | 6         | 1.69%   |
| HP Pavilion                   | 6         | 1.69%   |
| Dell XPS                      | 6         | 1.69%   |
| Lenovo ThinkBook              | 5         | 1.41%   |
| Lenovo Legion                 | 5         | 1.41%   |
| HP Laptop                     | 4         | 1.13%   |
| HP Compaq                     | 4         | 1.13%   |
| Dell Latitude                 | 4         | 1.13%   |
| Dell Inspiron                 | 4         | 1.13%   |
| ASUS TUF                      | 4         | 1.13%   |
| ASUS ROG                      | 4         | 1.13%   |
| ASUS All                      | 4         | 1.13%   |
| Lenovo IdeaCentre             | 3         | 0.85%   |
| Lenovo G710                   | 3         | 0.85%   |
| HP 250                        | 3         | 0.85%   |
| Acer Swift                    | 3         | 0.85%   |
| Lenovo Yoga                   | 2         | 0.56%   |
| Lenovo G40-30                 | 2         | 0.56%   |
| Lenovo B590                   | 2         | 0.56%   |
| HP ProDesk                    | 2         | 0.56%   |
| HP OMEN                       | 2         | 0.56%   |
| HP 2000                       | 2         | 0.56%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.56%   |
| Dell OptiPlex                 | 2         | 0.56%   |
| ASUS ZenBook                  | 2         | 0.56%   |
| ASUS X751NV                   | 2         | 0.56%   |
| ASUS P8H77-V                  | 2         | 0.56%   |
| ASUS M5A78L                   | 2         | 0.56%   |
| ASRock H97                    | 2         | 0.56%   |
| ASRock H61M-DGS               | 2         | 0.56%   |
| ASRock B450M-HDV              | 2         | 0.56%   |
| ASRock A320M-HDV              | 2         | 0.56%   |
| Unknown                       | 2         | 0.56%   |
| TUXEDO Pulse                  | 1         | 0.28%   |
| System76 Oryx                 | 1         | 0.28%   |
| Supermicro C7Z270-CG-M        | 1         | 0.28%   |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.28%   |
| Samsung N150                  | 1         | 0.28%   |
| Samsung 300E4C                | 1         | 0.28%   |
| Samsung 300E4A                | 1         | 0.28%   |
| Razer Blade                   | 1         | 0.28%   |
| RPi Raspberry                 | 1         | 0.28%   |
| Pegatron Pro                  | 1         | 0.28%   |
| Pegatron HPE-520ad            | 1         | 0.28%   |
| Pegatron G5261de              | 1         | 0.28%   |
| Pegatron Compaq               | 1         | 0.28%   |
| Pegatron 27-1001eu            | 1         | 0.28%   |
| Nvidia Tegra                  | 1         | 0.28%   |
| Notebook MAM2080              | 1         | 0.28%   |
| MSI MS-7C02                   | 1         | 0.28%   |
| MSI MS-7B98                   | 1         | 0.28%   |
| MSI MS-7B84                   | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 45        | 12.71%  |
| 2017    | 37        | 10.45%  |
| 2013    | 32        | 9.04%   |
| 2019    | 31        | 8.76%   |
| 2011    | 28        | 7.91%   |
| 2020    | 26        | 7.34%   |
| 2021    | 22        | 6.21%   |
| 2012    | 21        | 5.93%   |
| 2016    | 20        | 5.65%   |
| 2014    | 20        | 5.65%   |
| 2015    | 14        | 3.95%   |
| 2009    | 14        | 3.95%   |
| 2007    | 13        | 3.67%   |
| 2008    | 12        | 3.39%   |
| 2010    | 11        | 3.11%   |
| 2006    | 4         | 1.13%   |
| 2005    | 2         | 0.56%   |
| Unknown | 2         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 214       | 60.45%  |
| Desktop        | 124       | 35.03%  |
| All in one     | 6         | 1.69%   |
| Convertible    | 3         | 0.85%   |
| System on chip | 2         | 0.56%   |
| Mini pc        | 2         | 0.56%   |
| Server         | 2         | 0.56%   |
| Stick pc       | 1         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 325       | 91.04%  |
| Enabled  | 32        | 8.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 354       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 96        | 26.52%  |
| 8.01-16.0   | 80        | 22.1%   |
| 16.01-24.0  | 72        | 19.89%  |
| 3.01-4.0    | 59        | 16.3%   |
| 32.01-64.0  | 25        | 6.91%   |
| 1.01-2.0    | 16        | 4.42%   |
| 24.01-32.0  | 5         | 1.38%   |
| 2.01-3.0    | 5         | 1.38%   |
| 64.01-256.0 | 4         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 154       | 38.5%   |
| 2.01-3.0   | 102       | 25.5%   |
| 4.01-8.0   | 59        | 14.75%  |
| 3.01-4.0   | 43        | 10.75%  |
| 0.51-1.0   | 23        | 5.75%   |
| 8.01-16.0  | 12        | 3%      |
| 16.01-24.0 | 4         | 1%      |
| 0.01-0.5   | 3         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 224       | 60.87%  |
| 2       | 94        | 25.54%  |
| 3       | 27        | 7.34%   |
| 5       | 9         | 2.45%   |
| 4       | 6         | 1.63%   |
| 0       | 5         | 1.36%   |
| 7       | 1         | 0.27%   |
| 6       | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 216       | 60.5%   |
| Yes       | 141       | 39.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 317       | 89.3%   |
| No        | 38        | 10.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 267       | 75%     |
| No        | 89        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 58.77%  |
| No        | 148       | 41.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Croatia | 354       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Zagreb              | 213       | 53.25%  |
| Split               | 24        | 6%      |
| Rijeka              | 17        | 4.25%   |
| Varaždin           | 9         | 2.25%   |
| Pula                | 7         | 1.75%   |
| Koprivnica          | 7         | 1.75%   |
| Velika Gorica       | 6         | 1.5%    |
| Zaprešić          | 5         | 1.25%   |
| Samobor             | 5         | 1.25%   |
| Osijek              | 5         | 1.25%   |
| Virovitica          | 3         | 0.75%   |
| Krizevci            | 3         | 0.75%   |
| GJurgevac           | 3         | 0.75%   |
| Čakovec            | 3         | 0.75%   |
| Bjelovar            | 3         | 0.75%   |
| Zadar               | 2         | 0.5%    |
| Supetar             | 2         | 0.5%    |
| Rovinj              | 2         | 0.5%    |
| Pitomaca            | 2         | 0.5%    |
| Omiš               | 2         | 0.5%    |
| Novska              | 2         | 0.5%    |
| Matulji             | 2         | 0.5%    |
| Labin               | 2         | 0.5%    |
| Kastav              | 2         | 0.5%    |
| Karlovac            | 2         | 0.5%    |
| Jesenice            | 2         | 0.5%    |
| Ivanja Reka         | 2         | 0.5%    |
| Hvar                | 2         | 0.5%    |
| Đakovo             | 1         | 0.25%   |
| Zminj               | 1         | 0.25%   |
| Zabok               | 1         | 0.25%   |
| Visnjevac           | 1         | 0.25%   |
| Vinkovci            | 1         | 0.25%   |
| Varazdinske Toplice | 1         | 0.25%   |
| Umag                | 1         | 0.25%   |
| Trenkovo            | 1         | 0.25%   |
| Sveti Ivan Zelina   | 1         | 0.25%   |
| Sveta Marija        | 1         | 0.25%   |
| Stefanec            | 1         | 0.25%   |
| Sracinec            | 1         | 0.25%   |
| Slatina             | 1         | 0.25%   |
| Skrad               | 1         | 0.25%   |
| Sisak               | 1         | 0.25%   |
| Šibenik            | 1         | 0.25%   |
| Sesvete             | 1         | 0.25%   |
| Senj                | 1         | 0.25%   |
| Rokovci             | 1         | 0.25%   |
| Raslina             | 1         | 0.25%   |
| Prelog              | 1         | 0.25%   |
| Požega             | 1         | 0.25%   |
| Postira             | 1         | 0.25%   |
| Petrinja            | 1         | 0.25%   |
| Otocac              | 1         | 0.25%   |
| Opuzen              | 1         | 0.25%   |
| Ogulin              | 1         | 0.25%   |
| Novo Cice           | 1         | 0.25%   |
| Novi Marof          | 1         | 0.25%   |
| Našice             | 1         | 0.25%   |
| Medulin             | 1         | 0.25%   |
| Mali Lošinj        | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 96        | 146    | 19.24%  |
| Samsung Electronics   | 71        | 99     | 14.23%  |
| Kingston              | 51        | 70     | 10.22%  |
| Seagate               | 47        | 80     | 9.42%   |
| Toshiba               | 38        | 44     | 7.62%   |
| SK Hynix              | 22        | 32     | 4.41%   |
| Crucial               | 20        | 28     | 4.01%   |
| SanDisk               | 17        | 23     | 3.41%   |
| Intel                 | 15        | 22     | 3.01%   |
| Micron Technology     | 12        | 13     | 2.4%    |
| Hitachi               | 12        | 13     | 2.4%    |
| A-DATA Technology     | 12        | 15     | 2.4%    |
| Unknown               | 10        | 13     | 2%      |
| HGST                  | 9         | 9      | 1.8%    |
| Apple                 | 6         | 6      | 1.2%    |
| Transcend             | 5         | 6      | 1%      |
| Silicon Motion        | 5         | 6      | 1%      |
| Patriot               | 5         | 8      | 1%      |
| Fujitsu               | 4         | 4      | 0.8%    |
| Netac                 | 3         | 3      | 0.6%    |
| Corsair               | 3         | 3      | 0.6%    |
| StoreJet              | 2         | 2      | 0.4%    |
| Phison                | 2         | 2      | 0.4%    |
| OCZ                   | 2         | 3      | 0.4%    |
| MAXTOR                | 2         | 2      | 0.4%    |
| LITEON                | 2         | 3      | 0.4%    |
| KingFast              | 2         | 4      | 0.4%    |
| Intenso               | 2         | 3      | 0.4%    |
| Gigabyte Technology   | 2         | 2      | 0.4%    |
| AMD                   | 2         | 5      | 0.4%    |
| XPG                   | 1         | 3      | 0.2%    |
| Verbatim              | 1         | 1      | 0.2%    |
| UMIS                  | 1         | 1      | 0.2%    |
| Ugreen                | 1         | 1      | 0.2%    |
| TO Exter              | 1         | 1      | 0.2%    |
| Realtek Semiconductor | 1         | 3      | 0.2%    |
| Mushkin               | 1         | 2      | 0.2%    |
| Mass                  | 1         | 1      | 0.2%    |
| Lite-On               | 1         | 1      | 0.2%    |
| Lenovo                | 1         | 2      | 0.2%    |
| LaCie                 | 1         | 1      | 0.2%    |
| KIOXIA                | 1         | 1      | 0.2%    |
| KingSpec              | 1         | 1      | 0.2%    |
| Kingmax               | 1         | 1      | 0.2%    |
| HPE                   | 1         | 2      | 0.2%    |
| GOODRAM               | 1         | 1      | 0.2%    |
| External              | 1         | 1      | 0.2%    |
| ASMedia               | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD         | 8         | 1.5%    |
| Samsung SSD 850 EVO 250GB               | 7         | 1.31%   |
| Kingston SA400S37240G 240GB SSD         | 7         | 1.31%   |
| Samsung NVMe SSD Drive 512GB            | 6         | 1.12%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 1.12%   |
| Kingston SA400S37120G 120GB SSD         | 6         | 1.12%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 0.94%   |
| Sandisk NVMe SSD Drive 512GB            | 5         | 0.94%   |
| Kingston SV300S37A120G 120GB SSD        | 5         | 0.94%   |
| Crucial CT240BX500SSD1 240GB            | 5         | 0.94%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 4         | 0.75%   |
| Toshiba HDWD130 3TB                     | 4         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 0.75%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.75%   |
| A-DATA SU650 240GB SSD                  | 4         | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB             | 3         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.56%   |
| Toshiba HDWD110 1TB                     | 3         | 0.56%   |
| Toshiba DT01ACA100 1TB                  | 3         | 0.56%   |
| SK Hynix NVMe SSD Drive 512GB           | 3         | 0.56%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.56%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.56%   |
| Samsung HD103SI 1TB                     | 3         | 0.56%   |
| Patriot Burst 240GB SSD                 | 3         | 0.56%   |
| Intel SSDSC2BW120A4 120GB               | 3         | 0.56%   |
| A-DATA SU650 120GB SSD                  | 3         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.37%   |
| WDC WD6400AAKS-22A7B0 640GB             | 2         | 0.37%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.37%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 2         | 0.37%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2         | 0.37%   |
| WDC WD3200AAKS-00L9A0 320GB             | 2         | 0.37%   |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 0.37%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 0.37%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.37%   |
| WDC WD1600AAJS-07M0A0 160GB             | 2         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.37%   |
| WDC WD10EZEX-08M2NA0 1TB                | 2         | 0.37%   |
| Unknown SD/MMC/MS PRO 999GB             | 2         | 0.37%   |
| Unknown MMC Card  64GB                  | 2         | 0.37%   |
| Unknown MMC Card  32GB                  | 2         | 0.37%   |
| Unknown MMC Card  128GB                 | 2         | 0.37%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.37%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.37%   |
| Toshiba HDWD120 2TB                     | 2         | 0.37%   |
| StoreJet Transcend 480GB SSD            | 2         | 0.37%   |
| SK Hynix SH920 2.5 7MM 256GB SSD        | 2         | 0.37%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.37%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.37%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.37%   |
| Silicon Motion NVMe SSD Drive 1024GB    | 2         | 0.37%   |
| Seagate ST9500325AS 500GB               | 2         | 0.37%   |
| Seagate ST31000524AS 1TB                | 2         | 0.37%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 82        | 122    | 41.41%  |
| Seagate             | 47        | 69     | 23.74%  |
| Toshiba             | 31        | 37     | 15.66%  |
| Hitachi             | 12        | 13     | 6.06%   |
| HGST                | 9         | 9      | 4.55%   |
| Samsung Electronics | 8         | 11     | 4.04%   |
| Fujitsu             | 4         | 4      | 2.02%   |
| Unknown             | 2         | 2      | 1.01%   |
| MAXTOR              | 2         | 2      | 1.01%   |
| Intenso             | 1         | 2      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 46        | 59     | 25.7%   |
| Samsung Electronics | 28        | 42     | 15.64%  |
| Crucial             | 19        | 26     | 10.61%  |
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
| Mushkin             | 1         | 2      | 0.56%   |
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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 175       | 271    | 38.55%  |
| SSD     | 157       | 238    | 34.58%  |
| NVMe    | 106       | 153    | 23.35%  |
| Unknown | 9         | 22     | 1.98%   |
| MMC     | 7         | 10     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 265       | 498    | 67.26%  |
| NVMe | 106       | 153    | 26.9%   |
| SAS  | 16        | 33     | 4.06%   |
| MMC  | 7         | 10     | 1.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 318    | 60.77%  |
| 0.51-1.0   | 97        | 133    | 28.61%  |
| 1.01-2.0   | 20        | 27     | 5.9%    |
| 2.01-3.0   | 10        | 20     | 2.95%   |
| 3.01-4.0   | 5         | 10     | 1.47%   |
| 4.01-10.0  | 1         | 1      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 113       | 29.89%  |
| 251-500        | 83        | 21.96%  |
| 501-1000       | 57        | 15.08%  |
| 1001-2000      | 39        | 10.32%  |
| 51-100         | 25        | 6.61%   |
| 1-20           | 20        | 5.29%   |
| More than 3000 | 13        | 3.44%   |
| 21-50          | 12        | 3.17%   |
| Unknown        | 11        | 2.91%   |
| 2001-3000      | 5         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 149       | 36.97%  |
| 21-50          | 76        | 18.86%  |
| 51-100         | 45        | 11.17%  |
| 101-250        | 39        | 9.68%   |
| 251-500        | 32        | 7.94%   |
| 501-1000       | 31        | 7.69%   |
| 1001-2000      | 11        | 2.73%   |
| Unknown        | 11        | 2.73%   |
| 2001-3000      | 6         | 1.49%   |
| More than 3000 | 3         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 3.13%   |
| WDC WD6400AAKS-07A7B0 640GB         | 1         | 1      | 3.13%   |
| WDC WD600VE-75HDT0 64GB             | 1         | 1      | 3.13%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 1      | 3.13%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1         | 1      | 3.13%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 1      | 3.13%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 3.13%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1         | 1      | 3.13%   |
| Transcend TS480GSSD220S 480GB       | 1         | 1      | 3.13%   |
| Toshiba MK6459GSXP 640GB            | 1         | 1      | 3.13%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 3.13%   |
| SK Hynix SH920 2.5 7MM 256GB SSD    | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 3.13%   |
| Seagate ST9250827AS 250GB           | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 3.13%   |
| Seagate ST31500341AS 1TB            | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.13%   |
| SanDisk SDSSDXPS960G 960GB          | 1         | 1      | 3.13%   |
| SanDisk SDSSDA240G 240GB            | 1         | 1      | 3.13%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD | 1         | 1      | 3.13%   |
| Intel SSDSC2KF256H6 SATA 256GB      | 1         | 1      | 3.13%   |
| Intel SSDSC2BW120A4 120GB           | 1         | 1      | 3.13%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 3.13%   |
| Hitachi HDS723020BLA642 2TB         | 1         | 1      | 3.13%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 3.13%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 3.13%   |
| Crucial CT525MX300SSD1 528GB        | 1         | 1      | 3.13%   |
| Crucial CT120BX500SSD1 120GB        | 1         | 1      | 3.13%   |
| Crucial CT1024M550SSD1 1024GB       | 1         | 1      | 3.13%   |
| A-DATA Technology SU630 240GB SSD   | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 8         | 8      | 25.81%  |
| Seagate           | 6         | 6      | 19.35%  |
| HGST              | 3         | 3      | 9.68%   |
| Crucial           | 3         | 3      | 9.68%   |
| Toshiba           | 2         | 2      | 6.45%   |
| SanDisk           | 2         | 3      | 6.45%   |
| Intel             | 2         | 2      | 6.45%   |
| Hitachi           | 2         | 2      | 6.45%   |
| Transcend         | 1         | 1      | 3.23%   |
| SK Hynix          | 1         | 1      | 3.23%   |
| A-DATA Technology | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 35%     |
| Seagate | 6         | 6      | 30%     |
| HGST    | 3         | 3      | 15%     |
| Toshiba | 2         | 2      | 10%     |
| Hitachi | 2         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 66.67%  |
| SSD  | 10        | 12     | 33.33%  |

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
| Detected | 223       | 437    | 58.53%  |
| Works    | 131       | 225    | 34.38%  |
| Malfunc  | 27        | 32     | 7.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 241       | 54.28%  |
| AMD                              | 73        | 16.44%  |
| Samsung Electronics              | 40        | 9.01%   |
| Sandisk                          | 16        | 3.6%    |
| SK Hynix                         | 15        | 3.38%   |
| Kingston Technology Company      | 7         | 1.58%   |
| Toshiba America Info Systems     | 6         | 1.35%   |
| Silicon Motion                   | 5         | 1.13%   |
| Phison Electronics               | 5         | 1.13%   |
| JMicron Technology               | 5         | 1.13%   |
| Nvidia                           | 4         | 0.9%    |
| Marvell Technology Group         | 4         | 0.9%    |
| ASMedia Technology               | 3         | 0.68%   |
| VIA Technologies                 | 2         | 0.45%   |
| Silicon Integrated Systems [SiS] | 2         | 0.45%   |
| Micron Technology                | 2         | 0.45%   |
| Lite-On Technology               | 2         | 0.45%   |
| KIOXIA                           | 2         | 0.45%   |
| ADATA Technology                 | 2         | 0.45%   |
| Unknown                          | 1         | 0.23%   |
| Union Memory (Shenzhen)          | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| Micron/Crucial Technology        | 1         | 0.23%   |
| LSI Logic / Symbios Logic        | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| Broadcom / LSI                   | 1         | 0.23%   |
| Adaptec                          | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54        | 10.4%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 28        | 5.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26        | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16        | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 2.89%   |
| Samsung NVMe SSD Controller 980                                                         | 13        | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11        | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8         | 1.54%   |
| AMD FCH SATA Controller D                                                               | 8         | 1.54%   |
| SK Hynix Gold P31 SSD                                                                   | 7         | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.16%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 5         | 0.96%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 0.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 4         | 0.77%   |
| Intel SSD 600P Series                                                                   | 4         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.77%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.77%   |
| AMD FCH IDE Controller                                                                  | 4         | 0.77%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.58%   |
| SK Hynix BC511                                                                          | 3         | 0.58%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3         | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.58%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3         | 0.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.58%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.58%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.39%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 269       | 58.61%  |
| NVMe | 108       | 23.53%  |
| IDE  | 64        | 13.94%  |
| RAID | 17        | 3.7%    |
| SAS  | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 263       | 74.29%  |
| AMD    | 89        | 25.14%  |
| ARM    | 2         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 2.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.4%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.12%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 1.12%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.84%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.84%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.84%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.84%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.84%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.84%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.56%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.56%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 0.56%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.56%   |
| Intel Pentium 4 CPU 3.00GHz                   | 2         | 0.56%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.56%   |
| Intel Core i7-4771 CPU @ 3.50GHz              | 2         | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.56%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.56%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.56%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.56%   |
| Intel Core i5-2300 CPU @ 2.80GHz              | 2         | 0.56%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.56%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.56%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.56%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.56%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 2         | 0.56%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 2         | 0.56%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 2         | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.56%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 86        | 24.09%  |
| Intel Core i7           | 53        | 14.85%  |
| Intel Core i3           | 35        | 9.8%    |
| AMD Ryzen 5             | 23        | 6.44%   |
| Intel Core 2 Duo        | 19        | 5.32%   |
| Intel Pentium           | 18        | 5.04%   |
| AMD Ryzen 7             | 14        | 3.92%   |
| Other                   | 13        | 3.64%   |
| Intel Celeron           | 8         | 2.24%   |
| AMD Ryzen 3             | 8         | 2.24%   |
| Intel Pentium Dual-Core | 5         | 1.4%    |
| Intel Pentium Dual      | 5         | 1.4%    |
| Intel Core i9           | 5         | 1.4%    |
| Intel Atom              | 5         | 1.4%    |
| AMD Ryzen 9             | 5         | 1.4%    |
| AMD FX                  | 5         | 1.4%    |
| AMD A6                  | 5         | 1.4%    |
| AMD Athlon II X4        | 4         | 1.12%   |
| Intel Xeon              | 3         | 0.84%   |
| Intel Pentium Silver    | 3         | 0.84%   |
| AMD Phenom II X4        | 3         | 0.84%   |
| AMD E                   | 3         | 0.84%   |
| AMD Athlon X4           | 3         | 0.84%   |
| Intel Pentium M         | 2         | 0.56%   |
| Intel Pentium 4         | 2         | 0.56%   |
| Intel Core 2 Quad       | 2         | 0.56%   |
| Intel Core 2            | 2         | 0.56%   |
| AMD E1                  | 2         | 0.56%   |
| AMD Athlon 64 X2        | 2         | 0.56%   |
| AMD A8                  | 2         | 0.56%   |
| Intel Xeon Bronze       | 1         | 0.28%   |
| Intel Celeron M         | 1         | 0.28%   |
| ARM BCM                 | 1         | 0.28%   |
| AMD Turion 64 X2 Mobile | 1         | 0.28%   |
| AMD Ryzen Threadripper  | 1         | 0.28%   |
| AMD Ryzen 7 PRO         | 1         | 0.28%   |
| AMD Ryzen 3 PRO         | 1         | 0.28%   |
| AMD Phenom II X6        | 1         | 0.28%   |
| AMD Phenom II X2        | 1         | 0.28%   |
| AMD Athlon 64           | 1         | 0.28%   |
| AMD Athlon              | 1         | 0.28%   |
| AMD A4                  | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 148       | 41.46%  |
| 4       | 137       | 38.38%  |
| 6       | 31        | 8.68%   |
| 8       | 24        | 6.72%   |
| 1       | 8         | 2.24%   |
| 12      | 3         | 0.84%   |
| 3       | 2         | 0.56%   |
| 24      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 352       | 99.44%  |
| 2       | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 222       | 62.54%  |
| 1       | 132       | 37.18%  |
| Unknown | 1         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 339       | 95.22%  |
| Unknown        | 13        | 3.65%   |
| 32-bit         | 4         | 1.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 17.79%  |
| 0x306c3    | 30        | 8.09%   |
| 0x206a7    | 18        | 4.85%   |
| 0x906ea    | 15        | 4.04%   |
| 0x806ea    | 14        | 3.77%   |
| 0x306a9    | 14        | 3.77%   |
| 0x806e9    | 13        | 3.5%    |
| 0x1067a    | 12        | 3.23%   |
| 0x6fd      | 11        | 2.96%   |
| 0x806ec    | 10        | 2.7%    |
| 0x40651    | 8         | 2.16%   |
| 0x0a50000c | 7         | 1.89%   |
| 0x906e9    | 6         | 1.62%   |
| 0x08600106 | 6         | 1.62%   |
| 0x0810100b | 6         | 1.62%   |
| 0xa0653    | 5         | 1.35%   |
| 0x806c1    | 5         | 1.35%   |
| 0x306d4    | 5         | 1.35%   |
| 0x30678    | 5         | 1.35%   |
| 0x08108109 | 5         | 1.35%   |
| 0x0800820d | 5         | 1.35%   |
| 0x06006705 | 5         | 1.35%   |
| 0x906ed    | 4         | 1.08%   |
| 0x6fb      | 4         | 1.08%   |
| 0x506c9    | 4         | 1.08%   |
| 0x406e3    | 4         | 1.08%   |
| 0x20655    | 4         | 1.08%   |
| 0x010000db | 4         | 1.08%   |
| 0x010000c8 | 4         | 1.08%   |
| 0xa0671    | 3         | 0.81%   |
| 0x706e5    | 3         | 0.81%   |
| 0x506e3    | 3         | 0.81%   |
| 0x406c4    | 3         | 0.81%   |
| 0x08608103 | 3         | 0.81%   |
| 0x08600103 | 3         | 0.81%   |
| 0x06001119 | 3         | 0.81%   |
| 0x05000119 | 3         | 0.81%   |
| 0xf43      | 2         | 0.54%   |
| 0xa0655    | 2         | 0.54%   |
| 0x906eb    | 2         | 0.54%   |
| 0x806eb    | 2         | 0.54%   |
| 0x706a1    | 2         | 0.54%   |
| 0x6d8      | 2         | 0.54%   |
| 0x306f2    | 2         | 0.54%   |
| 0x10676    | 2         | 0.54%   |
| 0x08600104 | 2         | 0.54%   |
| 0x08108102 | 2         | 0.54%   |
| 0x08001137 | 2         | 0.54%   |
| 0x06000852 | 2         | 0.54%   |
| 0x0600063e | 2         | 0.54%   |
| 0xa0652    | 1         | 0.27%   |
| 0x906c0    | 1         | 0.27%   |
| 0x6fa      | 1         | 0.27%   |
| 0x6f6      | 1         | 0.27%   |
| 0x6e8      | 1         | 0.27%   |
| 0x50654    | 1         | 0.27%   |
| 0x40661    | 1         | 0.27%   |
| 0x106ca    | 1         | 0.27%   |
| 0x106c2    | 1         | 0.27%   |
| 0x106a4    | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 74        | 20.9%   |
| Haswell       | 45        | 12.71%  |
| SandyBridge   | 20        | 5.65%   |
| IvyBridge     | 19        | 5.37%   |
| Core          | 18        | 5.08%   |
| Penryn        | 15        | 4.24%   |
| Zen 2         | 14        | 3.95%   |
| Zen+          | 13        | 3.67%   |
| Zen           | 12        | 3.39%   |
| Skylake       | 11        | 3.11%   |
| Silvermont    | 11        | 3.11%   |
| Zen 3         | 10        | 2.82%   |
| CometLake     | 9         | 2.54%   |
| Unknown       | 9         | 2.54%   |
| Piledriver    | 8         | 2.26%   |
| K10           | 8         | 2.26%   |
| TigerLake     | 7         | 1.98%   |
| Excavator     | 7         | 1.98%   |
| Westmere      | 6         | 1.69%   |
| Broadwell     | 6         | 1.69%   |
| IceLake       | 5         | 1.41%   |
| K8 Hammer     | 4         | 1.13%   |
| Goldmont      | 4         | 1.13%   |
| Bobcat        | 4         | 1.13%   |
| P6            | 3         | 0.85%   |
| Goldmont plus | 3         | 0.85%   |
| NetBurst      | 2         | 0.56%   |
| Bulldozer     | 2         | 0.56%   |
| Tremont       | 1         | 0.28%   |
| Puma          | 1         | 0.28%   |
| Nehalem       | 1         | 0.28%   |
| Jaguar        | 1         | 0.28%   |
| Bonnell       | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 197       | 44.77%  |
| Nvidia                           | 125       | 28.41%  |
| AMD                              | 113       | 25.68%  |
| Silicon Integrated Systems [SiS] | 2         | 0.45%   |
| VIA Technologies                 | 1         | 0.23%   |
| Matrox Electronics Systems       | 1         | 0.23%   |
| ATI Technologies                 | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 17        | 3.79%   |
| Intel HD Graphics 620                                                                    | 14        | 3.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.45%   |
| AMD Renoir                                                                               | 11        | 2.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 2.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.34%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.34%   |
| AMD Cezanne                                                                              | 6         | 1.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.11%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.11%   |
| AMD Lucienne                                                                             | 5         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.89%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.89%   |
| Intel HD Graphics 630                                                                    | 4         | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.67%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.67%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.67%   |
| Intel HD Graphics 530                                                                    | 3         | 0.67%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.67%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.67%   |
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

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 121       | 33.89%  |
| 1 x AMD        | 83        | 23.25%  |
| 1 x Nvidia     | 61        | 17.09%  |
| Intel + Nvidia | 56        | 15.69%  |
| Intel + AMD    | 16        | 4.48%   |
| AMD + Nvidia   | 8         | 2.24%   |
| 2 x AMD        | 6         | 1.68%   |
| Other          | 2         | 0.56%   |
| 1 x SiS        | 2         | 0.56%   |
| 1 x VIA        | 1         | 0.28%   |
| 1 x Matrox     | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 273       | 76.04%  |
| Proprietary | 74        | 20.61%  |
| Unknown     | 12        | 3.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 47.55%  |
| 1.01-2.0   | 62        | 16.85%  |
| 0.51-1.0   | 38        | 10.33%  |
| 3.01-4.0   | 37        | 10.05%  |
| 0.01-0.5   | 36        | 9.78%   |
| 7.01-8.0   | 13        | 3.53%   |
| 5.01-6.0   | 3         | 0.82%   |
| 2.01-3.0   | 3         | 0.82%   |
| 8.01-16.0  | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 57        | 14.32%  |
| LG Display              | 41        | 10.3%   |
| AU Optronics            | 41        | 10.3%   |
| Dell                    | 38        | 9.55%   |
| BOE                     | 36        | 9.05%   |
| Chimei Innolux          | 35        | 8.79%   |
| AOC                     | 20        | 5.03%   |
| Goldstar                | 17        | 4.27%   |
| Philips                 | 16        | 4.02%   |
| Acer                    | 13        | 3.27%   |
| Hewlett-Packard         | 9         | 2.26%   |
| Lenovo                  | 8         | 2.01%   |
| Ancor Communications    | 8         | 2.01%   |
| Sharp                   | 7         | 1.76%   |
| Apple                   | 6         | 1.51%   |
| Chi Mei Optoelectronics | 4         | 1.01%   |
| PANDA                   | 3         | 0.75%   |
| LG Philips              | 3         | 0.75%   |
| Fujitsu Siemens         | 3         | 0.75%   |
| CSO                     | 3         | 0.75%   |
| BenQ                    | 3         | 0.75%   |
| Unknown                 | 2         | 0.5%    |
| Quanta Display          | 2         | 0.5%    |
| Panasonic               | 2         | 0.5%    |
| LG Electronics          | 2         | 0.5%    |
| InnoLux Display         | 2         | 0.5%    |
| Grundig                 | 2         | 0.5%    |
| Vestel Elektronik       | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| RTK                     | 1         | 0.25%   |
| NOA VISION              | 1         | 0.25%   |
| NEC Computers           | 1         | 0.25%   |
| NCS                     | 1         | 0.25%   |
| MSI                     | 1         | 0.25%   |
| KTC                     | 1         | 0.25%   |
| InfoVision              | 1         | 0.25%   |
| Iiyama                  | 1         | 0.25%   |
| IBM                     | 1         | 0.25%   |
| Huion                   | 1         | 0.25%   |
| BOE Technology Group    | 1         | 0.25%   |
| ASUSTek Computer        | 1         | 0.25%   |
| Achieva Shimian         | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.21%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 0.97%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 0.97%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 0.73%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 0.73%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.73%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 3         | 0.73%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                         | 3         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.73%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch      | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                         | 2         | 0.48%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.48%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                        | 2         | 0.48%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.48%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.48%   |
| Grundig WXGA GRU4448 1600x1200                                            | 2         | 0.48%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                       | 2         | 0.48%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                     | 2         | 0.48%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                          | 2         | 0.48%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 2         | 0.48%   |
| Dell LCD Monitor SE2416H 5760x1080                                        | 2         | 0.48%   |
| Dell LCD Monitor SE2416H                                                  | 2         | 0.48%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch           | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.48%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 2         | 0.48%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                           | 2         | 0.48%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                            | 2         | 0.48%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                           | 2         | 0.48%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                         | 2         | 0.48%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                             | 1         | 0.24%   |
| Unknown LCD Monitor SAMSUNG                                               | 1         | 0.24%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                               | 1         | 0.24%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                            | 1         | 0.24%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.24%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 0.24%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.24%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.24%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 600x340mm 27.2-inch         | 1         | 0.24%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch         | 1         | 0.24%   |
| Samsung Electronics SyncMaster SAM0626 1920x1080                          | 1         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 184       | 48.42%  |
| 1366x768 (WXGA)    | 47        | 12.37%  |
| 1600x900 (HD+)     | 26        | 6.84%   |
| 2560x1440 (QHD)    | 19        | 5%      |
| 3840x2160 (4K)     | 16        | 4.21%   |
| 1680x1050 (WSXGA+) | 16        | 4.21%   |
| 1440x900 (WXGA+)   | 10        | 2.63%   |
| 1280x1024 (SXGA)   | 10        | 2.63%   |
| 1920x1200 (WUXGA)  | 9         | 2.37%   |
| Unknown            | 9         | 2.37%   |
| 1280x800 (WXGA)    | 6         | 1.58%   |
| 3840x1080          | 4         | 1.05%   |
| 1360x768           | 4         | 1.05%   |
| 2560x1600          | 3         | 0.79%   |
| 2160x1440          | 3         | 0.79%   |
| 5760x1080          | 2         | 0.53%   |
| 3840x2400          | 2         | 0.53%   |
| 2560x1080          | 2         | 0.53%   |
| 1400x1050          | 2         | 0.53%   |
| 4480x1440          | 1         | 0.26%   |
| 2880x1800          | 1         | 0.26%   |
| 2048x1152          | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |
| 1024x600           | 1         | 0.26%   |
| 1024x576           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 115       | 28.97%  |
| 17      | 39        | 9.82%   |
| 27      | 32        | 8.06%   |
| 23      | 32        | 8.06%   |
| 24      | 27        | 6.8%    |
| 13      | 23        | 5.79%   |
| 14      | 22        | 5.54%   |
| Unknown | 22        | 5.54%   |
| 21      | 21        | 5.29%   |
| 22      | 9         | 2.27%   |
| 20      | 9         | 2.27%   |
| 31      | 8         | 2.02%   |
| 19      | 8         | 2.02%   |
| 12      | 5         | 1.26%   |
| 18      | 4         | 1.01%   |
| 54      | 3         | 0.76%   |
| 26      | 3         | 0.76%   |
| 16      | 3         | 0.76%   |
| 84      | 2         | 0.5%    |
| 25      | 2         | 0.5%    |
| 10      | 2         | 0.5%    |
| 72      | 1         | 0.25%   |
| 46      | 1         | 0.25%   |
| 34      | 1         | 0.25%   |
| 33      | 1         | 0.25%   |
| 32      | 1         | 0.25%   |
| 11      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 146       | 37.53%  |
| 501-600     | 84        | 21.59%  |
| 401-500     | 45        | 11.57%  |
| 351-400     | 44        | 11.31%  |
| 201-300     | 24        | 6.17%   |
| Unknown     | 22        | 5.66%   |
| 601-700     | 14        | 3.6%    |
| 1001-1500   | 4         | 1.03%   |
| 701-800     | 3         | 0.77%   |
| 1501-2000   | 3         | 0.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 268       | 76.14%  |
| 16/10   | 48        | 13.64%  |
| Unknown | 18        | 5.11%   |
| 5/4     | 9         | 2.56%   |
| 3/2     | 5         | 1.42%   |
| 4/3     | 3         | 0.85%   |
| 21/9    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 116       | 29.37%  |
| 201-250        | 65        | 16.46%  |
| 301-350        | 35        | 8.86%   |
| 81-90          | 33        | 8.35%   |
| 121-130        | 31        | 7.85%   |
| 151-200        | 28        | 7.09%   |
| Unknown        | 22        | 5.57%   |
| 251-300        | 13        | 3.29%   |
| 71-80          | 11        | 2.78%   |
| 351-500        | 11        | 2.78%   |
| 141-150        | 8         | 2.03%   |
| More than 1000 | 6         | 1.52%   |
| 61-70          | 4         | 1.01%   |
| 131-140        | 4         | 1.01%   |
| 41-50          | 2         | 0.51%   |
| 111-120        | 2         | 0.51%   |
| 91-100         | 2         | 0.51%   |
| 51-60          | 1         | 0.25%   |
| 501-1000       | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 125       | 32.72%  |
| 121-160       | 118       | 30.89%  |
| 101-120       | 92        | 24.08%  |
| Unknown       | 22        | 5.76%   |
| 161-240       | 15        | 3.93%   |
| 1-50          | 6         | 1.57%   |
| More than 240 | 4         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 283       | 76.9%   |
| 2     | 64        | 17.39%  |
| 0     | 14        | 3.8%    |
| 3     | 5         | 1.36%   |
| 4     | 2         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 216       | 39.2%   |
| Intel                             | 145       | 26.32%  |
| Qualcomm Atheros                  | 74        | 13.43%  |
| Broadcom                          | 28        | 5.08%   |
| MEDIATEK                          | 9         | 1.63%   |
| TP-Link                           | 8         | 1.45%   |
| Samsung Electronics               | 7         | 1.27%   |
| Qualcomm Atheros Communications   | 7         | 1.27%   |
| Broadcom Limited                  | 6         | 1.09%   |
| Ralink                            | 5         | 0.91%   |
| Marvell Technology Group          | 5         | 0.91%   |
| D-Link                            | 5         | 0.91%   |
| Ralink Technology                 | 4         | 0.73%   |
| Xiaomi                            | 3         | 0.54%   |
| Nvidia                            | 3         | 0.54%   |
| ASIX Electronics                  | 3         | 0.54%   |
| VIA Technologies                  | 2         | 0.36%   |
| Sundance Technology Inc / IC Plus | 2         | 0.36%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.36%   |
| Qualcomm                          | 2         | 0.36%   |
| Lenovo                            | 2         | 0.36%   |
| T & A Mobile Phones               | 1         | 0.18%   |
| Nokia Mobile Phones               | 1         | 0.18%   |
| Microsoft                         | 1         | 0.18%   |
| Linksys                           | 1         | 0.18%   |
| Huawei Technologies               | 1         | 0.18%   |
| HTC (High Tech Computer)          | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Fibocom                           | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| Edimax Technology                 | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| ASUSTek Computer                  | 1         | 0.18%   |
| Aquantia                          | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 173       | 27.72%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 3.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 2.72%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.72%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.12%   |
| Intel Wireless 3165                                                     | 7         | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.96%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.96%   |
| Intel Wireless 7260                                                     | 6         | 0.96%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.8%    |
| Intel Wireless 7265                                                     | 5         | 0.8%    |
| Intel Wireless 3160                                                     | 5         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.64%   |
| Intel I211 Gigabit Network Connection                                   | 4         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                    | 4         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.48%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.48%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.48%   |
| Intel WiFi Link 5100                                                    | 3         | 0.48%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.48%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.48%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.48%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.32%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.32%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2         | 0.32%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 41.45%  |
| Qualcomm Atheros                | 60        | 21.82%  |
| Realtek Semiconductor           | 35        | 12.73%  |
| Broadcom                        | 19        | 6.91%   |
| TP-Link                         | 8         | 2.91%   |
| MEDIATEK                        | 8         | 2.91%   |
| Qualcomm Atheros Communications | 7         | 2.55%   |
| Ralink                          | 5         | 1.82%   |
| D-Link                          | 5         | 1.82%   |
| Ralink Technology               | 4         | 1.45%   |
| Broadcom Limited                | 3         | 1.09%   |
| Qualcomm                        | 2         | 0.73%   |
| Microsoft                       | 1         | 0.36%   |
| Linksys                         | 1         | 0.36%   |
| Fibocom                         | 1         | 0.36%   |
| Edimax Technology               | 1         | 0.36%   |
| ASUSTek Computer                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 7.27%   |
| Intel Wireless 8265 / 8275                                              | 17        | 6.18%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 5.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.55%   |
| Intel Wireless 3165                                                     | 7         | 2.55%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 2.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.18%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.18%   |
| Intel Wireless 7260                                                     | 6         | 2.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.82%   |
| Intel Wireless 7265                                                     | 5         | 1.82%   |
| Intel Wireless 3160                                                     | 5         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.09%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.09%   |
| Intel WiFi Link 5100                                                    | 3         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.09%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.09%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.73%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2         | 0.73%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.73%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2         | 0.73%   |
| Intel Wireless 8260                                                     | 2         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.73%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.73%   |
| D-Link WLAN controller                                                  | 2         | 0.73%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.73%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.73%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.36%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 0.36%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.36%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.36%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.36%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.36%   |
| Realtek Realtek Network controller                                      | 1         | 0.36%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.36%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.36%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.36%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 204       | 59.65%  |
| Intel                             | 67        | 19.59%  |
| Qualcomm Atheros                  | 23        | 6.73%   |
| Broadcom                          | 10        | 2.92%   |
| Samsung Electronics               | 7         | 2.05%   |
| Marvell Technology Group          | 5         | 1.46%   |
| Xiaomi                            | 3         | 0.88%   |
| Nvidia                            | 3         | 0.88%   |
| Broadcom Limited                  | 3         | 0.88%   |
| ASIX Electronics                  | 3         | 0.88%   |
| VIA Technologies                  | 2         | 0.58%   |
| Sundance Technology Inc / IC Plus | 2         | 0.58%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.58%   |
| Lenovo                            | 2         | 0.58%   |
| T & A Mobile Phones               | 1         | 0.29%   |
| MediaTek                          | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| HTC (High Tech Computer)          | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| Aquantia                          | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 173       | 50.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 17        | 4.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 7         | 2.03%   |
| Intel Ethernet Connection I217-LM                                          | 6         | 1.74%   |
| Intel Ethernet Connection (4) I219-V                                       | 6         | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 5         | 1.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                     | 5         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 4         | 1.16%   |
| Intel I211 Gigabit Network Connection                                      | 4         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                                       | 4         | 1.16%   |
| Intel Ethernet Connection (2) I218-V                                       | 4         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 3         | 0.87%   |
| Intel Ethernet Connection I217-V                                           | 3         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                       | 3         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2         | 0.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 2         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 2         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.58%   |
| Nvidia MCP61 Ethernet                                                      | 2         | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2         | 0.58%   |
| Lenovo USB-C Dock Ethernet                                                 | 2         | 0.58%   |
| Intel I210 Gigabit Network Connection                                      | 2         | 0.58%   |
| Intel Ethernet Connection I219-LM                                          | 2         | 0.58%   |
| Intel Ethernet Connection I218-LM                                          | 2         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                       | 2         | 0.58%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2         | 0.58%   |
| Intel Ethernet Connection (14) I219-V                                      | 2         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                    | 2         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                   | 2         | 0.58%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                   | 2         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.29%   |
| T & A Mobile Phones 9010X                                                  | 1         | 0.29%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.29%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1         | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1         | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1         | 0.29%   |
| Nvidia MCP67 Ethernet                                                      | 1         | 0.29%   |
| MediaTek Vodafone Smart N10                                                | 1         | 0.29%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                    | 1         | 0.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1         | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 1         | 0.29%   |
| Intel Ethernet Controller I225-V                                           | 1         | 0.29%   |
| Intel Ethernet Connection (6) I219-LM                                      | 1         | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                                      | 1         | 0.29%   |
| Intel Ethernet Connection (4) I219-LM                                      | 1         | 0.29%   |
| Intel Ethernet Connection (3) I218-LM                                      | 1         | 0.29%   |
| Intel Ethernet Connection (13) I219-V                                      | 1         | 0.29%   |
| Intel Ethernet Connection (12) I219-V                                      | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 317       | 53.91%  |
| WiFi     | 267       | 45.41%  |
| Modem    | 4         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 221       | 59.73%  |
| Ethernet | 149       | 40.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 206       | 58.03%  |
| 1     | 140       | 39.44%  |
| 0     | 6         | 1.69%   |
| 4     | 2         | 0.56%   |
| 3     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 344       | 96.9%   |
| Yes  | 11        | 3.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 43.6%   |
| Qualcomm Atheros Communications | 21        | 9.95%   |
| Realtek Semiconductor           | 20        | 9.48%   |
| Lite-On Technology              | 19        | 9%      |
| IMC Networks                    | 14        | 6.64%   |
| Broadcom                        | 10        | 4.74%   |
| Foxconn / Hon Hai               | 8         | 3.79%   |
| Cambridge Silicon Radio         | 7         | 3.32%   |
| Hewlett-Packard                 | 5         | 2.37%   |
| Apple                           | 5         | 2.37%   |
| Toshiba                         | 3         | 1.42%   |
| Foxconn International           | 3         | 1.42%   |
| Realtek                         | 1         | 0.47%   |
| Integrated System Solution      | 1         | 0.47%   |
| Dell                            | 1         | 0.47%   |
| ASUSTek Computer                | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 43        | 20.38%  |
| Realtek Bluetooth Radio                               | 15        | 7.11%   |
| Intel AX200 Bluetooth                                 | 15        | 7.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 14        | 6.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10        | 4.74%   |
| Qualcomm Atheros  Bluetooth Device                    | 9         | 4.27%   |
| Intel AX201 Bluetooth                                 | 9         | 4.27%   |
| Intel Wireless-AC 3168 Bluetooth                      | 8         | 3.79%   |
| IMC Networks Bluetooth Radio                          | 7         | 3.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7         | 3.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 2.84%   |
| Foxconn / Hon Hai Bluetooth Device                    | 5         | 2.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3         | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.42%   |
| IMC Networks Wireless_Device                          | 3         | 1.42%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 0.95%   |
| Realtek 802.11ac WLAN Adapter                         | 2         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 0.95%   |
| Lite-On Bluetooth Device                              | 2         | 0.95%   |
| IMC Networks Bluetooth Device                         | 2         | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 2         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 0.95%   |
| Broadcom HP Portable Bumble Bee                       | 2         | 0.95%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2         | 0.95%   |
| Apple Bluetooth USB Host Controller                   | 2         | 0.95%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.47%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)            | 1         | 0.47%   |
| Toshiba Bluetooth Device                              | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                            | 1         | 0.47%   |
| Realtek Bluetooth Radio                               | 1         | 0.47%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.47%   |
| Lite-On Wireless_Device                               | 1         | 0.47%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1         | 0.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.47%   |
| IMC Networks BCM20702A0                               | 1         | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.47%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]         | 1         | 0.47%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter            | 1         | 0.47%   |
| Foxconn / Hon Hai BT                                  | 1         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.47%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.47%   |
| Broadcom Bluetooth 2.1 Device                         | 1         | 0.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1         | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1         | 0.47%   |
| Apple Bluetooth Host Controller                       | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 254       | 51%     |
| AMD                              | 116       | 23.29%  |
| Nvidia                           | 75        | 15.06%  |
| C-Media Electronics              | 11        | 2.21%   |
| Logitech                         | 7         | 1.41%   |
| JMTek                            | 4         | 0.8%    |
| Lenovo                           | 3         | 0.6%    |
| Creative Labs                    | 3         | 0.6%    |
| VIA Technologies                 | 2         | 0.4%    |
| Trust                            | 2         | 0.4%    |
| Silicon Integrated Systems [SiS] | 2         | 0.4%    |
| Microsoft                        | 2         | 0.4%    |
| ZOOM                             | 1         | 0.2%    |
| Yamaha                           | 1         | 0.2%    |
| XMOS                             | 1         | 0.2%    |
| Texas Instruments                | 1         | 0.2%    |
| Tenx Technology                  | 1         | 0.2%    |
| SteelSeries ApS                  | 1         | 0.2%    |
| Realtek Semiconductor            | 1         | 0.2%    |
| Razer USA                        | 1         | 0.2%    |
| Plantronics                      | 1         | 0.2%    |
| Pioneer DJ                       | 1         | 0.2%    |
| Native Instruments               | 1         | 0.2%    |
| GN Netcom                        | 1         | 0.2%    |
| Focusrite-Novation               | 1         | 0.2%    |
| Ensoniq                          | 1         | 0.2%    |
| Cirrus Logic                     | 1         | 0.2%    |
| ATI Technologies                 | 1         | 0.2%    |
| Astro Gaming                     | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 6.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 4.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 3.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.85%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 10        | 1.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.17%   |
| Nvidia Audio device                                                                               | 6         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.01%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.01%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.84%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.67%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.67%   |
| C-Media Electronics Audio Adapter                                                                 | 4         | 0.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.5%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.5%    |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.5%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.5%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.5%    |
| Trust GXT 232 Microphone                                                                          | 2         | 0.34%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 22.94%  |
| Kingston            | 46        | 21.1%   |
| SK Hynix            | 36        | 16.51%  |
| Micron Technology   | 21        | 9.63%   |
| Unknown             | 15        | 6.88%   |
| Crucial             | 10        | 4.59%   |
| Corsair             | 9         | 4.13%   |
| G.Skill             | 8         | 3.67%   |
| Transcend           | 4         | 1.83%   |
| Patriot             | 4         | 1.83%   |
| A-DATA Technology   | 4         | 1.83%   |
| Ramaxel Technology  | 3         | 1.38%   |
| Kingmax             | 2         | 0.92%   |
| Elpida              | 2         | 0.92%   |
| Qimonda             | 1         | 0.46%   |
| Mushkin             | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |
| 48spaces            | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 2.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 1.68%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 3         | 1.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.26%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 3         | 1.26%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s    | 3         | 1.26%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 0.84%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                        | 2         | 0.84%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 0.84%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 0.84%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s       | 2         | 0.84%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 2         | 0.84%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.84%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 0.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.84%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s        | 2         | 0.84%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s      | 2         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s      | 2         | 0.84%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s        | 2         | 0.84%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s          | 2         | 0.84%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s       | 2         | 0.84%   |
| Kingston RAM 9905700-047.A00G 16384MB SODIMM DDR4 2667MT/s    | 2         | 0.84%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                    | 1         | 0.42%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s         | 1         | 0.42%   |
| Transcend RAM TS128MSQ64V6J 1024MB SODIMM DDR2 667MT/s        | 1         | 0.42%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s          | 1         | 0.42%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s             | 1         | 0.42%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s             | 1         | 0.42%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.42%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.42%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.42%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 0.42%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 0.42%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 0.42%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.42%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 0.42%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s              | 1         | 0.42%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s       | 1         | 0.42%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s          | 1         | 0.42%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.42%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s          | 1         | 0.42%   |
| SK Hynix RAM HMT325S6CFR8A-PB 2GB SODIMM 1600MT/s             | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 50.27%  |
| DDR3    | 60        | 32.79%  |
| DDR2    | 10        | 5.46%   |
| LPDDR3  | 7         | 3.83%   |
| LPDDR4  | 6         | 3.28%   |
| Unknown | 4         | 2.19%   |
| SDRAM   | 3         | 1.64%   |
| DDR     | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 58.24%  |
| DIMM         | 59        | 32.42%  |
| Row Of Chips | 16        | 8.79%   |
| Chip         | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 80        | 40.2%   |
| 4096  | 59        | 29.65%  |
| 16384 | 27        | 13.57%  |
| 2048  | 21        | 10.55%  |
| 1024  | 8         | 4.02%   |
| 32768 | 3         | 1.51%   |
| 512   | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 42        | 21.65%  |
| 2667  | 40        | 20.62%  |
| 3200  | 31        | 15.98%  |
| 2400  | 13        | 6.7%    |
| 1333  | 13        | 6.7%    |
| 2133  | 11        | 5.67%   |
| 667   | 8         | 4.12%   |
| 1334  | 4         | 2.06%   |
| 2666  | 3         | 1.55%   |
| 4267  | 2         | 1.03%   |
| 4266  | 2         | 1.03%   |
| 3466  | 2         | 1.03%   |
| 2933  | 2         | 1.03%   |
| 1800  | 2         | 1.03%   |
| 1067  | 2         | 1.03%   |
| 800   | 2         | 1.03%   |
| 533   | 2         | 1.03%   |
| 4000  | 1         | 0.52%   |
| 3600  | 1         | 0.52%   |
| 3533  | 1         | 0.52%   |
| 3400  | 1         | 0.52%   |
| 3334  | 1         | 0.52%   |
| 3333  | 1         | 0.52%   |
| 3266  | 1         | 0.52%   |
| 3000  | 1         | 0.52%   |
| 2048  | 1         | 0.52%   |
| 1867  | 1         | 0.52%   |
| 1066  | 1         | 0.52%   |
| 975   | 1         | 0.52%   |
| 400   | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 50%     |
| Canon              | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ultima Artec Ultima 2000      | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 60        | 25.53%  |
| IMC Networks                           | 24        | 10.21%  |
| Realtek Semiconductor                  | 23        | 9.79%   |
| Quanta                                 | 18        | 7.66%   |
| Microdia                               | 16        | 6.81%   |
| Logitech                               | 13        | 5.53%   |
| Acer                                   | 12        | 5.11%   |
| Sunplus Innovation Technology          | 11        | 4.68%   |
| Syntek                                 | 10        | 4.26%   |
| Suyin                                  | 9         | 3.83%   |
| Lite-On Technology                     | 8         | 3.4%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.98%   |
| Apple                                  | 5         | 2.13%   |
| Luxvisions Innotech Limited            | 3         | 1.28%   |
| Silicon Motion                         | 2         | 0.85%   |
| Primax Electronics                     | 2         | 0.85%   |
| Anker                                  | 2         | 0.85%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
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

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 5.08%   |
| Chicony HD WebCam                                   | 11        | 4.66%   |
| IMC Networks Integrated Camera                      | 8         | 3.39%   |
| Quanta VGA WebCam                                   | 7         | 2.97%   |
| Microdia Integrated_Webcam_HD                       | 7         | 2.97%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 2.97%   |
| Syntek Integrated Camera                            | 6         | 2.54%   |
| Lite-On HP HD Camera                                | 5         | 2.12%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.69%   |
| Quanta HD Webcam                                    | 4         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.69%   |
| Acer Lenovo EasyCamera                              | 4         | 1.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.27%   |
| Sunplus HD 720P webcam                              | 3         | 1.27%   |
| Realtek Lenovo EasyCamera                           | 3         | 1.27%   |
| Logitech Webcam C270                                | 3         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.27%   |
| Chicony Integrated HP HD Webcam                     | 3         | 1.27%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.27%   |
| Chicony HP Webcam                                   | 3         | 1.27%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.27%   |
| Suyin WebCam                                        | 2         | 0.85%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.85%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 0.85%   |
| Sunplus HD WebCam                                   | 2         | 0.85%   |
| Sunplus ASUS Webcam                                 | 2         | 0.85%   |
| Realtek Integrated Webcam                           | 2         | 0.85%   |
| Realtek EasyCamera                                  | 2         | 0.85%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 0.85%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.85%   |
| Quanta HP HD Camera                                 | 2         | 0.85%   |
| Quanta HD User Facing                               | 2         | 0.85%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.85%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.85%   |
| Microdia Camera                                     | 2         | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.85%   |
| Logitech Webcam C170                                | 2         | 0.85%   |
| Lite-On Integrated Camera                           | 2         | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.85%   |
| Chicony USB 2.0 Camera                              | 2         | 0.85%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.85%   |
| Chicony EasyCamera                                  | 2         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.85%   |
| Anker PowerConf C300                                | 2         | 0.85%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.85%   |
| Acer Integrated Camera                              | 2         | 0.85%   |
| Acer EasyCamera                                     | 2         | 0.85%   |
| Z-Star Webcam                                       | 1         | 0.42%   |
| Trust Full HD Webcam                                | 1         | 0.42%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.42%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.42%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.42%   |
| Syntek EasyCamera                                   | 1         | 0.42%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.42%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.42%   |
| Sunplus Integrated Camera                           | 1         | 0.42%   |
| Sunplus Canyon CNS-CWC5 Webcam                      | 1         | 0.42%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.42%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 66.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 262       | 71.78%  |
| 1     | 82        | 22.47%  |
| 2     | 18        | 4.93%   |
| 3     | 3         | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 41.46%  |
| Graphics card            | 27        | 21.95%  |
| Net/wireless             | 13        | 10.57%  |
| Multimedia controller    | 7         | 5.69%   |
| Chipcard                 | 5         | 4.07%   |
| Communication controller | 4         | 3.25%   |
| Unassigned class         | 3         | 2.44%   |
| Card reader              | 3         | 2.44%   |
| Bluetooth                | 3         | 2.44%   |
| Camera                   | 2         | 1.63%   |
| Storage/raid             | 1         | 0.81%   |
| Storage/ide              | 1         | 0.81%   |
| Storage                  | 1         | 0.81%   |
| Sound                    | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |

