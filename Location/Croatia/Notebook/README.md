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

Total: 359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | XPS 15 9500                 | [f59cdbcb8d](https://linux-hardware.org/?probe=f59cdbcb8d) | Jul 07, 2022 |
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 49        | 18.63%  |
| Ubuntu 18.04                 | 18        | 6.84%   |
| Debian 11                    | 8         | 3.04%   |
| Pop!_OS 21.04                | 7         | 2.66%   |
| Ubuntu 22.04                 | 6         | 2.28%   |
| Pop!_OS 20.04                | 6         | 2.28%   |
| OpenMandriva 4.3             | 6         | 2.28%   |
| Ubuntu 19.04                 | 5         | 1.9%    |
| Fedora 36                    | 5         | 1.9%    |
| Fedora 35                    | 5         | 1.9%    |
| Ubuntu 21.04                 | 4         | 1.52%   |
| Pop!_OS 20.10                | 4         | 1.52%   |
| Linux Mint 20.2              | 4         | 1.52%   |
| KDE neon 20.04               | 4         | 1.52%   |
| Endless 3.7.8                | 4         | 1.52%   |
| Zorin 16                     | 3         | 1.14%   |
| Zorin 15                     | 3         | 1.14%   |
| Ubuntu 20.10                 | 3         | 1.14%   |
| Ubuntu 19.10                 | 3         | 1.14%   |
| Ubuntu 18.10                 | 3         | 1.14%   |
| ROSA R10                     | 3         | 1.14%   |
| Pop!_OS 21.10                | 3         | 1.14%   |
| OpenMandriva 4.2             | 3         | 1.14%   |
| Endless 3.9.5                | 3         | 1.14%   |
| Endless 3.9.4                | 3         | 1.14%   |
| Arch Rolling                 | 3         | 1.14%   |
| Arch                         | 3         | 1.14%   |
| Ubuntu 21.10                 | 2         | 0.76%   |
| Pop!_OS 22.04                | 2         | 0.76%   |
| Manjaro 21.0.7               | 2         | 0.76%   |
| Manjaro 21.0                 | 2         | 0.76%   |
| Manjaro 20.2.1               | 2         | 0.76%   |
| Manjaro 20.2                 | 2         | 0.76%   |
| Manjaro 20.1.2               | 2         | 0.76%   |
| Manjaro 18.1.5               | 2         | 0.76%   |
| Linux Mint 20.3              | 2         | 0.76%   |
| Linux Mint 20                | 2         | 0.76%   |
| Linux Mint 19.3              | 2         | 0.76%   |
| Kubuntu 21.04                | 2         | 0.76%   |
| Kubuntu 20.04                | 2         | 0.76%   |
| Fedora 34                    | 2         | 0.76%   |
| Fedora 33                    | 2         | 0.76%   |
| Endless 3.9.3                | 2         | 0.76%   |
| Endless 3.8.3                | 2         | 0.76%   |
| Debian 10                    | 2         | 0.76%   |
| ArcoLinux Rolling            | 2         | 0.76%   |
| Xubuntu 18.04                | 1         | 0.38%   |
| Ubuntu MATE 20.04            | 1         | 0.38%   |
| Ubuntu MATE 18.04            | 1         | 0.38%   |
| Ubuntu Budgie 20.04          | 1         | 0.38%   |
| ROSA R9                      | 1         | 0.38%   |
| ROSA R8.1                    | 1         | 0.38%   |
| ROSA R8                      | 1         | 0.38%   |
| Parrot 4.9                   | 1         | 0.38%   |
| Parrot 4.8                   | 1         | 0.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.38%   |
| openSUSE Leap-15.1           | 1         | 0.38%   |
| OpenMandriva 4.50            | 1         | 0.38%   |
| Manjaro 21.2.5               | 1         | 0.38%   |
| Manjaro 21.0.1               | 1         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 83        | 35.47%  |
| Pop!_OS       | 21        | 8.97%   |
| Endless       | 21        | 8.97%   |
| Fedora        | 15        | 6.41%   |
| Linux Mint    | 14        | 5.98%   |
| Manjaro       | 12        | 5.13%   |
| OpenMandriva  | 10        | 4.27%   |
| Debian        | 10        | 4.27%   |
| Kubuntu       | 7         | 2.99%   |
| Zorin         | 6         | 2.56%   |
| ROSA          | 6         | 2.56%   |
| Arch          | 6         | 2.56%   |
| KDE neon      | 4         | 1.71%   |
| Ubuntu MATE   | 2         | 0.85%   |
| openSUSE      | 2         | 0.85%   |
| Kali          | 2         | 0.85%   |
| EndeavourOS   | 2         | 0.85%   |
| Elementary    | 2         | 0.85%   |
| ArcoLinux     | 2         | 0.85%   |
| Xubuntu       | 1         | 0.43%   |
| Ubuntu Budgie | 1         | 0.43%   |
| Parrot        | 1         | 0.43%   |
| LMDE          | 1         | 0.43%   |
| LinuxFX       | 1         | 0.43%   |
| Gentoo        | 1         | 0.43%   |
| CentOS        | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 6         | 2.1%    |
| 5.16.7-desktop-1omv4003         | 6         | 2.1%    |
| 5.11.0-38-generic               | 6         | 2.1%    |
| 5.4.0-42-generic                | 5         | 1.75%   |
| 5.11.0-7620-generic             | 5         | 1.75%   |
| 5.3.0-28-generic                | 4         | 1.4%    |
| 5.13.0-30-generic               | 4         | 1.4%    |
| 5.8.16-2-MANJARO                | 3         | 1.05%   |
| 5.8.0-7630-generic              | 3         | 1.05%   |
| 5.8.0-59-generic                | 3         | 1.05%   |
| 5.8.0-43-generic                | 3         | 1.05%   |
| 5.4.0-52-generic                | 3         | 1.05%   |
| 5.4.0-48-generic                | 3         | 1.05%   |
| 5.4.0-47-generic                | 3         | 1.05%   |
| 5.4.0-37-generic                | 3         | 1.05%   |
| 5.4.0-29-generic                | 3         | 1.05%   |
| 5.4.0-19-generic                | 3         | 1.05%   |
| 5.15.0-40-generic               | 3         | 1.05%   |
| 5.13.0-7620-generic             | 3         | 1.05%   |
| 5.11.0-41-generic               | 3         | 1.05%   |
| 5.11.0-40-generic               | 3         | 1.05%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.05%   |
| 4.18.0-18-generic               | 3         | 1.05%   |
| 5.9.16-1-MANJARO                | 2         | 0.7%    |
| 5.8.0-49-generic                | 2         | 0.7%    |
| 5.8.0-48-generic                | 2         | 0.7%    |
| 5.4.0-91-generic                | 2         | 0.7%    |
| 5.4.0-84-generic                | 2         | 0.7%    |
| 5.4.0-7642-generic              | 2         | 0.7%    |
| 5.4.0-58-generic                | 2         | 0.7%    |
| 5.4.0-54-generic                | 2         | 0.7%    |
| 5.4.0-40-generic                | 2         | 0.7%    |
| 5.3.0-23-generic                | 2         | 0.7%    |
| 5.16.11-76051611-generic        | 2         | 0.7%    |
| 5.15.0-27-generic               | 2         | 0.7%    |
| 5.13.0-52-generic               | 2         | 0.7%    |
| 5.11.0-35-generic               | 2         | 0.7%    |
| 5.11.0-34-generic               | 2         | 0.7%    |
| 5.11.0-27-generic               | 2         | 0.7%    |
| 5.11.0-25-generic               | 2         | 0.7%    |
| 5.10.0-9-amd64                  | 2         | 0.7%    |
| 5.0.0-20-generic                | 2         | 0.7%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.7%    |
| 4.18.0-15-generic               | 2         | 0.7%    |
| 4.15.0-23-generic               | 2         | 0.7%    |
| 5.9.9-arch1-1                   | 1         | 0.35%   |
| 5.9.16-200.fc33.x86_64          | 1         | 0.35%   |
| 5.9.16-050916-generic           | 1         | 0.35%   |
| 5.9.11-arch2-1                  | 1         | 0.35%   |
| 5.9.11-3-MANJARO                | 1         | 0.35%   |
| 5.9.1-gentoo                    | 1         | 0.35%   |
| 5.8.6-1-MANJARO                 | 1         | 0.35%   |
| 5.8.0-7625-generic              | 1         | 0.35%   |
| 5.8.0-63-lowlatency             | 1         | 0.35%   |
| 5.8.0-63-generic                | 1         | 0.35%   |
| 5.8.0-51-generic                | 1         | 0.35%   |
| 5.8.0-31-generic                | 1         | 0.35%   |
| 5.7.11-arch1-1                  | 1         | 0.35%   |
| 5.6.6-300.fc32.x86_64           | 1         | 0.35%   |
| 5.6.2-050602-generic            | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 18.59%  |
| 5.11.0  | 31        | 11.52%  |
| 5.8.0   | 20        | 7.43%   |
| 5.13.0  | 15        | 5.58%   |
| 4.15.0  | 15        | 5.58%   |
| 5.3.0   | 11        | 4.09%   |
| 5.0.0   | 10        | 3.72%   |
| 4.18.0  | 10        | 3.72%   |
| 5.15.0  | 9         | 3.35%   |
| 5.10.0  | 8         | 2.97%   |
| 5.16.7  | 7         | 2.6%    |
| 5.9.16  | 4         | 1.49%   |
| 5.8.16  | 3         | 1.12%   |
| 5.10.14 | 3         | 1.12%   |
| 4.9.60  | 3         | 1.12%   |
| 4.19.0  | 3         | 1.12%   |
| 5.9.11  | 2         | 0.74%   |
| 5.5.0   | 2         | 0.74%   |
| 5.16.11 | 2         | 0.74%   |
| 5.15.8  | 2         | 0.74%   |
| 5.14.0  | 2         | 0.74%   |
| 5.9.9   | 1         | 0.37%   |
| 5.9.1   | 1         | 0.37%   |
| 5.8.6   | 1         | 0.37%   |
| 5.7.11  | 1         | 0.37%   |
| 5.6.6   | 1         | 0.37%   |
| 5.6.2   | 1         | 0.37%   |
| 5.6.19  | 1         | 0.37%   |
| 5.6.0   | 1         | 0.37%   |
| 5.4.74  | 1         | 0.37%   |
| 5.4.17  | 1         | 0.37%   |
| 5.4.13  | 1         | 0.37%   |
| 5.3.8   | 1         | 0.37%   |
| 5.3.18  | 1         | 0.37%   |
| 5.2.10  | 1         | 0.37%   |
| 5.18.9  | 1         | 0.37%   |
| 5.18.5  | 1         | 0.37%   |
| 5.18.11 | 1         | 0.37%   |
| 5.17.7  | 1         | 0.37%   |
| 5.17.5  | 1         | 0.37%   |
| 5.17.4  | 1         | 0.37%   |
| 5.17.15 | 1         | 0.37%   |
| 5.17.1  | 1         | 0.37%   |
| 5.16.9  | 1         | 0.37%   |
| 5.16.8  | 1         | 0.37%   |
| 5.16.14 | 1         | 0.37%   |
| 5.16.12 | 1         | 0.37%   |
| 5.15.7  | 1         | 0.37%   |
| 5.15.3  | 1         | 0.37%   |
| 5.15.16 | 1         | 0.37%   |
| 5.15.15 | 1         | 0.37%   |
| 5.14.9  | 1         | 0.37%   |
| 5.13.19 | 1         | 0.37%   |
| 5.13.13 | 1         | 0.37%   |
| 5.13.12 | 1         | 0.37%   |
| 5.12.4  | 1         | 0.37%   |
| 5.12.12 | 1         | 0.37%   |
| 5.11.6  | 1         | 0.37%   |
| 5.11.22 | 1         | 0.37%   |
| 5.11.16 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 20.08%  |
| 5.11    | 36        | 13.64%  |
| 5.8     | 24        | 9.09%   |
| 5.13    | 18        | 6.82%   |
| 5.10    | 16        | 6.06%   |
| 4.15    | 15        | 5.68%   |
| 5.15    | 14        | 5.3%    |
| 5.3     | 12        | 4.55%   |
| 5.16    | 12        | 4.55%   |
| 5.0     | 11        | 4.17%   |
| 4.18    | 10        | 3.79%   |
| 5.9     | 8         | 3.03%   |
| 5.17    | 5         | 1.89%   |
| 4.9     | 5         | 1.89%   |
| 5.6     | 4         | 1.52%   |
| 5.18    | 3         | 1.14%   |
| 5.14    | 3         | 1.14%   |
| 4.19    | 3         | 1.14%   |
| 5.5     | 2         | 0.76%   |
| 5.12    | 2         | 0.76%   |
| 5.7     | 1         | 0.38%   |
| 5.2     | 1         | 0.38%   |
| 5.1     | 1         | 0.38%   |
| 4.17    | 1         | 0.38%   |
| 4.16    | 1         | 0.38%   |
| 4.12    | 1         | 0.38%   |
| 4.1     | 1         | 0.38%   |
| 3.10    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 222       | 97.8%   |
| i686   | 5         | 2.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 121       | 50%     |
| Unknown         | 35        | 14.46%  |
| KDE5            | 34        | 14.05%  |
| X-Cinnamon      | 9         | 3.72%   |
| XFCE            | 6         | 2.48%   |
| KDE             | 6         | 2.48%   |
| Cinnamon        | 6         | 2.48%   |
| MATE            | 5         | 2.07%   |
| KDE4            | 4         | 1.65%   |
| GNOME Flashback | 4         | 1.65%   |
| DWM             | 3         | 1.24%   |
| Unity           | 2         | 0.83%   |
| Pantheon        | 2         | 0.83%   |
| Budgie          | 2         | 0.83%   |
| LXQt            | 1         | 0.41%   |
| i3              | 1         | 0.41%   |
| bspwm           | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 185       | 75.51%  |
| Wayland | 30        | 12.24%  |
| Unknown | 27        | 11.02%  |
| Tty     | 3         | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 117       | 50%     |
| GDM     | 47        | 20.09%  |
| SDDM    | 30        | 12.82%  |
| GDM3    | 15        | 6.41%   |
| LightDM | 11        | 4.7%    |
| TDM     | 10        | 4.27%   |
| KDM     | 3         | 1.28%   |
| Ly      | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 120       | 51.06%  |
| hr_HR   | 57        | 24.26%  |
| Unknown | 38        | 16.17%  |
| en_GB   | 8         | 3.4%    |
| de_DE   | 5         | 2.13%   |
| C       | 4         | 1.7%    |
| hr_BA   | 1         | 0.43%   |
| fr_FR   | 1         | 0.43%   |
| en_DE   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 141       | 60%     |
| BIOS | 94        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 184       | 78.3%   |
| Unknown | 16        | 6.81%   |
| Overlay | 13        | 5.53%   |
| Btrfs   | 11        | 4.68%   |
| Zfs     | 4         | 1.7%    |
| Xfs     | 4         | 1.7%    |
| Ext2    | 2         | 0.85%   |
| Jfs     | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 127       | 55.22%  |
| GPT     | 81        | 35.22%  |
| MBR     | 22        | 9.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 216       | 93.51%  |
| Yes       | 15        | 6.49%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 77.49%  |
| Yes       | 52        | 22.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 60        | 26.43%  |
| Hewlett-Packard         | 47        | 20.7%   |
| Acer                    | 39        | 17.18%  |
| ASUSTek Computer        | 28        | 12.33%  |
| Dell                    | 25        | 11.01%  |
| Toshiba                 | 6         | 2.64%   |
| Apple                   | 4         | 1.76%   |
| Samsung Electronics     | 3         | 1.32%   |
| eMachines               | 3         | 1.32%   |
| HUAWEI                  | 2         | 0.88%   |
| Fujitsu Siemens         | 2         | 0.88%   |
| TUXEDO                  | 1         | 0.44%   |
| System76                | 1         | 0.44%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.44%   |
| Razer                   | 1         | 0.44%   |
| Notebook                | 1         | 0.44%   |
| Medion                  | 1         | 0.44%   |
| Gigabyte Technology     | 1         | 0.44%   |
| Chuwi                   | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-21                        | 4         | 1.76%   |
| Lenovo G710 20252                          | 3         | 1.32%   |
| Acer Aspire A515-51G                       | 3         | 1.32%   |
| Lenovo Z50-70 20354                        | 2         | 0.88%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.88%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.88%   |
| Lenovo G40-30 80FY                         | 2         | 0.88%   |
| HP ProBook 450 G7                          | 2         | 0.88%   |
| HP EliteBook 850 G6                        | 2         | 0.88%   |
| HP 2000                                    | 2         | 0.88%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.88%   |
| Dell XPS 13 9310                           | 2         | 0.88%   |
| Dell Vostro 3500                           | 2         | 0.88%   |
| ASUS X751NV                                | 2         | 0.88%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.88%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.88%   |
| Acer Aspire E5-771G                        | 2         | 0.88%   |
| Acer Aspire A715-72G                       | 2         | 0.88%   |
| Acer Aspire 7739G                          | 2         | 0.88%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.44%   |
| Toshiba Satellite P200                     | 1         | 0.44%   |
| Toshiba Satellite L750                     | 1         | 0.44%   |
| Toshiba Satellite L50-B                    | 1         | 0.44%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.44%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.44%   |
| Toshiba Satellite A300                     | 1         | 0.44%   |
| System76 Oryx Pro                          | 1         | 0.44%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.44%   |
| Samsung N150/N210/N220                     | 1         | 0.44%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.44%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.44%   |
| Razer Blade                                | 1         | 0.44%   |
| Notebook MAM2080                           | 1         | 0.44%   |
| Medion P6618                               | 1         | 0.44%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.44%   |
| Lenovo Y50-70 20378                        | 1         | 0.44%   |
| Lenovo V340-17IWL 81RG                     | 1         | 0.44%   |
| Lenovo ThinkPad X260 20F5S0JF00            | 1         | 0.44%   |
| Lenovo ThinkPad X240 20AMS30A01            | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JSC   | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00   | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS7SE00   | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR005YSC   | 1         | 0.44%   |
| Lenovo ThinkPad W540 20BHS04K00            | 1         | 0.44%   |
| Lenovo ThinkPad T61 6458AU9                | 1         | 0.44%   |
| Lenovo ThinkPad T580 20LAS27000            | 1         | 0.44%   |
| Lenovo ThinkPad T490s 20NXCTO1WW           | 1         | 0.44%   |
| Lenovo ThinkPad T480s 20L8S23300           | 1         | 0.44%   |
| Lenovo ThinkPad T460 20FMS0X022            | 1         | 0.44%   |
| Lenovo ThinkPad T450s 20BWS2US00           | 1         | 0.44%   |
| Lenovo ThinkPad T440p 20AWS1HK0P           | 1         | 0.44%   |
| Lenovo ThinkPad T440 20B7S14N0U            | 1         | 0.44%   |
| Lenovo ThinkPad T430 2349AK2               | 1         | 0.44%   |
| Lenovo ThinkPad T410 2522DK2               | 1         | 0.44%   |
| Lenovo ThinkPad T15 Gen 1 20S6000USC       | 1         | 0.44%   |
| Lenovo ThinkPad P53 20QNZ4RBUS             | 1         | 0.44%   |
| Lenovo ThinkPad P1 20MES1T700              | 1         | 0.44%   |
| Lenovo ThinkPad L15 Gen 1 20U70001SC       | 1         | 0.44%   |
| Lenovo ThinkPad E590 20NB006MSC            | 1         | 0.44%   |
| Lenovo ThinkPad E580 20KS005ASC            | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 34        | 14.98%  |
| Lenovo ThinkPad               | 27        | 11.89%  |
| HP ProBook                    | 10        | 4.41%   |
| HP EliteBook                  | 10        | 4.41%   |
| ASUS VivoBook                 | 8         | 3.52%   |
| Dell XPS                      | 7         | 3.08%   |
| Dell Vostro                   | 7         | 3.08%   |
| Toshiba Satellite             | 6         | 2.64%   |
| Lenovo ThinkBook              | 6         | 2.64%   |
| Lenovo IdeaPad                | 6         | 2.64%   |
| HP Pavilion                   | 6         | 2.64%   |
| Lenovo Legion                 | 5         | 2.2%    |
| Dell Inspiron                 | 5         | 2.2%    |
| HP Laptop                     | 4         | 1.76%   |
| HP 250                        | 4         | 1.76%   |
| Dell Latitude                 | 4         | 1.76%   |
| Lenovo G710                   | 3         | 1.32%   |
| HP Compaq                     | 3         | 1.32%   |
| Acer Swift                    | 3         | 1.32%   |
| Lenovo Z50-70                 | 2         | 0.88%   |
| Lenovo G40-30                 | 2         | 0.88%   |
| Lenovo B590                   | 2         | 0.88%   |
| HP OMEN                       | 2         | 0.88%   |
| HP 2000                       | 2         | 0.88%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.88%   |
| ASUS ZenBook                  | 2         | 0.88%   |
| ASUS X751NV                   | 2         | 0.88%   |
| ASUS ROG                      | 2         | 0.88%   |
| TUXEDO Pulse                  | 1         | 0.44%   |
| System76 Oryx                 | 1         | 0.44%   |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.44%   |
| Samsung N150                  | 1         | 0.44%   |
| Samsung 300E4C                | 1         | 0.44%   |
| Samsung 300E4A                | 1         | 0.44%   |
| Razer Blade                   | 1         | 0.44%   |
| Notebook MAM2080              | 1         | 0.44%   |
| Medion P6618                  | 1         | 0.44%   |
| Lenovo Y520-15IKBN            | 1         | 0.44%   |
| Lenovo Y50-70                 | 1         | 0.44%   |
| Lenovo V340-17IWL             | 1         | 0.44%   |
| Lenovo G500                   | 1         | 0.44%   |
| Lenovo G50-45                 | 1         | 0.44%   |
| Lenovo G50-30                 | 1         | 0.44%   |
| Lenovo B50-70                 | 1         | 0.44%   |
| HUAWEI WRTB-WXX9              | 1         | 0.44%   |
| HUAWEI KLVL-WXX9              | 1         | 0.44%   |
| HP ZBook                      | 1         | 0.44%   |
| HP Presario                   | 1         | 0.44%   |
| HP Notebook                   | 1         | 0.44%   |
| HP 255                        | 1         | 0.44%   |
| HP 2140                       | 1         | 0.44%   |
| Gigabyte G5                   | 1         | 0.44%   |
| eMachines G725                | 1         | 0.44%   |
| eMachines E725                | 1         | 0.44%   |
| eMachines E525                | 1         | 0.44%   |
| Dell Precision                | 1         | 0.44%   |
| Dell G3                       | 1         | 0.44%   |
| Chuwi GemiBook                | 1         | 0.44%   |
| ASUS X75A1                    | 1         | 0.44%   |
| ASUS X71Sr                    | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 33        | 14.54%  |
| 2019 | 23        | 10.13%  |
| 2017 | 23        | 10.13%  |
| 2020 | 20        | 8.81%   |
| 2013 | 19        | 8.37%   |
| 2016 | 17        | 7.49%   |
| 2021 | 16        | 7.05%   |
| 2014 | 16        | 7.05%   |
| 2011 | 15        | 6.61%   |
| 2012 | 9         | 3.96%   |
| 2007 | 9         | 3.96%   |
| 2015 | 8         | 3.52%   |
| 2009 | 6         | 2.64%   |
| 2008 | 6         | 2.64%   |
| 2010 | 5         | 2.2%    |
| 2006 | 2         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 227       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 201       | 88.16%  |
| Enabled  | 27        | 11.84%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 227       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 78        | 33.62%  |
| 8.01-16.0   | 44        | 18.97%  |
| 3.01-4.0    | 41        | 17.67%  |
| 16.01-24.0  | 34        | 14.66%  |
| 32.01-64.0  | 16        | 6.9%    |
| 1.01-2.0    | 10        | 4.31%   |
| 24.01-32.0  | 4         | 1.72%   |
| 2.01-3.0    | 4         | 1.72%   |
| 64.01-256.0 | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 94        | 35.74%  |
| 2.01-3.0   | 62        | 23.57%  |
| 4.01-8.0   | 43        | 16.35%  |
| 3.01-4.0   | 33        | 12.55%  |
| 0.51-1.0   | 15        | 5.7%    |
| 8.01-16.0  | 12        | 4.56%   |
| 16.01-24.0 | 2         | 0.76%   |
| 0.01-0.5   | 2         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 175       | 74.79%  |
| 2      | 49        | 20.94%  |
| 3      | 4         | 1.71%   |
| 0      | 3         | 1.28%   |
| 6      | 1         | 0.43%   |
| 5      | 1         | 0.43%   |
| 4      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 67.25%  |
| Yes       | 75        | 32.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 85.96%  |
| No        | 32        | 14.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 99.12%  |
| No        | 2         | 0.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 81.9%   |
| No        | 42        | 18.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 227       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 148       | 56.06%  |
| Split               | 12        | 4.55%   |
| Rijeka              | 11        | 4.17%   |
| Varaždin           | 6         | 2.27%   |
| Pula                | 5         | 1.89%   |
| Velika Gorica       | 4         | 1.52%   |
| Zaprešić          | 3         | 1.14%   |
| Jesenice            | 3         | 1.14%   |
| Čakovec            | 3         | 1.14%   |
| Rovinj              | 2         | 0.76%   |
| Petrinja            | 2         | 0.76%   |
| Osijek              | 2         | 0.76%   |
| Omiš               | 2         | 0.76%   |
| Novska              | 2         | 0.76%   |
| Krizevci            | 2         | 0.76%   |
| Komiža             | 2         | 0.76%   |
| Kastav              | 2         | 0.76%   |
| Bjelovar            | 2         | 0.76%   |
| Đakovo             | 1         | 0.38%   |
| Zminj               | 1         | 0.38%   |
| Zadar               | 1         | 0.38%   |
| Zabok               | 1         | 0.38%   |
| Virovitica          | 1         | 0.38%   |
| Vinkovci            | 1         | 0.38%   |
| Varazdinske Toplice | 1         | 0.38%   |
| Umag                | 1         | 0.38%   |
| Udbinja             | 1         | 0.38%   |
| Trenkovo            | 1         | 0.38%   |
| Sveti Ivan Zelina   | 1         | 0.38%   |
| Sveta Marija        | 1         | 0.38%   |
| Supetar             | 1         | 0.38%   |
| Sracinec            | 1         | 0.38%   |
| Šibenik            | 1         | 0.38%   |
| Sesvete             | 1         | 0.38%   |
| Senj                | 1         | 0.38%   |
| Samobor             | 1         | 0.38%   |
| Rokovci             | 1         | 0.38%   |
| Požega             | 1         | 0.38%   |
| Pitomaca            | 1         | 0.38%   |
| Otocac              | 1         | 0.38%   |
| Opuzen              | 1         | 0.38%   |
| Ogulin              | 1         | 0.38%   |
| Novo Cice           | 1         | 0.38%   |
| Našice             | 1         | 0.38%   |
| Medulin             | 1         | 0.38%   |
| Matulji             | 1         | 0.38%   |
| Mala Subotica       | 1         | 0.38%   |
| Labin               | 1         | 0.38%   |
| Krk                 | 1         | 0.38%   |
| Koprivnica          | 1         | 0.38%   |
| Klis                | 1         | 0.38%   |
| Kastel Stafilic     | 1         | 0.38%   |
| Karlovac            | 1         | 0.38%   |
| Jelsa               | 1         | 0.38%   |
| Hvar                | 1         | 0.38%   |
| Dugopolje           | 1         | 0.38%   |
| Donji Desinec       | 1         | 0.38%   |
| Dinjevac            | 1         | 0.38%   |
| Cret Bizovacki      | 1         | 0.38%   |
| Cres                | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 45        | 59     | 16.3%   |
| WDC                   | 37        | 46     | 13.41%  |
| Kingston              | 26        | 34     | 9.42%   |
| Seagate               | 24        | 46     | 8.7%    |
| SK hynix              | 20        | 31     | 7.25%   |
| Toshiba               | 19        | 20     | 6.88%   |
| SanDisk               | 17        | 22     | 6.16%   |
| Micron Technology     | 12        | 13     | 4.35%   |
| Intel                 | 8         | 14     | 2.9%    |
| Hitachi               | 8         | 8      | 2.9%    |
| HGST                  | 8         | 8      | 2.9%    |
| Crucial               | 7         | 12     | 2.54%   |
| Unknown               | 6         | 6      | 2.17%   |
| A-DATA Technology     | 5         | 5      | 1.81%   |
| Fujitsu               | 4         | 4      | 1.45%   |
| Apple                 | 4         | 4      | 1.45%   |
| Transcend             | 2         | 3      | 0.72%   |
| Silicon Motion        | 2         | 3      | 0.72%   |
| LITEON                | 2         | 3      | 0.72%   |
| Lenovo                | 2         | 3      | 0.72%   |
| KingFast              | 2         | 4      | 0.72%   |
| Intenso               | 2         | 3      | 0.72%   |
| Verbatim              | 1         | 1      | 0.36%   |
| UMIS                  | 1         | 1      | 0.36%   |
| StoreJet              | 1         | 1      | 0.36%   |
| Realtek Semiconductor | 1         | 3      | 0.36%   |
| Phison                | 1         | 1      | 0.36%   |
| Patriot               | 1         | 1      | 0.36%   |
| Netac                 | 1         | 1      | 0.36%   |
| Mass                  | 1         | 1      | 0.36%   |
| Lite-On               | 1         | 1      | 0.36%   |
| LaCie                 | 1         | 1      | 0.36%   |
| KIOXIA                | 1         | 1      | 0.36%   |
| Gigabyte Technology   | 1         | 1      | 0.36%   |
| Corsair               | 1         | 1      | 0.36%   |
| AMD                   | 1         | 3      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 7         | 2.5%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 2.14%   |
| SanDisk NVMe SSD Drive 512GB            | 5         | 1.79%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.43%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.43%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 1.07%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.07%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.07%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 1.07%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 1.07%   |
| Intel NVMe SSD Drive 256GB              | 3         | 1.07%   |
| HGST HTS721010A9E630 1TB                | 3         | 1.07%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.71%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.71%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.71%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 2         | 0.71%   |
| Unknown SD/MMC/MS PRO 64GB              | 2         | 0.71%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.71%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB           | 2         | 0.71%   |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.71%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.71%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.71%   |
| Seagate ST9500325AS 500GB               | 2         | 0.71%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.71%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 2         | 0.71%   |
| Samsung PM9A1 NVMe 2048GB               | 2         | 0.71%   |
| Samsung PM981 NVMe 512GB                | 2         | 0.71%   |
| Samsung NVMe SSD Drive 256GB            | 2         | 0.71%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD    | 2         | 0.71%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 0.71%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.71%   |
| Micron 1100 SATA 256GB SSD              | 2         | 0.71%   |
| Kingston SV300S37A240G 240GB SSD        | 2         | 0.71%   |
| KingFast 256GB                          | 2         | 0.71%   |
| Intel SSDPEKNW512G8H 512GB              | 2         | 0.71%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 0.71%   |
| HGST HTS541010A9E680 1TB                | 2         | 0.71%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.71%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.71%   |
| A-DATA SU650 240GB SSD                  | 2         | 0.71%   |
| A-DATA SU650 120GB SSD                  | 2         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.36%   |
| WDC WDS250G2B0B-00YS70 250GB SSD        | 1         | 0.36%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.36%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.36%   |
| WDC WD800BEVS-08RST2 80GB               | 1         | 0.36%   |
| WDC WD7500BPVT-80HXZT1 752GB            | 1         | 0.36%   |
| WDC WD7500BPVT-08A1YT1 752GB            | 1         | 0.36%   |
| WDC WD600VE-75HDT0 64GB                 | 1         | 0.36%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.36%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.36%   |
| WDC WD2500BEKT-60PVMT0 250GB            | 1         | 0.36%   |
| WDC WD10SPZX-75Z10T2 1TB                | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 31     | 29.89%  |
| Seagate             | 24        | 35     | 27.59%  |
| Toshiba             | 13        | 14     | 14.94%  |
| Hitachi             | 8         | 8      | 9.2%    |
| HGST                | 8         | 8      | 9.2%    |
| Fujitsu             | 4         | 4      | 4.6%    |
| Unknown             | 2         | 2      | 2.3%    |
| Samsung Electronics | 1         | 2      | 1.15%   |
| Intenso             | 1         | 2      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 27     | 24.21%  |
| Samsung Electronics | 16        | 24     | 16.84%  |
| Micron Technology   | 10        | 11     | 10.53%  |
| SanDisk             | 9         | 13     | 9.47%   |
| Crucial             | 7         | 12     | 7.37%   |
| SK hynix            | 6         | 11     | 6.32%   |
| WDC                 | 5         | 6      | 5.26%   |
| A-DATA Technology   | 5         | 5      | 5.26%   |
| Apple               | 4         | 4      | 4.21%   |
| Transcend           | 1         | 2      | 1.05%   |
| Toshiba             | 1         | 1      | 1.05%   |
| StoreJet            | 1         | 1      | 1.05%   |
| Patriot             | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| LITEON              | 1         | 2      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| Intel               | 1         | 2      | 1.05%   |
| Gigabyte Technology | 1         | 1      | 1.05%   |
| AMD                 | 1         | 3      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 87        | 128    | 33.08%  |
| HDD     | 85        | 106    | 32.32%  |
| NVMe    | 82        | 114    | 31.18%  |
| Unknown | 6         | 18     | 2.28%   |
| MMC     | 3         | 3      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 153       | 227    | 61.94%  |
| NVMe | 82        | 114    | 33.2%   |
| SAS  | 9         | 25     | 3.64%   |
| MMC  | 3         | 3      | 1.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 156    | 67.82%  |
| 0.51-1.0   | 50        | 71     | 28.74%  |
| 1.01-2.0   | 6         | 7      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 33.05%  |
| 251-500        | 57        | 23.85%  |
| 501-1000       | 36        | 15.06%  |
| 1001-2000      | 23        | 9.62%   |
| 51-100         | 15        | 6.28%   |
| 1-20           | 11        | 4.6%    |
| 21-50          | 7         | 2.93%   |
| Unknown        | 7         | 2.93%   |
| More than 3000 | 2         | 0.84%   |
| 2001-3000      | 2         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 33.2%   |
| 21-50          | 61        | 23.55%  |
| 51-100         | 33        | 12.74%  |
| 101-250        | 29        | 11.2%   |
| 501-1000       | 20        | 7.72%   |
| 251-500        | 18        | 6.95%   |
| Unknown        | 7         | 2.7%    |
| 1001-2000      | 4         | 1.54%   |
| More than 3000 | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 6.67%   |
| WDC WD600VE-75HDT0 64GB             | 1         | 1      | 6.67%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 6.67%   |
| Toshiba MK6459GSXP 640GB            | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 6.67%   |
| Seagate ST9250827AS 250GB           | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 6.67%   |
| SanDisk SDSSDXPS960G 960GB          | 1         | 1      | 6.67%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 6.67%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 6.67%   |
| Crucial CT1024M550SSD1 1024GB       | 1         | 1      | 6.67%   |
| A-DATA Technology SU630 240GB SSD   | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 21.43%  |
| Seagate           | 3         | 3      | 21.43%  |
| HGST              | 3         | 3      | 21.43%  |
| Toshiba           | 1         | 1      | 7.14%   |
| SanDisk           | 1         | 2      | 7.14%   |
| Hitachi           | 1         | 1      | 7.14%   |
| Crucial           | 1         | 1      | 7.14%   |
| A-DATA Technology | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| HGST    | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 76.92%  |
| SSD  | 3         | 5      | 23.08%  |

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
| Detected | 141       | 223    | 58.75%  |
| Works    | 86        | 131    | 35.83%  |
| Malfunc  | 13        | 15     | 5.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 165       | 58.3%   |
| Samsung Electronics              | 30        | 10.6%   |
| AMD                              | 30        | 10.6%   |
| SK hynix                         | 14        | 4.95%   |
| SanDisk                          | 14        | 4.95%   |
| Toshiba America Info Systems     | 6         | 2.12%   |
| Kingston Technology Company      | 3         | 1.06%   |
| Silicon Motion                   | 2         | 0.71%   |
| Silicon Integrated Systems [SiS] | 2         | 0.71%   |
| Phison Electronics               | 2         | 0.71%   |
| Nvidia                           | 2         | 0.71%   |
| Micron Technology                | 2         | 0.71%   |
| Lite-On Technology               | 2         | 0.71%   |
| Lenovo                           | 2         | 0.71%   |
| KIOXIA                           | 2         | 0.71%   |
| VIA Technologies                 | 1         | 0.35%   |
| Union Memory (Shenzhen)          | 1         | 0.35%   |
| Realtek Semiconductor            | 1         | 0.35%   |
| Marvell Technology Group         | 1         | 0.35%   |
| JMicron Technology               | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 9.27%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 9.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 4.97%   |
| Samsung NVMe SSD Controller 980                                                  | 13        | 4.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 4.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 4.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 3.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.32%   |
| SK hynix Gold P31 SSD                                                            | 6         | 1.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.99%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.66%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.32%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.99%   |
| SK hynix BC511                                                                   | 3         | 0.99%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.99%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.66%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.66%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.66%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.66%   |
| Samsung Electronics SATA controller                                              | 2         | 0.66%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.66%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.66%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.66%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.66%   |
| Intel SSD 660P Series                                                            | 2         | 0.66%   |
| Intel SSD 600P Series                                                            | 2         | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.66%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.66%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.66%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.66%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.33%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.33%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.33%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.33%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.33%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 173       | 59.86%  |
| NVMe | 83        | 28.72%  |
| IDE  | 21        | 7.27%   |
| RAID | 12        | 4.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 81.5%   |
| AMD    | 42        | 18.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 4.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 3.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 2.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.76%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.76%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 1.32%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.32%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.32%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.32%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.32%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.32%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.88%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.88%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.88%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.88%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.88%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.88%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.88%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.88%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.88%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.88%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.88%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 2         | 0.88%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 2         | 0.88%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.88%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.88%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.88%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.44%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.44%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.44%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 1         | 0.44%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.44%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.44%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.44%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 69        | 30.4%   |
| Intel Core i7           | 39        | 17.18%  |
| Intel Core i3           | 17        | 7.49%   |
| Intel Pentium           | 15        | 6.61%   |
| AMD Ryzen 5             | 14        | 6.17%   |
| Intel Core 2 Duo        | 12        | 5.29%   |
| Other                   | 10        | 4.41%   |
| AMD Ryzen 7             | 9         | 3.96%   |
| Intel Celeron           | 6         | 2.64%   |
| Intel Pentium Dual      | 4         | 1.76%   |
| AMD Ryzen 3             | 4         | 1.76%   |
| AMD A6                  | 4         | 1.76%   |
| Intel Pentium Silver    | 3         | 1.32%   |
| Intel Pentium Dual-Core | 3         | 1.32%   |
| Intel Core i9           | 3         | 1.32%   |
| Intel Atom              | 3         | 1.32%   |
| Intel Pentium M         | 2         | 0.88%   |
| AMD Ryzen 9             | 2         | 0.88%   |
| AMD E1                  | 2         | 0.88%   |
| AMD E                   | 2         | 0.88%   |
| Intel Celeron M         | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Athlon              | 1         | 0.44%   |
| AMD A4                  | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 115       | 50.66%  |
| 4       | 77        | 33.92%  |
| 6       | 17        | 7.49%   |
| 8       | 13        | 5.73%   |
| 1       | 4         | 1.76%   |
| Unknown | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 226       | 99.56%  |
| Unknown | 1         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 160       | 70.48%  |
| 1       | 66        | 29.07%  |
| Unknown | 1         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 216       | 94.32%  |
| Unknown        | 9         | 3.93%   |
| 32-bit         | 4         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 19.67%  |
| 0x806ea    | 14        | 5.86%   |
| 0x806e9    | 13        | 5.44%   |
| 0x306c3    | 13        | 5.44%   |
| 0x306a9    | 12        | 5.02%   |
| 0x906ea    | 10        | 4.18%   |
| 0x806ec    | 10        | 4.18%   |
| 0x40651    | 10        | 4.18%   |
| 0x6fd      | 8         | 3.35%   |
| 0x806c1    | 6         | 2.51%   |
| 0x206a7    | 6         | 2.51%   |
| 0x0a50000c | 6         | 2.51%   |
| 0x306d4    | 5         | 2.09%   |
| 0x1067a    | 5         | 2.09%   |
| 0x06006705 | 5         | 2.09%   |
| 0x406e3    | 4         | 1.67%   |
| 0x30678    | 4         | 1.67%   |
| 0x08600106 | 4         | 1.67%   |
| 0x08108109 | 4         | 1.67%   |
| 0x0810100b | 4         | 1.67%   |
| 0xa0652    | 3         | 1.26%   |
| 0x706e5    | 3         | 1.26%   |
| 0x506c9    | 3         | 1.26%   |
| 0x20655    | 3         | 1.26%   |
| 0x08608103 | 3         | 1.26%   |
| 0x08600103 | 3         | 1.26%   |
| 0x05000119 | 3         | 1.26%   |
| 0x906ed    | 2         | 0.84%   |
| 0x906e9    | 2         | 0.84%   |
| 0x806eb    | 2         | 0.84%   |
| 0x706a1    | 2         | 0.84%   |
| 0x6fb      | 2         | 0.84%   |
| 0x6d8      | 2         | 0.84%   |
| 0x406c4    | 2         | 0.84%   |
| 0x10676    | 2         | 0.84%   |
| 0x906c0    | 1         | 0.42%   |
| 0x6fa      | 1         | 0.42%   |
| 0x6e8      | 1         | 0.42%   |
| 0x506e3    | 1         | 0.42%   |
| 0x40661    | 1         | 0.42%   |
| 0x106ca    | 1         | 0.42%   |
| 0x106c2    | 1         | 0.42%   |
| 0x08608102 | 1         | 0.42%   |
| 0x08600104 | 1         | 0.42%   |
| 0x08108102 | 1         | 0.42%   |
| 0x07030105 | 1         | 0.42%   |
| 0x06006704 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 63        | 27.75%  |
| Haswell       | 27        | 11.89%  |
| IvyBridge     | 16        | 7.05%   |
| Core          | 11        | 4.85%   |
| Zen 2         | 9         | 3.96%   |
| Silvermont    | 9         | 3.96%   |
| TigerLake     | 8         | 3.52%   |
| Penryn        | 8         | 3.52%   |
| Zen 3         | 7         | 3.08%   |
| Skylake       | 7         | 3.08%   |
| SandyBridge   | 7         | 3.08%   |
| Zen+          | 6         | 2.64%   |
| Excavator     | 6         | 2.64%   |
| Broadwell     | 6         | 2.64%   |
| Unknown       | 5         | 2.2%    |
| Zen           | 4         | 1.76%   |
| Westmere      | 4         | 1.76%   |
| IceLake       | 4         | 1.76%   |
| P6            | 3         | 1.32%   |
| Goldmont plus | 3         | 1.32%   |
| Goldmont      | 3         | 1.32%   |
| CometLake     | 3         | 1.32%   |
| Bobcat        | 3         | 1.32%   |
| Tremont       | 1         | 0.44%   |
| Puma          | 1         | 0.44%   |
| K8 Hammer     | 1         | 0.44%   |
| Jaguar        | 1         | 0.44%   |
| Bonnell       | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 166       | 54.25%  |
| Nvidia                           | 77        | 25.16%  |
| AMD                              | 60        | 19.61%  |
| Silicon Integrated Systems [SiS] | 2         | 0.65%   |
| VIA Technologies                 | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 18        | 5.75%   |
| Intel HD Graphics 620                                                                    | 14        | 4.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 2.56%   |
| AMD Renoir                                                                               | 8         | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.6%    |
| Intel HD Graphics 5500                                                                   | 5         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.6%    |
| AMD Cezanne                                                                              | 5         | 1.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.28%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.28%   |
| AMD Lucienne                                                                             | 4         | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.96%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.96%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.96%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.96%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.96%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.64%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.64%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.64%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.64%   |
| Intel HD Graphics 630                                                                    | 2         | 0.64%   |
| Intel HD Graphics 530                                                                    | 2         | 0.64%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.64%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.32%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.32%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.32%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.32%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.32%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.32%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.32%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 41.41%  |
| Intel + Nvidia | 56        | 24.67%  |
| 1 x AMD        | 33        | 14.54%  |
| Intel + AMD    | 16        | 7.05%   |
| 1 x Nvidia     | 14        | 6.17%   |
| AMD + Nvidia   | 7         | 3.08%   |
| 2 x AMD        | 4         | 1.76%   |
| 1 x SiS        | 2         | 0.88%   |
| 1 x VIA        | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 182       | 79.82%  |
| Proprietary | 38        | 16.67%  |
| Unknown     | 8         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 55.08%  |
| 1.01-2.0   | 34        | 14.41%  |
| 0.01-0.5   | 28        | 11.86%  |
| 3.01-4.0   | 27        | 11.44%  |
| 0.51-1.0   | 11        | 4.66%   |
| 7.01-8.0   | 3         | 1.27%   |
| 5.01-6.0   | 2         | 0.85%   |
| 2.01-3.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 16.6%   |
| LG Display              | 41        | 15.47%  |
| BOE                     | 38        | 14.34%  |
| Chimei Innolux          | 36        | 13.58%  |
| Samsung Electronics     | 28        | 10.57%  |
| Dell                    | 22        | 8.3%    |
| Sharp                   | 8         | 3.02%   |
| Goldstar                | 5         | 1.89%   |
| Lenovo                  | 4         | 1.51%   |
| Chi Mei Optoelectronics | 4         | 1.51%   |
| Apple                   | 4         | 1.51%   |
| PANDA                   | 3         | 1.13%   |
| LG Philips              | 3         | 1.13%   |
| CSO                     | 3         | 1.13%   |
| AOC                     | 3         | 1.13%   |
| Quanta Display          | 2         | 0.75%   |
| Hewlett-Packard         | 2         | 0.75%   |
| BenQ                    | 2         | 0.75%   |
| Philips                 | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| NCS                     | 1         | 0.38%   |
| MSI                     | 1         | 0.38%   |
| InnoLux Display         | 1         | 0.38%   |
| InfoVision              | 1         | 0.38%   |
| Iiyama                  | 1         | 0.38%   |
| IBM                     | 1         | 0.38%   |
| Grundig                 | 1         | 0.38%   |
| Fujitsu Siemens         | 1         | 0.38%   |
| BOE Technology Group    | 1         | 0.38%   |
| Achieva Shimian         | 1         | 0.38%   |
| Acer                    | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.83%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.47%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 1.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.47%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 1.1%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 1.1%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.73%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch      | 2         | 0.73%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.73%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.73%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.73%   |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                     | 2         | 0.73%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.73%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.73%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 2         | 0.73%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                     | 2         | 0.73%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                         | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch           | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.73%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 2         | 0.73%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.37%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 0.37%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.37%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch         | 1         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.37%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 600x340mm 27.2-inch         | 1         | 0.37%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch         | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0626 1920x1080                          | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                          | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM021D 1680x1050 433x271mm 20.1-inch      | 1         | 0.37%   |
| Samsung Electronics S23B300 SAM08CA 1920x1080 510x287mm 23.0-inch         | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 123       | 49.8%   |
| 1366x768 (WXGA)    | 46        | 18.62%  |
| 1600x900 (HD+)     | 22        | 8.91%   |
| 3840x2160 (4K)     | 12        | 4.86%   |
| 2560x1440 (QHD)    | 9         | 3.64%   |
| 1440x900 (WXGA+)   | 7         | 2.83%   |
| 1280x800 (WXGA)    | 6         | 2.43%   |
| 1920x1200 (WUXGA)  | 4         | 1.62%   |
| 1680x1050 (WSXGA+) | 4         | 1.62%   |
| 2160x1440          | 3         | 1.21%   |
| 3840x2400          | 2         | 0.81%   |
| 2560x1600          | 2         | 0.81%   |
| 1400x1050          | 2         | 0.81%   |
| 2880x1800          | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |
| 1280x1024 (SXGA)   | 1         | 0.4%    |
| 1024x600           | 1         | 0.4%    |
| 1024x576           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 125       | 46.64%  |
| 17      | 36        | 13.43%  |
| 13      | 23        | 8.58%   |
| 14      | 20        | 7.46%   |
| 27      | 16        | 5.97%   |
| 24      | 12        | 4.48%   |
| 23      | 7         | 2.61%   |
| 12      | 5         | 1.87%   |
| 31      | 4         | 1.49%   |
| 21      | 4         | 1.49%   |
| 54      | 3         | 1.12%   |
| 16      | 3         | 1.12%   |
| Unknown | 3         | 1.12%   |
| 20      | 2         | 0.75%   |
| 10      | 2         | 0.75%   |
| 25      | 1         | 0.37%   |
| 18      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 151       | 57.41%  |
| 351-400     | 39        | 14.83%  |
| 501-600     | 27        | 10.27%  |
| 201-300     | 24        | 9.13%   |
| 601-700     | 8         | 3.04%   |
| 401-500     | 8         | 3.04%   |
| 1001-1500   | 3         | 1.14%   |
| Unknown     | 3         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 190       | 84.44%  |
| 16/10   | 26        | 11.56%  |
| 3/2     | 4         | 1.78%   |
| 4/3     | 3         | 1.33%   |
| 5/4     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 47.01%  |
| 81-90          | 31        | 11.57%  |
| 121-130        | 31        | 11.57%  |
| 201-250        | 18        | 6.72%   |
| 301-350        | 16        | 5.97%   |
| 71-80          | 11        | 4.1%    |
| 61-70          | 4         | 1.49%   |
| 351-500        | 4         | 1.49%   |
| 251-300        | 4         | 1.49%   |
| 151-200        | 4         | 1.49%   |
| 131-140        | 4         | 1.49%   |
| More than 1000 | 3         | 1.12%   |
| Unknown        | 3         | 1.12%   |
| 41-50          | 2         | 0.75%   |
| 141-150        | 2         | 0.75%   |
| 111-120        | 2         | 0.75%   |
| 91-100         | 2         | 0.75%   |
| 51-60          | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 123       | 47.31%  |
| 101-120       | 72        | 27.69%  |
| 51-100        | 42        | 16.15%  |
| 161-240       | 13        | 5%      |
| More than 240 | 4         | 1.54%   |
| 1-50          | 3         | 1.15%   |
| Unknown       | 3         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 179       | 75.21%  |
| 2     | 44        | 18.49%  |
| 0     | 9         | 3.78%   |
| 3     | 5         | 2.1%    |
| 4     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 134       | 35.64%  |
| Intel                             | 115       | 30.59%  |
| Qualcomm Atheros                  | 64        | 17.02%  |
| Broadcom                          | 20        | 5.32%   |
| MediaTek                          | 7         | 1.86%   |
| Broadcom Limited                  | 5         | 1.33%   |
| Samsung Electronics               | 4         | 1.06%   |
| Marvell Technology Group          | 3         | 0.8%    |
| Xiaomi                            | 2         | 0.53%   |
| TP-Link                           | 2         | 0.53%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.53%   |
| Ralink                            | 2         | 0.53%   |
| Qualcomm Atheros Communications   | 2         | 0.53%   |
| Qualcomm                          | 2         | 0.53%   |
| Lenovo                            | 2         | 0.53%   |
| D-Link                            | 2         | 0.53%   |
| VIA Technologies                  | 1         | 0.27%   |
| Nvidia                            | 1         | 0.27%   |
| HTC (High Tech Computer)          | 1         | 0.27%   |
| Hewlett-Packard                   | 1         | 0.27%   |
| Fibocom                           | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 104       | 23.64%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 17        | 3.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 3.41%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.95%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.36%   |
| Intel Wireless 7260                                                     | 6         | 1.36%   |
| Intel Wireless 3165                                                     | 6         | 1.36%   |
| Intel Wireless 3160                                                     | 6         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 1.14%   |
| Intel Wireless 7265                                                     | 5         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.91%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.91%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.68%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.68%   |
| Intel WiFi Link 5100                                                    | 3         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.68%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.45%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.45%   |
| Lenovo USB-C Dock Ethernet                                              | 2         | 0.45%   |
| Intel Wireless 8260                                                     | 2         | 0.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.45%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.45%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.45%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.45%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 2         | 0.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.23%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 49.57%  |
| Qualcomm Atheros                | 55        | 23.91%  |
| Realtek Semiconductor           | 26        | 11.3%   |
| Broadcom                        | 14        | 6.09%   |
| MediaTek                        | 7         | 3.04%   |
| Broadcom Limited                | 3         | 1.3%    |
| TP-Link                         | 2         | 0.87%   |
| Ralink                          | 2         | 0.87%   |
| Qualcomm Atheros Communications | 2         | 0.87%   |
| Qualcomm                        | 2         | 0.87%   |
| D-Link                          | 2         | 0.87%   |
| Fibocom                         | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 8.7%    |
| Intel Wireless 8265 / 8275                                              | 17        | 7.39%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 6.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 3.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.61%   |
| Intel Wireless 7260                                                     | 6         | 2.61%   |
| Intel Wireless 3165                                                     | 6         | 2.61%   |
| Intel Wireless 3160                                                     | 6         | 2.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.61%   |
| Intel Wireless 7265                                                     | 5         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.74%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.3%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.3%    |
| Intel WiFi Link 5100                                                    | 3         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.3%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.87%   |
| Intel Wireless 8260                                                     | 2         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.87%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.43%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.43%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.43%   |
| Realtek Realtek Network controller                                      | 1         | 0.43%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.43%   |
| Qualcomm Atheros AR5523                                                 | 1         | 0.43%   |
| MediaTek WiFi                                                           | 1         | 0.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.43%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 0.43%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.43%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.43%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.43%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.43%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 127       | 61.35%  |
| Intel                            | 36        | 17.39%  |
| Qualcomm Atheros                 | 18        | 8.7%    |
| Broadcom                         | 6         | 2.9%    |
| Samsung Electronics              | 4         | 1.93%   |
| Marvell Technology Group         | 3         | 1.45%   |
| Xiaomi                           | 2         | 0.97%   |
| Silicon Integrated Systems [SiS] | 2         | 0.97%   |
| Lenovo                           | 2         | 0.97%   |
| Broadcom Limited                 | 2         | 0.97%   |
| VIA Technologies                 | 1         | 0.48%   |
| Nvidia                           | 1         | 0.48%   |
| HTC (High Tech Computer)         | 1         | 0.48%   |
| DisplayLink                      | 1         | 0.48%   |
| ASIX Electronics                 | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104       | 50.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.25%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.97%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.97%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.48%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.48%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.48%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.48%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.48%   |
| HTC (High Tech Computer) MEDIACOM PhonePad G501                   | 1         | 0.48%   |
| DisplayLink Dell D3100 Docking Station                            | 1         | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.48%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.48%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.48%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 53.07%  |
| Ethernet | 196       | 46.23%  |
| Modem    | 3         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 78.46%  |
| Ethernet | 53        | 21.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 183       | 80.62%  |
| 1     | 43        | 18.94%  |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 219       | 96.05%  |
| Yes  | 9         | 3.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 47.12%  |
| Qualcomm Atheros Communications | 19        | 9.95%   |
| Lite-On Technology              | 19        | 9.95%   |
| Realtek Semiconductor           | 15        | 7.85%   |
| IMC Networks                    | 14        | 7.33%   |
| Foxconn / Hon Hai               | 7         | 3.66%   |
| Broadcom                        | 7         | 3.66%   |
| Hewlett-Packard                 | 5         | 2.62%   |
| Apple                           | 4         | 2.09%   |
| Toshiba                         | 3         | 1.57%   |
| Foxconn International           | 3         | 1.57%   |
| Cambridge Silicon Radio         | 3         | 1.57%   |
| Realtek                         | 1         | 0.52%   |
| Dell                            | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 21.99%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 7.33%   |
| Intel AX200 Bluetooth                               | 14        | 7.33%   |
| Realtek Bluetooth Radio                             | 12        | 6.28%   |
| Intel AX201 Bluetooth                               | 11        | 5.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 4.19%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 3.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.62%   |
| Intel Bluetooth Device                              | 4         | 2.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.57%   |
| IMC Networks Wireless_Device                        | 3         | 1.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.05%   |
| Lite-On Bluetooth Device                            | 2         | 1.05%   |
| IMC Networks Bluetooth Device                       | 2         | 1.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.05%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.05%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.05%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.52%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.52%   |
| Toshiba Bluetooth Device                            | 1         | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.52%   |
| Realtek Bluetooth Radio                             | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.52%   |
| Lite-On Wireless_Device                             | 1         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.52%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.52%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.52%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter          | 1         | 0.52%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.52%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.52%   |
| Apple Bluetooth Host Controller                     | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 180       | 64.29%  |
| AMD                              | 46        | 16.43%  |
| Nvidia                           | 29        | 10.36%  |
| C-Media Electronics              | 4         | 1.43%   |
| Logitech                         | 3         | 1.07%   |
| Lenovo                           | 3         | 1.07%   |
| JMTek                            | 3         | 1.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.71%   |
| ZOOM                             | 1         | 0.36%   |
| YZ Technology                    | 1         | 0.36%   |
| VIA Technologies                 | 1         | 0.36%   |
| Trust                            | 1         | 0.36%   |
| Texas Instruments                | 1         | 0.36%   |
| SteelSeries ApS                  | 1         | 0.36%   |
| Realtek Semiconductor            | 1         | 0.36%   |
| Plantronics                      | 1         | 0.36%   |
| Pioneer DJ                       | 1         | 0.36%   |
| GN Netcom                        | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 11.05%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 8.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 4.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.78%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 2.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 1.74%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.16%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.87%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.87%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.58%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia Audio device                                                                               | 2         | 0.58%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.58%   |
| C-Media Electronics Audio Adapter                                                                 | 2         | 0.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.58%   |
| ZOOM U-22                                                                                         | 1         | 0.29%   |
| YZ Technology 2.4G Wireless headset                                                               | 1         | 0.29%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.29%   |
| Trust GXT 232 Microphone                                                                          | 1         | 0.29%   |
| Texas Instruments PCM2900B Audio CODEC                                                            | 1         | 0.29%   |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 1         | 0.29%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.29%   |
| Plantronics BT600                                                                                 | 1         | 0.29%   |
| Pioneer DJ DDJ-SB2                                                                                | 1         | 0.29%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.29%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.29%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.29%   |
| Logitech 960 Headset                                                                              | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 31.03%  |
| SK hynix            | 31        | 21.38%  |
| Kingston            | 23        | 15.86%  |
| Micron Technology   | 20        | 13.79%  |
| Crucial             | 7         | 4.83%   |
| Unknown             | 5         | 3.45%   |
| Ramaxel Technology  | 3         | 2.07%   |
| Patriot             | 2         | 1.38%   |
| Elpida              | 2         | 1.38%   |
| A-DATA Technology   | 2         | 1.38%   |
| Transcend           | 1         | 0.69%   |
| Qimonda             | 1         | 0.69%   |
| G.Skill             | 1         | 0.69%   |
| Corsair             | 1         | 0.69%   |
| 48spaces            | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 6         | 3.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 3.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.89%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 3         | 1.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.89%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 3         | 1.89%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 1.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.26%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 1.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.26%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 2         | 1.26%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.26%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.26%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 2         | 1.26%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s               | 2         | 1.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.26%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 1.26%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s             | 2         | 1.26%   |
| Kingston RAM 9905700-047.A00G 16GB SODIMM DDR4 2667MT/s             | 2         | 1.26%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.63%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.63%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s                  | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.63%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.63%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                          | 1         | 0.63%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 1         | 0.63%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                    | 1         | 0.63%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s               | 1         | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM 1600MT/s                   | 1         | 0.63%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s           | 1         | 0.63%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s           | 1         | 0.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.63%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 1         | 0.63%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.63%   |
| SK hynix RAM GKE160SO102408-3000 16384MB SODIMM DDR4 3000MT/s       | 1         | 0.63%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.63%   |
| Samsung RAM Module 1024MB SODIMM DDR2 533MT/s                       | 1         | 0.63%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 61        | 50.83%  |
| DDR3   | 39        | 32.5%   |
| LPDDR3 | 7         | 5.83%   |
| DDR2   | 7         | 5.83%   |
| LPDDR4 | 5         | 4.17%   |
| SDRAM  | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 86.67%  |
| Row Of Chips | 14        | 11.67%  |
| DIMM         | 1         | 0.83%   |
| Chip         | 1         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 39.69%  |
| 4096  | 42        | 32.06%  |
| 16384 | 19        | 14.5%   |
| 2048  | 10        | 7.63%   |
| 1024  | 5         | 3.82%   |
| 32768 | 3         | 2.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 33        | 25.58%  |
| 1600  | 32        | 24.81%  |
| 3200  | 23        | 17.83%  |
| 2133  | 9         | 6.98%   |
| 2400  | 7         | 5.43%   |
| 667   | 6         | 4.65%   |
| 1334  | 5         | 3.88%   |
| 4267  | 2         | 1.55%   |
| 1333  | 2         | 1.55%   |
| 8400  | 1         | 0.78%   |
| 4266  | 1         | 0.78%   |
| 3266  | 1         | 0.78%   |
| 3000  | 1         | 0.78%   |
| 2048  | 1         | 0.78%   |
| 1867  | 1         | 0.78%   |
| 1067  | 1         | 0.78%   |
| 1066  | 1         | 0.78%   |
| 975   | 1         | 0.78%   |
| 533   | 1         | 0.78%   |

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
| Chicony Electronics                    | 61        | 28.77%  |
| IMC Networks                           | 26        | 12.26%  |
| Quanta                                 | 20        | 9.43%   |
| Realtek Semiconductor                  | 19        | 8.96%   |
| Microdia                               | 14        | 6.6%    |
| Acer                                   | 14        | 6.6%    |
| Suyin                                  | 10        | 4.72%   |
| Lite-On Technology                     | 8         | 3.77%   |
| Syntek                                 | 7         | 3.3%    |
| Sunplus Innovation Technology          | 7         | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.83%   |
| Luxvisions Innotech Limited            | 3         | 1.42%   |
| Apple                                  | 3         | 1.42%   |
| Silicon Motion                         | 2         | 0.94%   |
| Primax Electronics                     | 2         | 0.94%   |
| Logitech                               | 2         | 0.94%   |
| Anker                                  | 2         | 0.94%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| Jieli Technology                       | 1         | 0.47%   |
| Goertek Electronics                    | 1         | 0.47%   |
| Genesys Logic                          | 1         | 0.47%   |
| Cubeternet                             | 1         | 0.47%   |
| AVerMedia Technologies                 | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 5.66%   |
| Chicony HD WebCam                                   | 12        | 5.66%   |
| IMC Networks Integrated Camera                      | 10        | 4.72%   |
| Quanta VGA WebCam                                   | 8         | 3.77%   |
| Microdia Integrated_Webcam_HD                       | 8         | 3.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 3.3%    |
| Lite-On HP HD Camera                                | 5         | 2.36%   |
| Acer Lenovo EasyCamera                              | 5         | 2.36%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.89%   |
| Quanta HD Webcam                                    | 4         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.89%   |
| Syntek Integrated Camera                            | 3         | 1.42%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.42%   |
| Realtek Lenovo EasyCamera                           | 3         | 1.42%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.42%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.42%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.42%   |
| Chicony Integrated HP HD Webcam                     | 3         | 1.42%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.42%   |
| Chicony HP Webcam                                   | 3         | 1.42%   |
| Suyin WebCam                                        | 2         | 0.94%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.94%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 0.94%   |
| Sunplus HD WebCam                                   | 2         | 0.94%   |
| Realtek Integrated Webcam                           | 2         | 0.94%   |
| Realtek EasyCamera                                  | 2         | 0.94%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 0.94%   |
| Quanta HP HD Camera                                 | 2         | 0.94%   |
| Quanta HD User Facing                               | 2         | 0.94%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.94%   |
| Lite-On Integrated Camera                           | 2         | 0.94%   |
| Chicony USB 2.0 Camera                              | 2         | 0.94%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.94%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.94%   |
| Chicony EasyCamera                                  | 2         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.94%   |
| Anker PowerConf C300                                | 2         | 0.94%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.94%   |
| Acer Integrated Camera                              | 2         | 0.94%   |
| Acer BisonCam,NB Pro                                | 2         | 0.94%   |
| Z-Star Webcam                                       | 1         | 0.47%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.47%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.47%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.47%   |
| Syntek EasyCamera                                   | 1         | 0.47%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.47%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.47%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.47%   |
| Sunplus Integrated Camera                           | 1         | 0.47%   |
| Sunplus ASUS Webcam                                 | 1         | 0.47%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.47%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.47%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.47%   |
| Realtek VGA WebCam                                  | 1         | 0.47%   |
| Realtek USB Camera                                  | 1         | 0.47%   |
| Realtek Integrated Webcam_HD                        | 1         | 0.47%   |
| Realtek HP Webcam-101                               | 1         | 0.47%   |
| Realtek HP Truevision HD                            | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 34.62%  |
| Validity Sensors           | 13        | 25%     |
| Shenzhen Goodix Technology | 11        | 21.15%  |
| Upek                       | 3         | 5.77%   |
| Elan Microelectronics      | 3         | 5.77%   |
| LighTuning Technology      | 2         | 3.85%   |
| STMicroelectronics         | 1         | 1.92%   |
| AuthenTec                  | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 15.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.54%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.77%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.77%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.77%   |
| Unknown                                                                    | 3         | 5.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.92%   |
| Validity Sensors VFS491                                                    | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.92%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.92%   |
| Synaptics  WBDI                                                            | 1         | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.92%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 66.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 146       | 62.13%  |
| 1     | 71        | 30.21%  |
| 2     | 16        | 6.81%   |
| 3     | 2         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 47.66%  |
| Graphics card            | 23        | 21.5%   |
| Net/wireless             | 11        | 10.28%  |
| Multimedia controller    | 6         | 5.61%   |
| Chipcard                 | 5         | 4.67%   |
| Card reader              | 3         | 2.8%    |
| Communication controller | 2         | 1.87%   |
| Camera                   | 2         | 1.87%   |
| Storage/ide              | 1         | 0.93%   |
| Storage                  | 1         | 0.93%   |
| Sound                    | 1         | 0.93%   |
| Modem                    | 1         | 0.93%   |

