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

Total: 386

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
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
| Ubuntu 20.04      | 49        | 17.38%  |
| Ubuntu 18.04      | 17        | 6.03%   |
| Ubuntu 22.04      | 8         | 2.84%   |
| Debian 11         | 8         | 2.84%   |
| Pop!_OS 21.04     | 7         | 2.48%   |
| OpenMandriva 4.3  | 7         | 2.48%   |
| Pop!_OS 20.04     | 6         | 2.13%   |
| Fedora 36         | 6         | 2.13%   |
| Ubuntu 19.04      | 5         | 1.77%   |
| Fedora 35         | 5         | 1.77%   |
| Arch Rolling      | 5         | 1.77%   |
| Ubuntu 21.04      | 4         | 1.42%   |
| Pop!_OS 20.10     | 4         | 1.42%   |
| Linux Mint 20.3   | 4         | 1.42%   |
| Linux Mint 20.2   | 4         | 1.42%   |
| KDE neon 20.04    | 4         | 1.42%   |
| Endless 3.7.8     | 4         | 1.42%   |
| Arch              | 4         | 1.42%   |
| Zorin 16          | 3         | 1.06%   |
| Zorin 15          | 3         | 1.06%   |
| Ubuntu 20.10      | 3         | 1.06%   |
| Ubuntu 19.10      | 3         | 1.06%   |
| Ubuntu 18.10      | 3         | 1.06%   |
| ROSA R10          | 3         | 1.06%   |
| Pop!_OS 22.04     | 3         | 1.06%   |
| Pop!_OS 21.10     | 3         | 1.06%   |
| OpenMandriva 4.2  | 3         | 1.06%   |
| Endless 3.9.5     | 3         | 1.06%   |
| Endless 3.9.4     | 3         | 1.06%   |
| Ubuntu 21.10      | 2         | 0.71%   |
| OpenMandriva 4.50 | 2         | 0.71%   |
| Nobara 36         | 2         | 0.71%   |
| Manjaro 21.0.7    | 2         | 0.71%   |
| Manjaro 21.0      | 2         | 0.71%   |
| Manjaro 20.2.1    | 2         | 0.71%   |
| Manjaro 20.2      | 2         | 0.71%   |
| Manjaro 20.1.2    | 2         | 0.71%   |
| Manjaro 18.1.5    | 2         | 0.71%   |
| Linux Mint 20.1   | 2         | 0.71%   |
| Linux Mint 20     | 2         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 84        | 33.2%   |
| Pop!_OS       | 22        | 8.7%    |
| Endless       | 21        | 8.3%    |
| Linux Mint    | 17        | 6.72%   |
| Fedora        | 16        | 6.32%   |
| Manjaro       | 14        | 5.53%   |
| OpenMandriva  | 12        | 4.74%   |
| Debian        | 10        | 3.95%   |
| Arch          | 9         | 3.56%   |
| Kubuntu       | 8         | 3.16%   |
| Zorin         | 6         | 2.37%   |
| ROSA          | 6         | 2.37%   |
| KDE neon      | 5         | 1.98%   |
| Kali          | 3         | 1.19%   |
| Ubuntu MATE   | 2         | 0.79%   |
| openSUSE      | 2         | 0.79%   |
| Nobara        | 2         | 0.79%   |
| EndeavourOS   | 2         | 0.79%   |
| Elementary    | 2         | 0.79%   |
| ArcoLinux     | 2         | 0.79%   |
| Xubuntu       | 1         | 0.4%    |
| Ubuntu Unity  | 1         | 0.4%    |
| Ubuntu Budgie | 1         | 0.4%    |
| Parrot        | 1         | 0.4%    |
| LMDE          | 1         | 0.4%    |
| LinuxFX       | 1         | 0.4%    |
| Gentoo        | 1         | 0.4%    |
| CentOS        | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 2.29%   |
| 5.8.0-14-generic         | 6         | 1.96%   |
| 5.11.0-38-generic        | 6         | 1.96%   |
| 5.4.0-42-generic         | 5         | 1.63%   |
| 5.11.0-7620-generic      | 5         | 1.63%   |
| 5.3.0-28-generic         | 4         | 1.31%   |
| 5.13.0-30-generic        | 4         | 1.31%   |
| 5.8.16-2-MANJARO         | 3         | 0.98%   |
| 5.8.0-7630-generic       | 3         | 0.98%   |
| 5.8.0-59-generic         | 3         | 0.98%   |
| 5.8.0-43-generic         | 3         | 0.98%   |
| 5.4.0-52-generic         | 3         | 0.98%   |
| 5.4.0-48-generic         | 3         | 0.98%   |
| 5.4.0-47-generic         | 3         | 0.98%   |
| 5.4.0-37-generic         | 3         | 0.98%   |
| 5.4.0-29-generic         | 3         | 0.98%   |
| 5.4.0-19-generic         | 3         | 0.98%   |
| 5.15.0-40-generic        | 3         | 0.98%   |
| 5.13.0-7620-generic      | 3         | 0.98%   |
| 5.13.0-52-generic        | 3         | 0.98%   |
| 5.11.0-41-generic        | 3         | 0.98%   |
| 5.11.0-40-generic        | 3         | 0.98%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.98%   |
| 4.18.0-18-generic        | 3         | 0.98%   |
| 5.9.16-1-MANJARO         | 2         | 0.65%   |
| 5.8.0-49-generic         | 2         | 0.65%   |
| 5.8.0-48-generic         | 2         | 0.65%   |
| 5.4.0-91-generic         | 2         | 0.65%   |
| 5.4.0-84-generic         | 2         | 0.65%   |
| 5.4.0-7642-generic       | 2         | 0.65%   |
| 5.4.0-58-generic         | 2         | 0.65%   |
| 5.4.0-54-generic         | 2         | 0.65%   |
| 5.4.0-40-generic         | 2         | 0.65%   |
| 5.4.0-128-generic        | 2         | 0.65%   |
| 5.3.0-23-generic         | 2         | 0.65%   |
| 5.16.11-76051611-generic | 2         | 0.65%   |
| 5.15.0-47-generic        | 2         | 0.65%   |
| 5.15.0-46-generic        | 2         | 0.65%   |
| 5.15.0-27-generic        | 2         | 0.65%   |
| 5.11.0-35-generic        | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 52        | 17.99%  |
| 5.11.0  | 31        | 10.73%  |
| 5.8.0   | 20        | 6.92%   |
| 5.13.0  | 16        | 5.54%   |
| 4.15.0  | 15        | 5.19%   |
| 5.15.0  | 14        | 4.84%   |
| 5.3.0   | 11        | 3.81%   |
| 5.0.0   | 10        | 3.46%   |
| 4.18.0  | 10        | 3.46%   |
| 5.16.7  | 8         | 2.77%   |
| 5.10.0  | 8         | 2.77%   |
| 5.9.16  | 4         | 1.38%   |
| 5.8.16  | 3         | 1.04%   |
| 5.10.14 | 3         | 1.04%   |
| 4.9.60  | 3         | 1.04%   |
| 4.19.0  | 3         | 1.04%   |
| 5.9.11  | 2         | 0.69%   |
| 5.5.0   | 2         | 0.69%   |
| 5.19.0  | 2         | 0.69%   |
| 5.16.11 | 2         | 0.69%   |
| 5.15.8  | 2         | 0.69%   |
| 5.14.0  | 2         | 0.69%   |
| 6.0.5   | 1         | 0.35%   |
| 5.9.9   | 1         | 0.35%   |
| 5.9.1   | 1         | 0.35%   |
| 5.8.6   | 1         | 0.35%   |
| 5.7.11  | 1         | 0.35%   |
| 5.6.6   | 1         | 0.35%   |
| 5.6.2   | 1         | 0.35%   |
| 5.6.19  | 1         | 0.35%   |
| 5.6.0   | 1         | 0.35%   |
| 5.4.74  | 1         | 0.35%   |
| 5.4.17  | 1         | 0.35%   |
| 5.4.13  | 1         | 0.35%   |
| 5.3.8   | 1         | 0.35%   |
| 5.3.18  | 1         | 0.35%   |
| 5.2.10  | 1         | 0.35%   |
| 5.19.5  | 1         | 0.35%   |
| 5.19.3  | 1         | 0.35%   |
| 5.19.14 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 55        | 19.37%  |
| 5.11    | 36        | 12.68%  |
| 5.8     | 24        | 8.45%   |
| 5.15    | 20        | 7.04%   |
| 5.13    | 19        | 6.69%   |
| 5.10    | 16        | 5.63%   |
| 4.15    | 15        | 5.28%   |
| 5.16    | 13        | 4.58%   |
| 5.3     | 12        | 4.23%   |
| 5.0     | 11        | 3.87%   |
| 4.18    | 10        | 3.52%   |
| 5.9     | 8         | 2.82%   |
| 5.19    | 7         | 2.46%   |
| 5.18    | 5         | 1.76%   |
| 5.17    | 5         | 1.76%   |
| 4.9     | 5         | 1.76%   |
| 5.6     | 4         | 1.41%   |
| 5.14    | 3         | 1.06%   |
| 4.19    | 3         | 1.06%   |
| 5.5     | 2         | 0.7%    |
| 5.12    | 2         | 0.7%    |
| 6.0     | 1         | 0.35%   |
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
| x86_64 | 241       | 97.97%  |
| i686   | 5         | 2.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 126       | 48.28%  |
| KDE5            | 42        | 16.09%  |
| Unknown         | 37        | 14.18%  |
| X-Cinnamon      | 12        | 4.6%    |
| XFCE            | 8         | 3.07%   |
| KDE             | 6         | 2.3%    |
| Cinnamon        | 6         | 2.3%    |
| MATE            | 5         | 1.92%   |
| KDE4            | 4         | 1.53%   |
| GNOME Flashback | 4         | 1.53%   |
| DWM             | 3         | 1.15%   |
| Pantheon        | 2         | 0.77%   |
| Budgie          | 2         | 0.77%   |
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
| X11     | 200       | 75.76%  |
| Wayland | 33        | 12.5%   |
| Unknown | 27        | 10.23%  |
| Tty     | 4         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 123       | 48.62%  |
| GDM     | 48        | 18.97%  |
| SDDM    | 37        | 14.62%  |
| GDM3    | 17        | 6.72%   |
| LightDM | 14        | 5.53%   |
| TDM     | 10        | 3.95%   |
| KDM     | 3         | 1.19%   |
| Ly      | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 133       | 52.36%  |
| hr_HR   | 59        | 23.23%  |
| Unknown | 38        | 14.96%  |
| en_GB   | 10        | 3.94%   |
| de_DE   | 6         | 2.36%   |
| C       | 4         | 1.57%   |
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
| EFI  | 150       | 59.06%  |
| BIOS | 104       | 40.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 198       | 77.95%  |
| Unknown | 16        | 6.3%    |
| Overlay | 15        | 5.91%   |
| Btrfs   | 15        | 5.91%   |
| Zfs     | 4         | 1.57%   |
| Xfs     | 4         | 1.57%   |
| Jfs     | 1         | 0.39%   |
| Ext2    | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 134       | 53.82%  |
| GPT     | 88        | 35.34%  |
| MBR     | 27        | 10.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 232       | 92.8%   |
| Yes       | 18        | 7.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 194       | 77.6%   |
| Yes       | 56        | 22.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 64        | 26.02%  |
| Hewlett-Packard         | 51        | 20.73%  |
| Acer                    | 43        | 17.48%  |
| ASUSTek Computer        | 30        | 12.2%   |
| Dell                    | 29        | 11.79%  |
| Toshiba                 | 7         | 2.85%   |
| Apple                   | 4         | 1.63%   |
| Samsung Electronics     | 3         | 1.22%   |
| eMachines               | 3         | 1.22%   |
| HUAWEI                  | 2         | 0.81%   |
| Fujitsu Siemens         | 2         | 0.81%   |
| TUXEDO                  | 1         | 0.41%   |
| System76                | 1         | 0.41%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.41%   |
| Razer                   | 1         | 0.41%   |
| Notebook                | 1         | 0.41%   |
| Medion                  | 1         | 0.41%   |
| Gigabyte Technology     | 1         | 0.41%   |
| Chuwi                   | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-21                        | 4         | 1.63%   |
| Lenovo G710 20252                          | 3         | 1.22%   |
| Acer Aspire A515-51G                       | 3         | 1.22%   |
| Lenovo Z50-70 20354                        | 2         | 0.81%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.81%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.81%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.81%   |
| Lenovo G40-30 80FY                         | 2         | 0.81%   |
| HP ProBook 450 G7                          | 2         | 0.81%   |
| HP EliteBook 8560p                         | 2         | 0.81%   |
| HP EliteBook 850 G6                        | 2         | 0.81%   |
| HP 2000                                    | 2         | 0.81%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.81%   |
| Dell XPS 13 9310                           | 2         | 0.81%   |
| Dell Vostro 3500                           | 2         | 0.81%   |
| ASUS X751NV                                | 2         | 0.81%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.81%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.81%   |
| ASUS N56VZ                                 | 2         | 0.81%   |
| Acer Aspire E5-771G                        | 2         | 0.81%   |
| Acer Aspire A715-72G                       | 2         | 0.81%   |
| Acer Aspire 7739G                          | 2         | 0.81%   |
| Unknown                                    | 2         | 0.81%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.41%   |
| Toshiba Satellite P200                     | 1         | 0.41%   |
| Toshiba Satellite L750                     | 1         | 0.41%   |
| Toshiba Satellite L50-B                    | 1         | 0.41%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.41%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.41%   |
| Toshiba Satellite A300                     | 1         | 0.41%   |
| Toshiba Encore                             | 1         | 0.41%   |
| System76 Oryx Pro                          | 1         | 0.41%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.41%   |
| Samsung N150/N210/N220                     | 1         | 0.41%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.41%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.41%   |
| Razer Blade                                | 1         | 0.41%   |
| Notebook MAM2080                           | 1         | 0.41%   |
| Medion P6618                               | 1         | 0.41%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 36        | 14.63%  |
| Lenovo ThinkPad               | 28        | 11.38%  |
| HP EliteBook                  | 12        | 4.88%   |
| HP ProBook                    | 10        | 4.07%   |
| HP Pavilion                   | 8         | 3.25%   |
| ASUS VivoBook                 | 8         | 3.25%   |
| Lenovo Legion                 | 7         | 2.85%   |
| Dell XPS                      | 7         | 2.85%   |
| Dell Vostro                   | 7         | 2.85%   |
| Dell Latitude                 | 7         | 2.85%   |
| Toshiba Satellite             | 6         | 2.44%   |
| Lenovo ThinkBook              | 6         | 2.44%   |
| Lenovo IdeaPad                | 6         | 2.44%   |
| Dell Inspiron                 | 5         | 2.03%   |
| Acer Swift                    | 5         | 2.03%   |
| HP Laptop                     | 4         | 1.63%   |
| HP 250                        | 4         | 1.63%   |
| Lenovo G710                   | 3         | 1.22%   |
| HP Compaq                     | 3         | 1.22%   |
| Lenovo Z50-70                 | 2         | 0.81%   |
| Lenovo G40-30                 | 2         | 0.81%   |
| Lenovo B590                   | 2         | 0.81%   |
| HP OMEN                       | 2         | 0.81%   |
| HP 2000                       | 2         | 0.81%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.81%   |
| ASUS ZenBook                  | 2         | 0.81%   |
| ASUS X751NV                   | 2         | 0.81%   |
| ASUS ROG                      | 2         | 0.81%   |
| ASUS N56VZ                    | 2         | 0.81%   |
| Unknown                       | 2         | 0.81%   |
| TUXEDO Pulse                  | 1         | 0.41%   |
| Toshiba Encore                | 1         | 0.41%   |
| System76 Oryx                 | 1         | 0.41%   |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.41%   |
| Samsung N150                  | 1         | 0.41%   |
| Samsung 300E4C                | 1         | 0.41%   |
| Samsung 300E4A                | 1         | 0.41%   |
| Razer Blade                   | 1         | 0.41%   |
| Notebook MAM2080              | 1         | 0.41%   |
| Medion P6618                  | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 35        | 14.23%  |
| 2019 | 25        | 10.16%  |
| 2017 | 24        | 9.76%   |
| 2020 | 22        | 8.94%   |
| 2013 | 20        | 8.13%   |
| 2021 | 18        | 7.32%   |
| 2016 | 17        | 6.91%   |
| 2014 | 17        | 6.91%   |
| 2011 | 17        | 6.91%   |
| 2012 | 11        | 4.47%   |
| 2007 | 10        | 4.07%   |
| 2015 | 8         | 3.25%   |
| 2008 | 8         | 3.25%   |
| 2009 | 6         | 2.44%   |
| 2010 | 5         | 2.03%   |
| 2006 | 2         | 0.81%   |
| 2022 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 246       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 220       | 89.07%  |
| Enabled  | 27        | 10.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 246       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 82        | 32.67%  |
| 8.01-16.0   | 47        | 18.73%  |
| 3.01-4.0    | 46        | 18.33%  |
| 16.01-24.0  | 38        | 15.14%  |
| 32.01-64.0  | 16        | 6.37%   |
| 1.01-2.0    | 11        | 4.38%   |
| 24.01-32.0  | 6         | 2.39%   |
| 2.01-3.0    | 4         | 1.59%   |
| 64.01-256.0 | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 99        | 34.98%  |
| 2.01-3.0   | 65        | 22.97%  |
| 4.01-8.0   | 45        | 15.9%   |
| 3.01-4.0   | 39        | 13.78%  |
| 0.51-1.0   | 17        | 6.01%   |
| 8.01-16.0  | 14        | 4.95%   |
| 16.01-24.0 | 2         | 0.71%   |
| 0.01-0.5   | 2         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 186       | 73.52%  |
| 2      | 56        | 22.13%  |
| 3      | 5         | 1.98%   |
| 0      | 3         | 1.19%   |
| 6      | 1         | 0.4%    |
| 5      | 1         | 0.4%    |
| 4      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 67.34%  |
| Yes       | 81        | 32.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 85.43%  |
| No        | 36        | 14.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 98.78%  |
| No        | 3         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 81.27%  |
| No        | 47        | 18.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 246       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 162       | 57.04%  |
| Split               | 12        | 4.23%   |
| Rijeka              | 12        | 4.23%   |
| Varaždin           | 7         | 2.46%   |
| Velika Gorica       | 5         | 1.76%   |
| Pula                | 5         | 1.76%   |
| Zaprešić          | 3         | 1.06%   |
| Jesenice            | 3         | 1.06%   |
| Čakovec            | 3         | 1.06%   |
| Zadar               | 2         | 0.7%    |
| Rovinj              | 2         | 0.7%    |
| Petrinja            | 2         | 0.7%    |
| Osijek              | 2         | 0.7%    |
| Omiš               | 2         | 0.7%    |
| Novska              | 2         | 0.7%    |
| Krizevci            | 2         | 0.7%    |
| Komiža             | 2         | 0.7%    |
| Kastav              | 2         | 0.7%    |
| Bjelovar            | 2         | 0.7%    |
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
| Samsung Electronics   | 52        | 66     | 17.22%  |
| WDC                   | 37        | 46     | 12.25%  |
| Kingston              | 29        | 38     | 9.6%    |
| Seagate               | 25        | 47     | 8.28%   |
| SK hynix              | 23        | 34     | 7.62%   |
| Toshiba               | 20        | 21     | 6.62%   |
| SanDisk               | 20        | 25     | 6.62%   |
| Micron Technology     | 12        | 13     | 3.97%   |
| Unknown               | 9         | 9      | 2.98%   |
| Intel                 | 9         | 15     | 2.98%   |
| Hitachi               | 9         | 9      | 2.98%   |
| HGST                  | 8         | 8      | 2.65%   |
| Crucial               | 7         | 12     | 2.32%   |
| Fujitsu               | 5         | 6      | 1.66%   |
| A-DATA Technology     | 5         | 5      | 1.66%   |
| Apple                 | 4         | 4      | 1.32%   |
| LITEON                | 3         | 4      | 0.99%   |
| Transcend             | 2         | 3      | 0.66%   |
| Silicon Motion        | 2         | 3      | 0.66%   |
| Lenovo                | 2         | 3      | 0.66%   |
| KingFast              | 2         | 4      | 0.66%   |
| Intenso               | 2         | 3      | 0.66%   |
| Verbatim              | 1         | 1      | 0.33%   |
| UMIS                  | 1         | 1      | 0.33%   |
| StoreJet              | 1         | 1      | 0.33%   |
| Realtek Semiconductor | 1         | 3      | 0.33%   |
| Phison                | 1         | 1      | 0.33%   |
| Patriot               | 1         | 1      | 0.33%   |
| Netac                 | 1         | 1      | 0.33%   |
| Mass                  | 1         | 1      | 0.33%   |
| Lite-On               | 1         | 1      | 0.33%   |
| LaCie                 | 1         | 1      | 0.33%   |
| KIOXIA                | 1         | 1      | 0.33%   |
| Gigabyte Technology   | 1         | 1      | 0.33%   |
| Emtec                 | 1         | 1      | 0.33%   |
| Corsair               | 1         | 1      | 0.33%   |
| AMD                   | 1         | 3      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 8         | 2.61%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 1.96%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 1.96%   |
| SanDisk NVMe SSD Drive 512GB            | 5         | 1.63%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.31%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.98%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.98%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.98%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 0.98%   |
| Intel NVMe SSD Drive 256GB              | 3         | 0.98%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.98%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.65%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.65%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.65%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 2         | 0.65%   |
| Unknown SD/MMC/MS PRO 1TB               | 2         | 0.65%   |
| Unknown MMC Card  32GB                  | 2         | 0.65%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.65%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.65%   |
| SK hynix NVMe SSD Drive 512GB           | 2         | 0.65%   |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.65%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.65%   |
| SK hynix HFM512GDJTNI-82A0A 512GB       | 2         | 0.65%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.65%   |
| Seagate ST9500325AS 500GB               | 2         | 0.65%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.65%   |
| Seagate ST1000LM048-2E7172 1TB          | 2         | 0.65%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 2         | 0.65%   |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB  | 2         | 0.65%   |
| Samsung PM9A1 NVMe 2048GB               | 2         | 0.65%   |
| Samsung PM981 NVMe 512GB                | 2         | 0.65%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD    | 2         | 0.65%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 0.65%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 31     | 28.57%  |
| Seagate             | 25        | 36     | 27.47%  |
| Toshiba             | 14        | 15     | 15.38%  |
| Hitachi             | 9         | 9      | 9.89%   |
| HGST                | 8         | 8      | 8.79%   |
| Fujitsu             | 5         | 6      | 5.49%   |
| Unknown             | 2         | 2      | 2.2%    |
| Samsung Electronics | 1         | 2      | 1.1%    |
| Intenso             | 1         | 2      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 25        | 30     | 23.81%  |
| Samsung Electronics | 18        | 26     | 17.14%  |
| SanDisk             | 11        | 15     | 10.48%  |
| Micron Technology   | 10        | 11     | 9.52%   |
| SK hynix            | 7         | 12     | 6.67%   |
| Crucial             | 7         | 12     | 6.67%   |
| WDC                 | 5         | 6      | 4.76%   |
| A-DATA Technology   | 5         | 5      | 4.76%   |
| Apple               | 4         | 4      | 3.81%   |
| LITEON              | 2         | 3      | 1.9%    |
| Intel               | 2         | 3      | 1.9%    |
| Transcend           | 1         | 2      | 0.95%   |
| Toshiba             | 1         | 1      | 0.95%   |
| StoreJet            | 1         | 1      | 0.95%   |
| Patriot             | 1         | 1      | 0.95%   |
| Netac               | 1         | 1      | 0.95%   |
| Intenso             | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Emtec               | 1         | 1      | 0.95%   |
| AMD                 | 1         | 3      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 97        | 139    | 33.56%  |
| NVMe    | 91        | 123    | 31.49%  |
| HDD     | 89        | 111    | 30.8%   |
| MMC     | 6         | 6      | 2.08%   |
| Unknown | 6         | 18     | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 164       | 243    | 60.74%  |
| NVMe | 91        | 123    | 33.7%   |
| SAS  | 9         | 25     | 3.33%   |
| MMC  | 6         | 6      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 126       | 169    | 68.11%  |
| 0.51-1.0   | 52        | 68     | 28.11%  |
| 1.01-2.0   | 7         | 13     | 3.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 33.33%  |
| 251-500        | 64        | 24.81%  |
| 501-1000       | 37        | 14.34%  |
| 1001-2000      | 23        | 8.91%   |
| 51-100         | 15        | 5.81%   |
| 1-20           | 13        | 5.04%   |
| 21-50          | 8         | 3.1%    |
| Unknown        | 7         | 2.71%   |
| 2001-3000      | 3         | 1.16%   |
| More than 3000 | 2         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 33.33%  |
| 21-50          | 64        | 22.94%  |
| 51-100         | 36        | 12.9%   |
| 101-250        | 34        | 12.19%  |
| 251-500        | 20        | 7.17%   |
| 501-1000       | 20        | 7.17%   |
| Unknown        | 7         | 2.51%   |
| 1001-2000      | 4         | 1.43%   |
| More than 3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 5.56%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 5.56%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 5.56%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 5.56%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.56%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 5.56%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 5.56%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 5.56%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 5.56%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 5.56%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 5.56%   |
| Crucial CT1024M550SSD1 1024GB        | 1         | 1      | 5.56%   |
| A-DATA Technology SU630 240GB SSD    | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 17.65%  |
| Seagate           | 3         | 3      | 17.65%  |
| HGST              | 3         | 3      | 17.65%  |
| Hitachi           | 2         | 2      | 11.76%  |
| Toshiba           | 1         | 1      | 5.88%   |
| SK hynix          | 1         | 1      | 5.88%   |
| SanDisk           | 1         | 2      | 5.88%   |
| LITEON            | 1         | 1      | 5.88%   |
| Crucial           | 1         | 1      | 5.88%   |
| A-DATA Technology | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 27.27%  |
| HGST    | 3         | 3      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Hitachi | 2         | 2      | 18.18%  |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 68.75%  |
| SSD  | 5         | 7      | 31.25%  |

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
| Detected | 151       | 239    | 57.85%  |
| Works    | 94        | 140    | 36.02%  |
| Malfunc  | 16        | 18     | 6.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 178       | 57.98%  |
| Samsung Electronics              | 35        | 11.4%   |
| AMD                              | 32        | 10.42%  |
| SK hynix                         | 16        | 5.21%   |
| SanDisk                          | 15        | 4.89%   |
| Toshiba America Info Systems     | 6         | 1.95%   |
| Kingston Technology Company      | 4         | 1.3%    |
| Silicon Motion                   | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 2         | 0.65%   |
| Phison Electronics               | 2         | 0.65%   |
| Nvidia                           | 2         | 0.65%   |
| Micron Technology                | 2         | 0.65%   |
| Lite-On Technology               | 2         | 0.65%   |
| Lenovo                           | 2         | 0.65%   |
| KIOXIA                           | 2         | 0.65%   |
| VIA Technologies                 | 1         | 0.33%   |
| Union Memory (Shenzhen)          | 1         | 0.33%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| Marvell Technology Group         | 1         | 0.33%   |
| JMicron Technology               | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 8.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 4.85%   |
| Samsung NVMe SSD Controller 980                                                  | 14        | 4.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 3.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 2.12%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 2.12%   |
| SK hynix Gold P31 SSD                                                            | 6         | 1.82%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 1.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.52%   |
| SK hynix BC511                                                                   | 4         | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.21%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.91%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.91%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.61%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.61%   |
| Samsung Electronics SATA controller                                              | 2         | 0.61%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.61%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 186       | 58.68%  |
| NVMe | 92        | 29.02%  |
| IDE  | 23        | 7.26%   |
| RAID | 16        | 5.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 81.71%  |
| AMD    | 45        | 18.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 4.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 3.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 2.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.63%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 1.22%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.22%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.22%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.22%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.22%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.22%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.22%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.81%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.81%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.81%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.81%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.81%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.81%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.81%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.81%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.81%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.81%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 30.08%  |
| Intel Core i7           | 41        | 16.67%  |
| Intel Core i3           | 17        | 6.91%   |
| Intel Core 2 Duo        | 16        | 6.5%    |
| Intel Pentium           | 15        | 6.1%    |
| AMD Ryzen 5             | 15        | 6.1%    |
| Other                   | 14        | 5.69%   |
| AMD Ryzen 7             | 10        | 4.07%   |
| Intel Celeron           | 6         | 2.44%   |
| Intel Pentium Dual      | 4         | 1.63%   |
| Intel Atom              | 4         | 1.63%   |
| AMD Ryzen 3             | 4         | 1.63%   |
| AMD A6                  | 4         | 1.63%   |
| Intel Pentium Silver    | 3         | 1.22%   |
| Intel Pentium Dual-Core | 3         | 1.22%   |
| Intel Core i9           | 3         | 1.22%   |
| AMD E                   | 3         | 1.22%   |
| Intel Pentium M         | 2         | 0.81%   |
| AMD Ryzen 9             | 2         | 0.81%   |
| AMD E1                  | 2         | 0.81%   |
| Intel Celeron M         | 1         | 0.41%   |
| AMD Turion 64 X2 Mobile | 1         | 0.41%   |
| AMD Athlon              | 1         | 0.41%   |
| AMD A4                  | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 124       | 50.41%  |
| 4       | 84        | 34.15%  |
| 6       | 18        | 7.32%   |
| 8       | 14        | 5.69%   |
| 1       | 4         | 1.63%   |
| 14      | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 245       | 99.59%  |
| Unknown | 1         | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 173       | 70.33%  |
| 1       | 72        | 29.27%  |
| Unknown | 1         | 0.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 94.76%  |
| Unknown        | 9         | 3.63%   |
| 32-bit         | 4         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 20.16%  |
| 0x806ea    | 16        | 6.2%    |
| 0x806e9    | 14        | 5.43%   |
| 0x306c3    | 13        | 5.04%   |
| 0x306a9    | 13        | 5.04%   |
| 0x40651    | 11        | 4.26%   |
| 0x906ea    | 10        | 3.88%   |
| 0x806ec    | 10        | 3.88%   |
| 0x6fd      | 8         | 3.1%    |
| 0x806c1    | 7         | 2.71%   |
| 0x206a7    | 6         | 2.33%   |
| 0x1067a    | 6         | 2.33%   |
| 0x0a50000c | 6         | 2.33%   |
| 0x306d4    | 5         | 1.94%   |
| 0x06006705 | 5         | 1.94%   |
| 0x406e3    | 4         | 1.55%   |
| 0x30678    | 4         | 1.55%   |
| 0x10676    | 4         | 1.55%   |
| 0x08600106 | 4         | 1.55%   |
| 0x08600103 | 4         | 1.55%   |
| 0x08108109 | 4         | 1.55%   |
| 0x0810100b | 4         | 1.55%   |
| 0xa0652    | 3         | 1.16%   |
| 0x706e5    | 3         | 1.16%   |
| 0x506c9    | 3         | 1.16%   |
| 0x20655    | 3         | 1.16%   |
| 0x08608103 | 3         | 1.16%   |
| 0x05000119 | 3         | 1.16%   |
| 0x906ed    | 2         | 0.78%   |
| 0x906e9    | 2         | 0.78%   |
| 0x806eb    | 2         | 0.78%   |
| 0x706a1    | 2         | 0.78%   |
| 0x6fb      | 2         | 0.78%   |
| 0x6d8      | 2         | 0.78%   |
| 0x406c4    | 2         | 0.78%   |
| 0x08108102 | 2         | 0.78%   |
| 0x906c0    | 1         | 0.39%   |
| 0x906a3    | 1         | 0.39%   |
| 0x6fa      | 1         | 0.39%   |
| 0x6e8      | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 27.24%  |
| Haswell          | 28        | 11.38%  |
| IvyBridge        | 17        | 6.91%   |
| Penryn           | 12        | 4.88%   |
| TigerLake        | 11        | 4.47%   |
| Core             | 11        | 4.47%   |
| Zen 2            | 10        | 4.07%   |
| Silvermont       | 10        | 4.07%   |
| SandyBridge      | 8         | 3.25%   |
| Zen+             | 7         | 2.85%   |
| Zen 3            | 7         | 2.85%   |
| Skylake          | 7         | 2.85%   |
| Excavator        | 6         | 2.44%   |
| Broadwell        | 6         | 2.44%   |
| Unknown          | 5         | 2.03%   |
| Zen              | 4         | 1.63%   |
| Westmere         | 4         | 1.63%   |
| IceLake          | 4         | 1.63%   |
| Bobcat           | 4         | 1.63%   |
| P6               | 3         | 1.22%   |
| Goldmont plus    | 3         | 1.22%   |
| Goldmont         | 3         | 1.22%   |
| CometLake        | 3         | 1.22%   |
| Tremont          | 1         | 0.41%   |
| Puma             | 1         | 0.41%   |
| K8 Hammer        | 1         | 0.41%   |
| Jaguar           | 1         | 0.41%   |
| Bonnell          | 1         | 0.41%   |
| Alderlake Hybrid | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 178       | 53.78%  |
| Nvidia                           | 84        | 25.38%  |
| AMD                              | 66        | 19.94%  |
| Silicon Integrated Systems [SiS] | 2         | 0.6%    |
| VIA Technologies                 | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 20        | 5.92%   |
| Intel HD Graphics 620                                                                    | 15        | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.66%   |
| AMD Renoir                                                                               | 9         | 2.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.48%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.48%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.48%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.48%   |
| AMD Cezanne                                                                              | 5         | 1.48%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.18%   |
| AMD Lucienne                                                                             | 4         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.89%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.89%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.89%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.89%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 41.06%  |
| Intel + Nvidia | 60        | 24.39%  |
| 1 x AMD        | 37        | 15.04%  |
| Intel + AMD    | 17        | 6.91%   |
| 1 x Nvidia     | 16        | 6.5%    |
| AMD + Nvidia   | 8         | 3.25%   |
| 2 x AMD        | 4         | 1.63%   |
| 1 x SiS        | 2         | 0.81%   |
| 1 x VIA        | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 197       | 79.76%  |
| Proprietary | 42        | 17%     |
| Unknown     | 8         | 3.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 55.29%  |
| 1.01-2.0   | 36        | 14.12%  |
| 0.01-0.5   | 32        | 12.55%  |
| 3.01-4.0   | 27        | 10.59%  |
| 0.51-1.0   | 12        | 4.71%   |
| 7.01-8.0   | 4         | 1.57%   |
| 5.01-6.0   | 2         | 0.78%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 16.67%  |
| LG Display              | 44        | 15.28%  |
| BOE                     | 42        | 14.58%  |
| Chimei Innolux          | 37        | 12.85%  |
| Samsung Electronics     | 33        | 11.46%  |
| Dell                    | 23        | 7.99%   |
| Sharp                   | 9         | 3.13%   |
| Lenovo                  | 5         | 1.74%   |
| Goldstar                | 5         | 1.74%   |
| Chi Mei Optoelectronics | 5         | 1.74%   |
| Apple                   | 4         | 1.39%   |
| PANDA                   | 3         | 1.04%   |
| LG Philips              | 3         | 1.04%   |
| CSO                     | 3         | 1.04%   |
| AOC                     | 3         | 1.04%   |
| Quanta Display          | 2         | 0.69%   |
| InfoVision              | 2         | 0.69%   |
| Hewlett-Packard         | 2         | 0.69%   |
| BenQ                    | 2         | 0.69%   |
| Philips                 | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| NCS                     | 1         | 0.35%   |
| MSI                     | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |
| Iiyama                  | 1         | 0.35%   |
| IBM                     | 1         | 0.35%   |
| HJW                     | 1         | 0.35%   |
| Grundig                 | 1         | 0.35%   |
| Fujitsu Siemens         | 1         | 0.35%   |
| BOE Technology Group    | 1         | 0.35%   |
| Achieva Shimian         | 1         | 0.35%   |
| Acer                    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.35%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 1.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.35%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 1.01%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 1.01%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.01%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.68%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch      | 2         | 0.68%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.68%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.68%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.68%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 2         | 0.68%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 2         | 0.68%   |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                     | 2         | 0.68%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.68%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.68%   |
| Dell U2312HM DEL4072 1920x1080 510x290mm 23.1-inch                        | 2         | 0.68%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                     | 2         | 0.68%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch           | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.68%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.68%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 132       | 49.07%  |
| 1366x768 (WXGA)    | 49        | 18.22%  |
| 1600x900 (HD+)     | 23        | 8.55%   |
| 3840x2160 (4K)     | 13        | 4.83%   |
| 2560x1440 (QHD)    | 9         | 3.35%   |
| 1440x900 (WXGA+)   | 9         | 3.35%   |
| 1280x800 (WXGA)    | 6         | 2.23%   |
| 1920x1200 (WUXGA)  | 5         | 1.86%   |
| 1680x1050 (WSXGA+) | 5         | 1.86%   |
| 2560x1600          | 3         | 1.12%   |
| 2160x1440          | 3         | 1.12%   |
| 3840x2400          | 2         | 0.74%   |
| 1400x1050          | 2         | 0.74%   |
| 3440x1440          | 1         | 0.37%   |
| 2880x1800          | 1         | 0.37%   |
| 1920x1280          | 1         | 0.37%   |
| 1280x960           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |
| 1024x600           | 1         | 0.37%   |
| 1024x576           | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 131       | 45.02%  |
| 17      | 41        | 14.09%  |
| 13      | 24        | 8.25%   |
| 14      | 23        | 7.9%    |
| 27      | 16        | 5.5%    |
| 24      | 12        | 4.12%   |
| 23      | 8         | 2.75%   |
| 12      | 7         | 2.41%   |
| 31      | 5         | 1.72%   |
| 54      | 4         | 1.37%   |
| 21      | 4         | 1.37%   |
| 16      | 4         | 1.37%   |
| Unknown | 3         | 1.03%   |
| 20      | 2         | 0.69%   |
| 10      | 2         | 0.69%   |
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
| 301-350     | 162       | 56.64%  |
| 351-400     | 44        | 15.38%  |
| 501-600     | 29        | 10.14%  |
| 201-300     | 26        | 9.09%   |
| 601-700     | 9         | 3.15%   |
| 401-500     | 8         | 2.8%    |
| 1001-1500   | 4         | 1.4%    |
| Unknown     | 3         | 1.05%   |
| 701-800     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 204       | 82.93%  |
| 16/10   | 31        | 12.6%   |
| 3/2     | 5         | 2.03%   |
| 4/3     | 3         | 1.22%   |
| 5/4     | 1         | 0.41%   |
| 21/9    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 132       | 45.36%  |
| 81-90          | 35        | 12.03%  |
| 121-130        | 33        | 11.34%  |
| 201-250        | 19        | 6.53%   |
| 301-350        | 17        | 5.84%   |
| 71-80          | 11        | 3.78%   |
| 131-140        | 7         | 2.41%   |
| 61-70          | 6         | 2.06%   |
| 351-500        | 6         | 2.06%   |
| More than 1000 | 4         | 1.37%   |
| 251-300        | 4         | 1.37%   |
| 151-200        | 4         | 1.37%   |
| 111-120        | 3         | 1.03%   |
| Unknown        | 3         | 1.03%   |
| 41-50          | 2         | 0.69%   |
| 141-150        | 2         | 0.69%   |
| 91-100         | 2         | 0.69%   |
| 51-60          | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 134       | 47.69%  |
| 101-120       | 74        | 26.33%  |
| 51-100        | 46        | 16.37%  |
| 161-240       | 15        | 5.34%   |
| 1-50          | 5         | 1.78%   |
| More than 240 | 4         | 1.42%   |
| Unknown       | 3         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 193       | 75.1%   |
| 2     | 49        | 19.07%  |
| 0     | 9         | 3.5%    |
| 3     | 5         | 1.95%   |
| 4     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 141       | 34.9%   |
| Intel                             | 127       | 31.44%  |
| Qualcomm Atheros                  | 67        | 16.58%  |
| Broadcom                          | 21        | 5.2%    |
| MediaTek                          | 9         | 2.23%   |
| Broadcom Limited                  | 6         | 1.49%   |
| Samsung Electronics               | 4         | 0.99%   |
| TP-Link                           | 3         | 0.74%   |
| Marvell Technology Group          | 3         | 0.74%   |
| Xiaomi                            | 2         | 0.5%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.5%    |
| Ralink                            | 2         | 0.5%    |
| Qualcomm Atheros Communications   | 2         | 0.5%    |
| Qualcomm                          | 2         | 0.5%    |
| Lenovo                            | 2         | 0.5%    |
| D-Link                            | 2         | 0.5%    |
| VIA Technologies                  | 1         | 0.25%   |
| Nvidia                            | 1         | 0.25%   |
| HTC (High Tech Computer)          | 1         | 0.25%   |
| Hewlett-Packard                   | 1         | 0.25%   |
| FIBOCOM                           | 1         | 0.25%   |
| Ericsson Business Mobile Networks | 1         | 0.25%   |
| DisplayLink                       | 1         | 0.25%   |
| Dell                              | 1         | 0.25%   |
| ASIX Electronics                  | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 111       | 23.37%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.21%   |
| Intel Wireless 8265 / 8275                                              | 19        | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 3.16%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.68%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.47%   |
| Intel Wireless 7260                                                     | 7         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.26%   |
| Intel Wireless 7265                                                     | 6         | 1.26%   |
| Intel Wireless 3165                                                     | 6         | 1.26%   |
| Intel Wireless 3160                                                     | 6         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.84%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.63%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.63%   |
| Intel WiFi Link 5100                                                    | 3         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.63%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 50.4%   |
| Qualcomm Atheros                | 58        | 23.2%   |
| Realtek Semiconductor           | 26        | 10.4%   |
| Broadcom                        | 14        | 5.6%    |
| MediaTek                        | 9         | 3.6%    |
| Broadcom Limited                | 4         | 1.6%    |
| TP-Link                         | 3         | 1.2%    |
| Ralink                          | 2         | 0.8%    |
| Qualcomm Atheros Communications | 2         | 0.8%    |
| Qualcomm                        | 2         | 0.8%    |
| D-Link                          | 2         | 0.8%    |
| FIBOCOM                         | 1         | 0.4%    |
| Dell                            | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 8%      |
| Intel Wireless 8265 / 8275                                              | 19        | 7.6%    |
| Intel Wi-Fi 6 AX200                                                     | 15        | 6%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.8%    |
| Intel Wireless 7260                                                     | 7         | 2.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.4%    |
| Intel Wireless 7265                                                     | 6         | 2.4%    |
| Intel Wireless 3165                                                     | 6         | 2.4%    |
| Intel Wireless 3160                                                     | 6         | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2%      |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.2%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.2%    |
| Intel WiFi Link 5100                                                    | 3         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.2%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.8%    |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.8%    |
| Intel Wireless 8260                                                     | 2         | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.8%    |
| Intel Centrino Wireless-N 100                                           | 2         | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.8%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 134       | 60.36%  |
| Intel                            | 42        | 18.92%  |
| Qualcomm Atheros                 | 19        | 8.56%   |
| Broadcom                         | 7         | 3.15%   |
| Samsung Electronics              | 4         | 1.8%    |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 111       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 6.76%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 3.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 2.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.8%    |
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
| WiFi     | 243       | 53.17%  |
| Ethernet | 211       | 46.17%  |
| Modem    | 3         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 79.62%  |
| Ethernet | 54        | 20.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 198       | 80.49%  |
| 1     | 46        | 18.7%   |
| 0     | 2         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 237       | 95.95%  |
| Yes  | 10        | 4.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 47.32%  |
| Lite-On Technology              | 23        | 11.22%  |
| Qualcomm Atheros Communications | 19        | 9.27%   |
| Realtek Semiconductor           | 15        | 7.32%   |
| IMC Networks                    | 14        | 6.83%   |
| Broadcom                        | 8         | 3.9%    |
| Foxconn / Hon Hai               | 7         | 3.41%   |
| Hewlett-Packard                 | 6         | 2.93%   |
| Cambridge Silicon Radio         | 4         | 1.95%   |
| Apple                           | 4         | 1.95%   |
| Toshiba                         | 3         | 1.46%   |
| Foxconn International           | 3         | 1.46%   |
| Realtek                         | 1         | 0.49%   |
| Dell                            | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 21.95%  |
| Intel AX200 Bluetooth                               | 15        | 7.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 6.83%   |
| Intel AX201 Bluetooth                               | 13        | 6.34%   |
| Realtek Bluetooth Radio                             | 12        | 5.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 5.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.41%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 2.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.95%   |
| Lite-On Wireless_Device                             | 3         | 1.46%   |
| Lite-On Bluetooth Device                            | 3         | 1.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.46%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.46%   |
| IMC Networks Wireless_Device                        | 3         | 1.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.46%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.98%   |
| IMC Networks Bluetooth Device                       | 2         | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.98%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.98%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.49%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.49%   |
| Toshiba Bluetooth Device                            | 1         | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.49%   |
| Realtek Bluetooth Radio                             | 1         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.49%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.49%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.49%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 195       | 63.73%  |
| AMD                              | 51        | 16.67%  |
| Nvidia                           | 33        | 10.78%  |
| C-Media Electronics              | 5         | 1.63%   |
| Logitech                         | 3         | 0.98%   |
| Lenovo                           | 3         | 0.98%   |
| JMTek                            | 3         | 0.98%   |
| Silicon Integrated Systems [SiS] | 2         | 0.65%   |
| ZOOM                             | 1         | 0.33%   |
| YZ Technology                    | 1         | 0.33%   |
| VIA Technologies                 | 1         | 0.33%   |
| Trust                            | 1         | 0.33%   |
| Texas Instruments                | 1         | 0.33%   |
| SteelSeries ApS                  | 1         | 0.33%   |
| Samson Technologies              | 1         | 0.33%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| Plantronics                      | 1         | 0.33%   |
| Pioneer DJ                       | 1         | 0.33%   |
| GN Netcom                        | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 10.99%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 8.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 4.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.75%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.61%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.34%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.8%    |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.8%    |
| AMD FCH Azalia Controller                                                                         | 3         | 0.8%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.54%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.54%   |
| Nvidia Audio device                                                                               | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 29.19%  |
| SK hynix            | 36        | 22.36%  |
| Kingston            | 24        | 14.91%  |
| Micron Technology   | 22        | 13.66%  |
| Crucial             | 9         | 5.59%   |
| Unknown             | 7         | 4.35%   |
| Ramaxel Technology  | 4         | 2.48%   |
| Patriot             | 2         | 1.24%   |
| Elpida              | 2         | 1.24%   |
| A-DATA Technology   | 2         | 1.24%   |
| Transcend           | 1         | 0.62%   |
| Qimonda             | 1         | 0.62%   |
| G.Skill             | 1         | 0.62%   |
| Corsair             | 1         | 0.62%   |
| Avant               | 1         | 0.62%   |
| 48spaces            | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 3.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 2.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 3         | 1.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 3         | 1.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 3         | 1.7%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 3         | 1.7%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 1.14%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 2         | 1.14%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 1.14%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 1.14%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.14%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s         | 2         | 1.14%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 1.14%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s       | 2         | 1.14%   |
| Kingston RAM 9905700-047.A00G 16GB SODIMM DDR4 2667MT/s       | 2         | 1.14%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                   | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                    | 1         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                 | 1         | 0.57%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s            | 1         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.57%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.57%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 0.57%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.57%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 0.57%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s              | 1         | 0.57%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 66        | 50%     |
| DDR3   | 44        | 33.33%  |
| LPDDR3 | 8         | 6.06%   |
| DDR2   | 8         | 6.06%   |
| LPDDR4 | 5         | 3.79%   |
| SDRAM  | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 87.12%  |
| Row Of Chips | 15        | 11.36%  |
| DIMM         | 1         | 0.76%   |
| Chip         | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 57        | 39.31%  |
| 4096  | 47        | 32.41%  |
| 16384 | 21        | 14.48%  |
| 2048  | 11        | 7.59%   |
| 1024  | 6         | 4.14%   |
| 32768 | 3         | 2.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 36        | 25%     |
| 1600  | 34        | 23.61%  |
| 3200  | 26        | 18.06%  |
| 2133  | 9         | 6.25%   |
| 2400  | 8         | 5.56%   |
| 1334  | 6         | 4.17%   |
| 667   | 6         | 4.17%   |
| 1333  | 3         | 2.08%   |
| 1066  | 3         | 2.08%   |
| 4267  | 2         | 1.39%   |
| 1867  | 2         | 1.39%   |
| 8400  | 1         | 0.69%   |
| 4266  | 1         | 0.69%   |
| 3266  | 1         | 0.69%   |
| 3000  | 1         | 0.69%   |
| 2048  | 1         | 0.69%   |
| 1067  | 1         | 0.69%   |
| 975   | 1         | 0.69%   |
| 800   | 1         | 0.69%   |
| 533   | 1         | 0.69%   |

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
| Chicony Electronics                    | 67        | 29.39%  |
| IMC Networks                           | 26        | 11.4%   |
| Quanta                                 | 21        | 9.21%   |
| Realtek Semiconductor                  | 20        | 8.77%   |
| Acer                                   | 16        | 7.02%   |
| Microdia                               | 15        | 6.58%   |
| Suyin                                  | 10        | 4.39%   |
| Sunplus Innovation Technology          | 9         | 3.95%   |
| Lite-On Technology                     | 8         | 3.51%   |
| Syntek                                 | 7         | 3.07%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.63%   |
| Luxvisions Innotech Limited            | 3         | 1.32%   |
| Logitech                               | 3         | 1.32%   |
| Apple                                  | 3         | 1.32%   |
| Silicon Motion                         | 2         | 0.88%   |
| Primax Electronics                     | 2         | 0.88%   |
| Jieli Technology                       | 2         | 0.88%   |
| Anker                                  | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| Ricoh                                  | 1         | 0.44%   |
| Goertek Electronics                    | 1         | 0.44%   |
| Genesys Logic                          | 1         | 0.44%   |
| Cubeternet                             | 1         | 0.44%   |
| AVerMedia Technologies                 | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 14        | 6.14%   |
| Chicony Integrated Camera                     | 12        | 5.26%   |
| IMC Networks Integrated Camera                | 10        | 4.39%   |
| Quanta VGA WebCam                             | 8         | 3.51%   |
| Microdia Integrated_Webcam_HD                 | 8         | 3.51%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 7         | 3.07%   |
| Realtek Integrated_Webcam_HD                  | 5         | 2.19%   |
| Lite-On HP HD Camera                          | 5         | 2.19%   |
| Acer Lenovo EasyCamera                        | 5         | 2.19%   |
| Quanta HD Webcam                              | 4         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 1.75%   |
| Acer Integrated Camera                        | 4         | 1.75%   |
| Syntek Integrated Camera                      | 3         | 1.32%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 3         | 1.32%   |
| Sunplus Asus Webcam                           | 3         | 1.32%   |
| Realtek Lenovo EasyCamera                     | 3         | 1.32%   |
| Quanta HP TrueVision HD Camera                | 3         | 1.32%   |
| Quanta HD User Facing                         | 3         | 1.32%   |
| Chicony USB2.0 VGA UVC WebCam                 | 3         | 1.32%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 1.32%   |
| Chicony Integrated HP HD Webcam               | 3         | 1.32%   |
| Chicony HP Wide Vision HD Camera              | 3         | 1.32%   |
| Chicony HP Webcam                             | 3         | 1.32%   |
| Suyin WebCam                                  | 2         | 0.88%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 0.88%   |
| Sunplus HD WebCam                             | 2         | 0.88%   |
| Realtek Integrated Webcam                     | 2         | 0.88%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 0.88%   |
| Quanta HP HD Camera                           | 2         | 0.88%   |
| Primax HP HD Webcam [Fixed]                   | 2         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_HD          | 2         | 0.88%   |
| Microdia Integrated Webcam                    | 2         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.88%   |
| Lite-On Integrated Camera                     | 2         | 0.88%   |
| Jieli USB PHY 2.0                             | 2         | 0.88%   |
| IMC Networks HD Camera                        | 2         | 0.88%   |
| Chicony USB 2.0 Camera                        | 2         | 0.88%   |
| Chicony ThinkPad T490 Webcam                  | 2         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 0.88%   |

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
| 0     | 152       | 59.61%  |
| 1     | 83        | 32.55%  |
| 2     | 18        | 7.06%   |
| 3     | 2         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 47.93%  |
| Graphics card            | 27        | 22.31%  |
| Net/wireless             | 11        | 9.09%   |
| Chipcard                 | 8         | 6.61%   |
| Multimedia controller    | 6         | 4.96%   |
| Card reader              | 3         | 2.48%   |
| Communication controller | 2         | 1.65%   |
| Camera                   | 2         | 1.65%   |
| Storage/ide              | 1         | 0.83%   |
| Storage                  | 1         | 0.83%   |
| Sound                    | 1         | 0.83%   |
| Modem                    | 1         | 0.83%   |

