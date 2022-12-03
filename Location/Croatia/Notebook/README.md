Linux in Croatia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 395

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| Acer          | Aspire A317-53              | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| HP            | Pavilion Notebook           | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Acer          | Aspire A515-56G             | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| HP            | 250 G8 Notebook PC          | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| Chuwi         | GemiBook Pro                | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Dell          | Vostro 3500                 | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| HP            | ProBook 4530s               | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Acer          | Aspire A515-51G             | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Dell          | XPS 13 9310                 | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| Apple         | MacBookPro11,4              | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | B590 20208                  | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Dell          | XPS 13 9310                 | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| Dell          | Inspiron N5110              | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| SHENZHEN X... | ST106                       | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| Toshiba       | Satellite P200              | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| HUAWEI        | WRTB-WXX9                   | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Dell          | Inspiron N5110              | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| Acer          | Aspire 6930G                | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| HP            | 255 G7 Notebook PC          | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Acer          | Aspire F5-571G              | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Acer          | Aspire A315-34              | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| Acer          | Aspire F5-573G              | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| Dell          | XPS 13 9380                 | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Acer          | Aspire A315-41              | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| HP            | 250 G5 Notebook PC          | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| Dell          | Latitude E6430              | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| Dell          | Vostro 3578                 | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| Acer          | Aspire A315-21              | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| Acer          | Aspire 7739G                | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| Dell          | XPS 15 7590                 | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Toshiba       | Satellite C55-A-1M7         | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| Dell          | XPS 15 9570                 | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| HP            | ProBook 450 G7              | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| HP            | EliteBook 850 G6            | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| HP            | ProBook 430 G3              | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| HP            | EliteBook 850 G6            | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| HP            | ProBook 430 G3              | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Dell          | Precision 5530              | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Notebook      | MAM2080                     | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Acer          | Swift SF314-52              | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Lenovo        | G500 20236                  | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Toshiba       | Satellite L50-B             | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| eMachines     | G725                        | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| Acer          | Aspire A315-51              | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| Medion        | P6618                       | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| HP            | Pavilion g6                 | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | Laptop 17-ca0xxx            | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| Toshiba       | Satellite A300              | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASUSTek       | G750JZ                      | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Acer          | Aspire A515-51G             | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| HP            | Laptop 17-ca0xxx            | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | Laptop 17-ca0xxx            | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| HP            | Unknown                     | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | X540UA                      | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Acer          | Aspire 5715Z                | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| HP            | ProBook 450 G4              | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| HP            | EliteBook 2540p             | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Samsung       | N150/N210/N220              | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 49        | 17.07%  |
| Ubuntu 18.04      | 17        | 5.92%   |
| Debian 11         | 9         | 3.14%   |
| Ubuntu 22.04      | 8         | 2.79%   |
| Pop!_OS 21.04     | 7         | 2.44%   |
| OpenMandriva 4.3  | 7         | 2.44%   |
| Fedora 36         | 7         | 2.44%   |
| Pop!_OS 20.04     | 6         | 2.09%   |
| Ubuntu 19.04      | 5         | 1.74%   |
| Fedora 35         | 5         | 1.74%   |
| Arch Rolling      | 5         | 1.74%   |
| Ubuntu 21.04      | 4         | 1.39%   |
| Pop!_OS 20.10     | 4         | 1.39%   |
| Linux Mint 20.3   | 4         | 1.39%   |
| Linux Mint 20.2   | 4         | 1.39%   |
| KDE neon 20.04    | 4         | 1.39%   |
| Endless 3.7.8     | 4         | 1.39%   |
| Arch              | 4         | 1.39%   |
| Zorin 16          | 3         | 1.05%   |
| Zorin 15          | 3         | 1.05%   |
| Ubuntu 20.10      | 3         | 1.05%   |
| Ubuntu 19.10      | 3         | 1.05%   |
| Ubuntu 18.10      | 3         | 1.05%   |
| ROSA R10          | 3         | 1.05%   |
| Pop!_OS 22.04     | 3         | 1.05%   |
| Pop!_OS 21.10     | 3         | 1.05%   |
| OpenMandriva 4.2  | 3         | 1.05%   |
| Endless 3.9.5     | 3         | 1.05%   |
| Endless 3.9.4     | 3         | 1.05%   |
| Ubuntu 21.10      | 2         | 0.7%    |
| OpenMandriva 4.50 | 2         | 0.7%    |
| Nobara 36         | 2         | 0.7%    |
| Manjaro 21.0.7    | 2         | 0.7%    |
| Manjaro 21.0      | 2         | 0.7%    |
| Manjaro 20.2.1    | 2         | 0.7%    |
| Manjaro 20.2      | 2         | 0.7%    |
| Manjaro 20.1.2    | 2         | 0.7%    |
| Manjaro 18.1.5    | 2         | 0.7%    |
| Linux Mint 20.1   | 2         | 0.7%    |
| Linux Mint 20     | 2         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 84        | 32.56%  |
| Pop!_OS       | 22        | 8.53%   |
| Endless       | 21        | 8.14%   |
| Linux Mint    | 17        | 6.59%   |
| Fedora        | 17        | 6.59%   |
| Manjaro       | 14        | 5.43%   |
| OpenMandriva  | 12        | 4.65%   |
| Debian        | 11        | 4.26%   |
| Kubuntu       | 9         | 3.49%   |
| Arch          | 9         | 3.49%   |
| Zorin         | 6         | 2.33%   |
| ROSA          | 6         | 2.33%   |
| KDE neon      | 6         | 2.33%   |
| Kali          | 3         | 1.16%   |
| Elementary    | 3         | 1.16%   |
| Ubuntu MATE   | 2         | 0.78%   |
| openSUSE      | 2         | 0.78%   |
| Nobara        | 2         | 0.78%   |
| EndeavourOS   | 2         | 0.78%   |
| ArcoLinux     | 2         | 0.78%   |
| Xubuntu       | 1         | 0.39%   |
| Ubuntu Unity  | 1         | 0.39%   |
| Ubuntu Budgie | 1         | 0.39%   |
| Parrot        | 1         | 0.39%   |
| LMDE          | 1         | 0.39%   |
| LinuxFX       | 1         | 0.39%   |
| Gentoo        | 1         | 0.39%   |
| CentOS        | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 2.25%   |
| 5.8.0-14-generic         | 6         | 1.93%   |
| 5.11.0-38-generic        | 6         | 1.93%   |
| 5.4.0-42-generic         | 5         | 1.61%   |
| 5.11.0-7620-generic      | 5         | 1.61%   |
| 5.3.0-28-generic         | 4         | 1.29%   |
| 5.13.0-30-generic        | 4         | 1.29%   |
| 5.8.16-2-MANJARO         | 3         | 0.96%   |
| 5.8.0-7630-generic       | 3         | 0.96%   |
| 5.8.0-59-generic         | 3         | 0.96%   |
| 5.8.0-43-generic         | 3         | 0.96%   |
| 5.4.0-52-generic         | 3         | 0.96%   |
| 5.4.0-48-generic         | 3         | 0.96%   |
| 5.4.0-47-generic         | 3         | 0.96%   |
| 5.4.0-37-generic         | 3         | 0.96%   |
| 5.4.0-29-generic         | 3         | 0.96%   |
| 5.4.0-19-generic         | 3         | 0.96%   |
| 5.15.0-40-generic        | 3         | 0.96%   |
| 5.13.0-7620-generic      | 3         | 0.96%   |
| 5.13.0-52-generic        | 3         | 0.96%   |
| 5.11.0-41-generic        | 3         | 0.96%   |
| 5.11.0-40-generic        | 3         | 0.96%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.96%   |
| 4.18.0-18-generic        | 3         | 0.96%   |
| 6.0.5-200.fc36.x86_64    | 2         | 0.64%   |
| 5.9.16-1-MANJARO         | 2         | 0.64%   |
| 5.8.0-49-generic         | 2         | 0.64%   |
| 5.8.0-48-generic         | 2         | 0.64%   |
| 5.4.0-91-generic         | 2         | 0.64%   |
| 5.4.0-84-generic         | 2         | 0.64%   |
| 5.4.0-7642-generic       | 2         | 0.64%   |
| 5.4.0-58-generic         | 2         | 0.64%   |
| 5.4.0-54-generic         | 2         | 0.64%   |
| 5.4.0-40-generic         | 2         | 0.64%   |
| 5.4.0-128-generic        | 2         | 0.64%   |
| 5.3.0-23-generic         | 2         | 0.64%   |
| 5.16.11-76051611-generic | 2         | 0.64%   |
| 5.15.0-47-generic        | 2         | 0.64%   |
| 5.15.0-46-generic        | 2         | 0.64%   |
| 5.15.0-27-generic        | 2         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 52        | 17.69%  |
| 5.11.0  | 31        | 10.54%  |
| 5.8.0   | 20        | 6.8%    |
| 5.15.0  | 16        | 5.44%   |
| 5.13.0  | 16        | 5.44%   |
| 4.15.0  | 15        | 5.1%    |
| 5.3.0   | 11        | 3.74%   |
| 5.0.0   | 10        | 3.4%    |
| 4.18.0  | 10        | 3.4%    |
| 5.10.0  | 9         | 3.06%   |
| 5.16.7  | 8         | 2.72%   |
| 5.9.16  | 4         | 1.36%   |
| 5.8.16  | 3         | 1.02%   |
| 5.19.0  | 3         | 1.02%   |
| 5.10.14 | 3         | 1.02%   |
| 4.9.60  | 3         | 1.02%   |
| 4.19.0  | 3         | 1.02%   |
| 6.0.5   | 2         | 0.68%   |
| 5.9.11  | 2         | 0.68%   |
| 5.5.0   | 2         | 0.68%   |
| 5.16.11 | 2         | 0.68%   |
| 5.15.8  | 2         | 0.68%   |
| 5.14.0  | 2         | 0.68%   |
| 5.9.9   | 1         | 0.34%   |
| 5.9.1   | 1         | 0.34%   |
| 5.8.6   | 1         | 0.34%   |
| 5.7.11  | 1         | 0.34%   |
| 5.6.6   | 1         | 0.34%   |
| 5.6.2   | 1         | 0.34%   |
| 5.6.19  | 1         | 0.34%   |
| 5.6.0   | 1         | 0.34%   |
| 5.4.74  | 1         | 0.34%   |
| 5.4.17  | 1         | 0.34%   |
| 5.4.13  | 1         | 0.34%   |
| 5.3.8   | 1         | 0.34%   |
| 5.3.18  | 1         | 0.34%   |
| 5.2.10  | 1         | 0.34%   |
| 5.19.5  | 1         | 0.34%   |
| 5.19.3  | 1         | 0.34%   |
| 5.19.14 | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 55        | 19.03%  |
| 5.11    | 36        | 12.46%  |
| 5.8     | 24        | 8.3%    |
| 5.15    | 22        | 7.61%   |
| 5.13    | 19        | 6.57%   |
| 5.10    | 17        | 5.88%   |
| 4.15    | 15        | 5.19%   |
| 5.16    | 13        | 4.5%    |
| 5.3     | 12        | 4.15%   |
| 5.0     | 11        | 3.81%   |
| 4.18    | 10        | 3.46%   |
| 5.9     | 8         | 2.77%   |
| 5.19    | 8         | 2.77%   |
| 5.18    | 5         | 1.73%   |
| 5.17    | 5         | 1.73%   |
| 4.9     | 5         | 1.73%   |
| 5.6     | 4         | 1.38%   |
| 5.14    | 3         | 1.04%   |
| 4.19    | 3         | 1.04%   |
| 6.0     | 2         | 0.69%   |
| 5.5     | 2         | 0.69%   |
| 5.12    | 2         | 0.69%   |
| 5.7     | 1         | 0.35%   |
| 5.2     | 1         | 0.35%   |
| 5.1     | 1         | 0.35%   |
| 4.17    | 1         | 0.35%   |
| 4.16    | 1         | 0.35%   |
| 4.12    | 1         | 0.35%   |
| 4.1     | 1         | 0.35%   |
| 3.10    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 246       | 98.01%  |
| i686   | 5         | 1.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 128       | 48.12%  |
| KDE5            | 44        | 16.54%  |
| Unknown         | 37        | 13.91%  |
| X-Cinnamon      | 12        | 4.51%   |
| XFCE            | 8         | 3.01%   |
| KDE             | 6         | 2.26%   |
| Cinnamon        | 6         | 2.26%   |
| MATE            | 5         | 1.88%   |
| KDE4            | 4         | 1.5%    |
| GNOME Flashback | 4         | 1.5%    |
| Pantheon        | 3         | 1.13%   |
| DWM             | 3         | 1.13%   |
| Budgie          | 2         | 0.75%   |
| Unity           | 1         | 0.38%   |
| LXQt            | 1         | 0.38%   |
| i3              | 1         | 0.38%   |
| bspwm           | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 203       | 75.46%  |
| Wayland | 35        | 13.01%  |
| Unknown | 27        | 10.04%  |
| Tty     | 4         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 125       | 48.45%  |
| GDM     | 50        | 19.38%  |
| SDDM    | 38        | 14.73%  |
| GDM3    | 17        | 6.59%   |
| LightDM | 14        | 5.43%   |
| TDM     | 10        | 3.88%   |
| KDM     | 3         | 1.16%   |
| Ly      | 1         | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 137       | 52.9%   |
| hr_HR   | 59        | 22.78%  |
| Unknown | 38        | 14.67%  |
| en_GB   | 11        | 4.25%   |
| de_DE   | 6         | 2.32%   |
| C       | 4         | 1.54%   |
| pl_PL   | 1         | 0.39%   |
| hr_BA   | 1         | 0.39%   |
| fr_FR   | 1         | 0.39%   |
| en_DE   | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 153       | 59.07%  |
| BIOS | 106       | 40.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 202       | 77.99%  |
| Btrfs   | 16        | 6.18%   |
| Unknown | 16        | 6.18%   |
| Overlay | 15        | 5.79%   |
| Zfs     | 4         | 1.54%   |
| Xfs     | 4         | 1.54%   |
| Jfs     | 1         | 0.39%   |
| Ext2    | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 136       | 53.54%  |
| GPT     | 91        | 35.83%  |
| MBR     | 27        | 10.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 237       | 92.94%  |
| Yes       | 18        | 7.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 198       | 77.65%  |
| Yes       | 57        | 22.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 64        | 25.5%   |
| Hewlett-Packard         | 52        | 20.72%  |
| Acer                    | 43        | 17.13%  |
| ASUSTek Computer        | 32        | 12.75%  |
| Dell                    | 29        | 11.55%  |
| Toshiba                 | 7         | 2.79%   |
| Apple                   | 5         | 1.99%   |
| Samsung Electronics     | 3         | 1.2%    |
| eMachines               | 3         | 1.2%    |
| HUAWEI                  | 2         | 0.8%    |
| Fujitsu Siemens         | 2         | 0.8%    |
| TUXEDO                  | 1         | 0.4%    |
| System76                | 1         | 0.4%    |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.4%    |
| Razer                   | 1         | 0.4%    |
| Pretech                 | 1         | 0.4%    |
| Notebook                | 1         | 0.4%    |
| Medion                  | 1         | 0.4%    |
| Gigabyte Technology     | 1         | 0.4%    |
| Chuwi                   | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-21                        | 4         | 1.59%   |
| Lenovo G710 20252                          | 3         | 1.2%    |
| Acer Aspire A515-51G                       | 3         | 1.2%    |
| Lenovo Z50-70 20354                        | 2         | 0.8%    |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.8%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.8%    |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.8%    |
| Lenovo G40-30 80FY                         | 2         | 0.8%    |
| HP ProBook 450 G7                          | 2         | 0.8%    |
| HP EliteBook 8560p                         | 2         | 0.8%    |
| HP EliteBook 850 G6                        | 2         | 0.8%    |
| HP 2000                                    | 2         | 0.8%    |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.8%    |
| Dell XPS 13 9310                           | 2         | 0.8%    |
| Dell Vostro 3500                           | 2         | 0.8%    |
| ASUS X751NV                                | 2         | 0.8%    |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.8%    |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.8%    |
| ASUS N56VZ                                 | 2         | 0.8%    |
| Acer Aspire E5-771G                        | 2         | 0.8%    |
| Acer Aspire A715-72G                       | 2         | 0.8%    |
| Acer Aspire 7739G                          | 2         | 0.8%    |
| Unknown                                    | 2         | 0.8%    |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.4%    |
| Toshiba Satellite P200                     | 1         | 0.4%    |
| Toshiba Satellite L750                     | 1         | 0.4%    |
| Toshiba Satellite L50-B                    | 1         | 0.4%    |
| Toshiba Satellite C850-1GD                 | 1         | 0.4%    |
| Toshiba Satellite C55-A-1M7                | 1         | 0.4%    |
| Toshiba Satellite A300                     | 1         | 0.4%    |
| Toshiba Encore                             | 1         | 0.4%    |
| System76 Oryx Pro                          | 1         | 0.4%    |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.4%    |
| Samsung N150/N210/N220                     | 1         | 0.4%    |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.4%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.4%    |
| Razer Blade                                | 1         | 0.4%    |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.4%    |
| Notebook MAM2080                           | 1         | 0.4%    |
| Medion P6618                               | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 36        | 14.34%  |
| Lenovo ThinkPad               | 28        | 11.16%  |
| HP EliteBook                  | 13        | 5.18%   |
| HP ProBook                    | 10        | 3.98%   |
| HP Pavilion                   | 8         | 3.19%   |
| ASUS VivoBook                 | 8         | 3.19%   |
| Lenovo Legion                 | 7         | 2.79%   |
| Dell XPS                      | 7         | 2.79%   |
| Dell Vostro                   | 7         | 2.79%   |
| Dell Latitude                 | 7         | 2.79%   |
| Toshiba Satellite             | 6         | 2.39%   |
| Lenovo ThinkBook              | 6         | 2.39%   |
| Lenovo IdeaPad                | 6         | 2.39%   |
| Dell Inspiron                 | 5         | 1.99%   |
| Acer Swift                    | 5         | 1.99%   |
| HP Laptop                     | 4         | 1.59%   |
| HP 250                        | 4         | 1.59%   |
| Lenovo G710                   | 3         | 1.2%    |
| HP Compaq                     | 3         | 1.2%    |
| ASUS ZenBook                  | 3         | 1.2%    |
| Lenovo Z50-70                 | 2         | 0.8%    |
| Lenovo G40-30                 | 2         | 0.8%    |
| Lenovo B590                   | 2         | 0.8%    |
| HP OMEN                       | 2         | 0.8%    |
| HP 2000                       | 2         | 0.8%    |
| Fujitsu Siemens ESPRIMO       | 2         | 0.8%    |
| ASUS X751NV                   | 2         | 0.8%    |
| ASUS ROG                      | 2         | 0.8%    |
| ASUS N56VZ                    | 2         | 0.8%    |
| Unknown                       | 2         | 0.8%    |
| TUXEDO Pulse                  | 1         | 0.4%    |
| Toshiba Encore                | 1         | 0.4%    |
| System76 Oryx                 | 1         | 0.4%    |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.4%    |
| Samsung N150                  | 1         | 0.4%    |
| Samsung 300E4C                | 1         | 0.4%    |
| Samsung 300E4A                | 1         | 0.4%    |
| Razer Blade                   | 1         | 0.4%    |
| Pretech EVE                   | 1         | 0.4%    |
| Notebook MAM2080              | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 35        | 13.94%  |
| 2019 | 25        | 9.96%   |
| 2017 | 24        | 9.56%   |
| 2020 | 23        | 9.16%   |
| 2013 | 20        | 7.97%   |
| 2021 | 18        | 7.17%   |
| 2016 | 18        | 7.17%   |
| 2014 | 17        | 6.77%   |
| 2011 | 17        | 6.77%   |
| 2012 | 12        | 4.78%   |
| 2007 | 10        | 3.98%   |
| 2015 | 9         | 3.59%   |
| 2008 | 8         | 3.19%   |
| 2009 | 6         | 2.39%   |
| 2010 | 5         | 1.99%   |
| 2022 | 2         | 0.8%    |
| 2006 | 2         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 251       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 225       | 89.29%  |
| Enabled  | 27        | 10.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 251       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 85        | 33.2%   |
| 8.01-16.0   | 47        | 18.36%  |
| 3.01-4.0    | 46        | 17.97%  |
| 16.01-24.0  | 39        | 15.23%  |
| 32.01-64.0  | 17        | 6.64%   |
| 1.01-2.0    | 11        | 4.3%    |
| 24.01-32.0  | 6         | 2.34%   |
| 2.01-3.0    | 4         | 1.56%   |
| 64.01-256.0 | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 100       | 34.72%  |
| 2.01-3.0   | 65        | 22.57%  |
| 4.01-8.0   | 45        | 15.63%  |
| 3.01-4.0   | 42        | 14.58%  |
| 0.51-1.0   | 17        | 5.9%    |
| 8.01-16.0  | 15        | 5.21%   |
| 16.01-24.0 | 2         | 0.69%   |
| 0.01-0.5   | 2         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 73.26%  |
| 2      | 58        | 22.48%  |
| 3      | 5         | 1.94%   |
| 0      | 3         | 1.16%   |
| 6      | 1         | 0.39%   |
| 5      | 1         | 0.39%   |
| 4      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 67.98%  |
| Yes       | 81        | 32.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 84.13%  |
| No        | 40        | 15.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 98.41%  |
| No        | 4         | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 80.86%  |
| No        | 49        | 19.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 251       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 166       | 57.44%  |
| Split               | 12        | 4.15%   |
| Rijeka              | 12        | 4.15%   |
| Varaždin           | 7         | 2.42%   |
| Velika Gorica       | 5         | 1.73%   |
| Pula                | 5         | 1.73%   |
| Zaprešić          | 3         | 1.04%   |
| Petrinja            | 3         | 1.04%   |
| Jesenice            | 3         | 1.04%   |
| Čakovec            | 3         | 1.04%   |
| Zadar               | 2         | 0.69%   |
| Rovinj              | 2         | 0.69%   |
| Osijek              | 2         | 0.69%   |
| Omiš               | 2         | 0.69%   |
| Novska              | 2         | 0.69%   |
| Krizevci            | 2         | 0.69%   |
| Komiža             | 2         | 0.69%   |
| Kastav              | 2         | 0.69%   |
| Bjelovar            | 2         | 0.69%   |
| Đakovo             | 1         | 0.35%   |
| Zminj               | 1         | 0.35%   |
| Zabok               | 1         | 0.35%   |
| Virovitica          | 1         | 0.35%   |
| Vinkovci            | 1         | 0.35%   |
| Varazdinske Toplice | 1         | 0.35%   |
| Umag                | 1         | 0.35%   |
| Udbinja             | 1         | 0.35%   |
| Trenkovo            | 1         | 0.35%   |
| Sveti Ivan Zelina   | 1         | 0.35%   |
| Sveta Marija        | 1         | 0.35%   |
| Supetar             | 1         | 0.35%   |
| Sracinec            | 1         | 0.35%   |
| Šibenik            | 1         | 0.35%   |
| Sesvete             | 1         | 0.35%   |
| Senj                | 1         | 0.35%   |
| Samobor             | 1         | 0.35%   |
| Rokovci             | 1         | 0.35%   |
| Požega             | 1         | 0.35%   |
| Pitomaca            | 1         | 0.35%   |
| Otocac              | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 53        | 67     | 17.1%   |
| WDC                   | 37        | 46     | 11.94%  |
| Kingston              | 31        | 40     | 10%     |
| Seagate               | 26        | 48     | 8.39%   |
| SK hynix              | 23        | 34     | 7.42%   |
| Toshiba               | 20        | 21     | 6.45%   |
| SanDisk               | 20        | 25     | 6.45%   |
| Micron Technology     | 13        | 14     | 4.19%   |
| Unknown               | 10        | 10     | 3.23%   |
| Intel                 | 9         | 15     | 2.9%    |
| Hitachi               | 9         | 9      | 2.9%    |
| HGST                  | 8         | 8      | 2.58%   |
| Crucial               | 7         | 12     | 2.26%   |
| Fujitsu               | 5         | 6      | 1.61%   |
| Apple                 | 5         | 5      | 1.61%   |
| A-DATA Technology     | 5         | 5      | 1.61%   |
| Silicon Motion        | 3         | 4      | 0.97%   |
| LITEON                | 3         | 4      | 0.97%   |
| Transcend             | 2         | 3      | 0.65%   |
| Lenovo                | 2         | 3      | 0.65%   |
| KingFast              | 2         | 4      | 0.65%   |
| Intenso               | 2         | 3      | 0.65%   |
| Verbatim              | 1         | 1      | 0.32%   |
| UMIS                  | 1         | 1      | 0.32%   |
| StoreJet              | 1         | 1      | 0.32%   |
| Realtek Semiconductor | 1         | 3      | 0.32%   |
| Phison                | 1         | 1      | 0.32%   |
| Patriot               | 1         | 1      | 0.32%   |
| Netac                 | 1         | 1      | 0.32%   |
| Mass                  | 1         | 1      | 0.32%   |
| Lite-On               | 1         | 1      | 0.32%   |
| LaCie                 | 1         | 1      | 0.32%   |
| KIOXIA                | 1         | 1      | 0.32%   |
| Gigabyte Technology   | 1         | 1      | 0.32%   |
| Emtec                 | 1         | 1      | 0.32%   |
| Corsair               | 1         | 1      | 0.32%   |
| AMD                   | 1         | 3      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 8         | 2.55%   |
| Kingston SA400S37240G 240GB SSD         | 7         | 2.23%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 1.91%   |
| SanDisk NVMe SSD Drive 512GB            | 5         | 1.59%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 1.27%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.96%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.96%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.96%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 0.96%   |
| Intel NVMe SSD Drive 256GB              | 3         | 0.96%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.96%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.64%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.64%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.64%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 2         | 0.64%   |
| Unknown SD/MMC/MS PRO 8GB               | 2         | 0.64%   |
| Unknown MMC Card  32GB                  | 2         | 0.64%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.64%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.64%   |
| SK hynix NVMe SSD Drive 512GB           | 2         | 0.64%   |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.64%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.64%   |
| SK hynix HFM512GDJTNI-82A0A 512GB       | 2         | 0.64%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.64%   |
| Seagate ST9500325AS 500GB               | 2         | 0.64%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB          | 2         | 0.64%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 2         | 0.64%   |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.64%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB  | 2         | 0.64%   |
| Samsung PM9A1 NVMe 2048GB               | 2         | 0.64%   |
| Samsung PM981 NVMe 512GB                | 2         | 0.64%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD    | 2         | 0.64%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 0.64%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 31     | 28.26%  |
| Seagate             | 26        | 37     | 28.26%  |
| Toshiba             | 14        | 15     | 15.22%  |
| Hitachi             | 9         | 9      | 9.78%   |
| HGST                | 8         | 8      | 8.7%    |
| Fujitsu             | 5         | 6      | 5.43%   |
| Unknown             | 2         | 2      | 2.17%   |
| Samsung Electronics | 1         | 2      | 1.09%   |
| Intenso             | 1         | 2      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 27        | 32     | 25%     |
| Samsung Electronics | 18        | 26     | 16.67%  |
| SanDisk             | 11        | 15     | 10.19%  |
| Micron Technology   | 10        | 11     | 9.26%   |
| SK hynix            | 7         | 12     | 6.48%   |
| Crucial             | 7         | 12     | 6.48%   |
| WDC                 | 5         | 6      | 4.63%   |
| Apple               | 5         | 5      | 4.63%   |
| A-DATA Technology   | 5         | 5      | 4.63%   |
| LITEON              | 2         | 3      | 1.85%   |
| Intel               | 2         | 3      | 1.85%   |
| Transcend           | 1         | 2      | 0.93%   |
| Toshiba             | 1         | 1      | 0.93%   |
| StoreJet            | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| Emtec               | 1         | 1      | 0.93%   |
| AMD                 | 1         | 3      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 100       | 142    | 33.67%  |
| NVMe    | 94        | 126    | 31.65%  |
| HDD     | 90        | 112    | 30.3%   |
| MMC     | 7         | 7      | 2.36%   |
| Unknown | 6         | 18     | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 167       | 247    | 60.29%  |
| NVMe | 94        | 126    | 33.94%  |
| SAS  | 9         | 25     | 3.25%   |
| MMC  | 7         | 7      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 132       | 175    | 69.11%  |
| 0.51-1.0   | 52        | 70     | 27.23%  |
| 1.01-2.0   | 6         | 7      | 3.14%   |
| 2.01-3.0   | 1         | 2      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 88        | 33.46%  |
| 251-500        | 65        | 24.71%  |
| 501-1000       | 38        | 14.45%  |
| 1001-2000      | 23        | 8.75%   |
| 51-100         | 16        | 6.08%   |
| 1-20           | 13        | 4.94%   |
| 21-50          | 8         | 3.04%   |
| Unknown        | 7         | 2.66%   |
| 2001-3000      | 3         | 1.14%   |
| More than 3000 | 2         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 94        | 33.1%   |
| 21-50          | 66        | 23.24%  |
| 101-250        | 36        | 12.68%  |
| 51-100         | 36        | 12.68%  |
| 251-500        | 20        | 7.04%   |
| 501-1000       | 20        | 7.04%   |
| Unknown        | 7         | 2.46%   |
| 1001-2000      | 4         | 1.41%   |
| More than 3000 | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 5.26%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 5.26%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 5.26%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 5.26%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.26%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 5.26%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 5.26%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 5.26%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 5.26%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 5.26%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 5.26%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 5.26%   |
| Crucial CT1024M550SSD1 1024GB        | 1         | 1      | 5.26%   |
| A-DATA Technology SU630 240GB SSD    | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 4      | 22.22%  |
| WDC               | 3         | 3      | 16.67%  |
| HGST              | 3         | 3      | 16.67%  |
| Hitachi           | 2         | 2      | 11.11%  |
| Toshiba           | 1         | 1      | 5.56%   |
| SK hynix          | 1         | 1      | 5.56%   |
| SanDisk           | 1         | 2      | 5.56%   |
| LITEON            | 1         | 1      | 5.56%   |
| Crucial           | 1         | 1      | 5.56%   |
| A-DATA Technology | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| HGST    | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 70.59%  |
| SSD  | 5         | 7      | 29.41%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 154       | 243    | 57.46%  |
| Works    | 97        | 143    | 36.19%  |
| Malfunc  | 17        | 19     | 6.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 57.64%  |
| Samsung Electronics              | 37        | 11.78%  |
| AMD                              | 32        | 10.19%  |
| SK hynix                         | 16        | 5.1%    |
| SanDisk                          | 15        | 4.78%   |
| Toshiba America Info Systems     | 6         | 1.91%   |
| Kingston Technology Company      | 4         | 1.27%   |
| Silicon Motion                   | 3         | 0.96%   |
| Micron Technology                | 3         | 0.96%   |
| Silicon Integrated Systems [SiS] | 2         | 0.64%   |
| Phison Electronics               | 2         | 0.64%   |
| Nvidia                           | 2         | 0.64%   |
| Lite-On Technology               | 2         | 0.64%   |
| Lenovo                           | 2         | 0.64%   |
| KIOXIA                           | 2         | 0.64%   |
| VIA Technologies                 | 1         | 0.32%   |
| Union Memory (Shenzhen)          | 1         | 0.32%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| Marvell Technology Group         | 1         | 0.32%   |
| JMicron Technology               | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 8.9%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 8.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 4.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 15        | 4.45%   |
| Samsung NVMe SSD Controller 980                                                  | 14        | 4.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 3.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.37%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 2.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 1.78%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 1.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.48%   |
| SK hynix BC511                                                                   | 4         | 1.19%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.19%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.89%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.89%   |
| Samsung Electronics SATA controller                                              | 3         | 0.89%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.89%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.59%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.59%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.59%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 189       | 58.33%  |
| NVMe | 95        | 29.32%  |
| IDE  | 23        | 7.1%    |
| RAID | 17        | 5.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 205       | 81.67%  |
| AMD    | 46        | 18.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 4.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 3.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 2.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 2.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.59%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.59%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.59%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 1.2%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.2%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.2%    |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.2%    |
| Intel Pentium M processor 1.86GHz             | 2         | 0.8%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.8%    |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.8%    |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.8%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.8%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.8%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.8%    |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.8%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 76        | 30.28%  |
| Intel Core i7           | 41        | 16.33%  |
| Intel Core i3           | 17        | 6.77%   |
| Intel Pentium           | 16        | 6.37%   |
| Intel Core 2 Duo        | 16        | 6.37%   |
| Other                   | 15        | 5.98%   |
| AMD Ryzen 5             | 15        | 5.98%   |
| AMD Ryzen 7             | 10        | 3.98%   |
| Intel Celeron           | 6         | 2.39%   |
| Intel Pentium Dual      | 4         | 1.59%   |
| Intel Atom              | 4         | 1.59%   |
| AMD Ryzen 3             | 4         | 1.59%   |
| AMD A6                  | 4         | 1.59%   |
| Intel Pentium Silver    | 3         | 1.2%    |
| Intel Pentium Dual-Core | 3         | 1.2%    |
| Intel Core i9           | 3         | 1.2%    |
| AMD E                   | 3         | 1.2%    |
| Intel Pentium M         | 2         | 0.8%    |
| AMD Ryzen 9             | 2         | 0.8%    |
| AMD E1                  | 2         | 0.8%    |
| Intel Celeron M         | 1         | 0.4%    |
| AMD Turion 64 X2 Mobile | 1         | 0.4%    |
| AMD Ryzen 7 PRO         | 1         | 0.4%    |
| AMD Athlon              | 1         | 0.4%    |
| AMD A4                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 127       | 50.6%   |
| 4       | 85        | 33.86%  |
| 6       | 18        | 7.17%   |
| 8       | 15        | 5.98%   |
| 1       | 4         | 1.59%   |
| 14      | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 250       | 99.6%   |
| Unknown | 1         | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 178       | 70.92%  |
| 1       | 72        | 28.69%  |
| Unknown | 1         | 0.4%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 240       | 94.86%  |
| Unknown        | 9         | 3.56%   |
| 32-bit         | 4         | 1.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 20.53%  |
| 0x806ea    | 16        | 6.08%   |
| 0x806e9    | 14        | 5.32%   |
| 0x306c3    | 13        | 4.94%   |
| 0x306a9    | 13        | 4.94%   |
| 0x40651    | 12        | 4.56%   |
| 0x906ea    | 10        | 3.8%    |
| 0x806ec    | 10        | 3.8%    |
| 0x806c1    | 8         | 3.04%   |
| 0x6fd      | 8         | 3.04%   |
| 0x206a7    | 6         | 2.28%   |
| 0x1067a    | 6         | 2.28%   |
| 0x0a50000c | 6         | 2.28%   |
| 0x306d4    | 5         | 1.9%    |
| 0x06006705 | 5         | 1.9%    |
| 0x406e3    | 4         | 1.52%   |
| 0x30678    | 4         | 1.52%   |
| 0x10676    | 4         | 1.52%   |
| 0x08600106 | 4         | 1.52%   |
| 0x08600103 | 4         | 1.52%   |
| 0x08108109 | 4         | 1.52%   |
| 0x0810100b | 4         | 1.52%   |
| 0xa0652    | 3         | 1.14%   |
| 0x706e5    | 3         | 1.14%   |
| 0x506c9    | 3         | 1.14%   |
| 0x20655    | 3         | 1.14%   |
| 0x08608103 | 3         | 1.14%   |
| 0x05000119 | 3         | 1.14%   |
| 0x906ed    | 2         | 0.76%   |
| 0x906e9    | 2         | 0.76%   |
| 0x806eb    | 2         | 0.76%   |
| 0x706a1    | 2         | 0.76%   |
| 0x6fb      | 2         | 0.76%   |
| 0x6d8      | 2         | 0.76%   |
| 0x406c4    | 2         | 0.76%   |
| 0x08108102 | 2         | 0.76%   |
| 0x906c0    | 1         | 0.38%   |
| 0x906a3    | 1         | 0.38%   |
| 0x6fa      | 1         | 0.38%   |
| 0x6e8      | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 68        | 27.09%  |
| Haswell          | 29        | 11.55%  |
| IvyBridge        | 17        | 6.77%   |
| TigerLake        | 12        | 4.78%   |
| Penryn           | 12        | 4.78%   |
| Zen 2            | 11        | 4.38%   |
| Core             | 11        | 4.38%   |
| Silvermont       | 10        | 3.98%   |
| SandyBridge      | 8         | 3.19%   |
| Zen+             | 7         | 2.79%   |
| Zen 3            | 7         | 2.79%   |
| Skylake          | 7         | 2.79%   |
| Broadwell        | 7         | 2.79%   |
| Excavator        | 6         | 2.39%   |
| Unknown          | 5         | 1.99%   |
| Zen              | 4         | 1.59%   |
| Westmere         | 4         | 1.59%   |
| IceLake          | 4         | 1.59%   |
| Bobcat           | 4         | 1.59%   |
| P6               | 3         | 1.2%    |
| Goldmont plus    | 3         | 1.2%    |
| Goldmont         | 3         | 1.2%    |
| CometLake        | 3         | 1.2%    |
| Tremont          | 1         | 0.4%    |
| Puma             | 1         | 0.4%    |
| K8 Hammer        | 1         | 0.4%    |
| Jaguar           | 1         | 0.4%    |
| Bonnell          | 1         | 0.4%    |
| Alderlake Hybrid | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 53.85%  |
| Nvidia                           | 85        | 25.15%  |
| AMD                              | 68        | 20.12%  |
| Silicon Integrated Systems [SiS] | 2         | 0.59%   |
| VIA Technologies                 | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 20        | 5.8%    |
| Intel HD Graphics 620                                                                    | 16        | 4.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.19%   |
| AMD Renoir                                                                               | 10        | 2.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 2.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.45%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.45%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.45%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.16%   |
| AMD Lucienne                                                                             | 4         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.87%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.87%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.87%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 3         | 0.87%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 41.04%  |
| Intel + Nvidia | 61        | 24.3%   |
| 1 x AMD        | 38        | 15.14%  |
| Intel + AMD    | 18        | 7.17%   |
| 1 x Nvidia     | 16        | 6.37%   |
| AMD + Nvidia   | 8         | 3.19%   |
| 2 x AMD        | 4         | 1.59%   |
| 1 x SiS        | 2         | 0.8%    |
| 1 x VIA        | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 202       | 80.16%  |
| Proprietary | 42        | 16.67%  |
| Unknown     | 8         | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 55.38%  |
| 1.01-2.0   | 37        | 14.23%  |
| 0.01-0.5   | 33        | 12.69%  |
| 3.01-4.0   | 27        | 10.38%  |
| 0.51-1.0   | 12        | 4.62%   |
| 7.01-8.0   | 4         | 1.54%   |
| 5.01-6.0   | 2         | 0.77%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 16.27%  |
| LG Display              | 45        | 15.25%  |
| BOE                     | 42        | 14.24%  |
| Chimei Innolux          | 37        | 12.54%  |
| Samsung Electronics     | 35        | 11.86%  |
| Dell                    | 24        | 8.14%   |
| Sharp                   | 9         | 3.05%   |
| Lenovo                  | 5         | 1.69%   |
| Goldstar                | 5         | 1.69%   |
| Chi Mei Optoelectronics | 5         | 1.69%   |
| Apple                   | 5         | 1.69%   |
| PANDA                   | 3         | 1.02%   |
| LG Philips              | 3         | 1.02%   |
| CSO                     | 3         | 1.02%   |
| AOC                     | 3         | 1.02%   |
| Quanta Display          | 2         | 0.68%   |
| InfoVision              | 2         | 0.68%   |
| Hewlett-Packard         | 2         | 0.68%   |
| Grundig                 | 2         | 0.68%   |
| BenQ                    | 2         | 0.68%   |
| Philips                 | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| NCS                     | 1         | 0.34%   |
| MSI                     | 1         | 0.34%   |
| InnoLux Display         | 1         | 0.34%   |
| Iiyama                  | 1         | 0.34%   |
| IBM                     | 1         | 0.34%   |
| HJW                     | 1         | 0.34%   |
| Fujitsu Siemens         | 1         | 0.34%   |
| Daewoo                  | 1         | 0.34%   |
| BOE Technology Group    | 1         | 0.34%   |
| Achieva Shimian         | 1         | 0.34%   |
| Acer                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.65%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.32%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.32%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 0.99%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 0.99%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                     | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.99%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.66%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch      | 2         | 0.66%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.66%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.66%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.66%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 2         | 0.66%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 2         | 0.66%   |
| Grundig WXGA GRU4448 1600x1200                                            | 2         | 0.66%   |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                     | 2         | 0.66%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.66%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.66%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 2         | 0.66%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch           | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.66%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 135       | 49.09%  |
| 1366x768 (WXGA)    | 49        | 17.82%  |
| 1600x900 (HD+)     | 23        | 8.36%   |
| 3840x2160 (4K)     | 14        | 5.09%   |
| 2560x1440 (QHD)    | 9         | 3.27%   |
| 1440x900 (WXGA+)   | 9         | 3.27%   |
| 1280x800 (WXGA)    | 6         | 2.18%   |
| 1920x1200 (WUXGA)  | 5         | 1.82%   |
| 1680x1050 (WSXGA+) | 5         | 1.82%   |
| 2560x1600          | 4         | 1.45%   |
| 2160x1440          | 3         | 1.09%   |
| 3840x2400          | 2         | 0.73%   |
| 2880x1800          | 2         | 0.73%   |
| 1400x1050          | 2         | 0.73%   |
| 3440x1440          | 1         | 0.36%   |
| 1920x1280          | 1         | 0.36%   |
| 1280x960           | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |
| 1024x600           | 1         | 0.36%   |
| 1024x576           | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 132       | 44.3%   |
| 17      | 41        | 13.76%  |
| 13      | 25        | 8.39%   |
| 14      | 24        | 8.05%   |
| 27      | 16        | 5.37%   |
| 24      | 12        | 4.03%   |
| 23      | 8         | 2.68%   |
| 12      | 7         | 2.35%   |
| 54      | 6         | 2.01%   |
| 31      | 5         | 1.68%   |
| 21      | 5         | 1.68%   |
| 16      | 4         | 1.34%   |
| Unknown | 3         | 1.01%   |
| 20      | 2         | 0.67%   |
| 10      | 2         | 0.67%   |
| 38      | 1         | 0.34%   |
| 34      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 18      | 1         | 0.34%   |
| 11      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 55.97%  |
| 351-400     | 44        | 15.02%  |
| 501-600     | 30        | 10.24%  |
| 201-300     | 27        | 9.22%   |
| 401-500     | 9         | 3.07%   |
| 601-700     | 8         | 2.73%   |
| 1001-1500   | 6         | 2.05%   |
| Unknown     | 3         | 1.02%   |
| 801-900     | 1         | 0.34%   |
| 701-800     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 207       | 82.47%  |
| 16/10   | 33        | 13.15%  |
| 3/2     | 5         | 1.99%   |
| 4/3     | 3         | 1.2%    |
| 5/4     | 1         | 0.4%    |
| 21/9    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 44.63%  |
| 81-90          | 37        | 12.42%  |
| 121-130        | 33        | 11.07%  |
| 201-250        | 19        | 6.38%   |
| 301-350        | 17        | 5.7%    |
| 71-80          | 11        | 3.69%   |
| 131-140        | 7         | 2.35%   |
| More than 1000 | 6         | 2.01%   |
| 61-70          | 6         | 2.01%   |
| 351-500        | 6         | 2.01%   |
| 151-200        | 5         | 1.68%   |
| 251-300        | 4         | 1.34%   |
| 111-120        | 3         | 1.01%   |
| Unknown        | 3         | 1.01%   |
| 41-50          | 2         | 0.67%   |
| 141-150        | 2         | 0.67%   |
| 91-100         | 2         | 0.67%   |
| 51-60          | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 135       | 47.04%  |
| 101-120       | 75        | 26.13%  |
| 51-100        | 47        | 16.38%  |
| 161-240       | 16        | 5.57%   |
| 1-50          | 6         | 2.09%   |
| More than 240 | 5         | 1.74%   |
| Unknown       | 3         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 198       | 75.57%  |
| 2     | 49        | 18.7%   |
| 0     | 9         | 3.44%   |
| 3     | 5         | 1.91%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 144       | 35.12%  |
| Intel                             | 128       | 31.22%  |
| Qualcomm Atheros                  | 67        | 16.34%  |
| Broadcom                          | 22        | 5.37%   |
| MediaTek                          | 9         | 2.2%    |
| Broadcom Limited                  | 6         | 1.46%   |
| Samsung Electronics               | 4         | 0.98%   |
| TP-Link                           | 3         | 0.73%   |
| Marvell Technology Group          | 3         | 0.73%   |
| Xiaomi                            | 2         | 0.49%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.49%   |
| Ralink                            | 2         | 0.49%   |
| Qualcomm Atheros Communications   | 2         | 0.49%   |
| Qualcomm                          | 2         | 0.49%   |
| Lenovo                            | 2         | 0.49%   |
| D-Link                            | 2         | 0.49%   |
| VIA Technologies                  | 1         | 0.24%   |
| Ralink Technology                 | 1         | 0.24%   |
| Nvidia                            | 1         | 0.24%   |
| HTC (High Tech Computer)          | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Fibocom                           | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| DisplayLink                       | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| ASIX Electronics                  | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 112       | 23.28%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.16%   |
| Intel Wireless 8265 / 8275                                              | 19        | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 3.12%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.66%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.46%   |
| Intel Wireless 7260                                                     | 7         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.25%   |
| Intel Wireless 7265                                                     | 6         | 1.25%   |
| Intel Wireless 3165                                                     | 6         | 1.25%   |
| Intel Wireless 3160                                                     | 6         | 1.25%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.83%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.62%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.62%   |
| Intel WiFi Link 5100                                                    | 3         | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.62%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 49.8%   |
| Qualcomm Atheros                | 58        | 22.75%  |
| Realtek Semiconductor           | 28        | 10.98%  |
| Broadcom                        | 15        | 5.88%   |
| MediaTek                        | 9         | 3.53%   |
| Broadcom Limited                | 4         | 1.57%   |
| TP-Link                         | 3         | 1.18%   |
| Ralink                          | 2         | 0.78%   |
| Qualcomm Atheros Communications | 2         | 0.78%   |
| Qualcomm                        | 2         | 0.78%   |
| D-Link                          | 2         | 0.78%   |
| Ralink Technology               | 1         | 0.39%   |
| Fibocom                         | 1         | 0.39%   |
| Dell                            | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 7.84%   |
| Intel Wireless 8265 / 8275                                              | 19        | 7.45%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.75%   |
| Intel Wireless 7260                                                     | 7         | 2.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.35%   |
| Intel Wireless 7265                                                     | 6         | 2.35%   |
| Intel Wireless 3165                                                     | 6         | 2.35%   |
| Intel Wireless 3160                                                     | 6         | 2.35%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.18%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.18%   |
| Intel WiFi Link 5100                                                    | 3         | 1.18%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.18%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.18%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.78%   |
| Intel Wireless 8260                                                     | 2         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.78%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 135       | 60.54%  |
| Intel                            | 42        | 18.83%  |
| Qualcomm Atheros                 | 19        | 8.52%   |
| Broadcom                         | 7         | 3.14%   |
| Samsung Electronics              | 4         | 1.79%   |
| Marvell Technology Group         | 3         | 1.35%   |
| Xiaomi                           | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] | 2         | 0.9%    |
| Lenovo                           | 2         | 0.9%    |
| Broadcom Limited                 | 2         | 0.9%    |
| VIA Technologies                 | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |
| HTC (High Tech Computer)         | 1         | 0.45%   |
| DisplayLink                      | 1         | 0.45%   |
| ASIX Electronics                 | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 50.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 6.73%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 3.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 2.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.35%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.35%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.9%    |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.9%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.45%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.45%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 247       | 53.46%  |
| Ethernet | 212       | 45.89%  |
| Modem    | 3         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 215       | 79.63%  |
| Ethernet | 55        | 20.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 198       | 78.88%  |
| 1     | 50        | 19.92%  |
| 0     | 3         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 242       | 96.03%  |
| Yes  | 10        | 3.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 47.12%  |
| Lite-On Technology              | 23        | 11.06%  |
| Qualcomm Atheros Communications | 19        | 9.13%   |
| Realtek Semiconductor           | 16        | 7.69%   |
| IMC Networks                    | 14        | 6.73%   |
| Broadcom                        | 8         | 3.85%   |
| Foxconn / Hon Hai               | 7         | 3.37%   |
| Hewlett-Packard                 | 6         | 2.88%   |
| Apple                           | 5         | 2.4%    |
| Cambridge Silicon Radio         | 4         | 1.92%   |
| Toshiba                         | 3         | 1.44%   |
| Foxconn International           | 3         | 1.44%   |
| Realtek                         | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 21.63%  |
| Intel AX200 Bluetooth                               | 15        | 7.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 6.73%   |
| Intel AX201 Bluetooth                               | 14        | 6.73%   |
| Realtek Bluetooth Radio                             | 13        | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 5.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.37%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 2.88%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.92%   |
| Lite-On Wireless_Device                             | 3         | 1.44%   |
| Lite-On Bluetooth Device                            | 3         | 1.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.44%   |
| IMC Networks Wireless_Device                        | 3         | 1.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.96%   |
| IMC Networks Bluetooth Device                       | 2         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.96%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.96%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.96%   |
| Apple Bluetooth Host Controller                     | 2         | 0.96%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.48%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.48%   |
| Toshiba Bluetooth Device                            | 1         | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.48%   |
| Realtek Bluetooth Radio                             | 1         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.48%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.48%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 199       | 63.78%  |
| AMD                              | 53        | 16.99%  |
| Nvidia                           | 33        | 10.58%  |
| C-Media Electronics              | 5         | 1.6%    |
| Logitech                         | 3         | 0.96%   |
| Lenovo                           | 3         | 0.96%   |
| JMTek                            | 3         | 0.96%   |
| Silicon Integrated Systems [SiS] | 2         | 0.64%   |
| ZOOM                             | 1         | 0.32%   |
| YZ Technology                    | 1         | 0.32%   |
| VIA Technologies                 | 1         | 0.32%   |
| Trust                            | 1         | 0.32%   |
| Texas Instruments                | 1         | 0.32%   |
| SteelSeries ApS                  | 1         | 0.32%   |
| Samson Technologies              | 1         | 0.32%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| Plantronics                      | 1         | 0.32%   |
| Pioneer DJ                       | 1         | 0.32%   |
| GN Netcom                        | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 10.73%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 8.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 2.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 2.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 1.83%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.31%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.31%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.79%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.79%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.52%   |
| Nvidia Audio device                                                                               | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 29.52%  |
| SK hynix            | 36        | 21.69%  |
| Kingston            | 25        | 15.06%  |
| Micron Technology   | 23        | 13.86%  |
| Crucial             | 9         | 5.42%   |
| Unknown             | 7         | 4.22%   |
| Ramaxel Technology  | 4         | 2.41%   |
| Elpida              | 3         | 1.81%   |
| Patriot             | 2         | 1.2%    |
| A-DATA Technology   | 2         | 1.2%    |
| Transcend           | 1         | 0.6%    |
| Qimonda             | 1         | 0.6%    |
| G.Skill             | 1         | 0.6%    |
| Corsair             | 1         | 0.6%    |
| Avant               | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 3.31%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 5         | 2.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 2.21%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.66%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 3         | 1.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 3         | 1.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 3         | 1.66%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 3         | 1.66%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 1.1%    |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s     | 2         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 1.1%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 2         | 1.1%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 1.1%    |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 1.1%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 2         | 1.1%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.1%    |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s         | 2         | 1.1%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 1.1%    |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s       | 2         | 1.1%    |
| Kingston RAM 9905700-047.A00G 16GB SODIMM DDR4 2667MT/s       | 2         | 1.1%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.1%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                 | 1         | 0.55%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s            | 1         | 0.55%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.55%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.55%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.55%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 0.55%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.55%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 0.55%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s              | 1         | 0.55%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s         | 1         | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 67        | 49.63%  |
| DDR3   | 45        | 33.33%  |
| LPDDR3 | 8         | 5.93%   |
| DDR2   | 8         | 5.93%   |
| LPDDR4 | 6         | 4.44%   |
| SDRAM  | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 86.67%  |
| Row Of Chips | 16        | 11.85%  |
| DIMM         | 1         | 0.74%   |
| Chip         | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 57        | 38.51%  |
| 4096  | 49        | 33.11%  |
| 16384 | 22        | 14.86%  |
| 2048  | 11        | 7.43%   |
| 1024  | 6         | 4.05%   |
| 32768 | 3         | 2.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 37        | 25.17%  |
| 1600  | 35        | 23.81%  |
| 3200  | 27        | 18.37%  |
| 2133  | 9         | 6.12%   |
| 2400  | 7         | 4.76%   |
| 1334  | 6         | 4.08%   |
| 667   | 6         | 4.08%   |
| 4267  | 3         | 2.04%   |
| 1333  | 3         | 2.04%   |
| 1066  | 3         | 2.04%   |
| 1867  | 2         | 1.36%   |
| 8400  | 1         | 0.68%   |
| 4266  | 1         | 0.68%   |
| 3266  | 1         | 0.68%   |
| 3000  | 1         | 0.68%   |
| 2048  | 1         | 0.68%   |
| 1067  | 1         | 0.68%   |
| 975   | 1         | 0.68%   |
| 800   | 1         | 0.68%   |
| 533   | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Canon               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Composite Device        | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| HP Deskjet 1050 J410            | 1         | 20%     |
| Canon PIXMA iP4300 Printer      | 1         | 20%     |
| Canon LBP6670 UFR II            | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Ultima Artec Ultima 2000 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 29.13%  |
| IMC Networks                           | 27        | 11.74%  |
| Quanta                                 | 22        | 9.57%   |
| Realtek Semiconductor                  | 20        | 8.7%    |
| Acer                                   | 16        | 6.96%   |
| Microdia                               | 15        | 6.52%   |
| Suyin                                  | 10        | 4.35%   |
| Sunplus Innovation Technology          | 9         | 3.91%   |
| Lite-On Technology                     | 8         | 3.48%   |
| Syntek                                 | 7         | 3.04%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.61%   |
| Luxvisions Innotech Limited            | 3         | 1.3%    |
| Logitech                               | 3         | 1.3%    |
| Apple                                  | 3         | 1.3%    |
| Silicon Motion                         | 2         | 0.87%   |
| Primax Electronics                     | 2         | 0.87%   |
| Jieli Technology                       | 2         | 0.87%   |
| Anker                                  | 2         | 0.87%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
| Ricoh                                  | 1         | 0.43%   |
| Goertek Electronics                    | 1         | 0.43%   |
| Genesys Logic                          | 1         | 0.43%   |
| Cubeternet                             | 1         | 0.43%   |
| AVerMedia Technologies                 | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 14        | 6.09%   |
| Chicony Integrated Camera                     | 12        | 5.22%   |
| IMC Networks Integrated Camera                | 10        | 4.35%   |
| Quanta VGA WebCam                             | 8         | 3.48%   |
| Microdia Integrated_Webcam_HD                 | 8         | 3.48%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 7         | 3.04%   |
| Realtek Integrated_Webcam_HD                  | 5         | 2.17%   |
| Lite-On HP HD Camera                          | 5         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 2.17%   |
| Acer Lenovo EasyCamera                        | 5         | 2.17%   |
| Quanta HD Webcam                              | 4         | 1.74%   |
| Acer Integrated Camera                        | 4         | 1.74%   |
| Syntek Integrated Camera                      | 3         | 1.3%    |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 3         | 1.3%    |
| Sunplus Asus Webcam                           | 3         | 1.3%    |
| Realtek Lenovo EasyCamera                     | 3         | 1.3%    |
| Quanta HP TrueVision HD Camera                | 3         | 1.3%    |
| Quanta HP HD Camera                           | 3         | 1.3%    |
| Quanta HD User Facing                         | 3         | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                 | 3         | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 1.3%    |
| Chicony Integrated HP HD Webcam               | 3         | 1.3%    |
| Chicony HP Wide Vision HD Camera              | 3         | 1.3%    |
| Chicony HP Webcam                             | 3         | 1.3%    |
| Suyin WebCam                                  | 2         | 0.87%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 0.87%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 0.87%   |
| Sunplus HD WebCam                             | 2         | 0.87%   |
| Realtek USB Camera                            | 2         | 0.87%   |
| Realtek Integrated Webcam                     | 2         | 0.87%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 0.87%   |
| Primax HP HD Webcam [Fixed]                   | 2         | 0.87%   |
| Microdia Laptop_Integrated_Webcam_HD          | 2         | 0.87%   |
| Microdia Integrated Webcam                    | 2         | 0.87%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.87%   |
| Lite-On Integrated Camera                     | 2         | 0.87%   |
| Jieli USB PHY 2.0                             | 2         | 0.87%   |
| Chicony USB 2.0 Camera                        | 2         | 0.87%   |
| Chicony ThinkPad T490 Webcam                  | 2         | 0.87%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 30.51%  |
| Validity Sensors           | 14        | 23.73%  |
| Shenzhen Goodix Technology | 11        | 18.64%  |
| AuthenTec                  | 5         | 8.47%   |
| LighTuning Technology      | 4         | 6.78%   |
| Upek                       | 3         | 5.08%   |
| Elan Microelectronics      | 3         | 5.08%   |
| STMicroelectronics         | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 13.56%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.17%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 6.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 6.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.08%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.08%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.08%   |
| AuthenTec AES2810                                                          | 3         | 5.08%   |
| Unknown                                                                    | 3         | 5.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.39%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS491                                                    | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.69%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.69%   |
| Synaptics  WBDI                                                            | 1         | 1.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.69%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 44.44%  |
| Broadcom              | 3         | 33.33%  |
| Realtek Semiconductor | 1         | 11.11%  |
| Lenovo                | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 4         | 44.44%  |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader               | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 11.11%  |
| Broadcom 5880                                     | 1         | 11.11%  |
| Broadcom 58200                                    | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 155       | 59.62%  |
| 1     | 85        | 32.69%  |
| 2     | 18        | 6.92%   |
| 3     | 2         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 47.15%  |
| Graphics card            | 27        | 21.95%  |
| Net/wireless             | 12        | 9.76%   |
| Chipcard                 | 8         | 6.5%    |
| Multimedia controller    | 7         | 5.69%   |
| Card reader              | 3         | 2.44%   |
| Communication controller | 2         | 1.63%   |
| Camera                   | 2         | 1.63%   |
| Storage/ide              | 1         | 0.81%   |
| Storage                  | 1         | 0.81%   |
| Sound                    | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |

